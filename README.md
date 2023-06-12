# (CSC 320) Foundations of Computer Science - Complete Notes - Summer 2023

[TOC]

- [Course Intro (syllabus)](#course-intro--syllabus-)
  * [Topics](#topics)
  * [Outcomes](#outcomes)
  * [Grading and due dates](#grading-and-due-dates)
    + [Quizzes](#quizzes)
    + [Assignments](#assignments)
    + [Midterms // Exams](#midterms----exams)
  * [Handling of late Quizzes and Assignments](#handling-of-late-quizzes-and-assignments)

# Course Intro (syllabus)

> Professor Name: Ulrike Stege
>
> Email: ustege@uvic.ca
>
> Office: ECS 624
>
> Office hours:
>
> - Monday 3:30pm - 4:30pm
> - Thursday 2:30pm - 3:30pm 
>
> Tutorials start May 8th 

## Topics 

- Formal definitions of computation, languages and computability
- Models of Computation: finite state automata, pushdown automata, grammars and Turing machines; deterministic and non-deterministic machines
- The Halting Problem, reductions, and NP-completeness
- Dealing with intractability (if time permits)

## Outcomes

- understand and analyze when it is possible to solve a problem computationally
- understand and prove when a problem is undecidable
- understand and illustrate how limitations on computational resources limit the class of problems that can be solved
- understand and apply models of computation for different problems in the Chomsky hierarchy
- characterize and analyze computational problems that are tractable
- characterize and prove computational problems that are intractable
- characterize the class of problems solvable in a model
- understand what it means for models of computation to be equivalent
- understand and apply reductions to prove intractability and undecidability of problems
- transform an automaton into a different equivalent representation, and vice versa

## Grading and due dates

### Quizzes

| **Quiz** | **Due date** | **Weight** |
| -------- | ------------ | ---------- |
| Quiz 1   | May 12       | 1%         |
| Quiz 2   | May 19       | 1%         |
| Quiz 3   | May 26       | 1%         |
| Quiz 4   | Jun 02       | 1%         |
| Quiz 5   | Jun 09       | 1%         |
| Quiz 6   | Jun 23       | 1%         |
| Quiz 7   | Jun 30       | 1%         |
| Quiz 8   | Jul 07       | 1%         |
| Quiz 9   | Jul 21       | 2%         |

### Assignments

| **Assignment** | **Assigned on** | **Due Date** | **Weight** |
| -------------- | --------------- | ------------ | ---------- |
| Assignment 1   | May 15          | May 20       | 5%         |
| Assignment 2   | May 25          | May 30       | 5%         |
| Assignment 3   | Jun 22          | Jun 27       | 5%         |
| Assignment 4   | Jun 29          | Jul 05       | 5%         |
| Assignment 5   | Jul 20          | Jul 25       | 5%         |

### Midterms // Exams

| **Exam**   | **Date** | **Duration** | **Weight** |
| ---------- | -------- | ------------ | ---------- |
| Midterm 1  | Jun 12   | 50 min       | 10%        |
| Midterm 2  | Jul 10   | 50 min       | 15%        |
| Final Exam | TBA      | 3 hours      | 40%        |

## Handling of late Quizzes and Assignments

To accommodate for potential difficulties keeping deadlines such as illness, note below. Note that **no other accommodations** will be made.

> <u>**Quizzes**</u>
>
> There are 9 **timed** quizzes. Each quiz is available throughout a 24-hour window. Once you start the quiz, you will need to complete it in the given time window.
>
> For quizzes 1 to 8, every student can miss at most one quiz. The weight of the missed quiz will be distributed evenly over the remaining quizzes. For other missed quizzes a grade of 0 will be assigned.

> <u>**Assignments**</u>
>
> There are 5 assignments.
>
> A late penalty of 3% is imposed for every hour of handing in an assignment late. For assignments 1 to 4, every student can miss at most one assignment. The weight of the missed assignment will be distributed evenly over the remaining assignments. For other missed assignments, a grade of 0 will be assigned.

> <u>**Midterms**</u>
>
> There are 2 midterms. Everyone can miss up to one midterm. The weight of the missed midterm will be added onto the weight of the final exam. For another missed midterm, a grade of 0 will be assigned.

## Lectures & Tutorials

- **Lectures** are taught in-person
- Each lecture will be streamed via zoom
- Lectures are recorded and posted
- I **strongly recommend** to attend every lecture live (in-person or online)
-  **Tutorials** are taught **online**
- Tutorials are not recorded
- I s**trongly recommend** to attend the weekly tutorials (starting week of May 08)

> If you are worried, feel unwell or have symptoms, participate online. We are working hard on providing a good hybrid experience for you.

## Operation & Team

- Course on Brightspace; assessment on Crowdmark
- Regularly check Brightspace & Crowdmark for reading materials, lecture slides, deadlines, assessments
- Instructor: Dr. Ulrike Stege
- TAs: 
  - Sajed Karimy
  - Ivan Perez Martell
  - Luke Trinity
  - Stella Zarei

## Office hours—in-person or online

> First Office Hours: May 8

- Instructor’s office hours (times: subject to change) 
- Zoom link on Brightspace (same as for lecture)
  - Mondays: 2:30pm—3:30pm 
  - Thursday: 3:30pm—4:30pm
- ECS 624

## Pre-requisites for CSC 320— Foundations of Computer Science

![image-20230517221443593](assets/image-20230517221443593.png)

## Foundations of Computer Science: Why this course?

- What can we do with (classical) computers?
- What are the limitations of (classical) computing?

## Foundations of Computer Science: Why this course?

![image-20230517221514207](assets/image-20230517221514207.png)

## Foundations of Computer Science—What’s that?

- Study **fundamental nature** of (classical) **computation**
- What **problems** are **solvable** using a (classical) **computer**?
- We **need to know** answers to
  - What exactly is a **problem**? 
  - What exactly is a **solution to a problem?** 
  - How do we **model** a **computer**?

> Note: 
>
> In our context, solving a problem means: 
>
> - answer the question posed in the problem exactly/ perfectly

## Remaining Outline for today’s lecture

- Expected Course and Learning Outcomes
- Administrative announcements 
- Academic Integrity
- Some basics and background

## CSC 320 Learning Outcomes

- An understanding of the following:
  - What are the fundamental capabilities and limitations of computers?
  -  What makes some problems computationally hard and others easy?
- Topics discussed are in the following areas: (Computational models from three perspectives)
  - Automata theory
  - Computability theory
  - Complexity theory

> CSC 225, 226: Theory of **algorithms**

## Automata Theory: Examples of Automata

- Finite automata
  - Used in text processing, compilers, hardware design, appliances, …
- Pushdown automata (or context-free grammars)
  - Used in programming languages, artificial intelligence
- Turing machines
  - Model of our “conventional” computer

## Some Terminology

> **Unsolvable** or **undecidable**
>
> problems not solvable using our (standard/classical) computing model (independent of resource limitations)

> **Easy** **to solve**
>
> problems solvable in polynomial time (using our standard/classical computing model)

> **Hard to solve:**
>
> problems solvable (in theory, using our standard computing model) but (likely) not solvable in polynomial time (using our standard/classical computing model)

## After completion of the course: You will be able to answer questions such as:

- Are there any problems that—no matter how powerful the computer/no matter how much time you have—your computer would not not be able to solve?
- Is it decidable (ie., is there a computation that allows us to decide), in **Conway's Game of Life**, whether given an initial pattern and another pattern, the latter pattern can ever appear when starting from the initial one?

## Conway’s Game of Life

- Example of a cellular automaton
- Played on an infinite two-dimensional rectangular grid of cells
- Each cell can be either alive or dead
- Status of each cell c changes each turn of the game (generation) depending on the statuses of c's (eight) neighbors: cells that touch c, either horizontal, vertical, or diagonal from that cell
- Initial pattern: first generation
- Next generation: evolves from applying given rules simultaneously to every cell on the game board 
  - If the cell is alive, then it stays alive if it has either exactly 2 or exactly 3 live neighbors 
  - If the cell is dead, then it is “born” only if it has exactly 3 live neighbors

![image-20230517222511378](assets/image-20230517222511378.png)

![image-20230517222536624](assets/image-20230517222536624.png)

## After completion of the course: You will be able to answer questions such as

- Are there any problems that—no matter how powerful the computer/no matter how much time you have—your computer would not not be able to solve?
- Is it decidable (ie., is there a computation that allows us to decide), in **Conway's Game of Life**, whether given an initial pattern and another pattern, the latter pattern can ever appear when starting from the initial one?
- Is it decidable, given a finite set of tile types, to determine whether there is an arrangement of them with adjacent sides matching that tiles the plane? (**The Tiling Problem**)
- Is it possible to design an algorithm that is the perfect antivirus software, that is a software that decides for any current or future software whether or not the software can act like a virus?
- Is it possible to design a perfect debugger (an algorithm that that, among other bugs, catches infinite loops)?
- Is there an algorithm that schedules exams over a limited time period, such that no student is scheduled to take two or more exams at the same time?

> If the answer is yes to one or more such questions, we ask whether there exists an algorithm that is tractable, that is it returns the solution in an acceptable amount of time.

## Big (but unachievable) goals ….

- Universal debuggers
- Universal interpreters
- Universal malware detectors

## Course Topics

- Formal definitions of computations, languages and computability 
- Models of computation
  - Finite automata, pushdown automata, Turing machines
  - Grammars 
  - Deterministic and non-deterministic machines
- Undecidability, Decidability, Church-Turing Thesis 
  - The Halting problem 
  - Reductions
- Complexity theory
  - **P = NP?** NP-hardness, NP-completeness
  - Polynomial-time reductions
- If time permits: Dealing with NP-hardness; quantum computing

## Related Questions

- If at all: what type of problems can humans solve of the ones that are not solvable by (classical) computers?
- Can computers (eg: robots, conversational agents) act as humans?

## Turing Machines, Turing Test, Conversational Agents

- Turing test (developed by A. Turing,1950) 
- First conversational agent: ELIZA (J. Weizenbaum, 1966)
- Today: many conversational agents:
  - IBM Watson Jeopardy 
  - Siri 
  - Cortana
  - Alexa 
  - Google Assistant
  - Chatbots

## Where to find Information, Course Materials, Assessments

- Official Course Outline
- Brightspace
- Crowdmark

## Deadlines; Assessment

![image-20230517223403884](assets/image-20230517223403884.png)

> Accommodation for potential difficulties keeping deadlines due to illness Note: No other accommodation will be made

### Quizzes

There are 9 timed quizzes. Each quiz is available throughout a 24-hour window. Once you start the quiz, you will need to complete it in the given time window.
For quizzes 1 to 8, every student can miss at most one quiz. The weight of the missed quiz will be distributed evenly over the remaining quizzes. For other missed quizzes a grade of 0 will be assigned.

### Assignments

There are 5 assignments.
A late penalty of 3% is imposed for every hour of handing in an assignment late. For assignments 1 to 4, every student can miss at most one assignment. The weight of the missed assignment will be distributed evenly over the remaining assignments. For other missed assignments, a grade of 0 will be assigned.

### Midterms

There are 2 midterms. Everyone can miss at most one midterm. The weight of the missed midterm will be added onto the weight of the final exam. For another missed midterm, a grade of 0 will be assigned.

## Textbook, Prerequisites

- Book: Introduction to the Theory of Computation by M. Sipser

## Questions about the course, assignments, content, …?

- Consult in the following order 
  - Course outline/Brightspace/Lecture Notes 
  - Instructor in office hours or TA in tutorials 
  - If unresolved: email (ustege@uvic.ca) 
    - Always: CSC 320 in subject line
    - Use your UVic preferred email

## Questions about marking

### Grade change requests

- Within one week of grades posted
- In my office hours or email to me (ustege@uvic.ca)
- Specific question/argument why your answer is correct/deserves your mark
- Present your knowledge

## Today’s Theory of (Classical) Computation …

- is based on the Church-Turing Thesis

> Fall 2018
>
> Any real-world computation can be translated into an equivalent computation involving a Turing machine

- resource constraints (time, space) are ignored
- **Turing** **machine**: abstract model of (classical) computer

> Today
>
> Does Quantum Computing add computational power?

## Assuming that any problem that can be computed can be translated into a Turing machine computation …

- then there must be a Turing machine computation for every problem that we can compute
- What if there are **more problems** that we would like to compute **than** there are **Turing machine computations?**
- Then, there would be **problems** that are **not computable** by a Turing machine

> We will learn that problems exist that are not computable/decidable by a Turing machine (eg: Halting problem)

## Countable and uncountable

- A set is **countable** if it is **finite** or **countably infinite**: the elements of a countable set can always be counted one at a time; every element of the set is associated with a unique natural number
- There exists a **bijection** between any **countably infinite** set and the **set of natural numbers** ℕ
- There exists a **bijection** between any **finite set** and a **finite subset of** ℕ
- A set that is neither finite nor countably infinite is **uncountable**

## Let’s count some sets

- By definition N is countable

- Lets count the set of all integers Z
- How do we enumerate all elements in Z?

| N    | Z    |
| ---- | ---- |
| 0    | 0    |
| 1    | -1   |
| 2    | 1    |
| 3    | -2   |
| 4    | 2    |
| 5    | -3   |
| 6    | 3    |

- Let’s first list them

![image-20230517224258525](assets/image-20230517224258525.png)

![image-20230517224313137](assets/image-20230517224313137.png)

### Counting ℚ+∖{0}

- We found a way to enumerate all rational numbers without getting stuck in infinity
- Enumeration algorithm above defines bijection with ℕ

> Note: 
>
> Counting row by row (or alternatively column by column) would never reach all numbers—since we would never leave the first row (column)

### Cantor’s Diagonalization Argument

**Proof by contradiction:** Assume: R is countable. 

If is countable then we can enumerate, eg, the set of all real numbers between 0 and 1:

![image-20230517224503262](assets/image-20230517224503262.png)

![image-20230517224544586](assets/image-20230517224544586.png)

![image-20230517224559134](assets/image-20230517224559134.png)

#### Conclusion

![image-20230517224632696](assets/image-20230517224632696.png)

## Terminology Review: Sets

> **A Set**
> $$
> S = \{3, l, 20, \text{{green}}, \delta\}
> $$
>
> - Objects in a set: elements / Members

> **Membership / Non-Membership**
> $$
> \alpha \in S, \quad \beta \notin S
> $$

> **Empty Set**
> $$
> \emptyset
> $$

> **Singleton Set** 
>
> - Set with exactly one pair 

> **Unordered Pair**
>
> - Set with exactly two members

## Terminology Review: Set Operations

- Union of sets A and B: 

$$
A \cup B = \{x|x \in A \text{ or } x \in B\}
$$



- Intersection of sets A and B:

$$
A \cap B = \{x|x \in A \text{ and } x \in B\}
$$



- Complement of set A: $$

$$
A' = \{x|x \notin A\}
$$



- Set difference of sets A and B:

$$
A \setminus B = \{x \in A : x \notin B\}
$$



## More terminology: Powerset

- Powerset P(A) of set A: Set of all subsets of A

$$
P(A) = \{S|S \subseteq A\} \quad \text{Note that} \quad \emptyset \in P(A)
$$



## Alphabets, Languages, Strings, Symbols

Terminology to describe and work with finite automata and more:

- An **alphabet Σ** is a **finite** set of **symbols**
  - For example, the binary alphabet is {0,1} or the Roman/Latin alphabet
- A **string** over an alphabet Σ is a finite sequence of symbols from Σ
  - 0001 is a string over alphabet {0,1}
- The **empty string** ε is the string with no symbols

## Alphabets, Languages, Strings, Symbols (2)

- The set of all strings over an alphabet is denoted Σ*
- Note: ε ∈ Σ*, i.e., ε is a string over any alphabet
- Example: Let Σ = {a,b}. Then Σ* = {ε, a, b, aa, ab, ba, bb, aaa, aab, aba, abb, baa, bab, bba, bbb, …}

## Alphabets, Languages, Strings, Symbols (3)

- The length |w| of a string w ∈ Σ* is the number of symbols of w when considered as a sequence
- For example, length of the empty string ε: |ε| = 0
- For a string w = ab, |w| = 2
- For a string w ∈ Σ*, the symbol in the ith position of w is denoted wi. We say that wi occurs in position i of w
- Note that a symbol may occur more than once in the same string. For example, for w = aba, w2 = b.

## Alphabets, Languages, Strings, Symbols (4)

#### Operations and relations on strings

- Concatenation for strings x and y yields string xy
- Concatenation is an associative operation: xyz := (xy)z = x(yz)
- For example, for Σ = {a, b, c} , if x = ab, y = bac, and z = bba : xyz = abbacbba

## Alphabets, Languages, Strings, Symbols (5)

#### More operations and relations on strings

- String v is a substring of string w if and only if there are strings x and y such that w = xvy
- If y = ε then w = xv and v is a suffix of w
- If x = ε then w = vy and v is a prefix of w
- For example, if w = abbacbba then:
  - cbba is a suffix of w
  - abb is a prefix of w

------

## Alphabets, Languages, Strings, Symbols (6)

#### And more operations and relations on strings

- A string written backwards is denoted w^R and called the reversal of w
- For example, If w = abbacbba then w^R = abbcabba

## Didn’t we say we wanted to study problems and their solutions?

- A (decision or yes/no) problem is a mapping from a set of problem instances to Yes/No (called yes-instances and no-instances)
- Languages: abstract representation of problems
- For a problem Π, the associated language LΠ is

$$
LΠ = \{x \in \Sigma^* \, | \, x \text{ is a yes-instance of } \Pi\}
$$

## Examples: Yes-No-Problems and their Languages

#### Sorted sequence

- **Input**:  A list of n comparable elements e_1, e_2, ..., e_n
- **Question**: Are the elements, as given, in sorted order? That is: is it true that e_1 <= e_2 <= .. <= e_n?

L_SORTED SEQUENCE = {list of comparable elements L | the elements of L are in sorted order}

#### Connected Graph

- **Input**: A simple, undirected graph G = (V, E)
- **Question**: Is G connected? That is: for any pair of vertices x, y ∈ V, does there exists a path from x to y in G?

L_CONNECTED GRAPH = {G = (V, E) | G is a simple, undirected connected graph}

#### Short Spanning Tree

- **Input**: A simple, undirected, edge-weighted graph G = (V, E) where each edge e ∈ E is assigned a positive integer weight w(e), an integer k
- **Output**: Does there exist a spanning tree T = (V, ET) for G where T has weight at most k? That is: T is a tree, ET ⊆ E, and

$$
\sum_{e \in E_T} w(e) \leq k
$$

L_SHORT SPANNING TREE = {(G = (V, E), k) | k is a positive integer and G is a
simple, undirected, edge-weighted graph has a spanning tree of weight at most k}

## Languages / Yes/No problems: How many are there?

- To figure this out, since the set of all languages over an alphabet is defined as the set of all subsets of , first Σ 
- Determine the size of Σ* for any alphabet Σ

## How large is the entire alphabet?

Claim: Σ* is countably infinite (and therefore countable)
Proof for Σ = {0,1}:

| N    | Σ*   |
| ---- | ---- |
| 0    | ε    |
| 1    | 0    |
| 2    | 1    |
| 3    | 00   |
| 4    | 01   |
| 5    | 10   |
| 6    | 11   |
| ...  | ...  |

## How large is the set of all languages over Sigma?

-  Recall: Σ* is countably infinite (and therefore countable) 

- and: Languages are subsets of Σ*
- Then the set of all languages over alphabet Σ is the set of all subsets of
  Σ*

$$
\mathcal{P}(\Sigma^*)
$$

- For every language L: L is countably infinite or finite
- How large is the set of all languages over alphabet Σ?

$$
\left| \mathcal{P}(\Sigma^*) \right|
$$



## The Powerset of sigma star equals ?

- Idea: Show that powerset of any countably infinite set is uncountable
- This would imply that the powerset of P(Σ*) is uncountable

> - Recall: Any countably infinite set has a bijection with ℕ, that is Σ* has a bijection with ℕ
> - Therefore, if we show that P(ℕ) is uncountable then we know that P(Σ*) is uncountable, ie uncountably infinite

## Powerset of the Natural Numbers is uncountable

![image-20230611161409223](assets/image-20230611161409223.png)

## How large is the set of all languages?

We recap:

- Since
  P(ℕ) is uncountably infinite, the powerset of any countably infinite set is uncountable
- Since the set of all languages is the powerset of Σ*, the set of all languages is uncountable

# Finite Automata & Regular Languages

- Understanding computability requires
  - Model(s) of computer that capture(s) its computational power
- Most simple model
- **Finite state machine** or **finite automaton**
- Model of computation with **finite amount of memory**, independent of problem size

## Finite Automata

- Finite automata are all around us! Example: electromechanical devices
- Controller of an automatic door

![image-20230611162028398](assets/image-20230611162028398.png)

## Finite Automata in Practice

- Automatic door controller: a finite automaton/computer with just a single bit of memory that records which of the two states the controller is in (closed or open)
- Many other common devices have controllers with somewhat larger memories
- **Elevator controller** 
  - state represents floor elevator is on 
  - inputs: signals received from the buttons 
- **Controllers for various household appliances**
  - dishwashers, electronic thermostats, parts of simple digital watches and simple calculators

## Other Applications of Finite Automata

- Pattern recognition

- Speech recognition
- Optical character recognition
- Compilers
- A (probabilistic) relative of the finite automaton: Markov chain

## Abstract Description of the Finite Automaton

- **State diagrams:** used to describe finite automata
- Formal Definition: **Deterministic finite automaton**

## State Diagram

![image-20230611163119525](assets/image-20230611163119525.png)

![image-20230611163136180](assets/image-20230611163136180.png)

## Formal Definition of Deterministic Finite Automaton

![image-20230611163653001](assets/image-20230611163653001.png)

## L+ vs L*

- Σ = {a, b, c} 
- L = {a, bc} 
- L* = represents the Kleene star operation applied to L, which means it includes all possible concatenations and repetitions of strings from L, including the empty string. In this case, L* would include the strings "", "a", "bc", "aa", "abc", "bca", "bcbc", "aaabc", and so on.
- L+ =  represents the positive closure operation applied to L, which means it includes all possible concatenations and repetitions of strings from L, excluding the empty string. In this case, L+ would include the strings "a", "bc", "aa", "abc", "bca", "bcbc", "aaabc", and so on.

> **Note:** 
>
> - L* includes the empty string
>
> - L+ does not include the empty string.



# DFAs (Deterministic Finite Automata)

## Language of a Deterministic Finite Automaton

- Let M = (Q, Σ, 𝛿, q0, F) be a DFA and A be the set of all strings that M accepts
  - A is called the language of machine M
  - L(M) = A
  - M recognizes language A

> Note:
>
> A machine that accepts no string recognizes empty language ∅

## Example: Language L(M) of DFA M

L(M) = {w|w ∈ Σ* of length at least 1 where: if w starts with symbol 1 then w is of length at least 2}

![image-20230611172509981](assets/image-20230611172509981.png)

## DFA: Formal Definition of Computation

Let M = (Q, Σ, 𝛿, q0, F) be a DFA and let w = w_1,w_2 … w_n be a
string over . Then M accepts w if there is a sequence of states r_0,r_1,r_2, … , r_n in Q such that:

1. r_0 = q_0
2. 𝛿(r_i, w_i+1) = r_i+1
3. r_n ∈ F

M recognizes language L if L = L(M) = {w ∈ | M accepts w}

- A language L is called a **regular language** if there exists a DFA that recognizes L



## Computation of DFA—Example Sequence of states for w = 001101

![image-20230611172753025](assets/image-20230611172753025.png)

## Computation of DFA—Example Sequence of states for w = 0011011

![image-20230611172807648](assets/image-20230611172807648.png)

## Regular languages

- Given DFA M, language L(M) is **exactly the set of all strings that M accepts**
- L(M) is a regular language

## Example: Language of DFA M

- L(M) = {w|w ∈ Σ* of length at least 1 where: if w starts with symbol 1 then w is of length at least 2}
- L(M) is a regular language

![image-20230611173006456](assets/image-20230611173006456.png)

## Regular languages—what we know so far

- **A language L is called a regular language if there exists a deterministic finite automaton that recognizes L**
- The set of languages that are recognized by the set of all DFAs, the **regular languages**, is a **subset of the set of all languages**

## Example 1: Is this a DFA?

![image-20230611173116732](assets/image-20230611173116732.png)

Answer: No

## Example 2: Is this a DFA?

![image-20230611173139354](assets/image-20230611173139354.png)

Answer: yes

## Regular Languages: Closure Properties

- Definition: closed
- Operations: union, intersection, concatenation

## Closure Properties for Sets

- A **set** is **closed** under some operation if applying that operation to elements of the set returns another element of the set
- If a certain operation applied to **any language** in a certain **class of languages** (ex. the class of regular languages) produces a result that is also in that same class, then the language class (eg, the class of regular languages) is **closed under this operation**

## Regular Languages: Closure Properties

- We show: regular languages are closed under
  - Union 
  - Intersection
  - Concatenation

#### Union

- **<u>Theorem</u>**: If L1 and L2 are regular languages over alphabet Σ then L1 ∪ L2 is a regular language. In other words: The class of regular languages is closed under the union operation

  - **<u>Proof (Part A)</u>**: Since L_1 and L_2 are regular languages there exist deterministic finite automata M_1 and M_2 with L_1 = L(M1) and L_2 = L(M2)

  - **<u>Idea</u>**: Construct DFA M that accepts exactly the strings accepted by M_1 and the strings accepted by M_2

  - <u>**Proof (Part B):**</u> Since L_1 and L_2 are regular languages there exist DFA M_1 and M_2 with L_1 = L(M_1) and L_2 = L(M_2)

  - <u>**Idea:**</u> Construct DFA M that accepts exactly the strings accepted by M1 and the strings accepted by M2
    - We do this by simulating both machines concurrently, and accepting if (at least) one of them accepts

![image-20230611174139815](assets/image-20230611174139815.png)

![image-20230611174346572](assets/image-20230611174346572.png)

#### Intersection

- Theorem:

  - Proof:

  - Idea:

#### Concatenation



Proof continued

Why does M recognize L_1 ∪ L_2?

# Major Topics for Midterm 1

## Checklist

- [ ] Countable vs  Uncountable
- [ ] Deterministic Finite Automaton (DFA)
- [ ] DFA state minimization
- [ ] Non-deterministic Finite Automata (NFA)
- [ ] Equivalence of NFAs and DFAs
- [ ] Reductions
- [ ] Regular languages 
- [ ] Closure properties of regular languages
- [ ] Regular languages are closed under concatenation
- [ ] Non-regular languages
- [ ] Regular Expressions 
- [ ] The languages of regular expressions are exactly the regular languages
- [ ] Pumping Lemma
- [ ] PL for Regular Languages
- [ ] PL for Non-regular Languages 
- [ ] Context-free Languages and grammars
- [ ] Context-free grammars
- [ ] Ambiguous grammars
- [ ] Context-free languages
- [ ] Inherently ambiguous languages
- [ ] Pushdown Automata
- [ ] Chomsky Normal Form
- [ ] Pumping Lemma for context-free languages


## Countable vs  Uncountable

## Deterministic Finite Automaton (DFA)

### DFA state minimization

## Non-deterministic Finite Automata (NFA)

### Equivalence of NFAs and DFAs

## Reductions

## Regular languages 

### Closure properties of regular languages

### Regular languages are closed under concatenation

## Non-regular languages

## Regular Expressions 

### The languages of regular expressions are exactly the regular languages

## Pumping Lemma

### PL for Regular Languages

### PL for Non-regular Languages 

## Context-free Languages and grammars

### Context-free grammars

#### Ambiguous grammars

### Context-free languages

#### Inherently ambiguous languages

### Pushdown Automata

### Chomsky Normal Form

### Pumping Lemma for context-free languages



# Quick Reference / Cheat Sheet



## DFA, NFA and PSA Tuples

$$
DFA = (Q, \Sigma, \delta, q_0, F)
$$

$$
NFA = (Q, \Sigma, \delta, q_0, F)
$$

$$
PSA =(Q, \Sigma, \Gamma, \delta, q_0, Z, F)
$$

## Topics / Definitions



| Topic                                    | Overview                                                     | Cheat Sheet                                                  |
| ---------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Countable vs. Uncountable                | Countable sets have the same cardinality as the natural numbers, while uncountable sets have a higher cardinality. | - Countable sets: Integers, rational numbers.<br> - Uncountable sets: Real numbers, power set of natural numbers. |
| Deterministic Finite Automaton (DFA)     | A DFA is a finite state machine where each transition is uniquely determined by the current state and input symbol. | - Formal Definition: 5-tuple (Q, Σ, δ, q0, F).<br> - DFA Diagram: Graph representation of states and transitions. |
| DFA State Minimization                   | DFA state minimization reduces the number of states in a DFA while preserving the language it recognizes. | - Hopcroft's Algorithm: Minimize DFA using partitioning of states.<br> - Merge equivalent states to reduce DFA size. |
| Non-deterministic Finite Automaton (NFA) | An NFA is a finite state machine allowing multiple possible transitions for a given state and input symbol. | - Formal Definition: 5-tuple (Q, Σ, δ, q0, F).<br> - NFA Diagram: Graph representation with ε-transitions. |
| Equivalence of NFAs and DFAs             | NFAs and DFAs recognize the same class of languages; every NFA has an equivalent DFA that recognizes the same language. | - Subset Construction: Convert NFA to DFA.<br> - Determinization: Transform NFA to an equivalent DFA. |
| Reductions                               | Reductions establish the computational complexity of problems by mapping instances of one problem to another. | - Polynomial Time Reductions: Mapping instances of one problem to another in polynomial time. |
| Regular Languages                        | Regular languages are recognized by finite automata (DFA/NFA) and generated by regular expressions. | - Closure Properties: Union, concatenation, Kleene star.<br> - Regular Operations: Combining regular languages. |
| Non-regular Languages                    | Non-regular languages cannot be recognized by finite automata (DFA/NFA) or described by regular expressions. | - Examples: The language of balanced parentheses.<br> - Non-regular languages require more powerful machines. |
| Regular Expressions                      | Regular expressions are a concise way to describe regular languages using symbols and operators. | - Operators: Union (                                         |
| Pumping Lemma                            | The Pumping Lemma is a tool to prove that certain languages are not regular by finding contradictions. | - For Regular Languages: Show pumping length, split strings, and prove the contradiction.<br> - For Non-regular Languages: Find a contradiction using the properties of regular languages. |
| Context-free Languages and Grammars      | Context-free languages are recognized by pushdown automata (PDA) and described by context-free grammars (CFGs). | - CFGs: Rules with non-terminals and terminals to generate strings.<br> - PDAs: Extended finite automata with a stack. |
| Ambiguous Grammars                       | Ambiguous grammars have multiple parse trees for a single string, leading to ambiguity in the language's structure. | - Ambiguity Resolution: Modify grammar rules or use precedence/associativity rules to resolve ambiguity. |
| Inherently Ambiguous Languages           | Inherently ambiguous languages cannot be represented by any unambiguous grammar, regardless of its complexity. | - Examples: Language of arithmetic expressions.<br> - These languages have inherent structural ambiguity. |
| Pushdown Automata (PDA)                  | PDAs extend finite automata with a stack for memory, enabling the recognition of context-free languages. | - Formal Definition: 7-tuple (Q, Σ, Γ, δ, q0, Z, F).<br> - Stack Operations: Push, pop, and peek. |
| Chomsky Normal Form                      | Chomsky Normal Form is a standard form for context-free grammars where all production rules have specific forms. | - Each production rule is either A → BC or A → a, where A, B, and C are non-terminals, and a is a terminal. |
| Pumping Lemma for Context-free Languages | The Pumping Lemma for context-free languages is used to prove that certain languages are not context-free. | - Split strings into uvwxy, show how to pump, and find a contradiction.<br> - Context-free languages have restrictions on pumping. |
