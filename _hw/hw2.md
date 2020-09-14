---
layout: assignment
title: Homework 2
duedate: 2020-09-23
mathjax: true
---

<!--  -->
Please remember to include your name and the homework number (this is
Homework 2) within the document. Some additional formatting instructions
are in the syllabus. To summarize:

* Turn in your homework as a PDF with a filename like
  `584-Homework-<number>-<your last name>.pdf`,
  e.g.,
  `584-Homework-03-Smith.pdf`
* Use a new page (`\newpage`) for each problem
* State which question you are answering and the actual question.
  Then, start your answer in a new paragraph
* Use environments such as `proof` and `theorem`
  (via `\begin{proof}`...`\end{proof}`)
* Use 12pt option `\documentclass[12pt]{amsart}`
  and `\linespread{2.4}`.

Please find and use the LaTeX template uploaded to BlackBoard and/or
course website.

This homework involves exercises from the Hassett textbook.
1. A.13 (Appendix A, page 244)
2. One of 1.7 or 1.8 (Chapter 1, page 8) (for Exercise 1.8, the relevant example is Example 1.9)
3. One of 1.9-1.14*

* Exercise 1.12 should say: Show that at least four of these points are collinear.

Exercise 1.8 is more straightforward than 1.7, and probably
1.10 is more straightforward than then other ones 1.9, 1.11-1.14.
(The tricky part is knowing what "ring of \\(k\\)-valued functions on \\(S\\)" means.
It means functions from the set \\(S\\) to the field \\(k\\).
Any polynomial $$f$$ gives you one of these functions, $$f : S \to k$$,
where for each point $$P$$ in the set $$S$$,
$$f(P)$$ is given by evaluating the polynomial $$f$$ at the point $$P$$---in other words,
plugging $$P$$ into $$f$$.
If $$S$$ has $$m$$ points \\(P_1,\dotsc,P_m\\), then each function gives a vector of values,
\\( (f(P_1),\dotsc,f(P_m)) \\), and we can think of this ring of functions as an $$m$$-dimensional
vector space, $$k^m$$.
Can you see why the mapping from \\( P_{n,d} \\) to this vector space is a linear map,
and how the ideal $$I$$ relates to the kernel?)

(I hope that you will at least think a little about all of these problems and solve
as many as possible. Turn in the best and/or most interesting ones you are able to solve.)

You are encouraged to work together on the homework!


