# Structuur van het toepassingsprofiel {#3F9A775E}
## DCAT als universeel vocabulaire {#09DBB0B1}
Het toepassingsprofiel in dit document is gebaseerd op de specificatie van de Data Catalog Vocabulary (DCAT), ontwikkeld onder verantwoordelijkheid van de Government Linked Data Working Group bij W3C. DCAT is een RDF-vocabulaire dat is ontworpen om interoperabiliteit tussen gegevenscatalogi gepubliceerd op het web te vergemakkelijken. Waar nodig worden aanvullende klassen en eigenschappen uit andere bekende vocabulaires hergebruikt.
<br/>
<br/>
Het DCAT vocabulaire bestaat uit klassen en eigenschappen.
<br/>
<br/>
<b>Klassen zijn dingen op het internet</b>: Ze hebben niet allemaal een URI, maar het wordt aanbevolen om ze van een URI te voorzien. Het zijn complexe dingen zoals een persoon, een organisatie, een dataset, een website of een downloadbaar databestand.
<b>Klassen hebben eigenschappen</b>: De eigenschappen zijn de attributen die deze dingen beschrijven. Sommige eigenschappen komen in meer dan één klasse voor, een titel bijvoorbeeld is een veel voorkomend attribuut. Andere eigenschappen zijn zeer gespecialiseerd, zoals een bestandsformaat dat alleen zinvol is voor een gegevensbestand.
<b>Eigenschappen kunnen eenvoudig of complex zijn</b>: sommige eigenschappen zijn klassen. Een organisatie kan bijvoorbeeld een website hebben. Of een dataset kan een data-uitgever hebben. Over het algemeen kan een klasse herkend worden aan de schrijfwijze: Een property naam begint met een kleine letter zoals dcat:dataset , terwijl een class begint met een hoofdletter zoals dcat:Dataset.
<br/>
<br/>
Klassen en properties worden gebruikt om de metadata op een gestructureerde manier aan te leveren.
## Overzicht Klassen {#1086A1F8}
Het volgende diagram geeft een overzicht van de basis functionaliteit van [[DCAT-3.0]]  en dient als startblok voor het begrijpen van de constructie. LET OP, er zijn dus meer klassen, eigenschappen en relaties dan weergegeven zoals te zien in klassen.
<br/>
<br/>
<span style='background-color: yellow;'>OPTIE. Korte beschrijving alle klasssen + schematische weergave.</span> Of DCAT-AP-3.0 overzicht
https://semiceu.github.io/DCAT-AP/releases/3.0.0/html/overview.jpg
<br/>
<br/>
<figure><img src='media/image3.svg' alt='Graphic 21501807' style='width: 100%;'></img>
<figcaption>[[DCAT-3.0]]   in het kort.</figcaption></figure>

## Optionaliteit {#5679FE7C}
DCAT-AP NL definieert vier niveaus van vereisten voor ontvangers en leveranciers van gegevens. Daarbij geldt dat de niveaus alleen gelden voor de leveranciers. Ontvangers MOETEN altijd in staat zijn om informatie over alle instanties van alle klassen en al hun eigenschappen te verwerken. In de volgende secties worden klassen en eigenschappen aangeduid als "verplicht", "aanbevolen", "optioneel" of conditioneel.. Deze termen hebben de volgende betekenis:
<br/>
<br/>
Verplichte eigenschap: een ontvanger MOET de informatie voor die eigenschap kunnen verwerken; een aanbieder MOET de informatie voor die eigenschap verstrekken.
Aanbevolen eigenschap: een ontvanger MOET de informatie voor die eigenschap kunnen verwerken; een aanbieder BEHOORT de informatie voor die eigenschap te verstrekken indien deze beschikbaar is.
Optionele eigenschap: een ontvanger MOET de informatie voor die eigenschap kunnen verwerken; een aanbieder MAG de informatie voor die eigenschap verstrekken, maar is daartoe niet verplicht.
Conditionele eigenschap: een ontvanger MOET de informatie voor die eigenschap kunnen verwerken; een aanbieder MOET de informatie voor die eigenschap verstrekken, indien de conditie van toepassing is.
<br/>
<br/>
In de gegeven context betekent de term "verwerken" dat ontvangers binnenkomende gegevens MOETEN accepteren en deze gegevens op transparante wijze aan applicaties en diensten moeten leveren. Het impliceert noch schrijft voor wat applicaties en diensten uiteindelijk met de gegevens doen (parseren, converteren, opslaan, doorzoekbaar maken, weergeven aan gebruikers, etc.).
<br/>
<br/>
De termen MOET, BEHOORT en MAG in dit document moeten worden geïnterpreteerd als in <a href='https://www.rfc-editor.org/info/bcp14' target='_blank'>BCP 14</a> [RFC2119] [RFC8174] als, en alleen als deze in hoofdletters zijn weergegeven, zoals hier getoond.
## Waardelijsten {#14786F8D}
In de metadata dienen de waarden uit de waardelijsten waarnaar verwezen wordt bij de element beschrijving, gehanteerd te worden. Dit zijn vaak de door de EU verplichte waardelijsten. Echter, niet elke waardelijst voorgesteld door DCAT-AP wordt toegepast voor DCAT-AP NL.
<br/>
<br/>
Deze waardelijsten zijn opgenomen in XXXX
### Thema’s en trefwoorden<b></b> {#71D2AE04}
Voor het vastleggen van thema's en trefwoorden in de metadata kan het  volgende onderscheid worden gehanteerd;
<br/>
<br/>
dct:subject wordt gebruikt voor onderwerpen, met of zonder URI
dcat:theme (sub-property of dct:subject) wordt gebruikt voor thema's uit een controlled vocabulary, die een URI hebben
dcat:keyword wordt gebruikt voor trefwoorden, die niet uit een controlled vocabulary komen en/of geen URI hebben. 
## Omschrijving eigenschappen {#64A3722D}
<b>Eigenschap:</b> Dit is de originele engelstalige naam zoals gebruikt in de W3C specificatie van <a href='https://www.w3.org/TR/vocab-dcat-2' target='_blank'><i>[[DCAT-3.0]]</i></a> en  <a href='https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/210' target='_blank'><i>[[</i><i>DCAT-AP-3.0</i><i>]] </i></a> 
<b>Definitie</b>: Dit is de Nederlandstalige definitie van de eigenschap.
<b>RDF-eigenschap (URI):</b> Dit is de (technische) naam van de eigenschap die van toepassing is voor de uitwisseling van de DCAT data.
<b>Bereik:</b> Beschrijft de mogelijke waarden van de eigenschap.
<b>Kardinaliteit</b>: Geeft aan of de eigenschap eigenschap 0, 1 of meerdere keren mag voorkomen. Hierbij wordt gebruik gemaakt van de schrijfwijze <code>x..y</code>, waarbij x het minimaal aantal voorkomens aangeeft en y het maximaal aantal. Bijvoorbeeld <code>1..n</code> geeft aan dat de eigenschap een of meer keer mag voorkomen. 
<b>Optionaliteit: Geeft aan  of een eigenschap verplicht, aanbevolen, optioneel of conditioneel  is. </b>
<b>Conditie:</b> Geeft de conditie aan in het geval de optionaliteit Conditioneel is. Bijvoorbeeld HighValueData set. 
<b>Gebruik / Toepassing (TBD):</b> Geeft instructies omtrent gebruik en achtergrond informatie
<b>Waardelijst</b>: Verwijzing naar de codelijsten die van toepassing zijn.
## Ondersteuning voor meertaligheid {#10B7B8F1}
Eigenschappen als <code>dct:title</code> en  <code>dct:description</code> kunnen waardes in verschillende talen bevatten. Voor elke vertaling wordt de eigenschap herhaalt met de toevoeging van een language tag om aan te geven in welke taal de waarde geschreven is. Elke taal mag slechts één keer voorkomen.
