The workshop DSB "Data Structures in Bioinformatics" (DSB) is an incubator of ideas and facilitates exchanges as well as collaborations on topics related to data structures in bioinformatics. Speakers will present state of the art techniques and recent advances in this field. Also see the [program of DSB 2015/2016](https://didy.uni-bielefeld.de/DSB2015).

### Dates

* Feb 20 2017: opening dinner
* Feb 21 2017: workshop day 1
* Feb 22 2017: workshop day 2

### Venue

The workshop will take place at [CWI Amsterdam](https://cwi.nl) ([map](https://www.google.nl/maps/place/Centrum+Wiskunde+%26+Informatica/@52.3564651,4.9501773,17z/data=!3m1!4b1!4m5!3m4!1s0x47c60943849abc4f:0x7c49bc3f6dd03051!8m2!3d52.3564651!4d4.952366?hl=en)). There is a direct train connection from Amsterdam Central Station (5 min) and Schiphol airport (30-50 min).
We suggest the nearby hotels [CASA](http://hotelcasa.nl/) (5 min bus ride) and [The Manor](https://www.hampshirehotelmanoramsterdam.com/en) (2 min train ride).

---

### Participants

| Name | Affiliation |
| ---- | ----------- |
| Mai Alzamel | King's College London |
| Lorraine Ayad | King's College London |
| Jasmijn Baaijens | CWI Amsterdam |
| Rayan Chikhi | University of Lille |
| Johannes Fischer | TU Dortmund |
| Guillaume Holley | Bielefeld University |
| Zamin Iqbal | Oxford University / EMBL-EBI |
| Leandro Ishi | INRIA |
| Johannes Köster | CWI Amsterdam |
| Thierry Lecroq | University of Rouen |
| Jasper Linthorst | TU Delft |
| Raquel Manzano | Wageningen University |
| Tom Mokveld | TU Delft |
| Simon Puglisi | University of Helsinki |
| Sven Rahmann | University of Duisburg-Essen |
| Eric Rivals | University of Montpellier |
| Kamil Salikhov | Université Paris-Est Marne-la-Vallée |
| Alexander Schönhuth | CWI Amsterdam |
| Jouni Sirén | Wellcome Trust Sanger Institute |
| Jens Stoye | Bielefeld University |

### Organizing Committee

| Name | Affiliation |
| ---- | ----------- |
| Jasmijn Baaijens | CWI Amsterdam, the Netherlands |
| Johannes Köster | CWI Amsterdam, the Netherlands |
| Alexander Schönhuth | CWI Amsterdam, the Netherlands |

---

### Schedule

TBA

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
**Lorraine Ayad**

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
