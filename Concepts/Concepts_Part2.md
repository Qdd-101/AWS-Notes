# AWS Basic Concepts Part2  

Basic concepts Part 2  
Include: CLI, 

- **CLI**  
  Run AWS services (such as launch S3 bucket, upload files, etc) by commands  
  Basic command type:  
  aws \<service\> \<operation\> \<parameters\>  

  • Install AWS CLI  
  Official AWS website: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html   
  Windows: install by msi  
  Mac: install by cmd  
  Self-check: **aws --version**  
  Example output: aws-cli/2.34.26 Python/3.14.3 Windows/11 exe/AMD64  

  • Configure AWS CLI  
    Match your AWS account with your local AWS CLI:  
    **aws configure**  
    
    Access key id and key:  
    Go to your AWS console account ->  
    user security credentials ->  
    Create new access keys (In industry, you'd better login and create keys as IAM users instead of root users)  
    Default region (example): us-east-1  
    Default format (example): json  

    Self-check:  
    **aws s3 ls**: It will output your S3 buckets information.  

    CLI reference book: https://docs.aws.amazon.com/cli/latest/
  
