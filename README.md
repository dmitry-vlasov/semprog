# semprog
Semantic programming framework.

Used to formalize and glue together semantics of different kinds.

Currently following semantics are implemented:
  - standard boolean operations (/\, \/, ->, <->, !, T, F),
  - restricted quantifiers (E, A),
  - equality (=, !=),
  - arithmetics (+,-,*,/)
  - integer constants,
  - arrays: (concat, tail, add, const arrays: [a1, a2], enum from to: [x ... y])
 
Implemented but not tested yet:
  - if-then-else operator,
  - lambda operator,
  - recursion operator
