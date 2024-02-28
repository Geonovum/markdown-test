#### Een DataService die Datasets ontsluit {#4EEF88C5}
De gemeente Nijmegen heeft een publiek beschikbare <code>OGC:WMS</code> webservice waarmee de gemeente gemaakte luchtfoto's aanbiedt. Een van de aangeboden luchtfoto's is de "Luchtfoto 2022" (De gemeente maakt jaarlijks luchtfoto's). Deze luchtfoto's kunnen individueel (of als bundel) als dataset aangeboden worden. De behoefte bestaat om de relaties tussen de dataset en de webservice duidelijk vast te leggen.
Dit voorbeeld uit zich in de volgende RDF (niet relevante eigenschappen zijn weggelaten):
<aside class='example'><p id='47EA093D'>Voorbeeld 9: Een DataService die Datasets ontsluit<pre class="text">&lt;https:∕∕opendata.nijmegen.nl∕dataset∕luchtfoto-2022&gt; a dcat:Dataset;
    dct:title "Luchtfoto 2022"@nl ;
    dcat:distribution &lt;odn.luchtfoto-2022.distribution.1&gt; ;
    dcat:distribution &lt;odn.luchtfoto-2022.distribution.2&gt; ;
</pre>

<pre class="text">&lt;odn.luchtfoto-2022.distribution.1&gt; [ a dcat:Distribution ;
    dct:title "Lage resolutie"@nl ;
    dcat:accessURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&service=WMS&version=1.3.0&request=GetMap&layers=Luchtfoto2022.ecw&styles=default&transparent=true&CRS=EPSG:28992&bbox=176999.975,420000.025,191999.975,435500.025&width=750&height=775&format=image∕png&gt;;
    dcat:accessService &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt;;
    ];
</pre>

<pre class="text">&lt;odn.luchtfoto-2022.distribution.2&gt; [ a dcat:Distribution ;
    dct:title "Hoge resolutie"@nl ;
    dcat:accessURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&service=WMS&version=1.3.0&request=GetMap&layers=Luchtfoto2022.ecw&styles=default&transparent=true&CRS=EPSG:28992&bbox=176999.975,420000.025,191999.975,435500.025&width=3000&height=3100&format=image∕png&gt; ;
    dcat:accessService &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt; ;
    ];
</pre>

<pre class="text">&lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto&gt; [ a dcat:DataService ;
    dcat:endpointURL &lt;https:∕∕services.nijmegen.nl∕geoservices∕wms∕extern_Luchtfoto?&request=getCapabilities&service=WMS&gt; ;
    rdf:servesDataset &lt;https:∕∕opendata.nijmegen.nl∕dataset∕luchtfoto-2022&gt; ;
    ];
.
</pre>

</aside>

We zien hier de dataset <code>https://opendata.nijmegen.nl/dataset/luchtfoto-2022</code> met een tweetal distributies. In de eigenschappen van de distributies is de relatie opgenomen via welke dataservice ze ontsloten worden. Daarnaast zien we de dataservice <code>https://services.nijmegen.nl/geoservices/wms/extern_Luchtfoto</code>. In de eigenschappen van deze dataservice is opgenomen dat deze de <code>https://opendata.nijmegen.nl/dataset/luchtfoto-2022</code> dataset ontsluit.
