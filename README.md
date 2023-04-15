# AWS-Plant-leaf-disease-detection-project1
PLANT DISEASE DETECTION
To detect crop disease through image analysis with Amazon Rekognition.


What is Amazon Rekognition used for?
Amazon Rekognition can detect objects, scenes, landmarks, faces, celebrities, text, and inappropriate content in videos. You can also search for faces appearing in a video using your own repository or collection of face images.

Services Used:
-S3 Bucket
-custom labels in rekognition
-IAM
-Lambda
-DynamoDB

Solution overview:
We create a custom model to detect the plant leaf disease. To create our custom model, we follow these steps:
Create a project in Amazon Rekognition Custom Labels.
Create a dataset with images containing multiple types of plant leaf diseases.
Train the model and evaluate the performance.
Test the new custom model using the automatically generated API endpoint.

