- When renaming, constants cannot be changed and also you can't rename two different variables into the same constant.
- **Constants** are **functions** of $\text{arity}\ 0$.
- $\text{The formula does not contain free variables} \implies \text{closed formula or sentence}$
- $\text{The formula does not contain any variable} \implies \text{ground formula}$
- $\text{The formula does contains atleast one free variable} \implies \text{open formula}$
- To reduce to clausal form, the procedure is always:
	1. Transform into NNF.
	2. Transform into prenex NNF.
	3. Transform into prenex CNF.
	4. Skolemize.
	5. Remove universal quantifiers.
- The interpretation of predicates is the set for which they evaluate to true.
- Predicates and $\top,\bot$ are atomic formulas.
- Every constant symbol $c$ is a **term**, every variable $x$ is a term. If $t_1,...,t_n$ are terms then $f(t_1,...,t_n)$ is a term. A term with no variables is called **ground term**.
- Consider the two predicates $R(f(x),z)\ \text{and}\ R(f(c),x)$, they unify because $x,z$ on the same position means that they share the same domain, so the two atomic formulae unify under $\sigma=\{\{x/c,z/c\},\cdot\}$.
- When converting to prenex CNF, describe what each step means. Example:
	- Conversion to NNF:
		- Remove all occurrencies of $\rightarrow, \leftrightarrow$.
		- Pushh all $\neg$ inwards.
- Be careful of quantifier scopes (my common distraction error).