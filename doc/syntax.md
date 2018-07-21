#  syntax

##  Parameter symbols

1. [a-z][a-zA-Z0-9_]   constants
2. [A-Z_][a-zA-Z0-9_]   variables

##  Terms

1.  All parameter symbols are terms

2.  If t0, .... tn are terms, then
    so is t0(t1,....t2)

3.  If f, t0, ...tn are terms, then
    <t0,...tn> fn is also a term

4.  If f, t0, ...tn are terms, then
    [t0,...tn] fn is also a term

5.  If t0,.....tn are terms, then
    t0 :- t1,.....,tn.
    is a rule.
