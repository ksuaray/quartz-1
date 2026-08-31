---
id: PROP-IN-EX
type: property
topic: prcce
status: canonical
---
Suppose $A,B\subset\Omega$ be [[Definition - Event|events]]. Then we can show that the [[Definition - Probability|probability]] of the union and intersection can be written as
$$P(A\cup B)=P(A)+P(B)-P(A\ B)$$ More generally,
 We can extend the inclusion-exclusion principle beyond two events to some set of $n$ events: $\{A_1, A_2, \ldots, A_n\}$. It becomes more complex because we need to account for the intersection of $r$ subsets of events:

> [!theorem] General Addition Rule
>
> $$
> P\left(\bigcup_{i=1}^{n} A_i\right)
> =
> \sum_{i=1}^{n} P(A_i)
> -
> \sum_{i_1 < i_2} P(A_{i_1}\cap A_{i_2})
> + \cdots
> $$
>
> $$
> \qquad
> +(-1)^{r+1}
> \sum_{i_1<i_2<\cdots<i_r}
> P(A_{i_1}\cap A_{i_2}\cap\cdots\cap A_{i_r})
> + \cdots
> $$
>
> $$
> \qquad
> +(-1)^{n+1}P(A_1\cap A_2\cap\cdots\cap A_n)
> $$
>
> **Note:** If the set of events $\{A_1, A_2, \ldots, A_n\}$ are **disjoint**, then
>
> $$
> P\left(\bigcup_{i=1}^{n} A_i\right)
> =
> \sum_{i=1}^{n} P(A_i).
> $$

## Related Knowledge
[[Definition - Probability]]
[[Set Algebra]]