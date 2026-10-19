## AansluitendeZone {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#AansluitendeZone</td>
</tr>
<tr>
<th>Naam</th>
<td>AansluitendeZone</td>
</tr>
<tr>
<th>Alias</th>
<td>Aansluitende zone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Het gebied buiten en grenzend aan de territoriale zee dat zich niet verder uitstrekt dan 24 zeemijlen vanaf de laagwaterlijn</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Rijkswet instelling aansluitende zone</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier de aansluitende zone zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_aansluitende_zone">http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_aansluitende_zone</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-06-01</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone_generalisatie_maritieme_zone" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#AansluitendeZone.generalisatie-MaritiemeZone</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone">AansluitendeZone</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_maritieme_zone">MaritiemeZone</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone_relatiesoort_is_aansluitende_zone_van">isAansluitendeZoneVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een aansluitende zone van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone_relatiesoort_is_aansluitende_zone_van">
<h4>isAansluitendeZoneVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isAansluitendeZoneVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isAansluitendeZoneVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is aansluitende zone van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een aansluitende zone van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone">AansluitendeZone</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
