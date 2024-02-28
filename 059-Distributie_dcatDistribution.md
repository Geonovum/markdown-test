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
<section data-include-format='markdown' data-include='059-accessURL.md'></section>
<section data-include-format='markdown' data-include='060-format.md'></section>
<section data-include-format='markdown' data-include='061-title.md'></section>
<section data-include-format='markdown' data-include='062-description.md'></section>
<section data-include-format='markdown' data-include='063-license.md'></section>
<section data-include-format='markdown' data-include='064-accessService_nieuw.md'></section>
<section data-include-format='markdown' data-include='065-downloadURL.md'></section>
<section data-include-format='markdown' data-include='066-modified.md'></section>
<section data-include-format='markdown' data-include='067-issued.md'></section>
<section data-include-format='markdown' data-include='068-language.md'></section>
<section data-include-format='markdown' data-include='069-rights.md'></section>
<section data-include-format='markdown' data-include='070-byteSize.md'></section>
<section data-include-format='markdown' data-include='071-conformsTo_.md'></section>
<section data-include-format='markdown' data-include='072-mediaType.md'></section>
<section data-include-format='markdown' data-include='073-checksum.md'></section>
<section data-include-format='markdown' data-include='074-documentation.md'></section>
<section data-include-format='markdown' data-include='075-Voorbeelden.md'></section>
