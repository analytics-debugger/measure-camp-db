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

| **Index** | **Date** | **Country** | **City** | **Link** | **Status ** | **Verified ** |
|--|--|--|--|--|--|--|
| #1 | `2012-09-22` | UK | London | [1.json](data/1.json) | in progress | false
| #2 | `2013-02-16` | UK | London | [2.json](data/2.json) | in progress | false
| #3 | `2013-09-14` | UK | London | [3.json](data/3.json) | in progress | false
| #4 | `2014-03-29` | UK | London | [4.json](data/4.json) | missing | false
| #5 | `2014-07-05` | FR | Paris | [5.json](data/5.json) | missing | false
| #6 | `2014-09-20` | UK | London | [6.json](data/6.json) | missing | false
| #7 | `2015-01-07` | CN | Hong Kong | [7.json](data/7.json) | missing | false
| #8 | `2015-03-14` | UK | London | [8.json](data/8.json) | missing | false
| #9 | (not set) | (not set) | (not set) | [9.json](data/9.json) | missing | false
| #10 | (not set) | (not set) | (not set) | [10.json](data/10.json) | missing | false
| #11 | (not set) | (not set) | (not set) | [11.json](data/11.json) | missing | false
| #12 | (not set) | (not set) | (not set) | [12.json](data/12.json) | missing | false
| #13 | (not set) | (not set) | (not set) | [13.json](data/13.json) | missing | false
| #14 | (not set) | (not set) | (not set) | [14.json](data/14.json) | missing | false
| #15 | (not set) | (not set) | (not set) | [15.json](data/15.json) | missing | false
| #16 | (not set) | (not set) | (not set) | [16.json](data/16.json) | missing | false
| #17 | (not set) | (not set) | (not set) | [17.json](data/17.json) | missing | false
| #18 | (not set) | (not set) | (not set) | [18.json](data/18.json) | missing | false
| #19 | (not set) | (not set) | (not set) | [19.json](data/19.json) | missing | false
| #20 | (not set) | (not set) | (not set) | [20.json](data/20.json) | missing | false
| #21 | (not set) | (not set) | (not set) | [21.json](data/21.json) | missing | false
| #22 | (not set) | (not set) | (not set) | [22.json](data/22.json) | missing | false
| #23 | (not set) | (not set) | (not set) | [23.json](data/23.json) | missing | false
| #24 | (not set) | (not set) | (not set) | [24.json](data/24.json) | missing | false
| #25 | (not set) | (not set) | (not set) | [25.json](data/25.json) | missing | false
| #26 | (not set) | (not set) | (not set) | [26.json](data/26.json) | missing | false
| #27 | (not set) | (not set) | (not set) | [27.json](data/27.json) | missing | false
| #28 | (not set) | (not set) | (not set) | [28.json](data/28.json) | missing | false
| #29 | (not set) | (not set) | (not set) | [29.json](data/29.json) | missing | false
| #30 | (not set) | (not set) | (not set) | [30.json](data/30.json) | missing | false
| #31 | (not set) | (not set) | (not set) | [31.json](data/31.json) | missing | false
| #32 | (not set) | (not set) | (not set) | [32.json](data/32.json) | missing | false
| #33 | (not set) | (not set) | (not set) | [33.json](data/33.json) | missing | false
| #34 | (not set) | (not set) | (not set) | [34.json](data/34.json) | missing | false
| #35 | (not set) | (not set) | (not set) | [35.json](data/35.json) | missing | false
| #36 | (not set) | (not set) | (not set) | [36.json](data/36.json) | missing | false
| #37 | (not set) | (not set) | (not set) | [37.json](data/37.json) | missing | false
| #38 | (not set) | (not set) | (not set) | [38.json](data/38.json) | missing | false
| #39 | (not set) | (not set) | (not set) | [39.json](data/39.json) | missing | false
| #40 | (not set) | (not set) | (not set) | [40.json](data/40.json) | missing | false
| #41 | (not set) | (not set) | (not set) | [41.json](data/41.json) | missing | false
| #42 | (not set) | (not set) | (not set) | [42.json](data/42.json) | missing | false
| #43 | (not set) | (not set) | (not set) | [43.json](data/43.json) | missing | false
| #44 | (not set) | (not set) | (not set) | [44.json](data/44.json) | missing | false
| #45 | (not set) | (not set) | (not set) | [45.json](data/45.json) | missing | false
| #46 | (not set) | (not set) | (not set) | [46.json](data/46.json) | missing | false
| #47 | (not set) | (not set) | (not set) | [47.json](data/47.json) | missing | false
| #48 | (not set) | (not set) | (not set) | [48.json](data/48.json) | missing | false
| #49 | (not set) | (not set) | (not set) | [49.json](data/49.json) | missing | false
| #50 | (not set) | (not set) | (not set) | [50.json](data/50.json) | missing | false
| #51 | (not set) | (not set) | (not set) | [51.json](data/51.json) | missing | false
| #52 | (not set) | (not set) | (not set) | [52.json](data/52.json) | missing | false
| #53 | (not set) | (not set) | (not set) | [53.json](data/53.json) | missing | false
| #54 | (not set) | (not set) | (not set) | [54.json](data/54.json) | missing | false
