# Cost Management + Billing

https://azure.microsoft.com/nl-nl/services/cost-management/#overview

https://docs.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview

## CAPEX vs OPEX

Bedrijven hebben verschillende uitgaven, van de huur die ze betalen voor hun fabrieken of kantoren tot de kosten van grondstoffen voor hun producten, 
tot de lonen die ze hun werknemers betalen tot de totale kosten van de groei van hun bedrijf. 
Om al deze kosten te vereenvoudigen, organiseren bedrijven ze in verschillende categorieën. Twee van de meest voorkomende zijn Capital Expenditures 'CAPEX' (kapitaaluitgaven) 
en Operating Expenses 'OPEX' (bedrijfskosten).
Capital Expenditures (CAPEX) worden gedaan wanneer een bedrijf activa aanneemt die na het lopende belastingjaar voordelig zouden kunnen zijn.
Operating Expenses (OPEX) bestaan uit de kosten die een bedrijf maakt om elke dag goed te kunnen functioneren. 
 
#### Capital Expenditures (CAPEX) 

o.a. hardware servers On-Premise en Enterprise software licensies

#### Operating Expenses (OPEX) 

o.a. virtual hardware (servers) en software subscriptions door middel van lease met Azure Pay-as-you-go 

## Azure geeft de volgende principes om succesvol je kosten te reduceren

#### Plan (Planning)

Met vooraf planning kunt u het cloudgebruik afstemmen op uw specifieke zakelijke vereisten. 

- Welk zakelijk probleem ben ik aan het oplossen?

- Welke gebruikspatronen verwacht ik van mijn resources?

- Uw antwoorden helpen u het aanbod te kiezen dat bij u past.
Ze bepalen welke infrastructuur moet worden gebruikt en hoe deze wordt gebruikt om uw Azure-efficiëntie te maximaliseren.

#### Visibility (Zichtbaarheid) 

Als het goed is gestructureerd, helpt de 'Cost Management' u om mensen te informeren over de Azure-kosten 
waarvoor ze verantwoordelijk zijn of voor het geld dat ze uitgeven. 
Azure heeft services zoals (Cost Management) die zijn ontworpen om u inzicht te geven in waar uw geld aan wordt besteed. 
Profiteer van deze hulpmiddelen. Ze kunnen u helpen bij het vinden van onderbenutte hulpbronnen, 
het verwijderen van afval en het maximaliseren van kostenbesparende mogelijkheden.

Azure fucties hier voor zijn bijvoorbeeld Cost Analysis'. Met 'Cost Analysis' analyseer je jou data en krijg interactief inzicht.
Met de Azure functie 'Export' push je jou data naar een storage account op een dagelijkse of wekenlijkse basis om daily snapshots intezien 
en of de gewonnen data te laten intergregren met andere services.

#### Accountability (Verantwoording)

Zorg voor inzicht mbt kosten in uw organisatie om ervoor te zorgen dat de verantwoordelijke personen verantwoordelijk zijn voor de uitgaven van hun team. 
Om de Azure-uitgaven van uw organisatie volledig te begrijpen, moet u uw resources zo organiseren dat u maximaal inzicht krijgt in de kostentoewijzing. 
Een goede organisatie helpt bij het beheersen en verlagen van kosten en houdt mensen verantwoordelijk voor efficiënte bestedingen in uw organisatie.

Stel artefacten zoals sjablonen, beleidsregels, roltoewijzingen en resourcegroepen samen op basis van algemene of organisatiegebaseerde patronen in herbruikbare blauwdrukken.

https://azure.microsoft.com/en-us/solutions/governance/#features

#### Optimization (Optimalisatie)

Met de meest optimale inzicht o.a. door middel van planning en zichtbaarheid kan je handellen om uitgaven te verminderen zo optimaliseer je de kosten. 
U kunt aankoop- en licentie-optimalisaties overwegen, evenals wijzigingen in de infrastructuurimplementatie.

#### Iteration (Iteratie)

In uw organisatie zal iedereen zich bewust moeten zijn van de levenscyclus van kostenbeheer. 
Ze moeten voortdurend betrokken blijven om de kosten te optimaliseren door o.a te monitoren en verbeteren.
Wees rigoureus over dit iteratieve proces en maak verantwoord cloudbeheer een belangrijk principe in uw organisatie.

https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-best-practices

#### Total Cost of Ownership 'TCO' (Totale Eigendomskosten)

Bij het evalueren van uw gebruik van de Azure-cloud is het belangrijk om rekening te houden met de Total Cost of Ownership (TCO).
De TCO wordt gebruikt om te berekenen hoeveel een infrastructuur kost als het op de traditionele manier gehost wordt. 
Met de TCO-calculator kan je de kosten van een traditionele infrastructuur vergelijken met de kosten voor dezelfde infrastructuur op Azure.

Je kan bijvoorbeeld met de TCO-calculator een schatting van de kostenbesparing maken door uw workloads te migreren naar Azure.

https://azure.microsoft.com/nl-nl/pricing/tco/calculator/

https://cloud.netapp.com/blog/azure-cvo-blg-how-to-reduce-your-cloud-bill-with-the-azure-tco-calculator#H_H3

## TCO-Calculator

#### Azure 'TCO-calculator' hoe wordt het gebruikt?

De Azure TCO-calculator werkt in drie fasen

#### Define your workloads (Uw workloads definiëren)
- Servers
- Databases
- Storage
- Networking

#### Adjust assumptions (Veronderstellingen aanpassen)
- Software Assurance coverage (Software Assurance dekking voor Windows Server ,Software Assurance dekking voor SQL Server)
- Geo-redundant storage 'GRS' (Geografisch redundante opslag)
- Virtual Machine costs (Kosten van virtuele machines)
- Electricity costs (Elektriciteitskosten)
- Storage costs (Opslagkosten)
- IT labor costs (Kosten IT-arbeid)

Er zijn nog overige veronderstellingen die tevens invloed hebben op het TCO-model o.a.
Hardware costs, Software costs, Virtualization costs, Data center costs, Networking costs, Database costs, Data warehouse costs

Hiervoor zijn echter door de klant minder aanpassingen vereist en kunt u hiervoor op elk gewenst moment naar deze sectie terugkomen en de veronderstellingen aanpassen.

#### Rapport bekijken
 
Nadat u hebt bevestigd dat uw gegevens correct zijn, kunt u de berekeningen uitvoeren. U kunt vervolgens uw geschatte kosten voor Azure-resources en -services bekijken.
 
Zie voorbeeld: [Berekening total cost of ownership (TCO) _ Microsoft Azure.pdf](https://github.com/techgrounds/cloud-6-repo-alyelrabat/files/7711801/Berekening.total.cost.of.ownership.TCO._.Microsoft.Azure.pdf)

### Azure-account free subscription

#### Voorwaarden

## Opdracht:

Maak een alert aan waarmee je eigen Cloud Pass kan monitoren. 

<img width="1432" alt="Screen Shot 2021-12-15 at 11 07 42" src="https://user-images.githubusercontent.com/89514322/146166838-ad4113cb-76ad-4715-89ab-2630381b704e.png">


## Begrijp de opties die Azure aanbiedt om je uitgaven in te zien

Als je in de auto rijdt wil je soms weten hoeveel brandstof je real time verbruikt. In een auto is dit gelukkig niet zo lastig, je gaat naar je dashboard en kiest daar voor je huidige verbruik weergeven. Je kunt precies zien hoeveel brandstof je op dat moment aan het verbranden bent.

Microsoft heeft hier verschillende manieren voor: Azure kan verbruik als CSV-bestand exporteren en importeren in een ander systeem, API’s inzetten om data op te halen vanuit je Azure cost management, Microsoft Power BI om een dashboard te creëren om een overzicht te krijgen van de gebruikte en verbruikte Azure resources.

## Uitgaven inzicht met Azure service tools: Azure Monitor en Log Analytics

Azure Cost Management Overview https://www.youtube.com/watch?v=dxtBdjfWCZU

Azure Cost Optimization Deep Dive https://www.youtube.com/watch?v=RjuTQvGm1zQ




