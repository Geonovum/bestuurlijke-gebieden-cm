# Conceptueel Informatiemodel Bestuurlijke Gebieden {#informatiemodel_cim_bg}

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

## Extern NEN 3610:2022 - Basismodel geo-informatie {#extern_nen_3610_2022_basismodel_geo_informatie}

<figure data-md-diagram="10f0e091-0d9f-3efb-8540-b6fcf92e4240">
<div data-include="data/model/nen-3610-2022-basismodel-geo-informatie/package-view.svg" data-include-format="html"><img src="data/model/nen-3610-2022-basismodel-geo-informatie/package-view.png" alt="Extern NEN 3610:2022 - Basismodel geo-informatie" loading="lazy"></div>
<figcaption>Extern NEN 3610:2022 - Basismodel geo-informatie</figcaption>
</figure>

### Objecttypen

#### GeoObject {#informatiemodel_nen3610_domein_semantisch_model_objecttype_geo_object}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:NEN3610:SemantischModel:GeoObject</td>
</tr>
<tr>
<th>Naam</th>
<td>GeoObject</td>
</tr>
<tr>
<th>Alias</th>
<td>Geo-object</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een fenomeen in de werkelijkheid dat direct of indirect is geassocieerd met een locatie relatief ten opzichte van de aarde.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

#### VirtueleRuimte {#informatiemodel_nen3610_domein_semantisch_model_objecttype_virtuele_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:NEN3610:SemantischModel:VirtueleRuimte</td>
</tr>
<tr>
<th>Naam</th>
<td>VirtueleRuimte</td>
</tr>
<tr>
<th>Alias</th>
<td>Virtuele ruimte</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geo-object dat zich geheel of gedeeltelijk niet-materieel manifesteert en dus slechts in abstracte en/of geregistreerde vorm bestaat.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

#### RegistratieveRuimte {#informatiemodel_nen3610_domein_semantisch_model_objecttype_registratieve_ruimte}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>urn:modelelement:NEN3610:SemantischModel:RegistratieveRuimte</td>
</tr>
<tr>
<th>Naam</th>
<td>RegistratieveRuimte</td>
</tr>
<tr>
<th>Alias</th>
<td>Registratieve ruimte</td>
</tr>
<tr>
<th>Herkomst</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Definitie</th>
<td>Op basis van wet- of regelgeving afgebakende ruimte die als eenheid geldt van politiek-bestuurlijke verantwoordelijkheid of voor bedrijfsvoering.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>nen 3610</td>
</tr>
<tr>
<th>Datum opname</th>
<td>20220601</td>
</tr>
<tbody>
</tbody>
</table>

