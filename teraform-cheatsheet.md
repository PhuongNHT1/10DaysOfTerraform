# <img src="img/teraform-cheatsheet_20230228225229.png" width=5%> Terraform Cheatsheet

## What is Terraform?
Terraform is an Infrastructure as Code tool, that help you `create` and `manage`
BOTH on-prem and cloud resources safely and efficiency.

The most notable feature (vs other IaC tool such as CloudFormation) is it is NOT limited to a single cloud provider.

Written in GO.

## How does Terrafrom work?
Terraform uses plugin call provider to interact with Cloud provider's API.
![workflow](https://developer.hashicorp.com/_next/image?url=https%3A%2F%2Fcontent.hashicorp.com%2Fapi%2Fassets%3Fproduct%3Dterraform%26version%3Drefs%252Fheads%252Fv1.3%26asset%3Dwebsite%252Fimg%252Fdocs%252Fintro-terraform-apis.png%26width%3D2048%26height%3D644&w=3840&q=75)



# P
- [Provider](cheatsheet/provider.md): plugin used to interact with cloud provider, service or infrastructure component.

# S
- [State file](): the file that stores current state of configuration and infrastructure.

# W
- [Workflow](): the core workflow consist of 3 stages
  - Write: define the configuration file
  - Plan (execution plan): review the changes
  - Apply: provision infrastructure
![](https://developer.hashicorp.com/_next/image?url=https%3A%2F%2Fcontent.hashicorp.com%2Fapi%2Fassets%3Fproduct%3Dterraform%26version%3Drefs%252Fheads%252Fv1.3%26asset%3Dwebsite%252Fimg%252Fdocs%252Fintro-terraform-workflow.png%26width%3D2038%26height%3D1773&w=3840&q=75)
