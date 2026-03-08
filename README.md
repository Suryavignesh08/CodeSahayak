# CodeSahayak: Vernacular AI Coding Tutor

## 🚀 Project Overview
CodeSahayak is an AI-powered learning assistant designed for the AWS AI for Bharat Hackathon. It helps Indian students learn coding by explaining technical concepts and errors in native languages (Hindi, Tamil, Telugu, etc.) using culturally relevant analogies.

## 🛠 Tech Stack
- **AI/ML:** AWS Bedrock (Amazon Nova Pro)
- **Compute:** AWS Lambda (Serverless)
- **API:** Amazon API Gateway
- **Frontend:** Amazon Amplify

## 📂 Documentation
The following technical documents were generated using **Kiro**:
- [Requirements Specification](./requirements.md)
- [System Design Document](./design.md)

## 💡 How it Works
1. User highlights code or an error message.
2. The system triggers an AWS Lambda function.
3. AWS Bedrock processes the request and generates a "Hinglish" or native language explanation with a real-world analogy.
4. The explanation is displayed or read aloud to the user.
