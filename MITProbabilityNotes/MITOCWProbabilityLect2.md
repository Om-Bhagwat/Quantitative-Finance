## Summary
The lecture is mainly about conditional Probability and the derivation of Bayes's Rule using the conditional probability. 

### <ins>  Conditional Probability </ins>
Conditional Probability means the probability of event B occuring after the event A has already happened. and is denoted by ->

P(B|A) 
which also equal ,
P(B|A) = P(A intersection B)/P(A)

Now this conditonal probability also applies to axioms, for example

we know that if A intersection B = empty
then P(A union B) = P(A) + P(B)
now if we want to shift the equation on if C has already happend then the above equation changes to ->
P(A union B | C) = P(A|C) + P(B|C)

### <ins> Multiplication </ins>
P(A intersection B intersection C) = P(A) * P(B|A) * P(C | A intersection B)

Proof ->

P(A intersection  B intersection C) = P((A intersection B) intersection C)
                                    = P(A intersection B) * P(C|A intersection B)
                                    = P(A) * P(B|A) * P(C|A intersection B)

### <ins> Total Probability Theoram </ins>

Assume P(A1) + P(A2) + P(A3) = 1, and B intersection A1 union A2 union A3 is not empty.

Then,
P(B) = P(A1) * P(B|A1) + P(A2) * P(B|A2) + P(A3) * P(B|A3) //These are basically weighted avgs.

### <ins> Bayes's Rule </ins>

Assume we know P(B|Ai) for each i,
and we wish to infer/revise this to P(Ai|B)

then,
P(Ai|B) = P(Ai intersection B)/P(B) = P(Ai) * P(B|Ai) / P(B)
                                    = P(Ai) * P(B|Ai) / Summation(j=1 to j=j)[P(Aj) * P(B|Aj)

This is basically called Cause-Effect Model
where if we know that A -> B and it's prob = P(B|A)

and we want to infer from B that is P(A|B).

