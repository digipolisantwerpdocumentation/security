# Security

Een algemeen overzicht van de security concepten en componenten kan je hier vinden : [IAM](https://acpaas.digipolis.be/nl/docs/identiteit-authenticatie-en-autorisatie)

## ACPaaS Identity & Access Engine

De [Identity & Access Engine](https://acpaas.digipolis.be/nl/product/identity-access-engine) faciliteert als centrale bouwsteen in het ACPaaS Platform de toegang van gebruikers tot een applicatie. 


## Identiteit

We onderscheiden grofweg 2 profielen, respectievelijk voor burgers en medewerkers:

* [A-profiel](https://acpaas.digipolis.be/nl/product/a-profiel-api/about)
* [M-profiel](https://acpaas.digipolis.be/nl/product/crs-medewerker/about)

Het opvragen van persoonsgegevens verloopt via de [Shared Identity Data API](https://acpaas.digipolis.be/nl/product/shared-identity-data-api). Deze component werkt als een 
firewall voor het ophalen van persoonsgegevens uit de achterliggende authentieke databronnen. Hij filtert op basis van de scopes of attributen die toegekend zijn na een 
succesvolle authenticatie. 

Registratie van een applicatie, eindgebruikers en gekoppelde rollen zijn mogelijk in de volgende componenten

* De [User Management Engine](https://acpaas.digipolis.be/nl/product/user-management-engine) faciliteert het aanvragen en toekennen van rollen en rechten in applicaties aan 
gebruikers met een M-profiel.
* De [Business Roles as a Service (BRaaS) Engine](https://acpaas.digipolis.be/nl/product/braas-engine) wordt hoofdzakelijk ingezet voor autorisaties voor gebruikers met A-
profielen en applicaties, alsook het gebruik van teams als bereiken.

## Authenticatie

Authenticatie gebeurt via OpenID connect a.d.h.v. authenticatiemethodes en betrouwbaarheidsniveaus.  
Applicaties kunnen de OAuth2 authorizatie server gebruiken om A/M-profielen te laten authenticeren(authorization_code). Daarnaast ondersteunen we ook de mogelijkheid om applicaties te authenticeren(client_credentials). 

Meer informatie kan je hier vinden: 
* Detailpagina [authenticatie met OAuth2](https://github.com/digipolisantwerpdocumentation/authentication/blob/master/README.md)

## Autorisatie

Meer informatie kan je hier vinden
*  Detailpagina [autorisatie met UME en APIs](https://github.com/digipolisantwerpdocumentation/autorisatie/blob/master/README.md)

