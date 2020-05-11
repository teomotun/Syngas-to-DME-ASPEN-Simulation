# OPTIMIZATION OF SYNGAS TO DME REACTION

ASPEN Plus was used to develop the process scheme shown below to simulate the conversion of synthesis gas to dimethylether via the following vapor-phase reactions over a Cu-ZnO-Al2O3 catalyst using the PSRK (Peng-Robinson-Soave-Redlich-Kwong) Properties Method. An investment analysis was also done on the plant to determine the ROI.
- - -
![scheme](Screenshots/process_scheme.png)
- - -
## PROBLEM SPECIFICS
- - -

Syn gas containing carbon monoxide and hydrogen in a molar ratio of 1:2 at 25oC and 7 atm
(sream S1) is fed at a molar flow rate of 1,200 kmol/h to a two-stage compressor (B1-B2-B3) that has an intercooler provision (B2) and an isentropic compression efficiency of 72% and 100% mechanical efficiency at both stages (B1 & B3). After leaving the first stage (B1) at a pressure Pint that is to be determined, the compressed syn gas (stream S2) is cooled by a pressurized water stream (S12) to a temperature of 80oC before entering the second stage. The heat exchange between cooling water and syn gas is characterized by a countercurrent exchange (B2) with an overall heat transfer coefficient of 200 kcal/(h.m2.K). In the second stage (B3), the pressure of the syn gas is raised to 50 atm. The pressure Pint is to be determined that minimizes the overall power requirement of the two-stage compressor.

Started off with an analysis assuming that after leaving the two-stage compressor, the
compressed syn gas enters directly into water-cooled, packed-bed reactor (B5) where the vaporphase reactions 1 and 2, occur over a Cu-ZnO-Al2O3 catalyst at 250oC and 50 atm. The rate expressions for Reactions 1 and 2 are given below.
- - -
![params](Screenshots/params.png)
- - -
Alsothe rate basis is catalyst weight, not reactor volume (as implied by the presence of kg in
the units for the reaction rate and rate constants). The reactor is a tubular reactor with the Cu-
ZnO-Al2O3 catalyst packed in a bundle of 500 stainless steel tubings with a bed voidage of 0.39
and a catalyst particle density of 1.3 kg/L. Each tubing has a 0.0762-m diameter and a length,
expected to be within the 2.0−10.0 m range, that is to be determined to achieve a (83 ± 0.05)%
consumption of carbon monoxide in the preliminary analysis. The heat duty of the reactor (Q2)
is taken up by the cooling water stream leaving the two-stage compressor (stream S13).
The reaction mixture is fed to a water-cooled partial condenser (B6-B8) operating at 50 atm and
10oC. Cooling at the partial condenser (B6) is provided by chilled water entering the partial
condenser at 5oC and 20 atm. The mass flow rate of the chilled water (> 60,000 kg/h) is to be
determined. After taking up the heat duty Q1 at the partial condenser (B6), the chilled water
stream (S12) goes to the two-stage compressor to cool the compressed syn gas stream S2. It is
desired to determine the molar flow rates of the various species in the vapor and liquid fractions
(S7 and S8, respectively) leaving the partial condenser.
