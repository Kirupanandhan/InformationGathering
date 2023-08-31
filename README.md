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
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/bfdff850-a1a9-47fe-bd0e-07db6dcd40a5)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/40a3568b-791a-42fb-b636-2573848749fe)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/b1e8d8f2-877e-4e4e-8fe1-86c21c7b1a8d)

## History of the wbsite:
## Output:
https://web.archive.org/
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/46565d8d-0c54-4f40-8350-dace155f34e7)

## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/3b8b5348-9eb5-4966-a383-22c5e1230b7e)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/79f8109d-64fe-4df4-b4d0-00d407ff38a0)

## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/9d17b3c6-1adf-4ef3-b31d-37a0eb1e6dd9)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/1472a31d-cca5-448f-ab92-ddb71cf8abdf)

## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/de3de44a-92d9-4694-864f-6514e88a815e)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/1d4af69f-f89e-43b0-a9ec-aa9aaf8dce2e)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![image](https://github.com/Kirupanandhan/InformationGathering/assets/94386222/582339ef-4bb5-4477-9cef-057ba1e95059)





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
