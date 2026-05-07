# 📝 Bucket List Tracker - AWS Amplify Full-Stack App

A modern full-stack web application for tracking personal bucket list goals, powered by serverless infrastructure on AWS.

## 🚀 Project Overview
This project was built using **AWS Amplify Gen 2** and **React** (Vite). It showcases the implementation of a cloud-backed database, hosting, and full CRUD (Create, Read, Update, Delete) capabilities to manage a user's bucket list items seamlessly.

## 🏗️ Architecture & Technologies
- **Frontend**: React (Vite) + TypeScript for typed safety and high performance.
- **Database**: Amazon DynamoDB (a fully-managed NoSQL database).
- **Backend API**: AWS AppSync (GraphQL) acting as the bridge between React and DynamoDB.
- **CI/CD**: Auto-deployment pipeline connected directly to GitHub via the Amplify Console.
- **Infrastructure as Code (IaC)**: The entire backend structure is declared purely in code inside the `amplify` directory.

## 🛠️ Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/nirtituani/bucketlistapp.git](https://github.com/nirtituani/bucketlistapp.git)
   cd bucketlistapp