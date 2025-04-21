## NAME : vignesh raaj
# REG NO: 212223230239

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


## OUTPUT:
![WhatsApp Image 2025-03-17 at 13 29 26_c00de78b](https://github.com/user-attachments/assets/645fdfe3-db49-4fa2-9c10-9f800abe4f46)


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
ping saveetha.ac.in

## OUTPUT:
![WhatsApp Image 2025-03-17 at 13 30 19_0e0db657](https://github.com/user-attachments/assets/ec14eb58-355b-4eef-a129-e0fe2a130b2b)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT:
![image](https://github.com/user-attachments/assets/fd0fc526-50af-46b8-91c2-a0bea6d30b23)
## History of the website:
## OUTPUT:
![image](https://github.com/user-attachments/assets/458c1bf4-ad9d-4592-a378-2961a207d9cc)
## Webserver Fingerprinting:
## Netcat: nc 172.17.52.118 80
## OUTPUT:
![image](https://github.com/user-attachments/assets/c43a733d-340b-4b4f-88f8-52c07d81be6c)
## nmap:
## nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/db4562f3-d689-48a1-9326-dd3adc048630)
## Whatweb:
## whatweb infosys.com
## whatweb zoho.com
## whatweb -v -a 3 172.17.52.201
## OUTPUT:
![image](https://github.com/user-attachments/assets/e536d0dd-8f46-4332-bfb5-6174118d6639)
## httprint:
## httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT:
![image](https://github.com/user-attachments/assets/b3404407-2dfd-4dc4-8612-932e4edae5fc)
## Tracing the Location
## TCP Traceroute:
## sudo traceroute -T www.saveetha.ac.in
## OUTPUT:
![image](https://github.com/user-attachments/assets/7b171ef0-8f17-46d5-8f92-a234772396a0)
## UDP Traceroute:
## sudo traceroute -U www.saveetha.ac.in
## OUTPUT:
![image](https://github.com/user-attachments/assets/3e33d6f5-7cad-463a-9050-c66151b99482)
## ICMP Traceroute:
## sudo traceroute www.saveetha.ac.in
## OUTPUT:
![image](https://github.com/user-attachments/assets/f973d064-7ef4-472a-9a23-6d1b0353e648)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
