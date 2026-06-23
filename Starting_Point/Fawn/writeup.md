##Fawn

#Box Information
- OS: Linux
- Difficulty: Very easy

##Enumerated ports with nmap scan
nmap -sV <target ip>
#Findings - Version info, Open ports, OS info and anonymous login is enabled.

#Exploitation
ftp <target ip>
username: anonymous 
no password 
Post login run ls to find flag.txt

##Successfully foudn flag

#Challenges I faced and learnings
- Didnt know how to login to ftp and that anonymous as username can be used
- tcp runs on port 21
