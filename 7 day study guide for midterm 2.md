# Comprehensive Study Guide for Midterm 2

> Date of Midterm: July 10th 2023
>
> Location: ECS 123
>
> Course: CSC 320

## Checklist

- [ ] **July 2nd, 2023**: Countability.
- [ ] **July 3rd, 2023**: DFA, Closure, NFA.
- [ ] **July 4th, 2023**: Equivalence of NFAs and DFAs, Regular Languages, Regular Expressions.
- [ ] **July 5th, 2023**: DFA State Minimization, Non-Regular Languages.
- [ ] **July 6th, 2023**: Pumping Lemma for Regular Languages.
- [ ] **July 7th, 2023**: Reduction II, Context-Free Grammars, CFG, CNF, PDA.
- [ ] **July 8th, 2023**: Context-Free Languages, Pumping Lemma for Context-Free Languages, Turing Machines.
- [ ]  **July 8th, 2023:** Variants of Turing Machines, Nondeterministic Turing Machines, Enumerators, Church-Turing Thesis.

## Topics

- Countability
- DFA
- Closure
- NFA
- Equivalence of NFAs and DFAs, regular languages are closed under concatenation
- Equivalence of languages of regular expressions and regular languages
- DFA state minimization; non-regular languages
- Pumping Lemma for Regular Languages
- The concept of reduction II; Context-free grammars
- CFG; CNF; PDA
- Models for context-free languages: PDAs, CFGs
- Pumping Lemma for context-free languages
- Turing Machines
- Variants of Turing machines
- Nondeterministic Turing machines, Enumerators, Church-Turing Thesis

| Day  | Topics                                                       | Study Guide                                                  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Countability                                                 | - Countability: ability to assign a unique counting number to elements of a set. Understand countable sets, infinities, and cardinality. |
| 2    | DFA, NFA, Closure                                            | - DFA: definition, transition function, and acceptance. - NFA: differences from DFAs and closure properties. - Closure properties. |
| 3    | Equivalence of NFAs and DFAs, Regular Languages and Expressions | - Equivalence of NFAs and DFAs. - Regular languages: closure under concatenation. - Equivalence of regular expressions and languages. |
| 4    | DFA State Minimization, Non-Regular Languages                | - DFA State Minimization: minimizing states. - Non-regular languages: properties, examples, and limitations. |
| 5    | Pumping Lemma for Regular Languages                          | - Pumping Lemma: proving languages are not regular. Understanding its statement, application, and limitations. |
| 6    | Reduction II, Context-Free Grammars, CFG, CNF, PDA           | - Concept of Reduction II: reducing problems. - Context-free grammars: definition, productions, and derivation trees. - CNF and PDA. |
| 7    | Context-Free Languages, Pumping Lemma for CFLs, Turing Machines | - Pumping Lemma for CFLs. - Turing Machines: components, halting, decidability. - Variants, NTMs, enumerators, and Church-Turing Thesis. |

> **<u>Note:</u>**
>
> Order to learn the specific topics:
>
> 1. Regular Expressions
> 2. Regular Languages
> 3. Non-Regular Languages
> 4. Context-Free Grammars
> 5. Context-Free Languages

## Content 

### **Day 1: Countability**

- Study Guide: Countability refers to the ability to assign a unique counting number to the elements of a set. Understand the concepts of countable sets, countable and uncountable infinities, and cardinality. Learn about bijections and diagonalization.

### **Day 2: Automata Theory (DFA, NFA, Closure)**

- Study Guide:
  - Deterministic Finite Automaton (DFA): Learn about DFAs, their definition, transition function, and accepting states. Understand how to construct a DFA from a given language and how to determine whether a string is accepted by a DFA.
  - Non-deterministic Finite Automaton (NFA): Study NFAs, their definition, transition function, and accepting states. Learn about the differences between DFAs and NFAs and how NFAs can accept languages that DFAs cannot.
  - Closure Properties: Explore the closure properties of regular languages, including closure under union, concatenation, and Kleene star.

### **Day 3: Equivalence and Regular Expressions**

- Study Guide:
  - Equivalence of NFAs and DFAs: Understand the equivalence between NFAs and DFAs. Learn about the powerset construction algorithm to convert an NFA to a DFA.
  - <u>Regular Expressions</u>: Study regular expressions and their relationship to regular languages. Learn how to convert regular expressions to NFAs and vice versa.
  - <u>Regular Languages</u> and Concatenation: Understand that regular languages are closed under concatenation, meaning that if two languages are regular, their concatenation is also regular.

### **Day 4: DFA State Minimization and Non-Regular Languages**

- Study Guide:
  - DFA State Minimization: Learn about the concept of minimizing states in a DFA. Study the algorithm for DFA state minimization and understand the equivalence between DFAs.
  - <u>Non-Regular Languages:</u> Explore non-regular languages that cannot be recognized by any DFA or NFA. Understand their properties and examples, and learn about their limitations.

### **Day 5: Pumping Lemma for Regular Languages**

- Study Guide: The Pumping Lemma is a tool to prove that a language is not regular. Understand the statement of the Pumping Lemma and how to use it to demonstrate that a language is not regular. Learn the steps to apply the Pumping Lemma and recognize its limitations.

### **Day 6: Context-Free Grammars and PDAs**

- Study Guide:
  - Concept of Reduction II: Understand the concept of reduction, particularly in the context of context-free languages. Learn how to reduce problems to other problems and their significance in computational theory.
  - <u>Context-Free Grammars (CFG):</u> Study CFGs, their definition, productions, and derivation trees. Learn how to generate strings and recognize whether a string belongs to a given CFG.
  - Chomsky Normal Form (CNF): Explore Chomsky Normal Form and its role in simplifying CFGs. Understand the rules for transforming CFGs into CNF.
  - Pushdown Automaton (PDA): Study PDAs, their definition, transition function, and acceptance. Learn how to construct a PDA from a given CFG and understand the relationship between PDAs and CFGs.

### **Day 7: Pumping Lemma for Context-Free Languages, Turing Machines, and Church-Turing Thesis**

- Study Guide:

  - Pumping Lemma for <u>Context-Free Languages</u>: Learn about the Pumping Lemma for context-free languages. Understand how it is used to show that a language is not context-free. Study the steps involved in applying the Pumping Lemma for context-free languages and its implications.

  - Turing Machines: Explore Turing Machines (TMs), which are abstract computational models capable of solving a wide range of problems. Understand the components of a TM, including the tape, head, states, and transition function. Learn about the concept of halting, decidability, and the language recognized by a TM.

  - Variants of Turing Machines: Study different variants of TMs, such as multi-tape TMs, non-deterministic TMs, and alternating TMs. Understand the differences and extensions of these models compared to the standard Turing Machine.

  - Nondeterministic Turing Machines: Learn about Nondeterministic Turing Machines (NTMs), which have multiple possible transitions for a given input. Understand the concept of accepting languages by NTMs and their relationship to deterministic TMs.

  - Enumerators: Explore the concept of enumerators, which are abstract devices capable of listing out all the strings in a language. Understand the limitations and capabilities of enumerators and their relationship to Turing Machines.

  - Church-Turing Thesis: Learn about the Church-Turing Thesis, which states that any effectively computable function can be computed by a Turing Machine. Understand the significance of this thesis in defining the boundaries of computability and the theory of computation.