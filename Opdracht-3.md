# PaaS Demo @Newskool
Author: Arjan Roos - GGM Consulting

## Opdracht 3 - Website in een Docker container op Azure Container Apps
We gaan een website, welke in een Docker contaier gevat is, deployen op een Azure Container App.
Probeer met de onderstaande tips de container app te bouwen:

- Maak een Azure Container App in je eigen resource group.
- Kies een eigen container app naam
- Regio West Europe
- Een Managed Container Apps Environment met:
    - Een eigen naam
    - Er worden geen logs opgeslagen
- We willen een eigen container kiezen, vanuit de volgende server: <br>

Docker image: acrggmwebprd001.azurecr.io/acrggmwebprd001/ggm-corp-fe:prd <br>
Container: ggm-corp-fe <br>
Tag: prd <br>
Server: acrggmwebprd001.azurecr.io <br>
Username: acrggmwebprd001 <br>
Password: *krijgen jullie te zien in de workshop* <br>
<br>
OF
<br>

Kies een Quickstart Image vanuit het formulier. (aanbevolen als eerste stap)

- Gebruik een Consumption plan
- Zorg dat je Container app van overal te benaderen is met Ingress en gebruik poort 3000

Na de deployment, ga naar de verkegen link van je nieuwe website.

