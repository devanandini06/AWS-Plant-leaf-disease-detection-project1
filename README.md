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
![Screenshot (602)](https://user-images.githubusercontent.com/90968558/232210506-e4c79bac-b681-4712-91a9-bc29d2e3d431.png)

1 For S3 folder location, enter the S3 bucket path.

2 For automatic labeling, select Automatically attach a label to my images based on the folder they’re stored in.
![Screenshot 2023-04-12 000702](https://user-images.githubusercontent.com/90968558/232210556-f2c95eac-2996-4b6d-a44c-ea751828e10d.png)
![Screenshot 2023-04-12 001021](https://user-images.githubusercontent.com/90968558/232210561-18835ad5-cfa0-4668-9333-85a4b63b72ee.png)





