---
marp: true
theme: uncover
class: invert
---

# <!--fit-->Topic 1

---

Decision problems map strings/programs to Booleans

---

Finite automaton can be represented as a 5-tuple
$M = (Q, \sum, \delta, q_0, F)$ where:
$$
\begin{aligned}
Q &= \text{set of states} \\
\sum &= \text{alphabet} \\
\delta &= \text{transition function} \\
q_0 &= \text{start state} \\
F &= \text{set of final states}
\end{aligned}
$$

---

They can also be represented as a graph with states as nodes and transitions as edges or as a table with states as rows and alphabet as columns (see notes pg 2)

---

Set operations:

$$
\begin{aligned}
A \cup B &= \{x \mid x \in A \text{ or } x \in B\} \\
A \cap B &= \{x \mid x \in A \text{ and } x \in B\} \\
\overline{A} &= \{x \mid x \notin A \} \\
A^* &= \{x_1 x_2 \cdots x_n \mid x_i \in A \text{ for all } i \in \{1, 2, \cdots, n\}\}\\
A \times B &= \{(x, y) \mid x \in A \text{ and } y \in B\}\\
A \circ B &= \{xy \mid x \in A \text{ and } y \in B\}
\end{aligned}
$$
