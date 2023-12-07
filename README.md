[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13107045&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

# Proof

Suppose $A$ is a graph $G_1 = (V_1, E_1)$ and $B$ is another graph $G_2 = (V_2, E_2)$ where

$V_1 = {A, B, C}$ and $V_2 = {D, E, F}$

$E_1 = {(A, B)}$ and $E_2 = {(D, E)}$

Now suppose there is a function $f: V_1 -> V_2$ such that 

$f(A) = D$, 

$f(B) = E$

$f(C) = F$

We see that f is a bijection between graphs $A$ and $B$, and that for the edge $(A, B) \in E_1$, $(D, E) \in E_2$. 
This satisfies in showing that $A$ and $B$ are isomorphic by its definition. 

Further, we see that $A$ and $B$ are not completely connected themselves, yet they're still isomorphic to each other.
Thus, this example proves the theorem. 
