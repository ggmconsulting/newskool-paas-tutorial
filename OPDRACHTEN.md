# PaaS Demo @Newskool
Author: Arjan Roos - GGM Consulting

## Opdracht 1 - Storage Account
In deze opdracht gebruiken we een Azure Storage Account om een website te bouwen. Om dit te bouwen gaan we het volgende doen:

- Bouw een Storage Account in je resource group.
- Bepaal zelf de naam van je storage account, let op: de naam moet uniek zijn!
- Regio: West Europe
- Service: Blob, Performance: Standard
- Redundancy: Local Redundant Storage
- ‘Anonymous’ users hebben toegang nodig
- Iedereen mag toegang hebben.
- Soft delete moet uit

Met deze opties kan je jouw nieuwe Storage Account aanmaken. Met deze resource kunnen we nu onze website gaan bouwen.

- In het Storage Account, ga naar 'Static Website'
- Als 'Index document name' vullen we in: index.html
- 'Error document name' laten we leeg.

Er wordt nu een 'Container' aangemaakt binnen het Storage Account genaamd: $web
In deze container, plaats de bestanden uit de map 'opdracht-1' van deze GitHub repo.

Heb je dit gedaan? Ga naar het Primary Endpoint van je 'Static Website'. 
(Je kan dit terugvinden bij 'Static Website')

Gefeliciteerd! Je eerst static website is live.

## Opdracht 2 - Azure Static Website
