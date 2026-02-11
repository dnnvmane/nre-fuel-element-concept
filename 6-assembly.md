# 6. Fuel Element Assembly

## I. Pre-Assembly Phase
*All components are manufactured in parallel due to different process requirements.*

| Component | Material / Method | Reference |
|:---|:---|:---|
| **Gas Column Cladding** | Inconel 718, CNC machining | [3-gas-column.md] |
| **Fuel Column Cladding** | TZM+Nb-1Zr, rolling + laser welding | [5-fuel-column.md] |
| **Intermediate Flange** | Pd/Mo/Nb-1Zr/TZM, diffusion brazing | [4-intermediate-flange.md] |
| **SAW Sensor** | LiTaO₃ + Ta + YH₂, brazing | [3-gas-column.md] |
| **Fuel Pellets** | UO₂–Mo, HIP | [5-fuel-column.md] |
| **Thermal Inserts** | Mo, stamping + machining | [5-fuel-column.md] |
| **Thermal Rod** | Mo, ∅7.00 mm, ground & calibrated | [5-fuel-column.md] |
| **Alignment Bushing** | Graphite + BN coating, ∅21/∅20×300 mm | This section |

---

## II. Assembly Phase

### 2.1 Outside Vacuum Furnace
| Step | Operation | Parameters | Tooling |
|:---|:---|:---|:---|
| **1** | Heat rod lower end | ~1000 K, induction heating | Electric inhibitor |
| **2** | Insert rod **with pellets/inserts installed** into bushing | Stack inside bushing | Graphite bushing |
| **3** | Fix assembly | Bushing protrudes 27 mm above cladding | Manipulator gripper |

### 2.2 Inside Vacuum Furnace
| Step | Operation | Parameters | Notes |
|:---|:---|:---|:---|
| **4** | Weld cladding to reactor bottom | TIG, 2×4 mm seam, **internal access** | **Welding tool enters from top** |
| **5** | Lower bushing into cladding | Mini-manipulator | **Bushing ensures coaxial alignment** |
| **6** | Braze rod to reactor | 1000 K, uniform top pressure | **Hydraulic press on manipulator** |
| **7** | Extract bushing | ~50 N pull force | **Manipulator grips 27 mm protrusion. BN coating + graphite** |
| **8** | Braze flange to cladding | 1500 K, heat cladding top | **Electric inhibitor** |
| **9** | Cool brazed zone | To 1000 K | **Cold argon (Ar), 5–10 min** |
| **10** | Braze tip to flange | 1000 K, heat only tip bottom | **Top pressure — manipulator** |

---

## III. Helium Filling

| Step | Operation | Parameters | Tooling |
|:---|:---|:---|:---|
| **1** | Fill fuel column | Micro-hole ∅0.3 mm in reactor bottom | Needle injector |
| **2** | Fill gas column | Micro-hole ∅0.2 mm in tip apex | Micro-drill |
| **3** | Pressure check | **5 atm at 273 K** | Helium leak detector |
| **4** | Seal holes | Electro-erosion welding | ∅0.1 mm electrode |

---

## IV. Quality Control

| Inspection Type | Target | Parameters | Acceptance Criteria |
|:---|:---|:---|:---|
| **Helium leak test** | Cladding & joint integrity | 8 atm, 273 K | Leak rate < 10⁻⁹ m³·Pa/s |
| **Ultrasonic (UT)** | Weld/braze defects (voids, cracks) | 5–10 MHz | Defects < 0.1 mm² |
| **X-ray** | Coaxiality, gaps, pellet position | 150 kV, 50 µm resolution | Deviation ≤0.1 mm |
| **SAW sensor test** | Functionality, accuracy | 300–1000 K | Linear response, stable signal |

---

## V. Open Issues & Challenges

| Problem | Severity | Proposed Approach |
|:---|:---|:---|
| **Helium filling** | High | Micro-holes in bottom + tip, sealed after filling |
| **Internal welding (∅21 mm)** | High | Orbital TIG / fiber-delivered laser |
| **Mass production tolerances** | Medium | Laser scanning + statistical process control |
| **Brazing temperatures** | Medium | **All values are estimates — require experimental validation** |
| **Graphite bushing extraction** | Low | BN coating + 0.5° taper |

---
***Not finished yet ⚠️.***