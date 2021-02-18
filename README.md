# VF
## Note to run.
-  install the AWS CLI and Configure it to use your credentials.
```
$ aws configure
AWS Access Key ID [None]: <YOUR_AWS_ACCESS_KEY_ID>
AWS Secret Access Key [None]: <YOUR_AWS_SECRET_ACCESS_KEY>
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

## Run Ansible
```
ansible-playbook main.yaml
```
## lets Run jenkins
```
kubectl get svc --namespace devops
```
```
kubectl get po -n devops
```
