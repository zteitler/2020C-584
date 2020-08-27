---
layout: assignment
title: Homework 0
duedate: 2020-09-02
---

This homework will be about using LaTeX to create a PDF,
and uploading that PDF to [BlackBoard](https://blackboard.boisestate.edu).
If you don't have LaTeX on your computer, you can use
[Overleaf.com](https://overleaf.com), or use the computer lab in MB 136.
You don't need to submit the LaTeX source, just the PDF.
Email your instructor (that's me) if you have questions or need help.

Please remember to include your name and the homework number
(this is Homework 0) within the document.
Some additional formatting instructions are in the syllabus.
To summarize:

- Turn in your homework as a PDF with a filename like
  `584-Homework-<number>-<your last name>.pdf`, e.g., `584-Homework-03-Smith.pdf`
- Use a new page (`\newpage`) for each problem
- State which question you are answering and the actual question.
  Then, start your answer in a new paragraph
- Use environments such as `proof` and `theorem` (via `\begin{proof}`...`\end{proof}`)
- Use 12pt option `\documentclass[12pt]{amsart}` and `\linespread{2.4}`.

Please find and use the LaTeX template uploaded to BlackBoard and/or course website.



1. (LaTeX: basics) Answer this question. Enter this LaTeX code into your tex file, and answer it:

    ```
    \begin{exer}
    What are the intersection $\{1,2,3,4,5\} \cap \{3,4,5,6,7\}$
    and the union $\{1,2,3,4,5\} \cup \{3,4,5,6,7\}$?
    \end{exer}
    \begin{answer}
    -enter your answer here-
    \end{answer}
    ```


2. (LaTeX: Using "split" to align equations) Complete this simplification.
Enter this LaTeX code into your tex file, and answer it (fill in the ?'s):

    ```
    \newpage
    \begin{exer}
    What is the sum of the squares of $\dfrac{1-t^2}{1+t^2}$ and $\dfrac{2t}{1+t^2}$?
    \end{exer}
    \begin{answer}
    \begin{theorem}
    $\left(\dfrac{1-t^2}{1+t^2}\right)^2 + \left(\dfrac{2t}{1+t^2}\right)^2 = ? $
    \end{f}
    \begin{proof}
    \begin{equation}
    \begin{split}
      \left(\frac{1-t^2}{1+t^2}\right)^2 + \left(\frac{2t}{1+t^2}\right)^2 &= ? \\
        &= ? \\
        &= ? \\
        &= ?
    \end{split}
    \end{equation}
    \end{proof}
    \end{answer}
    ```

3. (About yourself) Answer the questions.
  This will not be graded for correctness.
  The goal is just to tell me a little bit about yourself
  (and also to practice using LaTeX's enumerate lists).

    ```
    \newpage
    \begin{exer}
    \begin{enumerate}
    \item What name do you like to go by in class?
    \item What pronouns do you prefer (this could be she/her/hers, he/him/his, they/them/theirs, or other)?
    \item What is something that you are excited to learn in this class?
    \item What is something that you are concerned about in this class?
    \item Is there anything else you would like me to know?
    \end{enumerate}
    \end{exer}
    ```
