Analyzing program loops is an important part of multiple software engineering tasks, such
as bug detection, test case generation, and optimization. Loop analysis is, however, one
of the most challenging aspects of program analysis, especially with complex loops that
feature multiple paths and nested loops. Computing overapproximative loop summaries is a widely used
loop analyzation technique that represents the relationship between inputs and outputs as a set
of constraints. But, Overapproximation is prone to imprecision.
Kincaid and Silverman proposed a novel overapproximation approach, based on rational vector addition systems with resets (Q-VASR),
that guarantee a certain degree of precision. This project an implements a new loop summarization library based on Q-VASR in the software verification framework Ultimate.
https://ultimate.informatik.uni-freiburg.de