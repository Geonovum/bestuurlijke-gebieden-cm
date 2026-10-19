## Provinciegebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied}

<figure data-md-diagram="fdebe630-2f89-4048-aa52-ef0c1a0a272c">
<div data-include="data/model/bestuurlijk-gebied/objecttype/provinciegebied.provinciegebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/provinciegebied.provinciegebied-detail.png" alt="Provinciegebied - detail" loading="lazy"></div>
<figcaption>Provinciegebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/provinciegebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Provinciegebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Provinciegebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij wet afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een provincie met diverse bestuurlijke taken, ingesteld op basis van artikel 123 en 124 van de Grondwet, artikel 2:1 Burgerlijk Wetboek en artikel 13 van de Wet algemene regels herindeling.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Grondwet en Provinciewet</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het gaat bij dit begrip nadrukkelijk om het grondgebied en niet om de juridische entiteit (bevoegd gezag). Een provincie valt altijd volledig binnen het Europese deel van het Koninkrijk der Nederlanden. De geometrie van alle provincies moeten het Europese deel van het grondgebied van Nederland op land volledig bedekken. Provincies mogen niet overlappen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/provinciegebied">http://begrippen.geostandaarden.nl/bg/id/begrip/provinciegebied</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-29</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Provinciegebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_relatiesoort_ligt_in_landgebied">ligtInLandgebied</a>
</td>
<td>
De geometrische afbakening van het landgebied waarbinnen de geometrie van het provinciegebied zich moet bevinden, en/of mee moet samenvallen.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied">Landgebied</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_relatiesoort_is_provinciegebied_van">isProvinciegebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een provinciegebied van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie">Provincie</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_relatiesoort_ligt_in_landgebied">
<h4>ligtInLandgebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ligtInLandgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>ligtInLandgebied</td>
</tr>
<tr>
<th>Alias</th>
<td>ligt in landgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>De geometrische afbakening van het landgebied waarbinnen de geometrie van het provinciegebied zich moet bevinden, en/of mee moet samenvallen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
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
<td>0..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied">Landgebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_relatiesoort_is_provinciegebied_van">
<h4>isProvinciegebiedVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isProvinciegebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isProvinciegebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is provinciegebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een provinciegebied van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie">Provincie</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
