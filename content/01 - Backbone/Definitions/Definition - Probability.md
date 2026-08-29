```
---
id: DEF-PROBABILITY
type: definition
topic1: probsets
topic2: prcce
status: canonical
---
```

# Probability
## Definition 

In a random experiment with sample space $\Omega$, a **probability function** $P$ is a function on $\Omega$ that assigns to each element $\omega$ in the [[Definition - Sample Space|sample space]] a numerical value that measures the *chance* that event $\omega$ will occur. This is denoted as $P(\omega)$. A probability function has the following properties:
1.  $P(\omega) \ge 0$ for all $\omega \in \Omega$.
2.  $\sum_{\omega \in \Omega} P(\omega) = 1$ 
3. For all events $A \subseteq \Omega$, $P(A) = \sum_{\omega \in A} P(\omega)$

## Interpretation 
A number between 0 and 1 assigned to an [[Definition - Event|event]] that provides a precise measure of the chance that the event will occur.
## Related Knowledge

**Relative Frequency Formulation** - Consider the [[Definition - Sample Space|sample space]] of a random experiment that consists of **equally likely** elements. The probability of some event $A \subseteq \Omega$ is the relative frequency of event $A$ in $\Omega$:
$$
P(A)=\frac{n(A)}{n(\Omega)}
$$
where $n(\cdot)$ denotes the number of elements in $(\cdot)$.

This probability definition holds true **only if** each element in $\Omega$ is **equally likely**.

[[Definition - Set]] 
[[Definition - Random Experiment|Random  Experiment]] 
