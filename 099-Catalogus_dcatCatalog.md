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
<section data-include-format='markdown' data-include='099-homepage.md'/>
<section data-include-format='markdown' data-include='100-dataset.md'/>
<section data-include-format='markdown' data-include='101-service.md'/>
<section data-include-format='markdown' data-include='102-catalog.md'/>
<section data-include-format='markdown' data-include='103-themes.md'/>
