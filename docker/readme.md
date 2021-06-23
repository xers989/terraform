# Creating Docker container with Terraform
#### requirement
- terraform cli
- running docker engine
   
#### Terraform
initiate provider   
$ terraform init   
Plan the terraform   
$ terraform plan   
Apply the terraform   
$ terraform apply   
$ docker ps
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                  NAMES
e339e6984b37        d1a364dc548d        "/docker-entrypoint.…"   10 hours ago        Up 10 hours         0.0.0.0:8000->80/tcp   tutorial