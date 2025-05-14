---
  title: Procedures
---

--8<-- "includes/abbreviations.md"

## Methods of Communication

The primary method of communication is via HF Voice.

CPDLC is not yet supported but may be offered as a secondary means of communication if available. ARO's CPDLC logon code shall be `NTTT`.

### HF

Simulated HF radio is used as the primary long-range radio communications medium. The nature of HF radio makes it highly vulnerable to atmospheric distortion and noise, so radiotelephony procedures on HF tend to be more formal to maximize clarity.

#### SELCAL

Given the background noise level experienced on HF radio frequencies, flight crews usually prefer to turn down the audio level of their HF receiver. SELCAL uses a unique 4-letter code for each aircraft (e.g. `QR-AC`), transmitted over the communications frequency to sound an alert for the flight crew.

Controllers must check each aircraft’s flight plan for a discrete SELCAL code. If aircraft have nominated a discrete code (for example, `QR-AC`), a SELCAL check shall be completed on initial contact.

!!! important "Use of SELCAL"
    Where a SELCAL check has been completed successfully, all subsequent communications shall be conducted prefaced by a SELCAL chime.

!!! example "RTF Example for readback of a Position Report"
    **Tahiti Radio**: *"ANZ2, standby SELCAL check."*  
    Aircraft awaits the SELCAL chime before replying.  
    **ANZ2**: *"SELCAL check OK, ANZ2."*    
    Then continue with routine communications.

### CPDLC

!!! info "Not yet supported in NTTT"
    These procedures will be produced when CPDLC is supported in NTTT.


## Position Reports

As NTTT is procedural airspace, pilots are required to provide regular position reports to ATC, which can then be entered into your Controller Client software.

A Position Report will contain the following elements:

- Callsign
- Position & Time
- Flight level
- Next position and time over
- Ensuing significant point
- Specified Speed (if assigned)

If an aircraft fails to report its position within 3 minutes of its estimated time, controllers must attempt to establish contact with that aircraft and obtain a position report.

ATC shall acknowledge a position report by using the aircraft's callsign. A readback of the report is not required unless the controller needs to confirm the information provided.

!!! example "RTF Example for readback of a Position Report"
    **ANZ2**: *"Tahiti Radio, Tahiti Radio. ANZ2 with position."*  
    **Tahiti Radio**: *"ANZ2, pass position report."*    
    **ANZ2**: *"ANZ2 is position WIBIG time 1853. Estimating REVRO at 1953. RUTAK next."*  
    **Tahiti Radio**: *"ANZ2, Tahiti Radio copies position report."*  

!!! tip "Position Report Formatting Tool"
    If pilots in your airspace are struggling to provide accurate position reports, you can send them the [Oceanic Report Tool](https://www.vatnz.net/pilots/oceanic-report-tool/){ target=_blank } to help them out.

## Transfer of Control Point

### NTTC & TAH-A to NTTT

NTTC & TAH-A must provide a 10-minute warning to Auckland Radio (ARO) before an aircraft crosses the FIR boundary.

### NTTT to NTTC & TAH-A

Aircraft entering an NZZC enroute sector must do so via a named fix at their assigned flight level. Pilots shall be instructed to contact the appropriate NZZC sector frequency when crossing the boundary fix.

Since aircraft crossing into NZZC enter a surveillance environment, prior coordination with NZZC sectors is not required provided the aircraft meets the conditions above.

!!! example "RTF Example for handing off to a NZZC sector"
    **Auckland Radio**: *"UAE412, at position PEBLU, contact Auckland Control on 123.900."*    
    **UAE412**: *"UAE412 at position PEBLU, contact Auckland Control on 123.900."*

### NTTT to other Oceanic FIRs

For flights leaving NTTT to enter other oceanic FIRs, voiceless transfers may be used. There shall be no changes to the route or cleared flight level (CFL) within 15 minutes of the FIR boundary.
