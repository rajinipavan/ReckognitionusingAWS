# ReckognitionusingAWS
This code is used to detect the object present in the image using AWS REKOGNITION AI Service
To make this code WORK you need to follow the following steps:
1) An Active AWS Account usually AWS REKOGNITION service is not free we need set up AWS Rekognition by providing the credit card details.
2) We need to get the ACCESS_KEY and SECRET_ACCESS_KEY from the AWS Console
3) We need to set up these KEYS as enviromental variables
4) Download the AWS Rekgnition API by going into the AWS Console and selecting the Service 
5) Once selected the service drag and drop the install button into eclipse/Springsuitetool
6) This step conpletes the AWS Setup with Eclipse
7) Now we got the AWS API inside our Eclipse and are free to use the AAWS Services.
8) The next step is to upload the images in the S3 Bucket
9) We can upload the image manually or we can use the raspberry pi and IOT to capture the image and send it to S3 Bucket
10)We got the images and the AWS Rekognition Service is up and running.
11)Now we need to understand the various classes and aspects in the code and write the code in an editor.
12)The code contains some predefined classes given by AWS API
13)The output will be in the plain format and will be displayed in the console.
14)The output will contain :
                              a)Name of the Object
                              b)The Confidence Number of the Object prediction
Note:
Confidence Number is the Number provided by AWS Rekognition to state with how much of confidence the object predicted by AWS is correct.
