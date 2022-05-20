<img src="../assets/images/dpcUKR2022.png" alt="DPC Emergenza Ucraina 2022" data-canonical-src="../assets/images/dpcUKR2022.png" width="400" />

# Aiuti umanitari / Humanitarian aid

| IT|EN|
|-|-|
|**L'impegno del sistema italiano di protezione civile nell'assistenza umanitaria.**<br>Dall'inizio dell'emergenza, il Dipartimento della Protezione Civile sta garantendo assistenza umanitaria all'Ucraina e ai Paesi interessati dai consistenti flussi di profughi in fuga dal conflitto sia nell'ambito del Meccanismo Unionale di Protezione Civile, sia di accordi bilaterali.<br>Sulla base delle richieste di assistenza internazionale, il Dipartimento coordina la ricognizione e l'invio delle risorse disponibili di Componenti, Strutture operative e soggetti concorrenti del Servizio Nazionale di Protezione Civile.<br>Nell'ambito dell'emergenza, il Dipartimento sta inoltre garantendo l'evacuazione medica MedEvac-Medical Evacuation – anche con modulo DisEvac-Disability Evacuation – di pazienti con necessità di assistenza specialistica, trasportati in Italia e ricoverati in diversi centri nazionali.|**The commitment of the Italian civil protection system in humanitarian assistance.**<br>The Department of Civil Protection has been providing humanitarian assistance to Ukraine and the countries affected by the large flows of refugees fleeing the conflict since the beginning of the emergency, both within the framework of the Union Civil Protection Mechanism and under bilateral agreements.<br>On the basis of requests for international assistance, the Department coordinates the recognition and deployment of available resources of Components, Operational Structures and concurrent subjects of the National Service of Civil Protection.<br>As part of the emergency, the Department is also ensuring the medical evacuation - MedEvac-Medical Evacuation or DisEvac-Disability Evacuation - of patients in need of specialized assistance, flown to Italy and hospitalized in different national centers.|

Dati forniti da / Data provided by: **Dipartimento della Protezione Civile**<br>
Produzione Opendata e dashboard / Opendata production and dashboard: **Dipartimento della Protezione Civile**

## Aggiornamento dei dati / Data update

Ad ogni missione di aiuti umanitari / At every humanitarian aid mission

## Processo / Process

| IT|EN|
|-|-|
|Censimento della missione di aiuto su sistema DPC|Census of the aid mission on the DPC system|
|Produzione del dataset open|Opendata dataset production|
|Pubblicazione dashboard|Dashboard publishing|
|Pubblicazione dati|Opendata publishing|

## Dashboard

[https://mappe.protezionecivile.gov.it/it/mappe-e-dashboards-emergenze/mappe-e-dashboards-ucraina/aiuti-umanitari](https://mappe.protezionecivile.gov.it/it/mappe-e-dashboards-emergenze/mappe-e-dashboards-ucraina/aiuti-umanitari)

## Dataset

**Directory:**  [humanitarian-aid](../data/humanitarian-aid/)<br>
**Nome file / Filename (csv):** [dpc-ukr-2022--humanitarian-aid.csv](../data/humanitarian-aid/dpc-ukr-2022--humanitarian-aid.csv)<br>
**Nome file / Filename (json):** [dpc-ukr-2022--humanitarian-aid.json](../data/humanitarian-aid/dpc-ukr-2022--humanitarian-aid.json)<br>
**Nome file / Filename (geojson):** [dpc-ukr-2022--humanitarian-aid-geo.geojson](../data/humanitarian-aid/dpc-ukr-2022--humanitarian-aid-geo.geojson)<br>
**Nome file / Filename (topojson):** [dpc-ukr-2022--humanitarian-aid-geo.json](../data/humanitarian-aid/dpc-ukr-2022--humanitarian-aid-geo.json)<br>

|Nome campo<br>Field name|Descrizione<br>Description|Formato<br>Format|Esempio<br>Example|
|-|-|-|-|
| **update**|Data e ora di aggiornamento<br>Update datetime|Datetime<br>YYYY-MM-DDTHH:MM:SSZ<br>ISO 8601|2023-04-14T08:00:00Z|
| **date**|Data della missione di aiuto umanitario<br>Date of the humanitarian aid mission|Date<br>YYYY-MM-DD|2022-04-14|
| **country**|Nazione di arrivo<br>Country of arrival|String<br>ISO 3166 alpha-3|UKR|
| **region**|Regione di arrivo<br>Region of arrival|String|Zakarpattia|
| **municipality**|Città di arrivo<br>Municipality of arrival|String|Chop|
|**latitude**|Latitudine<br>Latitudine|Decimal|48.43165|
|**longitude**|Longitudine<br>Longitude|Decimal|22.20545|
| **destination**|Destinazione finale<br>Final destination|Array<br>ISO 3166 alpha-3|['UKR']|
| **category**|Categoria<br>Category|String|Materiali e attrezzature campi di accoglienza|
| **description**|Descrizione<br>Description|String|Tende coperte servizi generatori|
| **donor**|Donatore<br>Donor|Array|['Dipartimento della Protezione Civile']|
| **value**|Valore<br>Value|String|50.000 Euro circa|
| **field_intervention**|Campo di intervento<br>Field of intervention|String|Meccanismo Unionale di Protezione Civile|

## Licenza / License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)<br>
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/UKR-2022/blob/master/LICENSE)