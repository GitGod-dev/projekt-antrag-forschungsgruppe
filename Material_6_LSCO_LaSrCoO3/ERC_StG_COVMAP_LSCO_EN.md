European Research Council – Starting Grant 2027 (ERC-2027-StG)

 

 

 

**COVMAP**

**Covalency Maps for Memristive Oxides: Turning Oxygen-Vacancy Energetics into a Design Tool for Neuromorphic Hardware**

 

 

| **Principal Investigator** | Dr. Max Buczek |
|----|----|
| **Current position** | Feodor Lynen Research Fellow (Alexander von Humboldt Foundation), group of Prof. W. C. Chueh, Stanford University / SLAC, USA; previously Peter Grünberg Institute (PGI-7, Electronic Materials), Forschungszentrum Jülich, Germany |
| **Host Institution** | \[RWTH Aachen University or Forschungszentrum Jülich – to be fixed; Commitment of the Host Institution form to be attached. The grant marks the PI’s return to Europe after the Feodor Lynen fellowship; the ≥50 % residency condition will be met from the project start.\] |
| **Primary panel** | PE3 Condensed Matter Physics (PE3_4 electronic properties of interfaces and nanostructures; PE3_5 semiconductors/insulators: growth and properties); secondary keywords: PE11_7 engineering of metal oxides, PE7_5 nanoelectronics |
| **Duration** | 60 months |
| **Requested budget** | 1,497,500 € (incl. 25 % indirect costs) + 805,000 € additional funding for major equipment |
| **Call deadline** | \[October 2028 (ERC-2029-StG) – adjust to the actual submission date during/after the Lynen fellowship; PhD defence 2026 → comfortably eligible under the 0–10-year window\] |

 

Note: This is a complete draft following the new ERC proposal structure introduced with the 2026 Work Programme (Part B1: 5-page Extended Synopsis + 4-page CV and Track Record; Part B2: 7-page implementation). Bracketed items must be finalised before submission. The project is the ERC variant of the same research programme as the DFG Emmy Noether draft COMET-Ox; parallel submission is permissible, but double funding is not – disclose parallel applications in Part A.

# Part B1 – Extended Synopsis

## 1  The vision: from trial-and-error to treasure maps for memristive materials

Analog, brain-inspired computing needs a memory element that can be programmed gradually, retains its state, and can be manufactured reproducibly. Redox-based memristive devices – in which an electric field creates and moves oxygen vacancies in an oxide – are the leading candidate \[1–3\], yet after two decades of research the field still selects its materials essentially by trial and error. There is no quantitative rule that tells us *which oxide* will switch with *which* ON/OFF window, forming voltage, or retention. Every laboratory optimises its own material in its own device geometry, and results cannot be compared across studies. This is the central bottleneck between memristive physics and deployable neuromorphic hardware.

Meanwhile, an entirely different community has solved a structurally identical problem. Energy research (solid-oxide fuel cells, water splitting, solar thermochemistry) discovered that the key quantity of oxide redox chemistry – the **oxygen-vacancy formation energy E<sub>V</sub>** – is controlled by the **metal–oxygen covalency**, quantified by the charge-transfer energy and the O-2p band centre, and that this descriptor predicts catalytic activity across whole material families with R² \> 0.8 \[7, 8\]. Materials there are no longer found; they are *located* on descriptor maps \[7–12\]. Wuttig and co-workers have shown for chalcogenides how powerful such quantum-chemical “treasure maps” can be: two bonding descriptors separate bonding regimes and predict optical, thermoelectric and phase-change properties \[17\].

**COVMAP will build the treasure map for memristive oxides.** My central hypothesis is that the same descriptor pair – covalency and oxygen-vacancy formation energy – that organises oxide catalysis also organises memristive switching, because both phenomena are governed by the same elementary event: the creation and annihilation of oxygen vacancies. If this is true, the ON/OFF ratio, forming voltage and retention of a memristive device become *predictable material properties*, and the search for neuromorphic memory materials turns from an art into cartography. If successful, COVMAP delivers the first predictive, experimentally calibrated materials-selection map for redox-based memory – a tool of immediate use to every group and company developing neuromorphic hardware.

## 2  Why this is ground-breaking – and why it has not been done

The knowledge exists on both sides of the gap, but nobody has connected them. On the memristive side, quantitative models show that vacancy formation and migration energies enter switching currents and times *exponentially* \[2, 4, 31\]; operando spectromicroscopy has proven that a factor 2–3 change in local vacancy concentration moves device resistance by two orders of magnitude \[5, 6\]. On the descriptor side, DFT databases with thousands of computed E<sub>V</sub> values \[11, 12\] and validated covalency scales \[14–16\] exist. Yet a systematic experiment that varies covalency *continuously* in one structural family and measures switching under constant device architecture has never been performed; the closest approaches are vacancy-configuration design in a single solid solution \[18\] and dopant-tuning DFT studies on binary oxides without experimental series verification \[19, 32\]. My literature analysis identifies only a handful of composition series in the entire perovskite ReRAM literature \[20–22, 30, 33\] – none linked to vacancy energetics, none with spectroscopic descriptor quantification, and for the ferrite series La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> not a single intermediate-composition memristor study exists (the closest neighbour is a three-terminal electrochemical study \[26\]). Along the descriptor chain the evidence is complementary but nowhere complete: canonical covalency-vs-doping spectroscopy exists for the ferrite and manganite series \[14\], a quantitative EV(x) relation with explicit covalency reasoning only for the ferrites \[13, 34\], and switching at inert or noble interfaces proven for individual stoichiometries only (Pt/SrTiO3 with cation-stoichiometry control \[22\]; the Sr-rich ferrite end member under inert stacks \[23–25\]; Pr1-xCaxMnO3 between noble Pt contacts \[36\]) – no system combines all three links, and the missing composition series are thus the field's untapped optimisation space, accessible from a demonstrated switching base. The reason is structural: the experiment requires epitaxial synthesis of full composition series, device integration, statistically robust switching metrology, and synchrotron spectroscopy – a combination that established groups assemble only piecewise. As an early-career PI trained in exactly this combination, I can build the missing bridge in one coherent programme.

The conceptual risk is real and honest: the descriptor may not survive the transfer from thermodynamic equilibrium (catalysis) to the strongly driven, non-equilibrium regime of nanosecond switching. But the prize scales with the risk: even a *partial* correlation would replace anecdotal material choice by rational pre-selection; a validated map would redefine how the field chooses materials. Preliminary evidence makes the gain plausible: the few existing composition series consistently show a *non-monotonic* optimum of the switching window with doping \[20–22, 35\] – exactly the structured landscape a descriptor map predicts – and the end members with the lowest E<sub>V</sub> (SrFeO<sub>x</sub>, SrCoO<sub>x</sub>) show the largest topotactic switching contrast (ON/OFF ≈ 10<sup>4</sup>, endurance up to 10<sup>7</sup> cycles) \[23–25\]. Most importantly, my own ongoing Feodor Lynen project at Stanford provides direct preliminary evidence: an epitaxial La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> pilot series with its switching-proven SrCoOx anchor, measured under inert Au/Pt electrodes – the geometry in which the end member’s switching is already published – with an experimentally measured XAS covalency scale correlated against the switching metrics of the same cells \[insert one-sentence headline result once available; manuscript in preparation, P1\]. This is the proof of concept that both axes of the map can be measured on one and the same device.

## 3  Objectives

**O1 – Isolate covalency as the control variable.** Grow three epitaxial perovskite series by pulsed laser deposition – La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> (primary, largest documented E<sub>V</sub> span: ≈4 eV → \<1 eV across x = 0–0.5 \[13, 34\]), Pr<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub> (reference; noble-contact switching demonstrated \[36\]), La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> (map densification) – building on the noble-electrode descriptor methodology (inert-contact devices + XAS covalency scale) that I de-risked on La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> during my Feodor Lynen fellowship – and integrate them into one frozen device platform, so that A-site stoichiometry tunes covalency continuously while structure, electrodes and geometry stay constant. Epitaxial strain (substrate choice) provides a second, chemistry-free handle on E<sub>V</sub> \[27, 28\] as an internal consistency test.

**O2 – Measure the descriptors, not just compute them.** Establish an experimental covalency scale from the O-K pre-edge intensity and transition-metal L-edge X-ray absorption spectroscopy \[14–16\] for every composition, calibrated against literature DFT \[11–13\] and charge-transfer analysis – making the map independent of material-specific theory.

**O3 – Chart the switching landscape.** Measure ON/OFF ratio, forming/switching voltages, kinetics (10 ns–1 s), retention and endurance under one protocol with ≥30 devices per composition, and test the two central hypotheses: (H1) switching metrics scale with the covalency descriptor; (H2) a “Goldilocks” optimum exists where the usable window is maximal between the hard-to-form and the unstable-state regimes.

**O4 – Deliver and blind-validate the map.** Construct the covalency–E<sub>V</sub> map with switching metrics as colour-coded layers, including operando X-ray spectromicroscopy verification that descriptor-tuned devices differ in vacancy dynamics; then select an oxide *outside* the training set, predict its switching quantitatively, and test the prediction – the decisive falsifiable step from correlation to design tool.

## 4  Approach and why I will succeed

The methodology rests on three pillars. **(i) Synthesis with stoichiometric authority:** RHEED-controlled PLD \[29\] of full composition series with cation stoichiometry controlled via fluence/pressure windows and oxygen stoichiometry via p(O<sub>2</sub>) protocols – the growth physics I applied at wafer scale during my PhD. **(ii) Statistically robust device metrology:** a constant platform (Nb:SrTiO<sub>3</sub> or SrRuO<sub>3</sub> bottom electrodes, lithographically defined cells, graphene top electrodes for operando access \[6\]), with the variability-aware measurement methodology (device-to-device and cycle-to-cycle statistics, kinetics, retention Arrhenius analysis) that I developed for area-dependent PCMO devices. **(iii) Spectroscopic descriptor quantification:** soft-X-ray absorption at European synchrotrons (BESSY II, PETRA III, ESRF), transferring the established O-K pre-edge hybridisation analysis \[14–16\] to full memristive material series for the first time, and in the second phase operando spectromicroscopy of switched cells \[5, 6\].

I am, arguably uniquely, positioned for exactly this programme: my doctoral work in the Dittmann group (FZ Jülich) covered the complete chain from large-area PLD process development through cleanroom device integration to switching statistics on a mixed-valent, A-site-substituted manganite (Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub>) – the very material class and doping principle COVMAP generalises. My first-author review on PCMO-based memristive heterostructures (Chemical Reviews 2025) maps the mechanistic state of the art; my device papers (Advanced Electronic Materials 2026; Thin Solid Films 2024) demonstrate the fabrication and metrology base. The synchrotron dimension I have since added during my current Feodor Lynen fellowship in the Chueh group at Stanford: within the fellowship project I have grown a La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> pilot series with its SrCoOx anchor, established the O-K/Co-L covalency scale across it at SSRL, and correlated it with switching in noble-contact devices \[preliminary data; manuscript in preparation, P1\]. COVMAP scales this proven approach – developed independently of my PhD environment and now backed by an established transatlantic collaboration with the Chueh group and by European beamline and DFT partners \[letters to be attached\] – from one pilot series to the full three-family map.

**Gain if successful:** a published, open, blind-validated design map plus the underlying FAIR database – the “periodic table” moment for redox-based memory materials, with direct impact on neuromorphic hardware, and conceptual feedback to catalysis and solid-state ionics (does the equilibrium descriptor survive extreme non-equilibrium?). **Risk management in brief:** the programme is modular – each series and each descriptor axis has stand-alone publication value; if H1 fails in one family, the cross-family comparison (Fe vs. Mn vs. Co) localises why, which is itself a discovery about the limits of descriptor physics (full risk table in B2).

## References (Part B1)

\[1\] R. Waser, M. Aono, Nature Materials 6, 833–840 (2007).

\[2\] R. Dittmann, S. Menzel, R. Waser, Advances in Physics 70, 155–349 (2021).

\[3\] J. J. Yang, D. B. Strukov, D. R. Stewart, Nature Nanotechnology 8, 13–24 (2013).

\[4\] S. Menzel, M. Waters, A. Marchewka, U. Böttger, R. Dittmann, R. Waser, Advanced Functional Materials 21, 4487–4492 (2011).

\[5\] C. Baeumer et al., Nature Communications 6, 8610 (2015).

\[6\] C. Baeumer et al., Nature Communications 7, 12398 (2016).

\[7\] Y.-L. Lee, J. Kleis, J. Rossmeisl, Y. Shao-Horn, D. Morgan, Energy & Environmental Science 4, 3966–3970 (2011).

\[8\] R. Jacobs, J. Hwang, Y. Shao-Horn, D. Morgan, Chemistry of Materials 31, 785–797 (2019).

\[9\] A. M. Deml, V. Stevanović, C. L. Muhich, C. B. Musgrave, R. O’Hayre, Energy & Environmental Science 7, 1996–2004 (2014).

\[10\] R. B. Wexler, G. Sai Gautam, E. B. Stechel, E. A. Carter, Journal of the American Chemical Society 143, 13212–13227 (2021).

\[11\] A. A. Emery, C. Wolverton, Scientific Data 4, 170153 (2017).

\[12\] B. Baldassarri et al., Chemistry of Materials 35, 10619–10634 (2023).

\[13\] A. M. Ritzmann, A. B. Muñoz-García, M. Pavone, J. A. Keith, E. A. Carter, Chemistry of Materials 25, 3011–3019 (2013).

\[14\] M. Abbate et al., Physical Review B 46, 4511–4519 (1992).

\[15\] J. Suntivich et al., Journal of Physical Chemistry C 118, 1856–1863 (2014).

\[16\] F. Frati, M. O. J. Y. Hunault, F. M. F. de Groot, Chemical Reviews 120, 4056–4110 (2020).

\[17\] M. Wuttig et al., Advanced Materials 35, 2208485 (2023).

\[18\] R. Schmitt, J. Spring, R. Korobko, J. L. M. Rupp, ACS Nano 11, 8881–8891 (2017).

\[19\] H. Jiang, D. A. Stewart, ACS Applied Materials & Interfaces 9, 16296–16304 (2017).

\[20\] S. Asanuma, H. Akoh, H. Yamada, A. Sawa, Physical Review B 80, 235113 (2009).

\[21\] V. Lähteenlahti, A. Schulman, A. Beiranvand, H. Huhtinen, P. Paturi, ACS Applied Materials & Interfaces 13, 18365–18371 (2021).

\[22\] E. Mikheev, J. Hwang, A. P. Kajdos, A. J. Hauser, S. Stemmer, Scientific Reports 5, 11079 (2015).

\[23\] V. R. Nallagatla et al., Advanced Materials 31, 1903391 (2019).

\[24\] J. Tian et al., Advanced Materials 31, 1903679 (2019).

\[25\] X. Mou et al., Science Advances 7, eabh0648 (2021).

\[26\] P. Nizet et al., Applied Physics Reviews 11, 041426 (2024).

\[27\] U. Aschauer, R. Pfenninger, S. M. Selbach, T. Grande, N. A. Spaldin, Physical Review B 88, 054111 (2013).

\[28\] M. Kubicek et al., ACS Nano 7, 3276–3286 (2013).

\[29\] G. J. H. M. Rijnders, G. Koster, D. H. A. Blank, H. Rogalla, Applied Physics Letters 70, 1888–1890 (1997).

\[30\] S. G. Choi, H.-S. Lee, H. Choi, S.-W. Chung, H.-H. Park, Thin Solid Films 529, 352–355 (2013).

\[31\] A. Sarantopoulos, K. Lange, F. Rivadulla, S. Menzel, R. Dittmann, Advanced Electronic Materials 11, 2400555 (2025).

\[32\] M. Mladenović, M. Kaniselvan, C. Weilenmann, A. Emboras, M. Luisier, ACS Applied Electronic Materials 7, 2839–2847 (2025).

\[33\] A. Schulman, H. Huhtinen, P. Paturi, Journal of Physics D: Applied Physics 57, 422001 (2024).

\[34\] J. A. Santana, J. T. Krogel, P. R. C. Kent, F. A. Reboredo, The Journal of Chemical Physics 147, 034701 (2017).

\[35\] A. Antola et al., ACS Applied Electronic Materials 7, 4242–4250 (2025).

\[36\] T. Kramer, M. Scherff, D. Mierwaldt, J. Hoffmann, C. Jooss, Applied Physics Letters 110, 243502 (2017).

# Part B1 – Curriculum Vitae and Track Record (max. 4 pages)

## Personal details

Dr. Max Buczek · born 17 March 1994 · German · max.buczek@mailbox.org · Postdoctoral Researcher, Peter Grünberg Institute (PGI-7), Forschungszentrum Jülich, Germany

## Education and positions

| **Period** | **Position / Degree** |
|----|----|
| \[2027\] – present | Feodor Lynen Research Fellow (Alexander von Humboldt Foundation), group of Prof. W. C. Chueh, Stanford University / SLAC – covalency descriptors for memristive cobaltites: epitaxial La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> pilot series with noble-contact devices, XAS covalency scale at SSRL \[manuscript in preparation, P1\] |
| 07/2025 – \[2027\] | Postdoctoral Researcher, PGI-7, Forschungszentrum Jülich (advisor: Prof. R. Dittmann) – memristive optical phase shifters, EU project NeuroSys; patent application; supervision of master’s students |
| 2020 – 2026 | Doctorate (Dr.-Ing., Electrical Engineering), RWTH Aachen University / FZ Jülich. Thesis: “BEOL-Compatible Area-Dependent Memristive Devices from Wafer-Scale Pulsed Laser Deposited Amorphous Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub>” \[defence date to be inserted\] |
| 2015 – 2020 | M.Sc. Physics, University of Göttingen (focus: condensed matter and materials physics); Master’s thesis at Laser-Laboratorium Göttingen; Erasmus semester, University of Groningen (2018–2019) |
| 2012 – 2015 | B.Sc. Physics, University of Göttingen |

## Track record

**Selected publications:**

P1. M. Buczek, \[co-authors\], W. C. Chueh, \[working title: An experimental covalency scale for memristive La1-xSrxCoO3-δ\], manuscript in preparation (from the Feodor Lynen fellowship; insert status – in preparation / submitted / published – at submission time).

1\. M. Buczek et al., Amorphous, Highly Conductive Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> for Area-Dependent Resistive Switching Devices, Advanced Electronic Materials (2026, accepted).

2\. M. Buczek, Z. Moos, A. Gutsche, S. Menzel, R. Dittmann, Pr<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub>-Based Memristive Heterostructures: Basic Mechanisms and Applications, Chemical Reviews 125, 6156–6202 (2025) – first-author comprehensive review of the field.

3\. M. Buczek et al., Large Area Pulsed Laser Deposition of Memristive Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> Heterostructures for Neuromorphic Computing, Thin Solid Films (2024).

**Patent:** \[Patent application, memristive optical phase shifters, EU project NeuroSys – details to be inserted.\]

**Invited/contributed talks (selection):** Memrisys 2026 (Darmstadt); E-MRS Warsaw 2023; Jülich–Twente Summit 2023. Posters at ICNCE 2024/2026, iWOE-30 2024, E-MRS Strasbourg 2024.

**Methodological breadth (evidence of capacity):** PLD incl. wafer-scale process development; sputtering; e-beam evaporation; optical and e-beam lithography; RIBE; full memristive device metrology (Keithley 2600/4200, DC and pulsed; endurance, retention, variability statistics); XRD/XRR incl. in-situ, AFM, SEM, TEM-EDX, XPS, SIMS, Raman, PDF, impedance spectroscopy, ellipsometry; COMSOL simulation; Python-based data analysis.

**Supervision and teaching:** Master’s students (2023–present); laboratory course tutor, RWTH Aachen (2020–2025).

\[Add per new ERC CV template: research stays, funding IDs, career breaks if any, 10-line narrative statement. The CV receives qualitative comments only under the 2026+ evaluation rules; the proposal itself carries the numerical scores.\]

# Part B2 – The Project Implementation (max. 7 pages)

## 1  Work plan

The five work packages implement objectives O1–O4; WP structure, staffing and interdependencies are designed so that each material series produces stand-alone results while feeding the map.

| **WP** | **Content (lead objective)** | **Staff** | **Months** |
|----|----|----|----|
| WP1 Synthesis | PLD growth of the three composition series; stoichiometry control (XPS/XRD/RSM/AFM); strain series on SrTiO<sub>3</sub>/LSAT/NdGaO<sub>3</sub> (O1) | PhD-1, PI | 1–54 |
| WP2 Devices | Frozen device platform: Nb:SrTiO<sub>3</sub>/SrRuO<sub>3</sub> bottom electrodes, lithographic cell arrays, graphene top electrodes; platform validation on Fe:SrTiO<sub>3</sub> (O1) | PhD-2, PI | 1–48 |
| WP3 Switching metrology | Quasistatic and pulsed protocols; ON/OFF, kinetics, activation energies, temperature-accelerated retention, endurance, multilevel linearity; ≥30 cells per composition (O3) | PhD-2, postdoc | 10–58 |
| WP4 X-ray spectroscopy | O-K / TM-L<sub>2,3</sub> XAS campaigns (BESSY II, PETRA III, ESRF); covalency scale; vacancy quantification; phase 2: operando spectromicroscopy with graphene electrodes (O2, O4) | PhD-1, postdoc, PI | 10–58 |
| WP5 The map | FAIR database; correlation and ML regression against literature DFT; construction of the covalency–E<sub>V</sub> map; blind validation on an out-of-sample oxide (O4) | postdoc, PI | 24–60 |

**Milestones:** M1 (mo 12) series 1+2 grown and validated; M2 (mo 18) platform freeze, first switching in series 1; M3 (mo 30) XAS covalency scale complete for series 1+2; M4 (mo 42) H1/H2 tested and published; M5 (mo 54) operando campaign and series 3 integrated; M6 (mo 60) blind-validated map and database released.

## 2  Risk assessment and mitigation

| **Risk** | **L / I** | **Mitigation / fallback** |
|----|:--:|----|
| End-member compositions (metallic or too easily reduced) fail as devices | M / M | Expected physics, not failure: boundary points define the map edges; series interior carries the correlation. Composition step size adapts. |
| Descriptor does not correlate in the non-equilibrium switching regime (H1 fails) | M / H | Cross-family comparison (Fe/Mn/Co) localises the failure mode; kinetic descriptors (migration barrier from pulsed metrology) added as third axis; a validated negative is itself a high-impact result about descriptor limits. |
| Beamtime allocation delays | M / M | Biannual applications at three facilities; laboratory proxies (XPS valence analysis, optical spectroscopy) keep WP5 supplied; collaboration letters secure block allocation participation. |
| Graphene-electrode operando devices underperform | M / L | Operando is confirmatory, not load-bearing: ex-situ before/after spectroscopy of switched large-area cells as fallback (established at PGI-7). |
| Stoichiometry drift across long growth campaigns | L / M | Calibration-sample protocol per campaign (XRR/XPS); frozen fluence/pressure windows; wafer-scale process experience of the PI. |

## 3  Team and environment

Team: PI (60 % commitment – above the 50 % minimum; remaining time: teaching and group development), two doctoral researchers (48 months each, staggered), one postdoc (30 months, from month 24, leading spectroscopy analysis and the map), student assistant. The host institution provides PLD infrastructure with high-pressure RHEED, XRD, cleanroom access (Helmholtz Nano Facility / RWTH cleanroom) and AFM/XPS as in-kind contribution \[commitment letter\]. Collaborations (letters to be attached): the Chueh group (Stanford/SSRL) – the established transatlantic partnership from the PI’s current Feodor Lynen fellowship – on defect thermodynamics and XAS methodology; FZ Jülich PGI-7 (operando spectromicroscopy methodology); European synchrotron partner \[HZB or DESY\] to transfer the SSRL-proven measurement protocols to European beamlines; DFT partner \[to be named\] for computed E<sub>V</sub>/Δ validation.

## 4  Resources

| **Cost category (60 months)** | **Amount (€)** |
|----|---:|
| PI salary (60 % of 102,300 €/a employer cost, 5 years) | 306,900 |
| 2 doctoral researchers (75 % positions, 48 months each) | 489,600 |
| Postdoctoral researcher (30 months) | 220,500 |
| Student assistant | 21,000 |
| Consumables (PLD targets ~25 compositions, substrates, gases, lithography) | 70,000 |
| Small equipment / depreciation (measurement electronics share) | 30,000 |
| Travel (conferences; synchrotron campaigns 2–3 per year) | 45,000 |
| Open-access publications, data hosting | 15,000 |
| **Total direct costs** | **1,198,000** |
| Indirect costs (25 %) | 299,500 |
| **Requested grant** | **1,497,500** |

**Additional funding request (major equipment, up to 1 M€ category): 805,000 €.** Justification: COVMAP requires a dedicated deposition and metrology line that the host provides only partially as shared infrastructure. Requested: dedicated PLD system with high-pressure RHEED and multi-target carousel for uninterrupted composition-series campaigns (650,000 €); cryogenic vacuum probe station 80–400 K (80,000 €); pulsed switching electronics (SMUs, ns pulse generator, oscilloscope, switch matrix) (45,000 €); UHV transfer suitcase for contamination-free PLD-to-synchrotron sample transfer (30,000 €). These items are used \>90 % by COVMAP and are essential for the frozen-platform methodology (identical growth and measurement conditions across five years).

**Grand total requested: 2,302,500 €.** The PI commits ≥60 % of total working time to COVMAP and will spend 100 % of the project time in an EU member state.
