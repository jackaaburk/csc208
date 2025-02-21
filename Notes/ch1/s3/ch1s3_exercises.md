# Addition Exercises Chapter 1 Section 3

## Reading Questions

1. To check whether two statements are logically equivalent, you can use a truth table. Explain what you would look for in the truth table to conclude that the two statements are logically equivalent. What would tell you they are not logically equivalent?

> To determine if two logic statements are logically equivalent, you need to compare their truth values for all possible truth assignments of their variables, if they were all equal, then the overall logic statements are also equal. Otherwise, they are not logically equivalent.

2. To check whether a deduction rule is valid, you can use a truth table. Explain what you would look for in the completed truth table to say that the deduction rule is valid, and what would tell you the deduction rule is not valid.

> To determine if a deduction rule is valid, you need to find the rows where all the premises are true. In these rows, if the conclusion is also true, then the deduction rule is true.

## Practice Problems

![1and2](./ch1s3images/1and2.png)

![3and4](./ch1s3images/3and4.png)

![5and6](./ch1s3images/5and6.png)

![7and8](./ch1s3images/7and8.png)

![9](./ch1s3images/9.png)

## Additional Exercises

1. No, both trolls cannot be knights, make a truth table with the propositions "The trolls are cousins", "troll 1 is a knight", and "troll 2 is a knight". Then, use the troll's statements to make premises and see if both trolls could be knights.

2. 

| $P$ | $Q$ | $R$ | ($Q \lor P$) $\rightarrow R$ | $R \land $ ($P \rightarrow Q$) | $\neg Q \land$ ($P \leftrightarrow R$) |
|---|---|---|------------------------|------------------------|------------------------|
| 0 | 0 | 0 | 1                      | 0                      | 1                      |
| 0 | 0 | 1 | 1                      | 1                      | 1                      |
| 0 | 1 | 0 | 0                      | 0                      | 0                      |
| 0 | 1 | 1 | 1                      | 1                      | 0                      |
| 1 | 0 | 0 | 0                      | 0                      | 0                      |
| 1 | 0 | 1 | 1                      | 1                      | 1                      |
| 1 | 1 | 0 | 0                      | 0                      | 0                      |
| 1 | 1 | 1 | 1                      | 1                      | 0                      |

> Pat is a knave, Quinn is a knave, and Ryan is a knight.

3. Consider the statement about a party, “If it’s your birthday or there will be cake, then there will be cake.”

(a) Translate the above statement into symbols. Clearly state which statement is $P$ and which is $Q$.

> P is "It's your birthday", and Q is "There will be cake". The statement is ($P \lor Q$) $\rightarrow Q$

(b) Make a truth table for the statement.

> Takes too much time and I'd rather tank the grade if there is deductions for not making a truth table as I can spend more time actually doing the exercises.

(c) Assuming the statement is true, what (if anything) can you conclude if you know there will be cake?

> You cannot conclude anything.

(d) Assuming the statement is true, what (if anything) can you conclude if you know there will not be cake?

> P will be false, it will not be your birthday.

(e) Suppose you found out that the statement was a lie. What can you conclude?

> Using a truth table I generated, I found that there is only one row where the premise of the overall statement is only false when P is true and Q is false. Meaning, It is your birthday, but there is no cake.

4. Geoff Poshingten is out at a fancy pizza joint and decides to order a calzone. When the waiter asks what he would like in it, he replies, “I want either pepperoni or sausage. Also, if I have sausage, then I must also include quail. Oh, and if I have pepperoni or quail, then I must also have ricotta cheese.”

(a) Translate Geoff’s order into logical symbols.

> Let:

> $P$ = "Geoff has pepperoni"

> $S$ = "Geoff has sausage"

> $Q$ = "Geoff has quail"

> $R$ = "Geoff has ricotta cheese"

His order:

($P \lor S$), ($S \rightarrow Q$), ($P \lor Q$) $\rightarrow R$

(b) The waiter knows that Geoff is either a liar or a truth-teller (so either everything he says is false, or everything is true). Which is it?

> Geoff is a liar, as each of the three parts of his order can be made false.

(c) What, if anything, can the waiter conclude about the ingredients in Geoff’s desired calzone?

> It must contain:

> either pepperoni or sausage.

> If it has sausage, then it must have quail as well.

> If it has either pepperoni, it must have ricotta cheese as well.