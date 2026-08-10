**Marie Skłodowska-Curie Actions – Postdoctoral Fellowship (Global Fellowship)**

Covalency as an Experimental Descriptor of Memristive Switching: the SrTi1-xFexO3-δ Model Series

|  |  |
|----|----|
| **Applicant** | Dr. Max Buczek, Postdoctoral Researcher, Peter Grünberg Institute (PGI-7), Forschungszentrum Jülich, Germany |
| **Host abroad** | Prof. Dr. William C. Chueh, Department of Materials Science and Engineering, Stanford University, USA (Stanford Synchrotron Radiation Lightsource, SSRL) |
| **German / European host** | \[RWTH Aachen University or Forschungszentrum Jülich – to be fixed; hosts the return/reintegration phase where applicable\] |
| **Duration** | 36 months (24 outgoing + 12 return) |
| **Format** | Global Postdoctoral Fellowship: 24-month outgoing phase at Stanford University / SLAC (third country) + mandatory 12-month return phase at the European host \[FZ Jülich or RWTH Aachen as applicant/beneficiary organisation\] |
| **Funding** | Horizon Europe unit costs: living, mobility and (if applicable) family allowances, country-corrected \[insert current rates\] |
| **Eligibility** | PhD ≤ 8 years at call deadline; MSCA mobility rule for the outgoing host country (max. 12 months in the USA within the 36 months before the deadline) \[verify against personal record\] |
| **Application** | Annual single-stage call \[insert current deadline, typically September\], submitted by the European host institution |
| **Special feature** | Explicit training, supervision and two-way knowledge-transfer requirements; funded 12-month return phase |

*Standalone draft proposal for this funding line (status 09.08.2026). Only one of the parallel programme drafts of this folder will be pursued for the research stay – check each funder’s double-funding rules before submission. Materials selection follows the portfolio’s three-criterion evidence logic; all cited references are individually verified against publisher records (see Literaturpruefung_2026-08-09 and Materialscreening_2026-08-09).*

1 Research question and scientific significance

Memristive devices based on the valence change mechanism (VCM) switch their resistance through field-driven creation and migration of oxygen vacancies (VO) \[1–3\]. The oxygen-vacancy formation energy (EV) enters all quantitative switching models exponentially \[3, 4\] – and yet it has never been measured systematically how EV determines the central figures of merit (ON/OFF ratio, forming voltage, retention). Energy research, by contrast, has quantitatively established that EV in perovskites is controlled by the metal–oxygen covalency: the O-2p band centre scales linearly with EV and serves as a descriptor for catalysis and oxygen transport \[5–8\]. My project connects these two worlds experimentally for the first time – using the model system SrTi1-xFexO3-δ (STF), the one perovskite series in which intrinsic switching, an inert/graphene electrode platform and a quantitatively mapped defect chemistry already coexist. A decisive design requirement drives this choice: in many perovskite memristors – including Pr0.7Ca0.3MnO3, the system of my own doctorate – robust switching requires a reactive metal electrode, and the oxygen exchange with the resulting second oxide (TiOx, AlOx) then dominates the mechanism \[23, 24\]. A clean covalency study must instead use a system whose oxygen balance stays inside the oxide.

STF is the ideal test system for a clean covalency study, for three reasons. (i) The covalency/reducibility axis is quantitatively mapped: STF forms a continuous cubic solid solution between SrTiO3 and SrFeO3-δ, and its defect chemistry is known in closed form – band gap Eg(x) = 3.2 − 1.9x + 0.5x² eV and reduction enthalpy ΔHred(x) = 5.8 − 3.4x + 1.7x² eV \[9\]; the Fe–O hybridisation across the series is documented by X-ray absorption \[10–12\]. The Fe content thus tunes the ease of oxygen-vacancy formation continuously within one perovskite host – the descriptor axis of this project, with literature values to test against. (ii) The switching axis is intrinsic – no reactive electrode required: Fe-doped SrTiO3 devices with inert electrodes switch via oxygen-vacancy modulation of the Schottky barrier (“eightwise”) as well as via intrinsic filaments \[13, 14, 30\]; Cr-doped SrTiO3 switches with inert electrodes with operando-XAS-proven vacancy drift \[15\]; and spectromicroscopy has traced the mechanism to oxygen migration and Ti valence changes within the oxide itself \[16\]. Crucially, the photoelectron-transparent graphene top-electrode platform has been demonstrated on exactly this materials system \[17, 18\]. Graphene is not merely convenient here but scientifically necessary: 18O-tracer and humidity studies show that under permeable electrodes, eightwise switching exchanges oxygen with ambient water \[19, 20\] – only a gas-tight (graphene-sealed) electrode makes the oxygen balance truly internal and the covalency–switching correlation unambiguous. (iii) The mechanism is stable across the series: for x ≤ 0.3, STF remains a cubic, p-type semiconducting perovskite – no topotactic brownmillerite transition and no metal–insulator transition interferes \[9\], in deliberate contrast to the manganite, ferrite and cobaltite families. The gap: a systematic Fe-content series in epitaxial devices under inert/graphene electrodes does not exist – published composition series were measured either with reactive electrodes (Ti/Pr1-xCaxMnO3 \[23\], where the electrode oxide dominates the mechanism \[24\]) or on polycrystalline films in a narrow composition window \[22, 31\]. That stoichiometry can control switching at a noble-metal interface has, however, been demonstrated on the closest possible platform – for the cation (Sr/Ti) stoichiometry of Pt/SrTiO3 junctions \[32\]; the covalency-controlling Fe content is precisely the missing series. My central hypothesis: the switching figures of merit of intrinsic STF devices scale with the covalency/reduction-enthalpy descriptor, with an optimum of the usable window at intermediate x – and the descriptor is measured, not merely computed \[11\].

Conceptual footing (sharpened after expert feedback, 08/2026): throughout this project, “covalency” is used in the quantitative sense of the charge-transfer/cluster-model framework – charge-transfer energy Δ, on-site Coulomb energy U and transfer integrals, in the Zaanen–Sawatzky–Allen classification \[33\] and as extracted compound by compound by the configuration-interaction analyses of Fujimori, Bocquet, Saitoh, Sarma and co-workers \[34–37\]. O-K pre-edge intensities serve as a relative, series-internal hybridisation measure only; their limits as an absolute covalency scale (core-hole effects, ligand-hole distribution, band effects) are treated explicitly \[38\], and the conflation of hybridisation with covalency that is common in the catalysis-descriptor literature is deliberately avoided – the descriptor scale of this project is calibrated against cluster-model analysis, not against pre-edge intensity alone. System-specific parameter status (re-screening, 09.08.2026): no cluster-model parameter extraction exists for Fe in SrTiO3 – the project’s own CI analysis is therefore an explicit deliverable, starting from the published d0 host systematics \[39\] and the Fe3+/Fe4+ end-point parameters of the ferrate family \[40\].

Methodological platform (added 08/2026) – one wafer, one map: beyond discrete samples, the composition series is realised as a single wafer carrying a continuous lateral cation-stoichiometry gradient, grown in continuous-compositional-spread mode \[41\] on a large-area PLD system of the type I have already used for wafer-scale memristive heterostructures \[E3\]; combinatorial hardware of this class covers substrates up to four inches \[42\], and epitaxial perovskite composition spreads are established \[43\]. Spatially resolved soft XAS turns such a wafer into a continuous covalency map – on-the-fly L-edge mapping of a combinatorial spread with a 0.5 mm beam has recently been demonstrated \[44\], and beamlines built for automated high-throughput NEXAFS exist for exactly this duty cycle \[45\] – while automated prober mapping of device arrays along the same gradient track yields the corresponding switching map \[46\]. With a 0.2–0.5 mm beam footprint on a 50 mm gradient, one wafer carries 100–250 independent composition points; the limiting quantity is the composition calibration map (XRF/WDS), not the beam. The known pitfalls are addressed by design: slit-synchronised scanning decouples composition from thickness \[41\], cation transfer is fluence- and pO2-sensitive and therefore calibrated per position \[47\], and structural quality across the wafer is mapped rather than assumed.

The same wafer turns the weakest link of the descriptor chain into a measurement. Equilibrated at a defined oxygen partial pressure and temperature, every position adopts its own non-stoichiometry δ; mapping the transition-metal valence in the same XAS scan yields δ(x; pO2, T), and repeating this across oxidising and reducing conditions gives the reduction enthalpy ΔHred(x) – an experimentally determined vacancy-formation energy measured on the same spots, the same sample and the same growth run as the covalency descriptor. To be precise about what spectroscopy delivers: XAS gives valence, not an absolute oxygen content, so the map is calibrated against anchor points from chemical capacitance \[48\], chemical expansion (high-temperature XRD) or a reference of known stoichiometry; optical absorption provides a second, fully imageable δ read-out \[50\]. Thin-film defect chemistry of exactly this type is established for ceria films \[48\] and for (La,Sr)FeO3-δ films \[49\], and the composition-dependent reduction enthalpy of the SrTi1-xFexO3-δ solid solution is the natural validation target: if the gradient wafer reproduces that published curve, the method is proven, and only then does the co-located descriptor measurement carry weight. The covalency→EV link, which for most systems currently rests on calculation rather than experiment, thereby becomes a directly measured correlation whose predictive quality can be quantified per composition instead of asserted.

Three constraints are taken seriously from the outset. (i) Detection under gas: total-electron yield collapses above a few mbar; Auger yield through a differentially pumped analyser carries to roughly 25 mbar and windowed fluorescence yield to ambient pressure, the latter at the price of self-absorption corrections at the transition-metal L edges. Ambient-pressure NEXAFS endstations built for this envelope exist and are combined with high-throughput operation \[45\]. (ii) Surface versus bulk: electron and Auger yield probe only the outer nanometres, precisely where enrichment and reconstruction may occur under high temperature and oxygen pressure, so bulk-sensitive fluorescence yield is recorded alongside and film thicknesses kept small. (iii) Radiation dose: soft-X-ray photoreduction of Ce, Mn, Fe and Co drives the valence in the same direction as the gas-induced reduction under study, so dose series, defocused fast scans and fresh-spot rastering are part of the protocol rather than an afterthought. Where electrochemical δ control is required, it needs an ion-conducting substrate stack and is therefore a deliberate choice for dedicated calibration wafers, not the default of the epitaxial gradient series. An ex-situ equilibrate-quench-measure route remains available as a fallback where δ is frozen in, which is defensible for titanates and manganites and marginal for cobaltites, ceria and YBCO.

Descriptor construction (specified 08/2026): covalency is quantified as the ligand-hole weight w_L of the configuration-interaction ground state - the deviation of the d occupation from the formal valence, set by the charge-transfer energy, the d-d Coulomb energy and the transfer integrals \[34, 35\] within the Zaanen-Sawatzky-Allen classification \[33\]. Because O K pre-edge intensity probes unoccupied states whereas w_L is a ground-state quantity, the descriptor is built in three steps. (D1) The pre-edge area normalised per d hole - with the hole count taken from the transition-metal L2,3 fit at the same position rather than from the nominal stoichiometry - is the fast, mappable measure \[11\], its interpretation limits taken from the O K-edge methodology literature \[38\]. (D2) At six to ten support points per series, cluster-model analysis of the transition-metal 2p core-level satellites and of the L2,3 multiplets yields the charge-transfer energy, the Coulomb energy and the transfer integrals, and hence w_L itself \[35\], evaluated with charge-transfer multiplet and Wannier-based multiplet ligand-field codes \[51, 52\]. (D3) The regression between D1 and D2 converts the fast measure into a cluster-model-anchored covalency across all positions, with propagated uncertainty. Only this calibrated quantity enters the correlation with the vacancy formation energy; a pre-edge intensity on its own is treated as a series-internal relative measure and nothing more. Ambient-pressure endstations that combine core-level photoemission with NEXAFS allow D1 and D2 to be recorded at the same sample position \[45\], so the calibration is not carried across separate beamtimes. The descriptor is finally held to a model comparison against formal valence, tolerance factor and the uncalibrated pre-edge area; if it does not outperform them, that is reported as the result.

2 Programme fit and strategy

The MSCA Global Fellowship funds the project as a 24-month outgoing phase at Stanford plus a mandatory, funded 12-month return phase at the European host. The return phase institutionalises exactly what the planned group programme needs: transfer of the SSRL-proven XAS protocols to European beamlines, integration of the descriptor dataset into the map, and preparation of the ERC/Emmy Noether bid. MSCA-specific proposal sections (training objectives, supervision arrangement between Prof. Chueh and the German host, dissemination and exploitation plan, two-way transfer of knowledge) must be completed per the current template.

3 Why the Chueh group at Stanford is the ideal place

The group of Prof. William Chueh is a world leader in exactly the combination this project requires: defect chemistry and non-stoichiometry of redox-active oxides, quantitative operando X-ray absorption spectroscopy at the in-house Stanford Synchrotron Radiation Lightsource (SSRL), and redox chemistry of epitaxial perovskite thin films \[25–27\] – STF itself is a canonical solid-oxide-fuel-cell and oxygen-permeation material, so its defect thermodynamics \[9\] lie squarely in the group’s home territory. The group’s seminal work on the redox activity of oxygen anions in oxygen-deficient perovskites \[26\] is a direct methodological blueprint for my project; the Nature Materials study on atomically defined LaNiO3 surfaces \[27\] – with Christoph Baeumer from the Jülich school as first author – furthermore demonstrates that the group routinely masters epitaxial perovskite model systems of the type proposed here and successfully integrates German postdocs. Direct SSRL access makes XAS campaigns plannable that in Europe cost months of lead time through competitive single proposals. Complementarily, I contribute the device side, from which the Stanford environment profits in turn: PLD process development, memristive device processing and statistically robust switching characterisation from five years at the Peter Grünberg Institute (PGI-7, group of Prof. Dittmann) \[E1–E3\] – the very school that established both the Fe:SrTiO3 switching platform and the graphene-electrode spectroscopy concept \[13, 16–18\], whose processing and metrology I know first-hand. This two-sided fit is the strongest possible de-risking for a 24-month project: the device platform is proven Jülich methodology, the defect-chemistry and XAS side is proven Stanford methodology, and the fellowship time is spent on their genuinely new combination. The constellation is thus a genuine two-way transfer of knowledge. For complementary epitaxial growth questions, the environment of the Stanford Institute for Materials and Energy Sciences (SIMES) at SLAC is available. \[Host choice under review after first-hand feedback (08/2026): the Chueh group’s own perovskite/oxide-redox activities have largely moved on; the relevant lines are continued in alumni groups – C. Baeumer (University of Twente), Q. Lu (Westlake University), J. T. Mefford, D. Chen. If XAS quantification is the methodological core, a host with direct synchrotron access (e.g. PSI/SLS, MAX IV, Diamond, or a beamline-affiliated group) is a serious alternative. Re-validate and, if necessary, rewrite this section before submission.\]

4 Work programme

**WP1 – Synthesis and descriptor measurement of the STF series (months 1–10, Stanford)**

PLD growth of epitaxial SrTi1-xFexO3-δ films (x = 0; 0.02; 0.05; 0.1; 0.2; 0.3 – from the dilute-dopant regime of the established Fe:SrTiO3 devices \[13\] into the mixed-conducting regime, safely below the vacancy-ordering region) on Nb:SrTiO3 substrates in the Stanford/SLAC thin-film laboratories; structural validation (XRD, AFM); cation and oxygen stoichiometry (XPS, RBS where required). In parallel, first XAS campaign at SSRL: Fe-L2,3 and Ti-L2,3 valence analysis and O-K pre-edge quantification following \[11\] for every composition → experimental covalency scale of the series, benchmarked against the closed-form defect model \[9\] and the published STF spectroscopy \[10\]. Milestone M1 (month 10): validated sample series with complete descriptor set. In parallel with the discrete samples, a gradient wafer of the same system is grown in continuous-compositional-spread mode \[41, 42\] and calibrated position by position (XRF/WDS composition map, XRR thickness, XRD structural quality); the discrete series remains the backbone of the analysis, the gradient wafer is the throughput accelerator and the carrier of the defect-chemical titration in WP3.

**WP2 – Intrinsic devices and switching characterisation (months 8–18, Stanford)**

Two inert top-electrode flavours per composition, processed photolithographically with ≥ 30 nominally identical cells each: (i) Pt pads as the workhorse geometry, and (ii) graphene-sealed cells – photoelectron-transparent and gas-tight, following the platform demonstrated on SrTiO3 \[17, 18\] – which keep the oxygen balance strictly internal \[19, 20\] and remain spectroscopy-ready. Interface control against unintentional layers follows the lessons of \[21\] (epitaxial platform, reference samples). Quasistatic and pulsed characterisation of the eightwise regime \[13, 14, 29\] under the statistics protocol established in my doctorate (ON/OFF at defined read-out voltage, forming requirement, kinetics, temperature-accelerated retention, endurance). Milestone M2 (month 18): switching figures of merit as a function of x, in both geometries, with robust statistics.

**WP3 – Correlation, operando validation and publication (months 16–24, Stanford)**

Correlation analysis covalency (XAS) ↔ ΔHred/EV (defect model \[9\], descriptor models \[5–8\]) ↔ switching metrics; test of the optimum hypothesis. Second SSRL campaign: XAS through the graphene electrode on switched cells (ex-situ before/after switching, operando if successful, following \[17\]) to verify that the composition-dependent differences rest on different VO dynamics inside the oxide. Publication of the first covalency-resolved study of intrinsically switching perovskite devices; dataset released following FAIR principles. Milestone M3 (month 24): submitted publication(s), public dataset. On the gradient wafer, the defect-chemical gas titration introduced in Section 1 is carried out: δ(x; pO2, T) from oxidising and reducing equilibria yields ΔHred(x) and thus a covalency↔EV correlation measured spot-by-spot against the descriptor on one and the same sample \[45\], with equilibrium and radiation-dose controls preceding any descriptor claim.

**WP4 – Return phase: European transfer and map integration (months 25–36, \[RWTH Aachen / FZ Jülich\])**

European beamline campaigns (BESSY II/PETRA III) transferring the SSRL-proven XAS protocols; cross-class integration of the descriptor dataset into the map; publication of the extended dataset; preparation and submission of the junior-group proposal (Emmy Noether/ERC); supervision and training plan per MSCA rules spanning both phases. Milestone M4 (month 36): map integration complete, group proposal submitted.

5 Timeline

|  |  |  |  |  |  |  |  |  |  |  |  |  |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
| **Work package** | **Q1** | **Q2** | **Q3** | **Q4** | **Q5** | **Q6** | **Q7** | **Q8** | **Q9** | **Q10** | **Q11** | **Q12** |
| WP1 Synthesis + XAS descriptors | ■ | ■ | ■ | (■) |  |  |  |  |  |  |  |  |
| WP2 Devices + switching statistics |  |  | ■ | ■ | ■ | ■ |  |  |  |  |  |  |
| WP3 Correlation + operando + publication |  |  |  |  |  | ■ | ■ | ■ |  |  |  |  |
| WP4 Return phase: transfer + map integration |  |  |  |  |  |  |  |  | ■ | ■ | ■ | ■ |

6 Career perspective

The project is the building block between the applicant’s doctorate (memristive devices, PLD, switching statistics) and the goal of an own junior research group in Europe on descriptor-based materials development for memristive oxides. The funded return phase reintegrates the methodology into the European research area (FZ Jülich/RWTH Aachen, JARA) and prepares the ERC Starting Grant/Emmy Noether bid; the MSCA fellowship itself strengthens the European profile of that bid. The choice of STF is deliberate: the switching stays inside the oxide (no reactive-electrode confounder), the graphene-sealed platform keeps it spectroscopy-ready, and the mechanism is stable across the composition range – the subsequent group programme scales the validated methodology to the mixed-valent A-site families. The Stanford/SSRL collaboration will be continued as the transatlantic bridge of the future group.

7 References

\[1\] R. Waser, M. Aono, Nanoionics-based resistive switching memories. Nature Materials 6, 833–840 (2007).

\[2\] R. Waser, R. Dittmann, G. Staikov, K. Szot, Redox-Based Resistive Switching Memories – Nanoionic Mechanisms, Prospects, and Challenges. Advanced Materials 21, 2632–2663 (2009).

\[3\] R. Dittmann, S. Menzel, R. Waser, Nanoionic memristive phenomena in metal oxides: the valence change mechanism. Advances in Physics 70, 155–349 (2021).

\[4\] S. Menzel, M. Waters, A. Marchewka, U. Böttger, R. Dittmann, R. Waser, Origin of the Ultra-nonlinear Switching Kinetics in Oxide-Based Resistive Switches. Advanced Functional Materials 21, 4487–4492 (2011).

\[5\] Y.-L. Lee, J. Kleis, J. Rossmeisl, Y. Shao-Horn, D. Morgan, Prediction of solid oxide fuel cell cathode activity with first-principles descriptors. Energy & Environmental Science 4, 3966–3970 (2011).

\[6\] R. Jacobs, J. Hwang, Y. Shao-Horn, D. Morgan, Assessing Correlations of Perovskite Catalytic Performance with Electronic Structure Descriptors. Chemistry of Materials 31, 785–797 (2019).

\[7\] A. M. Deml, V. Stevanović, C. L. Muhich, C. B. Musgrave, R. O’Hayre, Oxide enthalpy of formation and band gap energy as accurate descriptors of oxygen vacancy formation energetics. Energy & Environmental Science 7, 1996–2004 (2014).

\[8\] R. B. Wexler, G. Sai Gautam, E. B. Stechel, E. A. Carter, Factors Governing Oxygen Vacancy Formation in Oxide Perovskites. Journal of the American Chemical Society 143, 13212–13227 (2021).

\[9\] A. Rothschild, W. Menesklou, H. L. Tuller, E. Ivers-Tiffée, Electronic Structure, Defect Chemistry, and Transport Properties of SrTi1-xFexO3-y Solid Solutions. Chemistry of Materials 18, 3651–3659 (2006).

\[10\] M. Vračar, A. Kuzmin, R. Merkle, J. Purans, E. A. Kotomin, J. Maier, O. Mathon, Jahn-Teller distortion around Fe4+ in Sr(FexTi1-x)O3-δ from x-ray absorption spectroscopy, x-ray diffraction, and vibrational spectroscopy. Physical Review B 76, 174107 (2007).

\[11\] J. Suntivich et al., Estimating Hybridization of Transition Metal and Oxygen States in Perovskites from O K-edge X-ray Absorption Spectroscopy. Journal of Physical Chemistry C 118, 1856–1863 (2014).

\[12\] F. Frati, M. O. J. Y. Hunault, F. M. F. de Groot, Oxygen K-edge X-ray Absorption Spectra. Chemical Reviews 120, 4056–4110 (2020).

\[13\] R. Muenstermann, T. Menke, R. Dittmann, R. Waser, Coexistence of Filamentary and Homogeneous Resistive Switching in Fe-Doped SrTiO3 Thin-Film Memristive Devices. Advanced Materials 22, 4819–4822 (2010).

\[14\] A. Sarantopoulos, R. Waser, R. Dittmann, Eightwise Switching Mechanism in Memristive SrTiO3 Devices and Its Implications on the Device Performance. Physica Status Solidi A 221, 2300483 (2024).

\[15\] M. Janousch, G. I. Meijer, U. Staub, B. Delley, S. F. Karg, B. P. Andreasson, Role of Oxygen Vacancies in Cr-Doped SrTiO3 for Resistance-Change Memory. Advanced Materials 19, 2232–2235 (2007).

\[16\] C. Baeumer et al., Spectromicroscopic insights for rational design of redox-based memristive devices. Nature Communications 6, 8610 (2015).

\[17\] C. Baeumer et al., Quantifying redox-induced Schottky barrier variations in memristive devices via in operando spectromicroscopy with graphene electrodes. Nature Communications 7, 12398 (2016).

\[18\] C. Baeumer et al., Subfilamentary Networks Cause Cycle-to-Cycle Variability in Memristive Devices. ACS Nano 11, 6921–6929 (2017).

\[19\] T. Heisig, C. Baeumer, U. N. Gries et al., Oxygen Exchange Processes between Oxide Memristive Devices and Water Molecules. Advanced Materials 30, 1800957 (2018).

\[20\] E. Sediva, W. J. Bowman, J. C. Gonzalez-Rosillo, J. L. M. Rupp, Investigation of the Eightwise Switching Mechanism and Its Suppression in SrTiO3 Modulated by Humidity and Interchanged Top and Bottom Platinum and LaNiO3 Electrode Contacts. Advanced Electronic Materials 5, 1800566 (2019).

\[21\] E. Mikheev, B. D. Hoskins, D. B. Strukov, S. Stemmer, Resistive switching and its suppression in Pt/Nb:SrTiO3 junctions. Nature Communications 5, 3990 (2014).

\[22\] K.-H. Son, H.-S. Lee, Grain boundary effect on the resistive switching characteristics of SrTi1-xFexO3 directly patterned via photochemical organic-metal deposition. Applied Surface Science 575, 151754 (2022).

\[23\] S. Asanuma, H. Akoh, H. Yamada, A. Sawa, Relationship between resistive switching characteristics and band diagrams of Ti/Pr1-xCaxMnO3 junctions. Physical Review B 80, 235113 (2009).

\[24\] A. Herpers, C. Lenser, C. Park, F. Offi, F. Borgatti, G. Panaccione, S. Menzel, R. Waser, R. Dittmann, Spectroscopic proof of the correlation between redox-state and charge-carrier transport at the interface of resistively switching Ti/PCMO devices. Advanced Materials 26, 2730–2735 (2014).

\[25\] W. C. Chueh, C. Falter, M. Abbott, D. Scipio, P. Furler, S. M. Haile, A. Steinfeld, High-Flux Solar-Driven Thermochemical Dissociation of CO2 and H2O Using Nonstoichiometric Ceria. Science 330, 1797–1801 (2010).

\[26\] D. N. Mueller, M. L. Machala, H. Bluhm, W. C. Chueh, Redox activity of surface oxygen anions in oxygen-deficient perovskite oxides during electrochemical reactions. Nature Communications 6, 6097 (2015).

\[27\] C. Baeumer, J. Li, Q. Lu et al. (with W. C. Chueh), Tuning electrochemically driven surface transformation in atomically flat LaNiO3 thin films for enhanced water electrolysis. Nature Materials 20, 674–682 (2021).

\[28\] M. Wuttig et al., Revisiting the Nature of Chemical Bonding in Chalcogenides to Explain and Design their Properties. Advanced Materials 35, 2208485 (2023).

\[29\] A. Sarantopoulos, K. Lange, F. Rivadulla, S. Menzel, R. Dittmann, Resistive Switching Acceleration Induced by Thermal Confinement. Advanced Electronic Materials 11, 2400555 (2025).

\[30\] M. Mladenović, M. Kaniselvan, C. Weilenmann, A. Emboras, M. Luisier, Termination-Dependent Resistive Switching in SrTiO3 Valence Change Memory Cells. ACS Applied Electronic Materials 7, 2839–2847 (2025).

\[31\] K.-J. Lee, C.-H. Wu, C.-J. Lee, D.-W. Chou, N.-F. Wang, Y.-H. Wang, Reset-Voltage Controlled Resistance-State and Applications of Forming-Free Fe-Doped SrTiO3 Thin-Film Memristor. Materials 17, 5021 (2024).

\[32\] E. Mikheev, J. Hwang, A. P. Kajdos, A. J. Hauser, S. Stemmer, Tailoring resistive switching in Pt/SrTiO3 junctions by stoichiometry control. Scientific Reports 5, 11079 (2015).

\[33\] J. Zaanen, G. A. Sawatzky, J. W. Allen, Band gaps and electronic structure of transition-metal compounds. Physical Review Letters 55, 418–421 (1985).

\[34\] A. Fujimori, F. Minami, Valence-band photoemission and optical absorption in nickel compounds. Physical Review B 30, 957–971 (1984).

\[35\] A. E. Bocquet, T. Mizokawa, T. Saitoh, H. Namatame, A. Fujimori, Electronic structure of 3d-transition-metal compounds by analysis of the 2p core-level photoemission spectra. Physical Review B 46, 3771–3784 (1992).

\[36\] T. Saitoh, A. E. Bocquet, T. Mizokawa, A. Fujimori, Systematic variation of the electronic structure of 3d transition-metal compounds. Physical Review B 52, 7934–7938 (1995).

\[37\] S. Nimkar, D. D. Sarma, H. R. Krishnamurthy, S. Ramasesha, Mean-field results of the multiple-band extended Hubbard model for the square-planar CuO2 lattice. Physical Review B 48, 7355–7363 (1993).

\[38\] F. M. F. de Groot, X-ray absorption and dichroism of transition metals and their compounds. Journal of Electron Spectroscopy and Related Phenomena 67, 529–622 (1994).

\[39\] A. E. Bocquet, T. Mizokawa, K. Morikawa, A. Fujimori et al., Electronic structure of early 3d-transition-metal oxides by analysis of the 2p core-level photoemission spectra. Physical Review B 53, 1161–1170 (1996).

\[40\] A. E. Bocquet, A. Fujimori, T. Mizokawa, T. Saitoh, H. Namatame, S. Suga, N. Kimizuka, Y. Takeda, M. Takano, Electronic structure of SrFe4+O3 and related Fe perovskite oxides. Physical Review B 45, 1561–1570 (1992).

\[41\] H. M. Christen, C. M. Rouleau, I. Ohkubo, H. Y. Zhai, H. N. Lee, S. Sathyamurthy, D. H. Lowndes, An improved continuous compositional-spread technique based on pulsed-laser deposition and applicable to large substrate areas. Review of Scientific Instruments 74, 4058–4062 (2003).

\[42\] M. Lorenz, H. Hochmuth, H. von Wenckstern, M. Grundmann, Flexible hardware concept of pulsed laser deposition for large areas and combinatorial composition spreads. Review of Scientific Instruments 94, 083905 (2023).

\[43\] A. Venimadhav, K. A. Yates, M. G. Blamire, Scanning Raman Spectroscopy for Characterizing Compositionally Spread Films. Journal of Combinatorial Chemistry 7, 85–89 (2005).

\[44\] Y. Yamasaki, N. Sasabe, Y. Ishii, Y. Sekiguchi, A. Sumiyoshiya, Y. Tanimoto, Y. Kotani, T. Nakamura, H. Nomura, High-throughput mapping of magnetic properties via the on-the-fly XMCD spectroscopy in a combinatorial Fe-Co-Ni film. Science and Technology of Advanced Materials: Methods 5, 2544528 (2025). \[volume/article number from a single source – verify before submission\]

\[45\] D. C. Grinter, P. Ferrer, F. Venturini, M. A. van Spronsen, A. I. Large et al., VerSoX B07-B: a high-throughput XPS and ambient pressure NEXAFS beamline at Diamond Light Source. Journal of Synchrotron Radiation 31, 578–589 (2024).

\[46\] M. Tang, L. Dai, M. Cheng, Y. Zhang, Y. Wang et al., High-Throughput Screening Thickness-Dependent Resistive Switching in SrTiO3 Thin Films for Robust Electronic Synapse. Advanced Functional Materials 33, 2213874 (2023).

\[47\] S. Wicklein, A. Sambri, S. Amoruso, X. Wang, R. Bruzzese, A. Koehl, R. Dittmann, Pulsed laser ablation of complex oxides: The role of congruent ablation and preferential scattering for the film stoichiometry. Applied Physics Letters 101, 131601 (2012).

\[48\] W. C. Chueh, S. M. Haile, Electrochemical studies of capacitance in cerium oxide thin films and its relationship to anionic and electronic defect densities. Physical Chemistry Chemical Physics 11, 8144–8148 (2009).

\[49\] A. Schmid, G. M. Rupp, J. Fleig, Voltage and partial pressure dependent defect chemistry in (La,Sr)FeO3-δ thin films investigated by chemical capacitance measurements. Physical Chemistry Chemical Physics 20, 12016–12026 (2018).

\[50\] J. J. Kim, S. R. Bishop, N. J. Thompson, H. L. Tuller, Investigation of Nonstoichiometry in Oxide Thin Films by Simultaneous in Situ Optical Absorption and Chemical Capacitance Measurements: Pr-Doped Ceria, a Case Study. Chemistry of Materials 26, 1374–1379 (2014).

\[51\] E. Stavitski, F. M. F. de Groot, The CTM4XAS program for EELS and XAS spectral shape analysis of transition metal L edges. Micron 41, 687-694 (2010).

\[52\] M. W. Haverkort, M. Zwierzycki, O. K. Andersen, Multiplet ligand-field theory using Wannier orbitals. Physical Review B 85, 165113 (2012).

\[E1\] M. Buczek et al., Amorphous, Highly Conductive Pr0.7Ca0.3MnO3 for Area-Dependent Resistive Switching Devices. Advanced Electronic Materials (2026, accepted).

\[E2\] M. Buczek, Z. Moos, A. Gutsche, S. Menzel, R. Dittmann, Pr1-xCaxMnO3-Based Memristive Heterostructures: Basic Mechanisms and Applications. Chemical Reviews 125, 6156–6202 (2025).

\[E3\] M. Buczek et al., Large Area Pulsed Laser Deposition of Memristive Pr0.7Ca0.3MnO3 Heterostructures for Neuromorphic Computing. Thin Solid Films (2024).

8 Notes before submission

• Verify all bracketed programme details (rates, deadlines, current call conditions) against the funder’s current documentation. • Coordinate the proposal with Prof. Chueh and fix the German/European host institution. • European host institution acts as applicant – letter of commitment, supervision agreement (both hosts) and training plan required per MSCA template. • Manuscript placeholders in the publication list (\[E1\]) to be updated at submission time.
