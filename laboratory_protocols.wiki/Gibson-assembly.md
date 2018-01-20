# Introduction
This protocol is adapted from the "one-step isothermal DNA assembly" method originally published by [Gibson _et al_](http://www.ncbi.nlm.nih.gov/pubmed/19363495).  Below you will find experimental details for running a Gibson Assembly.  For assistance and instruction in designing your construct, consult the [Gibson manual](https://www.neb.com/~/media/Catalog/All-Products/0AA961B294E444AFBEDD5C4A904C76E6/Datacards%20or%20Manuals/manualE2611.pdf) from NEB.

The Gibson Assembly is a very robust technique.  It is completely unnecessary to clean up DNA prior to performing an assembly reaction.  I have gotten successful assembly using digested vector where the restriction enzyme has simply been heat inactivated, and mixing this with a DNA insert strait from a colony PCR reaction.  The 1:1 molar ratio is a good range for maximal efficiency, but the assembly will still work even if the ratio is off.


# The Gibson Assembly
* Thaw a 15 μL [Gibson master mix](#gibson-assembly-master-mix) aliquot at room temperature.
* Add the DNA fragments to be assembled to the Gibson master mix aliquot.
  * The final volume of DNA fragments added to the master mix should be 5 μL.  The total reaction volume is 20 μL, _q.s._ with H<sub>2</sub>O if necessary.
  * The DNA fragments should be equimolar relative to one another. Aim for ≈ 0.025 pmol of each DNA fragment to be assembled.
  * Perform a ~100-fold over digest of your vector  prior to DNA fragment insertion.  This will ensure very minimal background.
* Incubate the reaction at 50 °C for 60 min.



# Recipes
### 5X ISO buffer
25% [wt/vol] PEG-8000, 500 mM Tris-HCl pH 7.5, 50 mM MgCl<sub>2</sub>, 50 mM DTT, 1 mM each of the four dNTPs, 5 mM NAD

To make 6 mL, add:

| quantity | chemical |
| :--- | :--- |
| 3 mL | 1 M Tris-HCl pH 7.5 |
| 150 μL | 2 M MgCl<sub>2</sub> |
| 60 μL | 100 mM dATP (New England Biolabs catalogue # N0446S) |
| 60 μL | 100 mM dTTP (New England Biolabs catalogue # N0446S) |
| 60 μL | 100 mM dGTP (New England Biolabs catalogue # N0446S) |
| 60 μL | 100 mM dCTP (New England Biolabs catalogue # N0446S) |
| 300 μL | 1 M DTT (Sigma-Aldrich catalogue # 43815) |
| 1.5 g | PEG-8000 (Sigma-Aldrich catalogue # 89510) |
| 300 μL | 100 mM NAD (Sigma-Aldrich catalogue # N6522) |
| _q.s._ to 6 mL with water. |

* aliquot out 320 μL and store at -20 °C.


### Gibson Assembly Master Mix
To make 1.2 mL, add:

| quantity | chemical |
| :--- | :--- |
| 699 μL | H<sub>2</sub>O |
| 320 μL | [5X ISO buffer](#5X-ISO-buffer) |
| 0.64 μL | 10 U/μL T5 exonuclease (Epicentre<sup>†</sup>) |
| 20 μL | 2 U/μL Phusion DNA polymerase (NEB<sup>‡</sup>) |
| 160 μL | 40 U/μL Taq DNA ligase (NEB) |

* aliquot out 15 μL in PCR tubes and store at -20 °C.
* This assembly mixture can be stored at -20 °C for at least one year. The enzymes remain active following ≈ 10 freeze-thaw cycles.
* This recipe is ideal for the assembly of DNA molecules with 20-150 bp overlaps. For DNA molecules overlapping by larger than 150 bp, prepare the assembly mixture by using 3.2 μL of 10 U/ μL T5 exonuclease.

<sup>†</sup> Epicentre and NEB both sell T5 Exonuclease. Their unit definitions are very similar, thus should be interchangeable in theory. The original citation uses Epicentre.

<sup>‡</sup> The brand and type of polymerase used is very important.  For example, the assembly reaction has significantly reduced efficiency when the master mix is prepared with Phusion from Thermo.  I cannot know the exact reason for this, but I suspect that proprietary differences in the manufacturers formula are responsible for this puzzling observation.