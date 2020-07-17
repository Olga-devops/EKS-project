# EKS-project
Creates EKS with 2 nodes

To create EKS clone this code. Adjust the nessessary requirenments. Run `source setenv.sh configurations/us-east-1.tfvars` 
and than run `terraform apply -var-file=configurations/us-east-1.tfvars` 

It will create cluster in Virginia region. You can add more regions, just change the tfvars
