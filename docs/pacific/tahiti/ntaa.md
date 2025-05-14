---
  title: NTAA - Tahiti
---

--8<-- "includes/abbreviations.md"

## Positions

| Position Name | Shortcode | Callsign        | Frequency | Login ID | Usage     |
| ------------- | --------- | --------------- | --------- | -------- | --------- |
| Tahiti SMC    | G-TAH     | Tahiti Ground   | 121.900   | NTAA_GND | Secondary |
| Tahiti ADC    | T-TAH     | Tahiti Tower    | 118.100   | NTAA_TWR | Primary   |
| Tahiti TMA    | A-TAH     | Tahiti Approach | 121.300   | NTAA_APP | Primary   |

## Airspace

The Tahiti CTR/D follows the lateral boundaries below from `SFC` to `A025`. The CTR/D comprises one sector. 

<figure markdown>
  ![Tahiti Control Zone](./assets/ntaa-airspace.png) 
  <figcaption>The Tahiti Control Zone (CTR/D). The small sector to the west is the Moorea Control Zone (CTR/D).</figcaption>
</figure>

## Areas of Responsibility

The areas of responsibility are as depicted below. The Transfer of Control Points are listed in the below table.

<figure markdown>
  ![Tahiti Areas of Responsibility](./assets/ntaa-resp.png) 
  <figcaption>Tahiti Areas of Responsibility</figcaption>
</figure>

### Transfer of Control points

| Transfer Flow     | Requirements                                                                         | Notes |
| ----------------- | ------------------------------------------------------------------------------------ | ----- |
| Ground -> Tower   | Before arriving at their assigned hold, once clear of other traffic.                 |       |
| Tower -> Approach | For Airline traffic, once airborne. For GA, when leaving the zone, if applicable.    |       |
| Approach -> Tower | When established on an instrument final, or if on an RNP approach, overhead the IAF. |       |
| Tower -> Ground   | Once clear of the active runway.                                                     |       |

## Control Positions
### Ground

#### Delivery

Clearances shall be issued by the Ground position and are given via voice.

As Tahiti is administered by the French, there are a few differences in the clearances. All SIDS have initial climb clearances. 

!!! example "Clearance Example to Auckland"
    **Tahiti Ground**: *"THT101A, Cleared to Auckland via Flight Plan Route, Climb and Maintain 5000ft, BEBIG 4W departure RWY 04 DCT TEKOT, Squawk 5021"* 

#### Pushback

Pushback and start up clearances are managed by the Ground Controller. 

Due to the lack of a parallel taxiway, heavy aircraft will not be issued push or start instructions if the runway is in use by aircraft that are either conducting an instrument approach or parking on the south ramp.

#### Taxiing 

Holding points `C1` and `B1` allow aircraft to be held clear of taxiway `S`, allowing aircraft to taxi on the South Ramp while allowing aircraft to vacate the runway.

#### Use of Holding Points

Four runway holding points are available at Tahiti and are as follows:

| Holding Point | Usage                                              |
| ------------- | -------------------------------------------------- |
| `S`           | Used for aircraft departing from the South Ramp.   |
| `G`           | Used for aircraft departing from the Golf Ramp.    |
| `N`           | Used for aircraft departing from the North Ramp.   |
| `W`           | Used for aircraft departing from the Whiskey Ramp. |

### Tower

The Tower shall ensure that all VFR traffic within the Tahiti CTR/D does not conflict with any IFR operations. IFR operations shall take precedence over VFR.

Unless established within the aerodrome circuit, VFR aircraft are not authorised to operate under any approach path or within 3nm laterally of the approach path.

### Departures

Aircraft departures shall be managed in line with the [Runway Operations section](../../controller-skills/separation.md#runway-operations). 

#### SID Assignment

Tahiti has both conventional and RNAV departures. The conventional departures are number `3`, e.g. `ARITI 3E`, whereas the RNAV departures are number `4,` e.g. `ARITI 4E`.

| Runway | Procedure                           | Allowed A/C Categories | Notes                                                             |
| ------ | ----------------------------------- | ---------------------- | ----------------------------------------------------------------- |
| 04     | `ARITI #E`                          | Cat A                  | Preferred departure for NTTE traffic.                             |
| 04     | `BENKO #E`                          | Cat A to D             | East bound departures.                                            |
| 04     | `IKELO #E`                          | Cat A to D             | North bound departures.                                           |
| 04     | `MOSMA #E`                          | Cat A to D             | Preferred departure for NTTM traffic.                             |
| 04     | `PASTI #E`                          | Cat A to C             | South bound departures.                                           |
| 04     | `VAITE #E`                          | Cat A to D             | West bound departures and depatures to the ILES SOUS LE VENT TMA. |
| 04     | `MUITIDIRECTIONAL DEPARTURE RWY 04` | Cat A to D             | Least preferred departure due to manual vectoring required.       |

| Runway | Procedure                           | Allowed A/C Categories | Notes                                                             |
| ------ | ----------------------------------- | ---------------------- | ----------------------------------------------------------------- |
| 22     | `ARITI #W`                          | Cat A                  | Preferred departure for NTTE traffic.                             |
| 22     | `BEBIG #W`                          | Cat A to D             | South and south west bound departures.                            |
| 22     | `IKELO #W`                          | Cat A to D             | North bound departures.                                           |
| 22     | `MOSMA #W`                          | Cat A to B             | Preferred departure for NTTM traffic.                             |
| 22     | `ONIDO #W`                          | Cat A to D             | West and east bound departures.                                   |
| 22     | `VAITE #W`                          | Cat A to D             | West bound departures and depatures to the ILES SOUS LE VENT TMA. |
| 22     | `MUITIDIRECTIONAL DEPARTURE RWY 22` | Cat A to D             | Least preferred departure due to manual vectoring required.       |

A series of transitions are published to allow aircraft to transfer from the published SIDs to the oceanic enroute environment.

| Runway | Enroute Fixes                                  | Procedure  | Route                 | Notes                                               |
| ------ | ---------------------------------------------- | ---------- | --------------------- | --------------------------------------------------- |
| 04     | `ISTAM`, `HAO`, `NANUE`, `VETEA`, `TATIA`      | `BENKO #E` | `BENKO DCT`           | Flights departing to the east                       |
| 04     | `MIKAT`, `RAN`,`PAERE`,`TIAMA`                 | `IKELO #E` | `IKELO DCT`           | Flights departing to the north                      |
| 04     | `ATURE`, `MIKOP`, `OPERU`, `RT`, `TB`, `TAPAP` | `PASTI #E` | `PASTI DCT`           | Flights departing to the south and west             |
| 04     | `MAITO`, `SABUB`, `TEKOT`                      | `PASTI #E` | `PASTI DCT ONIDO DCT` | Flights departing to the south-west                 |
| 04     | `MEGOG`, `VAITE`                               | `VAITE #E` | `VAITE DCT`           | Flights to the ILES SOUS LE VENT TMA and north-west |

| Runway | Enroute Fixes                               | Procedure  | Route                           | Notes                                               |
| ------ | ------------------------------------------- | ---------- | ------------------------------- | --------------------------------------------------- |
| 22     | `MAITO`, `RT`, `TB`, `SABUB`, `TEKOT`       | `BEBIG #W` | `BEBIG DCT`                     | Flights departing to the south and south west       |
| 22     | `ISTAM`, `MIKAT`, `RAN`, `PAERE`, `TIAMA`   | `IKELO #W` | `IKELO DCT`                     | Flights departing to the north                      |
| 22     | `ATURE`, `MIKOP`, `OPERU`, `TAPAP`, `TATIA` | `ONIDO #W` | `ONIDO DCT`                     | Flights departing to the west                       |
| 22     | `HAO`, `PEBRO`, `VETEA`                     | `ONIDO #W` | `ONIDO DCT TATIA DCT VETEA DCT` | Flights departing to the east                       |
| 22     | `MEGOG`                                     | `VAITE #W` | `VAITE DCT`                     | Flights to the ILES SOUS LE VENT TMA and north west |

## Moorea (NTTM) Procedures

When TNTTM is off watch, T-TAH inherits the Moorea CTR/D and provides a Tower service to the field.

## VFR Procedures

