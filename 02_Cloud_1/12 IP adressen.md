# IP adressen

## Introductie:

Een IP adres is een logisch adres die aan een netwerkapparaat toegewezen kan worden. De netwerkapparaten kunnen dan vervolgens met dit IP adres elkaar vinden op het netwerk.
Een IPv4 adres heeft 32 bits (8 bytes), en is meestal geschreven in decimalen (bijvoorbeeld: 132.88.142.5) waar iedere blok voor, na, en tussen de punten, 1 byte is. Dit betekent dat één blok tussen punten een maximale waarde kan hebben van 255. 

Het is wijd en zijd bekend in de ICT dat alle IPv4 adressen op zijn. De 8 bytes in een IPv4 adres maakt het mogelijk dat er 4,294,967,296 IPv4 adressen mogelijk zijn. En deze zijn allemaal al verkocht of gereserveerd. Mocht je interesse hebben wie jouw publieke IP adres mocht bezitten, dit is op te zoeken op met een whois-check.

Het originele idee dat iedere computer op het internet met ieder een eigen publiek IP(v4) adres aanspreekbaar is, is al lang niet meer zo. Over de jaren heen zijn er een aantal maatregelen genomen om nog langer met IPv4 te kunnen werken. Zo heb je als gebruiker van het internet, achter je modem, maar één publiek IP adres dat je deelt met alle apparaten op het netwerk. Dit is mogelijk vanwege een NAT-tabel in je modem. Een NAT-tabel houd bij welke verbindingen de apparaten in je privé netwerk maken met het publieke internet en zorgt er dan voor dat data als antwoord naar de juiste computers gestuurd worden.

## IP adres (172.16.254.1)

Wat is een IP adres ?

IP-adressen zorgen ervoor dat gegevens op de juiste bestemming terechtkomen. Mensen en bedrijven hebben uw adres nodig als ze post naar u willen sturen. Zo is het ook op internet: een digitaal adres is nodig om u de gewenste gegevens te kunnen toesturen.

Een IP-adres bestaat over het algemeen uit vier getallen tussen 0 en 255, van elkaar gescheiden met punten. De vier getallen hoeven niet allemaal te bestaan uit drie cijfers. In het bovenstaande voorbeeld is het eerste getal 172, het tweede getal 16, het derde getal 254 en het vierde getal 1.

## IPV4

Wat is IPv4?

IPv4, de vierde versie van het Internet Protocol, werd als eerste op grote schaal gebruikt en vormt hiermee de basis voor de adressering binnen het internet. IPv4 gebruikt adressen van 32 bits (bijvoorbeeld: 132.88.142.5). Er passen 8 bits in een byte. Een byte is de grootte waarmee een computer iets uit het geheugen haalt. Hiermee zijn zo’n 4,3 miljard adressen mogelijk. Het lage aantal adressen was een van de redenen voor het ontwikkelen van IPv6. Hoewel IPv6 vandaag de dag vooral in gebruik is, blijft IPv4 ook van toepassing.

## IPV6

Wat is IPv6?

Internet Protocol versie 6 (IPv6) is een bijgewerkte standaard voor de identificatie van computers op internet. Net als bij IPv4 wordt met dit protocol aan elk apparaat een uniek id toegewezen, met de nodige aanpassingen in verband met het toenemende aantal computers dat vandaag de dag met internet verbonden is.

IPv6 verhoogt het aantal mogelijke IP-adressen van die 4 miljard bij IPv4 tot 340 sextiljoen (een getal van 39 cijfers). IPv6 wordt geschreven als een 128-bits hexadecimale cijferreeks en een typisch IPv6-adres ziet er ongeveer zo uit: 2001:0ab8:85a2:0000:0000:8a3e:0370:7334

![image](https://user-images.githubusercontent.com/89514322/146917587-0ffe7442-41a6-4ba6-9eed-53901f0a59f5.png)

## Public en Private IPs

Wat zijn Public en Privare IPs ?

- Public (Openbare) IP-adressen zijn adressen waarmee twee computers elkaar kunnen identificeren. Wanneer een persoon verbinding maakt met internet, krijgt zijn computer een adres toegewezen uit een pool die door de internetprovider is gereserveerd voor zijn klanten. Wanneer jij een websiteadres typt - zoals Google.com  wordt die domeinnaam omgezet in het IP-adres van de server die de website host. De server gebruikt het openbare IP-adres van de computer om te weten waar de gevraagde sitepagina naartoe moet worden gestuurd.

- Private (Privé) IP-adressen of RFC 1918 zijn adressen die niet routeerbaar zijn op het internet. Door deze beperking wordt het mogelijk de adressen te hergebruiken: verschillende netwerken kunnen binnen het eigen netwerk dezelfde IP-adressen gebruiken. Hierdoor wordt het gebruik van publieke IPv4-adressen verminderd. Om computers (of andere apparaten) die geconfigureerd zijn met een RFC 1918-adres toch gebruik te laten maken van het internet, wordt er tussen het privénetwerk en het internet een network address translation (NAT)-router geplaatst die de RFC 1918-adressen vertaalt in een publiek IP-adres. Op deze manier kan een groot aantal computers één of enkele IP-adressen delen.

Er zijn 3 IP adres bereiken gereserveerd voor privé netwerken. Iedereen gebruikt één van deze netwerken thuis of op werk. 

Deze zijn:
- 192.168.0.0 - 192.168.255.255
- 172.16.0.0 - 172.31.255.255
- 10.0.0.0 - 10.255.255.255

## NAT (Network Address Translation)

Wat is NAT ?

NAT 'Network Address Translation' is een verzamelnaam voor technieken die gebruikt worden in computernetwerken waarbij de adresinformatie in de datapakketjes veranderd wordt (Private naar Public en Public naar Private). Zodoende kunnen verschillende netwerken aan elkaar worden verbonden. De techniek wordt hoofdzakelijk in routers ingezet.

## Opdracht:

### Ontdek wat je publieke IP adres is van je laptop en mobiel op wifi 

Macbook 192.168.xxx.xxx

Iphone  192.168.xxx.xx

### Ontdek wat je publieke IP adres is op je mobiel via mobiel internet (als mogelijk)

Iphone  109.36.xxx.xx

### Maak een VM in je cloud met een publiek IP. Maak verbinding met deze VM.

### Verwijder het publieke IP adres van je VM. Begrijp wat er gebeurt met je verbinding.

Vergeet niet de VMs te verwijderen en alle extra resources te verwijderen nadat je klaar bent.

## Benodigdheden:

Je laptop
Je mobiel
Je cloud omgeving

https://www.youtube.com/watch?v=FTUV0t6JaDA

https://www.extip.nl/
