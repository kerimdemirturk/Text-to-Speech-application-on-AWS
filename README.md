# Text-to-Speech-application-on-AWS
Text to speech convert application by using Amazon pollly,S3,Lambda

I will developing the project with @hkeremk.In this project we are going to create a project in amazon polly.Project implementing converts text into audio files by using amazon polly.A user upload a text file into the s3 then we use s3 event notification for invoking a lambda function whenever a text file is uploaded.Lambda function calls the polly apı to provide text into a speech audio stream.Then polly process the request from lambda function and returns the audio file.Lambda function saves the audio file into the output folder of the s3 bucket.
![Project Chard](docs/assets/Screenshot%20from%202023-04-06%2016-33-43.png)

