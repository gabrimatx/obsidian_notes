- **Forward chaining** resolves in $O(var(\Gamma))$ and needs a set of **definite clauses** to work (and also starting **facts**).
- Always remember to work with $\nvDash \Gamma \wedge \neg \psi$  when proving with **propositional resolution** and **tableaux**.  
- To check if $\phi \vDash \psi$ with hypothetical function $TAUT(\zeta)$ you must check $TAUT(\phi \rightarrow \psi)$ or  $TAUT(\neg \phi \vee \psi)$.