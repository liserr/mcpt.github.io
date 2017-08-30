---
layout: problem
title: Basically Right
problem-id: jdcc15octd
problem-author: Reyno Tilikaynen
contest: jdcc2015
round: 1
round-title: october
difficulty: d
---

# Problem
Eve, like many other students, wants to get a high mark. However, she forgot to study for her ICS exam and is shocked at the mark she received! Deciding to argue her grade, she thinks of the following plan: the teacher wrote down her mark as a fraction, but they never specified what base it's in, so to get a higher mark Eve can argue that her mark is given in a base other than 10. After doing some spying, she figures out that the teacher approves of this idea, however they limit the new base to be smaller than the denominator. Eve also has the option to not argue her mark. As someone who studied for their exam, help Eve figure out what is the best mark that she can receive.

**Note:** A number in base $$N$$ means that instead of the place values being ones, tens, hundreds, etc., they are ones, $$N$$'s, $$N^2$$'s, etc. For example, in base 10 the number $$123$$ is $$1 \times 100 + 2 \times 10 + 3 \times 1$$. In base $$4$$, it's $$1 \times 4^2 + 2 \times 4 + 3 \times 1$$. Numbers expressed in base $$N$$ can't have digits greater than or equal to $$N$$ (e.g. you can't have $$124$$ in base $$4$$). To convert out of base $$N$$, multiply each digit by its place value and add them together (e.g. $$123$$ in base $$4$$ is $$1 \times 16 + 2 \times 4 + 3 \times 1 = 27$$).

---

# Input
The first line of the input provides the number of test cases, $$T (1 \leq T \leq 100)$$. $$T$$ test cases follow, each test case consisting of two integers $$N$$ and $$D (1 \leq N \leq D  \leq 1200)$$, the numerator and denominator of her grade.

# Output
For each test case, output the percent value of the highest possible mark she can achieve by changing the base, rounded to 6 decimal places.

---

# Sample Input
{% highlight text %}
3
11 100
12 23
43 57
{% endhighlight %}

# Sample Output
{% highlight text %}
75.000000
54.545455
79.094077
{% endhighlight %}

# Explanation for Sample Output
In the first case, Eve should argue the mark is in base $$2$$, which would make it $$\frac{3}{4}$$.

---

# Editorial
[Read only if you are stuck or have already solved the problem.](/cpt-editorials/jdcc/2015/october/d)
