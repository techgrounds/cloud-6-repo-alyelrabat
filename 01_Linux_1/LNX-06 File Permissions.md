# File permissions (Toegangsrechten)

## Introductie

Op een groot deel van de webservers draait het Unix-achtige besturingssysteem Linux. 
Alle Unix-derivaten hebben gemeen dat aan bestanden en mappen bepaalde toegangsrechten worden toegekend 'rwx'. 
Je kunt die in Linux wijzigen met ‘chmod’ (change mode), een command-line-programma dat in de terminal via het gelijknamige commando geactiveerd wordt.
reading, writing, and executing files (rwx). 
n Unix en Linux heeft elk bestand op een server individuele toegangsrechten. Hetzelfde geldt voor directories. 
De toegangsrechten worden geregeld volgens drie klassen van gebruikers:

- (user) Eigenaar : een gebruiker die een bestand aanmaakt in Unix wordt gewoonlijk automatisch gedefinieerd als de ‘user’ van het bestand. 
Het eigendom kan later worden gewijzigd door het commando ‘chown’. In de symbolische notatie krijgt de gebruikersklasse ‘user’ de letter ‘u’.

- (group) Groep : de gebruikersklasse ‘group’ omvat verschillende gebruikersaccounts op de server. 
In Unix-bestandssystemen wordt elk gebruikersaccount automatisch toegewezen aan een hoofdgroep. 
Lidmaatschap in andere groepen is ook mogelijk. Zowel de eigenaar als de rootgebruiker kan bestanden groeperen met behulp van het ‘chgrp’ commando. 
De gebruikersklasse ‘groep’ wordt in de symbolische notatie met de letter ‘g’ weergegeven.

- (others) Andere : deze gebruikersklasse omvat alle gebruikers die geen user zijn van het bestand en ook niet bij een groep horen. 
Deze gebruikersklasse heeft de symbolische notatie ‘o’.

Heeft een opdracht betrekking op alle gebruikersklassen (user, group en others)? Dan is in de symbolische notatie hiervoor de afkorting ‘a’ beschikbaar, voor ‘all’.


## Requirements

Your CentOS VM

## Exercise

Create a text file.
Make a long listing to view the file’s permissions. Who is the file’s owner and group? What kind of permissions does the file have?
Make the file executable by adding the execute permission (x).
Remove the read and write permissions (rw) from the file for the group and everyone else, but not for the owner. Can you still read it?
Change the owner of the file to a different user. If everything went well, you shouldn’t be able to read the file unless you assume root privileges with ‘sudo’.
Change the group ownership of the file to a different group.
