## Domein Openbaar lichaam {#informatiemodel_cim_bg_domein_openbaar_lichaam}

<figure data-md-diagram="0bff1f59-8c83-3186-adfe-d88da88b0bcd">
<div data-include="data/model/openbaar-lichaam/package-view.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/package-view.png" alt="Domein Openbaar lichaam" loading="lazy"></div>
<figcaption>Domein Openbaar lichaam</figcaption>
</figure>

### Objecttypen

#### Overheidsorganisatie {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Overheidsorganisatie</td>
</tr>
<tr>
<th>Naam</th>
<td>Overheidsorganisatie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie die namens de overheid taken uitvoert en onder het gezag en toezicht van de overheid valt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/overheidsorganisatie">http://begrippen.geostandaarden.nl/bg/id/begrip/overheidsorganisatie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-30</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht attribuutsoorten</h5>    
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_naam">naam</a>
</td>
<td>
De voorkeursnaam van de organisatie</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_excl_soort">officieleNaamExclSoort</a>
</td>
<td>
De officiële naam van de organisatie zonder soortaanduiding, bijvoorbeeld &#39;&#39;s-Gravenhage&#39;</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_incl_soort">officieleNaamInclSoort</a>
</td>
<td>
De officiële naam van de organisatie met soortaanduiding, bijvoorbeeld &#39;gemeente &#39;s-Gravenhage&#39;</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_organisatiecode">organisatiecode</a>
</td>
<td>
De organisatiecode.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_naam">
<h6>naam</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/2000/01/rdf-schema#label</td>
</tr>
<tr>
<th>Naam</th>
<td>naam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De voorkeursnaam van de organisatie</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-09-10</td>
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
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_excl_soort">
<h6>officieleNaamExclSoort</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/officieleNaamExclSoort</td>
</tr>
<tr>
<th>Naam</th>
<td>officieleNaamExclSoort</td>
</tr>
<tr>
<th>Alias</th>
<td>Officiële naam exclusief soort</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De officiële naam van de organisatie zonder soortaanduiding, bijvoorbeeld &#39;&#39;s-Gravenhage&#39;</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..1</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_incl_soort">
<h6>officieleNaamInclSoort</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/officieleNaamInclSoort</td>
</tr>
<tr>
<th>Naam</th>
<td>officieleNaamInclSoort</td>
</tr>
<tr>
<th>Alias</th>
<td>Officiële naam inclusief soort</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De officiële naam van de organisatie met soortaanduiding, bijvoorbeeld &#39;gemeente &#39;s-Gravenhage&#39;</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
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
<td>0..1</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_overheidsorganisatie_attribuutsoort_organisatiecode">
<h6>organisatiecode</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/organisatiecode</td>
</tr>
<tr>
<th>Naam</th>
<td>organisatiecode</td>
</tr>
<tr>
<th>Alias</th>
<td>Organisatiecode</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De organisatiecode.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Deze is uniek voor elke organisatie en fungeert bovendien als local name (gegeven de namespace-conventies binnen de registers).</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/organisatiecode">http://begrippen.geostandaarden.nl/bg/id/begrip/organisatiecode</a></td>
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
<th>Indicatie afleidbaar</th>
<td>Nee</td>
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

#### RegionaalOpenbaarLichaam {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam}

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
<h5>Overzicht attribuutsoorten</h5>    
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
<h5>Overzicht Relatiesoorten</h5>
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
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_attribuutsoort_type">
<h6>type</h6>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam_relatiesoort_heeft_bestuurlijk_gebied">
<h6>heeftBestuurlijkGebied</h6>
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

#### Samenwerkingsorganisatie {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_samenwerkingsorganisatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Samenwerkingsorganisatie</td>
</tr>
<tr>
<th>Naam</th>
<td>Samenwerkingsorganisatie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie die in het leven is geroepen om een gemeenschappelijke regeling uit te voeren in een publiekrechtelijke of privaatrechtelijke constructie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/samenwerkingsorganisatie">http://begrippen.geostandaarden.nl/bg/id/begrip/samenwerkingsorganisatie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-10-14</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_samenwerkingsorganisatie_generalisatie_overheidsorganisatie" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Samenwerkingsorganisatie.generalisatie-Overheidsorganisatie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_samenwerkingsorganisatie">Samenwerkingsorganisatie</a>
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

#### OpenbaarLichaamUitGemeenschappelijkeRegeling {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Naam</th>
<td>OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Alias</th>
<td>Openbaar lichaam uit gemeenschappelijke regeling</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie die in het leven is geroepen om een gemeenschappelijke regeling uit te voeren uit hoofde van de Wet gemeenschappelijke regelingen (Wgr).</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/openbaar_lichaam_uit_gemeenschappelijke_regeling">http://begrippen.geostandaarden.nl/bg/id/begrip/openbaar_lichaam_uit_gemeenschappelijke_regeling</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-10-14</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling_generalisatie_samenwerkingsorganisatie" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#OpenbaarLichaamUitGemeenschappelijkeRegeling.generalisatie-Samenwerkingsorganisatie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling">OpenbaarLichaamUitGemeenschappelijkeRegeling</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_samenwerkingsorganisatie">Samenwerkingsorganisatie</a>
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
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#OpenbaarLichaamUitGemeenschappelijkeRegeling.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling">OpenbaarLichaamUitGemeenschappelijkeRegeling</a>
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

#### Gemeente {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente}

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
<h5>Overzicht Relatiesoorten</h5>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_gemeente_relatiesoort_heeft_gemeentegebied">
<h6>heeftGemeentegebied</h6>
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

#### Provincie {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie}

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
<h5>Overzicht Relatiesoorten</h5>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_provincie_relatiesoort_bestuurt_provinciegebied">
<h6>bestuurtProvinciegebied</h6>
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

#### Waterschap {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap}

<figure data-md-diagram="96c3ab79-94d5-48c6-8e26-0e50adb97d97">
<div data-include="data/model/openbaar-lichaam/objecttype/waterschap.waterschap-detail.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/objecttype/waterschap.waterschap-detail.png" alt="Waterschap - detail" loading="lazy"></div>
<figcaption>Waterschap - detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Waterschap</td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschap</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een waterschap is een territoriaal openbaar lichaam dat uitsluitend bevoegd is met betrekking tot de waterhuishouding.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/waterschap">http://begrippen.geostandaarden.nl/bg/id/begrip/waterschap</a></td>
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
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Waterschap.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap">Waterschap</a>
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
<h5>Overzicht Relatiesoorten</h5>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap_relatiesoort_heeft_waterschapsgebied">heeftWaterschapsgebied</a>
</td>
<td>
Waterschapsgebied waarin het waterschap op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap_relatiesoort_heeft_waterschapsgebied">
<h6>heeftWaterschapsgebied</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#bestuurtWaterschapsgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftWaterschapsgebied</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft waterschapsgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Waterschapsgebied waarin het waterschap op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap">Waterschap</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

#### Rijk {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk}

<figure data-md-diagram="8cc09e17-8c82-4db9-b815-9bed0c5277ef">
<div data-include="data/model/openbaar-lichaam/objecttype/rijk.rijk-detail.svg" data-include-format="html"><img src="data/model/openbaar-lichaam/objecttype/rijk.rijk-detail.png" alt="Rijk - detail" loading="lazy"></div>
<figcaption>Rijk - detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Rijk</td>
</tr>
<tr>
<th>Naam</th>
<td>Rijk</td>
</tr>
<tr>
<th>Alias</th>
<td>De Rijksoverheid</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>De klasse Rijk is de (singleton-) klasse van onderdelen van de Nederlandse overheid die wettelijke taken hebben op landelijk niveau: de ‘centrale overheid’</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/rijk">http://begrippen.geostandaarden.nl/bg/id/begrip/rijk</a></td>
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
<table id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Rijk.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
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
<h5>Overzicht Relatiesoorten</h5>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_aansluitende_zone">heeftAansluitendeZone</a>
</td>
<td>
Aansluitende zone waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone">AansluitendeZone</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_continentaal_plat">heeftContinentaalPlat</a>
</td>
<td>
Continentaal plat waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat">ContinentaalPlat</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_landgebied">heeftLandgebied</a>
</td>
<td>
Landgebied waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied">Landgebied</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_territoriale_zee">heeftTerritorialeZee</a>
</td>
<td>
Territoriale zee waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee">TerritorialeZee</a>
</td>
<td>
1..*</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_exclusieve_economische_zone">heeftExclusieveEconomischeZone</a>
</td>
<td>
Exclusieve economische zone waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone">ExclusieveEconomischeZone</a>
</td>
<td>
1..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_aansluitende_zone">
<h6>heeftAansluitendeZone</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftAansluitendeZone</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftAansluitendeZone</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft aansluitende zone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Aansluitende zone waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone">AansluitendeZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_continentaal_plat">
<h6>heeftContinentaalPlat</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftContinentaalPlat</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftContinentaalPlat</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft continentaal plat</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Continentaal plat waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat">ContinentaalPlat</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_landgebied">
<h6>heeftLandgebied</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftLandgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftLandgebied</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft landgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Landgebied waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_territoriale_zee">
<h6>heeftTerritorialeZee</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftTerritorialeZee</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftTerritorialeZee</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft territoriale zee</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Territoriale zee waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee">TerritorialeZee</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_exclusieve_economische_zone">
<h6>heeftExclusieveEconomischeZone</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#heeftExclusieveEconomischeZone</td>
</tr>
<tr>
<th>Naam</th>
<td>heeftExclusieveEconomischeZone</td>
</tr>
<tr>
<th>Alias</th>
<td>heeft exclusieve economische zone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Exclusieve economische zone waarin het Rijk op basis van wet- of regelgeving bepaalde taken uitvoert.</td>
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
<td>1..*</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk">Rijk</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone">ExclusieveEconomischeZone</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

#### Veiligheidsregio {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio}

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
<h5>Overzicht Relatiesoorten</h5>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_veiligheidsregio_relatiesoort_heeft_veiligheidsregiogebied">
<h6>heeftVeiligheidsregiogebied</h6>
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

### Enumeraties

#### TypeRegionaalOpenbaarLichaam {#informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#TypeRegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Naam</th>
<td>TypeRegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Alias</th>
<td>Type regionaal openbaar lichaam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Categorisering van een regionaal openbaar lichaam.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-06-01</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht waarden</h5>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 75%"></colgroup>
<tbody>
<tr>
  <th>Waarde</th>
  <th>Definitie</th>
</tr>
<tr id="informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam_enumeratiewaarde_gemeente">
<td>
Gemeente</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam_enumeratiewaarde_provincie">
<td>
Provincie</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam_enumeratiewaarde_rijk">
<td>
Rijk</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam_enumeratiewaarde_veiligheidsregio">
<td>
Veiligheidsregio</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_openbaar_lichaam_enumeratie_type_regionaal_openbaar_lichaam_enumeratiewaarde_waterschap">
<td>
Waterschap</td>
<td>
</td>
</tr>
</tbody>
</table>

</section>
