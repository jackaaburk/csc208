# Chapter 3.5 Exercise 1 and Additional Exercise 2 (11) Solution

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