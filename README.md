# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois


<img width="1015" height="441" alt="image" src="https://github.com/user-attachments/assets/e2e0705c-4767-42b9-8929-e0576f77af15" />

<img width="1021" height="512" alt="image" src="https://github.com/user-attachments/assets/b33d6435-9f07-4ecd-9249-d720686bddc2" />



### Finding Hosting Company :
<img width="1057" height="770" alt="image" src="https://github.com/user-attachments/assets/dfb49d4b-97ac-4f89-a815-6b977cf0a74d" />



### History of the website :

<img width="1889" height="904" alt="image" src="https://github.com/user-attachments/assets/6406bb24-6593-4dc7-b052-3a5d055024f8" />

### ping command :
<img width="984" height="427" alt="image" src="https://github.com/user-attachments/assets/a2752daf-5623-4805-9bda-a5323671b70b" />


### whois :
<img width="487" height="841" alt="image" src="https://github.com/user-attachments/assets/f3389641-7f86-4d97-ba33-7631c9262392" />


<img width="476" height="407" alt="image" src="https://github.com/user-attachments/assets/5c1e73fe-f90f-4c40-87ea-0654a53fc2df" />



### netcat :


<img width="1436" height="762" alt="image" src="https://github.com/user-attachments/assets/a45ee0e2-7590-43ab-ba2a-2747e3002f97" />

### nmap :

<img width="1060" height="343" alt="image" src="https://github.com/user-attachments/assets/aacb5f5d-df01-4b2b-8bf5-cb0e91116626" />


### whatweb :

![WhatsApp Image 2025-08-28 at 19 56 53_0a67f2bd](https://github.com/user-attachments/assets/aa809105-5eeb-402e-b4cc-fc41dab50477)


### httprint :

<img width="1090" height="729" alt="image" src="https://github.com/user-attachments/assets/672554dd-8162-4db5-9ff2-86498348f3d3" />


### TCP traceroute :

![WhatsApp Image 2025-08-28 at 09 28 12_8695ff5f](https://github.com/user-attachments/assets/739e84b0-e291-40fe-b8c5-a5fd5b7abfb1)


### UDP traceroute :

![WhatsApp Image 2025-08-28 at 09 29 08_136e5967](https://github.com/user-attachments/assets/da7ba03a-8c4f-47ba-b3e9-ed1780c0c5fd)



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
