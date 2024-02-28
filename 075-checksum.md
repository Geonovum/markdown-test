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
<tbody valign='top'><tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>spdx:algorithm
</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='662F937C'>waardelijst spdx:ChecksumAlgorithm</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1
</code>

</td>
</tr>
<tr><td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>spdx:checksumValue
</code>

</td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><p id='60D21F1E'><code>rdfs:Literal</code> typed as <code>xsd:hexBinary</code></td>
<td align='left' style='border-top: 0pt none #000000; border-left: 0pt none #000000; border-bottom: 0pt none #000000; border-right: 0pt none #000000; background-color: none;'><code>1..1
</code>

</td>
</tr>
</tbody>
</table>

<aside class='issue'><p id='01CCA33C'><a href='https://github.com/dataoverheid/dcat-ap-donl/issues/10' target='_blank'><span style='color: #0000FF;'><u>Issue 10</u></span></a>: checksum<p id='229EF217'>Openstaande vraag: hoe ziet de vulling van checksum er precies uit? Ik zou verwachten dat behalve de waarde van de checksum ook het gebruikte hash-alogoritme om de waarde mee te berekenen wordt meegestuurd.</aside>

