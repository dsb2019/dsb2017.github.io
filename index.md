The workshop DSB "Data Structures in Bioinformatics" (DSB) is an incubator of ideas and facilitates exchanges as well as collaborations on topics related to data structures in bioinformatics. Speakers will present state of the art techniques and recent advances in this field. Also see the [program of DSB 2015/2016](https://didy.uni-bielefeld.de/DSB2015).

### Dates

* Feb 20 2017: opening dinner
* Feb 21 2017: workshop day 1
* Feb 22 2017: workshop day 2

### Venue

The workshop will take place at [CWI Amsterdam](https://www.cwi.nl) ([travel information](https://www.cwi.nl/how-reach-cwi-public-transport), [map](https://www.google.nl/maps/place/Centrum+Wiskunde+%26+Informatica/@52.3564651,4.9501773,17z/data=!3m1!4b1!4m5!3m4!1s0x47c60943849abc4f:0x7c49bc3f6dd03051!8m2!3d52.3564651!4d4.952366?hl=en)). There is a direct train connection from Amsterdam Central Station (5 min) and Schiphol airport (30-50 min).
We suggest the nearby hotels [CASA](http://hotelcasa.nl/) (5 min bus ride) and [The Manor](https://www.hampshirehotelmanoramsterdam.com/en) (2 min train ride).

---

### Participants

| Name | Affiliation |
| ---- | ----------- |
| Mohamed Abouelhoda | KACST/KFSHRC, Saudi Arabia |
| Mai Alzamel | King's College London |
| Lorraine Ayad | King's College London |
| Jasmijn Baaijens | CWI Amsterdam |
| Paola Bonizzoni | University of Milano-Bicocca |
| Rayan Chikhi | University of Lille |
| Anthony Cox | Illumina UK |
| Luca Denti | University of Milano-Bicocca |
| Daniel Dörr | Bielefeld University |
| Johannes Fischer | TU Dortmund |
| Ehsan Haghshenas | Simon Fraser University |
| Guillaume Holley | Bielefeld University |
| Leandro Ishi | INRIA |
| Johannes Köster | CWI Amsterdam |
| Thierry Lecroq | University of Rouen |
| Jasper Linthorst | TU Delft |
| Tom Mokveld | TU Delft |
| Marco Previtali | University of Milano-Bicocca |
| Simon Puglisi | University of Helsinki |
| Sven Rahmann | University of Duisburg-Essen |
| Eric Rivals | University of Montpellier |
| Kamil Salikhov | Université Paris-Est Marne-la-Vallée |
| Alexander Schönhuth | CWI Amsterdam |
| Tizian Schulz | Bielefeld University |
| Siavash Sheikhizadeh | Wageningen University |
| Jouni Sirén | Wellcome Trust Sanger Institute |
| Sandra Smit | Wageningen University |
| Jens Stoye | Bielefeld University |
| Tina Zekic | Bielefeld University |

### Organizing Committee

| Name | Affiliation |
| ---- | ----------- |
| Jasmijn Baaijens | CWI Amsterdam, the Netherlands |
| Johannes Köster | CWI Amsterdam, the Netherlands |
| Alexander Schönhuth | CWI Amsterdam, the Netherlands |

---

### Preliminary Schedule

#### Monday, Feb 20 2017

* **19:00:** Opening dinner at restaurant [Nessun Dorma](http://www.osterianessundorma.nl/)

#### Tuesday, Feb 21 2017

**9:00-9:10:** Arrival at CWI

| Start | Speaker | |
| ----- | ------- | ----- |
| 9:10 | Sven Rahmann | From discrete to continuous - new algorithms for fused LASSO on graphs |
| 9:55 | Thierry Lecroq | FM-index of Alignment with Gaps |
| 10:40 | | Coffee Break |
| 11:00 | Jouni Siren | Relative Data Structures |
| 11:45 | Mohamed Abouelhoda | Big Data Challenges for Clinical Bioinformatics |
| 12:30 | | Lunch |
| 14:00 | Eric Rivals | Superstrings, cycles covers, and multiplicities |
| 14:45 | Jasmijn Baaijens | Haplotype-resolved genome assembly using overlap graphs |
| 15:30 | | Coffee Break |
| 16:00 | Rayan Chikhi | Efficient construction of compacted de Bruijn graphs |
| 16:45 | Ehsan Haghshenas | T.B.A. |
| 17:30 | | Open Discussion |

*Each talk of 25 minutes is followed by up to twenty minutes of questions/discussion*

**19:00:** Dinner at restaurant [Tomaz](http://tomaz.nl/)

#### Wednesday, Feb 22 2017

| Start | Speaker | |
| ----- | ------- | ----- |
| 9:00 | Johannes Fischer | New Results on Wavelet Tree/Matrix Construction |
| 9:45 | Siavash Sheikhizadeh | PanTools: representation, storage and exploration of pan-genomic data |
| 10:30 | | Coffee Break |
| 11:00 | Anthony Cox | Data structures for population sequencing projects |
| 11:45 | Jasper Linthorst, Tom Mokveld | Practical algorithms for the creation and use of multi-genome reference graphs |
| 12:30 | | Lunch |
| 14:00 | Kamil Salikhov | ProPhyle – a memory efficient BWT-based metagenomic classifier |
| 14:45 | Mai Alzamel | Palindromic Decompositions with Gaps and Errors |
| 15:30 | Coffee Break |
| 16:00 | Lorraine Ayad | MARS: improving multiple circular sequence alignment using refined sequences |
| 16:45 | | Open Discussion |

*Each talk of 25 minutes is followed by up to twenty minutes of questions/discussion*



### Talks (preliminary)

#### Palindromic Decompositions with Gaps and Errors
**Mai Alzamel**, Michał Adamczyk, Panagiotis Charalampopoulos, Costas Iliopoulos,
and Jakub Radoszewski.

Identifying palindromes in sequences has been an interesting line of research
after the discovery of the relation of palindromes in the DNA sequence with the
HIV virus. Efficient algorithms for the factorisation of sequences into
palindromes and maximal palindromes have been devised in recent years. We
extend these studies by imposing a lower bound to the length of acceptable
palindromes and allowing gaps and errors in the decompositions. We present an
algorithm for obtaining such a palindromic decomposition of a string of length
n with the minimal total gap length in time O(n log n.g) and space O(n.g),
where g is the number of allowed gaps. We further present an O(n (g + 𝛿
))-time and O(n. g)-space algorithm for the decomposition of a string of length
n in maximal palindromes with at most 𝛿 errors each, under the edit or Hamming
distance, and g allowed gaps.

#### New Results on Wavelet Tree/Matrix Construction
**Johannes Fischer**

#### FM-index of Alignment with Gaps
**Thierry Lecroq**, Joong Chae Na, Hyunjoon Kim, Seunghwan Min,
Heejin Park, Martine Leonard, Laurent Mouchard and Kunsoo Park

Recently a compressed index for similar strings, called the
FM-index of alignment (FMA), has been proposed with the functionalities
of pattern search and random access. The FMA is quite efficient in
space requirement and pattern search time, but it is applicable
only for an alignment of strings without gaps. In this talk we propose the
FM-index of alignment with gaps, a realistic index for similar strings,
which allows gaps in their alignment. For this, we design a new version
of the suffix array of alignment by using an alignment transformation
and a new definition of the alignment-suffix. The new suffix array of
alignment enables us to support the LF-mapping and backward search,
the key functionalities of the FM-index, regardless of gap existence
in the alignment.
We experimentally compared our index with RLCSA due to Makinen et al. and
related indexes GCSA due to Siren et al. and GCSA2 due to Siren on genome
sequences from the 1000 Genomes Project. The index size of our index is
smaller than those of other indexes.

#### Relative Data Structures
**Jouni Siren**

Relative data compression encodes the target dataset relative to a similar reference dataset. Given the reference and the target compressed relative to the reference, we can then recover the target dataset. With data structures, we may want to go further than that. Given a data structure for the reference and a relative data structure for the target, we may want to simulate the target data structure efficiently.

In this talk, I will present relative FM-indexes and suffix trees for assembled genomes. I will discuss the techniques used in the data structures and show benchmarks against ordinary FM-indexes and compressed suffix trees.

#### From discrete to continuous - new algorithms for fused LASSO on graphs
**Sven Rahmann**, Elias Kuthe

Frequently, solving a discrete optimization problem is much harder than
the corresponding continuous problem (e.g., general integer linear
programming vs. (continuous) linear programming).

We are interested in very large ("genome-wide") instances of the fused
LASSO problem, a continuous convex optimization problem.
Given a graph G=(V,E), observed data y=(y_v) on the nodes, weights
w=(w_v) on the nodes and weights u=(u_e) on the edges, find values
x=(x_v) on the nodes that are both close to the observed data (quadratic
error) and close to neighboring values (in the l1 sense).

Formally, we seek x to minimize
f(x) := sum_v w_v * (x_v - y_v)^2 + sum_{e={v,v'}} u_e * |x_v - x_v'|.
This particular target function ensures that the solution x is close to
the data y and regionally constant (nonzero differences are sparse).
In principle, standard convex optimization methods will do the job.
However, due to the special structure of the problem (and of the
particular graph in a given application!), one can hope to do much better.
Indeed, on a grid graph this formulation is frequently used for image
denoising.

Here, we consider ladder-like graphs that model a signal across a
chromosome in several individuals belonging to two classes.
Immediate applications include methylation levels and copy number
variations.
We show that a forward-like algorithm efficiently solves a discretized
version of the problem, which is often already sufficient in practice.
We further show that by iteratively refining the discretization, we are
able to solve the continuous problem to any desired accuracy.

This appears to be a rare case where taking the detour via a discrete
problem yields an efficient algorithm for the original continuous problem.
The efficiency of the method, however, crucially depends on the graph
structure.

#### MARS: improving multiple circular sequence alignment using refined sequences.
**Lorraine Ayad**, Solon Pissis

A fundamental assumption of all widely-used multiple sequence alignment techniques is that the left- and right-most positions of the input sequences are relevant to the alignment. However, the position where a sequence starts or ends can be totally arbitrary. This is relevant, for instance, in the process of multiple sequence alignment of mitochondrial DNA, viroid, viral or other genomes, which have a circular molecular structure.

A solution for these inconsistencies would be to identify a suitable rotation (cyclic shift) for each sequence; these refined sequences may in turn lead to improved multiple sequence alignments using the preferred multiple sequence alignment program. MARS is a new heuristic method for improving Multiple circular sequence Alignment using Refined Sequences. The program computes the rotations (cyclic shifts) required to best align a set of input sequences, where the output can then be input into any multiple sequence alignment program.

Experimental results, using real and synthetic data are presented, showing that MARS improves the alignments, with respect to standard genetic measures and the inferred maximum-likelihood-based phylogenies, and outperforms state-of-the-art methods both in terms of accuracy and efficiency.

#### Efficient construction of compacted de Bruijn graphs
**Rayan Chikhi**

The de Bruijn graph is a widely used data structure in
assembly algorithms. Compacting the graph is an important data reduction
step where long simple paths are compacted into single vertices.
Construction of the compacted graph has recently become the bottleneck
in assembly pipelines, and improving its running time and memory usage
is an important problem. In this talk I'll present an algorithm and a
tool BCALM 2 for the compaction of de Bruijn graphs. BCALM 2 is a
parallel algorithm that distributes the input based on a minimizer
hashing technique, allowing for good balance of memory usage throughout
its execution. It is at least an order of magnitude more efficient than
other available methods. Source code: https://github.com/GATB/bcalm

#### ProPhyle – a memory efficient BWT-based metagenomic classifier
Karel Brinda, **Kamil Salikhov**, Simone Pignotti

Metagenomics is a powerful approach to study genetic content of environmental samples
that has been strongly promoted by NGS technologies. A way to improve the
accuracy of metagenomic classification is to match the metagenome against a largest
possible set of known genomic sequences. With many thousands of completed microbial
genomes available today, modern metagenomic projects match their samples
against genomic databases of tens of billions of bp.
To cope with increasingly large metagenomic projects, alignment-free methods
have recently come into use. The most popular tool - Kraken - performs
metagenomic classification of NGS reads based on the analysis of shared k-mers
between an input read and each genome from a pre-compiled database. Kraken
provides an extremely rapid read classification, but its index suffers from two major
limitations. First, Kraken’s enormous memory consumption, due to a large hash
table, does not allow one to perform classification other than on high-performance
clusters. Second, each k-mer K in the index is represented by the lowest common
ancestor of all nodes that contains K, which can result in an inaccurate classification.
We present ProPhyle, a metagenomic classifier based on BWT-index. ProPhyle
uses a classification algorithm similar to Kraken, but with an indexing strategy
based on a bottom-up propagation of k-mers in the tree, assembling contigs at
each node and matching using a standard full-text search. Matching can be done
using two different approaches: “restarted search”, when each k-mer is processed
independently, and “rolling window”, which utilizes the fact that two consecutive
k-mers in a read have a suffix-prefix overlap of length k - 1. The latter approach,
which is based on kLCP data structure, allows to decrease the assignment time
so that it can be comparable to the Kraken’s one. The obtained index occupies
only a fraction of RAM compared to Kraken – 13 GB instead of 120 GB for index
construction and 14 GB instead of 75 GB for index querying. The resulting index is
also more expressive as it can, for every queried k-mer, retrieve a list of all genomes
in which the k-mer occurs.


#### Practical algorithms for the creation and use of multi-genome reference graphs
**Jasper Linthorst**, **Tom Mokveld**

The application of multi-reference representations holds a great promise
for improving the quality of genetic variant detection. We present a
practical algorithm for the construction of multi-genome reference graphs.
We introduce the concept of recursive exact matching and show how this can
be applied to graph-based multi-genome representations. Subsequently we
outline an algorithm that enables the alignment of reads through such a
graph, by indexing all haplotype informed paths.

#### Big Data Challenges for Clinical Bioinformatics
**Mohamed Abouelhoda**

The recent advancement of Next Generation Sequencing technologies in terms of cost, throughput, and accuracy has already changed the clinical practice largely for diagnosis and growingly for treatment. However, the analysis requirements regarding quality, accuracy, speed, and integrated knowledge sources are higher, compared to samples from other organisms. Such sophistications along with the sheer volume of data shape a real big data problem with a number of challenges.
In this talk, we will address a number of computational challenges for processing thousands of samples for large genome projects and for clinical use. We will discuss some criteria for selecting the data management and analysis methods, considering the recent advances in computational infrastructure and storage systems that can help overcoming the Big Data challenge. The discussion will be based on best practices in the Saudi Human Genome Program, which targets to sequence 100,000 genomes over a period of five years. We will also briefly shed light on the still coming challenges with new sequencing techniques and applications in the clinic.

#### Superstrings, cycles covers, and multiplicities.
**Eric Rivals**, Bastien Cazaux

In genome or transcriptome assembly, dealing with repeated sequence
remains a major bottleneck. The number of repeated elements in a genome
varies greatly between species, but both vertebrates and plants often
exhibit a repetitive fraction of their genome that goes beyond 40%.
Reads located in different copies of a repeated region tend to collapse
in a single region, the coverage of which provides an estimation of the
number of copies. It is thus crucial to develop algorithms able to
reconstruct a target sequence and at the same time to satisfy the
constraints imposed by the information on the /multiplicity/ of each
input word, where the multiplicity means the desired number of copies
for each "read". Here, we will describe an algorithm for computing a
cycle cover of a set of input words with multiplicities. This algorithm
uses a specific graph to account for these multiplicities and remains
linear in complexity. It thus provides a way to compute approximate
shortest superstring with multiplicities.

#### Data structures for population sequencing projects
**Anthony Cox**



#### PanTools: representation, storage and exploration of pan-genomic data
**Siavash Sheikhizadeh**, M. Eric Schranz, Mehmet Akdel, Dick de Ridder and Sandra Smit

Thanks to the impressive advances in sequencing technologies, the availability of eukaryotic genome assemblies is growing rapidly. The fact that many species are now represented by multiple (reference) genomes necessitates a transition from single-genome to pan-genome analyses. We define the pan-genome as a comprehensive representation of multiple genomes, facilitating comparative analyses at the nucleotide, gene, and function level. Current pan-genomic approaches do not thoroughly address scalability, functionality, and usability issues. We propose a graph structure consisting of a hierarchy of nucleotide, annotation, and function layers, which is stored in a Neo4j graph database making it scalable to large datasets. We have developed an online algorithm to construct a generalized De Bruijn graph as the nucleotide layer of the pan-genome. In addition, our toolbox PanTools provides useful functionalities for adding new genomes and annotations, retrieving sequence of genes and genomic regions, reconstructing the constituent genomes, and inferring orthology relationships in the pan-genome. Efficiency and accuracy of PanTools have been validated on various eukaryotic data sets.

#### Haplotype-resolved genome assembly using overlap graphs
**Jasmijn Baaijens**, Amal Zine El Aabidine, Eric Rivals, Alexander Schönhuth

While most genome assemblers focus on reconstructing a consensus genome, an even
more challenging task is to find the individual haplotype sequences present in an NGS
sample. These haplotypes can be of high clinical interest, for example when
studying a viral infection: such a sample contains multiple, closely related virus
strains (i.e., a viral quasispecies) which may react differently to a given
medical treatment. We present SAVAGE, a computational tool for
reconstructing individual haplotypes from a polyploid, highly diverse sample.
SAVAGE makes use of the overlap graph assembly paradigm in combination with a
sound statistical model, so that edges in the graph reflect that two reads
originate from identical haplotypic sequences, and iteratively extends contigs
into individual haplotypes. In benchmark experiments on both simulated and real
data, SAVAGE drastically outperforms generic de novo assemblers as well as the
only specialized de novo viral quasispecies assembler so far. When using an
ad-hoc consensus reference, SAVAGE also compares very favorably with the
state-of-the-art reference-guided viral quasispecies assemblers.

#### T.B.A.
**Ehsan Haghshenas**
