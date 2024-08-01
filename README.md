# devops-sample-app

## Overview

This is a sample application using Flask for the backend and Next.js for the frontend.

## Setup Instructions

### Backend

1. Navigate to the `server` directory:
    ```sh
    cd server
    ```

2. Create a virtual environment and activate it:
    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```sh
    python app.py
    or
    flask run
    ```

### Frontend

1. Navigate to the `client` directory:
    ```sh
    cd client
    ```

2. Install the required packages:
    ```sh
    npm install
    ```

3. Run the Next.js application:
    ```sh
    npm run dev
    ```

## Task for Candidates

1. **CI/CD Pipeline Setup**
   - Fork this repository.
   - Create a CI/CD pipeline using Azure DevOps.
   - Include automated testing in the pipeline.
   - Deploy the application to Azure App Services.

2. **Containerization**
   - Write Dockerfiles for both the Flask backend and the Next.js frontend.
   - Ensure both Docker containers run locally.

3. **Kubernetes Deployment on Azure**
   - Write Kubernetes manifests to deploy the Docker containers to a Kubernetes cluster.
   - Ensure the application is accessible through a Kubernetes service.

4. **Load Balancer**
   - Configure Nginx as a load balancer to distribute traffic.
     
5. **Bonus**
   - Implement basic logging for the application using ELK stack or Azure Monitor.

## Submission

1. **Code Repository:**
   - Host the project on a private GitHub repository forked from this sample application.
   - Provide a README.md file with instructions on how to set up and run the project locally.
   - Share access to the repository with jaymrp25@gmail.com.

2. **Video Demonstration:**
   - Record a video demonstrating the working of the CI/CD pipeline, Docker container, Kubernetes deployment on Azure, and load balancer setup.
   - The video should show:
     - The CI/CD pipeline in action, deploying the application.
     - Running the Docker containers locally.
     - Accessing the application through the Kubernetes service.
     - Nginx implementation.
   - Upload the video to Google Drive and provide the link in the README.md file.

## Evaluation Criteria
- Technical accuracy and functionality of the CI/CD pipeline, Docker containers, Kubernetes deployment, and load balancer setup.
- Attention to detail and adherence to best practices in DevOps.
