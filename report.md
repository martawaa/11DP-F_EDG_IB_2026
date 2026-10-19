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

**Q7. How do the properties of the WT and mutant amino acids differ?**
Both valine and methionine are non-polar, hydrophobic and uncharged, so the substitution does not change charge or polarity. They differ in size and shape: methionine has a longer, unbranched and more flexible side chain containing sulfur, whereas valine has a short, branched side chain. [Add values from the course material or UniProt if needed.]

**Q8. Could the substitution change the interactions made by this position? Why?**


**Q9. Could this affect how the protein folds or functions? Why?**


**Q10. How does the CDS-level variant compare with the protein-level variant?**
They describe the same event at two levels: c.280G>A in the CDS corresponds to p.Val94Met in the protein.

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

- **WTCDS - mutant CDS**


- **WTCDS - E. coli**

  
- **WTCDS - Mus musculus**




- **WTProtein - mutant Protein**

  
- **WTProtein - E. coli**

  
- **WTProtein - Mus musculus**


---

## Abbreviations
[List abbreviations used, e.g., AI: Artificial Intelligence.]

## Declarations
Availability of data and materials: [Statement on repository/access]
Authors' contributions: Specify roles

## References
1. Author A, Author B. Title. BMC Bioinformatics. Year;Vol:Pages.
