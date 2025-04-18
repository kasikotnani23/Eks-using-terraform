# EKS-Terraform

to execute the teffarom files 
the server should have terraform, awscli, eksctl, and kubectl so we have to install these first 
then only we have to perform the terraform commands like 
terraform init
terraform plan
terraform apply -auto-approve
finnaly after the work is completed need to destroy the source
terraform destroy -auto-approve

after the cluster is created we have to set up the kubeconfig file which is we have to use the below command 

aws eks --region ap-south-1 update-kubeconfig --name eks-cluster
