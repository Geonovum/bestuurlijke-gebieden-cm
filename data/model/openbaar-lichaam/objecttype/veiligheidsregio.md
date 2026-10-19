## Veiligheidsregio {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio}

<figure data-md-diagram="63b8005b-3e50-4212-b108-c6984036c6d1">
<div data-include="data/model/openbaar-lichaam/objecttype/veiligheidsregio.veiligheidsregio-detail.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/objecttype/veiligheidsregio.veiligheidsregio-detail.png" alt="Veiligheidsregio-detail" loading="lazy"></div>
<figcaption>Veiligheidsregio-detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Veiligheidsregio</td>
</tr>
<tr>
<th>Naam</th>
<td>Veiligheidsregio</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een veiligheidsregio is een openbaar lichaam voor de samenwerking door verschillende besturen en diensten ten aanzien van taken op het terrein van brandweerzorg, rampenbeheersing, crisisbeheersing, geneeskundige hulpverlening en handhaving van de openbare orde en veiligheid.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>https://www.vrgooienvechtstreek.nl/onze-organisatie/de-veiligheidsregio</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregio">http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregio</a></td>
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
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio_generalisatie_openbaar_lichaam_uit_gemeenschappelijke_regeling" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Veiligheidsregio.generalisatie-OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio">Veiligheidsregio</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling">OpenbaarLichaamUitGemeenschappelijkeRegeling</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-10-14</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio_relatiesoort_heeft_veiligheidsregiogebied">heeftVeiligheidsregiogebied</a>
</td>
<td>
Veiligheidsregiogebied waarin de veiligheidsregio op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied">Veiligheidsregiogebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio_relatiesoort_heeft_veiligheidsregiogebied">
<h4>heeftVeiligheidsregiogebied</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftVeiligheidsregiogebied</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftVeiligheidsregiogebied</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft veiligheidsregiogebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Veiligheidsregiogebied waarin de veiligheidsregio op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio">Veiligheidsregio</a>
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
</section>
