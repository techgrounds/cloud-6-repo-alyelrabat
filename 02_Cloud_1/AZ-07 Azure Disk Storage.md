# Azure Disk Storage
Azure Disk Storage kan gezien worden als een virtual hard drive in de cloud. Een disk kan een OS disk (waar het OS op staat) of een Data Disk (te vergelijken met een externe harde schijf) zijn. Je hebt een keuze tussen Managed Disks en Unmanaged Disks. Unmanaged Disks zijn goedkoper, maar je hebt er wel een Storage Account nodig (en je moet de disk dus zelf managen). Managed Data Disks kunnen gedeeld worden tussen meerdere VMs, maar dat is een relatief nieuwe feature en er zitten wat haken en ogen aan.

Backups van een Managed Disk kan je maken met Incremental Snapshots die alleen de aanpassingen sinds de laatste snapshot opslaan. Voor een Unmanaged Disk kan je alleen een ‘normale’ snapshot maken.

Er zijn 4 typen managed disks. Over het algemeen kan je zeggen dat meer performance zorgt voor hogere kosten:
bron: https://docs.microsoft.com/en-us/azure/virtual-machines/disks-types

## Key-terms

## Opdracht

### Start 2 Linux VMs. Zorgt dat je voor beide toegang hebt via SSH

<img width="1367" alt="Screen Shot 2021-12-20 at 14 27 19" src="https://user-images.githubusercontent.com/89514322/146774304-2b2dd97e-376a-4822-a666-20e65f067548.png">

<img width="1162" alt="Screen Shot 2021-12-20 at 14 23 58" src="https://user-images.githubusercontent.com/89514322/146773873-b04ea64b-9f3d-41c6-9985-c493fec6a600.png">

<img width="1149" alt="Screen Shot 2021-12-20 at 14 25 56" src="https://user-images.githubusercontent.com/89514322/146774079-d4da61c6-32db-4d1c-81d8-ff3ac3e8bf90.png">

### Maak een Azure Managed Disk aan en koppel deze aan beide VMs tegelijk.

<img width="1363" alt="Screen Shot 2021-12-20 at 14 31 00" src="https://user-images.githubusercontent.com/89514322/146774740-5a0ca1e3-bdd7-4347-b04e-dff59f7a7259.png">


### Creëer op je eerste machine een bestand en plaats deze op de Shared Disk.

### Kijk op de tweede machine of je het bestand kan lezen.

### Maak een snapshot van de schijf en probeer hier een nieuwe Disk mee te maken

### Mount deze nieuwe Disk en bekijk het bestand. 

### Gebruikte bronnen
https://help.ubuntu.com/community/InstallingANewHardDrive
https://superuser.com/questions/934678/fdisk-do-i-need-it-or-can-i-make-a-filesystem-directly
https://www.howtogeek.com/443342/how-to-use-the-mkfs-command-on-linux/
https://superuser.com/questions/676093/partition-not-showing-up-in-dev
https://docs.microsoft.com/en-us/azure/virtual-machines/disks-types
https://docs.microsoft.com/nl-nl/azure/virtual-machines/managed-disks-overview

### Ervaren problemen

<img width="1060" alt="Screen Shot 2021-12-20 at 15 52 19" src="https://user-images.githubusercontent.com/89514322/146876323-f7b33784-19aa-4ede-ac23-9c2923fb7660.png">
