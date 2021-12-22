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


<img width="1415" alt="Screen Shot 2021-12-22 at 11 24 28" src="https://user-images.githubusercontent.com/89514322/147078034-3a1bd5b7-33a1-4952-8622-d6daf4d1cff7.png">
