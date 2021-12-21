# Azure Global Infrastructure

### Azure Geography (Geografie):

Een Azure Geography is een gebied van de wereld dat ten minste één Azure regio bevat. India is bijvoorbeeld een Azure Geography. 
Evenzo zijn de Verenigde Staten en het Verenigd Koninkrijk Azure Geography Regions.

#### Specifiek: een Azure Geography is een gebied van de wereld dat één of meer Azure Regions bevat.

### Regions (Regio's):

Een Azure Region is een groep van een of meer Azure datacenters.
Azure Regions is een zeer belangrijk concept, want elke keer dat u een Azure resource maakt, zoals een virtuele machine, moet u de regio opgeven waar u de resource wilt maken, in dit geval de virtuele machine.
Een Azure Region kan ook worden gecombineerd met andere Azure Regions (Region Pairs) ook kan een Azure Region Availability Zones (beschikbaarheidszones) hebben.
Azure omvat veel Regions over de hele wereld. Elke Azure Region heeft specifieke kenmerken die het kiezen van de te gebruiken Region ongelooflijk belangrijk maken.
Het komt voor dat je één Region verkiest boven de ander omwille van bijv 'Service availability' zoals o.a. 'Azure Red Hat OpenShift' wel beschickbnaar is in Central India maar niet in South India of West India.
ook de 'Capacity' (capaciteit) speelt een belangerijke rol. Elke Region heeft een maximale Capacity. Dit kan van invloed zijn op welke typen abonnementen welke typen services kunnen worden geïmplementeerd en onder welke omstandigheden. Dit is anders dan abonnementsquota. Als u een grootschalige datacentermigratie naar Azure plant, kunt u het beste overleggen met uw lokale Azure-veldteam of accountmanager om te bevestigen dat u op de benodigde schaal kunt implementeren.


### Availability Zones (beschikbaarheidszones):

Een Azure Availability Zone is een unieke fysieke locatie binnen een Azure Region. 
Elke Availability Zone bestaat uit één of meer Datacenters. Niet alle Regions hebben Availability Zones. Regions die Availability Zones ondersteunen, hebben minimaal drie afzonderlijke zones om 'Resiliency' (veerkracht) te garanderen.
Als één van de Availability Zones om de één of andere reden is uitgevallen, hebben we nog steeds onze applicaties en gegevens beschikbaar van de rest van de twee Availability Zones. Er is een fysieke scheiding tussen elke Availability Zone en het is deze scheiding die onze applicaties en gegevens beschermt tegen storingen in het datacenter. Met Availability Zones biedt Azure de beste 99,99% VM-uptime SLA in de branche.

### Region Pairs (gekoppelde regio's)

De meeste Regions in een Geography zijn gekoppeld om Business Continuity and Disaster Recovery 'BCDR' (bedrijfscontinuïteit en noodherstel) te garanderen.

Het voordeel bij Region Pairs komt naar voren bij een storing in Azure. Zo krijgt één Region prioriteit uit elk paar om de hersteltijd voor toepassingen te verkorten. Ook geplande Azure updates worden één voor één naar gekoppelde Regions uitgerold om downtime en het risico op uitval van toepassingen te minimaliseren. Gegevens blijven zich binnen dezelfde Geography bevinden als het paar (behalve voor Zuid-Brazilië voor belasting- en rechtshandhavingsdoeleinden).

### Bronnen:

https://azure.microsoft.com/en-us/global-infrastructure/geographies/ 

https://docs.microsoft.com/en-us/azure/availability-zones/az-overview 

https://docs.microsoft.com/nl-nl/azure/availability-zones/cross-region-replication-azure 
 
https://www.pragimtech.com/blog/azure/azure-regions-and-paired-regions/ 




