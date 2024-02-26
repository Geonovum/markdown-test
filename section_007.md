# Waardelijsten {#6952D3B2}
## Beheer {#29903200}
TODO: Beheer van waardelijsten en beheer van de inhoud van de waardelijsten beschrijven.
## Overzicht {#3A605599}
Binnen dit toepassingsprofiel worden de onderstaande waardelijsten toegepast.
### donl:AccessRights {#27AAD628}
Bevat concepten die de mate van openbaarheid beschrijven van een bron. Deze waardelijst bestaat uitsluitend uit concepten die afgeleid zijn van de concepten uit de <a href='https://publications.europa.eu/resource/authority/access-right' target='_blank'><i>mdr:AccessRights (publications.europa.eu)</i></a> taxonomie die op Europees niveau toegepast wordt.
<aside class='note'><p id='28C2531D'>Noot<p id='41FB3F60'>De concepten zelf zullen in <a href='https://tardis.overheid.nl' target='_blank'><i>TOOI - Thesaurus en Ontologie Overheidsinformatie</i></a> opgenomen worden (en dus een <span style='background-color: cyan;'>identifier.overheid.nl</span> identifier krijgen. De werkversies van deze concepten zijn voorlopig raadpleegbaar op <a href='https://github.com/dataoverheid/dcat-ap-donl/tree/main/term/access-rights' target='_blank'><i>donl:AccessRights concepts (Github.com/dataoverheid)</i></a></aside>

<blockquote><p class='space-after' id='5EBB166C'>Elk <a href='https://github.com/dataoverheid/dcat-ap-donl/tree/main/term/access-rights' target='_blank'><i>donl:AccessRights concepts (Github.com/dataoverheid)</i></a> bevat een <span style='background-color: cyan;'>skos:broader</span> eigenschap met daarin een verwijzing naar het bovenliggende <a href='https://publications.europa.eu/resource/authority/access-right' target='_blank'><i>mdr:AccessRights (publications.europa.eu)</i></a> concept.</blockquote>

<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='4A581130'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='2F98441E'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='05538259'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='6FBC4D19'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/access-rights.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/access-rights.ttl</a></td>
</tr>
</tbody>
</table>

### donl:Language {#1B41E7FF}
Deze taxonomie bevat concepten die de taal van een bron (data of metadata) beschrijven. Alle concepten komen uit de <a href='https://publications.europa.eu/resource/authority/language' target='_blank'><i>mdr:Language (publications.europa.eu)</i></a>.
Er is geen ondersteuning voor alle talen uit de <a href='https://publications.europa.eu/resource/authority/language' target='_blank'><i>mdr:Language (publications.europa.eu)</i></a>. Alleen de voor <a href='https://data.overheid.nl/' target='_blank'><i>data.overheid.nl</i></a> relevante taalconcepten zijn overgenomen.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='4E45C872'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='66279959'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='73C7E0D8'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='5609BD8C'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/languages.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/languages.ttl</a></td>
</tr>
</tbody>
</table>

### donl:License {#3D740990}
Deze taxonomie bevat concepten die de licentie beschrijven die van toepassing is op een bron. Deze waardelijst bevat voornamelijk, maar niet uitsluitend, CreativeCommons licenties. Deze taxonomie is gespitst op het aanbieden van data via een "open" licentie.
In <a href='https://dcat-ap-donl.readthedocs.io/en/latest/' target='_blank'><i>DCAT-AP-DONL 1.1</i></a> werden van een aantal CreativeCommons licenties alleen de <span style='background-color: cyan;'>4.0</span> versies aangeboden. In dit profiel worden de <span style='background-color: cyan;'>3.0</span> versies van deze licenties ook aangeboden. Dit omdat blijkt dat veel data nog via een van de <span style='background-color: cyan;'>3.0</span> varianten beschikbaar wordt gesteld.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='3351DEA5'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='66D724B9'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='736757A0'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='5E999387'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/licences.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/licences.ttl</a></td>
</tr>
</tbody>
</table>

### donl:RelevantOrganization {#36BEC253}
<blockquote><p id='4F31AB44'>Zie ook: <span style='color: #0000FF;'><span style='background-color: cyan;'><u>overheid:Organisatie</u></span></span></blockquote>

<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='3F8423A0'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='4B577562'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='113AE34D'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='1B2EB01B'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/organizations.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/organizations.ttl</a></td>
</tr>
</tbody>
</table>

### donl:Role {#0D922483}
Deze taxonomie bevat concepten die beschrijven in welke capaciteit een persoon of organisatie betrokken is (of is geweest) bij een bron.
Het <a href='https://joinup.ec.europa.eu/collection/semantic-interoperability-community-semic/solution/dcat-application-profile-data-portals-europe/release/210' target='_blank'>C<i>[DCAT-AP-2.1.1]] </i></a><i> b</i>eveelt de <a href='https://standards.iso.org/iso/19115/resources/Codelists/gml/CI_RoleCode.xml' target='_blank'><i>ISO-19115 RoleCode</i></a> taxonomie aan. Deze is echter niet in linked data vorm beschikbaar. Om deze reden biedt dit profiel zelf een <span style='background-color: cyan;'>skos:ConceptScheme</span> aan met daarin opgenomen de <span style='background-color: cyan;'>CI_RoleCode</span> concepten.
Deze lijst moet gebruikt worden bij het invullen van het <span style='background-color: cyan;'>prov:hadRole</span> eigenschap, wat onderdeel is van het <span style='color: #0000FF;'><span style='background-color: cyan;'><u>prov:qualifiedAttribution</u></span></span> eigenschap, die vanuit <span style='color: #0000FF;'><span style='background-color: cyan;'><u>dcat:Resource</u></span></span> aangeboden wordt.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='470B8E84'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='21674A4D'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='41756541'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='4FBA4CA6'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/roles.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/roles.ttl</a></td>
</tr>
</tbody>
</table>

### donl:SupportingRole {#68883DD4}
Bevat concepten die beschrijven wat voor ondersteunende rol een bron dient voor een andere bron (het kan bijvoorbeeld aangeven dat een distributie documentatie bevat van een dataset). Deze waardelijst heette in <a href='https://dcat-ap-donl.readthedocs.io/en/latest/' target='_blank'><i>DCAT-AP-DONL 1.1</i></a> <span style='background-color: cyan;'>donl:DistributionType</span>.
De lijst is aanzienlijk ingekort aangezien een aantal 'types' herleidbaar zijn uit andere metadata-eigenschappen. Zo zijn de concepten <span style='background-color: cyan;'>DOWNLOAD</span> en <span style='background-color: cyan;'>WEBSERVICE</span> niet meegenomen uit de oude lijst aangezien deze informatie al geduid wordt door middel van de eigenschappen <span style='background-color: cyan;'>dcat:downloadURL</span> en/of <span style='background-color: cyan;'>dcat:accessService</span> die op <span style='background-color: cyan;'>dcat:Distribution</span> niveau aanwezig zijn.
<aside class='note'><p id='033CDB29'>Noot<p id='50B06439'>De concepten zelf zullen in <a href='https://tardis.overheid.nl' target='_blank'><i>TOOI - Thesaurus en Ontologie Overheidsinformatie</i></a> opgenomen worden (en dus een <span style='background-color: cyan;'>identifier.overheid.nl</span> identifier krijgen. De werkversies van deze concepten zijn voorlopig raadpleegbaar op <a href='https://github.com/dataoverheid/dcat-ap-donl/tree/main/term/supporting-roles' target='_blank'><i>donl:SupportingRole concepts (Github.com/dataoverheid)</i></a></aside>

<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 13.786202024958794%;'>
<col id='col2' style='width: 86.2137979750412%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='1A01BE9F'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='4FFA910F'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='255D9332'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='11E4A023'><a href='https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/supporting-roles.ttl' target='_blank'>https://raw.githubusercontent.com/dataoverheid/dcat-ap-donl/main/taxonomy/supporting-roles.ttl</a></td>
</tr>
</tbody>
</table>

### iana:Mediatype {#50DED6B4}
Bevat concepten die de mimetype van een bron beschrijven. Deze lijst is raadpleegbaar via <a href='https://www.iana.org/assignments/media-types/media-types.xhtml' target='_blank'><i>IANA Mediatypes</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 16.894278314104074%;'>
<col id='col2' style='width: 83.10572168589593%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='12B3097E'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='797FD779'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='44EADB3F'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='00E9C739'><a href='https://www.iana.org/assignments/media-types/media-types.xml' target='_blank'>https://www.iana.org/assignments/media-types/media-types.xml</a></td>
</tr>
</tbody>
</table>

### mdr:Filetype {#6104A6EB}
Bevat concepten die het bestandsformaat van een bron beschrijven. Dit is een Europese taxonomie raadpleegbaar via <a href='https://publications.europa.eu/resource/authority/file-type' target='_blank'><i>mdr:Filetype (publications.europa.eu)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 18.554273604897574%;'>
<col id='col2' style='width: 81.44572639510243%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='16A25599'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='6CBA7E75'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='0D46E30D'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='738133E6'><a href='https://publications.europa.eu/resource/authority/file-type' target='_blank'>https://publications.europa.eu/resource/authority/file-type</a></td>
</tr>
</tbody>
</table>

### mdr:Frequency {#262775DD}
Bevat concepten die beschrijven met welke frequentie een bron verwacht bijgewerkt te worden. Dit is een Europese taxonomie raadpleegbaar via <a href='https://publications.europa.eu/resource/authority/frequency' target='_blank'><i>mdr:Frequency (publications.europa.eu)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 18.04803390628679%;'>
<col id='col2' style='width: 81.95196609371321%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='2E01FD08'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='1D54F214'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='0FFE3E33'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='27A4E666'><a href='https://publications.europa.eu/resource/authority/frequency' target='_blank'>https://publications.europa.eu/resource/authority/frequency</a></td>
</tr>
</tbody>
</table>

### overheid:Gemeente {#14BAEC6B}
Deze taxonomie bevat concepten die de gemeenten van de Nederlandse overheid beschrijven. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/terms/Gemeente' target='_blank'><i>overheid:Gemeente (standaarden.overheid.nl)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 17.95384977631269%;'>
<col id='col2' style='width: 82.0461502236873%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='12410DB7'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='64B7E757'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='01F53140'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='366F0764'><a href='https://standaarden.overheid.nl/owms/terms/Gemeente.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/Gemeente.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='05626AC1'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='2BA62E54'><a href='https://standaarden.overheid.nl/owms/terms/Gemeente.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/Gemeente.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='7F7CB8D7'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='6ECC1E04'><a href='https://standaarden.overheid.nl/owms/terms/Gemeente.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/Gemeente.n3</a></td>
</tr>
</tbody>
</table>

### overheid:Koninkrijksdeel {#06641FB6}
Deze taxonomie bevat concepten die de koninkrijksdelen van het Koninkrijk der Nederlanden beschrijven. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel' target='_blank'><i>overheid:Koninkrijksdeel (standaarden.overheid.nl)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 16.894278314104074%;'>
<col id='col2' style='width: 83.10572168589593%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='7AB66703'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='429AE4F6'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='1EFA4508'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='02370D1E'><a href='https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='0F82171E'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='0CBD9253'><a href='https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='10CFBA09'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='0C20ABDC'><a href='https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/Koninkrijksdeel.n3</a></td>
</tr>
</tbody>
</table>

### overheid:Organisatie {#7E4796B4}
Deze taxonomie bevat concepten die de overheidsorganisaties van de Nederland beschrijven. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/terms/Organisatie' target='_blank'><i>overheid:Organisatie (standaarden.overheid.nl)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 17.71838945137744%;'>
<col id='col2' style='width: 82.28161054862255%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='4E27FB48'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='6EDFCC53'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='331DA9E5'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='140B9068'><a href='https://standaarden.overheid.nl/owms/terms/Organisatie.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/Organisatie.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='61969C9B'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='6A02DCC5'><a href='https://standaarden.overheid.nl/owms/terms/Organisatie.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/Organisatie.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='41457AF1'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='218A59CD'><a href='https://standaarden.overheid.nl/owms/terms/Organisatie.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/Organisatie.n3</a></td>
</tr>
</tbody>
</table>

### overheid:Provincie {#4F6F9672}
Deze taxonomie bevat concepten die de provincies van de Nederlandse overheid beschrijven. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/terms/Provincie' target='_blank'><i>overheid:Provincie (standaarden.overheid.nl)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 18.271721214975276%;'>
<col id='col2' style='width: 81.72827878502473%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='0FD9B327'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='2DBA9318'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='3356FCC5'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='2B2BE20A'><a href='https://standaarden.overheid.nl/owms/terms/Provincie.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/Provincie.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='7A527532'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='4866EB49'><a href='https://standaarden.overheid.nl/owms/terms/Provincie.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/Provincie.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='24A978DA'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='148E1BFD'><a href='https://standaarden.overheid.nl/owms/terms/Provincie.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/Provincie.n3</a></td>
</tr>
</tbody>
</table>

### overheid:Waterschap {#33B63379}
Deze taxonomie bevat concepten die de waterschappen van de Nederlandse overheid beschrijven. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/4.0/doc/waardelijsten/overheid.waterschap' target='_blank'><i>overheid:Waterschap (standaarden.overheid.nl)</i></a>.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 17.600659288909817%;'>
<col id='col2' style='width: 82.39934071109019%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='36DCDAE1'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='51C5C9B8'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='2D794B1D'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='21435E1F'><a href='https://standaarden.overheid.nl/owms/terms/Waterschap.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/Waterschap.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='006C235A'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='4F94EE5D'><a href='https://standaarden.overheid.nl/owms/terms/Waterschap.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/Waterschap.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='70A54B63'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='1049FF24'><a href='https://standaarden.overheid.nl/owms/terms/Waterschap.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/Waterschap.n3</a></td>
</tr>
</tbody>
</table>

### Coverheid:TaxonomieBeleidsagenda {#4EDA2EA7}
Bevat concepten die de beleidsagenda van de Nederlandse overheid vertegenwoordigen. Deze lijst komt uit de <a href='https://standaarden.overheid.nl/owms/terms' target='_blank'><i>OWMS 4.0</i></a> en is raadpleegbaar via <a href='https://standaarden.overheid.nl/owms/4.0/doc/waardelijsten/overheid.taxonomiebeleidsagenda' target='_blank'><i>overheid:TaxonomieBeleidsagenda (standaarden.overheid.nl)</i></a>.
<blockquote><p id='64C8F486'>Er wordt nog onderzocht hoe de mapping van de <a href='https://standaarden.overheid.nl/owms/4.0/doc/waardelijsten/overheid.taxonomiebeleidsagenda' target='_blank'><i>overheid:TaxonomieBeleidsagenda (standaarden.overheid.nl)</i></a> naar de <a href='https://publications.europa.eu/resource/authority/data-theme' target='_blank'><i>mdr:DataTheme (publications.europa.eu)</i></a> aangeboden gaat worden.</blockquote>

<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 14.822227454673886%;'>
<col id='col2' style='width: 85.1777725453261%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='0C599AFD'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='649B9B5F'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='02B3671D'>XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='378780FA'><a href='https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.xml' target='_blank'>https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.xml</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='16E04FB1'>RDF/XML</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='365E09ED'><a href='https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.rdf' target='_blank'>https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.rdf</a></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='79DA4796'>N3</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='45F9325D'><a href='https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.n3' target='_blank'>https://standaarden.overheid.nl/owms/terms/TaxonomieBeleidsagenda.n3</a></td>
</tr>
</tbody>
</table>

### spdx:ChecksumAlgorithm {#25DAD7B7}
Bevat concepten die beschrijven welk algorithme gebruikt is om tot een hash te komen die als checksum dient van een bron. Alle concepten komen uit de <a href='http://spdx.org/rdf/terms' target='_blank'><i>spdx:ChecksumAlgorithm</i></a>.
<span style='background-color: cyan;'>spdx:ChecksumAlgorithm</span> is niet als LinkedData beschikbaar. Om deze reden biedt <a href='https://data.overheid.nl/' target='_blank'><i>data.overheid.nl</i></a> deze lijst zelf als LinkedData aan.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 14.24534965858253%;'>
<col id='col2' style='width: 85.75465034141747%;'>
</colgroup>
<thead valign='top'><tr><th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='54DD9C4D'><b>Serialisatie</b></th>
<th align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: #000000;'><p id='54C211AF'><b>Adres</b></th>
</tr>
</thead>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='48EFDE74'>Turtle</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><p id='3535DFBC'><a href='https://github.com/dataoverheid/dcat-ap-donl/raw/main/taxonomy/algorithms.ttl' target='_blank'>https://github.com/dataoverheid/dcat-ap-donl/raw/main/taxonomy/algorithms.ttl</a></td>
</tr>
</tbody>
</table>

