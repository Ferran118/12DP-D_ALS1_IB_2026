# Tarea 2.1.1: Disease Project — ALS1

## Genetic Heterogeneity of Amyotrophic Lateral Sclerosis (ALS)

Amyotrophic Lateral Sclerosis (ALS) is a genetically heterogeneous neurodegenerative disorder, meaning that the disease phenotype is not linked to a single genetic locus, but can be triggered by pathogenic mutations across multiple distinct genes (e.g., *SOD1*, *C9orf72*, *FUS*, and *TARDBP*). Consequently, the precise genetic cause can vary significantly between patients.

---

## 1. Genetic Level Causation

### The *SOD1* Gene and Locus
Our study focuses on the **SOD1** (Superoxide Dismutase 1) gene, located at chromosome 21 at locus **21q22.11** ([OMIM 147450](https://omim.org/entry/147450)). 

*SOD1* was the first gene identified as a causative agent in ALS. Pathogenic variants in *SOD1* account for approximately 12–20% of familial ALS (fALS) cases and 1–2% of sporadic ALS (sALS) cases worldwide [1].

### Genetic Heterogeneity
Genetic heterogeneity means that the disease isn't caused by just one single genetic mistake, but can be triggered by many different ones; the patient's DNA mutation can vary from person to person. We focus on the *SOD1* gene as one of the key mutated genes driving the pathology.

### Mutation Profile
Scientists have identified over 150 distinct mutations in the *SOD1* gene linked to ALS [2]. 
* The vast majority are **missense mutations**—single nucleotide substitutions that lead to an amino acid replacement in the resulting polypeptide chain.
* A classic example is the well-studied **A4V mutation** (substitution of alanine for valine at position 4), which is associated with a rapidly progressive disease phenotype [1].

### Modes of Inheritance
* **Autosomal Dominant (AD):** The primary mode of inheritance for *SOD1*-linked ALS. A single inherited copy of the mutated allele from one parent is sufficient to trigger disease pathogenesis (e.g., the A4V variant) [4].
* **Autosomal Recessive (AR):** Exceptionally, certain *SOD1* variants display recessive inheritance, requiring two copies of the mutated allele (one from each parent) for disease expression (e.g., homozygous D90A mutation) [4].

---

## 2. Protein Level: The Cu/Zn-SOD Enzyme

The *SOD1* gene provides the instructions for creating the **copper/zinc superoxide dismutase (Cu/Zn-SOD)** enzyme [5].

### Composition & Quaternary State
* **Composition:** The mature, healthy protein consists of **154 amino acids** [5].
* **Quaternary State:** It naturally operates as a **homodimer**, meaning two identical SOD1 protein subunits must bind together non-covalently to function properly [5]. *(Dimerization is the biological process where two identical monomer subunits combine to form a single molecular complex).*

### Cofactors
Each SOD1 subunit requires the binding of two essential metal ions [5]:
* **Copper ion ($\text{Cu}^{2+}$):** Critical for the enzyme's catalytic antioxidant activity.
* **Zinc ion ($\text{Zn}^{2+}$):** Essential to promote dimerization and stabilize the protein's native three-dimensional folding.

### Normal Physiological Function
Physiologically, Cu/Zn-SOD functions as a vital antioxidant metalloenzyme [5]:
1. **Free Radical Scavenging:** Destroys superoxide radicals ($\text{O}_2^-$) that are normally produced within cells and are toxic to biological systems [5].
2. **$\text{H}_2\text{S}$ Detoxification:** Catalyzes the oxidation of hydrogen sulfide ($\text{H}_2\text{S}$) to sulfate, detoxifying $\text{H}_2\text{S}$ and limiting the accumulation of reactive sulfur species (RSS) such as persulfides and polysulfides [5].

### Pathological Mechanism (Fibrillar Aggregation)
The structural integrity of SOD1 relies heavily on its bound zinc ions and an internal structural clip known as an **intramolecular disulfide bond** [3, 5]. 
* In the absence of either this disulfide bond or the bound zinc, both wild-type and ALS1-associated mutant SOD1 proteins become structurally unstable.
* Without its zinc and structural clips, the protein falls apart into unstable monomers and has a strong tendency to form **fibrillar aggregates/clumps**.
* These insoluble aggregates exert severe **cytotoxic effects**, ultimately driving motor neuron degeneration [3].

---

## 3. Structural Level: Destabilization and Aggregation

At the structural level, mutant SOD1 proteins undergo severe conformational changes that lead directly to disease pathology [3].

* **Normal Structure:** Healthy SOD1 folds into a highly stable, eight-stranded anti-parallel $\beta$-barrel (a "Greek key" structural motif) [6].
* **Mutant Instability:** ALS-associated genetic mutations disrupt the protein's native folding [3]. They frequently impair the protein's ability to hold onto its zinc ion or form its crucial intrasubunit disulfide bond. This severe structural instability ultimately triggers **dimer dissociation**, forcing the stable complex to break apart into vulnerable monomers [3].
* **Misfolding and Aggregation:** The dissociation of the dimer and the unfolding of the protein expose hydrophobic regions that are normally safely buried within the native structure [3]. These destabilized, misfolded SOD1 monomers inappropriately interact with one another, assembling into insoluble oligomers and large fibrillar aggregates [3].

---

## 4. Functional Level: Toxic Gain-of-Function

The functional breakdown of SOD1 creates a lethal cellular environment specifically targeting motor neurons [3].

* **Normal Function:** Healthy SOD1 acts as an essential cellular antioxidant. It scavenges highly reactive superoxide radicals ($\text{O}_2^-$)—toxic byproducts of mitochondrial energy production—and neutralizes them into ordinary molecular oxygen ($\text{O}_2$) and hydrogen peroxide ($\text{H}_2\text{O}_2$) [5].
* **The ALS1 Mechanism (Toxic Gain-of-Function):** While some loss of antioxidant function occurs, ALS1 is driven primarily by a **toxic gain-of-function** [3, 4]. The disease is not caused by the absence of normal SOD1, but by the newly acquired, harmful properties of the mutated, misfolded protein [3].
* **Motor Neuron Death:** The structurally misfolded SOD1 aggregates physically accumulate in the cytoplasm of motor neurons [3]. These aggregates choke the cell's internal machinery:
  * Disrupt axonal transport
  * Impair mitochondrial function
  * Induce severe endoplasmic reticulum (ER) stress
  
  This overwhelming cellular toxicity eventually triggers **apoptosis** (programmed cell death), severing the communication network between the brain and muscles and resulting in fatal paralysis [3].

---

## Bibliography

### Paper References
1. Gagliardi D, Ripellino P, Meneri M, et al. Clinical and molecular features of patients with amyotrophic lateral sclerosis and SOD1 mutations: a monocentric study. *Front Neurol*. 2023; 14: 1169689.
2. Suthar SK, Lee SY. The role of superoxide dismutase 1 in amyotrophic lateral sclerosis: identification of signaling pathways, regulators, molecular interaction networks, and biological functions through bioinformatics. *Brain Sci*. 2023; 13(1): 151.
3. Redler RL, Dokholyan NV. The complex molecular biology of amyotrophic lateral sclerosis (ALS). *Prog Mol Biol Transl Sci*. 2012; 107: 215-262.

### Database References
4. Online Mendelian Inheritance in Man (OMIM). Amyotrophic lateral sclerosis 1; ALS1 (Entry 147450). *OMIM*. 2023. Available from: https://omim.org/entry/147450
5. The UniProt Consortium. Superoxide dismutase [Cu-Zn] (Entry P00441). *UniProtKB*. 2023. Available from: https://www.uniprot.org/uniprotkb/P00441/entry
6. Protein Data Bank (PDB). Crystal structure of wild-type human Cu, Zn superoxide dismutase (PDB 1HL5). *RCSB PDB*. 2003. Available from: https://www.rcsb.org/structure/1HL5