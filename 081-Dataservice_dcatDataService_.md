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
<section data-include-format='markdown' data-include='081-endpoint_URL_nieuw.md'></section>
<section data-include-format='markdown' data-include='082-endpoint_description.md'></section>
<section data-include-format='markdown' data-include='083-serves_dataset.md'></section>
<section data-include-format='markdown' data-include='084-Voorbeelden.md'></section>
