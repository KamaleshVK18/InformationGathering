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


### ping command :
<img width="773" height="331" alt="image" src="https://github.com/user-attachments/assets/12c65567-4274-4f9c-aa71-428b3c3fc214" />


### whois :
<img width="636" height="505" alt="image" src="https://github.com/user-attachments/assets/a4318712-7fd0-43b6-949c-fd17d18c471c" />



### netcat :
<img width="645" height="336" alt="image" src="https://github.com/user-attachments/assets/3c17ed42-2e4f-4ba6-b8ba-345edaf1124d" />



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
