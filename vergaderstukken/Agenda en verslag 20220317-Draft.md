# Agenda en Verslag 

Agenda en Verslag van de Werkgroep API Design Rules (dit omvat ook het Technisch Overleg (TO) van de Technische Architectuur Groep (TAG) inzake de API Design Rules Governance).
> dd 17-03-2022 - Online overleg via MS-Teams

## Deelnemers

- Pieter Dijkstra (Kadaster) - Voorzitter
- Martin van der Plas (Logius) - notulen
- Alexander Green (Logius)
- Edwin Wisse (Logius)
- Huub de Jong (Waterschap Vallei en Veluwe)
- Laura Rutte (BKWI)
- Johan Radder (Centric)
- Henri Korver (VNG)
- Jasper Roes (Kadaster)
- Joost Farla (Kadaster)
- Linda van den Brink (Geonovum)
- Martijn Blokker (Nationale Bibliotheek)

## Agenda

1. Opening en welkom
   1. Opening en welkom door de nieuwe voorzitter Pieter Dijkstra.

2. Mededelingen
   1. Intentieverklaring ondertekend (Toelichting Frank Terpstra of Martin van der Plas)
      - Zie de website van Geonovum [link](https://www.geonovum.nl/themas/kennisplatform-apis/intentie-overeenkomst)
   1. Doorontwikkeling testbaarheid Design Rules (toelichting martin van der Plas)
      - zie ook de [repository met de python scripts](https://github.com/VNG-Realisatie/api-test-platform-code/tree/master/src/vng/design_rules/tests/tasks/dr_20200709)  die de tests uitvoeren en [de visualisatie op developer.overheid.nl](https://developer.overheid.nl/apis/logius-cor/score-detail)
   1. Save the date: Op maandag 9 mei 2022  is er een seminar voor het kennisplatform API’s gepland.  Dit zal plaatsvinden in de Horeca Academie in Den Haag.
      - Het concept-programma is:
         - Ochtend        :      bijeenkomsten werkgroepen
         - Lunch
         - Middag        :        plenaire sessie
         - Borrel

3. Besluitvorming en producten van de subwerkgroepen:
   1. zie verslag
 
4. eerdere oproepen:
   1. Oproep aan de werkgroep: geef commentaar bij de issue's uit de openbare consultatie [Lijst issue's gefilterd](https://github.com/Geonovum/KP-APIs/issues?q=is%3Aopen+is%3Aissue+label%3AConsultatie)
   1. er wordt opgeroepen na te gaan welke rules men normatief op wil nemen.  

5. Rondvraag, nieuwe ontwikkelingen & wvttk 

## Verslag

3. Besluitvorming en producten van de subwerkgroepen:
- [Profielen en capabilities](https://github.com/Geonovum/KP-APIs/blob/master/Werkgroep%20API%20design%20rules/profielen.md) (trekker Jasper Roes)
   - De extensies gaan we labellen als modules zodat organisaties profielen/patronen op kunnen stellen waarbij ze de verplichte normatieve module uitbreiden met extra modules waaraan hun API's moeten voldoen. Zie ook de presentatie op https://github.com/Geonovum/KP-APIs/tree/master/Werkgroep%20API%20design%20rules/presentaties
   - De modules gaan worden geversioneerd op basis van SEMVER overeenkomstig de versionering van de Normatieve module. 
- [Tijdreizen](https://github.com/Geonovum/KP-APIs/blob/master/Werkgroep%20API%20design%20rules/tijdreizen.md) (trekker Tony Sloos) - uitwerking combineren met DIS Geo / SOR sessies en daarna extensie updaten
   - Geen reactie en update gehad tijdens dit overleg
- [Omgaan met relaties](https://github.com/Geonovum/KP-APIs/blob/master/Werkgroep%20API%20design%20rules/relaties.md) (voormalig put/patch/post/delete) (trekker Henri Korver)
   - Het onderzoek wat is gepubliceerd op https://github.com/Geonovum/KP-APIs/blob/master/API-strategie-extensies/ext-many-to-many-relations.md is kort doorgenomen en besproken.
   - Het is onduidelijk wat me met dergelijke achtergronden doen. Voorstel is om een folder achtergronden aan te maken waarin we research/best practices/opvattingen over andere standaarden/code/voorbeelden en andere zaken kunnen opnemen.
- [Geo](https://github.com/Geonovum/KP-APIs/blob/master/Werkgroep%20API%20design%20rules/geo.md) (trekker Linda van den Brink)
   - de vorderingen van de sub werkgroep zijn doorgenomen met behulp van de  presentatie op https://github.com/Geonovum/KP-APIs/tree/master/Werkgroep%20API%20design%20rules/presentaties
- [Normatieve Rules](https://github.com/Logius-standaarden/API-Design-Rules) (trekker Martin van der Plas)
   - Feature: Uitwerking Semantic versioning voor het Normatieve deel (Martin van der Plas)
   - Feature: Implicaties en testbaarheid Rules
   - Product roadmap: opleveren ADR v1.1
   - Feature: kleine tekstuele verbeteringen en verwerken feedback

* NB: Profielen en capabilities betreft de stuctuur wijziging "van extensies naar een modulaire opbouw van de NL API Design Rules"

