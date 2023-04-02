## IAM Role example in Terraform

In particular, this IAM role was designed to allow github actions to:

- Get a federated login for a specific github repository
- Allow pushing to a specific private repository in AWS ECR

Therefore, you also need to setup in AWS IAM console the corresponding __Identity provider__.