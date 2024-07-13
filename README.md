# Active Directory Setup


# Install VMs

* Using mostly defualt settings install windows 2022 server and windows 10 workstation

## Installing domain controller:
 1. Use `SCongig` to :
 	- Change the hostname
 	- Change the IP address to static
 	- Change the DNS server to our own IP adderss

 2. Install the Active directory Windows Feature

 ```shell
Install-WindowsFeature AD-Domain-Serverices -IncludeManagementTools
 ```
 