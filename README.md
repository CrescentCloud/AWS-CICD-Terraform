# terraform-cicd

setting up CodeBuild job that seamlessly deploys Terraform configurations whenever there are new commits in GitHub repository. 

** Terraform will install WebApp in this project with necessary aws resources<br>
** S3 as Remote Backend 

#### Set Up IAM User: 
Create an IAM user with full access permissions.

#### GitHub Repository: 
Create and clone a GitHub repository for the project.

#### Local Testing: 
Test Terraform scripts locally to ensure they work as expected.

#### Shell Scripts: 
Develop shell scripts to automate deployment tasks.

#### Buildspec.yml: 
Create a buildspec.yml file to define build instructions for CodeBuild.

#### Access Token: 
Generate a personal access token for secure GitHub interactions.

#### Terraform State: 
Store Terraform state files in an S3 bucket for centralized management.

#### CodeBuild Project: 
Set up a CodeBuild project to build and deploy infrastructure.

#### Terraform Destroy: 
Configure CodeBuild to run Terraform destroy commands for cleanup.
