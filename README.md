# github-action-aws-ec2-terraform-jenkins
Deployment of Aws ec2 infrastructure with terraform using github-actions to  automate the cicd process workflow and on top of the ec2 instance we install jenkins

#### Project overview

1.Github: Through the infrastructure.yml file script we are able to build and automate terraform on aws GUI while deploying jenkings on the ec2 instance.

2.Github Configuration: We are using the code to gihub so it makes sense if other activities will be halppening on the gihub self hosted runner. We can specify which operating system we are connecting to in aws if its ubuntun, amazon etc

3.Jenkins - installed jenkins on the server

4.Automate terraform deployment by setting up workflow that enables pull request.

#### Prerequisites:

Before starting the project, ensure you have the following prerequisites:

-An AWS account with the necessary permissions to create resources.

-AWS CLI installed on your local machine.

-Basic familiarity with Terraform and DevOps principles.

-Vscode - code editor installed locally on your machine.

- GitHub - a repository for your project code

https://github.com/Seun07/github-action-aws-ec2-terraform-jenkins.git


### Project Workflow
============
#### STAGE 1
==============
#### step 1: httpd application

#### creating the .github/workflows/infrastructure.yml
#### I have to first create the 
github folder 
workflows folder
infrastructure.yml file


<img width="1440" height="900" alt="Image" src="https://github.com/user-attachments/assets/38c0e100-3623-46d8-aaaf-56784fd80c92" />

#### push the code to github to trigger github actions

<img width="1440" height="900" alt="Image" src="https://github.com/user-attachments/assets/bd96f227-a8ca-4d5b-bdcf-d309b4792e4d" />

<img width="1440" height="900" alt="Image" src="https://github.com/user-attachments/assets/f1b637d9-e835-46af-a934-93967986f8a5" />

## final output of jenkins created on the ec2 instance server

<img width="1440" height="900" alt="Image" src="https://github.com/user-attachments/assets/392ef4f9-840f-47ad-8eb1-7840cc20d630" />