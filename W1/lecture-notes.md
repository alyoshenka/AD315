# Week 1

Contact via Slack

Can take quizzes/etc early, just give as much heads-up as possible

## What is Discrete Mathematics?

!= continuous (calculus)

integers/graphs/boolean logic

"Things with 'hard edges'"

## Sets and Functions

### Sets
- set: a collection of *distinct* items
- item = element (can be anything, even other sets!)
- order doesn't matter

### Important Sets
- N: natural numbers -> 1, 2, 3... (sometimes 0)
- Z: integers -> ...-2, -1, 0, 0, 2...
- Q: rational numbers -> 1/2, 3/7, 1/100, etc
- R: real numbers -> π, e, √2
- ∅ or {}: empty set

### Subsets
- Set A is a **subset** of set B if all elements of A are also in B
- ∅ is a subset of ALL sets
- All sets are a subset of itself
- Notation: ⊆ symbol
  - A ⊆ B - Set A is a subset of set B
  - Z ⊆ R - Integers are a subset of the Real Numbers
- A ⊂ B - Set A is a proper subset of B
  - Set A is a *Proper Subset* of B if A ⊆ B, but A != B.

**Z ∉ R**: R only contains numbers, not sets of numbers (Z is a set of numbers)

**5 ⊄ R**: 5 is not a set

### Set Enumeration Notation
use `{ }`

*Notation matters!*

### Algebra of Sets

*The result is another set*

- The *Union* of two sets is a set containing all elements that belong to either set.
  - A ∪ B
- The *Intersection* of two sets is a set containing all elements that belong to both sets.
  - A ∩ B
- The *Difference* of two sets is everything that is in one set but NOT in a second.
  - B – A or B ∖ A
- The *Complement* of a set is the set of everything that is NOT in a given set.
  - A'
- *Universal Set* U is the set of all relevant elements.
  - A' = U - A
- The *Power Set* of S is defined as the set of all sets that are subsets of S
  - S = {A, B}  P(S) = {∅, {A}, {B}, {A,B}}
  - 1 ∉ P(S); {1} ∈ P(S)

cardinality: number of elements*

W = {a, b, c}  |W| = 3

*What is the cardinality of Z, the set of all integers?!? What about Q or R?

### Power Sets
Sets can contain other sets!

If |S| = n, then |P(S)| = 2^n

### Functions
function: mapping from a set of inputs to a set of outputs

domain: set of all elements that can by used as inputs to the function

range: set of all elements the function can map to

#### Examples
- isEven 
  - domain: integers
  - range: { true, false }
- word length
  - domain: strings
  - range: integers
- power set
  - domain: sets
  - range: sets of sets
- isDog
  - domain: bitmap images
  - range: { true, false }

natural domain: 'whatever makes sense'

#### Bijections
- A Reversible 1:1 function between
sets is called a *Bijection*.
  - All elements in one set must map to a unique element in the other.
  - No elements can be left unpaired.
- Reversible!
- If a Bijection between sets A and B exist, then |A| = |B|; If |A| = |B|, then a Bijection between sets A and B exists!
- "Everyone gets a buddy!"

#### Other Types of Functions
- Injective Function: Each element maps to a unique result.
- Surjective Function: Every element in the range can be hit.
- Bijective Function: Function that is BOTH injective and surjective.

## Python
`set()` = hash set