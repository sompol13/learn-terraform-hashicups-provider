## Perform CRUD Operations with Providers
In this tutorial, you will use a Terraform provider to interact with a fictional coffee-shop application called Hashicups. In the process, you will learn how providers map target APIs to Terraform in order to create, read, update, and delete resources.

![Uploading image.png…]()

### Initialize HashiCups locally
- `git clone https://github.com/hashicorp/learn-terraform-hashicups-provider && cd learn-terraform-hashicups-provider`
- `cd docker_compose && docker-compose up`
- `curl localhost:19090/health`

### Reference
https://learn.hashicorp.com/tutorials/terraform/provider-use
