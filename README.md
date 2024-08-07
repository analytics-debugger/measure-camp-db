# Measure Camp DB
Database from previous and upcoming MeasureCamp Editions
 

# DRAFT: Spec
This a beta specification

|**Key**|**Value**|**Description**|
|--|--|--|
| `revision` | 20240805000000 | TimeStamp |
| `build_time` | "2024-08-05 00:00:00" | Build TimeStamp |
| `checksum` | "6332e130363a894b42fbaa522cc5242eed3e8dfb0e8b81606d15899331e7ed90" | editions object checksum |
| `editions` | [[Editions Array]] | |
  

## Event Main Object

|**Key**|**Value**|**Description**|
|--|--|--|
| `mc_index` | 54 | Overall MeasureCamp event index for this edition. |
| `city_edition_index` | 4 | Event index for this edition. Total editions on this city |
| `city` | Praha | The city where the event is taking place. |
| `country` | CZ | The country where the event is taking place. |
| `date` | 2024-09-07 | The date of the event in ISO 8601 format (YYYY-MM-DD). |
| `start_time` | 08:30 | The time the event starts, in 24-hour format (HH:MM). |
| `end_time` | null | The time the event ends, null indicates it is not specified. |
| `timezone` | CET | The time zone of the event. |
| `url` | [MeasureCamp Czechia](https://czechia.measurecamp.org/) | The URL of the event's main website. |
| `tickets_url` | [Eventbrite - MeasureCamp Czechia 2024](https://www.eventbrite.co.uk/e/measurecamp-czechia-2024-registration-911192249547) | The URL for the event's ticket purchasing page. |
| `city_editions_count` | 0 | The number of times this event has been held in the specified city. |
| `twitter` | [@MeasureCampCZ](https://twitter.com/MeasureCampCZ) | The Twitter handle for the event. |
| `venue.name` | ČSOB SHQ | The name of the venue. |
| `venue.address` | Výmolova 353, 150 00 Praha 5 | The full address of the venue. |
| `venue.gmaps` | [Google Maps](https://www.google.com/maps/place/%C4%8CSOB+SHQ/@50.0572031,14.3856235,17z/data=!3m1!4b1!4m6!3m5!1s0x470b955111aa4a69:0x2870f55422e8dcb4!8m2!3d50.0571997!4d14.3881984!16s%2Fg%2F11j07w2hxj?entry=tts&g_ep=EgoyMDI0MDcwNy4xKgBIAVAD) | A Google Maps link to the venue. |
| `metadata.tickets_sold` | null | Number of tickets sold, currently set to null. |
| `metadata.attendees` | null | Number of attendees, currently set to null. |
| `sponsors` | [[Sponsors Array]] | |
| `ticket_releases` | [[Ticket Releases Array]] | |

## Sponsors Object

| **Key** | **Value** | **Description** |
|--|--|--|
| `sponsors.name`| Analytics Debugger | The name of a sponsor. |
| `sponsors.tier`| Gold | The sponsorship tier. |

## Ticket Releases Object

| **Key** | **Value** | **Description** |
|--|--|--|
| `ticket_releases.date` | 2024-06-11| The date of the first ticket release. |
| `ticket_releases.time` | 10:00 | The time of the first ticket release. |
| `ticket_releases.timezone` | CEST | The time zone of the first release. |
| `ticket_releases.description`| 1st Ticket Release | A description of the first ticket release. |

  

## MeasureCamp Editions

|**Index**|**Date**|**Country**|**City**|**Link**|**Status**|**Verified**|
|--|--|--|--|--|--|--|
|#1|`2012-09-22`|UK|London|[1.json](data/1.json)|in progress|false|
|#2|`2013-02-16`|UK|London|[2.json](data/2.json)|in progress|false|
|#3|`2013-09-14`|UK|London|[3.json](data/3.json)|in progress|false|
|#4|`2014-03-29`|UK|London|[4.json](data/4.json)|missing|false|
|#5|`2014-07-05`|FR|Paris|[5.json](data/5.json)|missing|false|
|#6|`2014-09-20`|UK|London|[6.json](data/6.json)|missing|false|
|#7|`2015-01-17`|CN|Hong Kong|[7.json](data/7.json)|missing|false|
|#8|`2015-03-14`|UK|London|[8.json](data/8.json)|missing|false|
|#9|`2015-05-23`|ES|Madrid|[9.json](data/9.json)|missing|false|
|#10|`2015-06-27`|FR|Paris|[10.json](data/10.json)|missing|false|
|#11|`2015-09-12`|CZ|Prague|[11.json](data/11.json)|missing|false|
|#12|`2015-09-19`|UK|London|[12.json](data/12.json)|missing|false|
|#13|`2015-11-21`|ES|Barcelona|[13.json](data/13.json)|missing|false|
|#14|`2016-02-06`|SK|Bratislava| [14.json](data/14.json)|missing|false|
|#15|`2016-03-05`|UK|London|[15.json](data/15.json)|missing|false|
|#16|`2016-03-19`|AU|Melbourne|[16.json](data/16.json)|missing|false|
|#17|`2016-04-09`|NL|Amsterdam|[17.json](data/17.json)|missing|false|
|#18|`2016-05-21`|UK|Newcastle|[18.json](data/18.json)|missing|false|
|#19|`2016-06-04`|FR|Paris|[19.json](data/19.json)|missing|false|
|#20|`2016-09-10`|UK|London|[20.json](data/20.json)|missing|false|
|#21|`2016-09-10`|AU|Sydney|[21.json](data/21.json)|missing|false|
|#22|`2016-09-17`|ES|Madrid|[22.json](data/22.json)|missing|false|
|#23|`2016-10-01`|CZ|Prague|[23.json](data/23.json)|missing|false|
|#24|`2016-10-08`|DE|Berlin|[24.json](data/24.json)|missing|false|
|#25|`2016-11-05`|FR|Nantes|[25.json](data/25.json)|missing|false|
|#26|`2017-02-04`|UK|Cardiff|[26.json](data/26.json)|missing|false|
|#27|`2017-03-25`|UK|London|[27.json](data/27.json)|missing|false|
|#28|`2017-04-01`|ES|Barcelona|[28.json](data/28.json)|missing|false|
|#29|`2017-04-08`|NL|Amsterdam|[29.json](data/29.json)|missing|false|
|#30|`2017-04-08`|AU|Melbourne|[30.json](data/30.json)|missing|false|
|#31|`2017-05-13`|US|Cincinnati| [31.json](data/31.json)|missing|false|
|#32|`2017-06-10`|CZ|Brno|[32.json](data/32.json)|missing|false|
|#33|`2017-06-17`|SK|Bratislava| [33.json](data/33.json)|missing|false|
|#34|`2017-06-24`|FR|Paris|[34.json](data/34.json)|missing|false|
|#35|`2017-07-22`|US|San Francisco|[35.json](data/35.json)|missing|false|
|#36|`2017-07-29`|UK|Cardiff|[36.json](data/36.json)|missing|false|
|#37|`2017-08-19`|DK|Copenhagen| [37.json](data/37.json)|missing|false|
|#38|`2017-09-16`|CZ|Prague|[38.json](data/38.json)|missing|false|
|#39|`2017-09-23`|UK|London|[39.json](data/39.json)|missing|false|
|#40|`2017-10-21`|BE|Brussels| [40.json](data/40.json)|missing|false|
|#41|`2017-11-04`|FR|Nantes|[41.json](data/41.json)|missing|false|
|#42|`2017-11-04`|AU|Sydney|[42.json](data/42.json)|missing|false|
|#43|`2018-02-24`|AU|Melbourne|[43.json](data/43.json)|missing|false|
|#44|`2018-03-17`|UK|London|[44.json](data/44.json)|missing|false|
|#45|`2018-03-24`|SK|Bratislava| [45.json](data/45.json)|missing|false|
|#46|`2018-04-07`|RU|Moscow|[46.json](data/46.json)|missing|false|
|#47|`2018-04-21`|NL|Amsterdam|[47.json](data/47.json)|missing|false|
|#48|`2018-04-28`|US|Columbus| [48.json](data/48.json)|missing|false|
|#49|`2018-05-12`|UK|Manchester| [49.json](data/49.json)|missing|false|
|#50|`2018-06-09`|DK|Copenhagen| [50.json](data/50.json)|missing|false|
|#51|`2018-06-16`|NZ|Auckland| [51.json](data/51.json)|missing|false|
|#52|`2018-06-23`|FR|Paris|[52.json](data/52.json)|missing|false|
|#53|`2018-06-23`|ES|Madrid|[53.json](data/53.json)|missing|false|
|#54|`2018-07-28`|US|San Francisco|[54.json](data/54.json)|missing|false|
|#55|`2018-09-08`|CZ|Brno|[55.json](data/55.json)|missing|false|
|#56|`2018-09-22`|UK|London|[56.json](data/56.json)|missing|false|
|#57|`2018-10-06`|DE|Berlin|[57.json](data/57.json)|missing|false|
|#58|`2018-10-06`|BE|Brussels| [58.json](data/58.json)|missing|false|
|#59|`2018-10-13`|IT|Milan|[59.json](data/59.json)|missing|false|
|#60|`2018-10-20`|AU|Sydney|[60.json](data/60.json)|missing|false|
|#61|`2018-11-10`|TR|Istanbul| [61.json](data/61.json)|missing|false|
|#62|`2018-11-17`|FR|Nantes|[62.json](data/62.json)|missing|false|
|#63|`2019-02-23`|AU|Melbourne|[63.json](data/63.json)|missing|false|
|#64|`2019-04-06`|RU|Moscow|[64.json](data/64.json)|missing|false|
|#65|`2019-04-06`|SK|Bratislava| [65.json](data/65.json)|missing|false|
|#66|`2019-04-13`|NL|Amsterdam|[66.json](data/66.json)|missing|false|
|#67|`2019-04-27`|US|Cincinnati| [67.json](data/67.json)|missing|false|
|#68|`2019-05-18`|IT|Rome|[68.json](data/68.json)|missing|false|
|#69|`2019-05-25`|FR|Paris|[69.json](data/69.json)|missing|false|
|#70|`2019-05-25`|ES|Madrid|[70.json](data/70.json)|missing|false|
|#71|`2019-06-08`|UK|Manchester| [71.json](data/71.json)|missing|false|
|#72|`2019-06-08`|DK|Copenhagen| [72.json](data/72.json)|missing|false|
|#73|`2019-06-15`|NZ|Auckland| [73.json](data/73.json)|missing|false|
|#74|`2019-06-29`|PT|Faro|[74.json](data/74.json)|missing|false|
|#75|`2019-09-07`|RU|St Petersburg|[75.json](data/75.json)|missing|false|
|#76|`2019-09-07`|CZ|Prague|[76.json](data/76.json)|missing|false|
|#77|`2019-09-21`|UK|London|[77.json](data/77.json)|missing|false|
|#78|`2019-09-28`|DE|Berlin|[78.json](data/78.json)|missing|false|
|#79|`2019-09-28`|US|San Francisco|[79.json](data/79.json)|missing|false|
|#80|`2019-10-12`|TR|Istanbul| [80.json](data/80.json)|missing|false|
|#81|`2019-10-19`|BE|Brussels| [81.json](data/81.json)|missing|false|
|#82|`2019-10-19`|IE|Dublin|[82.json](data/82.json)|missing|false|
|#83|`2019-10-26`|SE|Stockholm|[83.json](data/83.json)|missing|false|
|#84|`2019-10-26`|AU|Sydney|[84.json](data/84.json)|missing|false|
|#85|`2019-11-02`|RO|Bucharest|[85.json](data/85.json)|missing|false|
|#86|`2019-11-16`|FR|Nantes|[86.json](data/86.json)|missing|false|
|#87|`2020-01-25`|US|Austin|[87.json](data/87.json)|missing|false|
|#88|`2020-02-22`|AU|Melbourne|[88.json](data/88.json)|missing|false|
|#89|`2020-06-27`|US|Cincinnati| [89.json](data/89.json)|missing|false|
|#90|`2020-07-11`|EU|Europe|[90.json](data/90.json)|missing|false|
|#91|`2020-09-05`|CZ|Czechia|[91.json](data/91.json)|missing|false|
|#92|`2020-11-28`|FR|Lyon|[92.json](data/92.json)|missing|false|
|#93|`2021-01-16`|UK|UK|[93.json](data/93.json)|missing|false|
|#94|`2021-01-23`|US|North America|[94.json](data/94.json)|missing|false|
|#95|`2021-03-06`|EU|Nordics|[95.json](data/95.json)|missing|false|
|#96|`2021-07-03`|EU|Europe|[96.json](data/96.json)|missing|false|
|#97|`2021-09-04`|CZ|Czechia|[97.json](data/97.json)|missing|false|
|#98|`2021-09-25`|FR|Francophonie|[98.json](data/98.json)|missing|false|
|#99|`2022-02-27`|US|North America|[99.json](data/99.json)|missing|false|
|#100|`2022-05-14`|UK|London|[100.json](data/100.json)|missing|false|
|#101|`2022-05-14`|RO|Bucharest|[101.json](data/101.json)|missing|false|
|#102|`2022-05-21`|NL|Amsterdam|[102.json](data/102.json)|missing|false|
|#103|`2022-06-11`|DK|Copenhagen| [103.json](data/103.json)|missing|false|
|#104|`2022-06-18`|NZ|Auckland| [104.json](data/104.json)|missing|false|
|#105|`2022-06-25`|FR|Paris|[105.json](data/105.json)|missing|false|
|#106|`2022-06-25`|DE|Berlin|[106.json](data/106.json)|missing|false|
|#107|`2022-09-10`|CZ|Czechia|[107.json](data/107.json)|missing|false|
|#108|`2022-09-24`|SK|Bratislava| [108.json](data/108.json)|missing|false|
|#109|`2022-10-08`|SE|Stockholm|[109.json](data/109.json)|missing|false|
|#110|`2022-10-15`|AZ|Baku|[110.json](data/110.json)|missing|false|
|#111|`2022-10-22`|AU|Sydney|[111.json](data/111.json)|missing|false|
|#112|`2022-12-03`|BE|Brussels| [112.json](data/112.json)|missing|false|
|#113|`2023-02-11`|AU|Melbourne|[113.json](data/113.json)|missing|false|
|#114|`2023-03-11`|US|North America|[114.json](data/114.json)|missing|false|
|#115|`2023-03-25`|FI|Helsinki| [115.json](data/115.json)|missing|false|
|#116|`2023-04-22`|NL|Amsterdam|[116.json](data/116.json)|missing|false|
|#117|`2023-06-10`|DK|Copenhagen| [117.json](data/117.json)|missing|false|
|#118|`2023-06-24`|FR|Paris|[118.json](data/118.json)|missing|false|
|#119|`2023-06-24`|DE|Munich|[119.json](data/119.json)|missing|false|
|#120|`2023-07-29`|NZ|Auckland| [120.json](data/120.json)|missing|false|
|#121|`2023-09-09`|AE|Dubai|[121.json](data/121.json)|missing|false|
|#122|`2023-09-09`|CZ|Czechia|[122.json](data/122.json)|missing|false|
|#123|`2023-09-09`|DE|Berlin|[123.json](data/123.json)|missing|false|
|#124|`2023-09-30`|UK|London|[124.json](data/124.json)|missing|false|
|#125|`2023-10-07`|SE|Stockholm|[125.json](data/125.json)|missing|false|
|#126|`2023-10-14`|TR|Istanbul| [126.json](data/126.json)|missing|false|
|#127|`2023-10-14`|PL|Warsaw|[127.json](data/127.json)|missing|false|
|#128|`2023-10-21`|SK|Bratislava| [128.json](data/128.json)|missing|false|
|#129|`2023-10-28`|AU|Sydney|[129.json](data/129.json)|missing|false|
|#130|`2023-11-04`|AZ|Baku|[130.json](data/130.json)|missing|false|
|#131|`2023-11-18`|AT|Vienna|[131.json](data/131.json)|missing|false|
|#132|`2023-12-02`|BE|Brussels| [132.json](data/132.json)|missing|false|
|#133|`2024-01-20`|SE|Malmö|[133.json](data/133.json)|missing|false|
|#134|`2024-02-10`|PK|Karachi|[134.json](data/134.json)|missing|false|
|#135|`2024-03-02`|US|Austin|[135.json](data/135.json)|missing|false|
|#136|`2024-03-09`|IT|Italy|[136.json](data/136.json)|missing|false|
|#137|`2024-03-16`|AU|Melbourne|[137.json](data/137.json)|missing|false|
|#138|`2024-03-23`|FI|Helsinki| [138.json](data/138.json)|missing|false|
|#139|`2024-04-06`|LK|Sri Lanka|[139.json](data/139.json)|missing|false|
|#140|`2024-04-13`|US|New York| [140.json](data/140.json)|missing|false|
|#141|`2024-04-20`|NL|Amsterdam|[141.json](data/141.json)|missing|false|
|#142|`2024-05-18`|HR|Split|[142.json](data/142.json)|missing|false|
|#143|`2024-05-25`|ES|Spain|[143.json](data/143.json)|missing|false|
|#144|`2024-06-08`|DK|Copenhagen| [144.json](data/144.json)|missing|false|
|#145|`2024-06-08`|CH|Zurich|[145.json](data/145.json)|missing|false|
|#146|`2024-06-15`|FR|Paris|[146.json](data/146.json)|missing|false|
|#147|`2024-09-07`|CZ|Czechia|[147.json](data/147.json)|missing|false|
|#148|`2024-09-07`|US|Chicago|[148.json](data/148.json)|missing|false|
|#149|`2024-09-21`|DE|Berlin|[149.json](data/149.json)|missing|false|
|#150|`2024-09-21`|UK|London|[150.json](data/150.json)|missing|false|
|#151|`2024-10-05`|CA|Toronto|[151.json](data/151.json)|missing|false|
|#152|`2024-10-12`|PL|Warsaw|[152.json](data/152.json)|missing|false|
|#153|`2024-10-19`|SK|Bratislava| [153.json](data/153.json)|missing|false|
|#154|`2024-10-26`|AU|Sydney|[154.json](data/154.json)|missing|false|
|#155|`2024-10-26`|AE|Dubai|[155.json](data/155.json)|missing|false|
|#156|`2024-11-09`|SE|Stockholm|[156.json](data/156.json)|missing|false|
|#157|`2024-11-16`|BE|Brussels| [157.json](data/157.json)|missing|false|
