# AWS_SageMaker_Project

## STEPS:

1. Create IAM User with Administrative Access.
2. AWS CLI Configure with Access and secrete Key
3. Start VS code studio and create new virtuakl environment awssegmaker

'''
conda create -p awssegmaker python=3.8
'''
Activate Environment:
'''
conda activate awssegmaker/
'''
### Install Requirments
'''
pip install -r requirements.txt
'''

### Create S3 bucket in AWS name : mobpricebucket

### Feature Engineering:
- Do some feature engineering and then split data into train test split and push that data to AWS s3 Bucket as sagemaker will use training data from aws s3