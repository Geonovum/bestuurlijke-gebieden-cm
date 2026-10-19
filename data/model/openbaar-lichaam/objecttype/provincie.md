## Provincie {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie}

<figure data-md-diagram="bfa0b746-27b8-49ba-b867-77a20e31f9b4">
<div data-include="data/model/openbaar-lichaam/objecttype/provincie.provincie-detail.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/objecttype/provincie.provincie-detail.png" alt="Provincie - detail" loading="lazy"></div>
<figcaption>Provincie - detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Provincie</td>
</tr>
<tr>
<th>Naam</th>
<td>Provincie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een provincie is een territoriaal openbaar lichaam met algemene bevoegdheden tussen gemeente en Rijk.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/provincie">http://begrippen.geostandaarden.nl/bg/id/begrip/provincie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-04-20</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Provincie.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie">Provincie</a>
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
<td>2022-04-20</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie_relatiesoort_bestuurt_provinciegebied">bestuurtProvinciegebied</a>
</td>
<td>
Provinciegebied waarin de provincie op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie_relatiesoort_bestuurt_provinciegebied">
<h4>bestuurtProvinciegebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#bestuurtProvinciegebied</td>
</tr>
<tr>
<th>Naam</th>
<td>bestuurtProvinciegebied</td>
</tr>
<tr>
<th>Alias</th>
<td>bestuurt provinciegebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Provinciegebied waarin de provincie op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-04-20</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie">Provincie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
