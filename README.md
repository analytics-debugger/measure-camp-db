
# Measure Camp DB

Database from previous and upcoming MeasureCamp Editions
 

# DRAFT: Spec

This a beta specification

|**Key**|**Value**|**Description**|
|--|--|--|
| `mc_index` | 54 | A unique identifier or index for this MeasureCamp event. |
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
| `venue` | - | An object containing information about the venue. |
| `venue.name` | ČSOB SHQ | The name of the venue. |
| `venue.address` | Výmolova 353, 150 00 Praha 5 | The full address of the venue. |
| `venue.gmaps` | [Google Maps](https://www.google.com/maps/place/%C4%8CSOB+SHQ/@50.0572031,14.3856235,17z/data=!3m1!4b1!4m6!3m5!1s0x470b955111aa4a69:0x2870f55422e8dcb4!8m2!3d50.0571997!4d14.3881984!16s%2Fg%2F11j07w2hxj?entry=tts&g_ep=EgoyMDI0MDcwNy4xKgBIAVAD) | A Google Maps link to the venue. |
| `metadata` | - | An object containing additional metadata. |
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