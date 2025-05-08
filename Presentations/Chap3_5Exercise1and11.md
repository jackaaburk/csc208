# Chapter 3.5 Exercise 1 and Additional Exercise 2 (11) Solution

## Exercise 1

> A multiset is a collection of objects, just like a set, but can contain an object more than once (the order of the elements still doesn’t matter). For example, $ \{1, 1, 2, 5, 5, 7\} $ is a multiset of size 6.

---

### (a) How many *sets* of size 5 can be made using the 10 numeric digits 0 through 9?

Since sets do **not** allow duplicates and order doesn't matter, we use the combination formula:

$ \binom{10}{5} = \frac{10!}{5!(10 - 5)!} = \boxed{252} $

---

### (b) How many *multisets* of size 5 can be made using the 10 numeric digits 0 through 9?

Multisets allow repeated elements, and order still doesn't matter. This is a combination **with** repetition:

$ \binom{10 + 5 - 1}{5} = \binom{14}{5} = \boxed{2002} $



## Additional Exercise 2

### 2. Solve the three counting problems below. Then say why it makes sense that they all have the same answer. That is, say how you can interpret them as each other.

#### (a) How many ways are there to distribute 8 cookies to 3 kids?

> This is a stars and bars problem.

- You can think of this like $x + y + z = 8$ (where $x, y, z$ are all greater than $0$). Each kid represents their own variable.

- Using the stars and bars formula, it will be:

$\binom{n + r - 1}{r - 1}$

Which plugs into:

$\binom{10}{2}$

Which equals $45$.

#### (b) How many solutions in non-negative integers are there to $x + y + z = 8$

- We just answered this question in (a). Since each kid represents a variable, and the 8 cookies can be divided in any way as long as each kid gets a cookie amount greater than or equal to 0, it can be represented as $x + y + z = 8$. 

- Thus, our answer is 45.

#### (c) How many different packs of 8 crayons can you make using crayons that come in red, blue, and yellow?

Let:

r = no. red crayons
b = no. blue crayons
y = no. yellow crayons

- Let's represent this like the cookie problem.

- Let's say that in this case, each cookie is a possible slot allocated to a crayon of a particular color.

- Let's say that each color of crayon has a respective kid from the cookie problem.

- Since there are 8 slots, and 3 possible crayons that these slots can be divided into randomly, the problem is the exact same as (a), with it being representable as $x + y + z = 8$.

Thus, the answer is 45.

> Since each of these questions are the division of 8 into the sum of three variables, they all have the same answer.