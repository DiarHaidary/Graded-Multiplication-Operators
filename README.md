# Graded-Multiplication-Operators
The following 4 proofs are formalized in Lean: 

[SparseStack](SparseStack.pdf): [PALOMAR-2026-08-23-000004 v1](https://palomar-registry.org/entry?id=PALOMAR-2026-08-23-000004&version=1)

[SRHT](SRHT.pdf): [PALOMAR-2026-09-09-000003 v1](https://palomar-registry.org/entry?id=PALOMAR-2026-09-09-000003&version=1)

[Graph Matrices](Graph%20Matrices.pdf): [PALOMAR-2026-09-08-000005 v1](https://palomar-registry.org/entry?id=PALOMAR-2026-09-08-000005&version=1)

[Spectral Norms of Independent-Entry Matrices with Regular Moment Growth](Spectral%20Norms%20of%20Independent-Entry%20Matrices%20with%20Regular%20Moment%20Growth.pdf): [PALOMAR-2026-09-14-000006 v1](https://palomar-registry.org/entry?id=PALOMAR-2026-09-14-000006&version=1)

For SRHT, there is another proof by [Yang](https://github.com/yuningyang19/OpenProblemsInNLA_TR-01/blob/ed21181197ac839eac95f549404f94e7e3aa6e10/manuscript.pdf).
For Graph Matrices, there is another proof by [Xu et al.](https://arxiv.org/abs/2609.14266v1).

Motivated by a common proof chain in the first three proofs, the [Calculus](Overlap-Aware%20Calculus%20for%20Polynomial%20Random%20Matrices.pdf) was developed. Due to its breadth, it was abandoned to a narrower [framework](Graded%20Multiplication%20Operators%20for%20Random-Matrix%20Moments.pdf) which might be useful for researchers. **The framework is not yet formalized in Lean**. It has been audited multiple times by different LLMs. The appendices include self-contained proofs of these 4 problems. The proof manuscripts are formalized in Lean so it was decided to not make any changes to them; the appendices resolve the same conjectures, but with better constants, using the improvements that were naturally obtained during the development of the framework.
