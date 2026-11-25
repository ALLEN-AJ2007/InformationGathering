# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

<img width="948" height="1017" alt="Screenshot 2026-11-25 223538" src="https://github.com/user-attachments/assets/69135905-5b8c-440d-bb2f-3a47e72e8682" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output


<img width="806" height="655" alt="Screenshot 2026-11-25 223908" src="https://github.com/user-attachments/assets/ebfe776d-fa0e-4a92-b054-c4b5023c0d08" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="798" height="717" alt="Screenshot 2026-11-25 224033" src="https://github.com/user-attachments/assets/d97495ae-1bd0-4fb4-a30b-88a36caf8884" />


## History of the website:
## output
https://web.archive.org/

<img width="961" height="1022" alt="Screenshot 2026-11-25 224207" src="https://github.com/user-attachments/assets/7f38a06e-9ef4-4ff6-8c4a-5ce4cecde3df" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="877" height="740" alt="Screenshot 2026-11-25 224428" src="https://github.com/user-attachments/assets/a06a2cd2-ee1e-4ed9-933f-ad3befcf1cd1" />



## nmap:
###output

<img width="867" height="713" alt="Screenshot 2026-11-25 224717" src="https://github.com/user-attachments/assets/32797e15-9ee8-4986-8e0b-08dd5443a632" />


## Whatweb
### output

<img width="902" height="692" alt="Screenshot 2026-11-25 224832" src="https://github.com/user-attachments/assets/2a7d796e-df97-4654-a0d4-ac5c907b0c49" />


## httprint
### output


<img width="853" height="697" alt="Screenshot 2026-11-25 225044" src="https://github.com/user-attachments/assets/c1da1ebf-6396-4001-93b0-2cf56d6280f2" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

<img width="836" height="166" alt="Screenshot 2026-11-25 225234" src="https://github.com/user-attachments/assets/90199fbf-35e5-465b-aec4-df0f4f1b8d22" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output


<img width="930" height="745" alt="Screenshot 2026-11-25 225258" src="https://github.com/user-attachments/assets/7934d265-4003-459b-8700-bb08c0324f4c" />




## ICMP Traceroute:
sudo traceroute  www.google.com
## output



<img width="946" height="356" alt="Screenshot 2026-11-25 225313" src="https://github.com/user-attachments/assets/a37b7b35-8943-4b4a-b397-178a3b1c4e85" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
