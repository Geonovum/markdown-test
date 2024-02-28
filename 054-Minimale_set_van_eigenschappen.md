#### Minimale set van eigenschappen {#34145E8C}
Onderstaand voorbeeld beschrijft een <code>dcat:Dataset</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>dcat:Dataset</code>.
<br/>
<br/>
<aside class='example'><p class='space-after' id='5F0114C7'>Voorbeeld 1: Minimale set van eigenschappen<pre class="text">&lt;https:∕∕data.overheid.nl∕dataset∕verkiezingsuitslag-tweede-kamer-2021&gt;
a dcat:Dataset;
    dct:identifier &lt;https://data.overheid.nl/dataset/verkiezingsuitslag-tweede-kamer-2021&gt;;
    dct:title "Verkiezingsuitslag Tweede Kamer 2021"@nl;
    dct:description "De dataset bevat de uitslagen van de verkiezing voor de Tweede Kamer van 17 maart 2021. De data is beschikbaar gesteld in EML formaat. De Kiesraad biedt geen ondersteuning voor het gebruik van het formaat. Bestemmingspagina: https://www.kiesraad.nl/verkiezingen/osv-en-eml/eml-standaard"@nl;
    dct:license &lt;http://creativecommons.org/publicdomain/zero/1.0/deed.nl&gt;;
    dct:creator &lt;http://standaarden.overheid.nl/owms/terms/Kiesraad&gt;;
    dct:publisher &lt;http://standaarden.overheid.nl/owms/terms/Kiesraad&gt;;
    dcat:contactPoint [a vcard:Organization ;
        vcard:fn "Kiesraad";
        vcard:hasEmail "kiesraad@kiesraad.nl";
        ];
    dcat:theme &lt;http://standaarden.overheid.nl/owms/terms/Parlement&gt;;
.
</pre>

</aside>

