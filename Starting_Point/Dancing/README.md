##Dancing

#Box Information
OS: Windows 
Difficulty: Very easy

##Nmap enumerations
#All opens ports
- port 135- msrpc
- port 139-netbios-ssn
- port 445- microsoft-ds
- port 5985- http - Trying broser login with target IP(didnt help)

#port 445= SMB port

##smbclient enumeration
- 4 services with only Workshares not needing a passowrd 
- Flag successfully found

##Learning
- smbclient -L <target IP>- lists SMB services
- To use/access services use: smbclient \\\\<Target IP>\\Service
