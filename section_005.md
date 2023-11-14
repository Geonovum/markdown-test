# Beschikbaar stellen {#647D7DE7}

De bronbestanden van ieder ruimtelijk instrument moeten beschikbaar worden gesteld door de bronhouder. In dit hoofdstuk zijn de eisen voor deze beschikbaarstelling gegeven, inclusief inhoud en opbouw van het Manifest en geleideformulier, dat hier een onderdeel van is.
## Eisen aan de beschikbaarstelling {#42F69F15}

Ieder ruimtelijk instrument dat is vastgelegd in het Manifest van een bronhouder dient door de bronhouder in zijn geheel beschikbaar te zijn gesteld. Dit betekent dat alle bronbestanden zoals genoemd in <a href='#d4e213'>Tabel 1</a> en <a href='#d4e757'>Tabel 2</a> beschikbaar zijn via het internet. Deze beschikbaarstelling moet voldoen aan een aantal eisen:
<br/>
<br/>

<ul><li>Publicatie van de manifesten en plannen door bronhouders van ruimtelijke plannen via standaard poort 443 voor HTTPS verkeer;</li>
<li>Het gebruik van een beveiligde HTTPS verbinding via TLS https://datatracker.ietf.org/doc/html/rfc8446 is wettelijk verplicht door de wet digitale overheid https://wetten.overheid.nl/BWBR0048156/2023-07-01. Gebruik hiervoor de richtlijnen van het NCSC https://www.ncsc.nl/onderwerpen/verbindingsbeveiliging/documenten/publicaties/2021/januari/19/ict-beveiligingsrichtlijnen-voor-transport-layer-security-2.1;</li>
<li>Voor de bestanden is de GET operatie van het transportprotocol van HTTP toegestaan conform de lijst van open standaarden van het Forum standaardisatie https://forumstandaardisatie.nl/open-standaarden/http;</li>
<li>Het gebruik van HTTP compressie via content encodings is onderdeel van de HTTP/1.1 standaard en is derhalve toegestaan; het gebruik hiervan kan een voordeel bieden bij het beschikbaar stellen van de potentieel erg grote planbestanden;</li>
<li>Alle bronbestanden dienen zonder autorisatie- of authenticatiemechanismen zoals inloggen beschikbaar te zijn en worden niet afgeschermd door bijvoorbeeld firewalls;</li>
<li>De beschikbaarstelling van een ruimtelijk instrument mag op iedere URL plaatsvinden en hoeft dus niet op de officiële website van de bronhouder te geschieden;</li>
<li>Alle bij het ruimtelijk instrument behorende bronbestanden worden binnen 1 virtuele directory beschikbaar gesteld.</li>
</ul>
<br/>
<br/>

De bronbestanden van ieder beschikbaar gesteld ruimtelijk instrument blijven toegankelijk totdat een instrument onherroepelijk in werking is getreden. Op dat moment blijven in elk geval de actuele versie van het instrument en alle eventuele daarbij behorende reactieve aanwijzingen en gerechtelijke uitspraken beschikbaar. Als een instrument geheel vervallen is, mag het in zijn geheel worden verwijderd van internet.
## Opbouw Manifest {#1A10E1C7}

Iedere bronhouder in Nederland stelt een Manifest beschikbaar. Het Manifest is een XML bestand dat een inhoudsopgave vormt van alle elektronisch beschikbare ruimtelijk instrumenten van de desbetreffende bronhouder. In het Manifest zijn de ruimtelijke instrumenten gerangschikt per dossiernummer. Aan ieder dossiernummer in het Manifest wordt een procedurestatus toegekend. De bronhouder houdt deze status per dossiernummer bij iedere wijziging actueel. Het Manifest is gewaarmerkt met een elektronische handtekening.
<br/>
<br/>

In aanvulling op het Manifest kent ieder ruimtelijk instrument een verplicht XML Geleideformulier met gedetailleerde informatie over het individueel instrument. Ook het geleideformulier is gewaarmerkt met een elektronische handtekening.
<br/>
<br/>

Het Manifest mag op ieder webadres (URL) beschikbaar worden gesteld. Het geleideformulier wordt beschikbaar gesteld binnen dezelfde virtuele directory als het instrument zelf.
<br/>
<br/>

Hoewel Manifest en geleideformulier beide een Signature element kennen, heeft dit element bij beide types documenten een andere inhoud en betekenis. In Hoofdstuk <a href='#1CDA4685'>6</a> wordt hier nader op ingegaan.
<br/>
<br/>

Het Manifest is als volgt opgebouwd:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E02'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E03'>Manifest</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E05'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E06'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E07'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E09'>overheidsCode</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E0A'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E0B'>CBS-code van de beleidsmatig verantwoordelijke overheid. Altijd 4 cijfers, indien nodig aangevuld met voorloopnullen. Ingeval Rijk “0000”. Ingeval provincie: CBS-code provincie met voorafgaand 2 voorloopnegens. In geval deelgemeente/stadsdeel: CBS-code gemeente.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E0D'>naamOverheid</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E0E'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E0F'>Naam van de voor het Manifest verantwoordelijke overheid.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E11'>datum</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E12'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E13'>Datum waarop het huidige Manifest is gegenereerd.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E15'>dossier</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E16'>1..*</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E17'>Het ordenend element waarbinnen alle ruimtelijke instrumenten met een identiek dossiernummer worden geplaatst.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E19'>signature</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E1A'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E1B'>het PKI-Overheid waarmerk.</td>
</tr>
</tbody>
</table>

Binnen ieder &lt;Dossier&gt; element worden de volgende gegevens opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E20'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E21'>Dossier</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E23'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E24'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E25'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E27'>id</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E28'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E29'>het dossiernummer van het desbetreffende Dossier conform het format zoals gegeven in Hoofdstuk 5 van de STRI2012</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E2B'>status</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E2C'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E2D'>De actuele procedurestatus van het desbetreffende Dossier. De volgende waarden zijn mogelijk:<ul><li><b>in voorbereiding</b></li>
<li><b>vastgesteld</b></li>
<li><b>geheel in werking</b></li>
<li><b>deels in werking</b></li>
<li><b>niet in werking</b></li>
<li><b>geheel onherroepelijk in werking</b></li>
<li><b>deels onherroepelijk in werking</b></li>
<li><b>vervallen</b></li>
<li><b>geconsolideerd</b></li>
</ul>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E38'>plan</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E39'>1..*</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E3A'>informatie over ieder beschikbaar gesteld ruimtelijk instrument binnen het Dossier</td>
</tr>
</tbody>
</table>

Bij ieder &lt;Plan&gt; element in het Dossier worden de volgende gegevens over het ruimtelijk instrument opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E40'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E41'>Plan (in Manifest)</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E43'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E44'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E45'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E47'>id</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E48'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E49'>het idn van het desbetreffende ruimtelijk instrument conform het format zoals gegeven in Hoofdstuk 5 van de STRI2012</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E4B'>naam</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E4C'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E4D'>De naam van het ruimtelijk instrument. De waarde is gelijk aan de Naam in het IMRO GML bestand.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E4F'>datum</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E50'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E51'>De datum van het ruimtelijk instrument. De Waarde is gelijk aan de Datum in het IMRO GML bestand.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E53'>geleideFormulier</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E54'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E55'>De URL van het geleideformulier van het ruimtelijk instrument</td>
</tr>
</tbody>
</table>

De exacte opbouw van het XML Manifest is vastgelegd in een XML Schema dat naast deze standaard beschikbaar is.
## Opbouw Geleideformulier {#293B3DB0}

Het geleideformulier is opgebouwd zoals weergegeven met de tabellen in deze paragraaf.
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E5D'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E5E'>Geleideformulier</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E60'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E61'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E62'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E64'>overheidsCode</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E65'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E66'>CBS-code van de beleidsmatig verantwoordelijke overheid. Altijd 4 cijfers, indien nodig aangevuld met voorloopnullen. Ingeval Rijk “0000”. Ingeval provincie: CBS-code provincie met voorafgaand 2 voorloopnegens. Ingeval deelgemeente/stadsdeel: CBS-code gemeente. De waarde is gelijk aan IMRO:overheidsCode in het IMRO GML bestand van het instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E68'>naamOverheid</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E69'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E6A'>Naam van de verantwoordelijke overheid. De waarde is gelijk aan IMRO:naamOverheid in het IMRO GML bestand van het instrument. In het geval dat de IMRO:naamOverheid in het IMRO GML bestand meer dan eens voorkomt, worden de waardes in dit attribuut achter elkaar gezet, gescheiden door komma’s.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E6C'>datum</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E6D'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E6E'>Datum waarop het geleideformulier is gegenereerd.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E70'>plan</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E71'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E72'>Het ordenend element waar binnen de informatie met betrekking tot een individueel ruimtelijk instrument wordt geplaatst</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E74'>signature</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E75'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E76'>het PKI-Overheid waarmerk</td>
</tr>
</tbody>
</table>

In het &lt;Plan&gt; element in het Geleideformulier worden de volgende gegevens over het ruimtelijk instrument opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E7B'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E7C'>Plan (in GeleideFormulier)</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E7E'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E7F'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E80'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E82'>id</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E83'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E84'>Identificatienummer van het instrument. De waarde is gelijk aan IMRO:identificatie in het IMRO GML bestand van het instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E86'>eigenschappen</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E87'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E88'>root element voor alle eigenschappen van het instrument</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E8A'>onderdelen</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E8B'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E8C'>root element van alle onderdelen behorende bij het instrument</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E8E'>supplementen</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E8F'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E90'>root element van de bij het instrument behorende supplementen</td>
</tr>
</tbody>
</table>

In het &lt;Eigenschappen&gt; element in het Geleideformulier worden de volgende gegevens over het ruimtelijk instrument opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7E95'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7E96'>Eigenschappen</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E98'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E99'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E9A'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E9C'>naam</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E9D'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7E9E'>De naam van het ruimtelijk instrument. De waarde is gelijk aan de Naam in het IMRO GML bestand.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA0'>type</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA1'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA2'>Het type instrument. De waarde is gelijk aan IMRO:typePlan in het IMRO GML bestand van het instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA4'>status</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA5'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EA6'>De status van het instrument. De volgende waarden zijn mogelijk:<ul><li><b>concept</b></li>
<li><b>voorontwerp</b></li>
<li><b>ontwerp</b></li>
<li><b>vastgesteld</b></li>
<li><b>geconsolideerd</b></li>
</ul>
<p id='647D7EAC'>De waarde is gelijk aan de status in het IMRO GML bestand.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EAE'>datum</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EAF'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB0'>Dit is de datum waarop de Status in werking is getreden of in werking treedt. De waarde is gelijk aan IMRO:datum in het IMRO GML bestand van het instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB2'>versieIMRO</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB3'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB4'>Dit geeft de gebruikte versie van IMRO weer die is gebruikt bij het coderen van het instrument. De waarde is gelijk aan IMRO: verwijzingNorm(norm) in het IMRO GML bestand van het instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB6'>versiePraktijkRichtlijn</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB7'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EB8'>Dit geeft de gebruikte Praktijkrichtlijn weer die is gebruikt bij het coderen van het instrument. De waarde is gelijk aan IMRO: verwijzingNorm(norm) in het IMRO GML bestand van het instrument.</td>
</tr>
</tbody>
</table>

In het &lt;Onderdelen&gt; element in het Geleideformulier wordt de volgende informatie over de beschikbaar gestelde bronbestanden opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7EC1'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7EC2'>Onderdelen</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EC4'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EC5'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EC6'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EC8'>basisUrl</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EC9'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ECA'>In dit attribuut wordt de virtuele directory gespecificeerd van alle onderliggende elementen.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ECC'>IMRO </td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ECD'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ECE'>bestandsnaam van het IMRO GML</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED0'>planteksten</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED1'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED2'>bestandsnaam van de XML planteksten</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED4'>regels</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED5'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED6'>bestandsnaam van de regels</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED8'>beleidsBesluitdocument</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7ED9'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EDA'>bestandsnaam van een beleids/besluitdocument</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EDC'>toelichting</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EDD'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EDE'>bestandsnaam van de toelichting</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE0'>vaststellingsbesluit</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE1'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE2'>bestandsnaam van het vaststellingsbesluit</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE4'>bijlage</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE5'>0..*</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE6'>bestandsnaam van een bijlage</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE8'>illustratie</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EE9'>0..*</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EEA'>bestandsnaam van een illustratie</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EEC'>geleideformulier</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EED'>1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EEE'>bestandsnaam van het XML geleideformulier</td>
</tr>
</tbody>
</table>

In het &lt;Supplementen&gt; element in het Geleideformulier worden de volgende gegevens over mogelijke supplementen opgenomen:
<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 25.860889395667048%;'>
<col id='col2' style='width: 6.465222348916762%;'>
<col id='col3' style='width: 67.67388825541619%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7EF4'>Klasse</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;' colspan='2'><p id='647D7EF5'>Supplementen</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EF7'><i>attribuutnaam</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EF8'><i>m</i></td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EF9'><i>Toelichting</i></td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EFB'>basisURL</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EFC'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EFD'>In dit attribuut wordt de virtuele directory gespecificeerd van alle onderliggende elementen. </td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7EFF'>startPagina</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7F00'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7F01'>Referentie naar een internetpagina over het instrument dat door de bronhouder beschikbaar is gesteld als startpunt van de verbeelding er van.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7F03'>CSS</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7F04'>0..1</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7F05'>Referentie naar een Cascading Style Sheet (CSS) voor de lay-out en presentatie van planteksten. Dit is van toepassing op zowel objectgerichte planteksten die vanuit XML naar HTML zijn getransformeerd, als niet-objectgerichte planregels in HTML of XHTML.</td>
</tr>
</tbody>
</table>

De exacte opbouw van het XML geleideformulier is vastgelegd in een XML Schema dat naast deze standaard beschikbaar is.
## Wijzigen reeds eerder gepubliceerde plannen {#5EBB12FD}

Ambtelijk foutherstel in een ruimtelijke plan of besluit door de bronhouder, zonder voorafgaand besluit, is het herstellen van de metadata c.q. de technische kenmerken van het ruimtelijk plan of besluit of het opheffen van inconsistenties in de planvoorraad tussen bronhouder en Ruimtelijkeplannen.nl. Het naderhand door de bronhouder aanpassen van reeds eerder gepubliceerde plannen kan en mag, indien het gaat om:
<ul><li>een (beperkte) set van metadata die van cruciaal belang is voor (blijvende) begrijpelijkheid, raadpleegbaarheid en bruikbaarheid van plannen, niet alleen in de huidige LV, maar ook in het DSO.</li>
<li>het ervoor zorgen dat, op grond van de bestaande verplichting daartoe in het Besluit ruimtelijke ordening (Bro), de lokaal aanwezige planvoorraad consistent is met de landelijke voorziening van de Wro Ruimtelijkeplannen.nl.</li>
</ul>
<br/>
<br/>

Bij gebreken aan de inhoud van het plan of besluit zal het bevoegd gezag een nieuw besluit moeten nemen of een nieuwe procedure moeten volgen.
## Aanvullende specificaties {#4FC40025}

Naast de voorwaarden voor het Manifest en Geleideformulier in voorgaande paragrafen, gelden deze aanvullende specificaties:
<ul><li>het is niet mogelijk om &lt;Plan&gt; elementen met een verschillend dossiernummer binnen hetzelfde &lt;Dossier&gt; element te plaatsen;</li>
<li>het is niet mogelijk om &lt;Plan&gt; elementen met hetzelfde dossiernummer in verschillende &lt;Dossier&gt; elementen te plaatsen;</li>
<li>het is niet mogelijk om meerdere &lt;Dossier&gt; elementen met hetzelfde dossiernummer te plaatsen;</li>
<li>&lt;Dossier&gt; elementen met de status geconsolideerd bevatten alleen &lt;Plan&gt; elementen met de status geconsolideerd;</li>
<li>&lt;Dossier&gt; elementen met de status vastgesteld, geheel in werking, deels in werking, niet in werking, geheel onherroepelijk in werking of deels onherroepelijk in werking bevatten altijd minstens één &lt;Plan&gt; element met de status vastgesteld of de status onherroepelijk.</li>
<li>&lt;Plan&gt; elementen met de status geconsolideerd komen alleen voor in &lt;Dossier&gt; elementen met de status geconsolideerd;</li>
<li>voor de opbouw van het Manifest en het Geleideformulier is een XML Schema beschikbaar, dat samen met deze standaard beschikbaar is.</li>
</ul>
Noot
De planstatus onherroepelijk wordt niet gebruikt in ruimtelijke plannen conform IMRO2012. De planstatus onherroepelijk is een planstatus uit IMRO2008, zie:
<a href='http://ro-standaarden.geonovum.nl/2008/1.1/20081224-IMRO2008.pdf' target='_blank'>http://ro-standaarden.geonovum.nl/2008/1.1/20081224-IMRO2008.pdf</a>
