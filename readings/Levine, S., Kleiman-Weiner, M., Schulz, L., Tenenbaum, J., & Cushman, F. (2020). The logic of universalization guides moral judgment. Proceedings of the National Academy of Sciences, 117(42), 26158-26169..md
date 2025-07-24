---
aliases:
  - Levine et al 2020
  - universalization
  - Levine PNAS
---
https://www.pnas.org/doi/pdf/10.1073/pnas.2014505117
# Summary
- universalization - "what if everyone felt free to do that"
- shows up in threshold problems (tragedy of the commons)
- an action is bad if # interested parties > harm threshold
# Theory
- universalization - asking what would happen if everyone did that
	- combines aspects of a lot of different theoretical frameworks
- threshold problems - it's ok if a few people do it, but if everyone does, everyone suffers
	- harm threshold - threshold for "too many people"
	- unique utility function (up then down, not monotonic)
- hypothesis - action is bad if # interested parties > harm threshold
- model with a softmax function $$p_{univ}(\text{acceptable})=\frac{1}{1+e^{\tau(U(0)-U(n_i))+\beta}}$$
	- $\tau$ - temperature = "strength of the effect of utility maximization on moral judgment"
	- $\beta$ - bias = "whether people err on the side of acceptability or unacceptability judgments when the relevant utilities are approximately equal"
- alternative theories
	- outcome based - current vs current + me
	- pessimistic - everyone vs everyone + me
	- norm-based - it's wrong if there's a social norm around it
# Experiments
### 1. explicit use of universalization
- situations with 4 different types of wrong
	- harm
	- fairness - not sharing resources
	- utility maximization - helping a few instead of helping many (?)
	- threshold problem
- explanations derived from the 4 categories
- for threshold problems, people preferred universalization as a reason
### 2. ruling out alternative theories
- outcome-based and pessimistic
	- nobody wants to use vs everyone wants to but chose not to
	- actual situation is nobody is going to use either way
- norm-based
	- nobody wants to use
	- harm threshold exists vs doesn't exist
	- norm-based doesn't see these two situations differently, but universalization does
### 3. people care about everyone's utilities, not just personal
- new situation where self always benefits, but everyone else suffers if all do it
	- only care about self utility -> it's fine
	- care about everyone's utility -> it's bad 
### 4. quantitative modeling
- collected more datapoints with different $n_i$ and more nuanced harm thresholds
- linear mixed effects model - universalization > norms explanation
- 55% participants followed rule of 'always morally acceptable'
	- only 27% varied with $n_i$ (indicating they used universalization)
- explicitly measure people's utility functions for the situation
	- fit better than idealized utility function
### 5. children replicate effect
- communal rock path vs personal rock collection, with high and low interest
- 4-11 yo
- 79.4% had same answer for high and low interest, 14.4% had expected switch
	- within-participant analysis fails bc not a lot of kids switched answers
- between-participants - significant difference between high and low interest conditions
	- no significant age effects
# Questions
- only surveyed at boundaries of harm threshold - what if you measured in the middle?