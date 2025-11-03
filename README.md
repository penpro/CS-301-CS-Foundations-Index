# CS-301 - Foundations of CS - Weekly Index

**Owner:** Wesley Weaver  
**Course:** CS-301 Foundations of Computer Science  
**Purpose:** Central landing page that links to each week’s repo and gives a fast skim of what’s inside (so Future Me can jump straight to the right example).

---

## Quick Links
- Week 1 - Getting started, PSVM anatomy, early expressions -> <https://github.com/penpro/CS301_WeekOne>
- Week 2 - Arrays, StdIn/StdOut, StdDraw, and PageRank client bits -> <https://github.com/penpro/CS301_WeekTwo>
- Week 3 - Chapter 2: Functions (libraries, recursion, classic problems) -> <https://github.com/penpro/CS301_WeekThree>
- Week 4 - Chapter 3: Object Oriented Programming -> <https://github.com/penpro/CS301_WeekFour>
- Week 5 - Chapter 4: Data Structures -> <https://github.com/penpro/CS301_WeekFive>
- Week 6 - Chapter 5: Theory of Computing (5.1-5.2) -> <https://github.com/penpro/CS301_WeekSix>

---

## Week 1 - Warm-up and Chapter 1 Basics
**Highlights**
- PSVM anatomy experiments: removing or misspelling `public`, `static`, `void`, and `args`; captured the exact compiler and runtime messages.  
- Early exercises on expressions, swapping variables, trig identity numeric error, and a first boolean logic evaluation.  
- Multi-argument CLI practice (`UserArgument`) and what actually happens when you pass different arg patterns.

**Why it matters**
- Locks down the Java entry-point contract and builds intuition for compiler vs. runtime errors.
- Sets up later chapters by making the rules of the road concrete.

**Where to look**
- Notes and results are in the repo README; examples live under `src/main`.  
Repo: <https://github.com/penpro/CS301_WeekOne>

---

## Week 2 - Arrays, I/O, and the PageRank Case Study
**Highlights**
- Arrays (1.4): creation, literal initializers, shuffle (Fisher–Yates), common patterns, and pitfalls (zero-based, defaults, `a.length` not `a.length()`).  
- Input/Output (1.5): `StdIn`, `StdOut`, redirection and pipes; patterns for building small filters.  
- StdDraw core usage: coordinate system, double-buffered animation loop.  
- Implementations and utilities in repo: `Banner.java` (console and animation variants), `Stats.java` (mean + sample stddev), `MyBeer.java` (Monte Carlo fixed-point odds), and local copies of `StdIn/StdOut/StdDraw` for convenience.

**Why it matters**
- Arrays and I/O are the backbone of most later exercises.  
- PageRank and Random-Surfer thinking introduces simulation and uniform shuffles.

**Where to look**
- See `README.md` for quick summaries and code pointers.  
Repo: <https://github.com/penpro/CS301_WeekTwo>

---

## Week 3 - Functions (Chapter 2)
**Highlights**
- Designing static methods with clear inputs and outputs and single purpose.  
- Building libraries and clients for modularity (keep I/O thin, computation pure).  
- Recursion patterns: base case first, then shrink the problem.  
- Classic helpers and snippets: Euclid’s GCD (iterative and recursive), Gaussian PDF, stats helpers, coupon collector, factorial, and fast power.

**Why it matters**
- Functions are the main abstraction tool; everything else composes on top of them.  
- Previews larger case studies (percolation, recursion fractals) that rely on clean APIs.

**Where to look**
- The repo README collects snippets and links back to the booksite for details.  
Repo: <https://github.com/penpro/CS301_WeekThree>

---

## Week 4 - Functions (Chapter 3)
- Object Oriented Programming
- Building classes  
**Where to look**  
- The repo README collects snippets and links back to the booksite for details.  
Repo: <https://github.com/penpro/CS301_WeekFour>

---

## Week 5 - Data Structures (Chapter 4)
**Highlights**
- Core ADTs and APIs: `Stack`, `Queue`, `Bag`, `Set`, `Map` and symbol tables.  
- Implementations: linked lists vs. resizing arrays; iterator patterns and `Iterable` for foreach.  
- Symbol tables: ordered vs. unordered, BST and hash-based approaches; load factor and resizing strategy.  
- Cost models: order-of-growth, amortized analysis for resizing arrays; when to choose which ADT.  
- Practical touches: Java generics, `equals` and `hashCode`, common iterator gotchas.

**Why it matters**
- These ADTs are the building blocks for almost every nontrivial client you will write.  
- Understanding implementations helps you predict performance and memory footprints.

**Where to look**
- Repo README for pointers to local implementations and exercises.  
Repo: <https://github.com/penpro/CS301_WeekFive>

---

## Week 6 - Theory of Computing, Part 1 (Chapter 5: 5.1 Formal Languages, 5.2 Turing Machines)
**Highlights**
- Formal languages: symbols, alphabets, strings, languages.  
- Regular expressions and closure properties; equivalence of regex, NFA, and DFA.  
- DFA vs. NFA design, subset construction, product automata tricks, and parity patterns.  
- Turing machines: tape, head, control; read-write-move semantics; accept, reject, and non-termination.  
- Practice tools: regex validators, DFA simulators, and the Princeton TM simulator.  
- Includes detailed Quiz 6 notes in the Week 6 repo (term matching and the parity regex with reasoning).

**Why it matters**
- Gives the conceptual ceiling and floor for what algorithms and programs can do.  
- Prepares you for computability and complexity topics, and sharpens language and automata design skills.

**Where to look**
- Repo has a focused README with runnable snippets and quiz notes.  
Repo: <https://github.com/penpro/CS301_WeekSix>

---

## Reference Links (Booksite and Stdlib)
- Chapter 2 (Functions) - <https://introcs.cs.princeton.edu/java/20functions/>
- Arrays (1.4) - <https://introcs.cs.princeton.edu/java/14array/>
- Input and Output (1.5) - <https://introcs.cs.princeton.edu/java/15inout/>
- PageRank and Random Web Surfer (1.6) - <https://introcs.cs.princeton.edu/java/16pagerank/>
- Algorithms and Data Structures (Chapter 4 hub) - <https://introcs.cs.princeton.edu/40algorithms>  
  - 4.4 Symbol Tables - <https://introcs.cs.princeton.edu/44st>
- Theory of Computing  
  - 5.1 Formal Languages - <https://introcs.cs.princeton.edu/java/51language/>  
  - 5.2 Turing Machines - <https://introcs.cs.princeton.edu/java/52turing/>  
- A Computing Machine (Chapter 6 - TOY) - <https://introcs.cs.princeton.edu/java/60machine/>
- Stdlib overview - <https://introcs.cs.princeton.edu/java/stdlib/>
- Programs index - <https://introcs.cs.princeton.edu/java/code/>

**Useful wiki primers**
- Euclidean algorithm - <https://en.wikipedia.org/wiki/Euclidean_algorithm>  
- Normal distribution - <https://en.wikipedia.org/wiki/Normal_distribution>  
- Coupon collector - <https://en.wikipedia.org/wiki/Coupon_collector%27s_problem>  
- Gray code - <https://en.wikipedia.org/wiki/Gray_code>  
- Longest common subsequence - <https://en.wikipedia.org/wiki/Longest_common_subsequence_problem>  
- Percolation theory - <https://en.wikipedia.org/wiki/Percolation_theory>

---

## How I’m Using This Index
- Each weekly repo has a top-level README with goals, snippets, and gotchas.  
- This index stays short and links forward to the details so it remains skimmable.  
- When a week adds a broadly useful helper, it gets promoted here under Reference Links.

## Conventions
- Java examples assume the Princeton stdlib (`StdIn`, `StdOut`, `StdDraw`) is available in the project.  
- Prefer small drivers and clients that read from stdin and write to stdout (easy to test with redirection).  
- Keep functions single purpose; isolate I/O at the edges.  

---

© 2025 Wesley Weaver - CS-301 Personal Guide
