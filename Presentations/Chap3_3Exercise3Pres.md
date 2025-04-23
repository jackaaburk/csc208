# Chapter 3.3 Exercise 3 Solution

> "A group of college students was asked about their TV watching habits. Of those surveyed, 29 students watch The Walking Dead, 24 watch The Blacklist, and 27 watch Game of Thrones. Additionally, 10 watch The Walking Dead and The Blacklist, 13 watch The Walking Dead and Game of Thrones, and 17 watch The Blacklist and Game of Thrones. There are 8 students who watch all three shows. How many students surveyed watched at least one of the shows?"


This problem can be solved easily with the inclusion and exclusion principles.

Let:
A = The Walking Dead
B = The Blacklist
C = Game of Thrones

Let's visualize this with a Venn Diagram.

![VennDiagram](../images/VennDiagram.png)

To get the answer to the problem, you must find how many students watches at least one of the shows, which can be represented as:
- $|A \cup B \cup C|$

The principles of inclusion and exclusion states that $|A \cup B \cup C|$ can be found with:

- $|A \cup B \cup C| = |A| + |B| + |C| - |A \cap B| - |A \cap C| - |B \cap C| + |A \cap B \cap C|$

This counts each of the people who watched any of the three movies. However, there is overlap and therefore overcounting. The principles solve this issue by subtracting each intersection. However, the intersection of each three movies ($|A \cap B \cap C|$) is both added thrice and removed thrice, making it uncounted completely. Which is why it is added at the end of the principle.

Now, we can simply just plug in the amount of students per movie.

$|A \cup B \cup C| = 29 + 24 + 27 - 10 - 13 - 17 + 8$ 

This will equal 48 which is our final answer.