# Operationeel

## Initiatie

1. Uitbreidingen en aanpassingen in de API-standaarden komen tot stand door participatie van de verschillende belanghebbenden.
2. Belanghebbenden kunnen op vier manieren participeren: als lid van de API Community en/of de Technische Architectuur Groep en/of als lid van de Adviesraad of als lid van het OBDO.

## Wensen en Eisen

RFC&#39;s kunnen binnen komen via verschillende kanalen:

1. Rechtstreeks bij Logius, tijdens overleggen, via de website of mail
2. Bij de werkgroep ADR van het Kennisplatform API&#39;s, tijdens overleggen, via de website of mail

RFC&#39;s worden als issue&#39;s geregistreerd in de repository van het kennisplatform API&#39;s op Github. [https://github.com/Geonovum/KP-APIs/issues](https://github.com/Geonovum/KP-APIs/issues)

Om te voorkomen dat er verschillende lijsten met issues en verzoeken ontstaan, is met het kennisplatform API&#39;s afgesproken dat ieder issue en verzoek als eerste wordt beoordeeld door de werkgroep ADR van het kennisplatform API&#39;s. Dit voorkomt het ontstaan van verschillende stromen met RFC&#39;s en geeft de werkgroep de gelegenheid om in te schatten of de RFC betrekking heeft op de ADR-standaard die Logius beheert, of dat er sprake is van een verzoek dat het best kan landen in één van de (niet normatieve) extensies die het kennisplatform beheert.

Dit houdt concreet in dat RFC&#39;s die rechtstreeks bij Logius worden neergelegd, door Logius worden doorgespeeld aan de werkgroep ADR zodat daar de eerste beoordeling kan plaatsvinden.

![ADR RFC Procesmodel](media/ADR_Governance-RFC_Process.svg "ADR RFC Procesmodel")
> Figuur 5. ADR RFC Procesmodel

## Uitvoering en ontwikkeling (Wijzigingsproces)

De procedure van RCF naar daadwerkelijke wijziging ziet er als volgt uit:

- Issues die in behandeling worden genomen worden als RFC gelabeld
- RFC&#39;s worden besproken en uitgewerkt in de Werkgroep ADR
- RFC&#39;s worden vastgesteld in Technisch Overleg API&#39;s (TO)
- RFC worden na vaststelling in het TO Openbaar geconsulteerd
- Na vaststelling volgt publicatie van de nieuwe versie van standaard

> N.B. Zolang het Centrum voor Standaarden nog geen predicaat &quot;Uitstekend beheer&quot; heeft ontvangen van Forum Standaardisatie, zullen nieuwe versies na vaststelling in het TO aan Forum Standaardisatie worden voorgelegd ter beoordeling.  
> N.B.2. Het technisch overleg is momenteel samengevoegd met het structurele overleg van de werkgroep ADR van het Kennisplatform

Dit is schematisch weergegeven in het onderstaande ADR Governance model:  

![ADR Governance model](media/ADR_Governance_model.svg "ADR Governance model")
> Figuur 6. ADR Governance model

## Status van de standaard

Logius, Centrum voor standaarden onderscheid vier statussen die de ADR-standaard kan hebben:

| **Afkorting** | **Status van de standaard** | **Beschrijving van de status**                                      |
| :------------: | :----------------------------- | :-------------------------------------------------------------------  |
| IO             | In Ontwikkeling                | Een nieuwe release van de standaard is &quot;In Ontwikkeling&quot; wanneer er met medeweten en medewerking van participanten aan gewerkt wordt en wanneer dit onderdeel of deze release nog niet voor de buitenwereld is gepubliceerd.                                                   |
| IG             | In Gebruik                     | Als een nieuwe release van de standaard gereed is, en is bestendigd door Forum Standaardisatie, stelt het Technisch Overleg de status &#39;In Gebruik&#39; vast. Door deze vaststelling worden gebruikers en ICT-leveranciers opgeroepen deze nieuwe release op te nemen in software en in gebruik te nemen.                              |
| EO             | Einde Ondersteuning            | De standaardversie met de status &quot;Einde ondersteuning&quot; wordt niet meer ondersteund door de beheerder.<br>De kennis en informatie voor vragen en support is bij de beheerder niet langer beschikbaar.                                                                       |
| TG             | Teruggetrokken                 | De standaard krijgt de status &quot;Teruggetrokken&quot; indien een release van de standaard niet bruikbaar blijkt (bijv. vanwege implementatieproblemen).                                                             |

> Figuur 7. Mogelijke statussen van de standaard

## Documentatie

Alle documenten m.b.t. de standaard en het beheer van de standaard worden openbaar en zonder drempels voor gebruik, gepubliceerd op logius.nl en onze Github pagina&#39;s. Logius publiceert tenminste de volgende documenten:

- Dit ADR-beheermodel
- De vergaderstukken van het Technisch overleg en overige besluitvormende gremia.
- De specificaties van de standaard
- De voorlopige specificaties van de nieuwe versie van de standaard.

- Versie 1.0 van de ADR is gepubliceerd op:  
  - [https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0](https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0)  
- De laatste versie van de ADR is gepubliceerd op:  
  - [https://publicatie.centrumvoorstandaarden.nl/api/adr/](https://publicatie.centrumvoorstandaarden.nl/api/adr/)  
- De laatste concept versie van de standard is gepubliceerd op:  
  - [https://logius-standaarden.github.io/API-Design-Rules/](https://logius-standaarden.github.io/API-Design-Rules/)  
- Het beheermodel is gepubliceerd op:  
  - [Logius-standaarden/ADR-Beheermodel (github.com)](https://github.com/Logius-standaarden/ADR-Beheermodel)  
- De vergaderstukken zijn gepubliceerd op:  
  - [Logius-standaarden/ADR-Beheermodel/vergaderstukken (github.com)](https://github.com/Logius-standaarden/ADR-Beheermodel/tree/develop/vergaderstukken)  

