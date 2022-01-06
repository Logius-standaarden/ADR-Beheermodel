# Inleiding

## Leeswijzer

Dit document beschrijft hoe Logius, afdeling Standaarden (hierna: Logius) de REST-API Design Rules standaard beheert en hoe de bijbehorende governance is ingericht. In dit document wordt verder ADR gebruikt als afkorting voor de (REST)-API Design Rules.

## De REST-API Design Rules ofwel ADR-standaard

De ADR-standaard omvat een set van normatieve ontwerpafspraken voor het structureren en documenteren van REST-API’s. De standaard heeft tot doel om betere, uniforme en ontwikkelaar vriendelijke API’s te ontwikkelen die makkelijk te implementeren zijn.
De set van afspraken bestaat uit breed toepasbare en ondubbelzinnige richtlijnen. Deze helpen organisaties die nieuwe API’s ontwikkelen voor Nederlandse overheden (Rijk, provincies, gemeenten en waterschappen) en instellingen uit de (semi-) publieke sector.
Het Nut en de werking van de standaard zijn reeds goed beschreven door het Forum Standaardisatie en voor de eenduidigheid hieronder integraal opgenomen [zie link](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules):

### Nut

> De overheid ontsluit gegevens en applicaties steeds vaker met REST-API's. Voorbeelden hiervan zijn te zien op de website [developer.overheid.nl](https://developer.overheid.nl), [in Common Ground](https://commonground.nl), [Haal Centraal](https://www.vngrealisatie.nl/producten/haal-centraal) en [het Digitaal Stelsel Omgevingswet](https://aandeslagmetdeomgevingswet.nl).  
> Representational state transfer (REST) is een ontwerpprincipe dat wereldwijd veel gebruikt wordt voor het bouwen van programmeerinterfaces over het web (API's). REST is geen standaard maar een ontwerpprincipe, en laat nog veel vrijheid in het structureren van API's.  
> De standaard REST-API Design Rules geeft een verzameling basisregels voor structuur en naamgeving waarmee de overheid op een uniforme en eenduidige manier REST-API's aanbiedt. Dit maakt het voor ontwikkelaars gemakkelijker om betrouwbare applicaties met te ontwikkelen met API's van de overheid.
> [Bron: Forum standaardisatie](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules)

### Werking

> Een application programming interface (API) is een gestructureerd en gedocumenteerd koppelvlak voor communicatie tussen applicaties. Zo lang er computers zijn, bestaan er API's en worden er verschillende API technologieën gebruikt. In de laatste 10 jaar heeft Representational state transfer (REST) zich ontwikkeld tot een bepalend principe voor het realiseren van API's.  Zogenaamde ‘REST-API's’ doen voor applicaties wat websites voor mensen doen. Websites presenteren informatie aan mensen, REST-API's maken applicaties en gegevens over het Internet beschikbaar voor andere applicaties. De technologie achter websites en REST-API's heeft daarom veel gemeen.  
> De overheid gebruikt REST-API's voor koppelingen met andere overheden, bedrijven en indirect ook met burgers, bijvoorbeeld via mobiele apps en webapps die aangeboden worden door bedrijven of overheden zelf. Ontwikkelaars kunnen deze REST-API's bevragen vanuit de gangbare programmeertalen en frameworks zoals Python, Java, Microsoft C#, PHP.  
> [Bron: Forum standaardisatie](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules)

### Status

De actuele versie van de ADR-standaard is 1.0. Deze versie is op 09-07-2020 door het OBDO vastgesteld op advies van het Forum Standaardisatie.  
De status van de ADR-standaard is ‘Verplicht (pas toe leg uit)’. Dit houdt kort gezegd in dat Nederlandse overheden en instellingen uit de (semi) publieke sector verplicht zijn deze standaard toe te passen op het moment dat zij REST API’s gaan gebruiken voor het ontsluiten van overheidsinformatie en/of functionaliteit. (Zie voor meer informatie over het [pas toe of leg uit beleid.](https://www.forumstandaardisatie.nl/node/229))  

- De verplichting is gepubliceerd door het Forum Standaardisatie op:  
(https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules)  
- Versie 1.0 van de ADR is gepubliceerd op:  
(https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0)  
- De laatste versie van de ADR is gepubliceerd op:  
(https://publicatie.centrumvoorstandaarden.nl/api/adr/)  
- De laatste concept versie van de standard is gepubliceerd op:  
(https://logius-standaarden.github.io/API-Design-Rules/) 

## Bomos

Logius richt de beheerorganisatie in conform het Beheer en OntwikkelModel voor Open Standaarden (BOMOS). Ook het beheer van de ADR-standaard is op basis van BOMOS ingericht. Voor de beheerorganisatie heeft Logius een generiek beheermodel opgezet, waar het beheerplan van de ADR-standaard is afgeleid.  

![Bomos model](media/Bomos_model_v2.svg "Bomos model")
> Figuur 1. Bomos model

Voor meer informatie over BOMOS zie ook [de beslisboom van het forumstandaardisatie](https://beslisboom.forumstandaardisatie.nl/thema/ontwikkelen-en-beheren-van-open-standaarden).  
BOMOS onderscheidt verschillende levenscyclusfases waarin een standaard zich kan bevinden. Deze fase bepaalt mede op welke beheeronderdelen meer of minder wordt ingezet. De verschillende fases zijn:  

1.	Creatie/ontwikkeling
2.	Introductie
3.	Implementatie/groei
4.	Volwaardige toepassing
5.	Uitfaseren

![Bomos_levenscyclus](media/Bomos_levenscyclus_v2.svg "Bomos levenscyclus")
> Figuur 2. Bomos levenscyclus

De ADR-standaard bevindt zich in de implementatie/groei fase. De eerste versie van de standaard is 15-10-2019 aangemeld bij het Forum Standaardisatie en op 09-07-2020 op de lijst van verplichte standaarden opgenomen. Vanuit het Kennisplatform API’s en Logius Centrum voor Standaarden wordt momenteel nog volop aan de API Design Rules gewerkt en de verwachting is dat de standaard nog de nodige ontwikkelingen door gaat maken. Daarnaast komt het gebruik van de API Design Rules pas net op stoom, waardoor er van een volwaardige toepassing bij de beoogde doelgroep nog geen sprake is.  

Dit heeft gevolgen voor het beheer van de standaard. Naast de groei in de aantallen toepassingen van de standaard is ook relevant dat eerst nog minor en major wijzigingen in de standaard op een correcte manier worden doorgevoerd en er veel informatie beschikbaar is die gebruikers helpt bij de implementatie van de standaard. Daarom is er komende tijd vooral aandacht voor:

-	Het in de praktijk bestendigen van het beheer van de standaard;  
-	Gestaag doorontwikkeling van de specificaties zelf;  
-	Bouwen en aanbieden ondersteunende tooling;  
-	Groei in het aantal toepassingen van de standaard;  
-	Monitoring van het gebruik van de standaard;  
-	Groei van de community rond de standaard.  

