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


## TESTED BY : MELKIN SAM.D
## REG NO : 212223220056
## OUTPUT:
![image](https://github.com/user-attachments/assets/3b3beb08-b1d8-4b2f-93e1-5026a71cab39)

## Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

## OUTPUT:
![image](https://github.com/user-attachments/assets/65ddf135-4483-4c08-a57b-3753e38df95f)

## Finding Hosting Company:
get further detail by using ip2location.com website.

## OUTPUT:
![image](https://github.com/user-attachments/assets/52a96bc1-8b53-49da-b356-7c4c587417df)

## HISTORY OF THE WEBSITE:
## OUTPUT:
![image](https://github.com/user-attachments/assets/6a22543c-b5b9-49a6-8f54-52341c617bfd)

## WEBSERVER FINGERPRINTING:
## NETCAT:
 ```nc 172.17.52.118 80```

 ## OUTPUT:
 ![image](https://github.com/user-attachments/assets/95763897-dc5b-46d0-b660-9e49bf392abc)

 ## NMAP:
 ```nmap -p 21 -sV --script=banner ftp.vim.org```

 ## OUTPUT:
 ![image](https://github.com/user-attachments/assets/f4476388-a851-49b5-8bda-4376e07fa971)

## Whatweb:

```whatweb infosys.com```

```whatweb zoho.com```

```whatweb -v -a 3 172.17.52.201```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f15f0f43-d4a9-4156-9356-5ca5f66dfbc7)

## httprint:
```httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more```
## OUTPUT:
![image](https://github.com/user-attachments/assets/f2a0443a-38aa-47ac-b10e-944cb0527805)

## TRACING THE LOCATION:

## TCP Traceroute:

```sudo traceroute -T www.saveetha.ac.in```

## OUTPUT:
![image](https://github.com/user-attachments/assets/dec80486-4b9b-41f5-a82b-dd9b773c9c35)

## UDP TRACEROUTE:
```sudo traceroute -U www.saveetha.ac.in```

## OUTPUT:
![image](https://github.com/user-attachments/assets/35a510f9-4d2a-4a53-863c-a93e9b1d5d2a)

## ICMP TRACEROUTE:
```sudo traceroute  www.saveetha.ac.in```
## OUTPUT:
![image](https://github.com/user-attachments/assets/d91d3933-5986-4bc7-b4de-35d7ebe0939d)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
