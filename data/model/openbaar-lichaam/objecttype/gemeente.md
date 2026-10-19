## Gemeente {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente}

<figure data-md-diagram="682c1460-b576-4198-98d9-891e1db055e3">
<div data-include="data/model/openbaar-lichaam/objecttype/gemeente.gemeente-detail.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/objecttype/gemeente.gemeente-detail.png" alt="Gemeente - detail" loading="lazy"></div>
<figcaption>Gemeente - detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Gemeente</td>
</tr>
<tr>
<th>Naam</th>
<td>Gemeente</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een gemeente is het kleinste territoriaal openbaar lichaam met algemene bevoegdheden.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/gemeente">http://begrippen.geostandaarden.nl/bg/id/begrip/gemeente</a></td>
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
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Gemeente.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente">Gemeente</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-05-11</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente_relatiesoort_heeft_gemeentegebied">heeftGemeentegebied</a>
</td>
<td>
Gemeentegebied waarin de gemeente op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente_relatiesoort_heeft_gemeentegebied">
<h4>heeftGemeentegebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftGemeentegebied</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftGemeentegebied</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft gemeentegebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gemeentegebied waarin de gemeente op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1</td>
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
<td>Nee</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente">Gemeente</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
