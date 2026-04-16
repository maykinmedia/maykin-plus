# Informatieblad bijdragen voor broncodebeheer 2026

*Voor producten waar Broncodebeheerder het broncodebeheer voor verzorgd*

Dit document bevat alle informatie rondom het broncodebeheer dat Broncodebeheerder verzorgt voor een aantal open source producten. De werkzaamheden en activiteiten voor het broncodebeheer zijn in ieders belang en de kosten worden gedekt door alle Gebruikers, in de vorm van bijdragen. Deze bijdragen vormen samen het doelbedrag en daarmee ook het budget voor de werkzaamheden. De werkzaamheden en de bijdragen die Gebruikers moeten betalen, staan in dit document.

## Definities

**Broncodebeheer**  
De werkzaamheden en activiteiten die horen bij het veilig en up-to-date houden van een open source applicatie, het onderhouden van de documentatie en het zorg dragen voor een gezond open source ecosysteem rondom het product.

**Broncodebeheerder**  
De hoofdontwikkelaar die de ontwikkeling leidt van het betreffende product en verantwoordelijk is voor het uitvoeren van de werkzaamheden en activiteiten die vallen onder Broncodebeheer.

**Doelbedrag**  
Het bedrag dat is vastgesteld en nodig is om invulling te geven aan de werkzaamheden en kosten voor het broncodebeheer.

**Eindgebruiker**  
Een Eindgebruiker wordt geteld als één afzonderlijke organisatie die ten minste één productie-installatie van het Product in gebruik heeft. Indien er sprake is van een (tussen)Leverancier die het Product (door)levert aan één of meerdere klanten, dan wordt iedere klant afzonderlijk geteld als Eindgebruiker. Het aantal productie-installaties van een enkele Eindgebruiker heeft geen invloed op de telling (bijvoorbeeld 2 afdelingen, met ieder hun eigen installatie van hetzelfde Product). 

**Gebruiker**  
De partij waarmee de broncodebeheer overeenkomst mee is afgesloten, zijnde een Eindgebruiker of een Leverancier. 

**Leverancier**  
Organisatie die het Product levert aan een Eindgebruiker.

**Product(en)**  
Een applicatie of registratie-component waar Broncodebeheerder de ontwikkeling van leidt en het broncodebeheer voor verzorgd.

**TPM-verklaring**  
Een Derdenverklaring of Third Party Mededeling (TPM) is een verklaring die afgegeven wordt door een onafhankelijk audit partij over de kwaliteit van een ICT-dienstverlening en -beheersing van een organisatie.

## Groeimodel

Een open source product veilig en up-to-date houden is vanaf de allereerste gebruiker nodig. Niet alleen voor die ene eerste gebruiker maar ook om het het product levend en aantrekkelijk te houden voor potentiële nieuwe gebruikers.

Een relatief nieuw open source product is anders dan product dat al langer bestaat. Een nieuw open source product heeft bijvoorbeeld:

* Weinig gebruikers,
* Een kleine of geen community,
* Een enkele aanbieder (vaak de ontwikkelaar),
* Geen externe bijdragen.

Het broncodebeheer kan daar ook op aangepast worden: Werkzaamheden en activiteiten kunnen geminimaliseerd worden terwijl het product toch veilig en up-to-date blijft. Denk bijvoorbeeld aan:

* Minder vaak releases uitbrengen,
* Minder actief op externe bijdragen of community vragen,
* Bugfixes scharen onder (door)ontwikkeling met ad-hoc budget.

Het broncodebeheermodel blijft hetzelfde maar er wordt een meetpunt geïntroduceerd om te bepalen in welke fase een product in het groeimodel zit. Als meetpunt hanteren we: Het aantal gebruikers dat het product in productie gebruikt, kortweg *eindgebruikers*. Het is zowel een eenvoudig te bepalen meetpunt en ook representatief voor welke werkzaamheden idealiter worden uitgevoerd.

Als het aantal activiteiten en werkzaamheden daalt, dalen ook de kosten. Dit wordt uitgedruk in het percentage van het doelbedrag (en daarmee de bijdrage) dat benodigd is.

| Fase              | # Eindgebruikers  | Kosten %  | Opmerkingen |
|---|---|---|---|
| 1. Opstarten      | 0 - 5             | 30 %      | Het minimale uit GIBIT 2025/2026 afdekken |
| 2. Groeien        | 6 - 29            | 60 %      | Instandhouding waarborgen en verbreden |
| 3. Opschalen      | 30+               | 100 %     | Meer community werkzaamheden t.b.v. groei |

De werkzaamheden zijn onderverdeeld in fasen. Sommige punten komen voor in meerdere fasen maar iets anders ingericht. Indien dit laatste het geval is, staat dat dikgedrukt aangegeven.

## Werkzaamheden

Om het broncodebeheer uit te voeren zijn de volgende werkzaamheden en activiteiten gedefinieerd, die Broncodebeheerder uitvoert op de Producten:

### Fase 1: Opstarten

1. invulling geven aan het team dat de werkzaamheden uitvoert,
2. zorg dragen voor de beschikbaarheid van de broncode en images (momenteel op Github en DockerHub),
3. minimaal **maandelijks** image en code beveiligingsscans uitvoeren en bevindingen oplossen,
4. gerapporteerde bugs valideren en beoordelen op prioriteit,
5. gevalideerde en geprioriteerde bugs oplossen in **het doorontwikkelingsproces**,
6. versiebeheer toepassen zoals uiteengezet in een versiebeleid,
7. een CI pipeline onderhouden inclusief geautomatiseerde testen met een testcoverage van 80% of hoger, teneinde de kwaliteit te waarborgen,
8. geschikte Helm charts publiceren voor het product,
9. actief meewerken om het product compliant te maken en houden met de relevante en toepasselijke standaarden,
10. het 'VNG groeipact' onderschrijven en bijdragen bij aan verbeteringen van VNG-standaarden,

### Fase 2: Groeien

Alle werkzaamheden en activiteiten uit fase 1 met aanvullend:

1. een openbare issue-tracker bijhouden die mogelijke bugs en suggesties van iedereen accepteert,
2. *(uitbreiding op 1.5)* gevalideerde en geprioriteerde bugs oplossen in **periodieke patch-releases (minimaal 4 keer per jaar)**,
3.	relevante documentatie bijhouden en openbaar beschikbaar maken,
4.	openbaar beschikbare release-notes bijhouden om o.a. gebruikers te helpen bij het upgraden,
5.	streven naar backwards compatibiliteit in kleine releases en daarmee installatie/implementatie-upgrades 
6.	zorg dragen voor compatibiliteit met de meest recente, grote, browsers,
7.	indien van toepassing, de Applicatie TPM-verklaring beschikbaar te stellen aan Broncodebeheerpartner, en deze – indien nodig, tegen kosten – op naam te laten zetten.

### Fase 3: Opschalen

Alle werkzaamheden en activiteiten uit fase 1 en 2 met aanvullend:

1. *(uitbreiding op 1.3)* minimaal **dagelijks** image en code beveiligingsscans uitvoeren en bevindingen oplossen,
2.	een responsible disclosure programma onderhouden, inclusief een e-mailadres voor beveiligingsproblemen,
3.	CVE's publiceren voor gevalideerde beveiligingsproblemen,
4.	*(uitbreiding op 2.2)* gevalideerde en geprioriteerde bugs oplossen in **periodieke patch-releases (minimaal 12 keer per jaar)**,
5.	koppelingen compatible houden met patches en minor versiewijzigingen in het betreffende koppelvlak (major versiewijzigingen vallen expliciet onder doorontwikkeling),
6.	contributies aan de open source codebase verwelkomen,
7.	contributies ("pull requests") monitoren op kwaliteit, veiligheid, herbruikbaarheid en architecturale fit,
8.	contributie richtlijnen opstellen en onderhouden,
9.	zorg dragen dat alle bijdragen voldoen aan de licentievoorwaarden van de Europese Unie Publieke Licentie (EUPL) versie 1.2 of hoger,
10.	een versie controlemechanisme voor productcode onderhouden,
12.	openbare mailinglijst bijhouden waarop gebruikers geïnformeerd worden over releases en relevant nieuws rondom het product,
vereenvoudigen,
13.	een compatibiliteitsmatrix bijhouden om devops- en implementatie-ontwikkelaars te ondersteunen bij hun werk,
14.	nieuwe gebruikers op weg helpen door gemakkelijk toegankelijke, eenvoudig te gebruiken voorbeelden beschikbaar te hebben,
15.	gebruikte componenten van derden ('afhankelijkheden' of 'software bibliotheken') bijhouden, beoordelen op kwaliteit, veiligheid, volwassenheid en naleving van de open source-licenties,
16.	minimaal eenmaal per jaar een bijeenkomst te organiseren voor alle broncodebeheerpartners die meedoen aan het broncodebeheer voor het product,
17.	inzetten om volledig compliant te zijn en blijven met de Standard for Public Code,
18. minimaal 3 maanden bugfixes toepassen op, en veiligheidsissues oplossen in, de vorige minor versie,
19. minimaal 6 maanden bugfixes toepassen op, en veiligheidsissues oplossen in, de vorige major versie,

Deze werkzaamheden kunnen enkel plaatsvinden mits het budget dit toelaat. Het is aan de product owner van het Product om dit in de gaten te houden, werkzaamheden te prioriteren en het doelbedrag later aan te passen.

## Staffel

Er wordt een staffel gehanteerd om de bijdragen naar rato te verdelen over alle gebruikers. Per categorie in de staffel wordt een gewicht toegekend, waarmee de spreiding van de doelbedrag wordt bepaald. De kosten voor de bijdrage zijn daarna per categorie bekend.

| Categorie | Omschrijving                              | Gewicht   |
|---|---|---|
| 1	        | Gemeente tot 25.000 inwoners              | 1         |
| 2	        | Gemeente tot 100.000 inwoners             | 2         |
| 3	        | Gemeente tot 200.000 inwoners             | 4         |
| 4	        | Gemeente met meer dan 200.000 inwoners    | 8         |
| A	        | Provincie                                 | 5         |
| B	        | Waterschap                                | 3         |
| C	        | Rijksoverheid                             | 10        |
| X	        | MKB-onderneming                           | 3         |
| Y	        | Grote onderneming                         | 8         |

Niet alle organisaties passen in de staffel. Als een organisatie niet in de staffel past, zal Broncodebeheerder de organisatie op een zo'n passend mogelijke plek in de staffel plaatsen.

Indien er geen gebruikers zijn in een bepaalde categorie, dan wordt deze categorie niet getoond bij het product.

## Doelbedrag

Om het doelbedrag te berekenen wordt per product gekeken naar de hieronder genoemde onderwerpen. De waarde bij elk onderwerp wordt bepaald door het ontwikkelteam en de product owner van het betreffende Product.

**Broncode complexiteit**  
De complexiteit van de broncode heeft invloed op de kans op issues en maakt issues typisch lastiger om te verhelpen. Een complexer product maakt broncodebeheer duurder.

* **Waarden**: A t/m F
* **Berekening naar FTE**: A=0,1, B=0,2, … F=0,6

**Aantal koppelingen**  
Koppelingen in het Product vormen een relatie naar externe koppelvlakken. Als de koppelvlakken wijzigen moet de koppeling in het Product ook worden bijgewerkt. Uitgangspunt is dat elke koppeling 1 wijziging heeft per jaar, waar 1 week capaciteit voor nodig is. 

* **Waarden**: 0 of hoger
* **Berekening naar FTE**: <waarde> / 52

**Developmentteam**  
Een groter developmentteam zorgt voor een sneller wijzigende codebase en meer kans op issues. Ook zijn er dan sneller meer wijzigingen op meer verschillende plekken. Een groter development team maakt het broncodebeheer duurder.

* **Waarden**: 0 tot 9
* **Berekening naar FTE**: <waarde> x 0,05

**Broncode grootte**  
De grootte van de broncode heeft invloed op het aantal issues dat kan optreden en hoe lang het duurt voordat de oorzaak van een issue gevonden en opgelost is. Hoe groter de broncode grootte, hoe duurder.

* **Waarden**: XS, S, … XL
* **Berekening naar FTE**: XS=0,05, S=0,1, … XL=0,25

**Aantal feature releases per jaar**  
Een feature release geeft overhead, zoals het opstellen van de release zelf, de changelog maken, volledig doortesten, mailings uitsturen. Patch releases kunnen ongelimiteerd plaatsvinden tellen niet mee in deze berekening. Uitgangspunt is 2 weken capaciteit van ontwikkelaars en testers, per release. Meer releases maakt het broncodebeheer duurder.

* **Waarden**: 0 tot 12
* **Berekening naar FTE**: <waarde> / 26


Het totale aantal FTE van bovenstaande onderwerpen wordt gedaan tegen een marktconform uurtarief van een ontwikkelaar.

### Additionele kosten

**PO-activiteiten per jaar**  
Dit bedrag wordt ingezet voor en door de product owner van het Product, voor bijvoorbeeld het organiseren van meetings, vragen beantwoorden en vormt de link naar het ontwikkelteam voor het deel dat wordt ingezet voor broncodebeheer. Dit kan per Product verschillen.

* **Waarden**: Bedrag in EUR.

**Tooling-kosten per jaar**  
Hier wordt allerhande tooling zoals Github, Dockerhub, test-runners, een playground-omgeving, security scanners, etc. van betaald. Dit kan per Product verschillen.

* **Waarden**: Bedrag in EUR.

  
## Producten

### Open Formulieren

* **Officiële code repository**: https://github.com/open-formulieren/open-forms/
* **Officiële image**: https://hub.docker.com/r/openformulieren/open-forms
* **Officiële Helm-chart**: https://github.com/maykinmedia/charts
* **Groeifase**: 3 / 3 (100%)
* **Vaststelling bijdragen**: 8 december 2025

Berekening doelbedrag op jaarbasis:

| Onderwerp                 | Waarde            |
|---|---|
| Broncode complexiteit	    | D                 |
| Aantal koppelingen	    | 12                |
| Developmentteam	        | 8,0               |
| Broncode grootte	        | Large             |
| Aantal feature releases	| 4                 |
| PO-activiteiten	        | EUR 40.000        |
| Toolingkosten	            | EUR 5.000         |
| **Doelbedrag**	        | **EUR 325.000**   |

Bijdrage per organisatie (bedrag door te berekenen aan Gebruiker):

| Categorie | Bijdrage per maand    |
|---|---|
| 1         | € 212                 |
| 2         | € 424                 |
| 3         | € 847                 |
| 4         | € 1.693               |

Totale bijdrage op jaarbasis:

| Categorie     | Aantal organisaties   | Bijdrage x Aantal organisaties    |
|---|---|---|
| 1             | 4                     | € 10.176                          |
| 2             | 28                    | € 142.464                         |
| 3             | 9                     | € 91.476                          |
| 4             | 4                     | € 81.264                          |
| **Totaal**    | **45**                | **€ 325.380**                     |

 
## Open Zaak

* **Officiële code repository**: https://github.com/open-zaak/open-zaak/
* **Officiële image**: https://hub.docker.com/r/openzaak/open-zaak
* **Officiële Helm-chart**: https://github.com/maykinmedia/charts
* **Groeifase**: 3 / 3 (100%)
* **Vaststelling bijdragen**: 8 december 2025

| Onderwerp                 | Waarde            |
|---|---|
| Broncode complexiteit	    | B                 |
| Aantal koppelingen	    | 1                 |
| Developmentteam	        | 1,0               |
| Broncode grootte	        | Medium            |
| Aantal feature releases	| 6                 |
| PO-activiteiten	        | EUR 10.000        |
| Toolingkosten	            | EUR 5.000         |
| **Doelbedrag**	        | **EUR 145.000**   |

| Categorie | Bijdrage per maand    |
|---|---|
| 1         | € 141                 |
| 2         | € 282                 |
| 3         | € 563                 |
| 4         | € 1.125               |

Totale bijdrage op jaarbasis:

| Categorie     | Aantal organisaties   | Bijdrage x Aantal organisaties    |
|---|---|---|
| 1             | 2                     | € 3.384                           |
| 2             | 14                    | € 47.376                          |
| 3             | 4                     | € 27.024                          |
| 4             | 5                     | € 67.500                          |
| **Totaal**    | **25**                | **€ 145.284**                     |


*Versie 3-concept (t.b.d.)*
