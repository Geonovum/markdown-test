#### Minimale set van eigenschappen {#0C0FA1D8}
Onderstaand voorbeeld beschrijft een <code>dcat:DataService</code> met enkel de verplichte eigenschappen. Dit is de meest minimale representatie van een <code>dcat:DataService</code>.
<aside class='example'><p id='4048F41E'>Voorbeeld 8: Minimale set van eigenschappen<pre class="text">&lt;OData/v4/2.0&gt; a dcat:DataService;
    dct:identifier &lt;OData/v4/2.0&gt;;
    dct:title "OData API"@nl;
    dct:description "Gebruik de OData API voor het opvragen van data met een zelfopgestelde zoekvraag in de vorm van een URL (query). De OData API levert de data in het machineleesbare bestandsformaat JSON."@nl;
    dct:license &lt;http://creativecommons.org/publicdomain/zero/1.0/deed.nl&gt;;
    dct:creator &lt;http://standaarden.overheid.nl/owms/terms/Tweede_Kamer_der_Staten-Generaal&gt;;
    dct:publisher &lt;http://standaarden.overheid.nl/owms/terms/Tweede_Kamer_der_Staten-Generaal&gt;;
    dcat:contactPoint [a vcard:Organization ;
        vcard:fn "Tweede Kamer der Staten-Generaal";
        vcard:hasEmail "opendata@tweedekamer.nl";
];
    dcat:theme &lt;http://standaarden.overheid.nl/owms/terms/Parlement&gt;;
    dcat:endpointURL &lt;https://gegevensmagazijn.tweedekamer.nl/OData/v4/2.0&gt;;
    dcat:endpointDescription &lt;https://opendata.tweedekamer.nl/documentatie/odata-api&gt;;
.
</pre>

</aside>

