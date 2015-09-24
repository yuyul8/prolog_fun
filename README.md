# An Exploration of Prolog

The purpose of this project was to venture into logic-based programming and use a constraint-based language rather than the usual procedural ones.
Because Prolog is logic-based rather than object-oriented or functional, it was necessary to see not only how to use it, but also to compare the characteristics of the language against others like Java, ML, or Racket, since these have different characteristics in terms of functional vs. OOP or dynamic vs. static.

To practice using Prolog, we built a small program that have declarative constraints in order to solve a problem of assigning dorm housing to students. Given constraints like roommate preferences and prioritizing upperclassmen, the program was able to find answers that assigned each student to a dorm and fulfilled the constraints given.

To think about Prolog in a more theoretical way, we wrote a paper discussing the structure, syntax, and semantics of Prologue, including discussion about querying and backtracing, features unique to Prolog, as well as general concepts like lists and recursion. 

-----
The program is a .pr file, which can be run on the command line after installing SWI-Prolog.
First, the file can be loaded using "swipl -s <filename>.pr".
After loading, the file needs to be consulted: "consult(filename)."
Now, queries can be made against the statements and rules specified in the file. 
