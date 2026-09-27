# FLL 2026 BIOGLOW Season: Innovation Project 12-Week Milestone Roadmap & FLL Rubrics Alignment Matrix

## Project: The Tree Stethoscope (Early-Stage Acoustic Bio-Sentinel for Emerald Ash Borer Detection)

**Team:** JoyRobots Rangers (#77358) | **Focus:** Urban Forest Canopy Protection & Sub-Bark Invasive Pest Defense

```text
┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐   ┌─────────────────┐
│   Milestone 1   │──►│   Milestone 2   │──►│   Milestone 3   │──►│   Milestone 4   │──►│   Milestone 5   │
│    Identify     │   │     Design      │   │     Create      │   │     Iterate     │   │   Communicate   │
│    [3 Weeks]    │   │    [2 Weeks]    │   │    [3 Weeks]    │   │    [2 Weeks]    │   │    [2 Weeks]    │
└─────────────────┘   └─────────────────┘   └─────────────────┘   └─────────────────┘   └─────────────────┘
  Week 1 ~ Week 3       Week 4 ~ Week 5       Week 6 ~ Week 8       Week 9 ~ Week 10     Week 11 ~ Week 12

```

| Week | Saturday | Innovation Project Milestone | Main Work | Robot Game & Presentation Practice |
| --- | --- | --- | --- | --- |
| **1** | Sep 12 | **1 — Identify** | Planned: macro urban canopy briefing; introduce tree cooling/flood defenses; assign Week 1 Secret Tree Detective homework sheet. Confirm what occurred. | Planned: set up field mat and practice basic single-degree motor rotations. Confirm actual work. |
| **2** | Sep 19 | **1 — Identify** | Planned: review homework on local invaders; unpack CFIA "2-minute check" blindspots; sign team mission ownership charters. Confirm what occurred. | Planned: basic straight-line navigation and first mission touch. Confirm actual work. |
| **3** | Sep 26 | **1 — Identify** | Confirm Weeks 1–2 work; synthesize student EAB research, compare current inspection methods, and finalize three LEAF tour questions. Assign sensor and controller owners. | Confirm robot baseline; draft navigation pseudocode; 1–2 min speaking drill. |
| **4** | Oct 3 *(Tour Oct 4)* | **2 — Design** | Prepare a system sketch and test plan; **attend the LEAF Tree Tour at Meander Park if confirmed**. Record observations and expert answers before finalizing the acoustic concept. | Choose priority robot missions; outline the 5-minute project pitch. |
| **5** | Oct 10 | **2 — Design** | Compare IMU and contact piezo options; bench-test one available sensor on wood and save readings. Use the result to guide the 3D-printed clamp and weather enclosure design. | Standardize modular attachments; practice 2–3 minutes per presentation part. |
| **6** | Oct 17 | **3 — Create** | Demonstrate the sensor-to-signal-to-alert chain and save wiring, code, and a short recording. Start "The Anatomic Tree Trunk" hinged demonstration model in parallel. | Test priority robot scoring runs; explain mechanical levers and the sensor demo aloud. |
| **7** | Oct 24 | **3 — Create** | Integrate the chosen contact sensor with the wood display; calibrate baseline noise and implement a simple pulse threshold. Document mounting and repeat trials. | Refine robot runs; practice 4-minute presentation runs with live timing. |
| **8** | Oct 31 | **3 — Create** | Add the waveform display and alert; test scratch and background inputs, recording both misses and false alerts. Explain that scratch triggering is a simulated signal. | First timed 5-minute run for both Robot Game and Innovation Project. |
| **9** | Nov 7 | **4 — Iterate** | Environmental noise filtering: program dynamic baseline calibration and duration window filters to eliminate wind and traffic interference. | Measure run-to-run consistency; log failure modes in the Hall of Failures. |
| **10** | Nov 14 | **4 — Iterate** | Test outdoor weatherproofing (PETG enclosure with stemflow rain-deflector and tree-friendly straps); finalize power consumption budget. | Full 5-minute rehearsals followed by adversarial mock judge questions. |
| **11** | Nov 21 | **5 — Communicate** | Share the prototype and measured results with LEAF / municipal forestry experts or another outside audience; record their actual feedback. | Deliver complete timed presentation to an outside guest audience. |
| **12** | Nov 28 | **5 — Communicate** | Document which expert feedback changed the design and why; finalize the 3-fold display showboard and Engineering White Paper. | Full mock judging session covering Project, Robot Design, and Core Values. |
| **13** | Dec 5 | **Five Milestones Complete** | Address minor feedback items from mock sessions; verify backup hardware and batteries. | Two timed dress rehearsals with all speakers, props, and live demos. |
| **14** | Dec 12 | **Five Milestones Complete** | Inspect transport packing, uniform badges, portfolio binders, and presentation props. | One calm, finalized run-through; lock down all systems for competition. |

---

## Weekly Breakdown & Execution Plan

### 🟢 Milestone 1: Problem Identification & Research into Existing Solutions (Identify) — 3 Weeks

* **FLL Rubric Alignment:** **Identify** (Clear real-world problem statement, thorough multi-source research, comprehensive analysis of existing solutions and their limitations)
* **Timeline:** Week 1 – Week 3
* **Week 1: Macro Canopy Crisis & Conceptual Exploration**
* **Instruction & Hands-on:** Explore the role of urban tree canopies as natural infrastructure (stormwater sponges, heat-island cooling, air filtration); discuss the catastrophic impacts of sudden urban canopy loss.
* **Deliverables:** Complete the simplified *Week 1: Secret Tree Detective* research worksheet; investigate invasive threats across Ontario and the Greater Toronto Area (GTA).


* **Week 2: Under-Bark Invaders & Conventional Inspection Blindspots**
* **Instruction & Hands-on:** Review student findings identifying the **Emerald Ash Borer (EAB)** as Ontario's primary forest threat; analyze Canadian Food Inspection Agency (CFIA) survey protocols (checking sawdust, bark cracks, canopy dieback); identify the critical flaw: *visible external damage only appears after internal vascular destruction is irreversible*.
* **Deliverables:** Confirm target problem statement; sign the team mission ownership charter; document limitations of late-stage visual inspections.


* **Week 3: Competitive Analysis & Field Tour Preparation**
* **Instruction & Hands-on:** Benchmark existing municipal defenses: high-cost systemic trunk micro-injections (TreeAzin, $200–$500/tree, only viable if canopy loss < 30%), pheromone traps (detect adult flight but not specific infested trees), and bulky industrial acoustic emission detectors ($3,000+ hand-carried units); formulate an early acoustic detection hypothesis.
* **Deliverables:** Produce the *Defect Matrix of Existing Forest Pest Monitoring Technologies*; draft 3 inquiry questions for LEAF arborists regarding early-stage detection challenges to deploy during the Meander Park field trip.



---

### 🔵 Milestone 2: Innovative Solution & Real-World Feasibility (Design) — 2 Weeks

* **FLL Rubric Alignment:** **Design** (Originality/breakthrough nature of the solution, practical feasibility, clear consideration of engineering constraints and trade-offs)
* **Timeline:** Week 4 – Week 5
* **Week 4: Field Scouting & Stakeholder Engagement (LEAF Tree Tour, Meander Park)**
* **Instruction & Hands-on:** Attend the guided LEAF Tree Tour at Meander Park in Richmond Hill (Oct 4); observe mature ash trees, inspect bark conditions, and interview forestry guides regarding local EAB damage and municipal replacement costs.
* **Deliverables:** Log real-world field notes and photo evidence in `leaf_tree_tour_oct04_notes.md`; establish direct contact with community forestry specialists; lock in project scope: **The Tree Stethoscope**.


* **Week 5: Sensor Physics & Engineering Trade-offs**
* **Instruction & Hands-on:** Evaluate hardware constraints: demonstrate why built-in IMUs (e.g., Bosch BMI270 on CoreS3) fail due to high noise floors ($160\ \mu\text{g}/\sqrt{\text{Hz}}$) and housing damping; select an external piezoelectric contact probe (Seeed Grove Piezo + LM358 pre-amp) coupled with a micro-invasive 1.2mm acoustic transmission pin (aligned with tree-healing CODIT principles); evaluate non-destructive tree-mounting requirements (elastic straps, no permanent nails).
* **Deliverables:** Complete the *Sensor Selection & Trade-off Analysis Log*; draft CAD drawings for the 3D-printed PETG enclosure featuring a top stemflow rain-deflector and bottom acoustic probe pass-through.



---

### 🟡 Milestone 3: Working Functional Prototype & Physical Sandbox (Create) — 3 Weeks

* **FLL Rubric Alignment:** **Create** (Development of a working functional model/prototype that clearly demonstrates core operating principles and physical mechanics)
* **Timeline:** Week 6 – Week 8
* **Week 6: "The Anatomic Tree Trunk" Physical Sandbox Assembly**
* **Instruction & Hands-on:** Construct the competition demonstration prop: halve a real hardwood/ash log (20–25 cm length) and join it with metal hinges; carve replica sub-bark S-shaped larval galleries and install an enlarged 3D-printed EAB larva on the inner face; drill a guide channel so the external sensor probe touches the inner wood interface when closed.
* **Deliverables:** Complete assembly of the hinged interactive display log, enabling judges to view external non-destructive mounting alongside hidden internal damage.


* **Week 7: Sensing Layer & Signal Acquisition Pipeline**
* **Instruction & Hands-on:** Interface the Grove Piezo Sensor with M5Stack CoreS3 via Port B (ADC); configure pre-amp potentiometer sensitivity; program dynamic baseline calibration ($V_{base}$) to measure ambient acoustic noise upon boot.
* **Deliverables:** Real-time analog amplitude waveform rendering on the CoreS3 2.0-inch LCD screen; verified capture of stress-wave mechanical vibrations conducted through the wood.


* **Week 8: Edge Feature Extraction & Alert Logic Validation**
* **Instruction & Hands-on:** Code the time-domain pulse burst verification state machine in UIFlow/MicroPython; apply temporal filters requiring valid chewing spikes ($2\text{ms} < t_{burst} < 15\text{ms}$) and train density verification ($\ge 4$ pulses within 3 seconds) to distinguish insect feeding from isolated knocks.
* **Deliverables:** Fully functioning prototype demonstration: executing an imperceptible micro-scratch on the log triggers a screen transition from a green resting line to a flashing red alert: `"BIO-THREAT DETECTED: EAB CHEWING FREQUENCY CONFIRMED"`.



---

### 🔴 Milestone 4: Robustness Testing & Engineering Iterations (Iterate) — 2 Weeks

* **FLL Rubric Alignment:** **Iterate** (Rigorous experimental testing, data-driven modifications based on failure points, evidence of multi-stage design evolution)
* **Timeline:** Week 9 – Week 10
* **Week 9: Environmental Noise Filtering & Firmware Refinement**
* **Instruction & Hands-on:** Test acoustic resistance against ambient forest noise (wind, rain drops, highway vibrations from nearby traffic, human footsteps); implement a moving-average envelope filter and high-pass threshold logic to eliminate false positive triggers caused by continuous low-frequency vibrations ($< 500\text{ Hz}$).
* **Deliverables:** Compile the *Acoustic Rejection Test Matrix*; plot the *False-Alarm Rate Reduction Chart* demonstrating suppression of false positives under continuous simulated background noise.


* **Week 10: Weatherproofing, Deployment Hardening & Field Validation**
* **Instruction & Hands-on:** Print the finalized IP65-rated PETG enclosure; install silicone gaskets and test water deflection against downward tree trunk water runoff (stemflow); test low-power sleep/wake intervals to ensure battery longevity; evaluate transition toward ultra-compact field nodes (AtomS3 Lite).
* **Deliverables:** Complete the waterproof field-ready prototype; document battery endurance budget logs; capture time-stamped outdoor installation test photos on a live park tree.



---

### 🟣 Milestone 5: Expert Feedback Loop & Presentation Pitch (Communicate) — 2 Weeks

* **FLL Rubric Alignment:** **Communicate & Core Values** (Sharing with diverse stakeholders, integrating professional expert critique, delivering an engaging, confident presentation with full team participation)
* **Timeline:** Week 11 – Week 12
* **Week 11: Expert Closing Loop & Community Dissemination**
* **Instruction & Hands-on:** Re-engage LEAF arborists and local conservation representatives with the completed prototype data; incorporate feedback (e.g., adding a warning log for anomalous bark-loosening detachment); present the solution to school science classes, parents, and community park volunteers.
* **Deliverables:** Archive written professional correspondence; compile community feedback evaluation forms; bind the 20–25 page *Project Tree Stethoscope Engineering White Paper* (including schematics, biological acoustic citations, and 3D exploded views).


* **Week 12: High-Impact Pitch Rehearsal & Defense Finalization**
* **Instruction & Hands-on:** Rehearse the 5-minute unscripted presentation structured around the **"Because (invisible sub-bark crisis) ➔ But (visual checks are post-mortem) ➔ So (acoustic edge detection)"** narrative arc; master the live interactive log demonstration (opening the hinged trunk to reveal inner galleries); conduct intensive Q&A defense drills.
* **Deliverables:** Complete the tri-fold presentation showboard; lock speaking roles across all team members; achieve flawless execution of the live log scratch-and-alert demonstration.



---

## 12-Week Roadmap vs. FLL Rubrics Gate Matrix

| Timeline | Milestone | FLL Official Rubric Criteria | Definition of Done (DoD) |
| --- | --- | --- | --- |
| **W1 ~ W3** | **M1: Identify**<br>

<br>(3 Weeks) | **Identify**<br>

<br>• Clear, well-defined problem statement<br>

<br>• Rigorous, multi-source evidence chain<br>

<br>• Thorough analysis of existing solutions and defects | • Defined EAB internal larval damage and urban canopy vulnerability in Ontario.<br>

<br>• Reviewed CFIA inspection protocols and documented visual inspection blindspots.<br>

<br>• Prepared 3 targeted arborist inquiry questions ahead of the field visit. |
| **W4 ~ W5** | **M2: Design**<br>

<br>(2 Weeks) | **Design**<br>

<br>• Original, breakthrough concept<br>

<br>• Realistic, practical feasibility<br>

<br>• Articulated engineering constraints and trade-offs | • Completed LEAF Tree Tour at Meander Park; logged field notes and photo evidence.<br>

<br>• Documented sensor trade-off (abandoned internal IMU for external piezo probe).<br>

<br>• Designed CAD models for 3D-printed enclosure with stemflow rain-deflector. |
| **W6 ~ W8** | **M3: Create**<br>

<br>(3 Weeks) | **Create**<br>

<br>• Functional, working prototype<br>

<br>• Direct visual proof of core mechanisms<br>

<br>• Integrated hardware-software pipeline | • Built hinged "Anatomic Tree Trunk" demonstration prop with S-shaped galleries.<br>

<br>• Integrated M5Stack CoreS3, Grove Piezo sensor, and acoustic transmission pin.<br>

<br>• Programmed real-time oscilloscope display and instant red bio-threat alert pop-up. |
| **W9 ~ W10** | **M4: Iterate**<br>

<br>(2 Weeks) | **Iterate**<br>

<br>• Rigorous experimental testing<br>

<br>• Design modifications driven by failure logs<br>

<br>• Multi-stage evolutionary iterations | • Tuned temporal pulse-burst filter to suppress wind/traffic false alarms to $< 2\%$.<br>

<br>• Validated IP65 PETG enclosure against water runoff and tested elastic tree straps.<br>

<br>• Documented design evolution from single-screen CoreS3 to compact field nodes. |
| **W11 ~ W12** | **M5: Communicate**<br>

<br>(2 Weeks) | **Communicate & Core Values**<br>

<br>• Direct collaboration with industry experts<br>

<br>• External critique incorporated into solution<br>

<br>• High-engagement, confident team presentation | • Archived professional feedback from LEAF/conservation arborists into firmware.<br>

<br>• Bound the complete Engineering White Paper and finalized the tri-fold showboard.<br>

<br>• Polished the 5-minute pitch featuring the live log reveal and sensor trigger demo. |
