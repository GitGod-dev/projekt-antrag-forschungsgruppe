DFG – Deutsche Forschungsgemeinschaft (German Research Foundation)

 

 

 

**Proposal for Funding within the Emmy Noether Programme**

 

**Covalency as a Design Parameter of Memristive Switching: Oxygen-Vacancy Energetics in Complex Oxides**

*(Acronym: COMET-Ox – “Covalency-cOntrolled MEmrisTive switching in complex OXides”)*

 

 

| **Applicant** | Dr. Max Buczek, currently Feodor Lynen Research Fellow (Alexander von Humboldt Foundation), group of Prof. W. C. Chueh, Stanford University / SLAC, USA; previously Peter Grünberg Institute (PGI-7), Forschungszentrum Jülich |
|----|----|
| **Host institution** | \[RWTH Aachen University or Forschungszentrum Jülich – to be fixed before submission; letter of commitment to be attached. The Emmy Noether group marks the applicant’s return to Germany after the Feodor Lynen fellowship, bridged if needed by the Feodor Lynen Return Fellowship.\] |
| **Subject area** | Experimental condensed matter physics / materials science (Review Board 307, alternatively 406) |
| **Funding instrument** | Emmy Noether Programme (independent junior research group) |
| **Duration** | 6 years (two funding periods of 3 years each) |
| **Requested funds** | € 1,757,700 (plus 22 % programme allowance: total volume approx. € 2.14 million) |

 

Note: This document is a complete, personalised draft proposal (English version of the German draft). Remaining \[bracketed items\] (choice of host institution, letters of commitment, bibliographic details of the applicant’s publications, starting date) must be finalised before submission. Formal eligibility: application normally within four years of the doctorate (doctorate 2026 – window until 2030).

# Summary

Redox-based memristive devices (valence change mechanism, VCM) are considered a key technology for non-volatile memory and neuromorphic computing. Their operating principle rests on the field-driven creation and redistribution of oxygen vacancies (V<sub>O</sub>). Although the oxygen-vacancy formation energy (E<sub>V</sub>) is thus the central energetic control parameter of switching, it has never been studied systematically how E<sub>V</sub> – and the metal–oxygen covalency that controls it – affects the switching figures of merit, in particular the ON/OFF ratio. In energy research (solid oxide fuel cells, water splitting, solar-thermochemical hydrogen production), by contrast, the relationship between covalency, charge-transfer energy and E<sub>V</sub> is quantitatively established: the O-2p band centre scales linearly with E<sub>V</sub> and has served there as a successful materials descriptor for more than a decade.

COMET-Ox transfers this descriptor concept systematically to memristive switching for the first time. In epitaxial model series of mixed-valent perovskites grown by pulsed laser deposition (PLD) – La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub>, La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3-δ</sub>, later La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> – the covalency is tuned continuously via the A-site stoichiometry, while crystal structure, device architecture and electrode configuration remain identical. This isolates the influence of covalency on the switching behaviour from all other variables. Covalency and vacancy concentration are quantified by X-ray absorption spectroscopy (XAS; O-K pre-edge, transition-metal L<sub>2,3</sub> edges), and the switching properties (ON/OFF ratio, switching voltages, kinetics, retention, endurance) are measured on a constant device platform.

The overarching goal is a “treasure map” for memristive oxides in analogy to the quantum-chemical bonding-descriptor maps of Wuttig et al. for chalcogenides: a two-dimensional map spanned by covalency (charge-transfer energy, or experimentally the O-K pre-edge intensity) and oxygen-vacancy formation energy, onto which the switching figures of merit are charted. This map is intended to enable, for the first time, a rational, descriptor-based materials selection for VCM memristors, and it will finally be validated by a “blind” prediction on an oxide not contained in the training set.

# 1  State of the Art and Preliminary Work

## 1.1  State of the art

### 1.1.1  Memristive switching in oxides: the valence change mechanism

Redox-based resistive memories (ReRAM) switch their resistance through field-driven nanoionic processes \[1–3\]. In the valence change mechanism (VCM), which dominates in oxides, oxygen vacancies (V<sub>O</sub>) migrate in the electric field; their local accumulation or depletion changes the valence of the transition-metal cations (e.g. Ti<sup>4+</sup> → Ti<sup>3+</sup>) and thereby modulates the conductivity or the height of the Schottky barrier at the metal/oxide interface \[3, 4\]. The authoritative systematics of the field is provided by the review of Dittmann, Menzel and Waser \[3\]. Two modes are distinguished: filamentary switching – after an electroforming step, a localised vacancy-rich conduction path is created – and area-type (“interface-type”) switching, in which the V<sub>O</sub> distribution within the depletion zone of a Schottky contact is modulated homogeneously \[4, 6\]. Both modes can coexist in the same material, as shown for Fe-doped SrTiO<sub>3</sub> \[7, 8, 83\]. Area-type switching (e.g. at Nb:SrTiO<sub>3</sub> or Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> contacts) is forming-free and analogue-tunable and therefore particularly attractive for neuromorphic synapses \[4–6\].

Direct microscopic proof of the VCM was provided by spectromicroscopic operando studies: Baeumer et al. showed by photoemission electron microscopy (X-PEEM) on SrTiO<sub>3</sub> devices that switching rests on nanoscale oxygen migration with accompanying Ti valence change \[9\], and quantified with graphene top electrodes that a change of the donor concentration (V<sub>O</sub>) by only a factor of 2–3 produces more than two orders of magnitude of resistance change via Schottky-barrier modulation \[10\]. The switching kinetics is extremely nonlinear: field acceleration and Joule heating of the ion migration span more than 15 orders of magnitude in time (the “voltage–time dilemma”) \[11, 12, 81\]. Decisive for the present project: in all quantitative models the *formation and migration energies of the oxygen vacancies enter exponentially* into switching currents, voltages and times \[3, 11, 12\] – they are the central energetic control parameters of the VCM.

In complex oxides, the topotactic phase transition adds a switching mechanism of its own: perovskite ↔ brownmillerite transitions (SrFeO<sub>3-δ</sub> ↔ SrFeO<sub>2.5</sub>, SrCoO<sub>3-δ</sub> ↔ SrCoO<sub>2.5</sub>, La<sub>2/3</sub>Sr<sub>1/3</sub>MnO<sub>3-δ</sub>) switch between phases with disordered and crystallographically ordered V<sub>O</sub> channels, respectively \[16–19\]. The crystal orientation can even toggle between area-type and localised switching \[16\]; SrCoO<sub>x</sub>-based devices achieve forming-free, analogue low-power switching with a dual volatile/non-volatile mode of operation \[20\]. Here, too, the ease of V<sub>O</sub> creation is the controlling quantity – SrFeO<sub>3-δ</sub> and SrCoO<sub>3-δ</sub> are switching-active precisely *because* of their exceptionally low vacancy formation energy (“oxygen sponges” \[63\]).

### 1.1.2  Covalency and oxygen-vacancy energetics: the descriptor knowledge of energy research

While memristics has so far mostly treated V<sub>O</sub> energetics as a given material property, energy research (solid oxide fuel cells, oxygen evolution reaction/water splitting, solar-thermochemical fuel production) has over the past fifteen years developed a quantitative descriptor framework that traces the oxygen-vacancy formation energy (E<sub>V</sub>) back to the electronic structure – ultimately to the metal–oxygen covalency. The conceptual foundation is the Zaanen–Sawatzky–Allen scheme \[21\]: the charge-transfer energy Δ (O 2p → metal 3d) measures the position of the O-2p states relative to the metal d states and is the microscopic measure of covalency. Along the perovskite series RMO<sub>3</sub> (M = Ti → Cu) the character of the band gap changes from Mott–Hubbard to charge-transfer type at about M = Cr \[22\]; late 3d perovskites with formally high oxidation states (ferrites, cobaltites, nickelates) lie in the regime of small or even negative charge-transfer energy, exhibit ligand-hole character and possess an easily reducible oxygen sublattice.

This relationship was made operational through the O-2p band centre: Lee, Morgan and co-workers showed that E<sub>V</sub> in perovskites scales linearly with the position of the O-2p band centre relative to the Fermi level and that the same descriptor predicts surface exchange coefficients and cathode activity \[23, 24\]. Jacobs et al. quantified the correlation with experimental activity measures at R² = 0.81–0.87 \[26\] and screened 2145 perovskites on this basis \[25\]. Complementary descriptor models predict E<sub>V</sub> from formation enthalpy and band gap with a mean accuracy of about 0.2 eV \[27, 28\]; Wexler et al. decomposed E<sub>V</sub> into a bond-breaking term (covalency/ionicity) and a redox term (position of the acceptor states) with an accuracy of 0.45 eV across ABO<sub>3</sub> perovskites \[29\]. High-throughput datasets with thousands of computed vacancy formation energies \[42–44\] and machine-learning models (accuracy 0.27–0.44 eV) are publicly available; remarkably, the most important ML features (formation enthalpy, band gap, O-2p band centre, electronegativity difference) reproduce exactly the physical descriptors \[44\].

For the material series envisaged in COMET-Ox, the trends are quantitatively documented: in La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub>, substituting La<sup>3+</sup> by Sr<sup>2+</sup> creates holes with substantial O-2p character, increases the Fe–O covalency and lowers E<sub>V</sub> from about 4 eV (x = 0) to below 1 eV (x = 0.5) \[31, 86\]; analogous trends hold for (La,Sr)(Co,Fe)O<sub>3-δ</sub> and (Ba,Sr)(Co,Fe)O<sub>3-δ</sub> (E<sub>V</sub> ≈ 1 eV, migration barriers 0.4–0.5 eV) \[32, 33\] and for La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> \[39\]. The electrocatalysis literature furthermore shows that an *optimum* of covalency exists: if the O-2p band centre lies too close to the Fermi level, lattice oxygen becomes redox-active and the material unstable (amorphisation, Sr segregation) \[35–37, 41\]. This “Goldilocks logic” – enough covalency for easy vacancy formation, enough stability for reversible operation – transfers directly to memristive devices, where large switching windows compete with retention and endurance.

### 1.1.3  X-ray absorption spectroscopy as a quantitative probe of covalency and vacancies

XAS provides exactly the observables required for an experimental descriptor map. The pre-edge of the O-K edge (528–532 eV) arises from transitions into unoccupied, covalently hybridised O2p–TM3d states; its integrated intensity is an established measure of metal–oxygen hybridisation \[45, 47\]. Classic work on La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3</sub> and La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3</sub> – precisely the series of this proposal – shows how hole doping systematically enhances the pre-edge (ligand-hole character) while oxygen vacancies attenuate it \[46\]. Suntivich et al. developed from this a semi-quantitative hybridisation measure per metal–oxygen bond \[40\]; Hong et al. extracted the charge-transfer energy on an absolute energy scale from combined X-ray emission and absorption \[38\]. The transition-metal L<sub>2,3</sub> edges provide a valence fingerprint via their multiplet structure, from which valence fractions – and hence V<sub>O</sub> concentrations (two electrons per vacancy) – can be determined to within a few per cent by linear combination of reference spectra \[47\].

On memristive devices, XAS-based spectromicroscopy is now operando-capable: X-PEEM with photoelectron-transparent graphene electrodes on SrTiO<sub>3</sub> cells \[9, 10\], time-resolved scanning transmission X-ray microscopy (STXM) on Ta<sub>2</sub>O<sub>5</sub> memristors \[49, 50\], operando X-ray microscopy on SrCoO<sub>x</sub> demonstrating threshold behaviour of the vacancy concentration \[51\], and HAXPES at buried HfO<sub>2</sub> interfaces \[52\]. Recent reviews and methodological work \[53, 54\] attest to the maturity of the spectromicroscopic approach. Suitable end stations are available in Germany and Europe, including SPEEM and EMIL/OÆSE at BESSY II, P04 (soft X-rays) and P22 (HAXPES) at PETRA III, ID32 at the ESRF, and SIM and PolLux at the SLS.

### 1.1.4  PLD growth of epitaxial oxide heterostructures

Pulsed laser deposition (PLD) is the method of choice for stoichiometrically complex oxide series: high-pressure RHEED enables layer-precise growth under realistic oxygen pressures \[55\], uniformly terminated SrTiO<sub>3</sub> substrates \[56\] and interval deposition \[57\] secure well-defined interfaces \[58\]. The cation stoichiometry is controlled via laser fluence and process pressure \[59\]; the oxygen stoichiometry – and thus the initial V<sub>O</sub> concentration – via the oxygen partial pressure during growth and cool-down. Epitaxial strain is a second, independent control parameter of vacancy energetics: tensile strain lowers E<sub>V</sub> and can induce vacancy ordering \[60, 61\]; experimentally it accelerates oxygen exchange and diffusion in La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> by factors of four to ten \[62\]. Epitaxially stabilised SrCoO<sub>x</sub> films act as reversible “oxygen sponges” \[63\]. Schmitt, Rupp and co-workers already demonstrated that V<sub>O</sub> configurations can be designed deliberately via solid-solution series for memristive systems \[14\] – however without systematic covalency variation and without spectroscopic descriptor quantification.

### 1.1.5  Research gap and project idea: from catalysis descriptors to a memristive treasure map

**The research gap:** No systematic experimental study exists that varies the metal–oxygen covalency – and with it the oxygen-vacancy formation energy – as a *continuous control parameter* within a structurally homogeneous material series and plots it against the memristive figures of merit (ON/OFF ratio, switching voltages, kinetics, retention, endurance) under constant device architecture. Existing approaches remain piecemeal: DFT studies on dopant tuning of E<sub>V</sub> in binary oxides (Ta<sub>2</sub>O<sub>5</sub>, ZrO<sub>2</sub>) without systematic experimental verification \[15, 82\]; V<sub>O</sub> configuration design in a single solid-solution series without covalency descriptors \[14\]; material comparisons across publication boundaries that are not quantitatively reliable because of differing electrodes and geometries \[3, 6\]. The rich descriptor knowledge of energy research \[23–44\] has simply not yet been applied to memristive switching – although both fields place the same elementary quantity E<sub>V</sub> at their centre.

**The overarching goal** follows methodologically the quantum-chemical bonding-descriptor maps (“treasure maps”) of Wuttig et al. for chalcogenides \[64\]: there, two descriptors (electron transfer and electron sharing) separate ionic, covalent, metallic and metavalent bonding and act as predictors of optical, thermoelectric and phase-change properties. COMET-Ox creates the analogue for redox-active complex oxides: a map spanned by covalency (charge-transfer energy, or experimentally the normalised O-K pre-edge intensity) versus the oxygen-vacancy formation energy, onto which the memristive figures of merit are charted as a landscape. Such a map would have the same dual function as the original: it *explains* (which bonding regime enables which switching behaviour?) and it *designs* (where does the next promising material lie?).

### 1.1.6  Feasibility and prior findings on the chosen material series

**All three envisaged series are documented as memristively switching at their end members or closest relatives.** For the ferrite series, the Sr-rich end member is excellently documented: epitaxial SrFeO<sub>2.5</sub>/SrFeO<sub>3-δ</sub> devices switch via the topotactic brownmillerite–perovskite transition with ON/OFF ratios around 10<sup>4</sup>, retention \> 10<sup>5</sup> s and endurance up to 10<sup>7</sup> cycles; the switching mode (area-type vs. localised) is tunable via the orientation of the vacancy channels, and the brownmillerite phase acts as a “pre-formed” state \[16, 17, 65, 66\]. LaFeO<sub>3</sub>, by contrast, has only been studied rudimentarily (polycrystalline, chemically deposited films \[67, 87\]) – consistent with its high vacancy formation energy. For the manganite series, besides the PCMO system \[4, E2\], La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3</sub> itself is documented as an active switching layer (multilevel switching \[68\], forming-free interface devices \[69, 88\], in-situ TEM evidence of vacancy-driven topotactic transitions \[19\]). For the cobaltite series, SrCoO<sub>x</sub> \[18, 20, 70–72\] and LaCoO<sub>x</sub> \[73\] have been demonstrated, including strain-controlled manipulation of switching \[74\].

**Systematic stoichiometry-dependent studies, on the other hand, are extremely rare – and precisely here lie the decisive prior findings.** The literature survey identifies only a handful of genuine composition series in the entire perovskite ReRAM literature \[84\]: Asanuma et al. measured Ti/Pr<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub> junctions across the full doping range and found a *maximum of the switching ratio at x ≈ 0.4* and a disappearance of switching for x \> 0.8 \[75\]; Lähteenlahti et al. found an optimum at x = 0.85 in Al/Gd<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub>/Au, correlated with minimal trap energy \[76, 85\]; for La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3</sub> a single three-point series exists (sputtered, x = 0.1/0.3/0.5) \[77\]; Mikheev et al. showed on Pt/SrTiO<sub>3</sub> that cation stoichiometry systematically controls Schottky barrier and retention \[78\]. For the ferrite series La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> (0 \< x \< 1) **not a single memristor study exists** – the closest neighbour is an electrochemical three-terminal study that controls the conductivity of La<sub>0.5</sub>Sr<sub>0.5</sub>FeO<sub>3-δ</sub> non-volatilely over more than four orders of magnitude via the oxygen stoichiometry \[79\], underscoring the feasibility of the concept; for La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3</sub> only a polycrystalline study with a small doping window exists \[80\]. None of these studies links the series to computed vacancy formation energies, covalency descriptors or spectroscopic observables. Viewed along the descriptor chain, the evidence is complementary rather than complete: for the ferrite series the covalency axis is canonical \[46\] and EV(x) quantitative \[31, 86\], but intermediate-composition devices are absent – though switching under inert Au/SrRuO3 stacks is proven at the Sr-rich end member \[16, 17\], which turns the series from a feasibility risk into an optimisation space; for the La1-xSrxMnO3 series the covalency axis is the calibration standard of the field \[46\], while EV is anchored only generically \[42–44\] and no switching at a noble-metal interface has been reported for any composition; and stoichiometry-controlled switching at a Pt interface has so far been shown only for the cation stoichiometry of SrTiO3 \[78\].

**First assessment derivable for the research question:** The few existing series consistently draw the picture of a *non-monotonic* dependence: with increasing acceptor doping (easier vacancy formation), forming and switching voltages decrease and the switching window initially grows – beyond an optimum, however, it collapses (metallic HRS, degraded retention through too-facile defect kinetics \[75, 78\]). At the same time, precisely the end members with the lowest vacancy formation energy (SrFeO<sub>x</sub>, SrCoO<sub>x</sub>) reach the highest ON/OFF ratios via the topotactic phase contrast \[17, 20\]. These prior findings directly support hypotheses H1 and H2 and simultaneously make clear why a descriptor-based mapping (rather than isolated single studies) is required: the landscape is structured, but so far uncharted.

## 1.2  Preliminary work of the applicant

The applicant has worked since 2020 at the Peter Grünberg Institute (PGI-7, Electronic Materials) of Forschungszentrum Jülich in the group of Prof. Regina Dittmann – one of the internationally leading centres for redox-based resistive switching \[2, 3, 8–12\] – and contributes exactly the methodological combination on which COMET-Ox builds: PLD synthesis of perovskites, memristive device processing and statistically robust electrical characterisation.

**Doctorate (RWTH Aachen / FZ Jülich, 2020–2026):** Within the dissertation “BEOL-Compatible Area-Dependent Memristive Devices from Wafer-Scale Pulsed Laser Deposited Amorphous Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub>”, the applicant developed a large-area PLD process (process control via XRR and ICP-MS) and established the complete process chain of memristive devices: deposition (PLD, sputtering, e-beam evaporation), optical and electron-beam lithography, ion-beam etching (RIBE) and wire bonding. Electrical characterisation (Keithley 2600/4200; DC and pulsed) systematically covered device-to-device and cycle-to-cycle variability, endurance, retention, read-out transients and switching kinetics – exactly the measurement protocol envisaged in WP3. Materials analytics (XRD/XRR, in-situ XRD, AFM, SEM, TEM-EDX, pair distribution function, XPS, sputter XPS, SIMS, Raman, impedance spectroscopy) as well as band-alignment calculations and COMSOL field simulations were performed or coordinated independently.

**Immediate project relevance:** With Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> (PCMO), the applicant has already worked for years on an A-site-substituted, mixed-valent manganite memristor – the very material class and doping principle that COMET-Ox turns into the systematic control variable (Section 2.3, series 2). The applicant’s first-author review of PCMO-based memristive heterostructures (Chemical Reviews 2025, \[E2\]) documents comprehensive command of the mechanistic debate; the work on area-dependent (non-filamentary) switching \[E1, E3\] demonstrates experience with precisely the switching mode best suited for descriptor-based correlation, since it scales with the active area and is statistically robust to evaluate.

**Postdoc (PGI-7, 07/2025–\[2027\]):** Investigation of optical phase shifters based on memristive heterostructures within the EU project NeuroSys, including device integration with optical waveguides and a patent application – evidence of the ability to transfer memristive materials development into new application contexts. Supervision of several master’s students and long-standing teaching (laboratory course supervision, RWTH Aachen) document the supervision experience required for leading a research group.

**Current Feodor Lynen fellowship (Stanford University / SLAC, group of Prof. W. C. Chueh, since \[2027\]) – the direct precursor of COMET-Ox:** Within the fellowship project “Covalency as an experimental descriptor of memristive switching: the La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> model series”, the applicant has grown the first epitaxial LSFO composition series – spanning the largest documented E<sub>V</sub> range of any perovskite family \[31\] – and established the O-K pre-edge covalency scale across it at the Stanford Synchrotron Radiation Lightsource (SSRL) \[preliminary results; manuscript in preparation, E4 – insert headline result and status at submission time\]. This closes the one former gap in the applicant’s methodological profile: quantitative synchrotron XAS and defect thermodynamics, acquired in one of the world-leading groups for oxide defect chemistry. COMET-Ox scales this personally established and de-risked approach from one pilot series to the full three-family descriptor map – with proprietary pilot data, proven measurement protocols, and an active transatlantic collaboration as starting capital.

**Scientific independence:** The descriptor programme was conceived by the applicant, developed outside his doctoral environment during the Feodor Lynen fellowship, and combines competences (device statistics from Jülich, defect spectroscopy from Stanford) that neither environment holds in this combination. PGI-7’s pioneering spectromicroscopic operando methodology \[9, 10, 53\] remains available through collaboration (Section 5.2), while the thematic demarcation from both former groups (descriptor physics of epitaxial composition series rather than BEOL integration or catalysis) defines the independent profile of the junior research group.

**Project-relevant publications of the applicant:**

\[E1\] M. Buczek et al., Amorphous, Highly Conductive Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> for Area-Dependent Resistive Switching Devices. Advanced Electronic Materials (2026, accepted).

\[E2\] M. Buczek, Z. Moos, A. Gutsche, S. Menzel, R. Dittmann, Pr<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub>-Based Memristive Heterostructures: Basic Mechanisms and Applications. Chemical Reviews 125, 6156–6202 (2025).

\[E3\] M. Buczek et al., Large Area Pulsed Laser Deposition of Memristive Pr<sub>0.7</sub>Ca<sub>0.3</sub>MnO<sub>3</sub> Heterostructures for Neuromorphic Computing. Thin Solid Films (2024).

\[E4\] M. Buczek, \[co-authors\], W. C. Chueh, \[working title: An experimental covalency scale for memristive La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub>\]. Manuscript in preparation (Feodor Lynen fellowship; update status at submission time).

\[Complete author lists and bibliographic details before submission; add patent application (NeuroSys) as \[E5\] if applicable.\]

# 2  Objectives and Work Programme

## 2.1  Anticipated total duration

Six years (two funding periods of three years each), starting \[insert quarter/year\]. The interim evaluation after the third year coincides with milestone M3 (completed descriptor quantification of the first two material series).

## 2.2  Objectives

**Guiding question:** How strongly, and in which functional form, does the metal–oxygen covalency – via the oxygen-vacancy formation energy E<sub>V</sub> it controls – determine the figures of merit of memristive switching in complex oxides, in particular the ON/OFF ratio?

Three testable hypotheses follow:

- **H1 (descriptor hypothesis):** Within a structurally homogeneous perovskite series, the ON/OFF ratio of VCM devices scales systematically with the covalency tuned via the A-site stoichiometry; the dependence is described by E<sub>V</sub> (or the O-2p band centre) as descriptor.

- **H2 (optimum hypothesis):** A covalency optimum (“Goldilocks zone”) exists: at too high E<sub>V</sub>, forming voltages are prohibitive and switching windows small; at too low E<sub>V</sub>, retention and state stability degrade because vacancies form and relax spontaneously. Maximum usable switching windows lie at intermediate covalency.

- **H3 (spectroscopy hypothesis):** The normalised O-K pre-edge intensity from XAS is a sufficiently quantitative *experimental* covalency descriptor, so that the treasure map can be spanned from purely experimental quantities without material-specific DFT calculations (literature DFT values serve for validation).

**The overarching goal** is the construction and validation of a bonding-descriptor “treasure map” for memristive oxides in analogy to Wuttig et al. \[64\]: axes covalency × E<sub>V</sub>, charted property the ON/OFF ratio (with retention and switching voltage as further map layers). The map is finally tested prospectively: an oxide not contained in the dataset is selected on the basis of the map, synthesised, and its switching behaviour predicted (“blind validation”, M6).

## 2.3  Materials strategy: covalency as an isolated control variable

The core of the experimental design are mixed-valent perovskite series with systematically varied A-site stoichiometry. The substitution La<sup>3+</sup> → Sr<sup>2+</sup> dopes holes with substantial O-2p character, reduces the charge-transfer energy, raises the O-2p band centre and lowers E<sub>V</sub> continuously – with unchanged perovskite structure, identical device geometry and identical electrodes \[22, 31, 46\]. Covalency is thereby decoupled from all competing influences (crystal structure, interface chemistry, processing) – the decisive difference from previous material comparisons across publication and system boundaries.

- **Series 1 – La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> (x = 0 … 1, ≥ 6 compositions):** Primary system. Largest documented E<sub>V</sub> span (approx. 4 eV → \< 1 eV \[31\]), crossover into the negative charge-transfer regime at the SrFeO<sub>3-δ</sub> end member including the topotactic brownmillerite transition \[16, 17\] – the series thus links classical VCM and phase-change switching in one system.

- **Series 2 – La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3-δ</sub> (x = 0 … 0.5):** Reference system with robust, well-documented VCM behaviour (PCMO kinship \[4–6, 19\]) and a flatter covalency span; XAS reference data are available from the literature \[46\].

- **Series 3 – La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> or B-site series La(Fe<sub>1-y</sub>Co<sub>y</sub>)O<sub>3</sub> (second project phase):** Densification and extension of the map; the cross-comparison Fe/Mn/Co separates covalency-driven from B-cation-specific effects (spin state, bandwidth) and tests the transferability of the descriptor.

As a second, independent handle on the same target quantity E<sub>V</sub>, epitaxial strain via substrate choice (SrTiO<sub>3</sub>, LSAT, NdGaO<sub>3</sub>) is employed \[60–62\]: it allows E<sub>V</sub> to be shifted at *constant chemistry* and thus provides an internal consistency test of the descriptor relation (orthogonality check: chemical vs. mechanical access to E<sub>V</sub>).

## 2.4  Work programme

### WP1 – PLD synthesis of epitaxial perovskite series (doctoral researcher 1; years 1–5)

Target preparation; RHEED-controlled, layer-precise growth \[55–58\] on uniformly terminated substrates; control of cation stoichiometry via fluence/pressure windows \[59\] (verification: XPS, XRD, RBS on calibration samples where required); adjustment of oxygen stoichiometry via p(O<sub>2</sub>) during growth and cool-down; structural characterisation (XRD/reciprocal space maps for the strain state, AFM for terrace morphology); basic electrical characterisation (transport, Hall). Series 1 starts with a decisive head start: the growth windows and the XAS covalency scale of the La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> pilot series are already established from the applicant’s Feodor Lynen project \[E4\]; WP1 reproduces the series in the group’s own infrastructure and extends it. *Deliverable:* a validated “materials data sheet” per composition as input for WP2–WP5. In years 4–5: series 3 and strain-varied series of selected compositions.

### WP2 – Device integration (doctoral researcher 2, supported by group leader; years 1–5)

Establishment of a *constant device platform* that remains unchanged across all series: epitaxial bottom electrode (Nb:SrTiO<sub>3</sub> or SrRuO<sub>3</sub>), active layer (20–50 nm), inert top electrodes (Pt/Au), and graphene top electrodes for operando measurements following \[10\]. Photolithographically defined cross-point and pad structures (5–100 µm) with ≥ 30 nominally identical cells per composition for robust statistics. The platform is validated in year 1 against the literature reference Fe:SrTiO<sub>3</sub> \[8\] and subsequently frozen (design freeze, M2) to guarantee comparability over the entire project duration.

### WP3 – Memristive characterisation (doctoral researcher 2; years 2–6)

Systematic measurement of all compositions under an identical protocol: quasistatic I–V characteristics (forming requirement, switching polarity, ON/OFF ratio at defined read-out voltage); pulsed measurements (10 ns – 1 s) to determine the switching kinetics and – via the analysis following \[11, 12\] – the effective activation energies of V<sub>O</sub> migration; retention (temperature-accelerated, extrapolation via Arrhenius analysis → state stability as a function of covalency, test of H2); endurance (≥ 10<sup>6</sup> cycles); multilevel capability and linearity of conductance modulation (neuromorphic relevance \[5, 20\]). Temperature-dependent measurements (80–400 K) at the requested cryogenic probe station separate electronic from ionic contributions.

### WP4 – X-ray absorption spectroscopy (doctoral researcher 1, group leader; years 2–6)

XAS at the O-K and TM-L<sub>2,3</sub> edges of all compositions (total electron yield and fluorescence): quantification of covalency via the normalised pre-edge intensity following \[40, 46, 47\]; determination of the TM valence and from it the V<sub>O</sub> concentration of the as-grown state; extraction of the charge-transfer energy in collaboration with \[insert theory/spectroscopy partner\] following \[38\]. Beamtime will be applied for biannually at BESSY II (EMIL, SPEEM), PETRA III (P04) and, where appropriate, ESRF (ID32); a UHV transfer system (requested) secures surface-sensitive measurements on well-defined films. In the second project phase: operando spectromicroscopy (X-PEEM/STXM) on switched cells with graphene electrodes following \[9, 10, 53\], verifying that the descriptor-tuned differences indeed rest on different V<sub>O</sub> dynamics.

### WP5 – Correlation, modelling and the treasure map (doctoral researcher 3, group leader; years 3–6)

Consolidation of all data streams in an open, versioned project database (one record per cell, FAIR principles). Statistical correlation analysis covalency ↔ E<sub>V</sub> ↔ switching metrics; comparison with published DFT values and high-throughput datasets \[31, 42–44\]; regression and ML models (Gaussian processes/random forest analogous to \[43, 44\]) for interpolating the map. Construction of the treasure map (axes: normalised O-K pre-edge intensity or Δ; E<sub>V</sub> from literature DFT and own calibration; colour layers: ON/OFF, retention, forming voltage). Finally, blind validation (M6): selection of a candidate oxide outside the training set (e.g. from the nickelate or double-perovskite family), quantitative prediction, synthesis and test.

## 2.5  Timeline and milestones

| **Work package**                | **Y1** | **Y2** | **Y3** | **Y4** | **Y5** | **Y6** |
|---------------------------------|:------:|:------:|:------:|:------:|:------:|:------:|
| WP1 PLD synthesis               |   ■    |   ■    |   ■    |   ■    |   ■    |        |
| WP2 Device integration          |   ■    |   ■    |   ■    |   ■    |   ■    |        |
| WP3 Memristive characterisation |        |   ■    |   ■    |   ■    |   ■    |   ■    |
| WP4 XAS / operando              |        |   ■    |   ■    |   ■    |   ■    |   ■    |
| WP5 Correlation / treasure map  |        |        |   ■    |   ■    |   ■    |   ■    |

| **MS** | **Milestone** | **Due** |
|----|----|----|
| M1 | Series 1 and 2 grown epitaxially and structurally validated (≥ 5 compositions each) | end Y1 |
| M2 | Device platform validated on Fe:SrTiO<sub>3</sub>, design freeze; first switching demonstrated in series 1 | mid Y2 |
| M3 | XAS covalency scale complete for series 1+2; first correlation ON/OFF vs. covalency (interim evaluation) | end Y3 |
| M4 | Quantitative descriptor test of H1/H2 published; decision on series 3 vs. B-site series | end Y4 |
| M5 | Operando campaign completed; series 3 integrated into the map | end Y5 |
| M6 | Treasure map published and validated by blind prediction; database released | end Y6 |

## 2.6  Handling of research data

All measurement and metadata (growth protocols, characteristics, spectra) will be recorded from the project start in an electronic laboratory notebook with standardised metadata schemata and handled according to the FAIR principles. Curated datasets will be published at the latest with the respective publication in a disciplinary repository (e.g. Zenodo/NOMAD) under an open licence; the complete descriptor database is itself a central deliverable of the project (M6). The regulations of the host institution and the DFG guidelines on the handling of research data will be observed.

## 2.7  Relevance and exploitation perspective

Scientifically, COMET-Ox closes the gap between two hitherto separate communities – defect chemistry/electrocatalysis and redox-based nanoelectronics – and establishes, with the treasure map, a transferable design tool. Technologically, the project addresses the central bottleneck of analogue neuromorphic hardware: reproducible, low-energy multilevel memories with a tunable switching window \[5, 20\]. The junior research group built up within the project moreover anchors the combination PLD synthesis / device physics / synchrotron spectroscopy as an independent profile at the host institution.

# 3  Bibliography

\[1\] R. Waser, M. Aono, Nanoionics-based resistive switching memories. Nature Materials 6, 833–840 (2007).

\[2\] R. Waser, R. Dittmann, G. Staikov, K. Szot, Redox-Based Resistive Switching Memories – Nanoionic Mechanisms, Prospects, and Challenges. Advanced Materials 21, 2632–2663 (2009).

\[3\] R. Dittmann, S. Menzel, R. Waser, Nanoionic memristive phenomena in metal oxides: the valence change mechanism. Advances in Physics 70, 155–349 (2021).

\[4\] A. Sawa, Resistive switching in transition metal oxides. Materials Today 11(6), 28–36 (2008).

\[5\] J. J. Yang, D. B. Strukov, D. R. Stewart, Memristive devices for computing. Nature Nanotechnology 8, 13–24 (2013).

\[6\] Š. Bagdzevičius, K. Maas, M. Boudard, M. Burriel, Interface-type resistive switching in perovskite materials. Journal of Electroceramics 39, 157–184 (2017).

\[7\] K. Szot, W. Speier, G. Bihlmayer, R. Waser, Switching the electrical resistance of individual dislocations in single-crystalline SrTiO<sub>3</sub>. Nature Materials 5, 312–320 (2006).

\[8\] R. Muenstermann, T. Menke, R. Dittmann, R. Waser, Coexistence of Filamentary and Homogeneous Resistive Switching in Fe-Doped SrTiO<sub>3</sub> Thin-Film Memristive Devices. Advanced Materials 22, 4819–4822 (2010).

\[9\] C. Baeumer et al., Spectromicroscopic insights for rational design of redox-based memristive devices. Nature Communications 6, 8610 (2015).

\[10\] C. Baeumer et al., Quantifying redox-induced Schottky barrier variations in memristive devices via in operando spectromicroscopy with graphene electrodes. Nature Communications 7, 12398 (2016).

\[11\] S. Menzel, M. Waters, A. Marchewka, U. Böttger, R. Dittmann, R. Waser, Origin of the Ultra-nonlinear Switching Kinetics in Oxide-Based Resistive Switches. Advanced Functional Materials 21, 4487–4492 (2011).

\[12\] S. Menzel, U. Böttger, M. Wimmer, M. Salinga, Physics of the Switching Kinetics in Resistive Memories. Advanced Functional Materials 25, 6306–6325 (2015).

\[13\] M.-J. Lee et al., A fast, high-endurance and scalable non-volatile memory device made from asymmetric Ta<sub>2</sub>O<sub>5-x</sub>/TaO<sub>2-x</sub> bilayer structures. Nature Materials 10, 625–630 (2011).

\[14\] R. Schmitt, J. Spring, R. Korobko, J. L. M. Rupp, Design of Oxygen Vacancy Configuration for Memristive Systems. ACS Nano 11, 8881–8891 (2017).

\[15\] H. Jiang, D. A. Stewart, Using Dopants to Tune Oxygen Vacancy Formation in Transition Metal Oxide Resistive Memory. ACS Applied Materials & Interfaces 9, 16296–16304 (2017).

\[16\] V. R. Nallagatla et al., Topotactic Phase Transition Driving Memristive Behavior (SrFeO<sub>2.5</sub>/SrFeO<sub>3</sub>). Advanced Materials 31, 1903391 (2019).

\[17\] J. Tian et al., Nanoscale Topotactic Phase Transformation in SrFeO<sub>x</sub> Epitaxial Thin Films for High-Density Resistive Switching Memory. Advanced Materials 31, 1903679 (2019).

\[18\] N. Lu et al., Electric-field control of tri-state phase transformation with a selective dual-ion switch. Nature 546, 124–128 (2017).

\[19\] L. Yao, S. Inkinen, S. van Dijken, Direct observation of oxygen vacancy-driven structural and resistive phase transitions in La<sub>2/3</sub>Sr<sub>1/3</sub>MnO<sub>3</sub>. Nature Communications 8, 14544 (2017).

\[20\] X. Mou et al., Analog memristive synapse based on topotactic phase transition for high-performance neuromorphic computing and neural network pruning. Science Advances 7, eabh0648 (2021).

\[21\] J. Zaanen, G. A. Sawatzky, J. W. Allen, Band gaps and electronic structure of transition-metal compounds. Physical Review Letters 55, 418–421 (1985).

\[22\] T. Arima, Y. Tokura, J. B. Torrance, Variation of optical gaps in perovskite-type 3d transition-metal oxides. Physical Review B 48, 17006–17009 (1993).

\[23\] Y.-L. Lee, J. Kleis, J. Rossmeisl, D. Morgan, Ab initio energetics of LaBO<sub>3</sub>(001) (B = Mn, Fe, Co, and Ni) for solid oxide fuel cell cathodes. Physical Review B 80, 224101 (2009).

\[24\] Y.-L. Lee, J. Kleis, J. Rossmeisl, Y. Shao-Horn, D. Morgan, Prediction of solid oxide fuel cell cathode activity with first-principles descriptors. Energy & Environmental Science 4, 3966–3970 (2011).

\[25\] R. Jacobs, T. Mayeshiba, J. Booske, D. Morgan, Material Discovery and Design Principles for Stable, High Activity Perovskite Cathodes for Solid Oxide Fuel Cells. Advanced Energy Materials 8, 1702708 (2018).

\[26\] R. Jacobs, J. Hwang, Y. Shao-Horn, D. Morgan, Assessing Correlations of Perovskite Catalytic Performance with Electronic Structure Descriptors. Chemistry of Materials 31, 785–797 (2019).

\[27\] A. M. Deml, V. Stevanović, C. L. Muhich, C. B. Musgrave, R. O’Hayre, Oxide enthalpy of formation and band gap energy as accurate descriptors of oxygen vacancy formation energetics. Energy & Environmental Science 7, 1996–2004 (2014).

\[28\] A. M. Deml, A. M. Holder, R. P. O’Hayre, C. B. Musgrave, V. Stevanović, Intrinsic Material Properties Dictating Oxygen Vacancy Formation Energetics in Metal Oxides. Journal of Physical Chemistry Letters 6, 1948–1953 (2015).

\[29\] R. B. Wexler, G. Sai Gautam, E. B. Stechel, E. A. Carter, Factors Governing Oxygen Vacancy Formation in Oxide Perovskites. Journal of the American Chemical Society 143, 13212–13227 (2021).

\[30\] M. T. Curnan, J. R. Kitchin, Effects of Concentration, Crystal Structure, Magnetism, and Electronic Structure Method on First-Principles Oxygen Vacancy Formation Energy Trends in Perovskites. Journal of Physical Chemistry C 118, 28776–28790 (2014).

\[31\] A. M. Ritzmann, A. B. Muñoz-García, M. Pavone, J. A. Keith, E. A. Carter, Ab Initio DFT+U Analysis of Oxygen Vacancy Formation and Migration in La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3-δ</sub> (x = 0, 0.25, 0.50). Chemistry of Materials 25, 3011–3019 (2013).

\[32\] R. Merkle, Y. A. Mastrikov, E. A. Kotomin, M. M. Kuklja, J. Maier, First Principles Calculations of Oxygen Vacancy Formation and Migration in Ba<sub>1-x</sub>Sr<sub>x</sub>Co<sub>1-y</sub>Fe<sub>y</sub>O<sub>3-δ</sub> Perovskites. Journal of the Electrochemical Society 159, B219–B226 (2012).

\[33\] Yu. A. Mastrikov, R. Merkle, E. A. Kotomin, M. M. Kuklja, J. Maier, Formation and migration of oxygen vacancies in La<sub>1-x</sub>Sr<sub>x</sub>Co<sub>1-y</sub>Fe<sub>y</sub>O<sub>3-δ</sub> perovskites. Physical Chemistry Chemical Physics 15, 911–918 (2013).

\[34\] J. Suntivich, K. J. May, H. A. Gasteiger, J. B. Goodenough, Y. Shao-Horn, A Perovskite Oxide Optimized for Oxygen Evolution Catalysis from Molecular Orbital Principles. Science 334, 1383–1385 (2011).

\[35\] A. Grimaud et al., Double perovskites as a family of highly active catalysts for oxygen evolution in alkaline solution. Nature Communications 4, 2439 (2013).

\[36\] A. Grimaud et al., Activating lattice oxygen redox reactions in metal oxides to catalyse oxygen evolution. Nature Chemistry 9, 457–465 (2017).

\[37\] W. T. Hong, M. Risch, K. A. Stoerzinger, A. Grimaud, J. Suntivich, Y. Shao-Horn, Toward the rational design of non-precious transition metal oxides for oxygen electrocatalysis. Energy & Environmental Science 8, 1404–1427 (2015).

\[38\] W. T. Hong et al., Charge-transfer-energy-dependent oxygen evolution reaction mechanisms for perovskite oxides. Energy & Environmental Science 10, 2190–2200 (2017).

\[39\] J. T. Mefford et al., Water electrolysis on La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> perovskite electrocatalysts. Nature Communications 7, 11053 (2016).

\[40\] J. Suntivich et al., Estimating Hybridization of Transition Metal and Oxygen States in Perovskites from O K-edge X-ray Absorption Spectroscopy. Journal of Physical Chemistry C 118, 1856–1863 (2014).

\[41\] N. Tsvetkov, Q. Lu, L. Sun, E. J. Crumlin, B. Yildiz, Improved chemical and electrochemical stability of perovskite oxides with less reducible cations at the surface. Nature Materials 15, 1010–1016 (2016).

\[42\] A. A. Emery, C. Wolverton, High-throughput DFT calculations of formation energy, stability and oxygen vacancy formation energy of ABO<sub>3</sub> perovskites. Scientific Data 4, 170153 (2017).

\[43\] Y. Kumagai, N. Tsunoda, A. Takahashi, F. Oba, Insights into oxygen vacancies from high-throughput first-principles calculations. Physical Review Materials 5, 123803 (2021).

\[44\] B. Baldassarri et al., Oxygen Vacancy Formation Energy in Metal Oxides: High-Throughput Computational Studies and Machine-Learning Predictions. Chemistry of Materials 35, 10619–10634 (2023).

\[45\] F. M. F. de Groot et al., Oxygen 1s x-ray-absorption edges of transition-metal oxides. Physical Review B 40, 5715–5723 (1989).

\[46\] M. Abbate et al., Controlled-valence properties of La<sub>1-x</sub>Sr<sub>x</sub>FeO<sub>3</sub> and La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3</sub> studied by soft-x-ray absorption spectroscopy. Physical Review B 46, 4511–4519 (1992).

\[47\] F. Frati, M. O. J. Y. Hunault, F. M. F. de Groot, Oxygen K-edge X-ray Absorption Spectra. Chemical Reviews 120, 4056–4110 (2020).

\[48\] D. N. Mueller, M. L. Machala, H. Bluhm, W. C. Chueh, Redox activity of surface oxygen anions in oxygen-deficient perovskite oxides during electrochemical reactions. Nature Communications 6, 6097 (2015).

\[49\] S. Kumar et al., In-operando synchronous time-multiplexed O K-edge x-ray absorption spectromicroscopy of functioning tantalum oxide memristors. Journal of Applied Physics 118, 034502 (2015).

\[50\] S. Kumar et al., Direct Observation of Localized Radial Oxygen Migration in Functioning Tantalum Oxide Memristors. Advanced Materials 28, 2772–2776 (2016).

\[51\] H. Liu et al., Quantitative Observation of Threshold Defect Behavior in Memristive Devices with Operando X-ray Microscopy. ACS Nano 12, 4938–4945 (2018).

\[52\] M. Sowinska et al., Hard x-ray photoelectron spectroscopy study of the electroforming in Ti/HfO<sub>2</sub>-based resistive switching structures. Applied Physics Letters 100, 233509 (2012).

\[53\] D. Gogoi, R. Dittmann et al., Resistive Switching Systems: A Spectromicroscopy Approach. Physica Status Solidi A 221, 2300500 (2024).

\[54\] T. Khuu et al., Operando Spectroscopic Investigation of the Valence Change Mechanism in La<sub>2</sub>NiO<sub>4+δ</sub>-Based Memristive Devices. Advanced Electronic Materials 11, 2400313 (2025).

\[55\] G. J. H. M. Rijnders, G. Koster, D. H. A. Blank, H. Rogalla, In situ monitoring during pulsed laser deposition of complex oxides using reflection high energy electron diffraction under high oxygen pressure. Applied Physics Letters 70, 1888–1890 (1997).

\[56\] G. Koster, B. L. Kropman, G. J. H. M. Rijnders, D. H. A. Blank, H. Rogalla, Quasi-ideal strontium titanate crystal surfaces through formation of strontium hydroxide. Applied Physics Letters 73, 2920–2922 (1998).

\[57\] G. Koster, G. J. H. M. Rijnders, D. H. A. Blank, H. Rogalla, Imposed layer-by-layer growth by pulsed laser interval deposition. Applied Physics Letters 74, 3729–3731 (1999).

\[58\] H. M. Christen, G. Eres, Recent advances in pulsed-laser deposition of complex oxides. Journal of Physics: Condensed Matter 20, 264005 (2008).

\[59\] S. Wicklein et al., Pulsed laser ablation of complex oxides: The role of congruent ablation and preferential scattering for the film stoichiometry. Applied Physics Letters 101, 131601 (2012).

\[60\] U. Aschauer, R. Pfenninger, S. M. Selbach, T. Grande, N. A. Spaldin, Strain-controlled oxygen vacancy formation and ordering in CaMnO<sub>3</sub>. Physical Review B 88, 054111 (2013).

\[61\] B. Yildiz, “Stretching” the energy landscape of oxides – Effects on electrocatalysis and diffusion. MRS Bulletin 39, 147–156 (2014).

\[62\] M. Kubicek et al., Tensile Lattice Strain Accelerates Oxygen Surface Exchange and Diffusion in La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3-δ</sub> Thin Films. ACS Nano 7, 3276–3286 (2013).

\[63\] H. Jeen et al., Reversible redox reactions in an epitaxially stabilized SrCoO<sub>x</sub> oxygen sponge. Nature Materials 12, 1057–1063 (2013).

\[64\] M. Wuttig et al., Revisiting the Nature of Chemical Bonding in Chalcogenides to Explain and Design their Properties. Advanced Materials 35, 2208485 (2023).

\[65\] V. R. Nallagatla, J. Kim, K. Lee, S. C. Chae, C. S. Hwang, C. U. Jung, Complementary Resistive Switching and Synaptic-Like Memory Behavior in an Epitaxial SrFeO<sub>2.5</sub> Thin Film through Oriented Oxygen-Vacancy Channels. ACS Applied Materials & Interfaces 12, 41740–41748 (2020).

\[66\] J. Rao, Z. Fan et al., An electroforming-free, analog interface-type memristor based on a SrFeO<sub>x</sub> epitaxial heterojunction for neuromorphic computing. Materials Today Physics 18, 100392 (2021).

\[67\] R. K. Aljurays, A. Loucif, A. M. Albadri, Synthesis of LaXO<sub>3</sub> (X = Fe, Mn, Cr, Ni) Thin Films Using a Simple Spin Coating Set-Up for Resistive Switching Memory Devices. Electronics 12, 4141 (2023).

\[68\] C. Moreno, C. Munuera, S. Valencia, F. Kronast, X. Obradors, C. Ocal, Reversible resistive switching and multilevel recording in La<sub>0.7</sub>Sr<sub>0.3</sub>MnO<sub>3</sub> thin films for low cost nonvolatile memories. Nano Letters 10, 3828–3835 (2010).

\[69\] M. Liu et al., Nanoscale-thick La<sub>0.7</sub>Sr<sub>0.3</sub>MnO<sub>3</sub> films for memristor devices with negative differential resistance-coupled resistive switching behavior. ACS Applied Nano Materials 7, 6139–6147 (2024).

\[70\] O. T. Tambunan et al., Resistance switching in epitaxial SrCoO<sub>x</sub> thin films. Applied Physics Letters 105, 063507 (2014).

\[71\] S. K. Acharya et al., Epitaxial Brownmillerite Oxide Thin Films for Reliable Switching Memory. ACS Applied Materials & Interfaces 8, 7902–7911 (2016).

\[72\] H.-Y. Lo et al., Observing topotactic phase transformation and resistive switching behaviors in low power SrCoO<sub>x</sub> memristor. Nano Energy 72, 104683 (2020).

\[73\] Y.-J. Chen, H.-Y. Lo, C.-C. Chiu, C.-H. Wang, J.-C. Yang, J.-Y. Chen, W.-W. Wu, Atomic-Scale Phase Transformation in Perovskite LaCoO<sub>x</sub> Resistive Switching Memristive Devices. Small Structures 5, 2400019 (2024).

\[74\] X. Xiang et al., Manipulating the Resistive Switching in Epitaxial SrCoO<sub>2.5</sub> Thin-Film-Based Memristors by Strain Engineering. ACS Applied Electronic Materials 4, 2729–2738 (2022).

\[75\] S. Asanuma, H. Akoh, H. Yamada, A. Sawa, Relationship between resistive switching characteristics and band diagrams of Ti/Pr<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub> junctions. Physical Review B 80, 235113 (2009).

\[76\] V. Lähteenlahti, A. Schulman, A. Beiranvand, H. Huhtinen, P. Paturi, Electron Doping Effect in the Resistive Switching Properties of Al/Gd<sub>1-x</sub>Ca<sub>x</sub>MnO<sub>3</sub>/Au Memristor Devices. ACS Applied Materials & Interfaces 13, 18365–18371 (2021).

\[77\] S. G. Choi, H.-S. Lee, H. Choi, S.-W. Chung, H.-H. Park, The effect of Sr concentration on resistive switching properties of La<sub>1-x</sub>Sr<sub>x</sub>MnO<sub>3</sub> films. Thin Solid Films 529, 352–355 (2013).

\[78\] E. Mikheev, J. Hwang, A. P. Kajdos, A. J. Hauser, S. Stemmer, Tailoring resistive switching in Pt/SrTiO<sub>3</sub> junctions by stoichiometry control. Scientific Reports 5, 11079 (2015).

\[79\] P. Nizet et al., Analog control of La<sub>0.5</sub>Sr<sub>0.5</sub>FeO<sub>3-δ</sub> electrical properties through oxygen deficiency induced magnetic transition. Applied Physics Reviews 11, 041426 (2024).

\[80\] Z. Viskadourakis, C. N. Mihailescu, G. Kenanakis, Spray-pyrolysis deposited La<sub>1-x</sub>Sr<sub>x</sub>CoO<sub>3</sub> thin films for potential non-volatile memory applications. Applied Physics A 126, 80 (2020).

\[81\] A. Sarantopoulos, K. Lange, F. Rivadulla, S. Menzel, R. Dittmann, Resistive Switching Acceleration Induced by Thermal Confinement. Advanced Electronic Materials 11, 2400555 (2025).

\[82\] M. Mladenović, M. Kaniselvan, C. Weilenmann, A. Emboras, M. Luisier, Termination-Dependent Resistive Switching in SrTiO3 Valence Change Memory Cells. ACS Applied Electronic Materials 7, 2839–2847 (2025).

\[83\] K.-J. Lee, C.-H. Wu, C.-J. Lee, D.-W. Chou, N.-F. Wang, Y.-H. Wang, Reset-Voltage Controlled Resistance-State and Applications of Forming-Free Fe-Doped SrTiO3 Thin-Film Memristor. Materials 17, 5021 (2024).

\[84\] A. Schulman, H. Huhtinen, P. Paturi, Manganite memristive devices: recent progress and emerging opportunities. Journal of Physics D: Applied Physics 57, 422001 (2024).

\[85\] A. Antola, J. Laaksonen, H. Huhtinen, I. Angervo, S. Granroth, A. Schulman, P. Laukkanen, P. Paturi, Area-Dependent Resistive Switching and Interfacial Dynamics in GCMO-Based Memristors. ACS Applied Electronic Materials 7, 4242–4250 (2025).

\[86\] J. A. Santana, J. T. Krogel, P. R. C. Kent, F. A. Reboredo, Diffusion quantum Monte Carlo calculations of SrFeO3 and LaFeO3. The Journal of Chemical Physics 147, 034701 (2017).

\[87\] C. Song, H. Luo, J. Xu, Y. Song, Q. Hu, Density functional theory study on conduction mechanisms in LaFeO3 nanofibers for resistive random access memory. Ionics 32, 2427–2437 (2026).

\[88\] S. Kunwar et al., Reconfigurable Resistive Switching in VO2/La0.7Sr0.3MnO3/Al2O3 (0001) Memristive Devices for Neuromorphic Computing. ACS Applied Materials & Interfaces 16, 19103–19111 (2024).

# 4  Requested Modules and Funds

The personnel funds are based on the DFG personnel rates for 2026 (form 60.12 – 01/26). Doctoral positions are budgeted at 75 % of a full-time position in line with standard practice in physics (100 % rate: € 81,600/year → € 61,200/year).

## 4.1  Emmy Noether group leader module and basic personnel module

| **Position** | **FTE** | **Duration** | **Rate (€/year)** | **Total (€)** |
|----|----|----|---:|---:|
| Emmy Noether group leader (E14/5–E15/4) | 100 % | 72 months | 102,300 | 613,800 |
| Doctoral researcher 1 (WP1, WP4: synthesis & XAS) | 75 % | 48 months (Y1–Y4) | 61,200 | 244,800 |
| Doctoral researcher 2 (WP2, WP3: devices & switching) | 75 % | 48 months (Y1–Y4) | 61,200 | 244,800 |
| Doctoral researcher 3 (WP5 + series 3: map & 2nd generation) | 75 % | 48 months (Y3–Y6) | 61,200 | 244,800 |
| Student assistant (measurement routines, data curation) | 40 h/month | 72 months | 6,000 | 36,000 |
| **Subtotal personnel** |  |  |  | **1,384,200** |

The staggering (doctoral researcher 3 from year 3) follows the work programme: WP5 requires the data basis from WP1–WP4; at the same time, the overlap Y3–Y4 secures knowledge transfer within the group and continuity across the interim evaluation.

## 4.2  Consumables

| **Item (over 6 years)** | **Total (€)** |
|----|---:|
| PLD targets (approx. 25 compositions at € 2,500 each, incl. replacements) | 62,500 |
| Single-crystal substrates (SrTiO<sub>3</sub>, Nb:SrTiO<sub>3</sub>, LSAT, NdGaO<sub>3</sub>; approx. 900 pieces) | 27,500 |
| Process gases, chemicals, lithography/cleanroom consumables, bonding wire, small parts | 30,000 |
| **Subtotal consumables** | **120,000** |

## 4.3  Instrumentation (investments \> € 10,000)

| **Instrument** | **Total (€)** |
|----|---:|
| Cryogenic/vacuum probe station (80–400 K) for temperature-dependent device characterisation | 80,000 |
| Measurement electronics: 2 source-measure units, pulse generator (ns range), oscilloscope, switch matrix | 45,000 |
| UHV transfer system (suitcase + docking modules) for contamination-free sample transfer PLD → synchrotron | 30,000 |
| **Subtotal instrumentation** | **155,000** |

The PLD system with high-pressure RHEED, X-ray diffractometry, cleanroom lithography and AFM are provided by the host institution as basic equipment \[attach confirmation of the host institution\]. Synchrotron beamtime is free of charge via the peer-reviewed allocation procedures of the facilities (BESSY II, PETRA III, ESRF); only the associated travel funds are requested.

## 4.4  Travel, publication costs, workshop

| **Item (over 6 years)** | **Total (€)** |
|----|---:|
| Conferences (2 international + 2 national per year for the group) | 48,000 |
| Synchrotron campaigns (2–3 per year, 2–4 persons, 5–7 days each) | 36,000 |
| Publication costs / open access (€ 750/year) | 4,500 |
| Project-specific workshop “Bonding descriptors for memristive materials” (year 5) | 10,000 |
| **Subtotal** | **98,500** |

## 4.5  Overall summary

| **Module**                                          |         **Total (€)** |
|-----------------------------------------------------|----------------------:|
| Personnel (incl. group leader)                      |             1,384,200 |
| Consumables                                         |               120,000 |
| Instrumentation                                     |               155,000 |
| Travel, publications, workshop                      |                98,500 |
| **Requested direct funds**                          |         **1,757,700** |
| Programme allowance (22 %, to the host institution) |               386,694 |
| **Total volume**                                    | **approx. 2,144,400** |

# 5  Prerequisites for Carrying Out the Project

## 5.1  Environment at the host institution

\[RWTH Aachen University or Forschungszentrum Jülich – to be fixed before submission; within the Jülich/Aachen environment (JARA) the entire required infrastructure is established and immediately familiar to the applicant from his doctorate and postdoc.\] Required basic equipment: PLD system with high-pressure RHEED and multi-target carousel; high-resolution X-ray diffractometry incl. reciprocal space mapping; cleanroom with optical and electron-beam lithography (Helmholtz Nano Facility or RWTH cleanroom) and metallisation; AFM; access to XPS. \[Attach confirmation of the institution on provision of laboratory space and basic equipment – obligatory for Emmy Noether proposals.\]

## 5.2  Collaborations

- **FZ Jülich, PGI-7 (Prof. R. Dittmann)** – exchange of methods on operando spectromicroscopy of memristive devices (X-PEEM with graphene electrodes \[9, 10, 53\]) and device benchmarking; at the same time, the spatial and thematic demarcation (descriptor physics of epitaxial solid-solution series rather than BEOL integration) documents the independence of the junior research group. \[Attach letter of commitment.\]

- **Chueh group, Stanford University / SLAC (Prof. W. C. Chueh)** – established transatlantic collaboration from the applicant’s Feodor Lynen fellowship: defect thermodynamics, XAS methodology, continued joint work on the descriptor programme. \[Attach letter of commitment.\]

- \[Insert synchrotron partner, e.g. HZB/BESSY II (SPEEM/EMIL) or DESY/P04\] – support with beamtime proposals, end-station know-how and transfer of the SSRL-proven XAS protocols to European beamlines (WP4).

- \[Insert theory partner, e.g. a group with DFT defect-chemistry expertise\] – computation of vacancy formation and charge-transfer energies of the investigated compositions for validation of the experimental descriptors (WP5).

\[Attach letters of commitment as appendices.\]

## 5.3  Equal opportunities, early-career researchers

The junior research group will advertise all positions internationally and aims for a balanced gender ratio; the doctoral researchers will be integrated into the structured doctoral programme of the host institution. The applicant brings several years of supervision experience (master’s theses at FZ Jülich/RWTH Aachen since 2023, laboratory course supervision 2020–2025) and will take up the leadership and training offers of the Emmy Noether network.

# 6  Declarations

- No proposal for funding of this project has been submitted to any other institution. In the event of parallel or later submission elsewhere, the DFG will be informed immediately.

- The guidelines for safeguarding good research practice (DFG Code of Conduct) will be observed; the host institution has implemented the guidelines.

- The DFG usage guidelines as well as the rules on publication and on the handling of research data (Section 2.6) will be observed.

- No ethical, safety-related or dual-use aspects are associated with this project.
