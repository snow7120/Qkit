# qkit: Quantum information tools for studying chaos and entanglement

A self-study project in computational physics. I am building a small,
tested Python toolkit for quantum information, and using it to study
entanglement and quantum chaos, working towards the SYK model and
black-hole-inspired toy models.

## Motivation

Quantum information concepts such as entanglement, scrambling, and chaos
are central to modern work on holography and the black hole information
problem. This project builds the numerical tools from scratch to understand
these ideas by computing them directly.

## Status

- [ ] Phase 0: toolkit (Paulis, partial trace, entropies, Haar sampling)
- [ ] Phase 1: Page curve for random states
- [ ] Phase 2: spin chains and level statistics
- [ ] Phase 3: SYK model
- [ ] Phase 4: scrambling (OTOCs)

## Project structure

- `qkit/`: library code (linear algebra helpers, entropies, random states)
- `tests/`: unit tests
- `notebooks/`: experiments and plots

## Conventions

- Qubit 0 is the leftmost tensor factor.
- Logarithms are natural (a Bell state has entropy ln 2).
- Kets are shape `(d,)` arrays; density matrices are `(d, d)`.

## References

- Nielsen and Chuang, *Quantum Computation and Quantum Information*
- Preskill, Ph219 lecture notes