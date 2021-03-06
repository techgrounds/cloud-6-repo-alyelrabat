# Azure Virtual Machines 
De Service waarmee je VMs kan maken in Azure heet (zeer toepasselijk) Azure Virtual Machines. Je kan deze VMs gebruiken voor alles waar je een fysieke server voor zou gebruiken. Omdat ze in een datacenter van Microsoft staan, kan je er alleen verbinding mee maken via het internet. Verbinding met een remote Linux-machine maak je met het Secure Shell (ssh) protocol. Voor een verbinding met Windows machines gebruik je het Remote Desktop Protocol (RDP).
Om een VM aan te maken moet je een image selecteren. Een image is een soort blauwdruk voor je machine. Het bevat onder andere een template voor het OS.
VMs komen in verschillende sizes. Elke size heeft een andere hoeveelheid vCPUs, RAM, Data disks, Max IOPS, Temp storage, Premium disk support en prijs.
Voor de OS disk (de root volume) kan je kiezen uit Premium SSD, Standard SSD en Standard HDD. Je hebt ook de optie om extra Data disks toe te voegen.
Je kan optioneel je VM beveiligen met een NIC network security group. Het wordt aangeraden om network security groups te configureren op subnet niveau (en dus niet op instance niveau) waar mogelijk, maar soms heb je een allow/deny rule nodig op een specifieke instance, dus de optie is er. In elk geval kan je firewalls dus buiten de instance regelen, en hoef je niet binnen de VM nog een extra firewall te configureren.
Met Custom Data kan je een cloud-init script, config file of andere data meegeven tijdens het opstarten van de VM. Hiermee kan je automatisch servers configureren zonder zelf in te loggen.
User data is een nieuwe versie van Custom data. Het grootste verschil is dat user data beschikbaar blijft gedurende de hele levensduur van de VM.
De prijs van een Azure VM hangt af van de size, de image, de regio waar hij in staat, het aantal minuten dat hij aan staat, en het type betaling dat je doet.
Pay-as-you-go is de duurste optie, maar ook het meest flexibel.
Reserved Instances zijn goedkoper, maar je zit vast aan een reservatie van 1 of 3 jaar.
Spot instances zijn over het algemeen het goedkoopst, maar de availability hangt af van de vraag naar VMs op dat moment, dus ze zijn niet altijd betrouwbaar.

## Key-terms [Schrijf hier een lijst met belangrijke termen met eventueel een korte uitleg.]

Resource Group

Inbound Ports (public /private)

SSH 22

HTTP 80

key.pem

### Gebruikte bronnen 

Quickstart: Create a Linux virtual machine in the Azure portal https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal

Create a Linux virtual machine in Azure https://docs.microsoft.com/en-us/learn/modules/create-linux-virtual-machine-in-azure/

### Resultaat

<img width="1440" alt="Screen Shot 2021-12-16 at 10 50 55" src="https://user-images.githubusercontent.com/89514322/146349434-60841eae-0d19-4d44-8ce3-cf5a5a7fa71a.png">

<img width="1431" alt="Screen Shot 2021-12-16 at 14 11 37" src="https://user-images.githubusercontent.com/89514322/146378175-6055c637-edc7-4720-9831-f69bfc874eb2.png">

<img width="516" alt="Screen Shot 2021-12-16 at 14 53 19" src="https://user-images.githubusercontent.com/89514322/146389031-68f41b4e-4c37-49ce-a72d-9595565908c2.png">
