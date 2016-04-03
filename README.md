# dismathportfolio-Jer2j
dismathportfolio-Jer2j created by Classroom for GitHub
## Week 1:
- In the very first week, I was introduced to a strange but interesting subject called DISMATH.
- Answering exercises in the book will help masterize the lessons.
- I discovered what "Discrete Mathematics" is all about.
- I learned that the subject focuses on mathematical truths instead of scientific or probable truths.
- I also learned that a proposition is a declarative statement which must be true or false.
- Some examples are: DLSU is along Taft Avenue; 2 + 1 = 3.
- Logical connectives were discussed as foundations of this subject.
- Statements, especially with only few variables, can be proven by using Truth table.
- At first, I was anxious because of the unfamiliar symbols used in math.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- The last thing I learned before the end of the first week was PROPOSITIONAL LOGIC.
  - Inverse of p → q: ¬p → ¬q
  - Converse of p → q: q → p
  - Contrapositive of p → q: ¬q → ¬p

## Week 2:
- In the second week, I was introduced to a set of new laws that would be used throughout this course.
- I learned another method of evaluating logical statements aside from Truth table, which is logical equivalences.
- LOGICAL EQUIVALENCES:

|                           Equivalence                          |         Name        |
|:--------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p  //     p v F ≡ p               |    Identity laws    |
|                       p v T ≡ T  //    p ∧ F ≡ F               |   Domination laws   |
|                       p v p ≡ p //     p ∧ p ≡ p               |   Idempotent laws   |
|                            ¬(¬p) ≡ p                           | Double negation law |
|                   p v q ≡ q v p // p ∧ q ≡ q ∧ p               |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) // (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)   |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) //  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q // ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p // p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T // p ∧ ¬p ≡ F                   |    Negation laws    |

- I had my first homework about Superman logic, and it was challenging.
- Superman does not exist logically!
- After discussing logical equivalences, the lesson shifted to QUANTIFIERS.
  - Two types are:
  - UNIVERSAL (∀x) - should be true to all values; predicate is true for every element under consideration.
  - EXISTENSIAL (∃x) - true to atleast one value; one or more element under consideration for which the predicate is true.
- This week ended with introduction to rules of inference.
  - ARGUMENT - sequence of statements that end with a conclusion. Ex. (p1 ∧ p2 ∧ p3 ... ∧ pn) → q
  - VALID - conclusion of the argument must follow from the true of the preceding statements of the argument. Ex. (p1 ∧ p2 ∧ p3 ... ∧             pn) → q is TAUTOLOGY
  - FALLACY - an invalid argument.

## Week 3:
- The week started with a review on the lessons of the first two weeks such as:
  - TRUTH TABLE
  - LOGICAL EQUIVALENCES
  - QUANTIFIERS
  - RULES OF INFERENCE
- So far, the hardest and most complexed is the rules of inference.

|         Name         |   Rule of Inference       |            Tautology           |
|:--------------------:|:-------------------------:|:------------------------------:|
|    Modus Ponens      |      p<br>p→q<br>∴q       |        (p ∧ (p → q)) → q       |
|      Modus Tollens   |    ¬q<br>p→q<br>∴ ¬p      |       (¬q ∧ (p → q)) → ¬p      |
|Hypothetical Syllogism|     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|Disjunctive Syllogism |     p∨q<br>¬p<br>∴q       |       ((p ∨ q) ∧ ¬p) → q       |
|      Addition        |         p<br>∴p ∨ q       |           p → (p ∨ q)          |
|      Simplication    |        p ∧ q<br>∴p        |           (p ∧ q) → p          |
|       Conjunction    |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|      Resolution      | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) | 

- Another lesson was taught in class, this was METHODS OF CONSTRUCTING PROOFS.
  - Direct Proof - way of showing the truth or falsehood of a conditional statement (p → q)
    - The important steps are as follows:
      - 1. Assume p (antecedent) is true.
      - 2. Prove that q (consequent) is also true through step 1.
- The definition of odd and even numbers werely clearly stated mathematically.
  - Odd number: {2k+1 | k ∈ Z}
  - Even number: {2K | k ∈ Z}
- As weeks passed by, the lectures get harder and harder that is why I need to study days before the exam.

## Week 4:
- Introduced another method of constructing proof known as CONTRAPOSITION.
- Contraposition - formed by negating both terms and reversing the direction of inference (p → q ≡ ¬q → ¬p)
  -Important Steps are as follows:
    - 1.Assume ¬q is true.
    - 2. Show that ¬p is also true from the previous assumption.
- Vacuous Proof: (¬p → (p → q)) Premise: ¬p Conclusion: p → q
  - Show that p is false, because (p → q) must be true when p is false.
- Trivial Proof: (q → (p → q))
  - Show that q is true, then it follows that (p → q) must also be true.
- Proof by Contradiction
  - Important Steps are as follows:
    - 1. Assume that the premise is not true: ¬(premise) ≡ T
    - 2. Show that the assumption will end up in a contradiction.
- Proof by Equivalence
  - Biconditional: p ↔ q, we show that p → q and q → p
  - An example was given to understand the proof, "if n is an integer, n is even iff n^2 is even."
- Rational numbers were clearly explained and defined to me by Sir Cabatuan.
- I learned more types of proofs that can make mathemical problems in life more logical.
  
## Week 5:
- I learned more about proof by Equivalences.
- I also learned that in DISMATH, substitution is not a proof. 
- Proof by Equivalence (Biconditionals)
  - This can help me understand the proof more, P ↔ Q ≡ (P → Q) ∧ (Q → P)
  - Important Steps are as follows:
    - Show P → Q is true.
    - Show Q → P is true.
- I was able to answer some exercises in class such as "If n is a positive integer, then n is odd if and only if n^2 is odd."
- I discovered that substitution can be used as a counterexample to a theorem.
- Mathematical Induction
  - My prof explained that the concept of mathematical inductions is "if it starts true and its stay true then it's always true."
  - It's like a domino or sequence of propositions (P(1), P(2), P(3), P(k), P(k+1), ...).
  - Important Steps are as Follows:
    - Basic Step: Show P(1) or P(0) is true
    - Inductive Steps:
      - Assume P(k) is true.
      - Show P(k+1) is also true.
- I learned how to solve this problem in class "P(n) = 1 + 2 + 3 + … + n = n(n+1)/2."

##Week 6
- This week was the start for the coverage of quiz 2.
- The lessons are becoming more challenging compared to the topics in quiz 1.
- **SUMMATION** - notation for sum of am, am+1, ..., an is ∑ai=m ai where i is the index of summation.
  - It is commonly reffered to as Σ “sigma”
- **RECURSIVE/INDUCTIVE DEFINITION**
  - 1. Basis step: specify the value at zero
  - 2. Recursive step: Find a rule for finding its value at an integer number from the values at smaller integers.
  - example: f(0) = 3, f(n+1) = 2f(n) + 3
- **RECURSIVE ALGORITHM** - solves a problem by reducing it to an instance with smaller input
- **PROGRAM CORRECTNES** - to ensure that a program gives the correct output
  - **PROGRAM VERIFICATION** - A program is said to be correct if it produces the correct output for every possible input.
    - 1. Show that the correct answer is obtained if the program terminates.(Partial correctness)
    - 2. Show that the program always terminates
  - **PARTIAL CORRECTNESS**
    - initial assertioN (p)- gives the properties that the input values must have.
    - final assertion (q) - gives the properties that the output of the program should have, if the program did what was intended.
- **HOARE TRIPLE** p{S}q
  - S is said to be partially correct with respect to the initial assertion p and the final assertion q if whenever p is true for the input values of S and S terminates, then q is true for the output values of S

- **RULES OF INFERENCE**
 - *COMPOSITION RULE* </br>
  p{S1}q </br>
  q{S2}r </br>
  ______________ </br>
   ∴ p{S1;S2)r <br>
  - *CONDITIONAL STATEMENTS* </br>
  (p ∧ _condition_) {S} q </br>
  (p ∧ _¬condition_) → q </br>
  ________________________________________</br>
    ∴ p {**if** _condition_ **then** _S_} q
  - *IF-ELSE STATEMENT* </br>
  (p ∧ _condition_) {S<sub>1</sub>} q </br>
  (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
  _____________________________________ </br>
    ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q

- **POWER SERIES**
  - ∑∞n = 0 anxn ;  where a0, a1, a2, ... is a given sequence of constants, and x is a real variable.
  - Examples:   1 + r + r2 + r3 + ... = 1/(1-r)


##Week 7
- Project 0.0:
  - It was the very first project for DISMATH.
  - I was introduced to a new sofware called "MIT App Inventor."
  - submitted on March 2, 2016
 
- **SET THEORY**
  - A set is an unordered collection of distinct objects, which may be anything (including other sets).
    - {f, a, e, n, i, c, l}
  - Empty Set { } = ∅ means no elements
    - {∅} is not an empty set
  - Set Builder Notation {x | some property that x satisfies}
  - Membership
    - 1 ∈ {1, 2, 3, 4}

- **SET IDENTITIES TABLE**

|  **LAW**  |  **IDENTITY**  |
| :------: | :-----------------------------: |
|  Identity Laws  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  Domination Laws  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  Idempotent Laws  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  Complementation Law  |  (A¯)‾ ≡ A  |
|  Commutative Laws  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
|  Associative Laws  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  Distributive Laws  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  De Morgan's Laws  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  Absorption Laws  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  Complement Laws  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

- SUBSETS ⊆
  - A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T
  - Example:  ℕ ⊆ ℤ (every natural number is an integer)
- POWER SET P(S) = {T|T ⊆ S} - A set of all subsets.
- CARDINALITY |S| - The number of element it contains
    - Infinite Cardinalities - alaph-null (0,1,2,3,...)
<br></br>
- **FUNCTIONS**
  - Let A and B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.
  -  Functions are also called MAPPINGS or TRANSFORMATIONS.
    - f: A to B </br>
       A: domain </br>
       B: co-domain
    - Range - actually occuring values
    - IMAGE
      - If _f(a) = b_, _b- is the image of _A_.
      - The range of _f_ is the set of all images of elements of _a_.

- **TYPES OF FUNCTIONS**
    - One - to - one Function (Injection)
      - functions that never assign the same value to two different domain elements.
    - Onto Function (Surjective)
      - functions have equal range & co-domain.
    - One - to - one Correspondence (Bijection)
     - function is both one - to - one and onto.

## Week 8:
- **ALGORITHMS** - A finite set of precise instructions for performing a computation or for solving a problem.
    - *Properties of Algorithms*
      - INPUT - has input values from a specified set 
      - OUTPUT - solution to the problem 
      - DEFINITENESS - defined precisely 
      - CORRECTNESS - produce the correct output values 
      - FINITENESS - produce the desired output 
      - EFFECTIVENESS - perform exactly and in a finite amount of time 
      - GENERALITY - applicable for all problems of the desired form
- **PSEUDOCODE**
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - Preconditions - describe valid input
    - Postconditions - conditions that the output should satisfy
- Algorithm example: Finding the Maximum {5,4,1,8,3}
  - Input: ({a1, a2, a3,..,an} ∈ , Z)
  - Output: largest 8
  - Pseudocode

    > max = a1; </br>
    > for i: 2 to n { </br>
    >   if(max < ai) </br>
    >       max = ai} </br>

## Week 9:

- Discussed the types of algorithm procedures that we can use when writing a pseudocode

- **SEARCHING ALGORITHMS** - Problem of locating an algorithm in an ordered list
    - *Linear Search* -  finding a particular value in a list that checks each element in sequence until the desired element is found
      - input: x
      - ouput: location, i; loc = i if found, loc = -1 if not found
      
      > i=0 </br>
      > while(i < n and x!=a1) </br>
      >   i=i+1 </br>
      > if i < n then loc = i </br>
      > else loc = -1 </br>

    - *Binary Search* - comparing the middle values of a list then repeated until the desired output is found.
    
              Require: {a1, a2, ..., ai, ..., an} ≠ ∈ Z, where a1 < a2 < ... < an; x ∈ Z
              Ensure: result = k, where (ak = x) and k ∈ {1, ..., n} if the element is found; otherwise k = -1
                i ← -1
                j ← n
                while i < j do
                  mid ← ⌊(i + j)/2⌋
                  if x > amid then
                    i ← mid +1
                  else
                    j ← mid
                  end if
                end while
                if x == ai then
                  result ← i
                else
                  result ← -1
                end if

- **SORTING ALGORITHMS** - Problem of assorting elements into increasing order
    - *Bubble Sort* - compares the first two elements then interchanging them if they are in the incorrect order.
    
      Require: {a1, a2, ..., ai, ..., an} ∈ R; n ≥ 2
              Ensure: {a1, a2, ..., an} where a1 < a2 < ... < an
                for i = 1 to n-1 do
                  for j = 1 to n-i do
                    if aj > aj+1 then
                      temp ← aj+1
                      aj+1 ← aj
                      aj ← temp
                    end if
                  end for
                end for

    - *Insertion Sort* - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.
    
    Require: {a1, a2, ..., ai, ..., an} ∈ R; n ≥ 2
              Ensure: {a1, a2, ..., an} where a1 < a2 < ... < an
                for j = 2 to n do
                  i ← 1
                  while aj > ai do
                    i ← i + 1
                  end while
                  temp ← aj
                  for k = 0 to j-i-1 do
                    aj-k = aj-k-1
                  end for
                  ai = temp
                end for

- **GREEDY ALGORITHMS** - Algorithms that make what seems to be the "best" choice at each step. Selects the best choice at each step, instead of considering all sequences of steps that may lead to optimal solution
  - *Greedy Change* -Making algorithm
  
     Require: {c1, c2, ..., ci, ..., cn} ∈ Coin Domination
                      where c1 > c2 > ... > cn; x - amount of money in cents
              Ensure: result[n] = minimum number of coins per domination
                for i = 1 to n do
                  resulti ← 0
                  while x ≥ ci do
                    x ← x - ci
                    resulti  ← resulti + 1
                  end while
                end for

- Also started on the *Growth of Functions* often described using Big-O Notation

## Week 10:
- **Big-O Notation**
    - Let f and g be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants C and k such that:
        |f(x)| ≤ C|g(x)| 
    whenever x > k.
    - Example: f(x)=x^2 + 2x + 1; O(x^2); k=1, C=4

- **Big-Omega and Big-Theta Notation**
    - Big-O Notation does not provide a lowerbound for the size of f(x). 
        - Big-Omega (Big-Ω) - lower bound
        - Big-Theta (Big-Θ) - both upper and lower bound

- **Algorithm Time Complexity** - can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
- **Division and Modulo Operator**
  - let a be an integer and d positive integer. Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r
  - Q = a div d
  - r = a mod d

## Week 12
- This is the coverage for quiz 3.
- I need to study well to get a high grade.
- **GRAPH THEORY**
- Graphs are discrete structures consisting of vertices and edges that connect these vertices.
- A graph G = (V,E) consists of V, a nonempty set of _vertices (or nodes)_ and E, a set of edges. Each edge has either one or two vertices associated with it, called its _endpoints_. An edge is said to _connect_ its endpoints.
- Isolated is a vertex with 0 degree
- Pendant is a vertex with 1 degree

- Hand shaking theorem: 2e = ∑deg(v)

- Path - sequence of edges travelling from vertex to vertex along the edges
- Euler Circuit - passess through every edge and goes back to starting point
  - A graph with all vertices/nodes having even degrees.
- Euler Path - simple path containing every edge of the graph
  - A graph with exactly two vertices/nodes having odd degrees.
- Hamilton Path - passes through every vertex.
  - Does not need to pass through all the edges.
  - Does not have a formula.
  - It is harder than Euler's path.
- Hamilton Circuit - passes through every vertex then goes back to the starting point
  - Does not need to pass through all the edges.
- **Matrices of Graphs** 
  - Adjacency of Matrices 
    - Matric between two vertices.
    - 1 for adjacent; 0 for non-adjacent
  - Incidence of Matrices - Matric between vertices and edges
- Isomorphism of Graphs
  - same connection, equal nodes and vertices 

- **PLANAR GRAPH**
- no edges cross in a graph
- Euler's Formula: r = e - v + 2
  - r - regions
  - e - edges
  - v - vertices
- Euler's Characteristic: ℵ = r - |e| + |v| = 2

- **HOMEOMORPHIC GRAPHS**
- can be obtained from the same graph by a sequence of elementary subdivisions
- Elementary Subdivision - everything is planar graph
- Kuratowski's Theorem - nonplanar if and only if it contains a subgraph homeophobic to K3,3 and K5
