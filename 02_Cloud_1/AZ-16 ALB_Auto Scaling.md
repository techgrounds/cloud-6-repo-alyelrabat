## Opdracht 1:

Load balancers perform many functions in addition to just splitting traffic across servers:

- HTTP reverse proxy

- Traffic and routing optimisation algorithms

- Image caching (reducing web server load)

- Content caching

- Compression

- Content switching and rewriting

- SSL encryption/decryption (further reducing server load)

- Single Sign-On (preventing users having to login when switched between servers)

- GEO (GSLB) and DNS Failover

- Cookie persistence

- HTTP/2 Proxy

- Web Application Firewall (WAF)

Maak een Virtual Machine Scale Set met de volgende vereisten:

Ubuntu Server 20.04 LTS - Gen1

Size: Standard_B1ls

Allowed inbound ports:

SSH (22)

HTTP (80)

OS Disk type: Standard SSD

Networking: defaults

Boot diagnostics zijn niet nodig

Custom data: 
	
  #!/bin/bash
sudo su
apt update
apt install apache2 -y
ufw allow 'Apache'
systemctl enable apache2
systemctl restart apache2
Initial Instance Count: 2

Scaling Policy: Custom

Aantal VMs: minimaal 1 en maximaal 4

Voeg een VM toe bij 75% CPU gebruik

Verwijder een VM bij 30% CPU gebruik


<img width="513" alt="Screen Shot 2021-12-22 at 21 06 05" src="https://user-images.githubusercontent.com/89514322/147149273-efb064da-a552-4aa2-9822-144584cf0996.png">

<img width="1435" alt="Screen Shot 2021-12-23 at 15 00 54" src="https://user-images.githubusercontent.com/89514322/147252992-5c072b3b-53e0-43a0-8dc8-36cf2f392dfc.png">

<img width="886" alt="Screen Shot 2021-12-23 at 14 51 00" src="https://user-images.githubusercontent.com/89514322/147253031-307f4f07-772c-4feb-b43b-b62892b0b4eb.png">
