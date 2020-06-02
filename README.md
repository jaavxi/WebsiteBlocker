# Website Blocker Using Python
This is real world program which blocks certain distracting website like Facebook, Youtube etc during your work hours.

**About the program:** What we are going to in this program is that we will pass the link of websites which you think is distracting and the time that you are working on your computer and program will block those website.

## Program Architecture:
1. Every system have host file whether it is Mac, Windows or Linux.

  Host file in Mac and Linux :
  
  `/etc/hosts`

  Host file in Windows:
  
  `C:\Windows\System32\drivers\etc`

2. Working of host file: Host is an operating system file which maps hostnames to IP addresses. In this program we will be mapping hostnames of websites to our localhost address. Using python file handling manipulation we will write the hostname in hosts.txt and remove the lines after your working hours.
