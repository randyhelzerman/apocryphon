#  syntax

##  Parameter symbols

1. [a-z][a-zA-Z0-9_]   constants
2. [A-Z_][a-zA-Z0-9_]   variables

##  Terms

1.  All parameter symbols are terms

2.  If t0, .... tn are terms, then
    so is t0(t1,....t2)

3.  If f, t0, ...tn are terms, then
    <t0,...tn> f is also a term

4.  If f, t0, ...tn are terms, then
    [t0,...tn] f is also a term


5.  If X is a variable, and t is a term, then
    X^t is also a term

6.  If t1 and t2 are terms, then
    t1@t2 is also a term.


## Rules

1.  If t0,.....tn are terms, then
    t0 :- t1,.....,tn.
    is a rule.



X^f(X)@a =>  f(a)