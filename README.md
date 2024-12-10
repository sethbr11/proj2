# PDCDonuts - Project 2

To run the project, enter the main folder and run `docker build -t proj2 .` followed by `docker run -dit -p 80:80 proj2`. To run the Terraform code, run `terraform init`, `terraform plan`, `terraform validate`, and `terraform apply`, then `terraform destroy` to delete your created resources. Automatic deployment can be done by running `./deployinfrastructure.sh` and subsequent destruction of those created resources is done with `./destroyinfrastructure.sh`. Some setup may be needed with installing docker, AWS CLI, terraform, etc, including IAM role creation.
