# Security

Een algemeen overzicht van de security concepten en componenten kan je hier vinden : https://wiki.antwerpen.be/ACPAAS/index.php/Identity_%26_Access_Management 

## ACPaaS Identity & Access Engine

De [Identity & Access Engine](https://acpaas.digipolis.be/nl/product/identity-access-engine) faciliteert als centrale bouwsteen in het ACPaaS Platform de toegang van gebruikers tot een applicatie:
* [Detailpagina](https://wiki.antwerpen.be/ACPAAS/index.php/Identity_%26_Access_Management/Identity_%26_Access_Engine)
## Identiteit

We onderscheiden grofweg 2 profielen, respectievelijk voor burgers en medewerkers:

* A-profiel : https://wiki.antwerpen.be/ACPAAS/index.php/A-Profiel_(burger)
* M-profiel : https://wiki.antwerpen.be/ACPAAS/index.php/M-Profiel_(medewerker)

* Registratie van een applicatie, eindgebruikers en gekoppelde rollen:

* De UME applicatie faciliteert het aanvragen en toekennen van rollen en rechten in applicaties aan gebruikers met een M-Account:
https://wiki.antwerpen.be/ACPAAS/index.php/Identity_%26_Access_Management/User_Management_Engine



## Authenticatie

Applicaties kunnen de OAuth2 authorizatie server gebruiken om A/M-profielen te laten authenticeren(authorization_code). Daarnaast ondersteunen we ook de mogelijkheid om applicaties te authenticeren(client_credentials). 

Meer informatie kan je hier vinden: 
* Detailpagina authenticatie met OAuth2 : https://github.com/digipolisantwerpdocumentation/authentication/blob/master/README.md




## Autorisatie

Meer informatie kan je hier vinden
*  Detailpagina autorisatie: https://github.com/digipolisantwerpdocumentation/autorisatie/blob/master/README.md

