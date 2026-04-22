# Categorical Logic for Proof Generation

## Introduction
 - **problem**: generate a proof of a proposition
 - introduction of Curry-Howard Isomorphism 
 - **problem rephrase**: generate a term from a type

### Simple Type Theory
 - minimal implicational logic + corresponding type theory
 - S and K are enough to generate everything
 - LLMs seem good way to go to generate SK-strings
 - **results**: almost never generate correct terms
 - **reason**: LLMs generate linearly, commit early to search paths 
    (beam search helps, agentic generation, ... *all fail*)
 - Simply typed Type Theory
 - Lawvere functorial semantics

### Generalized Algebraic Theories
 - Introduction to dependent type theory
 - Formal definition
 - Context Categories
 - Functorial Semantics note

### CoC - Categories With Families 
TODO: finish this section 

## Expansion Algorithm
### Formal Definition
 - Presentation of Algorithm
 - Proof of exhaustivity
### Application
 - return to minimal implicational logic
 - explain how implica works
 - show DEMO
### Graph Neural Networks
 - **task**: label nodes to drastically decrease the complexity of the algorithm
 - **model**: Conjecturer Prover 
 - **training loop**

## Conclusions

