# Face_Recognition
Fine-tune InceptionResnetV1 on CelebA Datase

Educational project in Deep Learning School.


• Fine-tune InceptionResnetV1 (pretrained on VGGFace2) on CelebA Dataset.

• Calculate cosine similarities between embeddings.

• Test data results: loss = 0.73, accuracy = 0.92.

• Implement the TPR@FPR metric. Measure with identification rate metric how good a model would work on unseen faces (which are not present in training, val & test sets).

• Implement a model and train it with TripletLoss and ArcFace loss. Compare the results with ordinary CE loss.

• Finding trash photo in dataset (whose embeddings norms are the highest)

![Alt text](img.png?raw=true "Result")
