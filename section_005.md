# Klassen {#70D20715}
In dit hoofdstuk worden de belangrijkste klassen van het <u>applicatieprofiel</u> benoemd en beschreven. Deze klassen vormen de kern van het applicatieprofiel. De eigenschappen en de bijbehorende beperkingen die van toepassing zijn in de context van dit profiel worden in tabelvorm weergegeven. Elke rij komt overeen met één eigenschap. De eigenschappen worden in sub paragrafen verder toegelicht.
## Klasse: Dataset (dcat:Dataset) {#207F91CA}
<blockquote><p id='1257ECA2'>Subklasse van <span style='background-color: #clear;'>dcat:Resource</span><span style='color: #0000FF;'><u> </u></span></blockquote>

Een dataset is een zinvolle verzameling van samenhangende gegevens, die beheerd of gepubliceerd wordt door één organisatie,en in één of meer formaten beschikbaar of downloadbaar is. 
<br/>
<br/>
In tegenstelling tot een DataService wordt van een Dataset verwacht dat het een verzameling gegevens is die beschikbaar is voor toegang of download in een of meer formaten, als Distributies. Distributies die tot dezelfde Dataset behoren, mogen niet verschillen wat betreft het idee van de gegevens die ze vertegenwoordigen. Ze kunnen verschillen wat betreft de fysieke representatie van de gegevens, zoals formaat of resolutie. Of ze kunnen de gegevens van de dataset opsplitsen in porties van vergelijkbare grootte, zoals gegevens per tijdsperiode of locatie.
<br/>
<br/>
.
### access rights {#79154C4C}
Deze eigenschap bevat informatie die aangeeft of de dataset openbaar toegankelijk is, toegangsbeperkingen heeft of niet openbaar is.
<br/>
<br/>
Een waarde uit <a href='http://publications.europa.eu/resource/authority/access-right' target='_blank'>Access Rights Named Authority List</a> is verplicht. .
### applicable legislation {#65CE305D}
Deze eigenschap bevat de wetgeving die de creatie of het beheer van de dataset verplicht stelt. 
Er kunnen meerdere wetgevingen op de dataset van toepassing kunnen zijn. Denk aan HVD, INSPIRE, kaderrichtlijn water etc.
<br/>
<br/>
Gebruik de referentie naar de officiële publicatie van de wetgeving.
<br/>
<br/>
Voor HVD moet de waarde de ELI http://data.europa.eu/eli/reg_impl/2023/138/oj bevatten.
### conforms to {#149B1473}
Deze eigenschap bevat een verwijzing naar de vastgestelde standaard of specificatie waaraan de beschreven dataset voldoet. Hierbij kan worden gedacht aan het informatie model, dataspecificatie of schema.
<br/>
<br/>
Gebruik de referentie naar de officiële publicatie van de standaard of specificatie.
### contact point  {#08AAC765}
Deze eigenschap bevat de contactinformatie waar eindgebruikers contact kunnen opnemen met vragen over de dataset. Dit element bevat het e-mail adres of link (URL) naar het contactformulier van de verantwoordelijke organisatie van de dataset. Het e-mail adres is een functioneel e-mailadres van de organisatie of organisatie onderdeel.
### creator {#727282BD}
De organisatie die verantwoordelijk is voor het creëren van de beschreven dataset. Gebruik bij voorkeur een URI of anders een waarde uit een organisatienamenlijst. Als dat niet mogelijk is, gebruik de volledig uitgeschreven naam van de verantwoordelijke organisatie. De afkorting kan toegevoegd worden aan de organisatienaam.
<br/>
<br/>
Waardelijsten die gebruikt kunnen worden zijn bijvoorbeeld <a href='https://organisaties.overheid.nl/' target='_blank'><span style='color: #0000FF;'><u><span style='background-color: #clear;'>Register Overheid-Organisaties</span></u></span></a><span style='color: #1F2328;'><span style='background-color: #FFFFFF;'>, </span></span><a href='https://ror.org/' target='_blank'><span style='color: #0000FF;'><u><span style='background-color: #clear;'>Research Organization Registry (ROR)</span></u></span></a> of <a href='https://semiceu.github.io/Core-Business-Vocabulary/releases/2.1.0/' target='_blank'><span style='color: #0000FF;'><u><span style='background-color: #clear;'>Core Business Vocabulary (organisaties)</span></u></span></a>
### dataset distribution {#40631A31}
Een distributie is de werkelijke data van de dataset in een bepaald formaat of een bepaalde aanbiedingsvorm. Een dataset kan meerdere distributies hebben, bijvoorbeeld via een API of directe download in verschillende formaten.  
### Description {#2564CC1B}
Deze eigenschap bevat een beschrijving van de inhoud van de dataset. Deze is bij voorkeur minimaal drie zinnen en maximaal één alinea lang (2000 karakters). De vindbaarheid van de dataset wordt bepaald door de kwaliteit van de tekst. Denk hierbij aan verschillende gebruikers, vakgenoten maar ook anderen, waarvoor de tekst begrijpelijk moet zijn..
Om ervoor te zorgen dat eindgebruikers de datasets goed kunnen vinden is het belangrijk dat de tekst goede trefwoorden bevat.
<br/>
<br/>
Zie meertaligheid voor het omgaan met verschillende talen.
### documentation {#1B73DB94}
Een pagina of document over deze dataset met aanvullende informatie.
### frequency {#543948A6}
Een indicatie van de frequentie waarmee de dataset wordt ververst.
<br/>
<br/>
Gebruik hiervoor een waarde uit <a href='http://publications.europa.eu/resource/authority/frequency' target='_blank'>EU Vocabularies Frequency Named Authority List</a>
### geographical coverage <b></b> {#1256F1C8}
Het geografische gebied waarop de gegevens in de dataset betrekking hebben. Het veld kan worden gevuld met de benaming van een gebied in de vorm van een URI of de coördinaten ervan. 
De coördinaten zijn de meest westelijke, oostelijke, noordelijke en zuidelijke coördinaat uit de horizontale dekking van de dataset weergegeven in lattitude en longitude in decimale graden (noord en oost als positieve waarden). De coördinaten dienen te worden weergegeven volgens referentiesysteem WGS 84.
Voor de invulling van deze eigenschap met een gebiedsnaam, wordt vereist dat een van de onderstaande als mogelijk gebruik wordt gemaakt van <a href='https://vocabs.cbs.nl/nl/' target='_blank'>https://vocabs.cbs.nl/nl/</a> of anders van
GeoNames.org 
<br/>
<br/>
Gebruik hiervoor een waarde uit  <a href='http://publications.europa.eu/resource/authority/continent/' target='_blank'>EU Vocabularies Continents Named Authority List</a>, <a href='http://publications.europa.eu/resource/authority/country' target='_blank'>EU Vocabularies Countries Named Authority List</a>, <a href='http://publications.europa.eu/resource/authority/place/' target='_blank'>EU Vocabularies Places Named Authority List</a>, <a href='http://sws.geonames.org/' target='_blank'>Geonames</a>
### has version {#491E935F}
Een gerelateerde dataset die een versie, editie of aanpassing is van de beschreven dataset.
### HVD Category {#4727AA23}
Deze eigenschap bevat de HVD-categorie waartoe deze dataset behoort, als de dataset onder de HVD uitvoeringsverordening valt.
<br/>
<br/>
Gebruik hiervoor een waarde uit <a href='https://op.europa.eu/en/web/eu-vocabularies/dataset/-/resource?uri=http://publications.europa.eu/resource/dataset/high-value-dataset-category' target='_blank'>EU Vocabularies HVD Categories</a>.
### identifier  {#0F97C04D}
Identifier wordt gebruikt voor de unieke identificatie van de dataset. Dit is bij voorkeur een persistente URI die via HTTP raadpleegbaar is (resolvable). Hier wordt de oorspronkelijke identificatie van de dataset overgenomen zoals de data-eigenaar deze gepubliceerd heeft. De identifier  mag niet door afnemers aangepast worden.
De eventuele andere identifiers worden in de eigenschap other identifier opgenomen, zoals bijvoorbeeld identifiers die door een catalog worden toegekend. 
<br/>
<br/>
Identifier heeft de beperking (ten opzichte van DCAT-AP) dat deze eigenschap alleen de waarde kan bevatten die de eerste eigenaar heeft gegeven.
### in series {#3B756281}
Een datasetreeks waarvan de dataset deel uitmaakt.
### is referenced by {#5BACFFDD}
Een gerelateerde bron, zoals een publicatie, die verwijst naar, citeert of anderszins verwijst naar de dataset.
### keyword  {#5D9B3DD6}
Deze eigenschap bevat in het algemeen gebruikte woorden of geformaliseerde zinnen om een dataset of datasetserie te beschrijven, die niet uit een controlled vocabulary komen.
<br/>
<br/>
Het is mogelijk om meerdere keywords toe te kennen aan een dataset. Deze waarden moeten in afzonderlijke voorkomens van deze eigenschap worden aangeleverd.
<br/>
<br/>
Theme word gebruikt voor trefwoorden die uit een controlled vocabulary komen.
### landing page {#46068BAF}
De webpagina die toegang geeft tot de dataset en aanvullende informatie verschaft over de dataset. Het gaat hierbij om de originele webpagina van de data-eigenaar.
### language  {#2E4241AA}
De natuurlijke taal van de tekstuele waardes in de dataset. Niet alle data heeft de eigenschap taal, bijvoorbeeld images.
<br/>
<br/>
Gebruik van de waardelijst  <a href='http://publications.europa.eu/resource/authority/language' target='_blank'>EU Vocabularies Languages Named Authority List</a> is vereist.
<br/>
<br/>
Language heeft de beperking (ten opzichte van DCAT-AP) dat deze eigenschap alleen de waarde kan bevatten van de taal van de tekstuele waardes in de dataset.
### modification date {#15D6E4CF}
De meest recente datum waarop de dataset is gewijzigd of aangepast.
<br/>
<br/>
Gebruik altijd een datum en tijd conform de ISO-8601 notatie.
### other identifier {#4A3C9337}
in de eigenschap other identifier, kunnen eventuele overige identifiers in aanvulling op de  identifier worden opgenomen, zoals identifiers die door een catalog worden toegekend. Eventueel kan naast de waarde van de identifier zelf, ook worden opgenomen wie deze toevoeging gedaan heeft. Hierdoor ontstaat een lijst met equivalente identifiers.
<br/>
<br/>
Het gebruik van other identifier wordt (ten opzichte van DCAT-AP) verder gespecificeerd, secundaire identifiers, zijn ook alle identifiers die aan de dataset zijn toegewezen tijdens het verwerken en delen van die dataset in het catalogusnetwerk.
### provenance  {#4EDCEAE0}
Een verklaring van alle wijzigingen in eigendom en bewaring van een dataset sinds de creatie ervan, die van belang zijn voor de authenticiteit, integriteit en interpretatie ervan.
### publisher {#61E26A2D}
De organisatie die verantwoordelijk is voor de publicatie van de dataset. 
<br/>
<br/>
Voor Europese instellingen en een klein aantal internationale organisaties moet de  <a href='http://publications.europa.eu/resource/authority/corporate-body' target='_blank'>EU Vocabularies Corporate bodies Named Authority List</a> worden gebruikt. 
<br/>
<br/>
Bij andere soorten organisaties moeten nationale, regionale of lokale woordenlijsten worden gebruikt, zoals bijvoorbeeld <a href='https://organisaties.overheid.nl/' target='_blank'>Register Overheid-Organisaties</a>, <a href='https://ror.org/' target='_blank'>Research Organization Registry (ROR)</a> of <a href='https://semiceu.github.io/Core-Business-Vocabulary/releases/2.1.0/' target='_blank'>Core Business Vocabulary (organisaties)</a>
### qualified attribution {#22DC9D59}
Een organisatie, anders dan contact point, creator of publisher die ook een verantwoordelijkheid draagt voor de dataset.
<br/>
<br/>
In de eigenschap prov:hadRole wordt de rol van de organisatie gespecificeerd. Hiervoor kan worden gekozen uit de ISO-waardelijst ISO-19115 RoleCode.
### qualified relation {#2248BDDC}
Een beschrijving van een relatie met een andere bron.
### related resource {#4283C86F}
Een gerelateerde bron.
### release date {#30D90039}
De datum van formele uitgifte (bijvoorbeeld publicatie) van de dataset.
<br/>
<br/>
Gebruik altijd een datum en tijd conform de ISO-8601 notatie
### sample  {#38F97C4B}
Een voorbeeld distributie van de dataset.
### source {#60A871F2}
Een gerelateerde dataset waarvan de beschreven dataset is afgeleid.
### spatial resolution {#25FAE795}
De meest precieze ruimtelijke resolutie in de dataset, gemeten in meters. Bij het publiceren van meerdere distributies van dezelfde dataset, elk met een verschillende resolutie - bijvoorbeeld de NUTS.status, kan deze eigenschap meerdere keren voorkomen.
### status {#2088D371}
De status van de dataset in de context van de levenscyclus.
<br/>
<br/>
Gebruik hiervoor een waarde uit  <a href='http://publications.europa.eu/resource/authority/distribution-status' target='_blank'>EU Vocabularies Distribution Status</a>  
### temporal coverage {#1378B0BD}
De tijdsperiode waar de dataset betrekking op heeft. 
### temporal resolution {#35A42546}
De meest precieze tijdsperiode in de dataset. Bij het publiceren van meerdere distributies van dezelfde dataset, elk met een verschillende resolutie kan deze eigenschap meerdere keren voorkomen.
### theme {#1E66B192}
Deze eigenschap bevat de categorie van de dataset. De waarde die voor deze eigenschap moeten worden gebruikt, is in ieder geval één URI van een concept uit <a href='http://publications.europa.eu/resource/authority/data-theme' target='_blank'>Dataset Theme Vocabulary  </a>
<br/>
<br/>
Aanbevolen wordt om naast een waarde uit de europese Dataset Theme Vocabulary ook in meerdere thema's waarden op te nemen uit domeinspecifieke vocabulaires.
<br/>
<br/>
Echter is op Europees niveau is nog een discussie gaande of naast een waarde uit Dataset Theme Vocabulary, waarden uit andere controlled vocabulary in deze of een andere eigenschap opgenomen kunnen worden. 
<br/>
<br/>
<a href='https://github.com/SEMICeu/DCAT-AP/issues/316' target='_blank'>https://github.com/SEMICeu/DCAT-AP/issues/316</a>: Add guidance on usage of additional themes for datasets
<br/>
<br/>
keyword word gebruikt voor trefwoorden die niet uit een controlled vocabulary komen.
### title {#4A2D5898}
De naam van de beschreven dataset. 
<br/>
<br/>
Een gebruiker moet op basis van de naam van de dataset (titel) deze snel kunnen identificeren. Een meer uitgebreide omschrijving van de dataset dient u op te nemen in de eigenschap description. Wanneer er verschillende versies van een dataset in de meta-informatie opgenomen worden, is het aan te raden om de verschillende versienummers overal op dezelfde manier in de titel van de dataset te verwerken. Aanbevolen schrijfwijze voor deze eigenschap is: (projectkenmerk) onderwerp (locatiekenmerk) (tijdskenmerk) (versie). Hierbij zijn de onderdelen tussen haakjes niet verplicht, de andere wel. Afkortingen zijn in de titel enkel toegestaan indienen deze tevens zijn uitgeschreven bijvoorbeeld: “Grootschalige Basiskaart Nederland (GBKN)”.
<br/>
<br/>
Deze eigenschap kan alleen meerdere keren worden opgenomen om de naam in andere talen weer te geven.  Zie meertaligheid voor het omgaan met verschillende talen.
### type {#2831B8D6}
Een type dataset. Er wordt gediscussieerd over een aanbevolen waardelijst.
### version {#2CA10D09}
De versie-indicator (naam of identificatie) van een bron.
### version notes {#1597E9D6}
Een beschrijving van de verschillen tussen deze versie en een eerdere versie van de dataset.
### was generated by {#5FEB19E2}
Een activiteit die de creatie van de dataset heeft gegenereerd of de zakelijke context daarvoor biedt.
### Voorbeelden {#061A2544}
#### Minimale set van eigenschappen {#34145E8C}
Onderstaand voorbeeld beschrijft een <code>dcat:Dataset</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>dcat:Dataset</code>.
<br/>
<br/>
<aside class='example'><p id='5F0114C7'>Voorbeeld 1: Minimale set van eigenschappen<pre class="text">&lt;https:∕∕data.overheid.nl∕dataset∕verkiezingsuitslag-tweede-kamer-2021&gt;a dcat:Dataset;    dct:identifier &lt;https://data.overheid.nl/dataset/verkiezingsuitslag-tweede-kamer-2021&gt;;    dct:title "Verkiezingsuitslag Tweede Kamer 2021"@nl;    dct:description "De dataset bevat de uitslagen van de verkiezing voor de Tweede Kamer van 17 maart 2021. De data is beschikbaar gesteld in EML formaat. De Kiesraad biedt geen ondersteuning voor het gebruik van het formaat. Bestemmingspagina: https://www.kiesraad.nl/verkiezingen/osv-en-eml/eml-standaard"@nl;    dct:license &lt;http://creativecommons.org/publicdomain/zero/1.0/deed.nl&gt;;    dct:creator &lt;http://standaarden.overheid.nl/owms/terms/Kiesraad&gt;;    dct:publisher &lt;http://standaarden.overheid.nl/owms/terms/Kiesraad&gt;;    dcat:contactPoint [a vcard:Organization ;        vcard:fn "Kiesraad";        vcard:hasEmail "kiesraad@kiesraad.nl";        ];    dcat:theme &lt;http://standaarden.overheid.nl/owms/terms/Parlement&gt;;.</pre>

</aside>

#### Niet publieke datasets {#4EFD3AE5}
TODO: Access rights, licentie, vertaling, legal foundation.
<br/>
<br/>
<aside class='example'><p id='128E62B0'>Voorbeeld 2: Minimale set van eigenschappen<pre class="text">&lt;https:∕∕data.overheid.nl∕dataset∕reisdocumenten--registers&gt;a dcat:Dataset;    dct:identifier &lt;https://data.overheid.nl/dataset/reisdocumenten--registers&gt;;    dct:title "Reisdocumenten, registers"@nl;    dct:title "Reisdocumenten, registers"@en;    dct:description "Basisregister reisdocumenten (BRR), verificatieregister (VR), Register. Deze dataset is niet beschikbaar voor hergebruik. De reden hiervoor is benoemd in art. 10 van de Wet Openbaarheid Bestuur: ‘De eerbiediging van de persoonlijke levenssfeer’"@nl;    dct:license &lt;http://standaarden.overheid.nl/owms/terms/geslotenlicentie&gt;;    dct:accessRights &lt;placeholder/PRIVACY&gt;;    dct:creator &lt;http://standaarden.overheid.nl/owms/terms/rvig&gt;;    dct:publisher &lt;http://standaarden.overheid.nl/owms/terms/rvig&gt;;    dcat:contactPoint [a vcard:Organization ;        vcard:fn "Rijksdienst voor Identiteitsgegevens";        vcard:hasEmail "info@rvig.nl";        ];    dcat:theme &lt;http://standaarden.overheid.nl/owms/terms/Bestuur&gt;;.</pre>

</aside>

#### Temporal coverage {#0E754346}
<aside class='example'><p id='56D783F4'>Voorbeeld 3: Temporal coverage<p id='7DCF2ABB'>Voorbeeld <a href='file:///C:\Users\g.wolbers\Desktop\(https:\www.w3.org\TR\vocab-dcat-2\' target='_blank'>overgenomen van het W3C</a>:<pre class="text">&lt;ds257&gt; a dcat:Dataset ;    dct:temporal [ a dct:PeriodOfTime ;    dcat:startDate "2016-03-04"^^xsd:date ;    dcat:endDate   "2018-08-05"^^xsd:date ;    ].</pre>

</aside>

## Distributie (dcat:Distribution) {#73DFC2AC}
Een distributie beschrijft hoe een (deel van) een dataset te verkrijgen is. Meestal gaat het over een download-bestand. Verschillende distributies van dezelfde dataset verschillen van elkaar in o.a. taal, formaat, data-schema's en nauwkeurigheid (resolutie).
De aanbieder van een dataset kan distributies aanbieden in meerdere verschillende formaten en/of samenstellingen die zijn afgestemd op de behoeften van afnemers. Deze worden elk als afzonderlijke distributie beschreven en gerelateerd aan de dataset.
Als een dataset (ook) wordt aangeboden in de vorm van een webservice kunnen hierover aanvullende gegevens worden opgenomen in een <span style='background-color: #clear;'>dcat:DataService</span>. Deze kan worden gerelateerd aan de bijbehorende distributie.
De distributie geeft aan dat er gegevens van een dataset beschikbaar zijn. Dat kan zijn via een directe download, een API of een webpagina. Een waarde in de eigenschap <span style='background-color: #clear;'>dcat:downloadURL</span> geeft aan dat de gegevens in de distributie direct gedownload kunnen worden.
In het <a href='https://dcat-ap-donl.readthedocs.io/en/latest/' target='_blank'><i>DCAT-AP-DONL 1.1</i></a> werden zowel de download-bestanden als de webservices om de data op te vragen, in de vorm van een distributie beschreven. Het nieuwe toepassingsprofiel biedt mogelijkheid om webservices te beschrijven in de klasse <span style='background-color: #clear;'>dcat:DataService</span>. Deze heeft nu de voorkeur. Het blijft echter mogelijk en toegestaan om webservices te beschrijven als distributie.
<br/>
<br/>
INVOEGEN SHACL TABEL: Normatief Tabel met overzicht alle propertjes per klasse.  
<br/>
<br/>
INVOEGEN: voorbeeld
### accessURL {#1D7327C1}
Het web-adres (URL) van de site die toegang verschaft tot de data, aan de hand van bijvoorbeeld een webformulier, een zoekopdracht of een API-call. Het is niet vereist dat dit adres een directe link naar de data is. Hier mag ook verwezen worden naar een landings-pagina die de link naar de data aanbiedt. Er kan in dat geval met <span style='background-color: #clear;'>dcat:downloadURL</span> een directe link naar de data aangeboden worden.
Wanneer de data via een <span style='background-color: #clear;'>dcat:DataService</span> wordt aangeboden, dan staat in deze eigenschap de volledige API-call waarmee de data uit de service gehaald kan worden. Met <span style='background-color: #clear;'>dcat:accessService</span> wordt dan de link gemaakt met de <span style='background-color: #clear;'>dcat:DataService</span>.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='note'><p id='585BDF10'>Gebruik altijd het HTTPS-protocol voor webadressen! Zie ook <a href='https://www.forumstandaardisatie.nl/open-standaarden/https-en-hsts' target='_blank'><i>HTTPS en HSTS</i></a>.</aside>

### format {#578954DC}
Informatie over het bestandsformaat van de distributie volgens de indeling van het publicatiebureau van de EU.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='issue'><p id='486979A3'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/8' target='_blank'>I<span style='color: #0000FF;'><u>ssue 8</u></span></a><span style='color: #0000FF;'><u>:</u></span> Verschil tussen dct:format en dcat:mediaType <a href='https://github.com/dataoverheid/dcat-ap-donl/issues/?q=is%3Aissue+is%3Aopen+label%3A%22Respec%22' target='_blank'><span style='background-color: #clear;'>Respec</span></a><p id='116C4E6A'>Distributie heeft eigenschappen dct:format en dcat:mediaType. Voor dcat:mediaType wordt verwezen naar de waardelijst van IANA, zie <a href='https://www.iana.org/' target='_blank'>https://www.iana.org/</a><p id='0308F714'>Is het nodig om beide eigenschappen op te nemen?</aside>

### title {#09FB6115}
De titel is belangrijk voor de herkenbaarheid van een distributie, dus kies deze zorgvuldig. Zie meertaligheid** voor het omgaan met verschillende talen.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='71F26F65'>Zie ook <span style='background-color: #clear;'>dct:title</span> van <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

### description {#7CA857EB}
Een beschrijving van de distributie in aanvulling op de titel, waarmee eindgebruikers een goed beeld krijgen welke gegevens in de Distributie aanwezig zijn. Samen zijn deze het belangrijkste waarmee een gebruiker een distributie kan beoordelen, dus kies deze zorgvuldig. Zie meertaligheid voor het omgaan met verschillende talen.
Voor overige informatie over de Distributie is de eigenschap Documentation beschikbaar, waarin naar aanvullende webpagina's verwezen wordt.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='3C859A81'>Zie ook <span style='background-color: #clear;'>dct:description</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

### license {#6C85098C}
De formele of wettelijke toestemming waaronder de gegevens in de distributie (her)gebruikt mogen worden. Een licentie zegt iets over het intellectuele eigendom. Gebruik in het geval van openbaar toegankelijke gegevens (dct:accessRights) , een <a href='https://creativecommons.nl/uitleg/' target='_blank'>Creative Commons licentie</a>. In het geval de gegevens niet of onder voorbehoud toegankelijk zijn, is er sprake van een ‘niet-open’ licentie. Aanbevolen wordt om steeds de meest recente versie van een licentie te gebruiken. 
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='2AB2BBC3'>Zie ook <span style='background-color: #clear;'>dct:license</span> in <span style='background-color: #clear;'>dcat:Resource</span>. </blockquote>

### accessService nieuw {#25DA049A}
Alleen van toepassing wanneer de distributie via een dataservice bereikbaar is. De dataservice biedt dan toegang tot het bestand of de bestanden van deze distributie. Access service wordt niet ingevuld als de toegang tot de distributie. Dit kan in <span style='background-color: #clear;'>dcat:accessURL</span>
Deze eigenschap is nieuw in DCAT2 en biedt aanbieders van datasets de mogelijkheid om extra informatie te verstrekken over datasets die via een dataservice worden aangeboden.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### downloadURL {#3804E62E}
De URL waarmee eindgebruikers het bestand direct kunnen downloaden in een van de beschikbare formaten. Dit formaat wordt aangegeven in de distributie in eigenschap <code>dct:format</code> en/of <code>dcat:mediaType</code>.
Wanneer <code>dcat:accessURL</code> al de directe link naar de data aanbiedt, hoeft deze eigenschap niet ingevuld te worden.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### modified {#54091389}
De datum waarop de data-eigenaar de distributie voor het laatst heeft gewijzigd. Dat geldt zowel voor een wijziging van de inhoud van de distributie als voor de metadata van de distributie. Deze eigenschap moet een datum en tijd bevatten conform de <a href='https://www.iso.org/iso-8601-date-and-time-format.html' target='_blank'><i>ISO-8601</i></a> standaard.
Bij de eerstvolgende wijziging wordt de oude wijzigingsdatum overschreven.
Als de gegevens automatisch periodiek worden aangepast hoeft deze waarde niet telkens gewijzigd te worden. Gebruikers kunnen dan uitgaan van de waarde van <span style='background-color: #clear;'>dct:accrualPeriodicity</span> die in de bovenliggende <code>dcat:Dataset</code> is opgenomen.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
Issue Test. Dit is een niewu issue dat middel tekssort issue is toegvoegd
<aside class='example'><p class='space-after' id='415AC241'>Noot test. Dit is een nieuwe noot die is toegvoegd. Voorbeeld test. Dit een een voorbeel dat als test is toegvoegd</aside>

<br/>
<br/>
<blockquote><p class='space-after' id='2E4BAE91'>Zie ook <span style='background-color: #clear;'>dct:modified</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

<aside class='issue'><p id='41C2962A'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/4' target='_blank'><span style='color: #0000FF;'><u>Issue 4</u></span></a>: Property: update/modification date in Distributie: Verplicht of Aanbevolen? <a href='https://github.com/dataoverheid/dcat-ap-donl/issues/?q=is%3Aissue+is%3Aopen+label%3A%22question%22' target='_blank'><span style='background-color: #clear;'>question</span></a><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/?q=is%3Aissue+is%3Aopen+label%3A%22Respec%22' target='_blank'><span style='background-color: #clear;'>Respec</span></a><p id='16E69EE6'>Het "update/modification date" veld is belangrijk om de kwaliteit van de aangeboden distributie te kunnen inschatten: Een oude dataset heeft minder waarde dan een nieuwere. Ook kan deze eigenschap niet worden afgeleid.<br/>
Dus het lijkt passend om op zijn minst deze property "aanbevolen" te maken.<br/>
Maar zijn er bezwaren om de property verplicht te maken? Zou dat leiden tot uitvak van datasets? Uitval lijkt op te lossen met een beschrijving hoe het veld in te vullen als de distributie er geen waarde voor heeft.</aside>

### issued {#7EA0F563}
De datum waarop de data-eigenaar de distributie voor de eerste keer heeft gepubliceerd. Deze eigenschap moet een datum en tijd bevatten conform de <a href='https://www.iso.org/iso-8601-date-and-time-format.html' target='_blank'><i>ISO-8601</i></a> standaard.
Als tijd niet bekend is, kan hier de tijd 00:00:00 worden ingevuld. Wanneer er geen tijdzone wordt opgegeven wordt er automatisch uitgegaan van de Nederlandse tijd.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='00690FDB'>Zie ook <span style='background-color: #clear;'>dct:issued</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

### language {#5991EAC5}
De natuurlijke taal van de gegevens in de distributie.
Niet alle data die aangeboden wordt is taalgebonden (denk aan cijfers, statistieken etc.), om deze reden is deze eigenschap optioneel. Zie meertaligheid voor het omgaan met verschillende talen.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='2E1004E4'>Zie ook <span style='background-color: #clear;'>dct:language</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

<aside class='issue'><p id='37986723'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/11' target='_blank'><span style='color: #0000FF;'><u>Issue 11</u></span></a>: Verschillende talen <a href='https://github.com/dataoverheid/dcat-ap-donl/issues/?q=is%3Aissue+is%3Aopen+label%3A%22Respec%22' target='_blank'><span style='background-color: #clear;'>Respec</span></a><p id='6CB9680E'>De W3C maakt het mogelijk om de metadata zoals titel en beschrijving vast te leggen in verschillende talen. Op data.overheid.nl is nu maximaal een taal mogelijk.<p id='1FD9BFB9'>Daarnaast is het mogelijk om de taal aan te geven van de dataset zelf.<p id='7F9CDF90'>De EU biedt ook de mogelijkheid om daarnaast ook apart de taal van de distributie aan te geven.<p id='4039A2D4'>Wat is hier precies gewenst?</aside>

### rights {#7E28813E}
De overige gebruiksrechten die niet worden gedekt met <span style='background-color: #clear;'>dct:license</span>, zoals de copyright-statements. Deze eigenschap kan bijvoorbeeld gebruikt worden om aan te geven hoe de attributie moet plaatsvinden wanneer bij <span style='background-color: #clear;'>dct:license</span> een CC-BY licentie is gekozen.
Voor iedere taal kan één aparte rights-statement worden opgenomen die wordt aangeduid door een "language tag" achter de literal te plaatsen. Zie meertaligheid voor het verder omgaan met verschillende talen.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<blockquote><p id='340279E7'>Zie ook <span style='background-color: #clear;'>dct:rights</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

### byteSize {#5E0B565A}
De omvang van de distributie (het feitelijke bestand) in bytes. Deze eigenschap is alleen relevant wanneer de grootte van het bestand bekend is. Wanneer het bijvoorbeeld om realtime (of near-realtime) data gaat, die dus op elk moment kan veranderen, dan is de grootte minder goed te voorspellen. In dat geval is het aan te bevelen om deze eigenschap niet in te vullen.
Uiteraard is een negatieve omvang niet mogelijk. De waarde moet dus 0 of hoger zijn.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### conformsTo  {#2B08C202}
Een vastgestelde standaard waaraan de data in de distributie voldoet. Deze property kan meerdere keren voorkomen. Wanneer een andere eigenschap al beschrijft dat er aan een standaard wordt voldaan, dan hoeft deze niet nog een keer opgenomen te worden in deze eigenschap (bijvoorbeeld de bestandsformaat-standaard wordt al gedekt via <code>dct:format</code>).
De gebruikte standaard kan heel divers zijn en verschillen per context. Denk bijvoorbeeld aan een standaard die beschrijft hoe de gegevens in de dataset zijn verzameld. Of aan een standaard hoe de gegevens zijn gecodeerd, of hoe de gegevens in een model passen, of welke representatie of view deze gegevens van het geheel bevatten, et cetera.
Verwijs naar standaarden door middel van een HTTPS adres.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='note'><p id='5AFBE839'>Gebruik altijd het HTTPS-protocol voor webadressen! Zie ook <a href='https://www.forumstandaardisatie.nl/open-standaarden/https-en-hsts' target='_blank'><i>HTTPS en HSTS</i></a>.</aside>

<blockquote><p id='0D08BA90'>Zie ook <span style='background-color: #clear;'>dct:conformsTo</span> in <span style='background-color: #clear;'>dcat:Resource</span>.</blockquote>

### mediaType {#22E9D059}
Informatie over de bestandsindeling (of MIME-type) van de distributie, volgens de indeling van <a href='https://www.iana.org/assignments/media-types/media-types.xhtml' target='_blank'><i>IANA Mediatypes</i></a>.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='issue'><p id='6E984AD8'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/8' target='_blank'><span style='color: #0000FF;'><u>Issue 8</u></span></a>: Verschil tussen dct:format en dcat:mediaType <a href='https://github.com/dataoverheid/dcat-ap-donl/issues/?q=is%3Aissue+is%3Aopen+label%3A%22Respec%22' target='_blank'><span style='background-color: #clear;'>Respec</span></a><p id='637C344E'>Distributie heeft eigenschappen dct:format en dcat:mediaType. Voor dcat:mediaType wordt verwezen naar de waardelijst van IANA, zie <a href='https://www.iana.org/' target='_blank'>https://www.iana.org/</a><p id='2EEF8DA5'>Is het nodig om beide eigenschappen op te nemen?</aside>

### checksum {#3719CFB4}
Met een checksum of controlegetal kan een afnemer eenvoudig vaststellen of een gedownload bestand identiek is aan het aangeboden bestand (en er dus geen problemen zijn ontstaan bij het downloaden of wijzigingen zijn geweest aan de data zelf).
De <code>spdx:Checksum</code> klasse bevat naast de berekende checksum-waarde ook een eigenschap die het gebruikte algoritme aangeeft. Hiervoor is een waardelijst opgezet.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
Het invullen van de klasse <code>spdx:Checksum</code> kan op de volgende manier. Voor een voorbeeld zie voorbeeld checksum.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 30.244590780809034%;'>
<col id='col2' style='width: 50.04703668861712%;'>
<col id='col3' style='width: 19.708372530573847%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='66C0DCAB'>URI</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='0FDE7493'>Range</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='642AE6D2'>Kardinaliteit</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>spdx:algorithm</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='662F937C'>waardelijst spdx:ChecksumAlgorithm</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>spdx:checksumValue</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='60D21F1E'><code>rdfs:Literal</code> typed as <code>xsd:hexBinary</code></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
</tbody>
</table>

<aside class='issue'><p id='01CCA33C'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/10' target='_blank'><span style='color: #0000FF;'><u>Issue 10</u></span></a>: checksum<p id='229EF217'>Openstaande vraag: hoe ziet de vulling van checksum er precies uit? Ik zou verwachten dat behalve de waarde van de checksum ook het gebruikte hash-alogoritme om de waarde mee te berekenen wordt meegestuurd.</aside>

### documentation {#46BA2629}
Een informatiepagina waar aanvullende informatie over deze distributie te vinden is.
Merk op dat eigenschap <code>dct:description</code> gebruikt kan worden om de betreffende distributie te beschrijven. Deze tekst wordt afgebeeld bij de distributie op data.overheid.nl. De eigenschap documentation verwijst met een hyperlink naar de webpagina die ook een beschrijving geeft van de distributie, mogelijk aangevuld met extra informatie die niet wordt opgenomen in <code>dct:description</code>. Denk aan hoe de gegevens geïnterpreteerd moeten worden, een beschrijving van het formaat van de gegevens of hoe de gegevens verkregen kunnen worden.
Een aantal data-eigenaren kiest ervoor om de documentatie als op zichzelf staande distributie toe te voegen aan de dataset. In die gevallen hoeft deze eigenschap niet ingevuld te worden. Vul in dat geval wel <span style='background-color: #clear;'>supportingRole</span> in.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='note'><p id='462FA177'>Gebruik altijd het HTTPS-protocol voor webadressen! Zie ook <a href='https://www.forumstandaardisatie.nl/open-standaarden/https-en-hsts' target='_blank'><i>HTTPS en HSTS</i></a>.</aside>

### Voorbeelden {#7999E48E}
#### Minimale set van eigenschappen {#1FE21067}
Onderstaand voorbeeld beschrijft een <code>dcat:Distribution</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>dcat:Distribution</code>.
<aside class='example'><p id='428CE144'>Voorbeeld 4: Minimale set van eigenschappen<pre class="text">&lt;ScoreLeefbaarometerBuurt2020&gt; a dcat:Distribution ;    dcat:accessURL &lt;https:∕∕data.overheid.nl∕sites∕default∕files∕dataset∕f37c3649-cc52-4e48-a864-870ae42807a2∕resources∕Leefbaarometer%203.0%20-%20meting%202020%20-%20scores%20buurt.csv&gt; ;    dct:format &lt;http:∕∕publications.europa.eu∕resource∕authority∕file-type∕CSV&gt; ;    dct:title "Score Leefbaarometer Buurt 2020"@nl;    dct:description "Scores (stand en ontwikkeling) leefbaarheid op buurtniveau 2002-2008-2012-2014-2016-2018-2020"@nl;    dct:license &lt;http:∕∕creativecommons.org∕publicdomain∕zero∕1.0∕deed.nl&gt;;.</pre>

</aside>

#### Distributie van een collectie van bestanden {#10F32466}
<aside class='example'><p id='217C38A6'>Voorbeeld 5: Distributie van een collectie van bestanden<pre class="text">&lt;ScoreLeefbaarometerBuurt2020&gt; a dcat:Distribution ;    dcat:accessURL &lt;https:∕∕data.overheid.nl∕sites∕default∕files∕dataset∕f37c3649-cc52-4e48-a864-870ae42807a2∕resources∕Leefbaarometer%203.0%20-%20meting%202020%20-%20scores%20buurt.csv&gt; ;    dct:format &lt;http:∕∕publications.europa.eu∕resource∕authority∕file-type∕PDF&gt; ;    dct:title "Score Leefbaarometer Buurt 2020"@nl;    dct:description "Scores (stand en ontwikkeling) leefbaarheid op buurtniveau 2002-2008-2012-2014-2016-2018-2020"@nl;    dct:license &lt;http:∕∕creativecommons.org∕publicdomain∕zero∕1.0∕deed.nl&gt;;.</pre>

</aside>

#### Documentatie als op zichzelf staande distributie {#27583548}
TODO: Supportring Role
<aside class='example'><p id='6BBF66DD'>Voorbeeld 6: Documentatie als op zichzelf staande distributie<pre class="text">&lt;LeefbaarometerDocumentatie2020&gt; a dcat:Distribution ;    dcat:accessURL &lt;https:∕∕data.overheid.nl∕OpenDataSets∕leefbaarometer∕lbom.zip&gt; ;    dct:format &lt;http:∕∕publications.europa.eu∕resource∕authority∕file-type∕ZIP&gt; ;    dct:title "Score Leefbaarometer Grid 2020"@nl;    dct:description "Scores (stand en ontwikkeling) leefbaarheid op gridniveau 2002-2008-2012-2014-2016-2018-2020. Let op: dit zip bestand bevat zowel de datasets op Gemeente-, Wijk-, Buurt-, PC4- en Grid niveau."@nl;    dct:license &lt;http:∕∕creativecommons.org∕publicdomain∕zero∕1.0∕deed.nl&gt;;    donl:supportingRole.</pre>

</aside>

#### Checksum {#6F79D929}
<aside class='example'><p id='1298BE25'>Voorbeeld 7: Checksum<pre class="text">spdx:checksum [ a spdx:checksum ;    spdx:algorithm &lt;http:∕∕spdx.org∕rdf∕terms#checksumAlgorithm_sha1&gt; ;    spdx:checksumValue "85ed0817af83a24ad8da68c2b5094de69833983c" ;    ];.</pre>

</aside>

## Dataservice (dcat:DataService)  {#3491A276}
<blockquote><p id='52124C27'>Subklasse van <span style='background-color: #clear;'>dcat:Resource</span></blockquote>

Een gegevensdienst of DataService is een computer service waar gegevens opgevraagd worden aan de hand van specificaties in een aanvraag. De gegevens die voldoen aan de meegegeven specificatie worden als antwoord teruggestuurd. Webservices zoals REST/JSON, WMS of XML interfaces zijn voorbeelden van <span style='background-color: #clear;'>dcat:DataService</span>. Merk op dat als de specificatie slechts een deel van de gegevens beschrijft, alleen desbetreffende subset wordt opgestuurd. Ook is het mogelijk dat een dataservice niet één, maar meerdere datasets ontsluit.
Dataservice zijn speciaal bedoeld voor geautomatiseerde koppelingen tussen systemen, hoewel ze ook door - meestal technisch onderlegde - mensen gebruikt kunnen worden.
De DataService klasse is geïntroduceerd in versie 2 van DCAT. Het biedt uitgebreidere mogelijkheden om geautomatiseerde toegang tot gegevens te beschrijven dan mogelijk is in de klasse <span style='background-color: #clear;'>dcat:Distributie</span>. In deze nieuwe versie van het toepassingsprofiel is de DataService klasse optioneel. Dat betekent dat het mogelijk blijft om dataservices te beschrijven met de klasse Distributie.
<br/>
<br/>
INVOEGEN SHACL TABEL: Normatief Tabel met overzicht alle propertjes per klasse.  
<br/>
<br/>
INVOEGEN: voorbeeld
### endpoint URL nieuw {#66EDAAD6}
De locatie of het endpoint van de service (over het algemeen een via HTTP raadpleegbaar adres).
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### endpoint description {#35EDC798}
Een verwijzing naar de documentatie die de DataService beschrijft. Denk hierbij aan een verwijzing naar een Open Api Specification (Swagger), een <code>OGC:WFS</code> of <code>OGC:WMS</code> getCapabilities aanroep, een <code>SPARQL Service Description</code> en dergelijke.
Een gebruiker is gebaat bij een accurate en volledige beschrijving van de aangeboden service.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
<br/>
<br/>
<aside class='note'><p id='7B2504C5'>Hoewel deze eigenschap qua naamgeving veel lijkt op <span style='background-color: #clear;'>dct:description</span>, heeft deze eigenschap een aanzienlijk andere definitie!</aside>

### serves dataset {#5750BB51}
Een dataset die via deze <code>dcat:DataService</code> aangeboden wordt. Een dataservice kan nul, een of meer datasets aanbieden.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### Voorbeelden {#0B39EC9F}
Naast de onderstaande voorbeelden, biedt het W3C enkele voorbeelden aan van hoe een <code>dcat:DataService</code> eruit ziet op <a href='https://www.w3.org/TR/vocab-dcat-2/' target='_blank'>www.w3.org/TR/vocab-dcat-2/#examples-data-service</a>.
#### Minimale set van eigenschappen {#0C0FA1D8}
Onderstaand voorbeeld beschrijft een <code>dcat:DataService</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>dcat:DataService</code>.
<aside class='example'><p id='4048F41E'>Voorbeeld 8: Minimale set van eigenschappen<pre class="text">&lt;OData/v4/2.0&gt; a dcat:DataService;    dct:identifier &lt;OData/v4/2.0&gt;;    dct:title "OData API"@nl;    dct:description "Gebruik de OData API voor het opvragen van data met een zelfopgestelde zoekvraag in de vorm van een URL (query). De OData API levert de data in het machineleesbare bestandsformaat JSON."@nl;    dct:license &lt;http://creativecommons.org/publicdomain/zero/1.0/deed.nl&gt;;    dct:creator &lt;http://standaarden.overheid.nl/owms/terms/Tweede_Kamer_der_Staten-Generaal&gt;;    dct:publisher &lt;http://standaarden.overheid.nl/owms/terms/Tweede_Kamer_der_Staten-Generaal&gt;;    dcat:contactPoint [a vcard:Organization ;        vcard:fn "Tweede Kamer der Staten-Generaal";        vcard:hasEmail "opendata@tweedekamer.nl";];    dcat:theme &lt;http://standaarden.overheid.nl/owms/terms/Parlement&gt;;    dcat:endpointURL &lt;https://gegevensmagazijn.tweedekamer.nl/OData/v4/2.0&gt;;    dcat:endpointDescription &lt;https://opendata.tweedekamer.nl/documentatie/odata-api&gt;;.</pre>

</aside>

#### Een DataService die Datasets ontsluit {#4EEF88C5}
De gemeente Nijmegen heeft een publiek beschikbare <code>OGC:WMS</code> webservice waarmee de gemeente gemaakte luchtfoto's aanbiedt. Een van de aangeboden luchtfoto's is de "Luchtfoto 2022" (De gemeente maakt jaarlijks luchtfoto's). Deze luchtfoto's kunnen individueel (of als bundel) als dataset aangeboden worden. De behoefte bestaat om de relaties tussen de dataset en de webservice duidelijk vast te leggen.
Dit voorbeeld uit zich in de volgende RDF (niet relevante eigenschappen zijn weggelaten):
<aside class='example'><p id='47EA093D'>Voorbeeld 9: Een DataService die Datasets ontsluit<pre class="text">&lt;https:∕∕opendata.nijmegen.nl∕dataset∕luchtfoto-2022&gt; a dcat:Dataset;    dct:title "Luchtfoto 2022"@nl ;    dcat:distribution &lt;odn.luchtfoto-2022.distribution.1&gt; ;    dcat:distribution &lt;odn.luchtfoto-2022.distribution.2&gt; ;</pre>

<pre class="text">&lt;odn.luchtfoto-2022.distribution.1&gt; [ a dcat:Distribution ;    dct:title "Lage resolutie"@nl ;    dcat:accessURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&service=WMS&version=1.3.0&request=GetMap&layers=Luchtfoto2022.ecw&styles=default&transparent=true&CRS=EPSG:28992&bbox=176999.975,420000.025,191999.975,435500.025&width=750&height=775&format=image∕png&gt;;    dcat:accessService &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt;;    ];</pre>

<pre class="text">&lt;odn.luchtfoto-2022.distribution.2&gt; [ a dcat:Distribution ;    dct:title "Hoge resolutie"@nl ;    dcat:accessURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&service=WMS&version=1.3.0&request=GetMap&layers=Luchtfoto2022.ecw&styles=default&transparent=true&CRS=EPSG:28992&bbox=176999.975,420000.025,191999.975,435500.025&width=3000&height=3100&format=image∕png&gt; ;    dcat:accessService &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt; ;    ];</pre>

<pre class="text">&lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt; [ a dcat:DataService ;    dcat:endpointURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&request=getCapabilities&service=WMS&gt; ;    rdf:servesDataset &lt;https:∕∕opendata.nijmegen.nl∕dataset∕luchtfoto-2022&gt; ;    ];.</pre>

</aside>

We zien hier de dataset <code>https://opendata.nijmegen.nl/dataset/luchtfoto-2022</code> met een tweetal distributies. In de eigenschappen van de distributies is de relatie opgenomen via welke dataservice ze ontsloten worden. Daarnaast zien we de dataservice <code>https://services.nijmegen.nl/geoservices/wms/extern_Luchtfoto</code>. In de eigenschappen van deze dataservice is opgenomen dat deze de <code>https://opendata.nijmegen.nl/dataset/luchtfoto-2022</code> dataset ontsluit.
## Legal foundation (donl:LegalFoundation) nieuw {#72D39D51}
Bevat een verwijzing naar een wettelijke grondslag conform de <a href='https://www.koopoverheid.nl/standaarden/juriconnect' target='_blank'><i>Juriconnect</i></a> standaard.
### Eigenschappen {#3570C3B0}
In de onderstaande tabel worden de eigenschappen van de <code>donl:LegalFoundation</code> beschreven.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 28.245531514581373%;'>
<col id='col2' style='width: 21.319379115710255%;'>
<col id='col3' style='width: 24.082784571966133%;'>
<col id='col4' style='width: 26.35230479774224%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='3DE8AA07'>Eigenschap</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='21CFAD7B'>Kardinaliteit</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='373F007B'>Aanwezigheid</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='07023C63'>Herkomst</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='779569CB'><span style='color: #0000FF;'><u>title</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='765A0443'>Mandatory</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='766273F9'>Legal foundation</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6488F43E'><span style='color: #0000FF;'><u>legal domain</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='54CFF672'>Mandatory</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='492E54E5'>Legal foundation</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='52C562C1'><span style='color: #0000FF;'><u>juriconnect code</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='04EC5768'>Mandatory</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='79E1DEB6'>Legal foundation</td>
</tr>
</tbody>
</table>

#### title {#0498E2CA}
De naam van de wettelijke grondslag. Deze naam is uitsluitend bedoeld voor presentatie doeleinden. Het is geen vereiste dat hier de formele naam van de wet of van het wetsartikel wordt opgenomen. "Wet BAG" kan als titel fungeren, terwijl de formele titel "Wet basisregistratie adressen en gebouwen" zou zijn.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 59.818908748824086%;'>
<col id='col2' style='width: 40.181091251175914%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='1069671C'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='36A54735'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6D5D4EFC'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:title</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='1E69E23D'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>rdfs:Literal</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='199F605B'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4BE8FFE7'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='44AE0C39'>Mandatory</td>
</tr>
</tbody>
</table>

#### legal domain {#7BAA8A67}
Het domein waarnaar verwezen wordt die de <a href='https://www.koopoverheid.nl/standaarden/juriconnect' target='_blank'><i>Juriconnect</i></a> verwijzing bevat. Dit zal in de meeste gevallen <a href='https://wetten.overheid.nl' target='_blank'>wetten.overheid.nl</a> zijn.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 52.70460959548448%;'>
<col id='col2' style='width: 47.29539040451552%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='62943E7F'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6C2E7B01'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='686AD264'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>foaf:homepage</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='141031B0'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>xsd:anyURI</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='370B194D'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='3911F712'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='014040F0'>Mandatory</td>
</tr>
</tbody>
</table>

#### juriconnect code {#60B6A270}
De <a href='https://www.koopoverheid.nl/standaarden/juriconnect' target='_blank'><i>Juriconnect</i></a> code die verwijst naar de daadwerkelijke wettelijke grondslag. <a href='https://wetten.overheid.nl' target='_blank'>wetten.overheid.nl</a> ondersteund <a href='https://www.juriconnect.nl/downloadreg.asp?bestand=Juriconnect%5FStandaard%5FBWB%5F1%5F3%2Epdf&type=pdf' target='_blank'><i>Juriconnect 1.3</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 45.190498588899345%;'>
<col id='col2' style='width: 54.809501411100655%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='2C13DA22'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='10A425B1'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='287C6A29'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>donl:juriconnectCode</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='0230AC80'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>rdfs:Literal</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='2BA6BDFC'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4A52AFD7'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6130A8EA'>Mandatory</td>
</tr>
</tbody>
</table>

### Voorbeelden {#2DEEA517}
#### Minimale set van eigenschappen {#37401F13}
Onderstaand voorbeeld beschrijft een <code>donl:LegalFoundation</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>donl:LegalFoundation</code>.
<aside class='example'><p id='349D8C11'>Voorbeeld 13: Minimale set van eigenschappen<pre class="text">ex:myLegalFoundation a donl:LegalFoundation;    dct:title "Wet BAG"@nl ;    foaf:homepage "https://wetten.overheid.nl/"^^xsd:anyURI ;    donl:juriconnectCode "jci1.3:c:BWBR0023466&z=2022-05-01&g=2022-05-01" ;.</pre>

</aside>

Webapplicaties zouden bovenstaande voorbeeld kunnen vertalen naar:
<pre class="text">&lt;a href="https://wetten.overheid.nl/jci1.3:c:BWBR0023466&z=2022-05-01&g=2022-05-01"&gt;    Wet BAG&lt;/a&gt;</pre>

### Voorbeelden {#3DD867E3}
#### Contact point {#321633BA}
<aside class='example'><p id='769C6BD5'>Voorbeeld 10: Contact point<pre class="text">&lt;https:∕∕data.overheid.nl∕ondersteuning∕algemeen∕contact&gt;    a dcat:Dataset;    dcat:contactPoint [a vcard:Organization ;    vcard:fn "data.overheid.nl";    vcard:hasEmail "data@koop.overheid.nl";    vcard:hasTelephone [        a vcard:Work,        vcard:Voice;        vcard:hasValue &lt;tel:31707000526&gt;        ];    vcard:hasURL "data.overheid.nl";    ];.</pre>

</aside>

#### Other identifier {#066F5878}
<aside class='example'><p id='0226A428'>Voorbeeld 11: Other identifier<pre class="text">&lt;GBI.WELZ_CULTHIS_AMK_V&gt; a dcat:Dataset;    dct:identifier &lt;https:∕∕kaartportaal.drenthe.nl/portal/home/item.html?id=41b396ac19754bc4a414ababe0773e03&gt;;    adms:Identifier [a adms:Identifier ;        skos:notation "https:∕∕data.overheid.nl/dataset/2bd6eae9-3192-4e0f-a89b-c8d6b64d241f"^^xsd:anyURI;        dct:creator &lt;https:∕∕data.overheid.nl/organisatie/koop&gt;;    ];.</pre>

</aside>

#### Qualified attribution {#4CEB062A}
TODO: Syntax en inhoud.
Voorbeeld overgenomen van <a href='https://www.w3.org/TR/vocab-dcat-2/' target='_blank'>W3C</a>
<aside class='example'><p id='2DA9E747'>Voorbeeld 12: Qualified attribution<pre class="text">ex:DS987a dcat:Dataset ;    prov:qualifiedAttribution [        a prov:Attribution ;        prov:agent &lt;https://www.ala.org.au/&gt; ;        dcat:hadRole &lt;http://registry.it.csiro.au/def/isotc211/CI_RoleCode/distributor&gt;    ] ;    prov:qualifiedAttribution [        a prov:Attribution ;        prov:agent &lt;https://www.education.gov.au/&gt; ;        dcat:hadRole &lt;http://registry.it.csiro.au/def/isotc211/CI_RoleCode/funder&gt;    ] ;.</pre>

</aside>

## Catalogus (dcat:Catalog) {#170A3A71}
<blockquote><p id='3C44C3D2'>Subklasse van <span style='background-color: #clear;'>dcat:Dataset</span>.</blockquote>

<code>dcat:Catalog</code> maakt het mogelijk om structuur aan te brengen in een DCAT beschrijving zonder de eigenschappen van de <span style='background-color: #clear;'>dcat:Resource</span> te veranderen. Instanties van de klasses <span style='background-color: #clear;'>dcat:Dataset</span>, <span style='background-color: #clear;'>dcat:DataService</span>, <span style='background-color: #clear;'>dcat:CatalogRecord</span> en <span style='background-color: #clear;'>dcat:Catalog</span> zelf kunnen volgens eigen criteria verzameld worden in een overkoepelende <code>dcat:Catalog</code>. Naast het opdelen van complexe DCAT beschrijvingen in samenhangende delen, wordt ook het omgekeerde mogelijk: Verschillende beschrijvingen kunnen in één DCAT gecombineerd worden.
Het gebruik van de term 'catalogus' kan verwarring opleveren. In het Nederlands (resp. Engels) is een catalogus (resp. catalogue) een register of lijst waarin een verzameling voorwerpen of termen is opgenomen, vaak met een korte omschrijving of definitie en een aantal bijzonderheden. In de informatietechnologie worden diverse soorten catalogi opgesteld, zoals termenlijsten of taxonomieën. Een dcat:Catalog is een verzameling dcat klasses, dus een verzameling van dcat:Datasets, dcat:Distributies of andere catalogi. Een dcat:catalogus is niet geschikt om de meer algemene rol van een catalogus te vervullen. DCAT kan wel gebruikt worden om een dergelijke catalogus (en het ontsluiten ervan) te beschrijven met dcat:Dataset, dcat:Distribution en dcat:DataService.
In grote datacatalogi als <a href='https://data.overheid.nl/' target='_blank'><i>data.overheid.nl</i></a> of <a href='https://data.europa.eu/en' target='_blank'><i>data.europa.eu</i></a> wordt DCAT
informatie van een groot aantal datasets en aanbieders verzameld. Een dcat:catalogus kan dan bijvoorbeeld worden gebruikt om de datasets van één aanbieder te groeperen. Een voorbeeld hiervan is: <a href='https://data.overheid.nl/datasets?facet_catalog%5B%5D=http://opendata.arnhem.nl/' target='_blank'>alle data van de <span style='background-color: #clear;'>gemeente Arnhem</span></a>. dcat:Catalogue stelt geen eisen aan de indeling van een DCAT beschrijving, dus ook andere catalogs zijn mogelijk zoals <a href='https://data.overheid.nl/statistieken/meest-bekeken-datasets' target='_blank'>de meest populaire data van het jaar</a>.
Het laatste voorbeeld is de catalogus op basis van een gedeeld onderwerp. Hiermee kunnen gegevens waarvan door de aanbieders niet met behulp van een dcat:theme, dcat:keyword, dct:conformsTo of op een andere wijze is aangegeven dat ze een bepaald onderwerp betreffen, toch in een catalog over dat onderwerp worden opgenomen, zonder dat de oorspronkelijk aangeleverde gegevens gewijzigd hoeven te worden. Met de juiste attributen kan deze catalog zelf worden voorzien van de juiste thema's, keywords etc. Een voorbeeld hiervan zou een catalog kunnen zijn waarmee de impact van de Corona pandemie zichtbaar wordt. Toen de pandemie uitbrak waren er vanzelfsprekend geen DCAT beschrijvingen waarin COVID was opgenomen. Een COVID catalogus zou gegevens kunnen bevatten met medische data en sterftecijfers, maar economische of sociale data. Eventueel kan met de hand of op basis van meerdere filters een Corona catalogus aangemaakt.
<br/>
<br/>
INVOEGEN SHACL TABEL: Normatief Tabel met overzicht alle propertjes per klasse.  
<br/>
<br/>
INVOEGEN: voorbeeld
<aside class='issue'><p id='4743CF3D'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/21' target='_blank'><span style='color: #0000FF;'><u>Issue 21</u></span></a>: Wat is een catalogus in DCAT nu precies<p id='0F72453C'>Er lijkt onduidelijkheid te zijn rondom de definitie van <a href='https://www.w3.org/TR/vocab-dcat-2/' target='_blank'>dcat:Catalog</a>. Wat is het precies en wanneer wordt het gebruikt?</aside>

<ul><li>Wanneer is een catalogus een <a href='https://www.w3.org/TR/vocab-dcat-2/' target='_blank'>dcat:Catalog</a>?</li>
<li>Wanneer is een catalogus een <a href='https://www.w3.org/TR/vocab-dcat-2/' target='_blank'>dcat:Dataset</a>?</li>
</ul>
### homepage {#1160C76F}
De homepage van de catalogus. Een catalogus kan op meerdere dataportals worden gepubliceerd. Deze eigenschap verwijst naar de originele homepage. Dat is in de regel de homepage van de maker van de catalogus.
Let op, dit is dus iets anders dan <span style='background-color: #clear;'>dcat:landingPage</span>.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### dataset {#4434659F}
De (metadata van de) dataset(s) die is/zijn opgenomen in de catalogus.
Het lijkt logisch dat een catalogus tenminste één dataset bevat, omdat een catalogus op zich niet zo interessant is. Desondanks geven we hier de cardinaliteit <code>0..n</code>, omdat een catalogus ook als resource in een andere catalogus kan voorkomen zonder verdere inhoud. In dat geval verwijst de catalogus door naar de homepage op een ander dataportaal die de inhoud wel toont. Een ander voorbeeld is een catalogus die alleen dataservices ontsluit.
Zie ook de discussie op <a href='https://github.com/SEMICeu/DCAT-AP/issues/180' target='_blank'>github.com/SEMICeu/DCAT-AP/issues/180</a>.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### service {#7D3FE459}
De (metadata van de) dataservice die voorkomt in de catalogus. Dataservice is een nieuwe resource in DCAT2.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### catalog {#190C90BC}
De (metadata van de) catalogus die voorkomt in de catalogus. Deze eigenschap maakt dus mogelijk om een catalogus te beschouwen als een resource en deze op te nemen in een catalogus.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
### themes {#2BFA190B}
De themalijst die van toepassing is op alle resources in deze catalogus. Deze zal binnen dit toepassingsprofiel altijd verwijzen naar de <a href='https://standaarden.overheid.nl/owms/4.0/doc/waardelijsten/overheid.taxonomiebeleidsagenda' target='_blank'><i>overheid:TaxonomieBeleidsagenda (standaarden.overheid.nl)</i></a>.
<br/>
<br/>
INVOEGEN SHACL TABEL: Tabel per property met de in mockup beschreven velden.
<br/>
<br/>
INVOEGEN: voorbeeld
## Catalogusrecord (dcat:CatalogRecord) {#594CCB0F}
<aside class='note'><p id='72A232F9'>Hoewel <a href='https://data.overheid.nl/' target='_blank'><i>data.overheid.nl</i></a> zelf wel <code>dcat:CatalogRecord</code>s aanbiedt, kunnen data-eigenaren hun eigen <code>dcat:CatalogRecord</code>s niet uitwisselen met <a href='https://data.overheid.nl/' target='_blank'><i>data.overheid.nl</i></a>.</aside>

Een Catalogusrecord geeft informatie over de registratie van één <span style='background-color: #clear;'>dcat:Resource</span> in een catalogus. Alle records samen bevatten de administratieve metadata van een DCAT beschrijving. Met name het versiebeheer van ieder <span style='background-color: #clear;'>dcat:Resource</span> in de DCAT beschrijving kan hiermee worden bijgehouden en uitgewisseld.
Deze klasse is optioneel en niet alle catalogi maken hiervan gebruik, omdat het niet altijd nuttig is de historie van wijzigingen in een DCAT beschrijving uit te wisselen. Ze maakt het catalogi mogelijk om een onderscheid te maken tussen de metadata over een dataset of dataservice en metadata over een voorkomen van een dataset of dataservice in een catalogus. Eigenschap publicatiedatum van een dataset beschrijft bijvoorbeeld de datum waarop de data-eigenaar de gegevens in eerste instantie heeft gepubliceerd, terwijl de publicatiedatum van het catalogus record de datum beschrijft waarop de dataset is opgenomen in de catalogus.
CatalogRecord kan met conformsTo aangeven aan welk toepassingsprofiel de metadata over de DCAT-resource voldoet. Dat kan belangrijk zijn bij de uitwisseling van de metadata van datasets (of andere DCAT-resources) tussen dataportalen. Het kan voorkomen dat de metadata moet voldoen aan een specifieke toepassingsprofielen van DCAT.
### Eigenschappen {#3328B4C9}
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 29.644873000940734%;'>
<col id='col2' style='width: 20.849012229539042%;'>
<col id='col3' style='width: 23.906396989651927%;'>
<col id='col4' style='width: 25.599717779868296%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='3BAC4ABA'>Eigenschap</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='5BBB94E4'>Kardinaliteit</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='464BC811'>Aanwezigheid</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='64471AD3'>Herkomst</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='38FC3D52'><span style='color: #0000FF;'><u>primary topic</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='24EA3810'>Mandatory</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='48758FB5'>Catalogusrecord</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4A901196'><span style='color: #0000FF;'><u>modified</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4A2021EC'>Mandatory</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4DC24A87'>Catalogusrecord</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='13648D42'><span style='color: #0000FF;'><u>listing date</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='78FEDED2'>Recommended</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='64B728AE'>Catalogusrecord</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='668BA4CD'><span style='color: #0000FF;'><u>conformsTo</u></span> nieuw</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>0..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6E979FF3'>Recommended</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='49E01A4C'>Catalogusrecord</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='67CA0D4F'><span style='color: #0000FF;'><u>source metadata</u></span></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>0..1</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='79FADEDA'>Optional</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='28445333'>Catalogusrecord</td>
</tr>
</tbody>
</table>

#### primary topic {#73479134}
Betreft de verwijzing naar de <span style='background-color: #clear;'>dcat:Dataset</span>, <span style='background-color: #clear;'>dcat:DataService</span> of <span style='background-color: #clear;'>dcat:Catalog</span> die met dit record beschreven wordt.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 28.11618062088429%;'>
<col id='col2' style='width: 71.8838193791157%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='0EFB4E1C'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='59F0356D'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='4D829B49'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>foaf:primaryTopic</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='20CA383C'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='08DC0F0C'><code>dcat:Resource</code> (dataset, dataservice or catalog)</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='31D85C6B'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='5EC2E663'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='760D3C61'>Mandatory</td>
</tr>
</tbody>
</table>

#### modified {#40534DC5}
De datum waarop het record in de catalogus voor het laatst is gewijzigd.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 57.16133584195673%;'>
<col id='col2' style='width: 42.83866415804327%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='361AF3A1'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='43013796'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='40F6160A'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:modified</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='48A925EF'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>xsd:date</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='23FB0889'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6E517552'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='460EAED1'>Mandatory</td>
</tr>
</tbody>
</table>

<aside class='note'><p id='10984037'>Deze eigenschap moet een datum en tijd bevatten conform de <a href='https://www.iso.org/iso-8601-date-and-time-format.html' target='_blank'><i>ISO-8601</i></a> standaard, <code>YYYY-MM-DDThh:mm:ss</code>.</aside>

#### listing date {#3BE43787}
De datum waarop het record in de catalogus voor het eerst is toegevoegd.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 52.35183443085607%;'>
<col id='col2' style='width: 47.64816556914393%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='681543E1'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='12D9FB50'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='1ED0D5BF'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:issued</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='345A4CA2'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>xsd:date</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='377F52F6'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='14417FF4'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='2FD6658B'>Recommended</td>
</tr>
</tbody>
</table>

<aside class='note'><p id='66641AED'>Deze eigenschap moet een datum en tijd bevatten conform de <a href='https://www.iso.org/iso-8601-date-and-time-format.html' target='_blank'><i>ISO-8601</i></a> standaard, <code>YYYY-MM-DDThh:mm:ss</code>.</aside>

#### conformsTo nieuw {#05CDE4AA}
Een verwijzing naar het DCAT <u>applicatieprofiel</u> waar de metadata van de <span style='background-color: #clear;'>dcat:Resource</span> aan voldoet.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 51.999059266227654%;'>
<col id='col2' style='width: 48.00094073377234%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6D6DB6EE'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='250FB57C'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='58CD9836'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:conformsTo</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='723F81B4'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:Standard</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='43D491C7'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>0..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='64F9F3FB'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6411CBBC'>Recommended</td>
</tr>
</tbody>
</table>

<aside class='note'><p id='6979F6D2'>Gebruik altijd het HTTPS-protocol voor webadressen! Zie ook <a href='https://www.forumstandaardisatie.nl/open-standaarden/https-en-hsts' target='_blank'><i>HTTPS en HSTS</i></a>.</aside>

#### source metadata {#06FED020}
Een verwijzing naar de bron waar de metadata van de <span style='background-color: #clear;'>dcat:Resource</span> vandaan komt.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 58.01975540921919%;'>
<col id='col2' style='width: 41.980244590780806%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='58E6D319'>Definitie</th>
<th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='2A3D3AD4'>Waarde</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='3A7CD89B'>RDF Eigenschap</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:source</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='163FACDB'>Bereik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>xsd:anyURI</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='00DE0D99'>Kardinaliteit</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='2152465A'>Gebruik</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='6C61B386'>Optional</td>
</tr>
</tbody>
</table>

<aside class='note'><p id='51E3DC31'>Gebruik altijd het HTTPS-protocol voor webadressen! Zie ook <a href='https://www.forumstandaardisatie.nl/open-standaarden/https-en-hsts' target='_blank'><i>HTTPS en HSTS</i></a>.</aside>

### Niet overgenomen eigenschappen {#2D83328C}
De eigenschappen in de onderstaande tabel bestaan wel in de bovenliggende <a href='https://www.w3.org/TR/vocab-dcat-2' target='_blank'><i>[[DCAT-2.0]]  </i></a>, <a href='https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/210' target='_blank'><i>[[DCAT-AP-2.1.1]] </i></a> en/of <a href='https://dcat-ap-donl.readthedocs.io/en/latest/' target='_blank'><i>DCAT-AP-DONL 1.1</i></a> standaarden, maar worden niet overgenomen in dit profiel.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 100%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='5EC24E22'>Eigenschap</th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:title</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:description</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>dct:language</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>adms:status</code>

</td>
</tr>
</tbody>
</table>

