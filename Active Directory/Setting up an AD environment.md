Need:
- Virtual Box
- [Windows Server 2019](https://info.microsoft.com/ww-landing-windows-server-2019.html)

Steps:
1. Create the virtual machine (Windows Server 2019)
	1. download Virtual Box
	2. download windows server 2019 iso
	3. add windows server 2019 as a new server via the iso
2. Configure the IP address and host name
	1. we need to configure our VM to have a static IP address and assign a host name
	2. assign it to any internal IP address
	3. an example:
		- Hostname: DC1
		- IP Address: 192.168.40.10
		- Subnet Mast: 255.255.255.0
		- Gateway: None
		- DNS: 192.168.40.10
3. Install AD
	1. Command to install the AD Domain services
		- Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
	2. Command to promote the server to a domain controller
		- Install-ADDSForest -DomainName "mylab.local" -CreateDnsDelegation:$false -DomainNetBiosName "mylab" -InstallDns:$true
4. Bulk import Users, Groups & OUs
	1. Bulk OUs (Orginizational Units)
		1. copy the scripts to c:/it in the domain controller
		2. run create_ous.ps1
	2. Bulk Groups
		1. run create_groups.ps1
	3. Bulk Users
		1. run create_users.ps1
5. Join computer to the domain
6. 
