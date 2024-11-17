# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

After completing the isomorphism connectivity exercise, we know that two graphs are considered isomorphic if there is a one-to-one correspondence (bijection) between vertices. In order for this to be possible, there is a node requirement. Meaning that since a bijection requires matching between each vertex in one of the graphs to each vertex in the other graph, it won't be possible to have isomorphism if there is a different number of nodes. SO if two graphs do not have the same number of nodes, then they cannot be isomorphic. 

Proof:

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Knowing this definition $f$ must be both a one-to-one (bijection) and be considered onto. So every vertex in $V_1$ maps onto a specific vertex in $V_2$, and every vertex in $V_2$ must be the image of some vertex in $V_1$. 

In order for $f$ to be bijective, the size of $V_1$ must match the size of $V_2$. So specifically $|V_1| = |V_2|$. This helps us with the analysis because if these do not equal each other then a bijection can not exist (if $|V_1| \not= |V_2|$, then no bijection $f: V_1 \rightarrow V_2$ can exists). 

By looking at the contrapositive argument, we can see that if not bijection f exists between $V_1$ and $V_2$, then $G_1$ and $G_2$ can't be isomorphic. 

Without a bijection between vertices, the graphs are not capable of satisfying the definition of isomorphism. This means that if two graphs do not have the same number of nodes, then they can not be isomorphic.


References:

Was able to use my information from isomorphism-connectivity to help come to this conclusion, so those references such as the videos and geeksforgeeks still applies, as well as the github mathematical expressions. 


I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.

