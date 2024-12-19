# PaaS Demo @Newskool
Author: Arjan Roos - GGM Consulting

## Opdracht 2 - Wordpress op een Azure App Service
In deze opdracht gebruiken we een aantal resources om een Wordpress website te bouwen:
- Azure App Service
- MySQL Database
- Azure Communication Service
- Storage Account
- Virtual Network

Moeten we dit allemaal zelf bouwen? Nee, gelukkig niet :p
Maar we gaan wel ervaren wat de kracht van de Cloud is!

Zoek in de Azure Portal naar: Marketplace.
Je bent nu aangekomen in de 'App Store' van de Azure Portal.

Zoek hier naar 'Wordpress' en selecteer de offer 'Wordpress' van de uitgever 'Microsoft'.

Klik op 'Create'

In het formulier lopen we de volgende zaken door:
- We kiezen onze eigen resource group
- Regio: North Europe
- We geven een eigen naam in (mag je zelf bepalen)
- Het Hosting Plan laten we voor nu zo staan: 'Premium V3 App Service Burstable, MySQL Database'
- We geven een wachtwoord op (onthoud deze)
- Klik op 'Next: Add-ins'
- Deselecteer 'Enable Azure CDN'
- Ga door naar Review + Create en klik op 'Create'

De deployment wordt nu gestart... let op wat er nu allemaal automatisch voor jou gebeurt.

Als de deployment is geslaagd, ga naar de resource.
Klik op de link naast 'Default domain'.
