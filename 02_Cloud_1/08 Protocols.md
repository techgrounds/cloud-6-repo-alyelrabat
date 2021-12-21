# Protocols

Een 'protocol' is een gedragsovereenkomst, meestal in de vorm van een aantal uit te voeren stappen. Er bestaan verschillende typen protocollen, zoals communicatieprotocollen, computerprotocollen, wetenschappelijke protocollen, medische protocollen, ceremoniële protocollen, ethische protocollen en verdragsprotocollen.

HyperText Transfer Protocol Secure, afgekort 'HTTPS', is een uitbreiding op het HTTP-protocol met als doel een veilige uitwisseling van gegevens.
'TCP/IP' is een verzamelnaam voor een reeks netwerkprotocollen die gebruikt worden voor het grootste deel van de netwerkcommunicatie tussen computers. 
Het internet is het grootste en bekendste TCP/IP-netwerk.

## Ontstaan OSI-Model

Het Open Systems Interconnection Model (OSI-model) werd in 1977 door de International Organization for Standardization (ISO)* ontworpen als referentiemodel voor een open communicatie tussen verschillende technische systemen.
Het OSI-model is het resultaat van een poging tot standaardiseren en biedt als conceptueel kader een designbasis voor communicatiestandaards die niet afhankelijk zijn van fabrikanten. 

Het OSI-model is het resultaat van een poging tot standaardiseren en biedt als conceptueel kader een designbasis voor communicatiestandaards die niet afhankelijk zijn van fabrikanten. Daarvoor verdeelt het door ISO ontworpen OSI-model het complexe proces van de netwerkcommunicatie in zeven niveaus, de zogenaamde lagen (in het Engels layers)

## Wat is het OSI-Model

Het OSI model is een veelgebruikte term in de netwerkwereld en staat voor Open Systems Interconnection. Het OSI model bestaat uit 7 lagen (1.Fysieke laag, 2.Datalinklaag, 3.Netwerklaag, 4.Transportlaag, 5.Sessielaag, 6.Presentatielaag, 7.Applicatielaag) die ieder staan voor een bepaalde functie in het netwerk. 
Alle netwerkcomponenten of clients die verbinding kunnen maken met het netwerk wisselen communicatie uit via de regels van het OSI model.

De International Organization for Standardization (ISO) is een internationale niet-gouvernementele organisatie die bestaat uit nationale normalisatie-instellingen; het ontwikkelt en publiceert een breed scala aan propriëtaire, industriële en commerciële normen en bestaat uit vertegenwoordigers van verschillende nationale normalisatie-organisaties.

## Hoe een HTTPS TCP/IP-pakket opgebouwd is

Als je data via Internet verstuurt dan gaat het in verschillende stappen. Er komen dan verschillende verschillende "stuurprogramma's" aan te pas, die verschillende dingen voor hun rekening nemen. Dat noem je de verschillende "lagen" van de transmissie. En bij elke laag heb je een protocol.

##### Fysieke laag - Deze laag verzorgt het fysieke transport van bits.
De fysieke laag omvat alle fysieke bekabeling die tussen de netwerkcomponenten hangt.
 
##### Datalinklaag - Deze laag beheert en controleert de datatransmissie en probeert fouten te corrigeren
De datalinklaag verzorgt de communicatie tussen verschillende hardware binnen een netwerk. Alle hardware apparatuur heeft een MAC of hardware adres die over de datalinklaag kunnen communiceren. Bijvoorbeeld switches werken op deze laag door middel van de ethernet techniek. De data die verstuurd worden over laag 2, worden ook wel frames genoemd.
 
##### Netwerklaag - Deze laag verzorgt het transport, de adressering en de routering van pakketten door een netwerk
De netwerklaag maakt het mogelijk om data te verzenden tussen verschillende netwerken. Daarnaast zorgt de netwerk laag ervoor dat er gerouteerd kan worden binnen een netwerk. Het protocol dat draait op deze laag is het Internet Protocol, ook wel bekend als (IP). Routers werken op de netwerklaag en kunnen dus IP adressen maken. Deze virtuele adressen kunnen pakketjes ontvangen en verzenden. De data die verstuurd wordt over laag 3, worden ook wel pakketjes genoemd.
 
##### Transportlaag - Deze laag verzorgt een data-onafhankelijk eind-naar-eindtransportsysteem

Als je een emailbericht intypt en drukt op "verzenden" gebeurt er van alles. Eerst wordt er een verbinding gemaakt met je provider via de telefoon of de kabel. 
En er wordt op een bepaalde manier duidelijk gemaakt aan de provider dat ze een bericht (bitstroom), kunnen verwachten. Hoe dat gebeurt zijn afspraken over gemaakt, die afspraken vormen het TCP-protocol (Transmission Control Protocol). De transportlaag verdeelt het bericht in stukken, meestal van 1500 bytes (TCP-segmenten).
Aan het TCP-segment wordt een 'Header' toegevoegd die bestaat uit 20 bytes. Zo'n TCP-segment ziet er dan als volgt uit:

##### Applicatielaag - Deze laag verbindt de netwerkapplicaties met de gebruikers
De applicatielaag wordt gebruikt door netwerk-applicaties zoals FTP clients, e-mail programma's en interne systemen. Deze systemen werken op de applicatielaag omdat ze gebruik maken van protocollen die draaien die ook compatible zijn met deze laag. Denk bijvoorbeeld aan FTP, HTTP, SMTP.

---------------------------------------------------------------------------------

## Wie bepaalt welke protocols wij gebruiken en hoe introduceer je zelf een nieuw protocol.

Wie: De Internet Engineering Task Force (IETF) en de Internet Society die toezicht houdt op de IETF, houden toezicht op de internetprotocollen, en het Internet Consortium for Assigned Names and Numbers (ICANN) controleert de DNS-hiërarchie en de toewijzing van IP-adressen.

Hoe: Je zal eerst moeten weten welke poorten wel of niet bezet zijn vervolgens test je jouw app of die luistert naar het protocol.
Werkt het, dan introduceer je het protocol met info (naam en port#) en bewijs materiaal (in operation) bij de directie.
De directie gaat buigen over het toekennen protocol als standard ja of nee.

## Facebook en de BGP-update (Border Gateway Protocol)

Facebook was recent niet beschickbaar omdat een routinematige BGP-update fout was gegaan. BGP staat voor Border Gateway Protocol. Dat is de routekaart die aan je computer laat weten waar websites en apps te vinden zijn.
Het systeem wordt ook gebruikt bij het laden van chats in WhatsApp en Messenger, de foto's op Instagram, interne berichten van bedrijven die Workplace gebruiken en de VR-apps van Oculus-brillen.
BGP is bedoeld om files en vertragingen te voorkomen. Als alle bezoekers langs dezelfde weg naar hun gegevens zouden gaan, zouden de netwerken namelijk vastlopen.
De mislukte update zorgde voor een situatie die het verhelpen van de storing door de Facebook-medewerkers heel lastig maakte. "De update blokkeerde gebruikers op afstand zodat die de wijzigingen niet ongedaan konden maken en tegelijk hadden medewerkers in de kantoren geen netwerktoegang.  

## Bronnen

TCP/IP-pakket https://nl.wikipedia.org/wiki/TCP/IP-pakket

OSI Model https://nl.wikipedia.org/wiki/OSI-model

Les 14.1. Het TCP/IP-protocol en de netwerklagen http://www.halict.nl/lcinformatica/klas5/h14/h14_1.htm#inhoud

De 7 lagen van het OSI model https://www.firewallshop.nl/kennisblog/item/het-osi-model-1

Wat is TCP en UDP? Een simpele uitleg https://nordvpn.com/nl/blog/wat-is-tcp-udp/

OSI Model Layers and Protocols in Computer Network https://www.guru99.com/layers-of-osi-model.html

TCP/IP vs OSI Model, What’s the Difference? https://www.guru99.com/difference-tcp-ip-vs-osi-model.html

Open Systems Interconnection model https://osi-model.com/

OSI Model Layers and Protocols in Computer Network https://www.guru99.com/layers-of-osi-model.html#5

what is TCP/IP and OSI? // FREE CCNA // EP 3 https://www.youtube.com/watch?v=CRdL1PcherM&t=424s

TCP, IP, HTTP/S and FTP https://www.youtube.com/watch?v=7LfTWbOp5vU

IETF https://www.ietf.org/about/participate/get-started/#participatinginmeetings

Scapy – Network Packet Toolkit https://jarnobaselier.nl/scapy-network-packet-toolkit/


![IMG_2510](https://user-images.githubusercontent.com/89514322/146156008-a5677672-e021-4104-af09-e9f2fdf10f93.PNG)
![Scapy-1](https://user-images.githubusercontent.com/89514322/146162449-6d445bc0-5830-42ac-91d2-3af703ad2064.jpeg)
![image](https://user-images.githubusercontent.com/89514322/146162862-44bcaaf2-c23a-4092-bc32-36ae74884bcc.png)
