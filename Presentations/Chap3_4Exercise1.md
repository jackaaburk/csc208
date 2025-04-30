# Chapter 3.4 Exercise 1 and 10 Solution

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

# Exercise 10

$\text{a. How many functions } f : A \to B \text{ are there?}

A \text{ function from } A \text{ to } B \text{ assigns an element in } B \text{ to each element in } A. 
\text{ For each of the 14 elements in } A, \text{ there are 21 possible choices in } B. 
\text{ Thus, the total number of functions is:}

\[
\text{Number of functions} = 21^{14}
\]

\text{b. How many functions } f : A \to B \text{ are injective?}

\text{For an injective function, each element of } A \text{ must map to a unique element in } B. 
\text{ In other words, no two elements in } A \text{ can map to the same element in } B. 

\text{To form an injective function, we need to assign a distinct element of } B \text{ to each element of } A. 
\text{ This is like choosing a 1-to-1 correspondence between the elements of } A \text{ and a subset of } B.

\text{First, we select 14 elements from } B. \text{ The number of ways to do this is given by:}

\[
\binom{21}{14}
\]

\text{After choosing the 14 elements, we can assign these 14 elements to the 14 elements of } A 
\text{ in any permutation. The number of ways to do this is } 14!.

\text{Thus, the total number of injective functions is:}

\[
\text{Number of injective functions} = \binom{21}{14} \times 14!
\]$