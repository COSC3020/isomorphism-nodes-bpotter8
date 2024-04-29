[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Answer:

Two graphs can only be isomorphic if there exists a bijection between their nodes. 

If graph $A$ has more nodes than graph $B$, there will be a node or some nodes in graph $A$ that do not have any correlation with graph $B$. If graph $B$ has more nodes, then it will contain nodes that have no correlation with graph $A$.

If there exists a node in graph $A$ that has no relation to a node in graph $B$, or there exists a node in graph $B$ that has no relation to a node in graph $A$, then the two graphs are not isomorphic.
