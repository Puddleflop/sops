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

The Tahiti CTR/D follows the lateral boundaries as shown below from `SFC` to `A025`. The CTR/D comprises of one sector. 


<figure markdown>
  ![Tahiti Control Zone](./assets/ntaa-airspace.png) 
  <figcaption>The Tahiti Control Zone (CTR/D). The small sector to the west is the Moorea Control Zone (CTR/D).</figcaption>
</figure>

## Areas of Responsibility

The areas of responsibility are as depicted below. The Transfer of Control Points are as listed in the below table.

<figure markdown>
  ![Tahiti Areas of Responsibility](./assets/ntaa-resp.png) 
  <figcaption>Tahiti Areas of Responsibility</figcaption>
</figure>

### Transfer of Control points

| Transfer Flow      | Requirements                                                                         | Notes |
| ------------------ | ------------------------------------------------------------------------------------ | ----- |
| Ground -> Tower    | Prior to arriving at their assigned hold, once clear of other traffic.               |       |
| Tower -> Approach  | For Airline traffic, once airborne. For GA, when leaving the zone, if applicable.    |       |
| Approach -> Tower  | When established on an instrument final, or if on an RNP approach, overhead the IAF. |       |
| Tower -> Ground    | Once clear of the active runway.                                                     |       |

## Control Positions
### Ground

#### Delivery

Clearances shall be issued by the Ground position, and are given via voice.

As Tahiti is an airport administered by the French

!!! example 
    



#### Pushback

Pushback and start up clearances are managed by the Ground Controller. 

Due to the lack of a parallel taxi way heavy aircraft will not be issued push or start instructions if the runway is in use by aircraft who are parking on the south ramp.

#### Taxiing 

Holding points `C1` and `B1` allow aircraft to be held clear of taxiway `S`, allowing aircraft to taxi on the South Ramp while allowing aircraft to vacate the runway.


#### Use of Holding Points

Four runway holding points are avalible at Tahiti, and are as follows:

| Holding Point | Usage                                                                                   |
| ------------- | --------------------------------------------------------------------------------------- | 
| `S`           |Used for aircraft departing from the South Ramp.                                         |
| `G`           |Used for aircraft departing from the Golf Ramp.                                           |
| `N`           |Used for aircraft departing from the North Ramp.                                          |
| `W`           |Used for aircraft departing from the Whiskey Ramp.                                       |

### Tower

The Tower shall ensure that all VFR traffic within the Tahiti CTR/C does not conflict with any IFR operations. IFR operations shall take precedence over VFR.

Unless established within the aerodrome circuit, Tower must ensure that no VFR aircraft are present within the Instrument Sector when an aircraft is either turning onto, or established on an approach. VFR aircraft are not authorised to operate under any approach path, or within 3nm laterally of the approach path.

Aircraft that have been cleared to operate within the North or South sectors are deemed to be separated from IFR arrivals on the ILS or RNP Z approaches, but not from RNP (AR) departures.

### Departures

Aircraft departures shall be managed in-line with the [Runway Operations section](../../controller-skills/separation.md#runway-operations). 

Some departures have immediate divergent turns once the aircraft passes `A005`, taking the aircraft away from the centreline, allowing for another aircraft to follow soon after.

#### SID Assignment

International SIDs are straight-forward, in that all of them have a shallow climb gradient, suitable for most aircraft types. The Controller shall issue the SID that is suggested by their Controller Client.

For Domestic aircraft that are departing to the North or Northeast, the Controller shall issue the SID that is suggested by the Controller Client. If the aircraft is departing to the South, the following rules shall be applied:

| Runway | Procedure  | Allowed A/C Categories | Is divergent?                  | Notes                                                                                                                       |
| ------ | ---------- | ---------------------- | ------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| 05R    | `BROOK #Q` | Cat A to C             | Yes - >30° turn passing `A005` | Available to Cat C Jets for noise-abatement. AA TMA approval required.                                                      |
| 05R    | `PAGLA #Q` | Cat A to D             | No                             | **Preferred departure for Cat C Jets**. Steep climb gradient - aircraft unable to meet this shall be given the `POLIS #Q`.  |
| 05R    | `POLIS #Q` | Cat A to D             | No                             | **Preferred departure for Cat D Jets, or heavies**. Shallower climb gradient.                                               |
| 05R    | `REKIS #Q` | Cat A to D             | Yes - >30° turn passing `A005` | **Preferred departure for Props**. May be given to jets provided they are comfortable with the 180kt limitation at `VINOD`. |
| 05R    | `EMRAG #Q` | Cat A to D             | No                             | Least preferred departure due to manual vectoring required.                                                                 |


| Runway | Procedure  | Allowed A/C Categories | Is divergent?                  | Notes                                                                                                     |
| ------ | ---------- | ---------------------- | ------------------------------ | --------------------------------------------------------------------------------------------------------- |
| 23L    | `LENGU #A` | Cat A to D             | No                             | Least preferred departure due to manual vectoring required.                                               |
| 23L    | `LENGU #P` | Cat A to D             | No                             |                                                                                                           |
| 23L    | `LEVRA #P` | Cat A to D             | No                             | **Preferred departure for Jets**.                                                                         |
| 23L    | `STEAL #P` | Cat A to D             | Yes - >30° turn passing `A005` | **Preferred departure for Props**. Shall not be initially issued to Jets, but may be issued if requested. |

#### Assigned Headings

To ensure a divergent departure occurs due to traffic, AA TMA may request an aircraft be assigned a heading to fly once passing `A005`. This ensures a 30 degree offset from the centreline exists, and therefore another aircraft may then depart. These will usually be issued when an aircraft is at the holding point, and will be given to the Tower as a part of AA TMA's release of the aircraft.

As the aircraft is off an evaluated procedure, there is a potential that an assigned heading departure may conflict with an arriving aircraft. In this case, ATMA may request a hold-down altitude to maintain separation.

!!! danger "Propellor Aircraft Only"
    Due to the early turn required, assigned heading departures shall be given to prop aircraft only.

!!! example "Coordination for an assigned heading departure"
    <span class="coldline">**AA TWR** -> **AA TMA**</span>: "Successive departures. Request ANZ631 assigned heading 190 degrees climbing five thousand then yours for vectors. Second in queue."  
    <span class="coldline">**AA TMA** -> **AA TWR**</span>: "ANZ631 approved heading 190 degrees climbing five thousand then my vectors. Copy second in line."


!!! example "Issuing a departure heading to an Aircraft"
    **Tahiti Tower**: *"ANZ631, additional departure instructions, report ready to copy"*  
    **ANZ631**: *"ANZ631, ready to copy"*  
    **Tahiti Tower**: *"ANZ631, on departure turn right heading 190, climb five thousand"*  
    **ANZ631**: *"ANZ631, on departure turn right heading 190, climb five thousand"* 


## Noise Abatement

!!! warning "Use of Noise Abatement Operations"
    The use of Noise Abatement Operations on the network is **not** mandatory, and Controllers may elect to provide a normal control service if they wish. As the primary Controller affected, the decision to implement Noise Abatement Operations sits with AA TMA.

      *Tahiti employs noise abatement procedures from 2300 until 0600 local in order to minimise disturbances over populated areas.*

### Use of the Preferential Runway System

Use of the Preferential Runway System is not authorised and Controllers shall nominate a single runway direction for both take-off and landing.

### Departures

#### Runway 05R

Aircraft operating from RWY 05R shall not be taken off the SID until passing `A030`. Aircraft shall not overfly the City lower than `A050` unless established on an approach or departure path.

For all international departures the Controller shall issue the SID that is suggested by their Controller Client. For Domestic departures, Controllers shall observe the following SID assignment preferences:

| Priority | Runway | Procedure      | Allowed A/C Categories | Notes                                                                                  |
| -------- | ------ | -------------- | ---------------------- | -------------------------------------------------------------------------------------- |
| 1        | 05R    | `BROOK #Q`     | Cat A to C             | AA TMR approval not required during Noise Abatement hours.                             |
| 2        | 05R    | `REKIS #Q`     | Cat A to D             | **Preferred departure for Props**. Shall not be issued to Jets during Noise Abatement. |
| 3        | 05R    | `POLIS #Q`     | Cat A to D             | **Preferred departure for Cat D Jets, or heavies**. Shallower climb gradient.          |
| 4        | 05R    | All other SIDs |                        | Use of the `PAGLA #Q` departure shall be avoided.                                      |


#### Runway 23L

Aircraft operating from Rwy 23L must climb to `A030` on the extended runway centreline before turning to the right on departure. Aircraft may turn left once above `A005`.

There are no limits on the issuing of SIDs for Rwy 23L.

### Arrivals

#### Domestic

There are no limitations on the assignment of STARs for Domestic traffic, however Controllers should avoid the issuing of RNP-linking STARs.

#### International

OCR has three Noise Abatement STARs that shall be issued as first preference. If track shortening is provided, Controllers shall ensure that aircraft do not overfly the city.

| Runway | Procedure  | Transitions                                                             | Allowed A/C Categories |
| ------ | ---------- | ----------------------------------------------------------------------- | ---------------------- |
| 23L    | `BASIV #N` | `ELNOS` `SALAG` `UPLAR`                                                 | All                    |
| 05R    | `RIKDI #N` | `KALAG` `AGREX` `TARIB` `SELKA` `AGEDU` `IDSEM` `DABAS` `AKLOM` `OLBEX` | All                    |
| 23L    | `TAZEY #N` | `PEBLU` `VELMO`                                                         | All                    |

## VFR Procedures

### Arrival

In order to lessen the amount of instructions given to VFR traffic, the Controller shall issue the `Mangere Bridge` VFR arrival where possible. Once the Pilot reports overhead Mangere Town, the Controller shall integrate them with the circuit. [AIP Chart refers](https://www.aip.net.nz/assets/AIP/Aerodrome-Charts/Tahiti-NTAA/NTAA_35.1_35.2.pdf){ target=new }.

!!! important
    If instructed to join via the overhead, it is the Controller's responsibilty to ensure that the missed approach is protected. A non-circuit side join may be given instead.


### Departure

In order to lessen the amount of instructions given to VFR traffic, the Controller shall issue the `Mangere Bridge` VFR departure at all times - ([AIP Chart](https://www.aip.net.nz/assets/AIP/Aerodrome-Charts/Tahiti-NTAA/NTAA_64.1.pdf){ target=new }). Once the Pilot reaches Mangere Bridge, the aircraft shall be handed off to UNICOM or Approach where appropriate. 

If a departing VFR aircraft requests to climb into controlled airspace, this shall be coordinated with Approach. The Tower Controller may amend the clearance as they see fit while the aircraft is in their Control Zone, however must be coordinated with Approach if the ammendment changes their Control Area entry point.

As flights to the West, North, and Northeast require a turn against the circuit direction, the Tower may approve a turn against the circuit direction.

!!! example "Turn against the Circuit direction"
    **Tahiti Tower**: *"On departure a left/right turn is approved. Runway 05R/23L, cleared for takeoff"*

### Helicopters

Helicopter operations are frequent within Tahiti CTR/C, usually operating within one of the three sectors. Tower must ensure that no VFR aircraft are present within the Instrument Sector when an aircraft is either turning onto, or established on an approach. VFR aircraft are not authorised to operate under any approach path, or within 3nm laterally of the approach path.


