# -cmb_plastid-genome_Pterocarpus_BEHANTE

# Characterization of a Plastid Genome: Pterocarpus

## Student Information

**Student Name:** Ivan Behante

**Course/Section:** BIO 300 - A

**Genus:** *Pterocarpus*

**Species:** *Pterocarpus indicus*

**Common Name:** Narra

**Family:** Fabaceae

---

## 1. Genome Information

The plastid genome analyzed in this activity is the complete chloroplast genome of *Pterocarpus indicus* isolate PI1903.

| Information    | Details                              |
| -------------- | ------------------------------------ |
| Organism       | *Pterocarpus indicus* isolate PI1903 |
| Genus          | *Pterocarpus*                        |
| Family         | Fabaceae                             |
| Organelle      | Chloroplast                          |
| NCBI Accession | NC_049082.1                          |
| Genome Type    | Circular DNA                         |
| Genome Size    | 158,107 bp                           |
| RefSeq Status  | Provisional RefSeq                   |
| Completeness   | Full length                          |
| BioProject     | PRJNA927338                          |
| Source         | NCBI Nucleotide / RefSeq             |

The NCBI record identifies NC_049082.1 as the complete chloroplast genome of *Pterocarpus indicus* isolate PI1903. The record is circular and 158,107 bp long. The sequence is marked as full length, and the reference sequence is identical to MT249115.

**NCBI source:**
NCBI Nucleotide record for NC_049082.1

---

## 2. Genome Organization

The *Pterocarpus indicus* chloroplast genome follows the typical quadripartite organization of angiosperm plastid genomes:

* Large Single Copy (LSC)
* Inverted Repeat A (IRa)
* Small Single Copy (SSC)
* Inverted Repeat B (IRb)

The published comparative analysis of five *Pterocarpus* chloroplast genomes confirms this typical four-part structure. Across the five species, LSC regions ranged from 87,789 to 88,460 bp, SSC regions from 18,723 to 19,122 bp, and the IR regions were approximately 25.7 kb each.

The exact overall genome size obtained from Galaxy is **158,107 bp**.

---

## 3. Galaxy Analysis

### Galaxy History

**History Name:** `Plastid_Pterocarpus_Behante`


### Galaxy FASTA Statistics

| Statistic                   |     Result |
| --------------------------- | ---------: |
| Scaffold L50                |          1 |
| Scaffold N50                |    158,107 |
| Scaffold L90                |          1 |
| Scaffold N90                |    158,107 |
| Scaffold maximum length     | 158,107 bp |
| Scaffold minimum length     | 158,107 bp |
| Scaffold mean length        | 158,107 bp |
| Scaffold median length      | 158,107 bp |
| Scaffold standard deviation |          0 |
| Number of A                 |     50,277 |
| Number of T                 |     50,316 |
| Number of C                 |     28,585 |
| Number of G                 |     28,929 |
| Number of N                 |          0 |
| Total bp                    |    158,107 |
| bp excluding N              |    158,107 |
| Number of sequences         |          1 |
| Overall GC content          |     36.38% |
| Contig L50                  |          1 |
| Contig N50                  |    158,107 |
| Contig L90                  |          1 |
| Contig N90                  |    158,107 |
| Contig maximum length       | 158,107 bp |
| Contig minimum length       | 158,107 bp |
| Contig mean length          | 158,107 bp |
| Contig median length        | 158,107 bp |
| Contig standard deviation   |          0 |
| Contig bp                   |    158,107 |
| Contig sequences            |          1 |
| Number of gaps              |          0 |

The Galaxy results show one sequence with a length of 158,107 bp and no ambiguous bases or gaps. The L50 and N50 values are both 1 and 158,107 bp, respectively, because the input consists of a single complete circular plastid sequence.

---

## 4. Gene Content

The annotated chloroplast genome contains **110 unique genes**, consisting of:

* **77 protein-coding genes**
* **29 tRNA genes**
* **4 rRNA genes**

Because the chloroplast genome contains inverted repeats, several genes occur in two copies. Therefore, the number of raw feature entries in the GenBank annotation is higher than the number of unique genes.

The four rRNA genes are:

* rrn16
* rrn23
* rrn4.5
* rrn5

The NCBI annotation shows duplicated rRNA copies in the inverted-repeat regions. For example, rrn16 is present at two separate locations in the record.

---

## 5. Representative Protein-Coding Genes


| Gene     | Functional Group                  | Function                                                                                                         |
| -------- | --------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **psbA** | Photosynthesis                    | Encodes photosystem II protein D1, an important component of photosynthetic electron transport.                  |
| **rbcL** | Carbon fixation                   | Encodes the large subunit of Rubisco, which catalyzes carbon fixation during the Calvin cycle.                   |
| **ndhD** | Photosynthesis/electron transport | Encodes a subunit of the chloroplast NADH dehydrogenase complex involved in photosynthetic electron transport.   |
| **petA** | Cytochrome b6/f complex           | Encodes cytochrome f, a component of the cytochrome b6/f complex that transfers electrons during photosynthesis. |
| **atpA** | ATP synthesis                     | Encodes the alpha subunit of chloroplast ATP synthase.                                                           |
| **rpoB** | Gene expression                   | Encodes the beta subunit of the chloroplast DNA-dependent RNA polymerase.                                        |
| **rpl2** | Translation                       | Encodes ribosomal protein L2, a component of the large ribosomal subunit.                                        |
| **accD** | Fatty-acid metabolism             | Encodes the beta subunit of acetyl-CoA carboxylase, involved in fatty-acid biosynthesis.                         |

These genes demonstrate that the plastid genome contains genes involved in photosynthesis, carbon fixation, energy production, transcription, translation, and metabolism.

---

## 6. RNA Genes and Introns

The genome contains **29 unique tRNA genes** and **4 unique rRNA genes**. The rRNA genes are rrn16, rrn23, rrn4.5, and rrn5.

Several chloroplast genes contain introns. The comparative Pterocarpus study identified genes with one or two introns, including **atpF, matK, ndhA, ndhB, ndhI, petB, petD, rpl16, rpl2, rpoC1, rpoC2, rps12, trnA-UGC, trnI-GAU, trnK-UUU, trnL-UAA, trnV-UAC, ycf68, ycf3, and clpP**. The study also reports that the ycf1 intron found in some Pterocarpus species is absent in *P. indicus*.

The **rps12** gene is notable because it is trans-spliced, with its coding regions separated between different parts of the chloroplast genome. The NCBI record specifically annotates rps12 as a trans-spliced gene.

---

## 7. Pseudogenes, Duplications, and Structural Features

No pseudogene or pseudo qualifier was identified in the supplied NCBI GenBank annotation.

Several genes occur in two copies because they are located within the inverted-repeat regions. Examples include:

* rpl2
* rpl23
* rps7
* ndhB
* rrn16
* rrn23
* rrn4.5
* rrn5
* selected tRNA genes
* ycf68

The presence of duplicated genes in the IR regions is a normal feature of many angiosperm plastid genomes rather than necessarily indicating a recent duplication event.

The *Pterocarpus* genomes have a conserved quadripartite organization. The published study also identified rps19, rpl2, ndhF, ycf1, and trnH around important LSC, SSC, and IR junctions. In *P. indicus*, ycf1 spans the SSC and IRa junction.

---

## 8. GC Content

The Galaxy analysis produced an overall GC content of **36.38%**.

The nucleotide composition was:

* A = 50,277
* T = 50,316
* C = 28,585
* G = 28,929
* N = 0

**GC = 36.38%**

**AT = 63.62%**

The plastid genome is therefore AT-rich. This is consistent with the published characterization of Pterocarpus chloroplast genomes, which reported approximately 63.61-63.69% A/T content.

---

## 9. Plastid Genome vs. Mitochondrial Genome

| Feature                         | Plastid Genome                                                     | Mitochondrial Genome                                                                 |
| ------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| Cellular location               | Chloroplast/plastid                                                | Mitochondrion                                                                        |
| Main function                   | Photosynthesis, carbon fixation, and plastid gene expression       | Cellular respiration, ATP production, and mitochondrial gene expression              |
| Organization                    | Usually circular and quadripartite in land plants                  | Usually circular, but can have complex multipart structures                          |
| Relative size                   | Usually around 120-170 kb in flowering plants                      | Usually highly variable and often larger in plants                                   |
| Gene content                    | Photosynthesis, ribosomal, tRNA, and housekeeping genes            | Mainly respiration-related genes, rRNAs, tRNAs, and some other genes                 |
| Copy number                     | Usually multiple copies per chloroplast                            | Usually multiple copies per mitochondrion                                            |
| Inheritance                     | Commonly maternal in angiosperms                                   | Commonly maternal in angiosperms                                                     |
| Recombination/structural change | Generally more conserved                                           | Often more structurally dynamic                                                      |
| Mutation/substitution pattern   | Generally relatively conserved, especially in IR regions           | More variable and often affected by structural rearrangements                        |
| Common applications             | Phylogeny, DNA barcoding, plant identification, population studies | Phylogeny, maternal lineage studies, mitochondrial function and evolutionary studies |

### Five similarities

1. Both are organellar genomes.
2. Both contain their own DNA and genes.
3. Both encode rRNAs and tRNAs.
4. Both are present in multiple copies within cells.
5. Both can be used for phylogenetic and evolutionary studies.

### Five differences

1. Plastid genomes contain genes associated with photosynthesis, while mitochondrial genomes primarily contain genes associated with respiration.
2. Plastid genomes of flowering plants are generally more structurally conserved than plant mitochondrial genomes.
3. Plastid genomes commonly show the LSC-IR-SSC-IR organization.
4. Plant mitochondrial genomes can be much larger and structurally more complex than plastid genomes.
5. Plastid genomes are particularly useful for plant DNA barcoding and chloroplast phylogenomics.

---

## 10. Practical Value, Limitations, and Research Questions

### Practical Value

The characterization of the *Pterocarpus indicus* chloroplast genome provides useful molecular information for plant identification, phylogenetic analysis, population studies, conservation, and DNA barcoding. Complete plastid genomes can also help distinguish closely related species and identify useful variable regions.

The Pterocarpus study identified several highly variable regions that may serve as DNA barcode candidates, including regions involving **ycf1, accD, rpoC2, ccsA, and trnF-related sequences**. Complete chloroplast genomes can therefore contribute to species discrimination and timber identification.

### Limitations

The chloroplast genome represents only one organellar genome and therefore does not represent the complete nuclear genetic variation of the species. Chloroplast inheritance is also often uniparental, so it may provide limited information about biparental gene flow. In addition, genome annotations may differ between databases and annotation pipelines.

### Possible Research Questions

1. How does the chloroplast genome of *Pterocarpus indicus* differ from other *Pterocarpus* species?
2. Which chloroplast regions are most useful for distinguishing closely related *Pterocarpus* species?
3. Can complete plastid genomes improve the identification of illegally harvested *Pterocarpus* timber?
4. How conserved are the IR regions among *Pterocarpus* species?
5. What chloroplast markers are most informative for studying the evolutionary history of the genus?

---

## References

Hong, Z., Wu, Z., Zhao, K., Yang, Z., Zhang, N., Guo, J., Tembrock, L. R., & Xu, D. (2020). Comparative Analyses of Five Complete Chloroplast Genomes from the Genus *Pterocarpus* (Fabaceae). *International Journal of Molecular Sciences, 21*(11), 3758.

NCBI Nucleotide. *Pterocarpus indicus* isolate PI1903 chloroplast, complete genome. RefSeq accession NC_049082.1.

Galaxy Project. FASTA Statistics analysis of *Pterocarpus indicus* chloroplast genome.

---

## Reproducibility Statement

The analysis can be reproduced by downloading the complete chloroplast genome of *Pterocarpus indicus* from NCBI using accession **NC_049082.1**, uploading the FASTA sequence to Galaxy, and running FASTA Statistics.

Galaxy history used for this activity:

`Plastid_Pterocarpus_Behante`

The resulting statistics should produce one sequence with a length of 158,107 bp, 36.38% GC content, and zero gaps.
