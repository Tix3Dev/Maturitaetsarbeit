# Maturitätsarbeit - Graphical Stabilizer Decompositions for Multi-Control Toffoli Gate Dense Quantum Circuits

This repository contains the [PDF document](https://github.com/Tix3Dev/Maturitaetsarbeit/blob/main/Thesis.pdf) which was written in my last year of high-school, as part of the mandatory Maturitätsarbeit:

> In their final year, all high school graduates complete a final paper. This is a larger, written paper or a written commentary on a topic of their own choosing. As a final paper, it shows that the
> high school graduates have learned to delve deeply into a freely chosen topic and to acquire the necessary working methods. The work process, from choosing the topic to structuring the work process
> to presenting the results, is carried out with the support of a teacher. (Original [german version](https://www.mng.ch/unterricht/maturitatsarbeit/))

Additionally, it contains the corresponding [presentation](https://github.com/Tix3Dev/Maturitaetsarbeit/blob/main/Presentation.pdf).

## Abstract

In this thesis, we study concepts in quantum computing using graphical languages, specifically using the ZX-calculus. The core of the research revolves around
(graphical) stabilizer decompositions. The first major focus is on the decomposition of non-stabilizer states created from star edges. We discuss previous results
and then present novel decompositions that yield a theoretical improvement, alongside with evidence that suggests potential applicability to barren plateau detection.
The second major focus is on weighting algorithms, applied to the special class of multi-control Toffoli gate dense quantum circuits. The representation of the
corresponding gates is based on star edges. The applicability of known methods, such as CNOT-grouping, traditionally used for other classes, is examined
in the context of this specific class. We then present a novel weighting algorithm that attempts to determine the best vertex to decompose. A refined version is
implemented to simulate a known class of quantum querying algorithms, which is used to search for causal configurations of multiloop Feynman diagrams. For this case, as
well as for a generalized benchmark consisting of randomly generated quantum circuits, we demonstrate occasional improvements in the final number of terms against traditional methods.
These results are discussed by considering different simplification strategies. This thesis also provides a brief but broad outline of the important preliminaries.

## Links

The following list contains all the external repositories linked throughout the thesis:

- [https://github.com/Tix3Dev/novel_star_state_decompositions](https://github.com/Tix3Dev/novel_star_state_decompositions)
- [https://github.com/Tix3Dev/feynman_loop_diagram_qsim](https://github.com/Tix3Dev/feynman_loop_diagram_qsim)
- [https://github.com/Tix3Dev/rand_multi_ctrl_toff_dense_qcirc_sim](https://github.com/Tix3Dev/rand_multi_ctrl_toff_dense_qcirc_sim)
- [https://github.com/Tix3Dev/unexpected_improv_of_speedy_algo](https://github.com/Tix3Dev/unexpected_improv_of_speedy_algo)
