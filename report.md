# Manuscript Title: Bioinformatic Analysis of Epimerase Deficiency Galactosemia
**Authors:** Mengxin Lin Huang, Marta Celdrán Abraldes, Elena Alexandra Gae Dumitru, Adrià Cuadros Farré-Escofet  
**Group:** 11DP-F

## Abstract
*Provide a structured abstract covering Background, Results, and Conclusions (Max 350
words).*

## Keywords
[Keyword 1, Keyword 2, Keyword 3, Keyword 4, Keyword 5]

## Background
[Explain the background to the study, its aims, and research gap.]

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
| *Escherichia coli* K-12 MG1655 | *galE* | [CDS accession] | NP_415280.3 (UDP-glucose 4-epimerase) | 338 aa |
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

**Q7. How do the properties of the WT and mutant amino acids differ?**
Both valine and methionine are non-polar, hydrophobic and uncharged, so the substitution does not change charge or polarity. They differ in size and shape: methionine has a longer, unbranched and more flexible side chain containing sulfur, whereas valine has a short, branched side chain. [Add values from the course material or UniProt if needed.]

**Q8. Could the substitution change the interactions made by this position? Why?**


**Q9. Could this affect how the protein folds or functions? Why?**


**Q10. How does the CDS-level variant compare with the protein-level variant?**
They describe the same event at two levels: c.280G>A in the CDS corresponds to p.Val94Met in the protein.

**Q11. How does the nucleotide variant produce the amino-acid variant?**
The G>A substitution at c.280 is the first base of codon 94, which changes GTG (valine) to ATG (methionine).

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

---

## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]

## Declarations
Availability of data and materials: [Statement on repository/access]
Authors' contributions: Specify roles

## References
1. Author A, Author B. Title. BMC Bioinformatics. Year;Vol:Pages.
