# Manuscript Title: Bioinformatic Analysis of Epimerase Deficiency Galactosemia
**Authors:** Mengxin Lin Huang, Marta Celdrán Abraldes, Elena Alexandra Gae Dumitru, Adrià Cuadros Farré-Escofet  
**Department, Institution, City, Country:** BBI, Polytechnic University of Catalonia, Barcelona, Spain

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

The WT CDS search identified the human gene GALE (Gene ID 2582, MIM 606953) at locus 1p36.11 (NC_000001.11), with the RefSeq record NM_000403.4 (13 exons). The WT protein search identified NP_000394.2 (348 aa). The mutant CDS had its best hit on NM_000403.4 with 99.90% identity to the WT CDS (1046/1047 nucleotides; query cover 100%, E-value 0.0), and the mutant protein had its best hit on NP_000394.2 with 99.71% identity to the WT protein (347/348 amino acids; query cover 100%, E-value 0.0).

The homologues selected were, for Mus musculus, Gale (CDS NM_001356493.1; protein NP_001343422.1, 347 aa) and, for Escherichia coli, galE (protein NP_415280.3, 338 aa, strain K-12 MG1655; nucleotide record OZ544371.1, strain RSZYD15081311_A, not K-12). The protein and the nucleotide sequences therefore come from different E. coli strains.

### Comparison of the WT and mutant sequences

The WT and mutant CDS (1047 nt) differ at one position, with no gaps: position 280 is G in the WT and A in the mutant (c.280G>A). The WT and mutant proteins (348 aa) differ at one position, with no gaps: valine at position 94 is replaced by methionine (p.Val94Met). Codon 94 occupies nucleotides 280–282, and position 280 is its first base. The change converts GTG (Val) to ATG (Met), so the substitution is missense; the stop codon is unchanged and the reading frame is not altered.

Valine and methionine are both non-polar, hydrophobic and uncharged. Valine is aliphatic with a medium volume (140.0 Å³), whereas methionine is sulfur-containing with a larger volume (162.9 Å³) (Pommié et al. 2004).

### Conservation across species: CDS

Because blastn aligned only 22% of the human CDS with the E. coli sequence, human vs mouse and human vs E. coli were aligned separately (Table 1).

#### Table 1. Identity and coverage of the WT human sequences against mouse and E. coli.

| Comparison | 	Level | Query cover | Identity | 	Identity per 60-position block |
|---|---|---|---|---|
| *Human vs mouse* | CDS | 99% (positions 7–1047) | 89.15% | 80.00–96.67% (18 blocks) |
| *Escherichia coli* | CDS | 	22% (positions 532–761) | 76.19% | 74.0–80.0% (4 blocks) |
| *Human vs mouse* | Protein | 99% | 93.93% (325/346) | 91.67–96.67% (6 blocks) |
| *Human vs E. coli* | Protein | 98% | 52.49% (179/341) | 40.48–80.00% (6 blocks) |

CDS. Human and mouse CDS align over almost their whole length (E-value 0.0), with 113 substitutions (928/1041 identities, no gaps): 88 at the third base of a codon, 12 at the first and 13 at the second. For E. coli, blastn aligned one segment (positions 532–761, E-value 5e-40; 176/231 identities), which corresponds approximately to residues 178–254 of the protein, with 53 substitutions and two gaps; outside it the human CDS has no alignment. Position c.280 is G in human and mouse. It lies outside the segment aligned with E. coli.

Protein. Of the 346 human positions covered by the three-way alignment (residues 3–348), 177 (51.2%) are identical in human, mouse and E. coli (Figure 1). The longest identical stretches are residues 85–102 (VIHFAGLKAVGESVQKPL), 198–211, 232–244 and 129–137. Identity with E. coli is lowest in residues 19–47 (7 of 29) and 303–348 (17 of 46). The mouse protein has 21 substitutions and no gaps; nine lie in residues 28–83. The E. coli protein has 156 substitutions and a six-residue gap corresponding to human residues 41–46. The full list of substitutions and the identity of every block are given in Additional file 1. Valine 94 is identical in the three species and lies inside the longest conserved stretch (residues 85–102).

CDS and protein. Human vs mouse has 113 nucleotide differences but 21 amino-acid differences, and identity is higher in the protein (93.93%) than in the CDS (89.15%). For E. coli, the protein aligned over 98% of the human protein and the CDS over 22% of the human CDS, so the two identities are not directly comparable.

Figure 1: MSA_position94.png

#### Figure 1. MSA_position94.png
Valine 94 is boxed. * identical, : strongly similar, . weakly similar. 

### Experimental 3D structures
Two X-ray structures of human GALE were selected: 1EK5 (WT; 1.80 Å; one chain in the asymmetric unit, with the dimer generated by symmetry; ligand NAD; Thoden et al. 2000) and 1I3N (V94M; 1.50 Å; chains A and B; ligands NAD, URIDINE-DIPHOSPHATE-N-ACETYLGLUCOSAMINE, CHLORIDE ION and MAGNESIUM ION; Thoden et al. 2001). The sequence of 1EK5 is identical to the WT protein. The sequence of 1I3N has methionine at position 94 and also differs from the WT at position 180 (Ala in the WT, Val in 1I3N).

In the WT, residue 94 is buried and lies in an α-helix. Within 4.5 Å, Lys92, Ala93, Gly95, Glu96 and Asn206 are neighbours in both structures; Ser97, Val98, Asn155 and Tyr157 only in the WT, and Asn37 and Tyr104 only in the mutant (Table 2, Figure 2). The Cα–Cα distance between residue 94 and Tyr157 was 5.6 Å in the WT and 10.0 Å (chain A) and 10.1 Å (chain B) in 1I3N. No NAD atom lies within 4.5 Å of residue 94 in the WT, and no atom of the UDP-sugar ligand lies within 4.5 Å in 1I3N. Residue 94 is not part of the dimer interface defined in 1I3N (residues 110, 117, 156, 163, 167, 171 and 174 are). In UniProt Q14376, residue 94 has no binding-site or active-site annotation; the nearby Lys92 and Asn206 are annotated as NAD-binding and substrate-binding, and Tyr157 as the proton acceptor.

**Table 2.** Structural environment of residue 94.

| Feature | WT (1EK5) | V94M (1I3N) |
|---|---|---|
| Burial | Buried | Not measured |
| Secondary structure | α-helix | Not measured |
| Neighbours < 4.5 Å (both) | Lys92, Ala93, Gly95, Glu96, Asn206 | Lys92, Ala93, Gly95, Glu96, Asn206 |
| Neighbours < 4.5 Å (only one structure) | Ser97, Val98, Asn155, Tyr157 | Asn37, Tyr104 |
| Cα–Cα distance 94–Tyr157 | 5.6 Å | 10.0 Å (chain A); 10.1 Å (chain B) |
| NAD atoms < 4.5 Å / < 8 Å| 0/6 | Not measured/10 |
| UDP-sugar atoms < 4.5 Å / < 8 Å | No substrate in the structure | 0 / 7 |
| Dimer interface | Not measured | Not part of it |

Figure 2: Superposition of WT and V94M mutant GALE structures

#### Figure 2. Superposition of human WT GALE (1EK5, green) and V94M mutant (1I3N, cyan), zoomed in on position 94.


# Marta, you may need this following information

The substitution of Val94 with Met94 introduces a bulkier, sulfur-containing side chain into a highly conserved, tightly packed region (residues 85–102). Comparison between `1EK5` (WT) and `1I3N` (Mutant) reveals that the V94M substitution causes a slight displacement of the surface loop (Ala93 to Glu96), disrupting optimal active site geometry and destabilizing the core structure, which accounts for the reduced enzymatic activity in Epimerase-Deficiency Galactosemia.

### Structural environment of residue 94

The environment of residue 94 was analysed in the WT (1EK5) and V94M (1I3N) structures (Table 2). Residue 94 is buried and lies in an α-helix. Within 4.5 Å, Lys92, Ala93, Gly95, Glu96 and Asn206 are neighbours in both structures. Ser97, Val98, Asn155 and Tyr157 are neighbours only in the WT, and Asn37 and Tyr104 only in the mutant. No residue of chain B lies within 4.5 Å of residue 94.

The Cα–Cα distance between residue 94 and Tyr157 was 5.6 Å in the WT, and 10.0 Å (chain A) and 10.1 Å (chain B) in 1I3N. No NAD atom lies within 4.5 Å of residue 94 in the WT; within 8 Å there are six NAD atoms in the WT and ten in 1I3N (chain A). In 1I3N, no atom of the substrate UDP-N-acetylglucosamine lies within 4.5 Å of residue 94, and seven atoms lie within 8 Å. Residue 94 is not part of the dimer interface (residues 110, 117, 156, 163, 167, 171 and 174 are).

Residue 94 therefore does not contact NAD, the substrate or the other subunit directly, but it lies close to residues annotated in UniProt Q14376 as NAD-binding (Lys92), substrate-binding (Asn206) and the catalytic proton acceptor (Tyr157). These are measurements. The interpretation that Met94 acts indirectly on the active site is a hypothesis.

*Limitations:* 1EK5 and 1I3N are different crystals (1.80 and 1.50 Å resolution), 1I3N also carries Ala180Val, and only 1I3N contains the substrate, so the differences cannot be attributed to V94M alone. The Cα–Cα change (4.4 Å) is large and should be compared with Thoden et al. 2001.


## Discussion
[Discuss implications, compare with existing research, and highlight limitations.]

The main aim of this study was to investigate the potential consequences of the p.Val94Met (V94M) variant in the human GALE gene. This comparison showed variation in a single nucleotid, resulting in the replacement of valine by methionine at position 94. The cross-species analysis supports the importance of residue 94. Human GALE showed 93.93% protein identity with mouse GALE and 52.49% identity with the Escherichia coli homologue. Despite the lower or higher identity percentages observed in both species, valine 94 was conserved in all three. This conservation suggests that the residue may contribute to a structurally or functionally important region of the enzyme. This region encodes for UDP-galactose 4-epimerase. This enzyme catalyses the interconversion of UDP-glucose and UDP-galactose, and of UDP-N-acetylglucosamine and UDP-N-acetylgalactosamine, therefore being essential for basic metabolic processes.

The structural comparison of the WT and mutant amino acid sequence showed that both valine and methionine are non-polar, hydrophobic and uncharged. Metionine, however, has a larger side-chain volume. The structural superposition of PDB 1EK5 and PDB 1I3N showed a displacement of Ala93-Glu96 in the region of the mutated residue 94. This diference in side-chain volume and the structural displacement suggest that the substitution contributed to a change in the structural environment of the protein. Nevertheless, these observations can't accurately explain the substitution's effects on the protein's function. Also, PDB 1I3N contains an Ala180Val difference, so the structural differences between the two structures can't be entirely attributed to the V94M substitution alone.

The nucleotide and protein comparisons also differed in their coverage across species. BLAST was able to align the human and mouse CDS sequences almost entirely, but the coverage offered by the E. coli alignment was only 22%, making it harder to accurately compare both sequences. Moreover, the protein alignment showed a higher coverage percentage in both mouse and E.coli comparisons.

[https://pubmed.ncbi.nlm.nih.gov/11279193/]
The findings of this study can be compared with those of Thoden et al. (2001), who investigated the human GALE V94M variant using X-ray crystallography. Their study described an opening of the Ala93–Glu96 loop associated with the substitution, providing a structural context for the loop displacement observed in our comparison. This supports the interpretation that the region surrounding residue 94 differs between the wild-type and variant structures.

## Conclusions
[State the main conclusions and their significance.]

## Methods

### Literature and database searches

Background information was collected from NCBI MeSH, PubMed, OMIM and UniProt, which were consulted between 8 and 12 October 2026. MeSH was searched with “galactosemias”[MeSH Terms] OR Epimerase-Deficiency Galactosemia[Text Word] and with “Epimerase”[MeSH Terms]; the records 68004926 (Escherichia coli) and 68017398 (Alternative Splicing) were also consulted to prepare the BLAST searches. The clinical description of EDG was taken from PMID 21290786 (GeneReviews) and the NORD page. Articles on galactose epimerase deficiency were searched in PubMed with the query “Galactose Epimerase Deficiency”, and articles on V94M with the query “V94M”, on 22 October 2026; they included Thoden et al. (2001) and Timson and Lindert (2013). OMIM entries *606953 (GALE, with its allelic variants .0001–.0008) and 
#230350 (galactosemia III) and UniProt Q14376 (function and functional sites) were read, and NCBI Gene (Gene ID 2582) was consulted on 9 October 2026.

### Sequences and sequence searches

The WT and mutant CDS and protein sequences were provided as FASTA files (EDG_CDS_WT.fasta, EDG_CDS_mutant.fasta, EDG_protein_WT.fasta, EDG_protein_mutant.fasta) and used as queries in NCBI BLAST (Altschul et al. 1990) on 12 October 2026: blastn against core_nt for the CDS and blastp for the protein. Hits were selected for high query cover and identity, a very small E-value, a matching description and organism, and a curated RefSeq record (NM_ or NP_). The searches returned RefSeq records of alternatively spliced transcripts (NM_000403.4, NM_001127621.2 and NM_001008216.2) and of their proteins (NP_000394.2 and NP_001126148.1). The two protein sequences were compared and were identical (348 aa), and both matched the provided WT protein with 100% identity. The longest transcript, NM_000403.4, was used as the reference for the CDS, and the protein NP_000394.2 is the product annotated in this record.

Homologues were searched in E. coli (protein NP_415280.3, strain K-12 MG1655, taxid:83333) and M. musculus (taxid:10090) with the same programs and criteria. The E. coli nucleotide sequence was the genome assembly OZ544371.1 (strain RSZYD15081311_A, not K-12; chromosome 1, 2 314 235 nt). A preliminary blastn search against the E. coli genome returned NC_ records and was not used.

### Pairwise and cross-species alignments

The WT and mutant sequences were compared with the “Align two or more sequences” option of BLAST (13 October 2026), with the WT as query: megablast for the CDS and blastp for the protein, with default parameters. Variants were named following HGVS nomenclature. For the cross-species CDS comparison, the human CDS (1047 nt) was the query and the mouse (highly similar sequences) and E. coli (somewhat similar sequences) sequences were subjects in separate runs, with other parameters at default (19 October 2026). For the protein, the human protein was the query and the mouse and E. coli proteins were subjects in the same alignment (15 October 2026; RID D21P1GCA114). All alignments were shown as “Query-anchored with dots for identities”, line length 60, and variable positions were read relative to the human sequence. Only WT sequences were used. The multiple alignment with the consensus line was produced with Clustal Omega (version 1.2.4; Sievers et al. 2011) on 14 October 2026.

### Calculation of identity and conservation

Percentage identity and query cover were taken from the BLAST output. Identity per 60-position block was calculated as **identical positions divided by aligned positions in the block, multiplied by 100,** with a Python script. Positions identical in the three proteins were counted position by position in the three-way alignment. Conserved stretches were defined as runs of consecutive positions identical in the three species. The codon position of each nucleotide difference in the human vs mouse alignment was calculated from its position in the human CDS.

```python
from yogi import scan

a = len(scan(str))

while a is not None:
    b = scan(str)
    c = ''
    for i in range(len(b)):
        if b[i] != '.':
            c = c + b[i]
    print(((a - len(c)) / a) * 100)
    a = len(scan(str))
```

### Protein structures and amino acid properties

Human GALE structures were searched in the RCSB Protein Data Bank (https://www.rcsb.org) and UniProt (Q14376), and selected for being human, determined by X-ray diffraction, having the WT sequence or the V94M substitution, and having a published study. 1EK5 and 1I3N were chosen because both have a resolution better than 2 Å (1.80 and 1.50 Å), cover almost the whole protein and come from the same research group. Resolution, ligands, chains and publications were taken from the RCSB entries on 20 October 2026. Structures were visualised and superposed in PyMOL (Schrödinger, LLC; version). Solvent was removed. Secondary structure was assigned with dss; neighbouring residues were selected with around 4.5 (whole residues); Cα–Cα distances were measured with get_distance; ligand atoms were counted with count_atoms within 4.5 and 8 Å; and the dimer interface was defined as residues of chain A within 4 Å of chain B in 1I3N. Measurements used chain A, with one control in chain B. Burial was judged visually from the surface representation.

The properties of valine and methionine were taken from the IMGT classes of the 20 common amino acids (https://www.imgt.org/IMGTeducation/Aide-memoire/_UK/aminoacids/IMGTclasses.html; Pommié et al. 2004).

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

**Task 3.7. Link between the structure, the enzyme function and the phenotype**

The p.Val94Met variant can be followed from the gene to the patient. The change c.280G>A in GALE makes the enzyme have methionine instead of valine at position 94. This enzyme, UDP-galactose 4-epimerase, needs NAD to work and is a dimer. It changes UDP-glucose into UDP-galactose, and UDP-N-acetylglucosamine into UDP-N-acetylgalactosamine, and Tyr157 is the residue that takes a proton during the reaction (UniProt Q14376). When the enzyme has low activity, the person has EDG. This disease can be mild, when only the blood cells are affected (peripheral form), or severe, when all the tissues tested are affected (generalized form). V94M has been found in patients with two copies of the variant who have the generalized form (Fridovich-Keil et al.).

Here it is important to separate what we found from what is only an idea. From our analysis, valine 94 is the same in human, mouse and E. coli. In the structures, it is inside the protein and it does not touch NAD, the UDP-sugar or the other subunit, but it is close to Lys92, Asn206 and Tyr157. The distance between residue 94 and Tyr157 is 5.6 Å in 1EK5 and 10.0 Å in 1I3N. From the literature, the V94M enzyme has about 5% of the normal activity with UDP-galactose and about 25% with UDP-N-acetylgalactosamine, and its structure shows that the loop Ala93–Glu96 opens (Thoden et al. 2001). A computer simulation also found that the substrate is farther from Tyr157 in the variant (Timson and Lindert 2013). 

Our idea is that, since residue 94 does not touch the substrate, Met94 may affect the active site in an indirect way, and this would fit with the low activity and the severe disease. However, we cannot prove it, because 1EK5 and 1I3N have different resolution and ligands, 1I3N also has the change Ala180Val, and we did not measure any activity.

## Abbreviations

- **aa:** amino acid
- **BLAST:** Basic Local Alignment Search Tool
- **CDS:** coding DNA sequence
- **EDG:** epimerase-deficiency galactosemia
- **GALE:** UDP-galactose 4-epimerase (gene symbol *GALE*)
- **HGVS:** Human Genome Variation Society
- **MeSH:** Medical Subject Headings
- **MSA:** multiple sequence alignment
- **NAD:** nicotinamide adenine dinucleotide
- **nt:** nucleotide
- **OMIM:** Online Mendelian Inheritance in Man
- **PDB:** Protein Data Bank
- **RefSeq:** NCBI Reference Sequence database
- **UDP:** uridine diphosphate
- **WT:** wild type


## Declarations

**Availability of data and materials:** All data are available in the GitHub repository of group 11DP-F: [https://github.com/martawaa/11DP-F_EDG_IB_2026.git]. The `references/data` folder contains three subfolders: `Blast`, with the sequence alignments; `Provided`, with the FASTA files of the WT and mutant CDS and proteins; and `homologs`, with the FASTA files of the three species (human, mouse and *E. coli*). The structure images and other figures are available in the `figures` folder. The 3D structures are available in the RCSB Protein Data Bank (1EK5 and 1I3N). The *E. coli* protein (NP_415280.3) comes from strain K-12 MG1655, whereas the *E. coli* CDS used for the nucleotide comparison (OZ544371.1) comes from a different strain (RSZYD15081311_A), because the BLASTn search against the K-12 genome returned only genome records and not a CDS. Only 22% of the human CDS aligned with this sequence, so the CDS comparison with *E. coli* should be interpreted with caution.


**Authors' contributions:** Mengxin retrieved the protein accessions and homologues, compared the WT and mutant sequences, linked structure to enzyme function and phenotype, drafted the Methods and Results and integrated the report. Adrià curated the OMIM data, performed the multiple sequence alignment, analysed the structural environment of residue 94, and drafted the Background , the Abstract, keywords and declarations. Alexandra defined the MeSH terms, identified and compared the WT and mutant structures, prepared the figures and tables, and coordinated the final submission. Marta carried out the literature research, analysed conservation and cross-species differences, drafted the Discussion and Conclusions, and managed the Gantt chart. All authors read and approved the final manuscript.


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
17. RCSB Protein Data Bank. Structure of human UDP-galactose 4-epimerase in complex with NAD+. PDB ID: 1EK5. Available at: https://www.rcsb.org/structure/1EK5 (accessed 20 October 2026).
18. RCSB Protein Data Bank. Molecular basis for severe epimerase-deficiency galactosemia: X-ray structure of the human V94M-substituted UDP-galactose 4-epimerase. PDB ID: 1I3N. Available at: https://www.rcsb.org/structure/1I3N (accessed 20 October 2026).
19. IMGT Education. IMGT classes of the 20 common amino acids. Available at: https://www.imgt.org/IMGTeducation/Aide-memoire/_UK/aminoacids/IMGTclasses.html (accessed 22 October 2026).
20. Pommié C, Levadoux S, Sabatier R et al. IMGT standardized criteria for statistical analysis of immunoglobulin V-REGION amino acid properties. J Mol Recognit 2004;17:17–32.
21. Schrödinger, LLC. The PyMOL Molecular Graphics System, Version 3.1. Available at: https://pymol.org/ (accessed 24 October 2026).
22. Thoden JB, Wohlers TM, Fridovich-Keil JL et al. Crystallographic evidence for Tyr 157 functioning as the active site base in human UDP-galactose 4-epimerase. Biochemistry  2000-05, Vol.39 (19), p.5691-5701
23. Thoden JB, Wohlers TM, Fridovich-Keil JL et al. Molecular basis for severe epimerase deficiency galactosemia. X-ray structure of the human V94M-substituted UDP-galactose 4-epimerase. J Biol Chem 2001;276:20617–23.
24. Timson DJ, Lindert S. Comparison of dynamics of wildtype and V94M human UDP-galactose 4-epimerase: a computational perspective on severe epimerase-deficiency galactosemia. Gene 2013;526:318–24.
