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

## Gebruikte bronnen

Linux File Permission Tutorial: How to Check and Change Permissions https://phoenixnap.com/kb/linux-file-permissions

Chmod: zo werken maprechten in Linux https://www.strato.nl/server/chmod-hoe-gebruik-je-het/

Chown Command in Linux (File Ownership) https://linuxize.com/post/linux-chown-command/

## Benodigheden

CentOS VM

## Opdracht

- Maak een tekstbestand.

- Maak een lange lijst om de machtigingen van het bestand te bekijken. Wie is de eigenaar en groep van het bestand? Welke machtigingen heeft het bestand?

- Maak het bestand uitvoerbaar door de uitvoermachtiging (x) toe te voegen.

- Verwijder de lees- en schrijfrechten (rw) uit het bestand voor de groep en alle anderen, maar niet voor de eigenaar. Kun je het nog lezen?

- Wijzig de eigenaar van het bestand in een andere gebruiker. Als alles goed is gegaan, zou je het bestand niet moeten kunnen lezen, tenzij je root-privileges aanneemt met 'sudo'.

- Wijzig het groepseigendom van het bestand in een andere groep.

## Ervaren problemen

geen.

## Resultaat
