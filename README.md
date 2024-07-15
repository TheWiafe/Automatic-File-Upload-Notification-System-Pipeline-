# How To Create An Automatic File Upload Notification System (Pipeline)

![System Architecture](https://github.com/TheWiafe/Automatic-File-Upload-Notification-System-Pipeline-/blob/main/System%20Architecture.png)

## Problem Statement

The problem/pain this project aims to solve is the need to automate notifications for new files uploaded to an Amazon Simple Storage Service (S3) bucket. Specifically, the project creates a solution that:

1. Monitors an S3 bucket for new file uploads.
2. Triggers a Lambda function to process the uploaded files.
3. Sends a notification via mail using Amazon Simple Notification Service (SNS).
4. Stores metadata about the processed files in an Amazon Simple Queue Service (SQS) for further downstream processing. 

This project therefore provides seamless integration between various AWS services such as Amazon S3, Lambda, SNS, CloudWatch and SQS.

Ready to take your cloud storage management to the next level? Kindly click on this [link](https://medium.com/@wiafeemmanuel600/how-to-create-an-automatic-file-upload-notification-system-pipeline-cef4033bfa6c) to view the full project details in my blog.  

## Contributing
Users can contribute to the project by reporting issues, submitting bug fixes, or adding new features. To contribute:

Fork the repository
1. Create a new branch (git checkout -b feature/your-feature)
2. Commit your changes (git commit -am 'Add some feature')
3. Push to the branch (git push origin feature/your-feature)
4. Create a new Pull Request

## Contact
For questions or to get in touch, please contact:

- Email: wiafeemmanuel600@gmail.com
- LinkedIn: https://www.linkedin.com/in/emmanuel-wiafe-6710a618b/
