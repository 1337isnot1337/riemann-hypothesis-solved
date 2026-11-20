# Levent Alpöge’s announcement

On November 20, 2026, Levent Alpöge announced that he and Claude had found and formalized proofs of the Riemann Hypothesis and the Generalized Riemann Hypothesis for Dirichlet L-functions. His note describes how iterated theta lifts enter the argument and releases the formalization in fourteen archive parts. [Original announcement (PDF)](https://alpo.ge/remark.pdf)

The project’s [entry point](extracted/lean/src/Main.lean) declares Mathlib’s `RiemannHypothesis` and results about Dirichlet L-functions, including that their zeros in the open critical strip have real part \(1/2\). The definitions are in [Statements.lean](extracted/lean/src/Statements.lean).

The fourteen parts run from [`part01`](https://alpo.ge/lean.tar.gz.part01) through [`part14`](https://alpo.ge/lean.tar.gz.part14). The concatenated gzip archive used for this mirror has SHA-256 `9631b4f020199e580ba86178cb56c6e9b09f690c2369a80dc4334aa93f49c7fc`.
