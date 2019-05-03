# README

This folder contains genetic alignments, XML files and phylogenetic trees generated for the paper *'Emergence of the Zika virus Asian lineage in Angola'* (Hill et al., 2019). This paper is under review as of 25th April 2019.

Below, we provide brief explanations of each of the files:

#### ZIKV genetic alignment
+ `15-11-2018_large.fas`: alignment of three new Angolan ZIKV genomic sequences with 390 other ZIKV genomes publicly available from GenBank. The alignment was generated using [MUSCLE] [1]. 

#### Maximum likelihood tree 
+ `15-11-2018_large-PhyML_tree.tre`: Maximum likelihood phylogeny of the ZIKV alignment, generated using [PhyML v3.1] [2] under a general time reversible nucleotide substitution model, with gamma-distributed among-site rate variation and a proportion of invariant sites (GTR + G + I). 

#### Molecular clock tree 
+ `ZIKV_07-11-2018.large_HKY_BSP_ULC_250E6_combined_10pcburnin.tre`: Maximum clade credibility phylogeny, estimated from the ZIKV genomic alignment using a molecular clock phylogenetic approach implemented in [BEAST v1.10.3.7] [3]. The phylogeny was estimated under a relaxed clock model and a codon-partition (SRD06) nucleotide substitution model.  

#### XML 
+ `ZIKV_15-11-2018.large_HKY_BSP_ULC_250E6_updated.xml`: XML file generated in [BEAUTI] [4] for the above BEAST analysis. 

## Authors
Sarah C Hill (1), Jocelyne Vasconcelos (2), Zoraima Neto (2), Domingos Jandondo (2), Líbia Zé-Zé (3,4), Renato Santana Aguiar (5,6), Joilson Xavier (6), Julien Thézé (1), Marinela Mirandela (2), Ana Luísa Micolo Cândido (2), Filipa Vaz (2), Cruz dos Santos Sebastião (2), Chieh-Hsi Wu (8), Moritz UG Kraemer (1,9,10), Adriana Melo (11), Bruno LF Schamber-Reis (12), Girlene S de Azevedo (11), Amilcar Tanuri (5), Luiza M. Higa (5), Carina Clemente (13), Sara Pereira da Silva (13), Darlan da Silva Candido (1), Ingra M Claro (14), Domingos Quibuco (15), Cristóvão Domingos (16), Bárbara Pocongo (16), Alexander G Watts (17,18), Kamran Khan (17,18,19), Luiz Carlos Junior Alcantara (6,20), Ester C Sabino (14), Eve Lackritz (21), Oliver Pybus (1), Maria-João Alves (3), Joana Afonso (2), Nuno R Faria (1)
1)	Department of Zoology, University of Oxford, U.K.
2)	Instituto Nacional de Investigação em Saúde, Ministry of Health, Luanda, Angola.
3)	Instituto Nacional de Saúde Doutor Ricardo Jorge, Águas de Moura, Portugal.
4)	University of Lisboa, Faculty of Sciences, BioISI - Biosystems & Integrative Sciences Institute, Lisboa, Portugal.
5)	Departamento de Genética, Instituto de Biologia, Universidade Federal do Rio de Janeiro, Brazil.
6)	Departamento de Genética, Ecologia e Evolução, Instituto de Ciências Biológicas, Universidade Federal de Minas Gerais, Brazil.
7)	Instituto Superior de Ciências da Saúde, Universidade Agostinho Neto, Luanda, Angola.
8)	Department of Statistics, University of Oxford, UK
9)	Computational Epidemiology Lab, Boston Children’s Hospital, Boston, USA
10)	Harvard Medical School, Boston, USA
11)	Instituto de Pesquisa Professor Joaquim Amorim Neto (IPESQ), Campina Grande, Brazil. 
12)	Department of Human Genetics, Centro Universitário Unifacisa, Campina Grande, Brazil.
13)	Cligest Clinic, Luanda, Angola.
14)	Instituto de Medicina Tropical e Faculdade de Medicina da Universidade de São Paulo, São Paulo, Brazil.
15)	Hospital Pediátrico David Bernardino, Luanda, Angola
16)	Instituto Nacional de Luta Contra SIDA, Luanda, Angola
17)	Li Ka Shing Knowledge Institute, St. Michael’s Hospital, Toronto, Canada
18)	BlueDot, Toronto, Canada.
19)	Department of Medicine, University of Toronto, Canada
20)	Laboratório de Flavivirus, IOC-Fundação Oswaldo Cruz/MS, Rio de Janeiro, Brazil.
21)	World Health Organization, Switzerland, Geneva

## Abstract of the work (under review)

*Background*
Zika virus (ZIKV) infections and suspected microcephaly cases have been recently reported in Angola, but no data are available on the origins, epidemiology, and diversity of the virus.

*Methods*
Diagnostic samples were tested for ZIKV by RT-qPCR as part of routine arboviral surveillance by the Angolan Ministry of Health. These included serum samples from 54 Serum samples from 54 suspected acute ZIKV infected cases, 76 infants with suspected microcephalysuspected microcephaly cases, and 24 mothers of infants with suspected microcephaly, and 336 patients suspected of acute dengue or chikungunya virus infection.  were received by the Angolan Ministry of Health. All sera were tested for ZIKV by RT-qPCR. To increase the number of ZIKV positive samples available for genomic sequencing, 349 samples from HIV+ patients were also tested for ZIKV. Portable sequencing was used to generate Angolan ZIKV genome sequences from three ZIKV positive individuals, including two cases identified in Angola and one ZIKV+ neonate with microcephaly who was identified in Portugal as part of a separate study. Genetic and mobility data were analysed to investigate the date of introduction and geographic origin of ZIKV in Angola. 

Computed tomographic brain imaging and serological assays (PRNT) were conducted on one microcephalic infant to assess previous ZIKV infection and confirm microcephaly. All sera were tested for ZIKV by RT-qPCR. 349 samples from HIV+ patients and 336 samples from patients suspected of chikungunya virus or dengue virus infection were also tested. Portable sequencing was used to generate Angolan ZIKV genome sequences, including from a ZIKV+ neonate with microcephaly born in Portugal to an Angolan resident. Genetic and mobility data were analysed to investigate the date of introduction and geographic origin of ZIKV in Angola. 

*Findings*
Four autochthonous cases from December 2016 to June 2017 were ZIKV positive via RT-qPCR, with all positive samples collected between December 2016 and June 2017. Viral genomes were generated for two of these cases, and from the neonate with microcephaly identified in Portugal. Genetic Aanalyses of three generated ZIKV genomes and other additional data indicate that ZIKV was likely introduced to Angola from Brazil between July 2015 and June 2016. This introduction likely initiated local ZIKV circulation in Angola that continued until June 2017. The scanned microcephaly case showed brain abnormalities consistent with congenital Zika syndrome and serological evidence for maternal ZIKV infection.

*Interpretation*
Our analyses confirm the autochthonous transmission of the ZIKV Asian lineage in continental Africa. Conducting ZIKV surveillance throughout Africa is critical in the light of presented evidence for autochthonous ZIKV transmission in Angola, and associated microcephaly cases.

*Funding*
Royal Society, Wellcome Trust, CNPq, CAPES, ERC, Oxford Martin School, Global Challenges Research Fund, Africa Oxford, and John Fell Fund. 

[1]: https://www.ebi.ac.uk/Tools/msa/muscle/
[2]: http://www.atgc-montpellier.fr/phyml/versions.php
[3]: http://beast.community/index.html
[4]: http://beast.community/beauti