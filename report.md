# Manuscript Title: Bioinformatic Analysis of Epimerase Deficiency Galactosemia
**Authors:** Mengxin Lin Huang, Marta Celdrán Abraldes, Elena Alexandra Gae Dumitru, Adrià Cuadros Farré-Escofet  
**Department, Institution, City, Country:** BBI,Polytechnic University of Catalonia, Barcelona, Spain

## Abstract
*Provide a structured abstract covering Background, Results, and Conclusions (Max 350
words).*

## Keywords
[Keyword 1, Keyword 2, Keyword 3, Keyword 4, Keyword 5]

## Background

Galactose is a sugar found mainly in milk and dairy products. The body converts it into glucose so it can be used as energy. Galactosemias are a group of inherited disorders in which this process fails and galactose accumulates in the blood [1].

The *GALE* gene (chromosome 1, 1p36.11) encodes the enzyme UDP-galactose 4-epimerase [3,14]. This enzyme catalyses two reversible reactions: the interconversion of UDP-glucose and UDP-galactose, and of UDP-N-acetylglucosamine and UDP-N-acetylgalactosamine [14,15]. The second reaction is important because these sugars are needed to build glycoproteins and glycolipids [15]. Several alternatively spliced transcripts of *GALE* have been described, and they encode the same protein [15].

Mutations in *GALE* cause epimerase-deficiency galactosemia (EDG, galactosemia type III), an autosomal recessive disorder [2,7]. Three forms of EDG are distinguished according to how widely the enzyme activity is reduced [7,8]. In the generalized form, enzyme activity is profoundly decreased in all tissues tested. Affected infants show hypotonia, poor feeding, vomiting, jaundice, hepatomegaly, liver dysfunction and cataracts, and long-term features can include short stature, developmental delay, sensorineural hearing loss and skeletal anomalies. In the peripheral form, activity is deficient only in red and white blood cells and is normal or near normal in other tissues. In the intermediate form, activity is deficient in blood cells and below 50% of normal in the other cells tested. It has been reported that peripheral and intermediate EDG are difficult to tell apart [7]. Treatment is based on a galactose-restricted diet, which resolves or prevents the acute symptoms but not the developmental delay or learning impairment seen in some patients [7].

Several missense variants in *GALE* have been reported in OMIM, including p.Val94Met [3]. However, it is not fully understood how a single amino-acid change affects the structure and function of the enzyme. In this study, we compared the wild-type and mutant *GALE* sequences, analysed their conservation across species (human, mouse and *Escherichia coli*), and examined the 3D structural environment of the mutated residue using PDB structures. Our aim is to explain how this variant may cause EDG.

## Results

### Identification of the human GALE sequences

The wild-type (WT) CDS search identified the human gene GALE (UDP-galactose-4-epimerase; Gene ID 2582, HGNC:4116, MIM 606953) at locus 1p36.11 on chromosome 1 (NC_000001.11), with the RefSeq record NM_000403.4. The gene has 13 exons and is expressed broadly, with the highest levels in the stomach and duodenum. The WT protein search identified NP_000394.2 (348 aa), the product of this gene, named UDP-galactose 4-epimerase (also listed as UDP-glucose 4-epimerase).

The mutant sequences matched the same records. The mutant CDS had its best hit on NM_000403.4 with 99.90% identity to the WT CDS (1046/1047 nucleotides; query cover 100%, E-value 0.0) and the mutant protein had its best hit on NP_000394.2 with 99.71% identity to the WT protein (347/348 amino acids; query cover 100%, E-value 0.0).

Homologous sequences were selected for the cross-species comparison: for Mus musculus, the gene Gale (CDS NM_001356493.1; protein NP_001343422.1, 347 aa), and for Escherichia coli, the gene galE (protein NP_415280.3, 338 aa, from strain K-12 MG1655; nucleotide record OZ544371.1, from strain RSZYD15081311_A, which is not K-12). The human reference sequences are NM_000403.4 and NP_000394.2 (348 aa).

A blastp search of the E. coli protein against the human protein gave 98% query cover, 52.49% identity and an E-value of 1e-134. In the blastn comparison of the human CDS with OZ544371.1 a genome assembly, chromosome 1, 2 314 235 nt; the aligned segment is at positions 176 507–176 736, the alignment covered 22% of the human CDS (positions 532–761), with 76.19% identity and an E-value of 5e-40. A search against the E. coli genome gave 25% query cover and 71.5% identity. In both cases only a short segment of the human CDS aligned. The protein and the nucleotide sequences come from different E. coli strains.

### Comparison of the WT and mutant sequences

The WT and mutant CDS are both 1047 nt long and differ at one position only, with no gaps (1046/1047 identities, 99.90%). The difference is at position 280, where the WT has G and the mutant has A, a transition (c.280G>A).

The WT and mutant proteins are both 348 aa long and also differ at one position only, with no gaps (347/348 identities, 99.71%). The difference is at position 94, where valine (Val, V) in the WT is replaced by methionine (Met, M), written p.Val94Met. 

Codon 94 occupies nucleotides 280–282, and position 280 is its first base. The G>A change converts GTG (Val) to ATG (Met), so the substitution is missense: the new codon still encodes an amino acid, and the stop codon is unchanged. No nucleotides are inserted or deleted, so the reading frame is not altered.

Valine and methionine are both non-polar, hydrophobic and uncharged, so charge and polarity are the same. They differ in side-chain size and shape. Valine has a short, branched side chain, whereas methionine has a longer, unbranched and more flexible side chain that contains sulfur.

### Conservation across species: CDS

The CDS could not be compared in a single three-way alignment, because blastn aligned only 22% of the human CDS with the E. coli sequence. Human vs mouse and human vs E. coli were therefore aligned separately, with the human WT CDS as the query in both runs (Table 1).

Table 1. Identity and coverage of the WT human sequences against mouse and E. coli.

| Comparison | 	Level | Query cover | Identity | 	Identity per 60-position block |
|---|---|---|---|---|
| *Human vs mouse* | CDS | 99% (positions 7–1047) | 89.15% | 80.00–96.67% (18 blocks) |
| *Escherichia coli* | CDS | 	22% (positions 532–761) | 76.19% | 74.0–80.0% (4 blocks) |
| *Human vs mouse* | Protein | 99% | 93.93% (325/346) | 91.67–96.67% (6 blocks) |
| *Human vs E. coli* | Protein | 98% | 52.49% (179/341) | 40.48–80.00% (6 blocks) |

Human and mouse CDS align over almost their whole length (E-value 0.0). Identity differs between blocks: the blocks at positions 367–426 and 847–906 have two and three mismatches per 60 nt, whereas the block at positions 547–606 has 12 mismatches. For E. coli, blastn aligned only one segment of about 230 nt (positions 532–761, E-value 5e-40; 176/231 identities, 76.19%). Outside this segment the human CDS has no alignment with the E. coli sequence. This segment corresponds approximately to residues 178–254 of the protein.

Human vs mouse shows 113 substitutions (928/1041 identities, no gaps), spread along the sequence; 88 of them are at the third base of a codon, 12 at the first and 13 at the second. The first six nucleotides of the human CDS are not aligned, and the mouse CDS is 1044 nt long against 1047 nt for human. Within the segment aligned with E. coli there are 53 substitutions and two gaps. Position c.280 is G in both human and mouse, so it is identical in these two species. It lies outside the segment aligned with E. coli and could not be compared.

### Conservation across species: protein

The human protein is 93.93% identical to the mouse protein and 52.49% identical to the E. coli protein (Table 1). Of the 346 human positions covered by the three-way alignment (residues 3–348), 177 (51.2%) are identical in human, mouse and E. coli. The longest stretches identical in the three species are residues 85–102 (VIHFAGLKAVGESVQKPL, 18 aa), 198–211 (GEDPQGIPNNLMPY), 232–244 (TEDGTGVRDYIHV) and 129–137 (FSSSATVYG). The N-terminal stretch at residues 8–17 (TGGAGYIGSH) is identical in mouse and has one substitution in E. coli (A11S), and the stretch at residues 157–161 (YGKSK) is identical in the three species. Identity with E. coli is lowest in residues 19–47 (7 of 29 positions identical) and in the C-terminal residues 303–348 (17 of 46).

Compared with human, the mouse protein has 21 substitutions (L28S, F39I, G42E, G43D, L45M, G71A, R75H, Y80H, M83K, K120R, Q173R, K176T, T177A, T189I, C196R, N228D, D231A, R256K, I266T, Q315H, T346A) and no internal gaps. The E. coli protein has 156 substitutions and one internal gap of six residues, corresponding to human residues 41–46 (GGGSLP). Human residues 1–3 and 345–348 have no counterpart in the E. coli alignment.

### Comparison of the CDS and protein alignments

Mouse differences are located at residues 28–83 (nine of the 21) and 173–177 (three of the 21). In the E. coli protein comparison, the identity per block is lowest in the last block (residues 303–344) and highest at residues 183–242 (80.00%). At CDS level, the only region of the E. coli sequence that aligned is the segment at positions 532–761.

The two alignments do not show the same number of differences. Human vs mouse has 113 nucleotide differences but 21 amino-acid differences.

For mouse, identity is higher at protein level (93.93%) than at CDS level (89.15%). For E. coli, the protein aligned over 98% of the human protein and the CDS over 22% of the human CDS, so the two percentages are not directly comparable.

Valine 94 is identical in human, mouse and E. coli, and lies inside the longest stretch conserved in the three species (residues 85–102).

### Experimental 3D structures
Protein Data Bank (Table 2). The sequence of 1EK5 is identical to the WT protein. The sequence of 1I3N has methionine at position 94 and also differs from the WT protein at position 180 (Ala in the WT, Val in 1I3N).

| Feature | Wild Type (WT) Structure | Mutant (V94M) Structure |
| :--- | :--- | :--- |
| **PDB ID** | **1EK5** | **1I3N** |
| **Experimental Method** | X-ray Diffraction | X-ray Diffraction |
| **Resolution** | 1.80 Å | 1.50 Å |
| **Organism** | *Homo sapiens* | *Homo sapiens* |
| **Mutation** | None (WT - Val94) | V94M (p.Val94Met) |
| **Ligands / Cofactors** | NAD | NAD, UDP-N-acetylglucosamine, chloride, magnesium |
| **Chains in the asymmetric unit** | One (chain A); the dimer is generated by symmetry | Two (A and B) |

[results of tasks 3.5 and 3.6]

**Structural Impact of p.Val94Met:**
The substitution of Val94 with Met94 introduces a bulkier, sulfur-containing side chain into a highly conserved, tightly packed region (residues 85–102). Comparison between `1EK5` (WT) and `1I3N` (Mutant) reveals that the V94M substitution causes a slight displacement of the surface loop (Ala93 to Glu96), disrupting optimal active site geometry and destabilizing the core structure, which accounts for the reduced enzymatic activity in Epimerase-Deficiency Galactosemia.

**Q7. How do the properties of the WT and mutant amino acids differ?**
Both valine and methionine are non-polar, hydrophobic and uncharged, so the substitution does not change charge or polarity. They differ in size and shape: methionine has a longer, unbranched and more flexible side chain containing sulfur, whereas valine has a short, branched side chain. [Add values from the course material or UniProt if needed.]

**Q8. Could the substitution change the interactions made by this position? Why?**
Yes, while both valine and methionine are non-polar and hydrophobic, methionine has a significantly longer, bulkier side chain containing a sulfur atom. Substituting Val94 with Met introduces steric hindrance in the hydrophobic core, disrupting optimal van der Waals contacts and compact hydrophobic packing.

**Q9. Could this affect how the protein folds or functions? Why?**
Yes. Position 94 is located within a highly conserved sequence block (residues 85–102). The steric clashes caused by the bulkier methionine side chain can destabilize the local 3D fold, reduce protein stability, and distort the active site, leading to reduced epimerase activity.

**Q10. How does the CDS-level variant compare with the protein-level variant?**
They describe the same event at two levels: c.280G > A in the CDS corresponds to p.Val94Met in the protein.

**Q11. How does the nucleotide variant produce the amino-acid variant?**
The G>A substitution at c.280 is the first base of codon 94, which changes GTG (valine) to ATG (methionine).

**Q12. Are there any highly conserved regions across the three species in the CDS sequences?**

Yes, but the CDS comparison could not be done as a single three-way alignment. Human vs mouse and human vs *E. coli* were aligned separately with blastn, with the human WT CDS as the query in both runs. The *E. coli* CDS was too divergent to be aligned together with the other two sequences.

Human and mouse CDS align over almost their whole length (positions 7–1047, cover 99%, 89.15% identity, E-value 0.0). Conservation is not uniform: positions 367–426 and 847–906 are almost identical (2 and 3 mismatches per 60 nt), whereas positions 547–606 have about 12 mismatches. For *E. coli*, blastn only aligned a 230 nt segment (positions 532–761, cover 22%, 76.19% identity, E-value 5e-40).

**Q13. Are there any sequence positions with variants across the three species, either substitutions or gaps in the CDS sequences?**

Yes. As above, each species was compared with human separately. Human vs mouse shows about 113 substitutions, spread along the sequence and frequently at the third base of codons. There are no gaps, and the mouse CDS is one codon shorter (1044 vs 1047 nt). Human vs *E. coli* shows, within the aligned segment (positions 532–761), about 53 substitutions and 2 gaps, which compensate each other. No variants can be reported outside this segment.

Position c.280 is identical in human and mouse (G), so it is conserved between these two species. It lies outside the segment aligned with *E. coli* (positions 532–761), so it could not be compared.

**Q14. Are there any highly conserved regions across the three species in the protein sequences?&#xA0;**
Yes. The human protein is 93.93% identical to the mouse protein and 52.49% identical to the *E. coli* protein. Several stretches are identical in all three species, for example residues 5–18 (VLVTGGAGYIGSHT, except position 11 in *E. coli*), 85–102 (VIHFAGLKAVGESVQKPL), 129–137 (FSSSATVYG), 198–211 (GEDPQGIPNNLMPY) and 232–242 (TEDGTGVRDYI). The N-terminal region (about residues 19–47) and the C-terminal region are less conserved, mainly in *E. coli*.  

**Q15. Are there any sequence positions with variants across the three species, either substitutions or gaps in the protein sequences? &#xA0;**
Yes. Compared with human, the mouse protein shows about 21 substitutions (e.g. Leu28Ser, Gly71Ala, Arg75His, Lys120Arg) and no gaps. The *E. coli* protein shows many more substitutions (about half of the aligned positions; e.g. Lys4Arg, Glu21Gln, Ala84Thr) and a 6-residue gap corresponding to human residues 41–46. The last residues of the human protein (345–348) have no counterpart in the *E. coli* alignment. 

---
## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]

## Conclusions
[State the main conclusions and their significance.]

## Methods

### Literature and database searches

Background information on the disease, the gene and the variant was collected from the NCBI MeSH database, OMIM, PubMed, NCBI Gene and UniProt.

The NCBI MeSH database was searched with the query "galactosemias"[MeSH Terms] OR Epimerase-Deficiency Galactosemia[Text Word], and with the term "Epimerase". The MeSH records 68004926 and 68017398 [name the two headings] were consulted to define the terms used to search PubMed [add the PubMed query and the date of the search].

- **Tool and databases:** NCBI BLAST was used to identify the human *GALE* sequences (blastn against core_nt for the CDS, blastp for the protein) and the homologs from *Escherichia coli* K-12 (taxid:83333) and *Mus musculus* (taxid:10090).
- **Query sequences:** the provided FASTA files for the WT and mutant CDS and proteins (`EDG_CDS_WT.fasta`, `EDG_CDS_mutant.fasta`, `EDG_protein_WT.fasta`, `EDG_protein_mutant.fasta`).
- **Hit selection criteria:** high query cover, high identity, very small E-value, correct description and organism, and curated RefSeq records (NM_ / NP_) preferred.
- **Search date:** 12/10/2026

### Pairwise alignment of WT and mutant CDS (Lab 2.1)

- Tool: NCBI BLAST, blastn, "Align two or more sequences" option activated.
- Query: WT CDS (1047 nt). Subject: mutant CDS (1047 nt).
- Algorithm: highly similar sequences (megablast), default parameters.
- Run on: 13/10/2026.
- Alignment view: "Query-anchored with dots for identities", line length 60.

### Pairwise alignment of WT and mutant proteins (Lab 2.2)

- Tool: NCBI BLAST, blastp, "Align two or more sequences".option activated.
- Query: WT protein (348 aa). Subject: mutant protein (348 aa).
- Algorithm: blastp (protein-protein BLAST)
- Run on: 13/10/2026.
- Alignment view: query-anchored with dots for identities, line length 60.

  
### Multiple sequence alignment across species (Lab 2.3–2.4)

- **Sequences:** the WT CDS and WT protein of human *GALE* (`EDG_CDS_WT.fasta`, `EDG_protein_WT.fasta`; NM_000403.4 / NP_000394.2) were compared with the homologs from *Mus musculus* (NM_001356493.1 / NP_001343422.1) and *Escherichia coli* K-12 MG1655 (NP_415280.3).
- **CDS alignment:** NCBI BLAST, blastn, with the "Align two or more sequences" option activated. Query: human WT CDS (1047 nt). Subjects: *E. coli* sequence and mouse CDS, entered one after the other. Algorithm: [somewhat similar sequences (blastn) / megablast — write the one you used], other parameters left at default. Run on: [15/10/2026].
- **Protein alignment:** NCBI BLAST, blastp, with the "Align two or more sequences" option activated. Query: human WT protein (348 aa). Subjects: mouse protein (347 aa) and *E. coli* protein (338 aa, NP_415280.3). Run on: [15/10/2026].
- **Alignment view:** "Query-anchored with dots for identities", with the human sequence as the reference in all cases. Variable positions were identified as non-identical letters or gaps (`-`) relative to the human sequence.

### Comparison of the alignments (Lab 2.5)

Conservation can suggest that a position is important for protein structure or function because some positions tolerate fewer changes than others. Nevertheless, these comparisons aren't sufficient to demonstrate it in all species and shouldn't be considered universal.

---

##### 1. WTCDS - mutant CDS

The aligment covers 100% of the WTCDS sequence provided to BLAST. The percentage identity states that 99.90% of the aligned nucleotides in that coverage are identical, with only a 0.10% of differance approximately.

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 100,0% |
| **SECTION 2** | 100.0% |
| **SECTION 3** | 100.0% |
| **SECTION 4** | 100.0% |
| **SECTION 5** | 98.33% |
| **SECTION 6** | 100.0% |
| **SECTION 7** | 100.0% |
| **SECTION 8** | 100.0% |
| **SECTION 9** | 100.0% |
| **SECTION 10** | 100.0% |
| **SECTION 11** | 100.0% |
| **SECTION 12** | 100.0% |
| **SECTION 13** | 100.0% |
| **SECTION 14** | 100.0% |
| **SECTION 15** | 100.0% |
| **SECTION 16** | 100.0% |
| **SECTION 17** | 100.0% |
| **SECTION 18** | 100.0% |

Every section matches the original sequence perfectly except for *SECTION 5*, with a percentage identity of 98.33%. The mutation consists of the single nucleotide A (Adenine) instead of G (Guanine) in this section.

---

##### 2. WTCDS - E. coli

The aligment covers 22% of the WTCDS sequence provided to BLAST. The percentage identity states that 76.19% of the aligned nucleotides in that coverage are identical, with a 23.79% of differance approximately.

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 76.7% |
| **SECTION 2** | 80.0% |
| **SECTION 3** | 75.0% |
| **SECTION 4** | 74.0% |

The identity only varies slightly between the different sections of the covered sequence. Therefore, there's no pattern in particular sections.

---

##### 3. WTCDS - Mus musculus

The aligment covers 99% of the WTCDS sequence provided to BLAST. The percentage identity states that 89.15% of the aligned nucleotides in that coverage are identical, with a 10.85% of differance approximately.

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 91.67% |
| **SECTION 2** | 83.33% |
| **SECTION 3** | 93.33% |
| **SECTION 4** | 88.33% |
| **SECTION 5** | 90.00% |
| **SECTION 6** | 86.67% |
| **SECTION 7** | 96.67% |
| **SECTION 8** | 91.67% |
| **SECTION 9** | 90.00% |
| **SECTION 10** | 80.00% |
| **SECTION 11** | 90.00% |
| **SECTION 12** | 85.00% |
| **SECTION 13** | 81.67% |
| **SECTION 14** | 90.00% |
| **SECTION 15** | 95.00% |
| **SECTION 16** | 93.33% |
| **SECTION 17** | 90.00% |
| **SECTION 18** | 85.71% |

There's sections with noticeably higher identity than the rest: *SECTION 7*, *SECTION 15*, *SECTION 3* and *SECTION 16*, with a percentage identity > 90%. On the contrary, the lowest identities are *SECTION 10* and *SECTION 13* with percentages closer or equal to 80%. Nevertheless, all sections present high similarity.

---

##### 4. WTProtein - mutant Protein

The aligment covers 100% of the WTCDS sequence provided to BLAST. The percentage identity states that 99.71% of the aligned nucleotides in that coverage are identical, with only a 0.29% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 100,0% |
| **SECTION 2** | 98.33% |
| **SECTION 3** | 100.0% |
| **SECTION 4** | 100.0% |
| **SECTION 5** | 100.0% |
| **SECTION 6** | 100.0% |

Every section matches the original sequence perfectly except for *SECTION 2*, with a percentage identity of 98.33%. The mutation consists of the M aminoacid instead of V in this section.

---

##### 5. WTProtein - E. coli

The aligment covers 98% of the WTCDS sequence provided to BLAST. The percentage identity states that 52.49% of the aligned nucleotides in that coverage are identical, with a 48.52% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 51.67% |
| **SECTION 2** | 48.33% |
| **SECTION 3** | 48.33% |
| **SECTION 4** | 80.0% |
| **SECTION 5** | 53.33% |
| **SECTION 6** | 45.65% |

All sections present a percentage identity < 60% except for *SECTION 4* with an 80.0%.

---

##### 6. WTProtein - Mus musculus

The aligment covers 99% of the WTCDS sequence provided to BLAST. The percentage identity states that 93.93% of the aligned nucleotides in that coverage are identical, with a 6.07% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:

| Section | Percentage Identity |
|:--|--:|
| **SECTION 1** | 91.67% |
| **SECTION 2** | 91.67% |
| **SECTION 3** | 95.00% |
| **SECTION 4** | 93.33% |
| **SECTION 5** | 96.67% |
| **SECTION 6** | 95.65% |

All sections present a percentage identity > 90%, the highest being *SECTION 5* with 96.67% and the lowest *SECTION 1* and *SECTION 2* with 91.67%. Nevertheless, all sections present high similarity.

---

*(this should be added to discussion)*

## Sequence Alignment Analysis

#### 1. WTCDS vs. Mutant CDS

| Alignment | Percentage Identity | Coverage |
|:--|--:|--:|
| WTCDS - mutant CDS | 99.90% | 100% |
| WTProtein - mutant Protein | 99.71% | 100% |

> Although the nucleotid sequence alignment has a higher identity percentage, the variation in both cases is only one component of the sequence. The mutation consists of a substitution at nucleotide 280 that corresponds to a V --> M substitution at amino-acid position 94. The highest percentage of the CDS sequence is due to a greater ammount of nucleotids in the sequence than aminoacids, as three nucleotids (a codon) are needed to form an aminoacid during traduction. This is called a missense mutation.

---

#### 2. WTCDS vs. *E. coli*

| Alignment | Percentage Identity | Coverage |
|:--|--:|--:|
| WTCDS - E. coli | 76.19% | 22% |
| WTProtein - E. coli | 52.49% | 98% |

> The highest percentage identity is the WTCDS - E. coli alignment. Although it is higher, this is only because it is a percentage made within the section that BLAST covered, which is only a 22% of the sequence provided. This suggests that the rest of the sequence doesn't align with the human protein sequence and, therefore, would have a significantly lower identity percentage than the protein's if 98% of the sequence had been taken into account aswell.

---

#### 3. WTCDS vs. *Mus musculus*

| Alignment | Percentage Identity | Coverage |
|:--|--:|--:|
| WTCDS - Mus musculus | 89.15% | 99% |
| WTProtein - Mus musculus | 93.93% | 99% |

> Both percentage identities are similar, but the highest is the protein sequence. This is because throughout the alignment there can be cases where the change of a nucleotid doesn't necessarily imply a change in the codificated aminoacid. Aminoacids can be codificated by different codon sequences at the same time, meaning that the change of a nucleotid could create a new codon that also codificates for that same aminoacid, making it a neutral mutation with no visible effect on the final protein.

---

[  https://www.ncbi.nlm.nih.gov/books/NBK26836/ ]

##The conservation of the genome and proteins throughout evolution

The conservation of the genome sequences between two different species depend on the ammount of time they have separately evolved. 
Also, purifying selection eliminates individuals that carry mutations that interfere with important genetic functions. Sequences that are subject to strong functional constraint (the sequence has an important impact on the organism's wellness) are often conserved.

According to the molecular-clock hypothesis, changes of specific sequences of genes and proteins are not sudden, but constant in time. This molecular clock runs faster in sequences that are not affected by purifying selection, and slower in those that suffer from strong functional constraints.

[https://www.uniprot.org/uniprotkb/Q14376/ ]

The general function of the gene UDP-glucose 4-epimerase (GALE) is to catalyze two analogous reactions: the reversible epimerization of UDP-glucose to UDP-galactose and the reversible epimerization of UDP-N-acetylglucosamine to UDP-N-acetylgalactosamine. The reaction with UDP-Gal plays a critical role in the Leloir pathway of galactose catabolism in which galactose is converted to the glycolytic intermediate glucose 6-phosphate. It contributes to the catabolism of dietary galactose and enables the endogenous biosynthesis of both UDP-Gal and UDP-GalNAc when exogenous sources are limited.

more specifically, it contains the following functional sites:

[https://www.uniprot.org/uniprotkb/Q14376/entry]
Positions 12-14, 33-37, 66-67, 88, 92, 161 and 185: binding sites for NAD+.
Position 157: active site of proton acceptor
Positions 132-134, 185-187, 206-208, 224-226, 239 and 300-303: binding sites for substrate

the studied mutation appears in postion 279, meaning that it does not directly affect any of the indicated functional sites. These are needed for the basic wellness of the organism and therefore are less prone to effective mutation. 

---

## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]

## Declarations
Availability of data and materials: [Statement on repository/access]
Authors' contributions: Specify roles

## References

## References

1. NCBI. MeSH search: "galactosemias" OR Epimerase-Deficiency Galactosemia. National Library of Medicine. https://www.ncbi.nlm.nih.gov/mesh/?term=%22galactosemias%22%5BMeSH%20Terms%5D%20OR%20Epimerase-Deficiency%20Galactosemia%5BText%20Word%5D&cmd=DetailsSearch
2. OMIM. Entry #230350: Galactosemia III; GALAC3. https://omim.org/entry/230350
3. OMIM. Entry *606953: UDP-galactose-4-epimerase; GALE. https://omim.org/entry/606953
4. NCBI. MeSH record 68004926. https://www.ncbi.nlm.nih.gov/mesh/68004926
5. NCBI. MeSH record 68017398. https://www.ncbi.nlm.nih.gov/mesh/68017398
6. NCBI. MeSH search: "Epimerase". https://www.ncbi.nlm.nih.gov/mesh/?term=%22Epimerase%22%5BMeSH+Terms%5D
7. Fridovich-Keil J, Bean L, He M, Schroer R. Epimerase deficiency galactosemia. In: Adam MP, Feldman J, Mirzaa GM, et al., editors. GeneReviews® [Internet]. Seattle: University of Washington. PMID: 21290786. https://pubmed.ncbi.nlm.nih.gov/21290786/
8. National Organization for Rare Disorders (NORD). Galactose epimerase deficiency. https://rarediseases.org/mondo-disease/galactose-epimerase-deficiency/
9. NCBI BLAST. Basic Local Alignment Search Tool. https://blast.ncbi.nlm.nih.gov/Blast.cgi
10. NCBI Nucleotide. NM_000403.4: Homo sapiens UDP-galactose-4-epimerase (GALE), transcript variant 1, mRNA. https://www.ncbi.nlm.nih.gov/nucleotide/NM_000403.4
11. NCBI Nucleotide. NM_001127621.2. https://www.ncbi.nlm.nih.gov/nucleotide/NM_001127621.2
12. NCBI Nucleotide. NM_001008216.2. https://www.ncbi.nlm.nih.gov/nucleotide/NM_001008216.2
13. NCBI Protein. NP_001126148.1. https://www.ncbi.nlm.nih.gov/protein/NP_001126148.1
14. UniProt. Q14376: UDP-glucose 4-epimerase (GALE_HUMAN). https://www.uniprot.org/uniprotkb/Q14376/entry
16. NCBI Gene. GALE UDP-galactose-4-epimerase [Homo sapiens], Gene ID: 2582. https://www.ncbi.nlm.nih.gov/gene/2582
17. RCSB Protein Data Bank. Structure of human UDP-galactose 4-epimerase in complex with NAD+. PDB ID: 1EK5. Available at: https://www.rcsb.org/structure/1EK5 (accessed 23 October 2026).
18. RCSB Protein Data Bank. Molecular basis for severe epimerase-deficiency galactosemia: X-ray structure of the human V94M-substituted UDP-galactose 4-epimerase. PDB ID: 1I3N. Available at: https://www.rcsb.org/structure/1I3N (accessed 23 October 2026).
19. IMGT Education. IMGT classes of the 20 common amino acids. Available at: https://www.imgt.org/IMGTeducation/Aide-memoire/_UK/aminoacids/IMGTclasses.html (accessed 23 October 2026).
