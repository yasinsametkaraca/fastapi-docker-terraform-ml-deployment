# fastapi-docker-terraform-ml-deployment

This project uses Terraform to manage the deployment of a Docker container.

## How to Use

1. **Initialize Terraform:**
   ```bash
   terraform init
   
2. **terraform apply --auto-approve**
    ```bash
    terraform apply --auto-approve

3. **Check if the Docker container is running**
    ```bash
    docker ps
Access the Interface
After the deployment, you can access the interface at http://localhost:8002/docs