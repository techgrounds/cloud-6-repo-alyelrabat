# Azure Global Infrastructure

## Introductie:

Alles in de cloud, van servers tot networking, is virtualized. Als klant van een cloud provider hoef je je geen zorgen te maken over de onderliggende fysieke infrastructuur. De fysieke locatie van je applicatie of data kan echter wel belangrijk zijn.

De global infrastructure van Azure bestaat uit de volgende componenten:

Regions

Availability Zones

Region Pairs

Je hebt zelf controle over welke regio je gebruikt, maar niet elke service is beschikbaar in elke regio. Sommige services zijn ook niet gebonden aan een specifieke regio. Denk hierbij bijvoorbeeld aan Azure Subscriptions.

## Benodigdheden:

Google >> https://docs.microsoft.com/en-us/azure/availability-zones/az-overview , https://azure.microsoft.com/en-us/global-infrastructure/geographies/

## Bestudeer:
Wat is een Azure Region? https://www.pragimtech.com/blog/azure/azure-regions-and-paired-regions/

Wat is een Azure Availability Zone?

Wat is een Azure Region Pair?

Waarom zou je een regio boven een andere verkiezen?

## Resultaat

### When your workloads run on Azure, data may travel near or far—but that journey always starts in an Azure geography and hits some common points along the way.

### Datacenter regions are accessible across the world

With more global regions than any other cloud provider, Azure gives customers the flexibility to deploy applications where they need.

A region is a set of datacenters deployed within a latency-defined perimeter and connected through a dedicated regional low-latency network.
While solution suites Microsoft 365 and Dynamics 365 deploy in geographies, Azure itself deploys in regions, each with distinct pricing and service availability.

### Availability Zones provide resiliency and options for high availability

Availability Zones protect your applications and data from datacenter failures.
Azure Availability Zones, which are made up of a minimum of three zones, allow customers to spread their infrastructure and applications across discrete and dispersed datacenters for added resiliency, high availability, and the confidence that data traversing between Availability Zones is always encrypted.

We use more than 30 viability and risk-based criteria to evaluate the placement of each of the three Availability Zones to identify both significant individual risk as well as collective and shared risk between Availability Zones—without compromising the latency perimeter of less than two milliseconds.

### Azure Edge Zones let you meet customers where they are

Extending through Edge Zones means better delivery of latency-sensitive services in densely populated cities.
Edge Zones are small-footprint extensions of Azure placed in population centers that are far from Azure regions.

Edge Zones support virtual machines (VMs), containers, and a selected set of Azure services that let you run latency-sensitive and throughput-intensive applications close to end users.

### Geographies support your data, wherever it lives

An Azure geography is a distinct market, typically containing one or more regions.
Geographies allow customers with specific data residency (where data is stored and processed) and compliance needs to keep their data and applications close. 
Through their connection to our dedicated high-capacity networking infrastructure, geographies are fault-tolerant to withstand complete region failure.

When you explore the globe, select the white diamond icons to view details for major geographies, including associated regions, highlights, and updates.
