# Chapter 3.4 Exercise 1 Solution

> A pizza parlor offers 8 toppings.

> a. How many 4-topping pizzas could they put on their menu? Assume double toppings are not allowed.

> b. How many total pizzas are possible, with between zero and 8 toppings (but not double toppings) allowed?

> c. The pizza parlor will list the 8 toppings in two equal-sized columns on their menu. How many ways can they arrange the toppings in the left column?

## a. To solve a., all we need to do is set up a combination formula to count the possible sets, since combinations are the same as a set of x choose y (This is only possible in this case due to no double toppings being allowed).

- We are selecting 4 toppings from a set of 8, so the equation will be $\frac{8!}{(8-4)!4!}$, which equals 70.

- Therefore, our answer is 70 possible pizzas with 4 toppings.

## b. In this question we are counting every possible pizza from 0 to 8 toppings. This can be treated like a bit string of eight bits, with each bit position serving as a possible topping. 

- All we need to do from here is count all possible numbers made with an 8 bit integer, which is $2^8$ or $256$.

- Therefore, our answer is 256 possible pizzas from 0 to 8 toppings.

## c. The pizza parlor will list the 8 toppings in two equal-sized columns on their menu. How many ways can they arrange the toppings in the left column?

- For c., we could use the entire permutation principle, but it's unnecessary. Since the quotient principle states $\begin{equation*}
P(n,k) = \binom{n}{k} \cdot k! \end{equation*}$, we can just multiply our answer from the a. by $k!$ (which is 4!). This will give us 1680, which is the answer.