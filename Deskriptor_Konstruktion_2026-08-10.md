Konstruktion des Kovalenz-Deskriptors aus XAS-Daten und seine Verknüpfung mit der Sauerstoffleerstellen-Bildungsenergie

*Stand: 10.08.2026. Claude-Code-generiert. Ausgearbeitet auf Grundlage der Clustermodell- und Konfigurationswechselwirkungs-Literatur der 1980er und 1990er Jahre (Fujimori/Minami; Bocquet; Mizokawa/Fujimori; Fuggle; Sarma; ZSA-Schema) und als Antwort auf das externe Fachfeedback (08/2026), die O-K-Vorkantenquantifizierung nicht als etablierte Kovalenzskala zu behandeln. Dieses Dokument legt fest, wie der Deskriptor gebildet, kalibriert und geprüft wird; es ist die methodische Grundlage der Anträge und der Gradient-Wafer-Plattform.*

1 Was „Kovalenz“ im Clustermodell exakt bedeutet

Im Konfigurationswechselwirkungs-Clustermodell ist der Grundzustand eines Übergangsmetall-Sauerstoff-Clusters keine reine d^n-Konfiguration, sondern eine Überlagerung \|ψ⟩ = α\|d^n⟩ + β\|d^(n+1)L⟩ + γ\|d^(n+2)L²⟩ + …, wobei L ein Loch im Sauerstoff-2p-Ligandenorbital bezeichnet \[2, 3\]. Das natürliche, quantitative Kovalenzmaß ist damit das Ligandenlochgewicht des Grundzustands, w_L = β² + 2γ² + …, gleichbedeutend mit der Abweichung der d-Besetzung von der formalen Valenz (n_d = n + w_L). Genau diese Größe – nicht eine Spektrenintensität – ist gemeint, wenn in diesem Portfolio von Kovalenz gesprochen wird.

w_L wird von drei Parametern bestimmt: der Ladungstransferenergie Δ = E(d^(n+1)L) − E(d^n), der d-d-Coulomb-Energie U_dd und den Transferintegralen (pdσ, pdπ), aus denen sich die effektive Hybridisierung der jeweiligen Symmetrie ergibt – in oktaedrischer Umgebung V(e_g) = √3 · pdσ und V(t_2g) = 2 · pdπ, mit dem üblichen Verhältnis pdπ ≈ −pdσ/2,2. Im Zweikonfigurationslimit gilt die geschlossene Form w_L = ½ · \[1 − Δ/√(Δ² + 4V²)\], also ein Mischungswinkel mit tan 2θ = 2V/Δ. Diese Formel ist der begriffliche Kern des Deskriptors: Kovalenz ist eine Funktion von Δ und V, nicht eine Eigenschaft eines einzelnen Spektralmerkmals.

Die Einordnung im Zaanen-Sawatzky-Allen-Schema \[1\] entscheidet über die Lesart: Bei Δ \> U liegt ein Mott-Hubbard-System vor, bei Δ \< U ein Ladungstransfer-System; im Grenzfall negativer Δ (Sr-reiche Ferrate und Kobaltite) ist der Grundzustand bereits von \|d^(n+1)L⟩ dominiert, und w_L sättigt. Systematische Parametertabellen über die 3d-Reihe liegen aus der Analyse von 2p-Rumpfniveau-Photoemission vor \[3, 4, 9\], ergänzt um Hartree-Fock-Rechnungen zu Spin- und Orbitalordnung in Perowskiten \[5\] und um Bandstrukturrechnungen, die Grundzustandsgrößen und Anregungsspektren der Reihe LaMO3 (M = Mn, Fe, Co, Ni) gemeinsam behandeln \[7\]; sie liefern die Startwerte und den Plausibilitätsrahmen für alle eigenen Fits.

Wichtige begriffliche Trennung, die im Weiteren durchgehalten wird: w_L ist eine Grundzustandsgröße. Die O-K-Vorkante misst dagegen unbesetzte Zustände mit O-2p-Charakter. Beide hängen über dieselbe Hybridisierung zusammen, sind aber nicht identisch – deshalb wird die Vorkante hier als Transfergröße einer Kalibrierung verwendet und nicht als Kovalenzskala.

2 Was XAS misst – und was nicht

O-K-Vorkante: Der Übergang O 1s → unbesetzte Zustände wiegt den O-2p-Anteil der hybridisierten TM-3d-O-2p-Zustände. Die Vorkantenfläche skaliert deshalb mit dem Produkt aus Lochzahl und Hybridisierungsgrad. Daraus folgt unmittelbar die wichtigste Auswertungsregel: Ohne Normierung auf die tatsächliche Lochzahl misst die Vorkante primär die Valenzänderung entlang der Serie, nicht die Kovalenzänderung. Ihre Aussagekraft ist überdies durch Endzustandseffekte, überlappende Beiträge weiterer Kationen und die Wahl von Untergrund und Normierungsfenster begrenzt \[11, 12\]; als serieninternes Relativmaß ist sie belastbar, als absolute Skala nicht \[13\].

TM-L2,3-Kanten: multiplettdominiert und damit empfindlich auf Ligandenfeld (10Dq), Spinzustand und d-Besetzung. Sie sind über Ladungstransfer-Multiplettrechnungen mit denselben Parametern Δ, U_dd und V auswertbar \[14, 15\] und liefern zugleich die für die Vorkantennormierung benötigte Valenz bzw. Lochzahl an derselben Position.

TM-2p-Rumpfniveau-Photoemission: Die Satellitenstruktur ist der klassische und direkteste Kanal zu Δ, U_dd und den Transferintegralen \[3, 4\]. Für das Projekt ist entscheidend, dass Ambient-Pressure-Endstationen mit Analysator (Diamond B07-B, ALBA CIRCE-NAPP) Rumpfniveau-Photoemission und NEXAFS an derselben Probenposition liefern: Der schnelle Vorkantenmaßstab und die CI-Parameter entstehen damit aus einer Messgeometrie und einem Probenpunkt. Für Cer-basierte Systeme tritt an die Stelle des 3d-Clustermodells das Anderson-Impurity-Modell nach Gunnarsson und Schönhammer, aus dem sich die Hybridisierungsstärke und die f-Besetzung quantitativ aus den Spektren gewinnen lassen \[6\].

Bekannte Fallstricke, die im Protokoll adressiert werden: Selbstabsorption in der Fluoreszenzausbeute, Sättigung in der Elektronenausbeute, Oberflächenempfindlichkeit der Elektronenausbeute (2–10 nm), strahlinduzierte Photoreduktion sowie – bei Fits von Rumpfniveauspektren – nichtlokale Schirmung, die Einplatz-Clusterfits verfälschen kann \[10\] und besonders bei Kupraten relevant ist.

3 Der Deskriptor: drei Stufen

Die Konstruktion trennt bewusst die schnelle, kartierbare Messgröße von der physikalisch definierten Kovalenz und verbindet beide über eine Kalibrierung. Damit ist der Deskriptor sowohl hochdurchsatzfähig als auch in der Grundlagenliteratur verankert.

|  |  |  |  |
|----|----|----|----|
| **Stufe** | **Definition** | **Eigenschaften und Grenzen** | **Umfang** |
| D1 – operativ | Normierte O-K-Vorkantenfläche pro d-Loch: I\*(x) = A_pre / (h · N_cont). A_pre nach Untergrundabzug in einem serienweit identischen Energiefenster, N_cont Normierung auf den atomaren Kontinuumsbereich, h die an derselben Position aus dem TM-L-Fit bestimmte Lochzahl. | Schnell (Minuten), an jeder Waferposition messbar, damit kartierbar. Misst Hybridisierung in den unbesetzten Zuständen – ein serieninterner Relativmaßstab, keine absolute Kovalenzskala. | Alle 100–250 Positionen des Gradientenwafers. |
| D2 – verankernd | CI-Clustermodell-Analyse: Fit von TM-2p-Rumpfniveau-Photoemission (Satellitenstruktur) und/oder TM-L2,3-XAS mit den Parametern Δ, U_dd und Transferintegral pdσ. Daraus das Ligandenlochgewicht w_L = β² + 2γ² des Grundzustands \|ψ⟩ = α\|d^n⟩ + β\|d^(n+1)L⟩ + γ\|d^(n+2)L²⟩. | Physikalisch definierte Kovalenz im Sinne der Grundlagenliteratur (Fujimori/Minami 1984, Bocquet 1992/1996). Aufwendig: Stunden pro Punkt, Fit mit begrenzten Freiheitsgraden. | 6–10 Stützstellen je Serie, über den Kompositionsbereich verteilt. |
| D3 – kalibriert | Regression D1 ↔ w_L über die Stützstellen; die resultierende Kalibrierkurve überträgt den schnellen Vorkantenmaßstab in eine CI-verankerte Kovalenz w_L^cal(x) samt Unsicherheit. | Das ist die Größe, die in die Korrelation mit E_V eingeht. Sie erfüllt die Forderung, den Deskriptor gegen Clustermodell-Analyse zu kalibrieren statt gegen Vorkantenintensität allein. | Alle Positionen, mit propagierter Unsicherheit aus D1 und D2. |

Ergebnis ist eine Kovalenzkarte w_L^cal(x) mit Unsicherheiten – und eine explizite Aussage darüber, welcher Teil davon gemessen (D2), welcher übertragen (D3) und welcher nur relativ (D1) ist.

4 Mess- und Auswerteprotokoll

• Normierung: Vorkantenfläche nach Abzug eines Arctan-/Stufenuntergrunds in einem serienweit identischen Energiefenster, normiert auf den atomaren Kontinuumsbereich derselben Messung. Fenstergrenzen werden vor der Auswertung festgelegt und nicht nachträglich optimiert.

• Lochzahl: h wird an jeder Position aus dem TM-L2,3-Fit derselben Messung bestimmt, nicht aus der Nominalstöchiometrie – sonst wird die Valenzänderung in den Kovalenzdeskriptor hineingerechnet.

• Zwei Detektionskanäle gleichzeitig (Elektronenausbeute und Fluoreszenz- bzw. inverse partielle Fluoreszenzausbeute), um Oberflächen- gegen Volumeninformation zu prüfen und Sättigungs- bzw. Selbstabsorptionseffekte zu erkennen.

• CI-Fit: Startparameter aus den tabellierten Werten der Referenzliteratur \[3, 4, 5, 9\]; Freiheitsgrade begrenzen (pdπ/pdσ fest, Ligandenfeld aus der L-Kante), Fitqualität und Parameterkovarianz berichten. Werkzeuge: Ladungstransfer-Multiplettrechnung \[14\] für die L-Kanten, Wannier-basierte Multiplett-Ligandenfeldtheorie \[15, 16\] für die anspruchsvolleren Fälle; die Festlegung erfolgt an einem Referenzsystem mit publizierten Parametern.

• Fehlerbudget: Statistik, Normierungsfenster, Untergrundmodell, h-Bestimmung und Fitparameterkovarianz werden getrennt ausgewiesen und in w_L^cal propagiert. Ein Deskriptorwert ohne Unsicherheit wird nicht berichtet.

• Kontrollen je Strahlzeit: Dosisreihen gegen Photoreduktion, Referenzprobe bekannter Stöchiometrie, Wiederholmessung an einer Position nach Abschluss der Karte.

5 Systemspezifische Anpassungen

STF: Verdünntes Fe in einer d0-Matrix – der Fe-Beitrag zur Vorkante muss vom Ti-Beitrag getrennt werden (getrennte Fe-L- und Ti-L-Messung, Vorkantendekomposition). CI-Parameter für Fe in SrTiO3 sind unpubliziert; Startwerte aus der d0-Systematik \[4\] und den Ferrat-Endpunkten \[3\].

PCMO: Mn-Multiplett mit Jahn-Teller-Verzerrung; CI-Anker existieren nur für die La-Manganite, ein PCMO-Parametersatz ist eigener Projektbeitrag.

LSFO: Die Serie kreuzt das Vorzeichen von Δ. Im Bereich negativer Ladungstransferenergie sättigt w_L – hier ist die Deskriptorformulierung explizit umzustellen (ligandenlochdominierter Grundzustand), und Monotonie ist nicht zu erwarten. Das ist die konzeptionell reichste Achse des Portfolios und zugleich die schärfste Prüfung des Deskriptorbegriffs.

LSCO: Spinzustandsübergänge verändern die Multiplettstruktur unabhängig von der Kovalenz; 10Dq und Spinzustand müssen mitgefittet werden, sonst wird ein Spinzustandswechsel als Kovalenzänderung fehlgedeutet.

YBCO: platzaufgelöste Auswertung (Kette, Ebene, Apex) und Vorsicht bei Rumpfniveaufits wegen nichtlokaler Schirmung \[10\]; gegebenenfalls Mehrplatz-Cluster.

GDC: kein 3d-Clustermodell, sondern das 4f-Anderson-Impurity-Modell in der Fuggle-Gunnarsson-Schönhammer-Tradition \[6\]. Deskriptor-Analogon sind die Hybridisierungsstärke und die f-Besetzung; die Übertragbarkeit der Deskriptorformulierung über die Bindungsklassen hinweg ist hier der eigentliche Test.

6 Verknüpfung mit der Leerstellenbildungsenergie: sechs Wege

|  |  |  |  |
|----|----|----|----|
| **Weg** | **Prinzip** | **Was er leistet** | **Einschränkung** |
| W1 | Direkt experimentell: Gas-Titration auf dem Gradientenwafer. Äquilibrierung bei definiertem pO2 und T, ortsaufgelöste δ-Bestimmung, van-’t-Hoff-Auswertung über oxidierende und reduzierende Bedingungen → ΔH_red(x), regressiert gegen w_L^cal(x). | Trägt die Beweislast. Deskriptor und Zielgröße stammen aus derselben Probe, demselben Wachstumslauf und denselben Positionen. | Kalibrierung auf absolutes δ nötig (chemische Kapazität, chemische Expansion); Dosiskontrolle zwingend. |
| W2 | Mikroskopisches Argument über Δ: Eine Sauerstoffleerstelle gibt zwei Elektronen ab. Wo diese hingehen, entscheidet die Ladungstransferenergie – bei kleinem oder negativem Δ ist der Grundzustand bereits ligandenlochdominiert, die Reduktion also billiger. Δ ist damit die mikroskopische Größe, deren Bandstruktur-Näherung das „O-2p-Bandzentrum“ der Katalyseliteratur ist. | Liefert die theoretische Begründung und die Richtung der erwarteten Korrelation (E_V fällt mit steigendem w_L bzw. fallendem Δ) – und verbindet die Deskriptorliteratur mit ihrer eigentlichen Grundlage. | Im Regime negativer Δ sättigt w_L; dort ist Monotonie nicht zu erwarten, sondern eine physikalisch begründete Grenze. |
| W3 | Thermochemische Zerlegung: E_V als Summe aus Bindungs-, Madelung- und Relaxationsbeiträgen; Kovalenz senkt den ionischen (Madelung-)Anteil und verschiebt die Bilanz. | Verbindet die Messung mit den etablierten Deskriptorformalismen (Deml, Wexler) und macht Beiträge trennbar. | Rein rechnerisch; nur als Interpretationsrahmen, nicht als Beleg. |
| W4 | Theorieinterne Korrelation: E_V und w_L aus derselben DFT+U/Hybrid-Wellenfunktion (projizierte Besetzungen) berechnen. | Konsistenzprüfung: Stimmt die gemessene Steigung mit der gerechneten überein, ist die Kette geschlossen; weicht sie ab, ist das ein eigenes Ergebnis. | U-Abhängigkeit der projizierten Besetzungen sauber dokumentieren. |
| W5 | Chemische Expansion: Gitterparameter- bzw. Krümmungsantwort auf δ, ortsaufgelöst per HT-XRD; Kovalenz steuert die mechanische Antwort mit. | Unabhängiger Kanal auf dieselbe Zielgröße, vollständig kartierbar und ohne Vakuumbeschränkung. | In epitaktischen Filmen anisotrop und verspannungsgekoppelt – Kalibrierrisiko. |
| W6 | Elektrochemisch: chemische Kapazität liefert ∂δ/∂μ_O; die μ_O-Skala ist genau die Achse, auf der Δ die Redoxenergetik festlegt. | Präziseste δ-Messung an Filmen und der beste absolute Ankerpunkt für W1. | Erfordert ionenleitenden Substratstapel – nur auf dedizierten Kalibrierwafern, nicht auf der epitaktischen Gradientenserie. |

Arbeitsteilung: W1 trägt die Beweislast, weil Deskriptor und Zielgröße ko-lokalisiert gemessen werden. W2 liefert die theoretische Begründung – und zugleich die Brücke, die in der Deskriptorliteratur der Katalyse meist übersprungen wird: Das dort verwendete O-2p-Bandzentrum ist die Bandstruktur-Näherung derselben Größe, die im Clustermodell als Δ auftritt. W4 prüft die Konsistenz gegen die Rechnung, W3, W5 und W6 sind Stützkanäle, wobei W6 zugleich den absoluten Ankerpunkt für W1 liefert.

7 Statistische Prüfung und Falsifikationskriterien

Die zentrale Auswertung ist die Regression von ΔH_red gegen w_L^cal innerhalb einer Serie, berichtet mit Steigung, Konfidenzintervall und Bestimmtheitsmaß. Entscheidend ist jedoch der Modellvergleich: Der Deskriptor muss einfachere Kandidaten schlagen – formale Valenz, Toleranzfaktor, O-2p-Bandzentrum und die unkalibrierte Vorkantenfläche allein. Gelingt das nicht, ist er kein Deskriptor, und das ist als Ergebnis zu berichten.

Vorab festgelegte Falsifikationskriterien: (i) Keine monotone Beziehung innerhalb einer Familie bei kontrollierter Lochzahl – der Deskriptor scheitert bereits serienintern. (ii) Familienübergreifend deutlich verschiedene Steigungen – der Deskriptor ist nur serienintern gültig; das bleibt nützlich, muss aber ausdrücklich so benannt werden. (iii) Bruch der Monotonie beim Übergang in das Regime negativer Δ – erwartet und physikalisch begründet, daher kein Scheitern, sondern eine Grenze der Gültigkeit, die selbst kartiert wird.

Offene Punkte vor der ersten Strahlzeit: Festlegung des Fitwerkzeugs an einem Referenzsystem mit publizierten Parametern; Prüfung der exakten Parametertabellen der Grundlagenarbeiten am Volltext (Verlagszugänge aus der Arbeitsumgebung gesperrt); Entscheidung, ob die 2p-Rumpfniveau-Messung an derselben Endstation wie die NEXAFS-Karte erfolgen kann – davon hängt ab, ob D2 und D1 wirklich ko-lokalisiert sind oder über getrennte Strahlzeiten verknüpft werden müssen.

8 Referenzen

*Verifikationsstand (10.08.2026): Alle Angaben dieser Liste wurden gegen Verlags- und Repositoriumseinträge geprüft; \[1\]–\[4\], \[8\], \[9\] und \[11\]–\[13\] werden zusätzlich bereits in den Antragsdokumenten geführt. Einschränkung wie im übrigen Portfolio: Direktzugriffe auf Verlagsseiten sind aus dieser Arbeitsumgebung gesperrt, die Prüfung stützt sich auf indizierte Titelangaben mehrerer unabhängiger Quellen – die Orthografie der Autorennamen in \[6\] (Żołnierek, Lässer, Schönhammer) ist am Volltext gegenzulesen.*

\[1\] J. Zaanen, G. A. Sawatzky, J. W. Allen, Band gaps and electronic structure of transition-metal compounds. Physical Review Letters 55, 418–421 (1985).

\[2\] A. Fujimori, F. Minami, Valence-band photoemission and optical absorption in nickel compounds. Physical Review B 30, 957–971 (1984).

\[3\] A. E. Bocquet, T. Mizokawa, T. Saitoh, H. Namatame, A. Fujimori, Electronic structure of 3d-transition-metal compounds by analysis of the 2p core-level photoemission spectra. Physical Review B 46, 3771–3784 (1992).

\[4\] A. E. Bocquet, T. Mizokawa, K. Morikawa, A. Fujimori, S. R. Barman, K. Maiti, D. D. Sarma, Y. Tokura, M. Onoda, Electronic structure of early 3d-transition-metal oxides by analysis of the 2p core-level photoemission spectra. Physical Review B 53, 1161–1170 (1996).

\[5\] T. Mizokawa, A. Fujimori, Electronic structure and orbital ordering in perovskite-type 3d transition-metal oxides studied by Hartree-Fock band-structure calculations. Physical Review B 54, 5368–5380 (1996).

\[6\] J. C. Fuggle, F. U. Hillebrecht, Z. Zolnierek, R. Lasser, Ch. Freiburg, O. Gunnarsson, K. Schonhammer, Electronic structure of Ce and its intermetallic compounds. Physical Review B 27, 7330–7341 (1983).

\[7\] D. D. Sarma, N. Shanthi, S. R. Barman, N. Hamada, H. Sawada, K. Terakura, Band theory for ground-state properties and excitation spectra of perovskite LaMO3 (M = Mn, Fe, Co, Ni). Physical Review Letters 75, 1126–1129 (1995).

\[8\] S. Nimkar, D. D. Sarma, H. R. Krishnamurthy, S. Ramasesha, Mean-field results of the multiple-band extended Hubbard model for the square-planar CuO2 lattice. Physical Review B 48, 7355–7363 (1993).

\[9\] T. Saitoh, A. E. Bocquet, T. Mizokawa, A. Fujimori, Systematic variation of the electronic structure of 3d transition-metal compounds. Physical Review B 52, 7934–7938 (1995).

\[10\] M. A. van Veenendaal, G. A. Sawatzky, Nonlocal screening effects in 2p x-ray photoemission spectroscopy core-level line shapes of transition metal compounds. Physical Review Letters 70, 2459–2462 (1993).

\[11\] F. M. F. de Groot, X-ray absorption and dichroism of transition metals and their compounds. Journal of Electron Spectroscopy and Related Phenomena 67, 529–622 (1994).

\[12\] F. Frati, M. O. J. Y. Hunault, F. M. F. de Groot, Oxygen K-edge X-ray Absorption Spectra. Chemical Reviews 120, 4056–4110 (2020).

\[13\] J. Suntivich, W. T. Hong, Y.-L. Lee, J. M. Rondinelli, W. Yang, J. B. Goodenough, B. Dabrowski, J. W. Freeland, Y. Shao-Horn, Estimating Hybridization of Transition Metal and Oxygen States in Perovskites from O K-edge X-ray Absorption Spectroscopy. The Journal of Physical Chemistry C 118, 1856–1863 (2014).

\[14\] E. Stavitski, F. M. F. de Groot, The CTM4XAS program for EELS and XAS spectral shape analysis of transition metal L edges. Micron 41, 687–694 (2010).

\[15\] M. W. Haverkort, M. Zwierzycki, O. K. Andersen, Multiplet ligand-field theory using Wannier orbitals. Physical Review B 85, 165113 (2012).

\[16\] M. W. Haverkort, Quanty for core level spectroscopy – excitons, resonances and band excitations in time and frequency domain. Journal of Physics: Conference Series 712, 012001 (2016).
