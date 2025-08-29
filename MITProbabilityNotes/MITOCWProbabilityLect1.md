# Summary
Lecture mainly covers Subtle differences between Discrete and Continous means of probability by the understanding of the smaple space, why & how is it used while assinging the probability to the outcomes later events. Also illustrates different axioms which are very important to understand and solve the problems.

### <ins>Sample Space</ins> -> List of all possibilities, (Flipping a single coin -> {H, T})

### <ins>Mutually Exclusive Sets</ins> -> Ones that don't interect, S1 = {Set of even Number} S2 = {Set of odd numbers}

### <ins>Collectively Exhaustive</ins> -> At a time only one event/outcome could happen, example if i flip a single coin I can only get a Heads/Tails at one time. 

The above examples are mostly for the discrete set of exmaples, for the continous Model the sample space is infinite.
Consider the example of your book on the table, the points it touches the surface?

### <ins>Assingning Probabilites </ins>

Event -> Asign prob to subsets instead of the entire outcome.

0 <= prob(event/outcome) < =1 (Because of normalization)

### <ins> Axioms </ins>
Set of ground rules.
1) Nonnegativity P(sample space) >= 0
2) Normalization as I showed above.
3) Additive
What is means if basically of you have a disjoints sets, then
P(A union B) = P(A) + P(B) // as P(A intersection B) = 0.

Proof of nomalization as to why the prob will always be less then equal to 1.
1 = P(sample space) = P(A union A^c)
                   1 = P(A) + P(A^c)
                   P(A) = 1 - P(A^c)

P({s1, s2, s3 ...sk}) = P(s1) + P(s2) .. + P(sk) //assumming set's are disjoint.

Union of 3 sets follow the same principe as above given they are disjoint

### <ins>Discrete Uniform Law</ins>
Let all outcomes be equally likely.
P(A) = no. of elements in A/Total no of sample points // becomes counting.

### <ins>Continous Uniform Law </ins>
Probability  = Area.

### <ins> Countable Additivity Axiom </ins>
P(A1 union A2 union A3 ...) = P(A1) + P(A2) ....
