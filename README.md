This repository contains the code samples to get the secret(s) created in AWS Secret Manager.

The code samples are in these programming languages:
- Go
- Python3

To run the codes, please trigger the .github/workflows/get-secret.yml file via workflow_dispatch.

Expected output in all the runs should be:

Secret: {"soon-secret-key":"soon-secret-value"}

![alt text](images/golang-output.png)

![alt text](images/python-output.png)

![alt text](images/aws-secret-manager.png)
