# BD-Smart-Homes
Backup Files For HA
Configuration Instructions

Manual IP Address Configuration
For this version, the IP addresses must be added manually to the configuration file.

Steps
1.	Navigate to the system settings:
Settings → System → Network


2.	Locate Automatic IP for:
•	IPv4
•	IPv6

3.	Copy the required IP address(es).
4.	Open the configuration.yaml file.
5.	Paste the copied IP address(es) under the following path:
http:
  trusted_proxies:
    - <IP_ADDRESS>


6.	Save the file after updating.
⚠️ Ensure both IPv4 and IPv6 addresses are added if applicable.

User Profiles Note:

 	User profiles must be created manually.
	The master profile is named:
		Username: backoffice
		Password: *****

