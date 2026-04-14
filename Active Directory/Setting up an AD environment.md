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
	- 
