# Idris2-Multiset-Ternary

[![Idris 2 Verification](https://img.shields.io/badge/Idris_2-0.8.0-blue.svg)](https://www.idris-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Layer 2c Balanced Ternary Algebras, Narayana Polynomials & 3-State Spatial Sifting for Idris 2**

`Idris2-Multiset-Ternary` forms **Layer 2c** of the 10-layer constructive non-linear multiset science framework. It provides balanced ternary algebra ($\mathbb{F}_3$), 3-state spatial logic singletons (`MinusOne`, `Zero`, `PlusOne`), Narayana combinatorial polynomials $N(n, k)$, catalytic partition geometry, tri-state QTT linear state channels, and compile-time `%macro` reflection provers.

---

## 📦 Core Library Architecture & Modules

### 1. `Core.NarayAlphabet`
- **Balanced Ternary Singletons ($\mathbb{F}_3$):** 3-state spatial logic singletons (`MinusOne`, `Zero`, `PlusOne`) representing negative, neutral, and positive spatial polarizations.
- **Narayana Alphabets:** Combinatorial symbol sets for Dyck path sifting and peak counting.

### 2. `Math.NarayanaPolynomial` & `Math.AlgebraOfBoole`
- **Narayana Combinatorial Polynomials:** Exact integer evaluation of Narayana numbers $N(n, k) = \frac{1}{n}\binom{n}{k}\binom{n}{k-1}$.
- **Catalytic Partition Geometry:** Dyck path peak sifting and catalytic partition maps over discrete multiset spaces.
- **Tri-State Boolean Extensions:** 3-state extension of George Boole's algebra mapping ternary truth values to spatial partition boundaries.

### 3. `Linear.NarayState`
- **QTT Linear Ternary State Channels:** Linear state containers (`NarayState`) for tri-state quantum/classical multiset channels, enforcing strict linear resource conservation.

### 4. `Logic.TernaryLogic`
- **Tri-State Logic Gates:** 3-state logic gate matrices, 3-way decision channels, and ternary truth tables.

### 5. `Reflect.NarayElab`
- **Elaborator Macro Reflection:** Compile-time `%macro` reflection provers verifying Narayana polynomial identities and ternary algebraic closure.

---

## 🚀 Building & Installing

```bash
idris2 --build Idris2-Multiset-Ternary.ipkg
idris2 --install Idris2-Multiset-Ternary.ipkg
```

---

## 🔬 Architectural Principles

- **Total Constructivism:** Enforces `%default total` across all ternary logic and Narayana polynomial modules.
- **3-Way Spatial Partitioning:** Balanced ternary singletons (`MinusOne`, `Zero`, `PlusOne`) modeling 3-fold spatial chromogeometric partition geometry.
- **Zero Floating-Point Drift:** Combinatorial Narayana polynomials evaluated via exact integer arithmetic.
