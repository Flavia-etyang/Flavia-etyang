<div align="center">

<img src="assets/hero/satellite-vessel-intelligence-cover.png" alt="Satellite Vessel Intelligence" width="100%" />

# SATELLITE VESSEL INTELLIGENCE

**Detect. Measure. Classify. Verify.**

*Extracting vessel intelligence from overhead imagery through structural analysis, dimension estimation and classification.*

</div>

<br>

<div align="center">

```
VESSEL DETECTION
       ↓
STRUCTURAL ANALYSIS
       ↓
DIMENSION ESTIMATION
       ↓
VESSEL CLASSIFICATION
       ↓
CONFIDENCE ASSESSMENT
       ↓
CROSS-SOURCE VALIDATION
```

</div>

<br>

## What can vessel structure reveal from overhead imagery?

Overhead imagery can reveal more than vessel presence. Hull proportions, deck configuration, superstructure, cranes, piping and cargo arrangements can provide sufficient evidence to determine a vessel's likely class and estimate its physical dimensions.

> **The objective is not simply to identify a vessel. It is to extract defensible intelligence from observable evidence.**

<br>

---

## THE OBSERVATION

Three views of the same evidence — optical, radar, and measurement.

<table>
<tr>
<td align="center" width="33%">
<img src="assets/vessel-01-tanker/eo.png" width="100%"><br>
<b>EO</b><br>
<sub>Optical observation</sub>
</td>
<td align="center" width="33%">
<img src="assets/vessel-01-tanker/sar.png" width="100%"><br>
<b>SAR</b><br>
<sub>Radar observation</sub>
</td>
<td align="center" width="33%">
<img src="assets/vessel-01-tanker/measurement-overlay.png" width="100%"><br>
<b>REFERENCE AERIAL</b><br>
<sub>Measurement visualization</sub>
</td>
</tr>
</table>

<br>

---

## CASE 01 — CRUDE OIL TANKER

<table>
<tr>
<td width="60%">
<img src="assets/vessel-01-tanker/annotated-features.png" width="100%">
</td>
<td width="40%" valign="top">

### VESSEL INTELLIGENCE

**CLASS**
Crude Oil Tanker

**LENGTH**
182.4 m

**BEAM**
32.1 m

**CLASS CONFIDENCE**
`HIGH`

</td>
</tr>
</table>

#### Vessel Intelligence — Full Profile

| Field | Value |
|---|---|
| Broad Type | Merchant Vessel |
| Classification | Crude Oil Tanker |
| Estimated Length | 182.4 m |
| Estimated Beam | 32.1 m |
| L/B Ratio | 5.68 |
| Detection Confidence | `HIGH` |
| Classification Confidence | `HIGH` |
| Identity Confidence | N/A |

### WHY A TANKER?

**01 — Deck piping**
Extensive longitudinal piping is visible across the cargo deck, consistent with liquid-cargo transfer infrastructure.

**02 — Clear cargo deck**
The deck lacks the dense, repetitive cargo arrangement expected on container vessels.

**03 — Superstructure**
The position and configuration of the superstructure support the tanker hypothesis.

**04 — Hull proportions**
Overall vessel geometry is consistent with a large merchant tanker configuration.

> **Classification Assessment**
> The convergence of deck piping, cargo-deck configuration, superstructure placement and hull proportions supports classification as a crude oil tanker.

*[Full write-up →](case-studies/tanker.md)*

<br>

---

## CASE 02 — LPG CARRIER

### When deck geometry changes the classification

<img src="assets/vessel-02-lpg/annotated-features.png" width="100%">

**Observable indicators**
- Cylindrical/spherical cargo containment structures
- Specialized deck equipment
- Distinctive cargo arrangement
- Different deck profile from conventional oil tankers

**Classification:** LPG Carrier
**Confidence:** `HIGH`

> Not every tanker-like vessel with a relatively clear deck is an oil tanker. Cargo containment architecture becomes an important discriminator.

*[Full write-up →](case-studies/lpg-carrier.md)*

<br>

---

## CASE 03 — CONTAINER VESSEL

<img src="assets/vessel-03-container/annotated-features.png" width="100%">

**01 — Container stacks**
Regular rectangular cargo blocks.

**02 — Cargo cranes**
Where visible, cranes provide additional classification evidence.

**03 — Cellular arrangement**
Repeated container geometry across the cargo deck distinguishes the vessel from bulk and liquid cargo vessels.

**Classification:** Container Vessel
**Confidence:** `HIGH`

*[Full write-up →](case-studies/container-vessel.md)*

<br>

---

## CONFIDENCE FRAMEWORK

| Level | Meaning |
|---|---|
| `HIGH` | Multiple independent visual characteristics support the classification. |
| `MEDIUM` | The classification is supported, but image quality or vessel orientation limits certainty. |
| `LOW` | Available evidence is insufficient or conflicting. |

> Confidence refers to the strength of the evidence supporting the classification, not the certainty of vessel identity.

<br>

---

## FROM IMAGE TO INTELLIGENCE

```
01  OBSERVE     →  Identify visible vessel characteristics
02  MEASURE     →  Estimate length, beam and proportions
03  CLASSIFY    →  Compare structural features against vessel classes
04  VALIDATE    →  Cross-reference AIS and vessel particulars where available
05  ASSESS      →  Assign classification and confidence
```

<br>

---

## Analytical Methodology

*[View methodology →](methodology/classification-framework.md)*

<br>

---

## Analytical Principle

**Observation → Inference → Validation → Assessment**

Satellite imagery provides the observation.
Maritime data provides the context.
Analytical reasoning turns both into intelligence.

<br>

## Skills Demonstrated

`Satellite Vessel Detection` `Vessel Classification` `Dimension Estimation` `EO / SAR Interpretation` `Visual Intelligence` `AIS Correlation` `Maritime Data Analysis` `Confidence Assessment`

<br>

---

<sub>See [SOURCES.md](SOURCES.md) for imagery and data attribution. See [methodology/](methodology/) for the full analytical framework.</sub>

