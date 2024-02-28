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

