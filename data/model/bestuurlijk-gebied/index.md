## Domein Bestuurlijk gebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied}

<figure data-md-diagram="d3377e86-4b10-35f5-a084-d597da5e2c2b">
<div data-include="data/model/bestuurlijk-gebied/package-view.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/package-view.png" alt="Domein Bestuurlijk gebied" loading="lazy"></div>
<figcaption>Domein Bestuurlijk gebied</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/index.md"></div>

### Objecttypen

#### RegistratieveRuimte {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#RegistratieveRuimte</td>
</tr>
<tr>
<th>Naam</th>
<td>RegistratieveRuimte</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Op basis van wet- of regelgeving afgebakende ruimte die als eenheid geldt van politiek-bestuurlijke verantwoordelijkheid of voor bedrijfsvoering.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Dit objecttype is gelijk aan het objecttype Registratieve ruimte uit NEN 3610, maar is opgenomen als specialisatie daarvan omdat er specifieke kenmerken voor zijn gedefinieerd.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/registratieve_ruimte">http://begrippen.geostandaarden.nl/bg/id/begrip/registratieve_ruimte</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte_generalisatie_registratieve_ruimte" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#RegistratieveRuimte.generalisatie-RegistratieveRuimte</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_nen3610_domein_semantisch_model_objecttype_registratieve_ruimte">RegistratieveRuimte (NEN 3610:2022 - Basismodel geo-informatie)</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-23</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte_attribuutsoort_status">status</a>
</td>
<td>
Fase van de levenscyclus waarin een bestuurlijk gebied zich bevindt.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte">StatusRegistratieveRuimte</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte_attribuutsoort_status">
<h6>status</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#status</td>
</tr>
<tr>
<th>Naam</th>
<td>status</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fase van de levenscyclus waarin een bestuurlijk gebied zich bevindt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-04-22</td>
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

#### BestuurlijkGebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied}

<figure data-md-diagram="9f8f56b9-2394-4def-ba62-30c95d3e0132">
<div data-include="data/model/bestuurlijk-gebied/objecttype/bestuurlijkgebied.bestuurlijkgebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/bestuurlijkgebied.bestuurlijkgebied-detail.png" alt="BestuurlijkGebied - detail" loading="lazy"></div>
<figcaption>BestuurlijkGebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/bestuurlijkgebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#BestuurlijkGebied</td>
</tr>
<tr>
<th>Naam</th>
<td>BestuurlijkGebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een bestuurlijk gebied is een registratieve ruimte die op basis van wet- of regelgeving als eenheid geldt van bestuurlijke verantwoordelijkheid.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Dit betreft bijvoorbeeld de gebieden behorende bij de vier formele bestuurslagen uit de Grondwet (Rijk, provincie, waterschap, gemeente), maar kan ook gebieden van bestuurlijke samenwerkingsverbanden met eigen politiek/bestuurlijke verantwoordelijkheid omvatten. Een voorbeeld daarvan betreft de veiligheidsregio’s.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/bestuurlijk_gebied">http://begrippen.geostandaarden.nl/bg/id/begrip/bestuurlijk_gebied</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_generalisatie_registratieve_ruimte" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#BestuurlijkGebied.generalisatie-RegistratieveRuimte</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-23</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_naam">naam</a>
</td>
<td>
Naam van een object.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebied op land dat door een openbaar lichaam wordt bestuurd.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_type">type</a>
</td>
<td>
Categorie waartoe het betreffende bestuurlijke gebied behoort.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied">TypeBestuurlijkGebied</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_is_gebied_van">isGebiedVan</a>
</td>
<td>
Relatie die aangeeft dat het gebied bestuurd wordt door de bestuurder.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_ligt_in_bestuurlijk_gebied">ligtInBestuurlijkGebied</a>
</td>
<td>
De geometrische afbakening van het bevattendGebied, waarbinnen de geometrie van het bevatteGebied, zich moet bevinden, en/of mee moet samenvallen.</td>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_naam">
<h6>naam</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#naam</td>
</tr>
<tr>
<th>Naam</th>
<td>naam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Naam van een object.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Breed geaccepteerde benaming van een gebied zoals deze is toegekend of zoals deze in de volksmond bekend staat.</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-10-15</td>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie">
<h6>geometrie</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#geometrie</td>
</tr>
<tr>
<th>Naam</th>
<td>geometrie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geometrische representatie van een gebied op land dat door een openbaar lichaam wordt bestuurd.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-05-31</td>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_type">
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
<td>Categorie waartoe het betreffende bestuurlijke gebied behoort.</td>
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
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_is_gebied_van">
<h6>isGebiedVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isGebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isGebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is gebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat het gebied bestuurd wordt door de bestuurder.</td>
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
<td>Ja</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_ligt_in_bestuurlijk_gebied">
<h6>ligtInBestuurlijkGebied</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ligtInBestuurlijkGebied</td>
</tr>
<tr>
<th>Naam</th>
<td>ligtInBestuurlijkGebied</td>
</tr>
<tr>
<th>Alias</th>
<td>ligtIn bestuurlijk gebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>De geometrische afbakening van het bevattendGebied, waarbinnen de geometrie van het bevatteGebied, zich moet bevinden, en/of mee moet samenvallen.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Dit kan worden afgeleid op basis van de relaties:

- ligtInLandgebied
- ligtInProvinciegebied
- ligtInVeiligheidsregiogebied</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-08-19</td>
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
<td>Ja</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
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

#### Gemeentegebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied}

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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied_relatiesoort_ligt_in_provinciegebied">
<h6>ligtInProvinciegebied</h6>
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
<h6>ligtInVeiligheidsregiogebied</h6>
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
<h6>isGemeentegebiedVan</h6>
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

#### Provinciegebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied}

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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied_relatiesoort_ligt_in_landgebied">
<h6>ligtInLandgebied</h6>
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
<h6>isProvinciegebiedVan</h6>
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

#### Landgebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied}

<figure data-md-diagram="93e29841-b290-4801-a35f-b05f0ea03ec8">
<div data-include="data/model/bestuurlijk-gebied/objecttype/landgebied.landgebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/landgebied.landgebied-detail.png" alt="Landgebied - detail" loading="lazy"></div>
<figcaption>Landgebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/landgebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Landgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Landgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gebied aan de landzijde van de basislijn als bedoeld in artikel 2, eerste lid, van het Verdrag van de Verenigde Naties inzake het recht van de zee.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/landgebied">http://begrippen.geostandaarden.nl/bg/id/begrip/landgebied</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Landgebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied">Landgebied</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied_relatiesoort_is_landgebied_van">isLandgebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een landgebied van een regionaal openbaar lichaam is.</td>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied_relatiesoort_is_landgebied_van">
<h6>isLandgebiedVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isLandgebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isLandgebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is landgebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een landgebied van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_landgebied">Landgebied</a>
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

#### Waterschapsgebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied}

<figure data-md-diagram="9703e48f-1981-4d41-b87b-fb59fe1c603f">
<div data-include="data/model/bestuurlijk-gebied/objecttype/waterschapsgebied.waterschapsgebied-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/waterschapsgebied.waterschapsgebied-detail.png" alt="Waterschapsgebied - detail" loading="lazy"></div>
<figcaption>Waterschapsgebied - detail</figcaption>
</figure>

<div data-include-format="markdown" data-include="md-notes/bestuurlijk-gebied/objecttype/waterschapsgebied.md"></div>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Waterschapsgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschapsgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij wet afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een waterschap welke de waterstaatskundige verzorging van dat gebied ten doel heeft, ingesteld op basis van artikel 133 van de Grondwet en de Waterschapswet.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Grondwet, Waterschapswet en INSPIRE</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het &#39;Waterschapsgebied&#39; betreft het administratief gebied.

Het administratief gebied betreft de geografische representatie van de verkiezingsgrenzen zoals die door de waterschappen zijn vastgelegd. Het gaat bij dit begrip nadrukkelijk om het grondgebied en niet om de juridische entiteit (bevoegd gezag).

Dit gebied is inclusief de grote wateren die niet door de waterschappen beheerd worden, maar door Rijkswaterstaat. Het gaat dus om het gebied waarin het waterschap de verkiezingen uitschrijft.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/waterschapsgebied">http://begrippen.geostandaarden.nl/bg/id/begrip/waterschapsgebied</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Waterschapsgebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_relatiesoort_is_waterschapsgebied_van">isWaterschapsgebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een waterschapsgebied van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap">Waterschap</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_relatiesoort_is_waterschapsgebied_van">
<h6>isWaterschapsgebiedVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isWaterschapsgebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isWaterschapsgebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is waterschapsgebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een waterschapsgebied van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_waterschap">Waterschap</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

#### Veiligheidsregiogebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied}

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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied_relatiesoort_is_veiligheidsregiogebied_van">
<h6>isVeiligheidsregiogebiedVan</h6>
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

#### MaritiemeZone {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_maritieme_zone}

<figure data-md-diagram="fe710b7e-6dd8-4e51-9613-893cb06e96c5">
<div data-include="data/model/bestuurlijk-gebied/objecttype/maritiemezone.maritiemezone-detail.svg" data-include-format="html"><img src="data/model/bestuurlijk-gebied/objecttype/maritiemezone.maritiemezone-detail.png" alt="MaritiemeZone - detail" loading="lazy"></div>
<figcaption>MaritiemeZone - detail</figcaption>
</figure>

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#MaritiemeZone</td>
</tr>
<tr>
<th>Naam</th>
<td>MaritiemeZone</td>
</tr>
<tr>
<th>Alias</th>
<td>Maritieme zone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een zeegebied, inclusief de zeebodem en de ondergrond daarvan, waarbinnen een kuststaat soevereiniteit, soevereine rechten of rechtsmacht uitoefent, zoals gedefinieerd in het Verdrag van de Verenigde Naties inzake het recht van de zee.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>UNCLOS</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/maritieme_zone">http://begrippen.geostandaarden.nl/bg/id/begrip/maritieme_zone</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-12-29</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_maritieme_zone_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#MaritiemeZone.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_maritieme_zone">MaritiemeZone</a>
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

#### TerritorialeZee {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#TerritorialeZee</td>
</tr>
<tr>
<th>Naam</th>
<td>TerritorialeZee</td>
</tr>
<tr>
<th>Alias</th>
<td>Territoriale zee</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Het gebied vanaf de laagwaterlijn tot 12 zeemijl uit de kust dat behoort bij het Rijk.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Wet grenzen Nederlandse territoriale zee</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier de territoriale zee zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie.

Dit gebied is ook wel bekend als “de 12-mijlszone”. In het Eems-Dollard gebied is er tussen Nederland en Duitsland geen formeel grensverdrag en dus geen wederzijds bevestigde begrenzing van de territoriale zee.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_territoriale_zee">http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_territoriale_zee</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee_generalisatie_maritieme_zone" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#TerritorialeZee.generalisatie-MaritiemeZone</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee">TerritorialeZee</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee_relatiesoort_is_territoriale_zee_van">isTerritorialeZeeVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een territoriale zee van een regionaal openbaar lichaam is.</td>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee_relatiesoort_is_territoriale_zee_van">
<h6>isTerritorialeZeeVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isTerritorialeZeeVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isTerritorialeZeeVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is territoriale zee van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een territoriale zee van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee">TerritorialeZee</a>
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

#### AansluitendeZone {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone}

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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone_relatiesoort_is_aansluitende_zone_van">
<h6>isAansluitendeZoneVan</h6>
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

#### ExclusieveEconomischeZone {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ExclusieveEconomischeZone</td>
</tr>
<tr>
<th>Naam</th>
<td>ExclusieveEconomischeZone</td>
</tr>
<tr>
<th>Alias</th>
<td>Exclusieve economische zone</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Het gebied buiten en grenzend aan de territoriale zee dat zich niet verder uitstrekt dan tweehonderd zeemijlen vanaf de laagwaterlijn.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Rijkswet instelling exclusieve economische zone</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier de Nederlandse exclusieve economische zone zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_exclusieve_economische_zone">http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_exclusieve_economische_zone</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone_generalisatie_maritieme_zone" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ExclusieveEconomischeZone.generalisatie-MaritiemeZone</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone">ExclusieveEconomischeZone</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone_relatiesoort_is_exclusieve_economische_zone_van">isExclusieveEconomischeZoneVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een exclusieve economische zone van een regionaal openbaar lichaam is.</td>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone_relatiesoort_is_exclusieve_economische_zone_van">
<h6>isExclusieveEconomischeZoneVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isExclusieveEconomischeZoneVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isExclusieveEconomischeZoneVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is exclusieve economische zone van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een exclusieve economische zone van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone">ExclusieveEconomischeZone</a>
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

#### ContinentaalPlat {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ContinentaalPlat</td>
</tr>
<tr>
<th>Naam</th>
<td>ContinentaalPlat</td>
</tr>
<tr>
<th>Alias</th>
<td>Continentaal plat</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Het onder de Noordzee gelegen deel van de zeebodem en de ondergrond daarvan, waarop het Koninkrijk soevereine rechten heeft, en gelegen is buiten en grenzend aan de territoriale zee.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Mijnwet continentaal plat</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het betreft hier het Nederlandse continentaal plat zoals nu reeds wordt vastgelegd door de Dienst der Hydrografie.

Binnen het Europese deel van het Rijk kent deze dezelfde contour als de Nederlandse Exclusieve Economische Zone.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_continentaal_plat">http://begrippen.geostandaarden.nl/bg/id/begrip/nederlandse_continentaal_plat</a></td>
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
<table id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat_generalisatie_maritieme_zone" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#ContinentaalPlat.generalisatie-MaritiemeZone</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat">ContinentaalPlat</a>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat_relatiesoort_is_continentaal_plat_van">isContinentaalPlatVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een continentaal plat van een regionaal openbaar lichaam is.</td>
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
<h5>Details Relatiesoorten</h5>
<section class="notoc" id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat_relatiesoort_is_continentaal_plat_van">
<h6>isContinentaalPlatVan</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isContinentaalPlatVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isContinentaalPlatVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is continentaal plat van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een continentaal plat van een regionaal openbaar lichaam is.</td>
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
<a class="link" href="#informatiemodel_cim_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat">ContinentaalPlat</a>
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

### Keuzen tussen datatypen

#### VlakOfMultivlak {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_keuze_datatype__vlak_of_multivlak}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#VlakOfMultivlak</td>
</tr>
<tr>
<th>Naam</th>
<td>VlakOfMultivlak</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Keuze uit een vlak- of multivlakgeometrie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-30</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht datatypekeuzen</h5>
<table style="width: 100%">
<colgroup style="width: 50%"></colgroup>
<tbody>
<tr>
  <th>Datatype</th>
</tr>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_Surface"> GM_Surface</a>
</td>
<tr>
<td>
<a class="external-link" href="https://geonovum.github.io/uml-datatypen/#global_class_ISO191072003_GM_MultiSurface"> GM_MultiSurface</a>
</td>
</tbody>
</table>
</section>

### Enumeraties

#### TypeBestuurlijkGebied {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#TypeBestuurlijkGebied</td>
</tr>
<tr>
<th>Naam</th>
<td>TypeBestuurlijkGebied</td>
</tr>
<tr>
<th>Alias</th>
<td>Type bestuurlijk gebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Categorisering van een bestuurlijk gebied.</td>
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
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_aansluitende_zone">
<td>
Aansluitende zone</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_continentaal_plat">
<td>
Continentaal plat</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_exclusieve_economische_zone">
<td>
Exclusieve economische zone</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_gemeentegebied">
<td>
Gemeentegebied</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_provinciegebied">
<td>
Provinciegebied</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_landgebied">
<td>
Landgebied</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_territoriale_zee">
<td>
Territoriale zee</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_veiligheidsregiogebied">
<td>
Veiligheidsregiogebied</td>
<td>
</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_type_bestuurlijk_gebied_enumeratiewaarde_waterschapsgebied">
<td>
Waterschapsgebied</td>
<td>
</td>
</tr>
</tbody>
</table>

</section>

#### StatusRegistratieveRuimte {#informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#StatusRegistratieveRuimte</td>
</tr>
<tr>
<th>Naam</th>
<td>StatusRegistratieveRuimte</td>
</tr>
<tr>
<th>Alias</th>
<td>Status registratieve ruimte</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fasen van de levenscycli van een registratieve ruimte.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/levensfase ">http://begrippen.geostandaarden.nl/bg/id/begrip/levensfase </a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2022-03-29</td>
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
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte_enumeratiewaarde_ontwerp">
<td>
Ontwerp</td>
<td>
Object waarvan de vaststelling wordt voorbereid.</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte_enumeratiewaarde_niet_gerealiseerd">
<td>
Niet gerealiseerd</td>
<td>
Object waarvan de het ontwerp niet is gerealiseerd.</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte_enumeratiewaarde_vastgesteld">
<td>
Vastgesteld</td>
<td>
Object dat door het bevoegd gezag is benoemd of afgebakend op grond van wet- of regelgeving.</td>
</tr>
<tr id="informatiemodel_cim_bg_domein_bestuurlijk_gebied_enumeratie_status_registratieve_ruimte_enumeratiewaarde_ingetrokken">
<td>
Ingetrokken</td>
<td>
Object dat door het bevoegd gezag is ingetrokken op grond van wet- of regelgeving.</td>
</tr>
</tbody>
</table>

</section>
