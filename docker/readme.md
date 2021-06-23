# Creating Docker container with Terraform
#### requirement
- terraform cli
- running docker engine
   
#### Terraform
initiate provider   
$ terraform init   
Plan the terraform   
$ terraform plan -var "container_name=mynginx"      
Apply the terraform   
$ terraform apply -var "container_name=mynginx"  
Terraform inspect state    
$ terraform show   
```bash
$ docker ps
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                  NAMES
e339e6984b37        d1a364dc548d        "/docker-entrypoint.…"   10 hours ago        Up 10 hours         0.0.0.0:8000->80/tcp   tutorial
$ terraform state list
docker_container.nginx
docker_image.nginx
```


