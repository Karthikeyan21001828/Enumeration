# Enumeration
# Explore Google hacking and enumeration 
# AIM:
To use Google for gathering information and perform enumeration of targets
## STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode
### Step 2:
Investigate on the various Google hacking keywords and enumeration tools as follows:
### Step 3:
Open terminal and try execute some kali linux commands
## Pen Test Tools Categories:  
Following Categories of pen test tools are identified:
Information Gathering.
## Google Hacking:
Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
# OUTPUT:
![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/871744fe-d97c-4b38-9e88-e5e5d2efa1cb)
filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/13df1ea0-7fc1-42fe-9cd4-da59bd836460)





intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/19e18899-353e-4410-8ecb-bd4e042743ec)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/2f829b78-9e55-4949-a3a6-b2d274ee14f7)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.


![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/8919541c-ed27-4139-bf67-a8486f08d319)



link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/c742dc3f-1754-4c6b-a5dd-53c04aeda220)


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/e5a5226a-0798-4a63-99a3-6f3ca67510cc)

## DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/d87393fe-bfea-41d3-9c3e-45da4f8c713b)

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/e1034efb-de6d-4ded-bd6b-8a770af86195)










## Dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/29906077-8039-4cac-b76e-3803a7f49983)

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/6a01e60b-2376-465f-b94e-c827779f3079)

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/03ff33df-9ac5-4d1a-9b76-b11577a3414b)

select any username in the first column of the above file and check the same

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/fc664c66-2a05-4d07-9dc6-a3bc6fbc42b5)




## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/3e7c58f7-411b-4b5c-9c3e-f4d1342f774f)

  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

![image](https://github.com/Karthikeyan21001828/Enumeration/assets/93427303/04757986-5523-495e-8654-f3bada940a3e)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
