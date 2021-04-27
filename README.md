# semprog
Semantic programming framework.

Used to formalize and glue together semantics of different kinds.

Currently following semantics are implemented:
  - standard boolean operations (/\\, \\/, ->, <->, !, T, F),
  - restricted quantifiers (E, A),
  - equality (=, !=),
  - arithmetics (+,-,*,/)
  - integer constants,
  - arrays: (concat, tail, add, const arrays: [a1, a2], enum from to: [x ... y])
  - if-then-else operator,
  - lambda operator,
  - recursion operator

## Installation
Just add semprog/bin directory to the system PATH

## Building
To build semprog you need to insall flow9 compiler [flowc]{https://github.com/area9innovation/flow9}
Run `flowc1 jar=1 semprog.flow` in src directory to compile the sources and generate a new `semprog.jar`
