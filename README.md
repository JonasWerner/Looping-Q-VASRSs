Loop Summarization using Rational Vector Addition Systems with Resets in Accelerated Interpolation
==================================================================================================
Analyzing program loops is an important part of multiple software engineering tasks, such
as bug detection, test case generation, and optimization. Loop analysis is, however, one
of the most challenging aspects of program analysis, especially with complex loops that
feature multiple paths and nested loops. A widely used loop analysis technique is computing overapproximative 
loop summaries that represent the relationship between inputs and outputs as a set
of constraints. But overapproximation is prone to imprecision.
Kincaid and Silverman proposed a novel overapproximation approach, based on rational vector addition systems with resets (Q-VASR),
that guarantee a certain degree of precision. In this presentation we will introduce this approach, and
propose an implementation of a new loop summarization library based on Q-VASR,
which we want to integrate in the already implemented accelerated interpolation scheme.