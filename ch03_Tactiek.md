# Tactiek

## Community

De ADR community/ Interesse Groep bestaat uit eenieder die belanghebbende of belangstellende is m.b.t. de standaard. Deelname aan de community kent geen drempels of restricties. Leden van de community kunnen alle informatie m.b.t. de standaard en het beheer daarvan inzien via de website en via verschillende kanalen issues of RFC&#39;s melden. Daarnaast kunnen community leden reageren op openbare consultaties en onder bepaalde voorwaarden deelnemen aan de Technische Architectuur Groep (zie paragraaf [deelname](#deelname)).

## Architectuur

De ADR standaard is een op zichzelf staande standaard en geen onderdeel van een bovenliggende standaard. Wel wordt er in de ADR verwezen naar verschillende andere (internationale) standaarden.

### Internationale, Europese en nationale standaardisatiegemeenschap

De ADR-Standaard volgt de ontwikkeling van internationale standaarden (zoals bijvoorbeeld de HTTP standaarden van het IETF) in het algemeen. Meer specifiek volgen de specialisten van Logius en de leden van de TAG de standaarden waarnaar wordt gerefereerd in de standaard en bespreken deze ontwikkelingen ook in het Technisch Overleg. Indien relevant worden op basis van de internationale ontwikkelingen rfc&#39;s opgesteld om de ADR-standaard aan te passen, verbeteren of actualiseren. Onderstaand is het overzicht overgenomen van de standaarden waaraan wordt gerefereerd in de ADR:

1. **[OPENAPIS]** <br>
[_OpenAPI Specification_](https://www.openapis.org/). Darrell Miller; Jeremy Whitlock; Marsh Gardiner; Mike Ralphson; Ron Ratovsky; Uri Sarid; Tony Tam; Jason Harmon. OpenAPI Initiative. URL: [https://www.openapis.org/](https://www.openapis.org/)
1. **[rfc3986]** <br>
[_Uniform Resource Identifier (URI): Generic Syntax_](https://datatracker.ietf.org/doc/html/rfc3986). T. Berners-Lee; R. Fielding; L. Masinter. IETF. January 2005. Internet Standard. URL: [https://datatracker.ietf.org/doc/html/rfc3986](https://datatracker.ietf.org/doc/html/rfc3986)
1. **[rfc5789]** <br>
[_PATCH Method for HTTP_](https://httpwg.org/specs/rfc5789.html). L. Dusseault; J. Snell. IETF. March 2010. Proposed Standard. URL: [https://httpwg.org/specs/rfc5789.html](https://httpwg.org/specs/rfc5789.html)
1. **[rfc7231]**<br>
[_Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content_](https://httpwg.org/specs/rfc7231.html). R. Fielding, Ed.; J. Reschke, Ed.. IETF. June 2014. Proposed Standard. URL: [https://httpwg.org/specs/rfc7231.html](https://httpwg.org/specs/rfc7231.html)
1. **[SemVer]**<br>
[_Semantic Versioning 2.0.0_](https://semver.org/). T. Preston-Werner. June 2013. URL: [https://semver.org](https://semver.org/)

### Samenwerking met andere beheerorganisaties

#### Kennisplatform API&#39;s

Kennisplatform API&#39;s is een initiatief van Geonovum, Bureau Forum Standaardisatie, Kamer van Koophandel, VNG Realisatie en Logius. Het doel van het Kennisplatform is om de kennis over het toepassen van API&#39;s uit te wisselen en de aanpak bij verschillende organisaties op elkaar af te stemmen en waar nodig te standaardiseren. In het kennisplatform wordt gezamenlijk gekeken naar strategische en tactische vraagstukken rond het ontwikkelen van API&#39;s door de overheid en gebruik van deze API&#39;s buiten en binnen de overheid. Dit vanuit de gedachte dat we in een digitale samenleving eenvoudig met elkaar moeten kunnen samenwerken.  

De ADR-standaard komt voort uit de Nederlandse API Strategie die beheerd wordt door het Kennisplatform API&#39;s en is door het kennisplatform ontwikkeld. Op het moment dat er in het kennisplatform consensus was over de kwaliteit van de ADR-standaard en de wenselijkheid deze via het &#39;pas toe of leg uit&#39; -principe normatief te laten verklaren is de standaard voorgedragen aan Forum Standaardisatie voor het verkrijgen van de voor overheden verplichte &#39;pas toe of leg uit&#39; status en heeft Logius het beheer van dit normatieve deel op zich genomen.  

Het kennisplatform API&#39;s blijft via haar werkgroep ADR actief met API Design Rules, maar richt zich primair op de ontwikkeling van extensies op de ADR. Deze extensies zijn bovendien (nog) niet normatief van aard. Logius heeft bij het beheer van de ADR-standaard nauw contact met het kennisplatform (en specifiek de werkgroep ADR) om zo te borgen dat wensen en issues m.b.t. de ADR bij beide partijen helder zijn en hier gezamenlijk de beste aanpak voor gekozen kan worden. (Zie ook h4).  

### Nederlandse Overheid Referentie Architectuur (NORA)  

De ADR-standaard volgt de principes van de Nederlandse Overheid Referentie Architectuur. Zie voor meer informatie: [https://www.noraonline.nl/wiki/NORA\_online](https://www.noraonline.nl/wiki/NORA_online)  

In de NORA is sinds 2017 het Thema API&#39;s opgenomen en beschreven. De NORA beschrijft met name wat een API is en waarom API&#39;s belangrijk zijn. Ook zijn er op de site aanbevelingen voor API&#39;s in de Enterprise Architectuur en de toepassing van API&#39;s in het ontwerp van een dienst.

### Overige belangrijke vermeldingen (zoals overlap met andere standaarden)  

#### OAuth (pas toe of leg uit standaard)

De API Design rules beschrijven zoals gezegd een set van richtlijnen om REST API&#39;s vorm te geven en toe te passen. Autorisatie van personen die API&#39;s raadplegen is nader uitgewerkt en beschreven in de OAuth standaard zoals gepubliceerd op [Logius-standaarden/OAuth-NL-profiel (github.com)](https://github.com/Logius-standaarden/OAuth-NL-profiel)).

#### Haal Centraal &amp; Common Ground (VNG)

Hoe API&#39;s daadwerkelijk dienen te functioneren en welke generieke, specifieke en meta functies API&#39;s moeten omvatten wordt o.a. door VNG gestandaardiseerd in de Haal Centraal initiatieven.

Een lijst van API&#39;s die in ontwikkeling zijn is te vinden op [VNG Realisatie (github.com)](https://github.com/VNG-Realisatie) Ook is er een belangrijk initiatief vanuit VNG Realisatie wat een drijvende kracht is achter de gezamenlijke ontwikkeling van standaard API&#39;s genaamd [Common Ground](https://commonground.nl/). Vanuit dit initiatief zijn standaard API voorzieningen ontwikkeld zoals een [Developer portaal voor de overheid](https://developer.overheid.nl/) en het [API Test Platform (api-test.nl)](https://api-test.nl/)

## Rechtenbeleid  

De ADR Standaard zelf en dit beheermodel vallen onder de Creative Commons licentie ([Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/)) Dit houdt in dat het is toegestaan om deze documenten te gebruiken, verder te verspreiden en aan te passen. Dit werk en de specificaties van de ADR-standaard worden royaltee-free ter beschikking gesteld. Organisaties en personen die bijdragen aan de ADR dienen dit onder dezelfde voorwaarden te doen als bij het originele werk. Door bij te dragen aan de ADR verklaren zij hiermee in te stemmen.

Uitgesloten van alle bovenstaande zijn rechten verbonden aan de standaarden, profielen en andere onderdelen waar de ADR gebruik van maakt. Hierop zijn de rechten van de betreffende standaarden, profielen en andere onderdelen zelf van toepassing. Dit zijn in geval van de ADR allemaal open standaarden.

## Kwaliteitsbeleid en benchmarking  

Zoals gezegd wordt het beheer van de ADR-standaard volledig open ingevuld (zie ook de paragraaf [Bomos](#bomos) en [Governance](#governance)) Dit borgt dat zoveel mogelijk belangstellenden en belanghebbenden betrokken zijn bij wijzigingen en besluitvorming die wijzigingen.

## Adoptie en erkenning  

De ADR-standaard heeft de &#39;pas toe of leg uit&#39; -status van Forum Standaardisatie. Dit betekent kort gezegd dat Nederlandse overheidspartijen en partijen uit de (semi) publieke sector deze standaard dienen toe te passen op het moment dat zij hun informatie met behulp van (REST) API&#39;s willen ontsluiten. Zie hoofdstuk 1 voor meer informatie.

