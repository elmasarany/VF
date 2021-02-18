# VF
## Note to run.
-  install the AWS CLI and Configure it to use your credentials.
```
$ aws configure
AWS Access Key ID [None]: <YOUR_AWS_ACCESS_KEY_ID>
AWS Secret Access Key [None]: <YOUR_AWS_SECRET_ACCESS_KEY>
Default region name [None]: <YOUR_AWS_REGION>
Default output format [None]: json
```
- terraform init
- terraform apply

## Configure kubectl and AWS IAM Authenticator.
- Then
```
- aws eks --region {region-id} update-kubeconfig --name {Cluster Name}
```
```
aws eks --region us-west-2 update-kubeconfig --name terraform-eks-demo
```
