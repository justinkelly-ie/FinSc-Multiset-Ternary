# FinSc-Multiset-Ternary

[![Idris 2 Verification](https://img.shields.io/badge/Idris_2-0.8.0-blue.svg)](https://www.idris-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Layer 2b Balanced Ternary Algebras, Narayana Polynomials & 3-State Spatial Sifting for Idris 2**

`FinSc-Multiset-Ternary` forms **Layer 2b** of the 10-layer constructive non-linear multiset science framework. Built on top of the discrete foundations of `FinSc-Multiset-Core`, it provides balanced ternary algebra ($\mathbb{F}_3$), 3-state spatial logic singletons (`MinusOne`, `Zero`, `PlusOne`), Narayana combinatorial polynomials $N(n, k)$, catalytic partition geometry, tri-state QTT linear state channels, and compile-time `%macro` reflection provers.

---

## 📦 Core Library Architecture & Staged Modules

### Stage 0: Ground Balanced Ternary Singletons & QTT State Channels
- **`Stage0.NarayAlphabet`:** Balanced ternary singletons ($\mathbb{F}_3$: `MinusOne`, `Zero`, `PlusOne`) representing negative, neutral, and positive spatial polarizations; combinatorial symbol sets for Dyck path sifting and peak counting.
- **`Stage0.NarayState`:** Quantitative Type Theory (QTT) linear state channels (`NarayState`) for tri-state quantum/classical multiset channels, enforcing strict linear resource conservation.
- **`Stage0.NarayElab`:** Compile-time elaborator macro reflection provers verifying Narayana polynomial identities and ternary algebraic closure.

### Stage 1: Combinatorial Polynomials & 3-State Spatial Logic
- **`Stage1.NarayanaPolynomial`:** Exact integer evaluation of Narayana numbers $N(n, k) = \frac{1}{n}\binom{n}{k}\binom{n}{k-1}$; Dyck path peak sifting and catalytic partition maps over discrete multiset spaces.
- **`Stage1.AlgebraOfBoole`:** 3-state extension of George Boole's algebra mapping ternary truth values to spatial partition boundaries.
- **`Stage1.TernaryLogic`:** Tri-state logic gate matrices, 3-way decision channels, and balanced ternary truth tables.

---

## 🚀 Building & Installing

Built with Idris 2 (`0.8.0`) via `pack`:

```bash
pack build FinSc-Multiset-Ternary.ipkg
pack install FinSc-Multiset-Ternary.ipkg
```

---

## 🔬 Architectural Principles

- **Total Constructivism:** Enforces `%default total` across all ternary logic and Narayana polynomial modules.
- **3-Way Spatial Partitioning:** Balanced ternary singletons (`MinusOne`, `Zero`, `PlusOne`) modeling 3-fold spatial chromogeometric partition geometry.
- **Zero Floating-Point Drift:** Combinatorial Narayana polynomials evaluated via exact integer arithmetic.
- **2LTT Staged Modularity:** Clean separation between ground alphabet singletons (`Ternary.Stage0`) and polynomial/logic operators (`Ternary.Stage1`).
