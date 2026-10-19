# AWS CloudFormation Deployments

Infrastructure as Code projects from my UMGC graduate coursework (CCA 625 Networking Engineering and CCA 640), deploying AWS resources from templates instead of manual console configuration.

## Projects

### CloudFormation Template Designer — VPC and Internet Gateway Stacks (CCA 625)
- Built a CloudFormation template in the AWS Template Designer, dragging and configuring **VPC** and **Internet Gateway** resources onto the template canvas
- Created **two stacks** from the template; both reached a healthy (green) state
- Worked through template validation and error messages during the design process

### LAMP Stack Deployment (CCA 640)
- Deployed the **CCA640LAMPStack** from the AWS LAMP single-instance sample template
- Parameterized the stack: MySQL database name, DB credentials (masked parameters), **t2.small** instance type, EC2 key pair (`cca640key`), and SSH access location
- The template used CloudFormation bootstrap scripts to install Apache, PHP, and MySQL at instance launch
- Reviewed stack options (tags, IAM role permissions, rollback configuration, notification options) before creation

## Skills demonstrated
- Infrastructure as Code (IaC) concepts and template-based provisioning
- AWS CloudFormation: Template Designer, stacks, parameters, stack options, creation lifecycle
- YAML/JSON template structure


---
*Shannon Javone Jenkins — MS in Cloud Computing Architecture, University of Maryland Global Campus (UMGC). Graduate coursework and hands-on labs.*
