# Cloud-Based Image Classification System for Handwritten Text

## Overview
This project focuses on developing a cloud-based image classification system to convert handwritten Cyrillic text into digital formats. Leveraging AWS services, the system addresses the challenge of digital translation for non-Latin scripts, particularly in contexts such as historical document digitization, processing handwritten forms, or translating literary works in native scripts.

## Project Documents

### 1. **Final Project Proposal (PPTX)**
   - **Description**: This presentation outlines the initial proposal for the project, including the business problem, data procurement strategy, system design, and the planned responsibilities for each team member. It serves as the foundational blueprint for the project.
   - **[View the Proposal](https://github.com/shijianfei1413/Cloud-Based-Image-Classification-System-for-Handwritten-Text/blob/ba2b9a855ce2cb6a097fb0f575b6815d27f0e09b/Final%20Project%20Proposal.pptx)**

### 2. **Final Project Powerpoints (PPTX)**
   - **Description**: This PowerPoint presentation provides a detailed overview of the project's execution, including system design, data storage, model training, deployment, and recommendations for future improvements. It offers a comprehensive look at the project’s lifecycle and outcomes.
   - **[View the Presentation](https://github.com/shijianfei1413/Cloud-Based-Image-Classification-System-for-Handwritten-Text/blob/fd66b8eaf8efcd1f86dec5b0025ee4fb30d47301/Final%20Project%20Powerpoints.pptx)**

### 3. **Final Project Report (PDF)**
   - **Description**: The final report offers an in-depth analysis of the project, covering the business case, data procurement, cloud architecture, security features, and cost analysis. It includes detailed descriptions of the AWS services used, the implementation process, and the results achieved.
   - **[Read the Full Report](https://github.com/shijianfei1413/Cloud-Based-Image-Classification-System-for-Handwritten-Text/blob/33d27c4b2615227257179ef5b2dce2fe96de8bc1/Final%20Project%20Report.pdf)**

## Key Components

### Data Source
- **Cyrillic Handwriting Dataset**: The primary dataset used in this project was retrieved from Kaggle and includes over 73,000 segments of handwritten Russian texts. The dataset was used to train and evaluate the image classification model.

### System Architecture
- **AWS S3**: Used for storing training and test data, as well as the trained model weights.
- **AWS SageMaker**: Employed for model training, evaluation, and deployment. The project utilized a pre-trained model for efficiency.
- **AWS Lambda**: Developed a Lambda function to handle HTTP requests and invoke the SageMaker endpoint for image classification.
- **Amazon API Gateway**: Implemented to manage API requests and interact with the Lambda function and SageMaker endpoint.

### Security & Cost Optimization
- **Security**: Implemented VPC, Load Balancer, and Network ACLs to ensure secure access and protect against unauthorized access and attacks.
- **Cost Optimization**: Leveraged AWS services like Lambda’s pay-as-you-go model and S3’s scalable storage to minimize operational expenses.

## Future Extensions
- Consider deploying the system across multiple availability zones for enhanced reliability and fault tolerance.
- Explore the use of user input to further train and improve the model over time, with the potential to integrate automated retraining pipelines.

## Authors
Madison Raasch, Jianfei Shi, Fei Wu

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
