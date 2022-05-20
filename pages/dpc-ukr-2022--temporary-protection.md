<img src="../assets/images/dpcUKR2022.png" alt="DPC Emergenza Ucraina 2022" data-canonical-src="../assets/images/dpcUKR2022.png" width="400" />

# Protezione temporanea / Temporary Protection

| IT|EN|
|-|-|
|All'arrivo in Italia, le persone in fuga dalla guerra in Ucraina possono presentare richiesta di permesso di soggiorno per protezione temporanea presso gli Uffici immigrazione delle Questure.|People fleeing the war in Ukraine can apply for residence permits for temporary protection at the Immigration Offices of the Police Stations upon their arrival in Italy.|

Dati forniti da / Data provided by: **Ministero dell'Interno Direzione centrale dell'Immigrazione e della Polizia delle frontiere**<br>
Produzione Opendata e dashboard / Opendata production and dashboard: **Dipartimento della Protezione Civile**

## Aggiornamento dei dati / Data update

Settimanale - Sabato alle 15:00 / Weekly - Saturday at 03:00pm<br>
I dati si riferiscono al giorno precedente / The data refer to the previous day

## Processo / Process

| IT|EN|
|-|-|
|Raccolta dei dati da parte delle Questure che rilasciano la protezione temporanea|Data collection by the police headquarters issuing temporary protection|
|Ricezione dei dati da parte del Ministero dell'Interno|Receipt of data by the Ministry of the Interior|
|Pubblicazione dashboard|Dashboard publishing|
|Pubblicazione dati|Opendata publishing|

## Dashboard

[https://mappe.protezionecivile.gov.it/it/mappe-e-dashboards-emergenze/mappe-e-dashboards-ucraina/richieste-di-protezione-temporanea](https://mappe.protezionecivile.gov.it/it/mappe-e-dashboards-emergenze/mappe-e-dashboards-ucraina/richieste-di-protezione-temporanea)

## Dataset

**Directory:**  [temporary-protection](../data/temporary-protection/)<br>
**Nome file / Filename (csv):** [dpc-ukr-2022--temporary-protection.csv](../data/temporary-protection/dpc-ukr-2022--temporary-protection.csv)<br>
**Nome file / Filename (json):** [dpc-ukr-2022--temporary-protection.json](../data/temporary-protection/dpc-ukr-2022--temporary-protection.json)<br>

|Nome campo<br>Field name|Descrizione<br>Description|Formato<br>Format|Esempio<br>Example|
|-|-|-|-|
|**update**|Data e ora di aggiornamento<br>Update datetime|Datetime<br>YYYY-MM-DDTHH:MM:SSZ<br>ISO 8601|2023-04-14T15:00:00Z|
|**gender**|Genere<br>Gender|String|M|
|**age**|Età<br>Age|Number|0|
|**country_birth**|Nazione di nascita<br>Country of birth|String<br>ISO 3166 alpha-3|UKR|
|**nationality**|Nazionalità<br>Nazionalità|String<br>ISO 3166 alpha-3|UKR|
|**number_children**|Numero di figli<br>Number of children|Number|0|
|**temporary_protection_release_date**|Data di richiesta della protezione temporanea<br>Date of application for temporary protection|Date<br>YYYY-MM-DD<br>ISO 8601|2023-04-14|
|**temporary_protection_release_nuts_1**|Codice NUTS 1<br>NUTS 1 Code|String<br>[Mappa/Map](https://ec.europa.eu/statistical-atlas/viewer/?config=typologies.json&ch=NUTS,NUTS2021&mids=BKGCNT,NUTS2021L1,CNTOVL&o=1,1,0.7&center=50.00754,19.98211,3&lcis=NUTS2021L1&)|ITI|
|**temporary_protection_release_area**|Area d'Italia<br>Italy Area|String|Centro|
|**temporary_protection_release_nuts_2**|Codice NUTS 2<br>NUTS 2 Code|String<br>[Mappa/Map](https://ec.europa.eu/statistical-atlas/viewer/?config=typologies.json&ch=NUTS,NUTS2021&mids=BKGCNT,NUTS2021L2,CNTOVL&o=1,1,0.7&center=50.00754,19.98211,3&lcis=NUTS2021L2&)|ITI4|
|**temporary_protection_release_region**|Region<br>Regione|String|Lazio|
|**temporary_protection_release_nuts_3**|Codice NUTS 3<br>NUTS 3 Code|String<br>[Mappa/Map](https://ec.europa.eu/statistical-atlas/viewer/?config=typologies.json&ch=NUTS,NUTS2021&mids=BKGCNT,NUTS2021L3,CNTOVL&o=1,1,0.7&center=50.00754,19.98211,3&lcis=NUTS2021L3&)|ITI43|
|**temporary_protection_release_province**|Provincia<br>Province|String|Roma|
|**people**|Numero di persone<br>Number of people|Number|0|

## Licenza / License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)<br>
[CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [Visualizza licenza](https://github.com/pcm-dpc/UKR-2022/blob/master/LICENSE)