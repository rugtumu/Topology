# Topological Spaces

**Definition** A collection $\tau \subseteq 2^X$ is said to be a **topology** on $X$ if

$i)\; \emptyset,X \in \tau$
$ii)\; O_1,O_2 \in \tau \; \Rightarrow \; O_1\cap O_2 \in \tau$
$iii)\; \forall (O_{\alpha})_{\alpha \in I} \subseteq \tau,\; O=\bigcup_{\alpha \in I} O_{\alpha} \subseteq \tau.$


**Definition** $(X,\tau)$ be a topological space. $\mathcal{B}\subseteq\tau$, a collection of open sets in $X$. $\mathcal{B}$ is said to be a **basis** for $\tau$ if $\forall O\in \tau, \;\exists(B_{\alpha})_{\alpha\in I} \subseteq \mathcal{B}$ s.t. $\cup_{\alpha\in I} B_{\alpha} =O$.