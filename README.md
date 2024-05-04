CloudFormation Templates (YAML and JSON) TO CREATE Active Directory, Certificate Authority, ADFS and other resources:

Files:

    CFN-Template-NewVPC-DomainControllersEC2-CA-ADFS.v4.8.json
    
    CFN-Template-NewVPC-DomainControllersEC2-CA-ADFS.v4.8.yaml

Resources:

	02 EC2 Instances as Domain Controllers
	01 EC2 Instance as Remote Desktop
	02 EC2 Instances as Standalone Root CA and Enterprise Subordinate CA
	01 AD Connector
	01 EC2 Instance as ADFS Server
	01 IAM Identity Provider
	04 IAM Roles (02 for EC2 instances, 02 for users authenticated via ADFS)
	01 VPC with 8 subnets distributed in two AZs of your choice
	02 NAT Gateways01 Internet Gateway 
	01 AppStream Stack and Fleet
	01 FSx
	01 Workspace for the Administrator and 01 Workspace for each user imported to AD depending of the parameters chosen
	01 Workmail Organization

	Time estimated to launch the stack: between 30 min - 1h 20min (depending on the resources you selected to launch).

Files: 

    CFN-Template-NewVPC-ManagedAD-CA-ADFS.v4.8.json
    
    CFN-Template-NewVPC-ManagedAD-CA-ADFS.v4.8

Resources:

	01 Managed AD
	01 EC2 Instance as Remote Desktop
	02 EC2 Instances as Standalone Root CA and Enterprise Subordinate CA
	01 EC2 Instance as ADFS Server
	01 IAM Identity Provider
	04 IAM Roles (02 for EC2 instances, 02 for users authenticated via ADFS)
	01 VPC with 8 subnets distributed in two AZs of your choice
	02 NAT Gateways
	01 Internet Gateway 
	01 AppStream Stack and Fleet
	01 FSx
	01 Workspace for the Administrator and 01 Workspace for each user imported to AD depending of the parameters chosen
	01 Workmail Organization
	01 Linux Domain Joined Instance (Microsoft AD)

	Time estimated to launch the stack: between 30 min - 1h 20min (depending on the resources you selected to launch).

