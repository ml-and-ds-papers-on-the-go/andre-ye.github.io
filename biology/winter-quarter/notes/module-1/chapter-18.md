[Home](https://andre-ye.github.io) > [Biology Navigation](https://andre-ye.github.io/biology/biology_navigation) > [Biology Content](https://andre-ye.github.io/biology/biology_navigation#biology-content) > Module 1: Gene Expression, Development, Technologies > Chapter 18 Textbook Notes

## Textbook Notes: Chapter 18, "Control of Gene Expression in Bacteria"
Andre Ye, 1/6/21

<br>

---

<br>

### Navigation
- [Introduction](#introduction)
- [18.1: An Overview of Gene Regulation and Information Flow](#181-an-overview-of-gene-regulation-and-information-flow)
  * [Mechanisms of Regulation](#mechanisms-of-regulation)
  * [Metabolizing Lactose - A Model System](#metabolizing-lactose-a-model-system)
- [18.2: Negative and Positive Control of Transcription](#182-negative-and-positive-control-of-transcription)
  * [A Gene Needed to Regulate Lactose Metabolism](#a-gene-needed-to-regulate-lactose-metabolism)
  * [Negative Control of Lactose Utilization Genes](#negative-control-of-lactose-utilization-genes)
  * [The Operon Model](#the-operon-model)
    + [Key Ideas from the Operon Model](#key-ideas-from-the-operon-model)
  * [Positive Control of Lactose Utilization Genes](#positive-control-of-lactose-utilization-genes)
    + [Positive Control by CAP Regulation](#positive-control-by-cap-regulation)
    + [Control by Inducer Exclusion](#control-by-inducer-exclusion)
  * [Why Has the *lac* Operon Model Been SO Important Scientifically?](#why-has-the-lac-operon-model-been-so-important-scientifically)
  * [The *trp* Operon: A Twist on Negative Control](#the-trp-operon-a-twist-on-negative-control)
- [18.3: Global Gene Regulation](#183-global-gene-regulation)

<br>

---

<br>

### Introduction
- Imagine seeing an orchestra; all the instruments play all at once, uncoordinated. It's not music.
- Similarly, if a bacterial cell expressed all its genes all the time, the organism would not function properly.
- Bacteria cells control the activity, or expression, of their genes.
- **Gene expression** is the process of converting information from DNA to molecules that function.

<br>

---

<br>

### 18.1: An Overview of Gene Regulation and Information Flow
- Bacterial organisms in your intestine compete for space and nutrients.
  - The cell must use resources efficiently.
- The cell needs to orchestrate and regulate which proteins they produce in accordance with reactions from the environment.

#### Mechanisms of Regulation
- Gene expression can be controlled at any of the steps in the Central Dogma:
  - DNA to mRNA, *transcriptional control*. The cell only makes mRNAs for proteins it needs. Regulatory proteins affect RNA polymerase's ability to bind to the promoter and initiate transcription.
  - mRNA to protein, *translational control*. The cell prevents mRNAs for unneeded proteins from being translated. Regulation of mRNA's life span or ability is used.
  - protein to activated protein, *post-translational control*. Modifications required to activate proteins can be denied.
- All of these forms of control appear in bacteria, but this textbook will only focus on *transcriptional control*.

| Type | Speed | Energy |
| --- | --- | --- |
| Transcriptional | Not too fast. | Saves energy of the cell because it controls gene expression before the cell spends too many resources on it. |
| Translational | Faster changes than transcriptional, because mRNA has already been made and the *amount* of proteins can be regulated. | More energy than transcriptional, because mRNAs are being made when they may not need to be. |
| Post-translational | The fastest response of all mechanisms; only one step is needed to inactivate or activate a protein. | Energetically inefficient; the entire protein needs to be made first. |

- Clear **tradeoff between efficiency and speed**.
- **Constutively transcribed** genes are ones that are transcribed all the time.
  - e.g. enzymes required for glycolysis.
- Genes are not just 'on' or 'off', instead, the *level* of expression varies.

#### Metabolizing Lactose - A Model System
- Jacques Monod and Francois Jacob used *E. coli* to study regulation of lactose metabolism.
- *E. coli* uses many sugars for ATP production; glucose is its preferred carbon source.
  - Lactose can also be used in the absence of glucose.
  - To use it, *E. coli* uses **galactoside permease* to transport the sugar into the cell.
  - Enzyme **beta-galactosidase** breaks down lactose into glucose and galactose.
- ***E. coli* produces a high level of beta-galactosidase only when lactose is present.***
  - Lactose regulates the gene for beta-galactosidase; lactose is an **inducer**, or a small molecule that triggers transcription of a gene.
- *E. coli* did not produce beta-galactosidase when *both* glucose and lactose were present.

<br>

---

<br>

### 18.2: Negative and Positive Control of Transcription
- Transcription of any gene can be regulated through:
  - **Negative control**. A **repressor** (a regulatory protein) binds to DNA and stops transcription.
  - **Positive control**. An **activator** (a regulatory protein) binds to DNA and *triggers* transcription.
- Genes are under both negative and positive control.

#### A Gene Needed to Regulate Lactose Metabolism
- Monod and Jacob isolated and analyzed mutants of *E. coli* unable to use lactose.
- Three types of mutants:
  - Cells unable to cleave lactose, even when lactose was in the medium and transported into cells. These mutants lacked functioning beta-galactosidase proteins. Genotype `lacZ-`
  - Cells failed to accumulate lactose in the cell. These mutants lacked galactosidase permease. Genotype `lacY-`
  - Cells can cleave lactose even if lactose is absent. Cells could produce beta-galactosidase and galactoside permease, but could not regulate their expression. Genotype `lacI-`
- **Constitutive mutants** are cells that produce a product *consistently* at all times instead of regulating its expression.
- **`lacI` prevents the transcription of `lacZ` and `lacY` when lactose is absent.**
  - `lacI` is supposed to act as a negative regulator; thus, lactose probably is an inducer, interacting with `lacI`.

#### Negative Control of Lactose Utilization Genes
- Leo Szilard suggested `lacI` codes for a *protein product* that represses transcription of `lacZ` and `lacY`.
  - Genetic mapping suggests `lacZ` and `lacY` are transcribed together.
- `lacI` produces a repressor protein that binds to DNA and overlaps the promoter for both the `lacZ` and the `lacY` genes.
  - This prevents RNA polymerase by interfering with the binding.
- Lactose binds to the repressor, changes its shape, and causes the repressor to release from its binding site in the DNA.
  - Lactose "releases" the "brake" (negative control repressor)
- Constitutive transcription happens when the functional repressor is absent (no "brake").
- **To test out this hypothesis of negative control;**
  - Added a functioning copy of `lacI` repressor to `lacI-` mutants.
  - Beta-galactosidase production stopped.
- **Lactose acts as an inducer by causing the repressor to release from DNA and ending negative control.**

#### The Operon Model
- Genes for beta-galactosidase and galactoside permease are controlled *together* and transcribed into a single mRNA.
  - An mRNA that codes for two or more polypeptides is a **polycistronic mRNA**.
  - (Most bacteria mRNAs are polycistronic; almost all eukaryotic mRNAs are not.)
- An **operon** is a set of coordinately regulated bacteria genes transcribed into *one* polycistronic mRNA.
  - Genes involved in lactose metabolism are the **lac operon**.
- `lacA` codes for the enzyme transacetylase; allows certain types of sugars to be exported from the cell when they are too abundant.

# Key Ideas from the Operon Model
1. `lacZ`, `lacY`, and `lacA` genes are adjacent and transcribed as *one* mRNA. This is known as **cotranscription**.
2. The repressor protein encoded by `lacI` binds to a specific sequence in DNA and prevents transcription of the *lac* operon genes. `lacI` is expressed constitutively. The repressor binds to a DNA sequence in the *lac* operon called the **operator**.
3. The inducer (lactose) binds to the repressor and changes its shape, causing it to come off the DNA. Control over protein function like this is **allosteric regulation**.
  - Allosteric regulation: a small molecule binds to a protein and changes its shape and activity.

#### Positive Control of Lactose Utilization Genes
- Transcription of *lac* operon is reduced when glucose is present.

# Positive Control by CAP Regulation
- **Catabolite activator protein (CAP)** exerts positive control on many operons in *E. coli*.
  - Is transcribed & transcripted constitutively.
- CAP binds to a regulatory sequence of DNA and *increases* the frequency of initiating transcription.
  - CAP promotes the association of the RNA polymerase holoenzyme w/ the promoter.
  - CAP can only be bound to cyclic AMP. When glucose level outside the cell is high, cAMP is inhibited.
  - When glucose level outside a cell is low, cAMP synthesis ramps up. This enables CAP to bind and promote transcription.

# Control by Inducer Exclusion
- Glucose inhibits the transport of sugars other than glucose into the cell.
  - When glucose is abundant, galactoside permease is inhibited.

#### Why Has the *lac* Operon Model Been SO Important Scientifically?
- Many bacterial genes and operons are under negative control by repressor proteins.
- Activator proteins often work by enhancing the binding of RNA polymerase to the promoter.
- Gene transcription is often regulated by contact between regulatory proteins and regulatory sequences in DNA.
- Post-translational control allows for a quick response to changing environments.
  - Activity of repressors can be altered allosterically.

#### The *trp* Operon: A Twist on Negative Control
- The *lac* operon breaks down lactose into component sugars.
  - Operons can also *create* compounds.
- The *trp* operon synthesizes the amino acid tryptophan.
- Each reaction in the multistep biochemical pathway are catalyzed by an enzyme encoded by a *trp* operon gene.
  - 5 enzymes are needed - corresponding to 5 *trp* operon genes.
  - All genes are needed to work together by trnascribing the genes into one polycistronic mRNA.
  - Control of transcription *is mediated by a repressor protein*.
- Genes for tryptophan synthesis should be expressed only when tryptophan is required.
  - Genes need to be turned on when tryptophan is *absent*, instead of when something is *present* (like the *lac* operon).
- The *trp* repressor binds to its operator only when it is bound by tryptophan (its regulator).
  - *lac* repressor binds to the *lac* operator only when it is *not* bound to its operator.
- The repressor no longer binds to the operator when the tryptophan level drops, and the *trp* operon genes are transcribed.
- This is a form of **negative feedback** control.
  - The final product of a pathway inhibits the production of the product.
- The *trp* operon has a **co-repressor** that works *with* the repressor to make it active during allosteric regulation.

<br>

---

<br>

### 18.3: Global Gene Regulation
- Sometimes, one cannot only turn on genes or even operons individually. Bacteria may need to coordinate change.
- **Global gene regulation** is the coordinated regulation of many genes.
  - A **regulon** is a set of separate genes and operons that contain the same regulatory sequences and are controlled by one type of regulatory protein.
  - Regulons can be under *negative* control by a repressor protein or under *positive* control by an activator protein.
  - SOS response regulon: damage to DNA sets off an SOS signal that induces transcriptions of many genes that code for enzymes needed for DNA repair.
- The SOS system is under control of one of *its own genes*.
  - *lexA* codes for the LexA protein, which represses transcription of SOS regulon genes when the cell is healthy; DNA damage makes LexA cleaved and inactivated.
  - Since *lexA* is *part* of the genes, it is also produced. By the time the DNA is repaired, the SOS regulon is restroed by active LexA.
- **Interactions between protein regulators and DNA sequences produce finely tuned control over gene expression.**

<br>

---

<br>

[Back to top](#)
