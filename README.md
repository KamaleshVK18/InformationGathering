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

<img width="1919" height="1135" alt="image" src="https://github.com/user-attachments/assets/4cc485ff-1c92-4d20-bd33-ce1ccb902b44" />



### Finding Hosting Company :
<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/48cb5f70-bb4e-4fae-9072-06a36df95a3b" />


### History of the website :
<img width="1882" height="1126" alt="image" src="https://github.com/user-attachments/assets/241ceb61-691c-4757-b33a-d4aaf6992baa" />

### ping command :
<img width="773" height="331" alt="image" src="https://github.com/user-attachments/assets/12c65567-4274-4f9c-aa71-428b3c3fc214" />


### whois :
<img width="1919" height="1107" alt="image" src="https://github.com/user-attachments/assets/a1513a93-7233-4334-b018-2d8c6919ab90" />


### netcat :
<img width="1919" height="992" alt="image" src="https://github.com/user-attachments/assets/3de85b26-2047-45f9-a6d5-3034a47b059d" />


### nmap :
<img width="1918" height="486" alt="image" src="https://github.com/user-attachments/assets/f1ae0a08-fc14-49ca-9973-7fcc6e494603" />


### whatweb :
<img width="1919" height="136" alt="image" src="https://github.com/user-attachments/assets/f260708d-594d-4078-b947-44b38c53cb03" />


### httprint :
<img width="1917" height="850" alt="image" src="https://github.com/user-attachments/assets/7157122e-ce49-4b30-9ea7-858e5955163d" />

### TCP traceroute :
<img width="1915" height="102" alt="image" src="https://github.com/user-attachments/assets/1d0427d5-c2ef-4b86-acab-74a04a45c65f" />

### UDP traceroute :
<img width="1893" height="356" alt="image" src="https://github.com/user-attachments/assets/fef6d83f-88ca-4072-8ff7-1b34708d64da" />


## RESULT:

The information gathering techniques tools/procedure were identified successfully.
