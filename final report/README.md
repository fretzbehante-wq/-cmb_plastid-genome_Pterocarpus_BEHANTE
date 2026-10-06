# CHARACTERIZATION OF A PLASTID GENOME

## *Pterocarpus indicus* Chloroplast Genome

**Student Name:** Fretz Ivan Behante

**Course/Section:** BIO 300 - A

**Genus:** *Pterocarpus*

**Species:** *Pterocarpus indicus*

**Family:** Fabaceae

**NCBI Accession:** NC_049082.1

**Galaxy History:** `Plastid_Pterocarpus_Behante`

---

### 1. What is the scientific name, family, accession number, source, and genome size of the plastid genome?

The scientific name of the organism analyzed is *Pterocarpus indicus* isolate PI1903, a member of the family Fabaceae. The chloroplast genome was obtained from the NCBI Nucleotide database under RefSeq accession **NC_049082.1**. The genome is a complete, circular chloroplast DNA molecule with a total length of **158,107 bp**. The NCBI record identifies it as a full-length chloroplast genome.

**Answer:**

* Scientific name: *Pterocarpus indicus*
* Family: Fabaceae
* Accession: NC_049082.1
* Source: NCBI Nucleotide / RefSeq
* Genome size: 158,107 bp
* Topology: Circular
* Organelle: Chloroplast

---

### 2. What evidence shows that the sequence is a complete plastid genome?

The NCBI record is explicitly titled **“Pterocarpus indicus isolate PI1903 chloroplast, complete genome.”** It also identifies the molecule as circular and 158,107 bp long. The record further states **“COMPLETENESS: full length.”**
The Galaxy analysis also supports the completeness of the sequence because only one sequence was obtained, with a length of 158,107 bp, no N bases, and no gaps.

---

### 3. What is the overall organization of the plastid genome?

The *Pterocarpus indicus* chloroplast genome follows the typical quadripartite organization of flowering plant plastid genomes. It consists of a **Large Single Copy region (LSC), Inverted Repeat A (IRa), Small Single Copy region (SSC), and Inverted Repeat B (IRb)**.

The published comparison of five *Pterocarpus* chloroplast genomes confirms this four-part organization. Across the five species, the LSC ranged from 87,789 to 88,460 bp, the SSC from 18,723 to 19,122 bp, and the IR regions were approximately 25.7 kb each.
The general organization was **LSC → IRa → SSC → IRb**,
with the two IR regions containing duplicated sequences.

---

### 4. What is the gene content, and why are some genes duplicated?

The genome contains **110 unique genes**, having;
* **77 protein-coding genes**
* **29 tRNA genes**
* **4 rRNA genes**

The four rRNA genes are rrn16, rrn23, rrn4.5, and rrn5. The NCBI annotation shows two copies of several genes because the inverted-repeat regions contain duplicated genetic material. For example, rrn16 occurs in both IR regions.
The duplication of genes in the IR regions contributes to the higher number of individual annotation features compared with the number of unique genes.

---

### 5. Give at least eight protein-coding genes from different functional groups and state their functions.

| Gene     | Functional Group                  | Function                                                                                |
| -------- | --------------------------------- | --------------------------------------------------------------------------------------- |
| **psbA** | Photosynthesis                    | Encodes photosystem II protein D1 involved in photosynthetic electron transport.        |
| **rbcL** | Carbon fixation                   | Encodes the large subunit of Rubisco involved in CO₂ fixation.                          |
| **ndhD** | Photosynthetic electron transport | Encodes a subunit of the NADH dehydrogenase complex.                                    |
| **petA** | Cytochrome b6/f complex           | Encodes cytochrome f involved in electron transfer.                                     |
| **atpA** | ATP synthesis                     | Encodes the alpha subunit of chloroplast ATP synthase.                                  |
| **rpoB** | Transcription                     | Encodes the beta subunit of chloroplast RNA polymerase.                                 |
| **rpl2** | Translation                       | Encodes ribosomal protein L2.                                                           |
| **accD** | Metabolism                        | Encodes the beta subunit of acetyl-CoA carboxylase involved in fatty-acid biosynthesis. |

These genes demonstrate that the plastid genome is involved in several important processes including photosynthesis, carbon fixation, energy production, transcription, translation, and metabolism.

---

### 6. What RNA genes and introns are present?

The genome contains **29 unique tRNA genes** and **4 unique rRNA genes**. The rRNA genes are rrn16, rrn23, rrn4.5, and rrn5.

The Pterocarpus comparison identified several genes with introns. Genes with one or two introns include **atpF, matK, ndhA, ndhB, ndhI, petB, petD, rpl16, rpl2, rpoC1, rpoC2, rps12, trnA-UGC, trnI-GAU, trnK-UUU, trnL-UAA, trnV-UAC, ycf68, ycf3, and clpP**. The ycf1 intron present in some Pterocarpus species is absent from *P. indicus*.

The **rps12** gene is also notable because it is trans-spliced. The NCBI annotation explicitly identifies its CDS as trans-spliced.

---

### 7. Are there pseudogenes, gene losses, duplications, or unusual structural features?

No pseudogene qualifier was identified in the supplied NCBI GenBank record.

Several genes are duplicated because they are located within the inverted-repeat regions. These include genes such as **rpl2, rpl23, rps7, ndhB, rrn16, rrn23, rrn4.5, and rrn5**, as well as several tRNA genes.

One notable feature is the **ycf1** gene, which spans the SSC and IRa junction. The Pterocarpus comparison also identifies rps19, rpl2, ndhF, ycf1, and trnH around the major region boundaries.

The genome retains the typical quadripartite plastid structure, so no major unusual rearrangement is evident from the supplied record.

---

### 8. What is the GC content, and what does it indicate?

The Galaxy FASTA Statistics result gave an overall GC content of **36.38%**.

Nucleotide composition:

* A = 50,277
* T = 50,316
* C = 28,585
* G = 28,929
* N = 0

The calculated AT content is **63.62%**, indicating that the genome is AT-rich.

Galaxy output:

* Total length = 158,107 bp
* Number of sequences = 1
* Number of gaps = 0
* Number of N bases = 0
* N50 = 158,107 bp
* L50 = 1

The GC result is consistent with published Pterocarpus chloroplast genomes, which were reported to have approximately 63.61-63.69% A/T content.

---

### 9. Give five similarities and five differences between plastid and mitochondrial genomes.

#### Similarities

1. Both are organellar genomes.
2. Both contain their own DNA.
3. Both encode rRNAs and tRNAs.
4. Both are present in multiple copies within cells.
5. Both are useful for evolutionary and phylogenetic studies.

#### Differences

1. Plastid genomes contain genes associated with photosynthesis, whereas mitochondrial genomes mainly contain genes associated with cellular respiration.
2. Plastid genomes of flowering plants are generally more conserved structurally than plant mitochondrial genomes.
3. Plastid genomes commonly have an LSC-IR-SSC-IR organization.
4. Plant mitochondrial genomes can be much larger and structurally more complex.
5. Plastid genomes are particularly useful for plant DNA barcoding and chloroplast phylogenomics.

---

### 10. What is the practical value and what research questions can be developed from this genome?

The characterization of the *Pterocarpus indicus* chloroplast genome provides useful molecular information for **species identification, phylogenetic analysis, conservation studies, population genetics, and DNA barcoding**.

This is especially useful for *Pterocarpus* because several species are economically valuable timber trees. Comparative chloroplast studies have identified variable regions that may be useful for species discrimination and timber identification. The ycf1 region and other variable regions have been investigated as potential DNA barcodes for Pterocarpus species.

However, the chloroplast genome represents only one organellar genome and does not capture the full nuclear genetic variation of the species. Chloroplast inheritance is also commonly uniparental, which can limit its ability to represent biparental gene flow.

### Possible research questions

1. How does the chloroplast genome of *P. indicus* differ from other *Pterocarpus* species?
2. Which chloroplast regions are most effective for distinguishing closely related *Pterocarpus* species?
3. Can complete chloroplast genomes improve the identification of illegally harvested *Pterocarpus* timber?
4. How conserved are the inverted-repeat regions within the genus?
5. Which chloroplast genes or regions are most useful for reconstructing the evolutionary history of *Pterocarpus*?

---

# Plastid vs. Mitochondrial Genome Comparison

| Feature                         | Plastid Genome                                               | Mitochondrial Genome                                                      |
| ------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------- |
| Cellular location               | Chloroplast/plastid                                          | Mitochondrion                                                             |
| Main function                   | Photosynthesis and plastid metabolism                        | Cellular respiration and ATP production                                   |
| Organization                    | Usually circular and often quadripartite in plants           | Circular, linear, or multipartite structures may occur                    |
| Relative size                   | Usually about 120-170 kb in flowering plants                 | Highly variable and often larger in plants                                |
| Gene content                    | Photosynthetic, ribosomal, tRNA, and housekeeping genes      | Respiratory, ribosomal, tRNA, and other mitochondrial genes               |
| Copy number                     | Multiple copies per chloroplast                              | Multiple copies per mitochondrion                                         |
| Inheritance                     | Commonly maternal in angiosperms                             | Commonly maternal in angiosperms                                          |
| Recombination/structural change | Generally conserved                                          | More structurally dynamic                                                 |
| Mutation/substitution pattern   | Generally conserved, particularly within IR regions          | More variable with frequent structural changes                            |
| Common applications             | DNA barcoding, plant identification, phylogeny, conservation | Maternal lineage, phylogeny, mitochondrial evolution, respiration studies |

---

# Galaxy Results Summary

**Galaxy History:** `Plastid_Pterocarpus_Behante`

| Parameter           |     Result |
| ------------------- | ---------: |
| Genome length       | 158,107 bp |
| Number of sequences |          1 |
| GC content          |     36.38% |
| AT content          |     63.62% |
| A                   |     50,277 |
| T                   |     50,316 |
| C                   |     28,585 |
| G                   |     28,929 |
| N                   |          0 |
| Number of gaps      |          0 |
| N50                 |    158,107 |
| L50                 |          1 |

---

# Conclusion

The chloroplast genome of *Pterocarpus indicus* isolate PI1903 is a complete circular plastid genome with a length of **158,107 bp** and an overall GC content of **36.38%**. Galaxy analysis confirmed that the uploaded sequence consisted of one complete sequence without gaps or ambiguous bases.

The genome has the typical quadripartite organization of flowering plant chloroplast genomes and contains **110 unique genes**, including **77 protein-coding genes, 29 tRNAs, and 4 rRNAs**. Several genes are duplicated within the inverted-repeat regions, while genes such as rps12 show specialized structural characteristics such as trans-splicing.

Overall, the *P. indicus* plastid genome provides valuable molecular information for studying plant evolution, species identification, conservation, DNA barcoding, and the genetic relationships of the genus *Pterocarpus*.

---

# References

Hong, Z., Wu, Z., Zhao, K., Yang, Z., Zhang, N., Guo, J., Tembrock, L. R., & Xu, D. (2020). Comparative Analyses of Five Complete Chloroplast Genomes from the Genus *Pterocarpus* (Fabaceae). *International Journal of Molecular Sciences, 21*(11), 3758.

NCBI Nucleotide. *Pterocarpus indicus* isolate PI1903 chloroplast, complete genome. RefSeq accession NC_049082.1.

Galaxy Project. FASTA Statistics analysis of *Pterocarpus indicus* chloroplast genome.

NCBI Reference Sequence database.

