## Rijk {#informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk}

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
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_cim_bg_domein_openbaar_lichaam_objecttype_rijk_relatiesoort_heeft_aansluitende_zone">
<h4>heeftAansluitendeZone</h4>
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
<h4>heeftContinentaalPlat</h4>
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
<h4>heeftLandgebied</h4>
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
<h4>heeftTerritorialeZee</h4>
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
<h4>heeftExclusieveEconomischeZone</h4>
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
