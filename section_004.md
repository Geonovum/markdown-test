# Identificatienummer en bestandsnaam {#647D7DA1}

Ieder ruimtelijk instrument kent een eigen identificatienummer (idn). In dit hoofdstuk is aangegeven hoe de opbouw van dit idn is. Tevens zijn in dit hoofdstuk de eisen voor de bestandsnamen van de bronbestanden vastgelegd, waarvan het idn een belangrijke basis is.

## Identificatienummer {#647D7DA3}

Ieder ruimtelijk instrument kent een eigen identificatienummer (idn). Het idn is beschreven door middel van een reguliere expressie, als volgt:

[WR]<br/>
<br/>

NL\.(IMRO\.[0-9]{4}\.[A-Za-z0-9]{1,18}-[A-Za-z0-9]{4}

[WR]<br/>
<br/>

In <a href='#d4e2277'>Tabel 5</a> worden de onderdelen van deze reguliere expressie nader verklaard.

<table style='width: 100%;'><caption>Onderdelen van het identificatienummer</caption>
<colgroup><col id='col1' style='width: 22.58504949368529%;'>
<col id='col2' style='width: 77.41495050631471%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7DAC'>Onderdeel reg. exp.</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7DAD'>Betekenis </td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DAF'>NL\.(IMRO)\.</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB1'>de namespace NL.IMRO. als vaste tekst</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB3'>[0-9]{4}</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB4'>CBS code van de verantwoordelijke overheid. Altijd 4 cijfers, indien nodig aangevuld met voorloopnullen. Ingeval Rijk “0000”. De CBS-code van de provincie wordt voorafgegaan door 2 voorloopnegens. Ingeval deelgemeente/stadsdeel: CBS-code gemeente.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB6'>\.</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB7'>Een punt .</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DB9'>[A-Za-z0-9]{1,18}</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DBA'>Minimaal 1 en maximaal 18 alfanumerieke tekens, te bepalen door de bronhouder</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DBC'>- </td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DBD'>Een liggend streepje -</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DBF'>[A-Za-z0-9]{4}</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DC0'>Vier alfanumerieke karakters voor de door de bronhouder te bepalen versiecode van het instrument binnen het desbetreffende dossier. De versiecode bestaat uit exact 4 alfanumerieke karakters. De versiecode is uniek voor alle instrumenten die met hetzelfde dossiernummer op een openbare weblocatie beschikbaar gesteld en in het Manifest aangeduid zijn. </td>
</tr>
</tbody>
</table>

Het gedeelte van het identificatienummer tot aan het liggend streepje wordt het dossiernummer genoemd. De reguliere expressie voor het dossiernummer is derhalve als volgt:

[WR]<br/>
<br/>

NL\.(IMRO)\.[0-9]{4}\.[A-Za-z0-9]{1,18}

## Bestandsnaam vereisten {#4036FA61}

Voor ieder bronbestand worden in <a href='#d4e213'>Tabel 1</a> en <a href='#d4e757'>Tabel 2</a> eisen gesteld aan de bestandsnaam. De reguliere expressie waarmee de naam van een bestand wordt beschreven, is als volgt:

[WR]<br/>
<br/>

([a-z]{1,2}_)?NL\.(IMRO)\.[0-9]{4}\.[A-Za-z0-9]{1,18}-[A-Za-z0-9]{4}

(_[A-Za-z0-9\.]{1,20})?\.(html|htm|xhtml|xml|gml|pdf|png|jpg|jpeg)

[WR]<br/>
<br/>

In <a href='#d4e2517'>Tabel 6</a> worden de onderdelen van deze reguliere expressie nader verklaard.

<table style='width: 100%;'><caption>Onderdelen van de bestandsnaam vereisten</caption>
<colgroup><col id='col1' style='width: 43.73648879280919%;'>
<col id='col2' style='width: 56.26351120719081%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7DD1'>Onderdeel</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: #4F81BD;'><p id='647D7DD2'>Betekenis </td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DD4'>([a-z]{1,2}_)?</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DD5'>Het type onderdeel als één of twee letters en een underscore _ ; dit onderdeel wordt bij het GML bestand niet toegepast en is daarom optioneel; de beschrijving van de lettercodes wordt nader uitgewerkt bij de bestandsnaamconventies.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DD7'>NL\.(IMRO)\.[0-9]{4}\.[A-Za-z0-9]{1,18}-[A-Za-z0-9]{4}</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DD8'>idn van het ruimtelijk instrument.</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DDA'>(_[A-Za-z0-9\.]{1,20})?</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DDB'>bij bijlagen en illustraties wordt het identificatienummer gevolgd door een underscore _ en daarna een nadere aanduiding van minimaal 1 en maximaal 20 alfanumerieke tekens en punten, te bepalen door de bronhouder. </td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DDD'>\.</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DDE'>Een punt .</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DE0'>(html|htm|xhtml|xml|gml|pdf|png|jpg|jpeg)</td>
<td align='left' style='border-top: 0.5pt solid #95B3D7; border-left: 0.5pt solid #95B3D7; border-bottom: 0.5pt solid #95B3D7; border-right: 0.5pt solid #95B3D7; background-color: none;'><p id='647D7DE1'>De mogelijke bestandsextensies; de exacte relaties tussen onderdelen en bestandsformaten is nader uitgewerkt in paragraaf <a href='#4036FA61'>4.2</a>.</td>
</tr>
</tbody>
</table>

