## Veiligheidsregiogebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied}

<figure data-md-diagram="74b3a8c6-84ec-464e-808a-ea3c53621616">
<div data-include="data/model/bestuurlijk-gebied/objecttype/veiligheidsregiogebied.veiligheidsregiogebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/veiligheidsregiogebied.veiligheidsregiogebied-detail.png" alt="Veiligheidsregiogebied - detail" loading="lazy"></div>
<figcaption>Veiligheidsregiogebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/veiligheidsregiogebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Veiligheidsregiogebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Veiligheidsregiogebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij wet afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een veiligheidsregio met diverse bestuurlijke taken, ingesteld op basis van artikel 9 van de Wet Veiligheidsregio’s</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Wet Veiligheidsregio’s</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregiogebied">http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregiogebied</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-05-11</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Veiligheidsregiogebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-12-29</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied_relatiesoort_is_veiligheidsregiogebied_van">isVeiligheidsregiogebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een veiligheidsregiogebied van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio">Veiligheidsregio</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied_relatiesoort_is_veiligheidsregiogebied_van">
<h4>isVeiligheidsregiogebiedVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isVeiligheidsregiogebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isVeiligheidsregiogebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is veiligheidsregiogebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een veiligheidsregiogebied van een regionaal openbaar lichaam is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-09-19</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio">Veiligheidsregio</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
