# Chapter 4.1 Additional Exercise 8 and Additional Exercise 10 Solution

## Exercise 8

**Given:**  
$a_n$  = $2a_{n-1} - a_{n-2}, \quad \text{with } a_1 = 1 \text{ and } a_2 = 2$

**Step 1: Characteristic Equation**  

Assume a solution of the form  
$a_n = r^n$.  
Then:  
$r^n = 2r^{n-1} - r^{n-2}$  
$\Rightarrow \frac{r^n}{r^{n-2}} = \frac{2r^{n-1}}{r^{n-2}} - \frac{r^{n-2}}{r^{n-2}}$  
$\Rightarrow r^2 = 2r - 1$  
$\Rightarrow r^2 - 2r + 1 = 0$  
$\Rightarrow (r - 1)^2 = 0$  

So, we have a repeated root  
$r = 1$.

**Step 2: General Solution**  

Since the root is repeated, the general solution is:  
$a_n = (A + Bn) \cdot 1^n = A + Bn$.

**Step 3: Use Initial Conditions**  

$\begin{cases} a_1 = A + B \cdot 1 = 1 \\ a_2 = A + B \cdot 2 = 2 \end{cases} \Rightarrow \begin{cases} A + B = 1 \\ A + 2B = 2 \end{cases}$  

Subtracting the first equation from the second:  
$(A + 2B) - (A + B) = 2 - 1$  
$\Rightarrow B = 1$  
$\Rightarrow A = 0$  

**Final Answer:**  
$\boxed{a_n = n}$


## Exercise 10

### Use summation ($\sum$) or product ($\prod$) notation to rewrite the following.

(a) $2 + 4 + 6 + 8 + \cdots + 2n$.

> - This is just a summation formula (since you are adding values) that increases by a ratio of 2 each value.

$\sum_{k=1}^{n} 2k$

(b) $1 + 5 + 9 + 13 + \cdots + 425\text{.}$

> - This is also a summation formula that increases by 4 for each value, meaning the ratio will be 4.

> - However, it ends at 425, meaning we must find the number of terms in the sequence.

- Since a general term of this sequence would be $4k-3$, we set that equal to 425.

- $4k-3 = 425$ can be simplified into $k = 107$

Thus, the answer to (b) is $\sum_{k=1}^{107} (4k - 3)$.

(c) $1$ $+$ $\frac{1}{2}$ $+$ $\frac{1}{3}$ $+$ $\frac{1}{4}$ $+$ $\cdots$ $+$ $\frac{1}{50}\text{.}$

> - This is a summation of a harmonic series.

> - Here, we could do the same thing we did in (b) to find the number of terms.

> - However, since each term's denominator is equal to k, we know that the number of terms is $50$.

Thus, the answer to (c) is $\sum_{k=1}^{50}$ $\frac{1}{k}$.

(d) $2$ $\cdot$ $4$ $\cdot$ $6$ $\cdot$ $\cdots$ $\cdot$ $2n\text{.}$

> - Since we are multiplying each term, this is a product of numbers.

> - Since each term increases by a ratio of 2, our general term will be 2k.

> - Additionally, the last term is 2n, meaning the number of terms is infinite.

Thus, the answer for (d) is $\prod_{k=1}^{n}$ $2k$ 

(e) $(\frac{1}{2})$ $(\frac{2}{3})$ $(\frac{3}{4})$ $\cdots$ $(\frac{100}{101})$ $\text{.}$

> - In this multiplicative sequence, both the numerator and denominator increase by 1 at a time, the denominator just has a head start by one.

> - Additionally, we know our last term will be 100, since the last numerator is 100 and our starting term's numerator is 1.

Thus, with this information, we can conclude that the answer to (e) is $\prod_{k=1}^{100}$ $\frac{k}{k+1}$.
