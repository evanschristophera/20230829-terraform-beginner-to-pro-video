# [Complete Terraform Course - From BEGINNER to PRO! (Learn Infrastructure as Code)](https://youtu.be/7xngnjfIlK4)
## Important Parts
* [Remote Backend Setup](#aws-s3)
* [Remote Backend Azure](#azure)
## [Course Overview](https://youtu.be/7xngnjfIlK4?t=86)
- Uses AWS
- [Accompaning GIT Repository](https://github.com/sidpalas/devops-directive-terraform-course)
- [Ansible mentioned](https://youtu.be/7xngnjfIlK4?t=601)
  
  Better suited to "on prem"?
- 
## [Evoloution of IaC](https://youtu.be/7xngnjfIlK4?t=721)
- Declarative!
- Cloud agnostic
-   
## [Terraform Overview & Setup](https://youtu.be/7xngnjfIlK4?t=877)

- [Ansible is a configuration management tool](https://youtu.be/7xngnjfIlK4?t=992)
- [Packer made by terraform is a templating tool](https://youtu.be/7xngnjfIlK4?t=1040)
  - Can bundle the application code
- [Orchestration tool with Terraform - a good thing](https://youtu.be/7xngnjfIlK4?t=1082)
- [Terrafpr, Arcjotectire](https://youtu.be/7xngnjfIlK4?t=1131)
  - Providers are like plugins
## [DEMO](https://youtu.be/7xngnjfIlK4?t=1131)
= Installation
- [AWS User](https://youtu.be/7xngnjfIlK4?t=1306)
  - [Roles](https://youtu.be/7xngnjfIlK4?t=1330)
- AWS cli configuration is used by Terraform to authenticate to AWS
## [Part 3 - Basic Usage](https://youtu.be/7xngnjfIlK4?t=1717)
- Providers have modules.  More to follow, I hope.
- [init command](https://youtu.be/7xngnjfIlK4?t=1853)
  - Downloads provider(s)
  - [Modules are mentioned](https://youtu.be/7xngnjfIlK4?t=1951)
    - Modules directory
  - [State file](https://youtu.be/7xngnjfIlK4?t=1992)
  - There are data blocks to reference resources not managed by Terraform
  - [State file](https://youtu.be/7xngnjfIlK4?t=2087)
  - **Sensative values are in plain text by default**
- [Remote Backend](https://youtu.be/7xngnjfIlK4)
  - S3 can be used **need to look at Azure equivalent**
  - Automation is now possible
    - pipelines
- [Terraform plan](https://youtu.be/7xngnjfIlK4?t=2272)
  - Avoid making infrastructure changes outside of terraform
- [Terraform destroy](https://youtu.be/7xngnjfIlK4?t=2382)
- [Remote backend](https://youtu.be/7xngnjfIlK4?t=2413)
  - Terraform cloud
    - Free up to 5 users 
    - 20/user/month over 5
### [AWS S3](https://youtu.be/7xngnjfIlK4?t=2496)
    - DynamoDB is used for locking
    - Yes, this is necessary
    - [Bootstrapping process](https://youtu.be/7xngnjfIlK4?t=2546)
### [Azure](https://learn.microsoft.com/en-us/azure/developer/terraform/store-state-in-azure-storage?tabs=terraform)
## [Another Demo](https://youtu.be/7xngnjfIlK4?t=2715)
