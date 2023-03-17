![small banner](./assets/small-banner.png)
<div align='center'>
  <h3>
    Simple, minimal, aseptic programming language for learning about compilers and program-correctness proofs
  </h3>
</div>

<br/><br/><br/><br/>


## Introduction

This programming language is **heavily** influenced by the one presented on Gries' [The Science of Programming](https://www.amazon.com/Science-Programming-Monographs-Computer/dp/0387964800), introduced as a language small enough so that reasoning about (simple) programs is easier in comparison to more complex languages like C or Java where the syntax sugar specifics or fancy keywords hide the building blocks of imperative programming reasoning. Having an absolutely minimal language allows for precise statements to be made, exploring fundamental yet abstract concepts like _state transformers_ by handcrafting a predicate-based deduction system.

In Gries' book formal logic is used to prove theorems about programs regarding completion, states and correctness. Although most theorems require human deduction abilities, many simple theorems (including loop invariants) can be machine-proved due to the mechanical aspect of the given methodology.

## The project 

The main idea of this repo is that of a personal project. I want to use the ideas from The Science of Programming to create a SmallLang-inspired interpreted language, using the concisely defined grammar to generate a toy compiler. Once the language by itself is consistent, the axiomatization can start: Using [z3](https://github.com/Z3Prover/z3), a theorem prover by Microsoft Research, and given a proper specification, the language can have theorem-proving capabilities by establishing axioms for each statement, and generating valid predicates after their execution.

## Current state

