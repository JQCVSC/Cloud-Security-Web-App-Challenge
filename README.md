# Cloud Security Web App Challenge: Secure-Pass-Sentinel

## Project Overview
This cloud challenge focuses on enhancing and deploying "Secure-Pass-Sentinel", a password strength checker web application, using serverless cloud technologies. Participants will improve the existing application and deploy it on either Google Cloud Platform (GCP) using Cloud Run or Amazon Web Services (AWS) using Lambda and API Gateway.

## Challenge Objective 🎯
Enhance the Secure-Pass-Sentinel application and deploy it as a serverless web app using either Google Cloud Platform (GCP) or Amazon Web Services (AWS). The goal is to improve functionality, security, and performance of the web app while ensuring it's correctly deployed and functioning in a serverless cloud environment.

## Key Requirements
1. **Enhance/Modify the App**: Make significant improvements or add new features to the provided password strength checker.
2. **Cloud Deployment**: Deploy the modified app using the services outlined below for either GCP or AWS.
3. **CI/CD Integration**: Integrate GitHub Actions (or similar tool) to automatically deploy updates to your cloud environment when you push to your repository.

## Cloud Provider Requirements
### GCP Requirements:
- **Compute Engine** or **Cloud Run**: Host the web application.
- **Cloud Storage**: Store the common_passwords.txt file (if needed).
- **IAM**: Set up appropriate roles and permissions.
- **Cloud Build**: Integrate for CI/CD.

### AWS Requirements:
- **EC2** or **Lambda**: Host the web application.
- **S3**: Store the common_passwords.txt file (if needed).
- **IAM**: Set up appropriate roles and permissions.
- **CodePipeline**: Integrate for CI/CD.

# Getting Started 🚀

### Step 1: Clone the Repository

git clone https://github.com/your-username/Secure-Pass-Sentinel.git
cd Secure-Pass-Sentinel

### Step 2: Set Up Locally
pip install -r requirements.txt
python main.py

### Step 3: Implement Enhancements
Enhance the web app. For example:

Improve the user interface
Add password generation functionality
Implement password history checking

### Step 4: Deploy to the Cloud
Choose either GCP or AWS for deployment.
GCP Deployment:

Compute Engine VM:
gcloud compute ssh your-vm-instance
git clone https://github.com/your-username/Secure-Pass-Sentinel.git
cd Secure-Pass-Sentinel
pip install -r requirements.txt
python main.py

Cloud Run: Use the provided cloudbuild.yaml file to deploy to Cloud Run.

## AWS Deployment:

EC2 Instance:
ssh ec2-user@your-ec2-instance
git clone https://github.com/your-username/Secure-Pass-Sentinel.git
cd Secure-Pass-Sentinel
pip install -r requirements.txt
python main.py

Lambda Function: Package the app as a Lambda function and set up an API Gateway.

### Step 5: Set Up CI/CD
Integrate GitHub Actions for automatic deployment. Refer to GitHub Actions documentation for setup.
Project Structure

main.py: The main Flask application file containing the password checking logic.
requirements.txt: List of Python dependencies.
cloudbuild.yaml: Configuration file for Google Cloud Build (for GCP deployment only).
common_passwords.txt: A list of common passwords to check against (ensure this file is in the same directory as main.py).

Submission/Showcase 📥

Create a pull request to this repository.
Add your name, GitHub repo URL, and deployed app URL to the submissions.md file.
Provide a summary of your enhancements and any additional features in your pull request.

Acknowledgements 👏
Thank you for participating! We look forward to seeing your innovative enhancements and deployments of the Secure-Pass-Sentinel project.
