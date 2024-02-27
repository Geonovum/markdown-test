# Verschillen tov DONL x.x en DCAT AP ?  [nog nader invullen]  {#7A3CA2D2}
## Introductie van nieuwe klassen  {#2A378139}
### dcat:DataService {#22A9D1A0}
De DataService klasse is geïntroduceerd in versie 2 van DCAT. Services die toegang geven tot een of meer datasets of processing functies, worden gezien als dcat:DataService. Het biedt andere mogelijkheden om toegang tot gegevens te beschrijven dan mogelijk is in de klasse dcat:Distributie. Het gebruik van dcat:DataService sluit het gebruik van  dcat:Distributie niet uit, ze kunnen beiden op een ander niveau toegang geven tot de data in een service. In dcat:Distributie wordt in de eigenschap dcat:downloadURL de URL opgenomen die rechtstreeks  een dataset in een specifiek mediatype oplevert, In de eigenschap  dcat:accessURL de URL die direct informatie geeft over de service inclusief zijn endPoints. Bijvoorbeeld  een capabilities document zijn, zoals http://services.rce.geovoorziening.nl/rce/wms?&request=GetCapabilities&service=WMS) In dit toepassingsprofiel is de DataService klasse optioneel. Dat betekent dat het mogelijk blijft om dataservices alleen te beschrijven met de klasse Distributie.
### dcat:DatasetSeries {#09E7C7C7}
## Nieuwe eigenschappen DONL 2 tov DONL 1.1 {#0BF13D69}
In het toepassingsprofiel worden nieuwe eigenschappen aangegeven met de tag nieuw.
De eigenschappen behorend tot de klasse dcat:DataService zijn nieuw.
Nieuw is access service zodat een distributie naar dcat:DataServices kan verwijzen.
Nieuw is conforms to om de vindbaarheid van datasets te verbeteren.
Nieuw zijn creator en qualified-attribution om een beter onderscheid te kunnen maken tussen welke rollen verschillende partijen hebben rondom de dataset.
Legal foundation is een aangepaste versie van de overheid:grondslag uit DCAT-AP-DONL 1.1.
