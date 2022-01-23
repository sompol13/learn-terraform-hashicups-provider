## Perform CRUD Operations with Providers
In this tutorial, you will use a Terraform provider to interact with a fictional coffee-shop application called Hashicups. In the process, you will learn how providers map target APIs to Terraform in order to create, read, update, and delete resources.

![image](https://user-images.githubusercontent.com/33342822/150666827-8ab2bb8f-9600-4d98-99fe-5c357ff3ea02.png)

### Initialize HashiCups locally
- `git clone https://github.com/hashicorp/learn-terraform-hashicups-provider && cd learn-terraform-hashicups-provider`
- `cd docker_compose && docker-compose up`
- `curl localhost:19090/health`

### Reference
https://learn.hashicorp.com/tutorials/terraform/provider-use
