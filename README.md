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

<img width="940" height="609" alt="image" src="https://github.com/user-attachments/assets/5b59c966-84e5-4d57-9e24-48e936b8036d" />



### IP Lookup result:
<img width="940" height="455" alt="image" src="https://github.com/user-attachments/assets/50de1e71-ddfb-45d6-9f37-96ecedd65e0b" />


### History of the website :
<img width="940" height="535" alt="image" src="https://github.com/user-attachments/assets/25c22f90-badd-4891-a706-34be88f2f7eb" />

### whois :
<img width="636" height="505" alt="image" src="https://github.com/user-attachments/assets/a4318712-7fd0-43b6-949c-fd17d18c471c" />

### netcat :
<img width="645" height="336" alt="image" src="https://github.com/user-attachments/assets/3c17ed42-2e4f-4ba6-b8ba-345edaf1124d" />



### nmap :
<img width="644" height="193" alt="image" src="https://github.com/user-attachments/assets/995a8ec2-47a2-49e6-819c-5893a686b8c8" />



### whatweb :
<img width="625" height="386" alt="image" src="https://github.com/user-attachments/assets/cd66ac8a-a703-41fc-8551-ba39b1e6050a" />



### httprint :
<img width="705" height="840" alt="image" src="https://github.com/user-attachments/assets/8d342099-5a01-45a2-b79e-b6af587994c8" />


### TCP traceroute :
<img width="695" height="78" alt="image" src="https://github.com/user-attachments/assets/99780a2f-918b-4ad2-89c6-49e4eac9308e" />

### UDP traceroute :
<img width="693" height="532" alt="image" src="https://github.com/user-attachments/assets/ab1b6572-7700-4ae1-9e14-34a4a728ef94" />


### ICMP traceroute:
<img width="691" height="538" alt="image" src="https://github.com/user-attachments/assets/515ab07d-bf82-4522-8a77-bacc64b0abea" />



## RESULT:

The information gathering techniques tools/procedure were identified successfully.
