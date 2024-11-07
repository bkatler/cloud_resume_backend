# Cloud Resume Challenge - Backend

This repository contains the backend components for the **Cloud Resume Challenge**, including AWS Lambda functions and corresponding tests.

## Repository Structure
- **`lambda_function.py`**: The main Lambda function that powers the backend for the Cloud Resume Challenge.
- **`__init__.py`**: This file initializes the package structure for Python, enabling imports within the project.
- **`tests/`**: Contains all test files for the project.
  - **`test_cloud_resume_e2e.py`**: End-to-end tests for the cloud resume backend.
  - **`test_lambda_unit.py`**: Unit tests for the Lambda function.
  - **`test_visitor_counter_system.py`**: System tests for visitor counter functionality.

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bkatler/cloud_resume_backend/tree/main
   cd cloud_resume_backend

## Install dependencies:
- Install any dependencies listed in the `requirements.txt` (if applicable).
- Make sure to install the AWS CLI and configure it with your AWS credentials.

## Set up AWS Lambda Function:
- Deploy `lambda_function.py` to AWS Lambda.
- Configure necessary permissions for the Lambda function to interact with other AWS services like DynamoDB for visitor counting.

## Running Tests

To run the tests, navigate to the project directory and use a test runner like `pytest`:

```pytest tests/```

## Project Details

The backend function is designed to count and display the number of visitors to a resume hosted on the cloud. This is part of the Cloud Resume Challenge, where the backend interacts with AWS services to manage visitor data.
