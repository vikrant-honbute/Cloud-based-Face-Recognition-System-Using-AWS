# Cloud-based-Face-Recognition-System-Using-AWS
Cloud-based Face Recognition System Using AWS This project implements a cloud-based face recognition system using AWS services. Key components include:  Amazon Rekognition for face detection and recognition. Amazon S3 for secure image storage. AWS Lambda for serverless computations. Amazon DynamoDB for metadata management.

 DEMO video- https://github.com/user-attachments/assets/48eca402-f6db-4bf4-a2bb-21c19904c7c5
---

## Features  
- **Face Recognition**: Utilizes **Amazon Rekognition** for detecting and matching faces.  
- **Secure Storage**: Stores images in **Amazon S3** with robust access control.  
- **Serverless Architecture**: Processes data using **AWS Lambda**, reducing infrastructure management.  
- **Metadata Management**: Efficiently organizes and retrieves metadata using **Amazon DynamoDB**.  

---

## Technologies Used  
- **Amazon Rekognition**  
- **Amazon S3**  
- **AWS Lambda**  
- **Amazon DynamoDB**  

---

## System Workflow  
1. **Image Upload**: Images are uploaded to an S3 bucket.  
2. **Face Detection**: AWS Rekognition detects and analyzes faces from the uploaded images.  
3. **Data Processing**: Lambda functions handle processing tasks and trigger necessary operations.  
4. **Metadata Storage**: Results and metadata are stored in DynamoDB for querying.  

---

## Setup Instructions  
### Prerequisites  
- AWS account with access to Rekognition, S3, Lambda, and DynamoDB.  
- AWS CLI installed and configured with proper credentials.  
- Node.js or Python installed for writing Lambda functions.  

### Steps  
1. **Create an S3 Bucket** for storing images.  
2. Set up **Amazon Rekognition** for face detection and matching.  
3. Deploy **AWS Lambda functions** to handle image processing and trigger Rekognition.  
4. Configure **DynamoDB** to store metadata (e.g., face IDs, labels).  
5. Integrate all components into the workflow using AWS Management Console or the CLI.  

---

## Future Work  
- Conduct testing and evaluate the system’s performance with real-world datasets.  
- Add features like live video recognition or API integrations.  
- Implement detailed logging and monitoring using AWS CloudWatch.  

---

## Note  
Testing has not been conducted for this system. The current implementation demonstrates the design and architecture for a functional face recognition system.  

---

## License  
This project is open-source and available under the [MIT License](LICENSE).  
