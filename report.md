# Manuscript Title: Bioinformatic Analysis of Epimerase Deficiency Galactosemia
**Authors:** Mengxin Lin Huang, Marta Celdrán Abraldes, Elena Alexandra Gae Dumitru, Adrià Cuadros Farré-Escofet  
**Group:** 11DP-F

## Abstract
*Provide a structured abstract covering Background, Results, and Conclusions (Max 350
words).*

## Keywords
[Keyword 1, Keyword 2, Keyword 3, Keyword 4, Keyword 5]

## Background

Galactose is a sugar found mainly in milk and dairy products. The body converts it into glucose so it can be used as energy. Galactosemias are a group of inherited disorders in which this process fails and galactose accumulates in the blood.

The *GALE* gene (chromosome 1, 1p36.11) encodes the enzyme UDP-galactose 4-epimerase. This enzyme catalyses two reversible reactions: the interconversion of UDP-glucose and UDP-galactose, and of UDP-N-acetylglucosamine and UDP-N-acetylgalactosamine. The second reaction is important because these sugars are needed to build glycoproteins and glycolipids. Several alternatively spliced transcripts of *GALE* have been described, and they encode the same protein.

Mutations in *GALE* cause epimerase-deficiency galactosemia (EDG, galactosemia type III), an autosomal recessive disorder. Its severity varies widely. The generalized form, with very low enzyme activity in all tissues, can cause liver damage, cataracts, hearing loss and developmental delay. The peripheral form is milder, with reduced activity only in blood cells. Treatment is based on a galactose-restricted diet, which prevents many acute symptoms but not all long-term problems.

Several missense variants in *GALE* have been reported in OMIM, including p.Val94Met. However, it is not fully understood how a single amino-acid change affects the structure and function of the enzyme. In this study, we compared the wild-type and mutant *GALE* sequences, analysed their conservation across species (human, mouse and *Escherichia coli*), and examined the 3D structural environment of the mutated residue using PDB structures. Our aim is to explain how this variant may cause EDG.

## Results

### Human WT gene and protein

|Item |Value |
|---|---|
| Gene | *GALE* (UDP-galactose-4-epimerase); also known as THC13, SDR1E1 |
| Gene ID / HGNC / MIM | 2582 / HGNC:4116 / 606953 |
| Location | 1p36.11, chromosome 1 (NC_000001.11) |
| Exons | 13 |
| Expression | Broad; highest in stomach and duodenum |
| WT CDS | NM_000403.4 |
| WT protein | NP_000394.2 (348 aa) |

### Homologs

| Species | Gene | CDS | Protein | Length |
|---|---|---|---|---|
| *Homo sapiens* | *GALE* | NM_000403.4 | NP_000394.2 | 348 aa |
| *Escherichia coli* | *galE* | OZ544371.1 | NP_415280.3 (*Escherichia coli* K-12 MG1655:UDP-glucose 4-epimerase) | 338 aa |
| *Mus musculus* | *Gale* | NM_001356493.1 | NP_001343422.1 | 347 aa |


*E. coli* blastp against human: cover 98%, identity 52.49%, E-value 4e-131. Blastn against the *E. coli* genome returned NC_ genome records (cover 25%, identity 71.5%, E-value 5e-22), not a CDS.

### WT vs mutant CDS (Lab 2.1)
- Both sequences are 1047 nt long. Identities: 1046/1047 (99.90%); gaps: 0/1047.
- The two sequences are identical except at one position.
- Position of the difference: 280 (alignment block 241–300; the mismatch is the 40th column of that block).
- WT nucleotide: G. Mutant nucleotide: A.
- No insertions or deletions were observed (no gaps in the alignment).
- Variant type: substitution (single-nucleotide variant, transition G>A).
- CDS annotation: **c.280G>A**.
  
**Q5. Is the mutation synonymous, missense or nonsense?**
Missense. The substitution changes codon 94 from GTG (Val) to ATG (Met), and the stop codon is unchanged.

**Q6. Could insertions or deletions alter the reading frame?**
Not applicable: the change is a single nucleotide substitution, with no insertions or deletions.

### WT vs mutant protein (Lab 2.2)
- Both proteins are 348 aa long. Identities: 347/348 (99.71%); gaps: 0/348.
- The two sequences are identical except at one position.
- Position of the difference: 94 (alignment block 61–120; the mismatch is the 34th column of that block).
- WT amino acid: Val (V). Mutant amino acid: Met (M).
- No insertions or deletions were observed (no gaps in the alignment).
- Variant type: single amino-acid substitution (missense).
- Protein annotation: **p.Val94Met**.

### Protein 3D Structures (PDB Analysis)
*Supplementary material: [View GALE 3D structure and sequence comparison PDF](figures/GALE_PDB_1EK5_comparison.pdf).*

To evaluate the 3D structural consequences of the p.Val94Met mutation, experimental crystal structures were retrieved from the Protein Data Bank (RCSB PDB):

| Feature | Wild Type (WT) Structure | Mutant (V94M) Structure |
| :--- | :--- | :--- |
| **PDB ID** | **1EK5** | **1I3N** |
| **Experimental Method** | X-ray Diffraction | X-ray Diffraction |
| **Resolution** | 1.80 Å | 1.50 Å |
| **Organism** | *Homo sapiens* | *Homo sapiens* |
| **Mutation** | None (WT - Val94) | V94M (p.Val94Met) |
| **Ligands / Cofactors** | NAD+, UDP-Glucose / UDP-Galactose | NAD+, UDP-N-acetylglucosamine |
| **Oligomeric State** | Homodimer | Homodimer |

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
### Sequence searches (Lab Session 1)

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
Conservation can suggest that a position is important for protein structure or function
because some positions tolerate fewer changes than others. Nevertheless, these comparisons aren't sufficient to demonstrate it in all species and shouldn't be considered universal.

- **WTCDS - mutant CDS**
  
The aligment covers 100% of the WTCDS sequence provided to BLAST. The percentage identity states that 99.90% of the aligned nucleotides in that coverage are identical, with only a 0.10% of differance approximately.

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

*SECTION 1* :	100,0%

*SECTION 2* :	100.0%

*SECTION 3* :	100.0%

*SECTION 4* :	100.0%

*SECTION 5* :	98.33%

*SECTION 6* :	100.0%

*SECTION 7* :	100.0%

*SECTION 8* :	100.0%

*SECTION 9* :	100.0%

*SECTION 10* :	100.0%

*SECTION 11* :	100.0%

*SECTION 12* :	100.0%

*SECTION 13* :	100.0%

*SECTION 14* :	100.0%

*SECTION 15* :	100.0%

*SECTION 16* :	100.0%

*SECTION 17* :	100.0%

*SECTION 18* :	100.0%

Every section matches the original sequence perfectly except for *SECTION 5*, with a percentage identity of 98.33%. The mutation consists of the single nucleotide A (Adenine) instead of G (Guanine) in this section.


- **WTCDS - E. coli**
  
The aligment covers 22% of the WTCDS sequence provided to BLAST. The percentage identity states that 76.19% of the aligned nucleotides in that coverage are identical, with a 23.79% of differance approximately. 

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

*SECTION 1* : 76.7%

*SECTION 2* : 80.0%

*SECTION 3* : 75.0%

*SECTION 4* : 74.0%

The identity only varies slightly between the different sections of the covered sequence. Therefore, there's no pattern in particular sections.


- **WTCDS - Mus musculus**
  
The aligment covers 99% of the WTCDS sequence provided to BLAST. The percentage identity states that 89.15% of the aligned nucleotides in that coverage are identical, with a 10.85% of differance approximately.

Knowing that the percentage identity = identical nucleotides / total nucleotides * 100:

*SECTION 1* :	91.67%

*SECTION 2* :	83.33%

*SECTION 3* :	93.33%

*SECTION 4* :	88.33%

*SECTION 5* :	90.00%

*SECTION 6* :	86.67%

*SECTION 7* :	96.67%

*SECTION 8* :	91.67%

*SECTION 9* :	90.00%

*SECTION 10* :	80.00%

*SECTION 11* :	90.00%

*SECTION 12* :	85.00%

*SECTION 13* :	81.67%

*SECTION 14* :	90.00%

*SECTION 15* :	95.00%

*SECTION 16* :	93.33%

*SECTION 17* :	90.00%

*SECTION 18* :	85.71%

There's sections with noticeably higher identity than the rest: *SECTION 7*, *SECTION 15*, *SECTION 3* and *SECTION 16*, with a percentage identity > 90%. On the contrary, the lowest identities are *SECTION 10* and *SECTION 13* with percentages closer or equal to 80%. Nevertheless, all sections present high similarity.


- **WTProtein - mutant Protein**
  
The aligment covers 100% of the WTCDS sequence provided to BLAST. The percentage identity states that 99.71% of the aligned nucleotides in that coverage are identical, with only a 0.29% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:
  
*SECTION 1* :	100,0%

*SECTION 2* :	98.33%

*SECTION 3* :	100.0%

*SECTION 4* :	100.0%

*SECTION 5* :	100.0%

*SECTION 6* :	100.0%

Every section matches the original sequence perfectly except for *SECTION 2*, with a percentage identity of 98.33%. The mutation consists of the M aminoacid instead of V in this section.

  
- **WTProtein - E. coli**
  
The aligment covers 98% of the WTCDS sequence provided to BLAST. The percentage identity states that 52.49% of the aligned nucleotides in that coverage are identical, with a 48.52% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:

*SECTION 1* : 51.67%

*SECTION 2* :	48.33%

*SECTION 3* :	48.33%

*SECTION 4* :	80.0%

*SECTION 5* :	53.33%

*SECTION 6* :	45.65%

All sections present a percentage identity < 60% except for *SECTION 4* with a 80.0%. 

  
- **WTProtein - Mus musculus**
  
The aligment covers 99% of the WTCDS sequence provided to BLAST. The percentage identity states that 93.93% of the aligned nucleotides in that coverage are identical, with a 6.07% of differance approximately.

Knowing that the percentage identity = identical aminoacids / total aminoacids * 100:

*SECTION 1* :	91.67%

*SECTION 2* :	91.67%

*SECTION 3* :	95.00%

*SECTION 4* :	93.33%

*SECTION 5* :	96.67%

*SECTION 6* :	95.65%

All sections present a percentage identity > 90%, the highest being *SECTION 5* with 96.67% and the lowest *SECTION 1* and *SECTION 2* with 91.67%. Nevertheless, all sections present high similarity.

---

*(this should be added to discussion)*


In the comparison between WT CDS & mutant CDS, the G --> A substitution at nucleotide po 280 corresponds to a V --> M substitution at amino-acid position 94. This means that a different nucleotid will codsitionificate a different aminoacid aswell and the sequence will be affected. This happens in the comparisons of the aligments WT CDS & mouse CDS and WT CDS & E. coli CDS aswell, but in both of them there's cases where regardless of the different nucleotids, it still codificates for the same aminoacid and the sequence is unaffected.

WTCDS - mutant CDS - 99.90% (100% coverage) 

WTProtein - mutant Protein - 99.71% (100% coverage) 

-> Both percentage identities are similar, but the highest is the nucleotid sequence


WTCDS - E. coli - 76.19% (22% coverage)

WTProtein - E. coli - 52.49% (98% coverage)

-> Both percentage identities are similar, but the highest is the nucleotid sequence


WTCDS - Mus musculus - 98.15% (99% coverage)

WTProtein - Mus musculus - 93.93% (99% coverage)

-> Both percentage identities are similar, but the highest is the nucleotid sequence

# I dont understand why this happens. Ask teacher

---

## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]

## Declarations
Availability of data and materials: [Statement on repository/access]
Authors' contributions: Specify roles

## References

1. NCBI. MeSH search: "galactosemias" OR Epimerase-Deficiency Galactosemia. National Library of Medicine. https://www.ncbi.nlm.nih.gov/mesh/?term=%22galactosemias%22%5BMeSH%20Terms%5D%20OR%20Epimerase-Deficiency%20Galactosemia%5BText%20Word%5D&cmd=DetailsSearch
2. OMIM. Entry #230350: Galactosemia III; GALAC3. https://omim.org/entry/230350
3. OMIM. Entry *606953: UDP-galactose-4-epimerase; GALE. https://omim.org/entry/606953
4. NCBI. MeSH record 68004926. https://www.ncbi.nlm.nih.gov/mesh/68004926
5. NCBI. MeSH record 68017398. https://www.ncbi.nlm.nih.gov/mesh/68017398
6. NCBI. MeSH search: "Epimerase". https://www.ncbi.nlm.nih.gov/mesh/?term=%22Epimerase%22%5BMeSH+Terms%5D
7. PubMed. Epimerase Deficiency Galactosemia. PMID 21290786. https://pubmed.ncbi.nlm.nih.gov/21290786/
8. National Organization for Rare Disorders (NORD). Galactose epimerase deficiency. https://rarediseases.org/mondo-disease/galactose-epimerase-deficiency/
9. NCBI BLAST. Basic Local Alignment Search Tool. https://blast.ncbi.nlm.nih.gov/Blast.cgi
10. NCBI Nucleotide. NM_000403.4: Homo sapiens UDP-galactose-4-epimerase (GALE), transcript variant 1, mRNA. https://www.ncbi.nlm.nih.gov/nucleotide/NM_000403.4
11. NCBI Nucleotide. NM_001127621.2. https://www.ncbi.nlm.nih.gov/nucleotide/NM_001127621.2
12. NCBI Nucleotide. NM_001008216.2. https://www.ncbi.nlm.nih.gov/nucleotide/NM_001008216.2
13. NCBI Protein. NP_001126148.1. https://www.ncbi.nlm.nih.gov/protein/NP_001126148.1
14. UniProt. Q14376: UDP-glucose 4-epimerase (GALE_HUMAN). https://www.uniprot.org/uniprotkb/Q14376/entry
