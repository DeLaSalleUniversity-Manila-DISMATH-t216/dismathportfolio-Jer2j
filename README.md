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

|         Name         |   Rule of Inference  |            Tautology           |
|:--------------------:|:--------------------:|:------------------------------:|
|    Modus Ponens      |      p, p→q ∴q       |        (p ∧ (p → q)) → q       |
|      Modus Tollens   |     ¬q, p→q ∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
|Hypothetical Syllogism|     p→q, q→r ∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|Disjunctive Syllogism |      p∨q, ¬p ∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|      Addition        |       p ∴p ∨ q       |           p → (p ∨ q)          |
|      Simplication    |       p ∧ q ∴p       |           (p ∧ q) → p          |
|       Conjunction    |      p, q ∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|      Resolution      | p ∨ q, ¬p ∨ r ∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) | 

- Another lesson was taught in class, this was METHODS OF CONSTRUCTING PROOFS.
  - Direct Proof - way of showing the truth or falsehood of a conditional statement (p → q)
    - The important steps are as follows:
      - 1. Assume p (antecedent) is true.
      - 2. Prove that q (consequent) is also true through step 1.
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
