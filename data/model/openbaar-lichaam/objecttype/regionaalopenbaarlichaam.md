## RegionaalOpenbaarLichaam {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Naam</th>
<td>RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Alias</th>
<td>Regionaal openbaar lichaam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een regionaal openbaar lichaam is, in de bestuurlijke indeling van het Koninkrijk der Nederlanden, een overheid die wettelijk bepaalde taken uitvoert binnen een bepaald ruimtelijk gebied.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>De belangrijkste regionale openbare lichamen zijn het Rijk, de provincies, de gemeenten en de waterschappen. De provincies en gemeenten worden in artikel 123 en verder van de Nederlandse Grondwet geregeld. De waterschappen in artikel 133.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/regionaal_openbaar_lichaam">http://begrippen.geostandaarden.nl/bg/id/begrip/regionaal_openbaar_lichaam</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-30</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_generalisatie_overheidsorganisatie" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#RegionaalOpenbaarLichaam.generalisatie-Overheidsorganisatie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie">Overheidsorganisatie</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-30</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Overzicht attribuutsoorten</h3>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_attribuutsoort_type">type</a>
</td>
<td>
Categorie waartoe het betreffende openbaar lichaam behoort.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam">TypeRegionaalOpenbaarLichaam</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Overzicht Relatiesoorten</h3>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_relatiesoort_heeft_bestuurlijk_gebied">heeftBestuurlijkGebied</a>
</td>
<td>
Relatie die aangeeft dat het regionaal openbaar lichaam het bestuurlijk gebied heeft.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details attribuutsoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_attribuutsoort_type">
<h4>type</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#type</td>
</tr>
<tr>
<th>Naam</th>
<td>type</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Categorie waartoe het betreffende openbaar lichaam behoort.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-08-17</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Ja</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_relatiesoort_heeft_bestuurlijk_gebied">
<h4>heeftBestuurlijkGebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftBestuurlijkGebied</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftBestuurlijkGebied</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft bestuurlijk gebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat het regionaal openbaar lichaam het bestuurlijk gebied heeft.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-30</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..*</td>
</tr>
<tr>
<th>Kardinaliteit relatie bron</th>
<td>1</td>
</tr>
<tr>
<th>Unidirectioneel</th>
<td>Ja</td>
</tr>
<tr>
<th>Aggregatietype</th>
<td>Geen</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Ja</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
