## Gemeentegebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied}

<figure data-md-diagram="c74d8c27-9fa6-47d4-b752-38bc3912ab86">
<div data-include="data/model/bestuurlijk-gebied/objecttype/gemeentegebied.gemeentegebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/gemeentegebied.gemeentegebied-detail.png" alt="Gemeentegebied - detail" loading="lazy"></div>
<figcaption>Gemeentegebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/gemeentegebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Gemeentegebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Gemeentegebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij wet afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een gemeente met diverse bestuurlijke taken, ingesteld op basis van artikel 123 en 124 van de Grondwet, artikel 2:1 Burgerlijk Wetboek en artikel 3 van de Wet algemene regels herindeling.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Grondwet en Gemeentewet</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het gaat bij dit begrip nadrukkelijk om het grondgebied en niet om de juridische entiteit (bevoegd gezag). Een gemeente valt altijd volledig binnen een provincie. De geometrie van alle gemeenten in een provincie moeten de provincie volledig bedekken. Provincies mogen niet overlappen.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/gemeentegebied">http://begrippen.geostandaarden.nl/bg/id/begrip/gemeentegebied</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-23</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Gemeentegebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_ligt_in_provinciegebied">ligtInProvinciegebied</a>
</td>
<td>
De geometrische afbakening van het provinciegebied waarbinnen de geometrie van het gemeentegebied zich moet bevinden, en/of mee moet samenvallen.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied">Provinciegebied</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_ligt_in_veiligheidsregiogebied">ligtInVeiligheidsregiogebied</a>
</td>
<td>
De geometrische afbakening van het veiligheidsregiogebied waarbinnen de geometrie van het gemeentegebied zich moet bevinden, en/of mee moet samenvallen.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_is_gemeentegebied_van">isGemeentegebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een gemeentegebied van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente">Gemeente</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_ligt_in_provinciegebied">
<h4>ligtInProvinciegebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ligtInProvinciegebied</td>
</tr>
<tr>
<th>Naam</th>
<td>ligtInProvinciegebied</td>
</tr>
<tr>
<th>Alias</th>
<td>ligt in provinciegebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>De geometrische afbakening van het provinciegebied waarbinnen de geometrie van het gemeentegebied zich moet bevinden, en/of mee moet samenvallen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-29</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_ligt_in_veiligheidsregiogebied">
<h4>ligtInVeiligheidsregiogebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ligtInVeiligheidsregiogebied</td>
</tr>
<tr>
<th>Naam</th>
<td>ligtInVeiligheidsregiogebied</td>
</tr>
<tr>
<th>Alias</th>
<td>ligt in veiligheidsregiogebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>De geometrische afbakening van het veiligheidsregiogebied waarbinnen de geometrie van het gemeentegebied zich moet bevinden, en/of mee moet samenvallen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-05-11</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_is_gemeentegebied_van">
<h4>isGemeentegebiedVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isGemeentegebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isGemeentegebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is gemeentegebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een gemeentegebied van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied">Gemeentegebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente">Gemeente</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
