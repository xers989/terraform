# Creating OCI VCN with Terraform
## Authentication
#### requirement
- terraform cli
- oci cli
   
$ oci session authenticate   
login to the cloud and then authentication session is created.   
The expiration time is 1 hour.   
You can extend the expiration with refresh command in oci   
$ oci session refresh --profile ***   

#### Terraform
Terraform apply   
change profile name and compartment_id    
   
initiate provider   
$ terraform init   
Plan the terraform   
$ terraform plan   
Apply the terraform   
$ terraform apply   
