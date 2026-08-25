---
title: Author's reply \#1
subtitle: manuscript NPB-D-26-01179
fontsize: 11
header-includes:
  - \usepackage{xcolor}
  - \usepackage{cancel}
---

## To the Editor

We, first, would like to thank the Editor for the opportunity to submit this response. We have addressed all the concerns and suggestions raised by Reviewer\#1, in detail. Our point-by-point responses are provided below. For completeness, a summary of changes made to the manuscript can be found at the end of this letter. We hope the manuscript may now be considered favorably for publication.

## To Reviewer\#1

We would like to sincerely thank Reviewer\#1 for the careful evaluation of our manuscript, and for the constructive comments and suggestions. We have carefully considered all points raised. Below, we addressed them in detail, along with the corresponding revisions to the manuscript. Hopefully, the presentation is sufficient to fully alleviate Reviewer\#1's concerns.

> "My main concern about this work is the following: looking at eqs.(19a)-(19d), it turns out that the operator $\bar{s}$ splits as $\bar{s}=s+Q$ where $sA=\psi$, $s\psi=-D\phi$, $s\phi=0$, $sF=-D\psi$, $s(\varphi,\eta,\xi,b)=0$ and $Q(A,\textcolor{red}{\psi},\phi,F)=0$ \textcolor{red}{[my correction]}, $Q\varphi=\eta$, $Q\eta=0$, $Q\xi=b$, $Qb=0$ with $(s,Q)$ anti-commuting. The operator $Q$ is nothing but the Fujikawa operator acting on the quartet $(\varphi,\eta,\xi,b)$. The previous splitting means that the spontaneous symmetry breaking pattern is always tied to $Q$, i.e. to the usual Fujikawa operator, not affecting the operator $s$.

> As such, my impression is that nothing new happens. The breaking remains confined to the Fujikawa sector. I would strongly recommend that the author checks out explicitly if the topological observables built out from $(A,\psi,F,\phi)$ receive quantum corrections exhibiting a manifest dependence from the parameter $B_0$. The addition of an explicit computation would be much helpful."

Reviewer\#1 is correct that the operator $\bar{s}$ in eqs. (19) can be split into two nilpotent and anti-commuting pieces. This kind of split can introduce a bi-grading in a factorized field space, and is a common occurrence in BRST algebra cohomology (see [@baulieu1985a;@perry1993a;@barnich2000a] for similar examples). In what follows, we analyze the meaning and consequences of the proposed split, clarifying, in particular, why it is insufficient to algebraically or dynamically define disconnected sectors of the physical theory. Subsequentially, we also clarify the argument for the $B_0$-dependence of quantum observables in the adjoint model.

Before proceeding further, let us consider a quick change in notation: $\bar{s}=s_1+s_2 \; ; \; s_1^2=s_2^2=\{s_1,s_2\}=0$. There is a good reason for this: the $s$ defined above by Reviewer\#1 is not quite isomorphic to the $s$ defined in the manuscript (eqs. (5) _and_ (11)), and this distinction is important (see below). Let us also assume the total field space $\mathcal{F}= \mathcal{F}_1 \oplus \mathcal{F}_2$, with $\mathcal{F}_i=\{\Phi^i(x)\}$ and $i\in\{1,2\}$, which mirrors the split suggested by Reviewer\#1: $\Phi^1=(A,\psi,\phi)$ and $\Phi^2=(\varphi,\eta,\xi,b)$. Technically, we also have to consider the $k$-jet space $J^k\mathcal{F}=J^k\mathcal{F}_1 \oplus J^k\mathcal{F}_2$, with $J^k\mathcal{F}_i=\{\Phi^i, \partial_{\mu}\Phi^i, \cdots, \partial_{(\mu_1 \cdots \mu_k)}\Phi^i\}$, and the algebra of local functions over it, $\mathcal{A}_{loc}(J^k \mathcal{F})=\{ f(\Phi^1, \Phi^2, \partial_{\mu}\Phi^1, \partial_{\mu}\Phi^2, \cdots, \partial_{(\mu_1 \cdots \mu_k)}\Phi^1,\partial_{(\mu_1 \cdots \mu_k)}\Phi^2)\}$. The latter is where Lagrangians belong to, and from where observables are filtered out of via cohomologies groups. So, we assume that all cohomologies below are over $\mathcal{A}_{loc}(J^k \mathcal{F})$, unless explicitly state otherwise.

Let us address the split:

- Physical observables do not factorize. The proposed split factorizes the spaces $\mathcal{F}$ and $J^k \mathcal{F}$ but does not generically factorize the algebra $\mathcal{A}_{loc}(J^k \mathcal{F})$. It is easy to accept this since there is no reason for a generic local function $f([\Phi^1], [\Phi^2])$ in $\mathcal{A}_{loc}(J^k \mathcal{F})$ to necessarily assume the form $f_1([\Phi^1])+f_2([\Phi^2])$ --- here we have adopted the compact notation $[\Phi^i]\equiv(\Phi^i, \partial_{\mu}\Phi^i, \cdots, \partial_{(\mu_1 \cdots \mu_k)}\Phi^i)$. Thus, the cohomology $H(\bar{s}) \sim H(s_1+s_2)$ does not simply factorize into $H(s_1) \oplus H(s_2)$ or even $H(s_1) \otimes H(s_2)$. In homological perturbation theory, $H(s_1+s_2)$ can be approximated by a spectral sequence $E_1 \rightarrow E_2 \rightarrow \cdots \rightarrow E_{\infty}$, implying _descent equations_ --- a hierarchical tower of coupled equations of mixing degrees involving both $s_i$. This does not equate to the simple evaluation of each $H(s_i)$, which only inform us about obstructions to lift bottom solutions up the tower. So, generic $(s_1+s_2)$-observables over $\mathcal{A}_{loc}(J^k \mathcal{F})$ are in non-trivial mixtures of the "$s_i$-sectors". The split alone is not sufficient, for example, to confirm that the order parameter $B_0$ remains confined at a "$s_2$-sector" --- we will come back to this point;

- The dynamics also does not factorize. This is, of course, related to the previous point since the $\bar{s}$-symmetric action $\bar{S}_{\text{aFH}}$, in eq. (17), is just an integrated element of $\mathcal{A}_{loc}(J^2 \mathcal{F})$. Had $\mathcal{A}_{loc}(J^k \mathcal{F})$ factorized, then necessarily $\bar{S}_{\text{aFH}}[\Phi^1, \Phi^2] = S_1[\Phi^1] + S_2 [\Phi^2]$ and only free theories between the $\Phi^i$-sectors would exist. Consequentially, only factorizable vacuum-to-vacuum amplitudes would be possible, $\bar{Z}_{\text{aFH}} = Z_1 \otimes Z_2$, with $\bar{Z}_{\text{aFH}} = \int \mathcal{D}\Phi^1 \mathcal{D}\Phi^2 e^{-\bar{S}_{\text{aFH}}[\Phi^1,\Phi^2]}$ and $Z_i = \int \mathcal{D}\Phi^i e^{-S_i[\Phi^i]}$. In such a scenario, Reviewer\#1's concerns would be fully justified: each $\Phi^i$-sector would only be able to interact with itself, and effects would remain sector-confined. However, this is not the case here. Interacting theories exist, such as the one in (17), implying non-factorizable $\bar{Z}_{\text{aFH}}$: the $\Phi^i$-sectors can dynamically influence each other;

- $H(s_1+s_2) \nsim H(s_i) \; \forall \; i$. To be convinced of this, notice how the split field transformations, $s_i \Phi^j = \bar{s} \Phi^i \;; \; i=j$ and $s_i \Phi^j=0 \;;\; i \neq j$, put $[\Phi^j]$ --- and many functions depending on it --- directly inside $H(s_i)\; ; \; i \neq j$, since they are $s_i$-closed but not $s_i$-exact. These classes are in excess, making it obvious that $H(s_i)$ just cannot be in one-to-one correspondence with $H(s_1+s_2)$. This also further clarifies why neither $H(s_1)\oplus H(s_2)$ nor $H(s_1)\otimes H(s_2)$ can be isomorphic to $H(s_1+s_2)$: no amount of linear combination can get rid of the excess. Additionally, because (17) is $\bar{s}$-symmetric, it cannot also be $s_i$-symmetric. In fact, $s_i$-symmetric theories in $\mathcal{A}_{loc}(J^k \mathcal{F})$ are non-topological (standard) local field theories --- the excess consists of classes not associated with topological invariants;

- $H(s_1+s_2) \sim H(s_1,\mathcal{A}_{loc}(J^k\mathcal{F}_1))$. On one hand, due to its $s_2$-doublet structure, functions of $[\Phi^2]$ cannot be in $H(s_2)$. On the other, due to their $s_2$-closedness, every function built exclusively out of $[\Phi^1]$ is in $H(s_2)$. Thus, we can conclude that $H(s_2) \sim \mathcal{A}_{loc}(J^k\mathcal{F}_1)$. This is important, the $s_2$-cohomology over $\mathcal{A}_{loc}(J^k\mathcal{F})$ just collapsed to $\mathcal{A}_{loc}(J^k\mathcal{F}_1)$, implying that the spectral sequence above becomes exact at the second page, $E_2 \sim E_\infty$. Assuming a $s_1$-filtration [@piguet1995a], we have $E_1 \sim H(s_2)$ and $E_2 \sim H(s_1,H(s_2))$, where $H(s_i,H(s_j))$ is the iterative $s_i$- over the $s_j$-cohomology. Thus, the exactness of $E_2$ implies $H(s_1+s_2) \sim H(s_1,\mathcal{A}_{loc}(J^k\mathcal{F}_1))$[^collapse]. In other words, $(s_1+s_2)$-observables over $\mathcal{A}_{loc}(J^k\mathcal{F})$ are isomorphic to $s_1$-observables over $\mathcal{A}_{loc}(J^k\mathcal{F}_1)$[^rig]. The latter are isomorphic to the $s$-observables of pure TYM theories --- the Donaldson polynomials in eq. (6). Therefore, the split $\bar{s}=s_1+s_2$ just gave us a very convoluted way to conclude that $H(\bar{s}) \sim H(s)$[^orig-coho]. This fact was readily recognized in the manuscript in a much more straightforward manner (see, _e.g._, the paragraph surrounding (19)).

Hopefully, the discussion above has convinced Reviewer\#1 that the proposed split is not very helpful. Nonetheless, Reviewer\#1's main concern is still valid: the aFH fields $\Phi, \eta, \xi, B$ were introduced via $s$-doublet structures[^intentional]; functions like $f([\Phi], [\eta], [\xi], [B])$ are forbidden inside $H(s)$; thus, how can one claim relevant physics emerges out of the shift $(B,\Phi) \mapsto (B_0+b, \Phi_0+\varphi)$? Isn't $H(s)$ completely insensitive to it? This line of questioning might better illustrate the "sector-isolation" Reviewer\#1 is concerned about. And, the answer is quite straightforward. Yes, $H(s)$ is completely insensitive to the shift. Let us address this issue now:

- A common ground: classically "nothing new happens". The adjoint model is particular, it has no Nambu-Goldstone fermion in (17). Thus, (17) remains $\bar{s}$-symmetric, and $H(s) \sim H(\bar{s})$ remains relevant in classifying the physical observables of the model. Saying it differently, _classically_, the topological BRST symmetry does not spontaneously break alongside the gauge symmetry; it is _classically_ stable, $\bar{s}(B_0,\Phi_0)=(0,0)$. Additionally, the representatives of the classes in $H(s)$ do not change as they normally do in a traditional Higgs setup[^higgs], _i.e._, they remain the Donaldson polynomials in eq. (6). Thus, Reviewer\#1's main concern is fully realized in this limit: (8)+(12) and (8)+(17) are just complicated ways to write down (8); nothing new physically happens. In particular, physical observables cannot effectively depend on $B_0$. Why then does Section 3 exist? The adjoint model is physically interesting because the quantization of (8)+(12) or (8)+(17) does not simply equate the quantization of (8). We should address this in more detail;

- Uneven ground: quantum mechanically "something new does happen". We have emphasized how cohomologies depend on the choice of (nilpotent) differential _and_ representation space. Classically, we only worried about $s$ and $\mathcal{A}_{loc} (J^k\mathcal{F})$ --- implicit in $H(s)$. Nonetheless, upon quantization, we also have to worry about $\hat{Q}$ and $\mathbb{H}$, respectively, the BRST charge operator acting on the Hilbert space of states. Assuming no instantons, the vacuum state $| 0 \rangle \in \mathbb{H}$ is usually considered non-degenerate; uniquely defined by $\hat{\mathbb{E}}_{\text{aFH}} | 0 \rangle=0$ and $\hat{Q} | 0 \rangle = 0$. Due to the latter condition, the VEV of $s$-exact local functions automatically vanishes, $\langle sf \rangle_{0} = \langle 0 | [\hat{Q},\hat{f}] | 0 \rangle = 0 \;;\; \forall \; f \in \mathcal{A}_{loc} (J^k\mathcal{F})$. And, the $\hat{Q}$-cohomology over $\mathbb{H}$ successfully defines the physical subspace of states, $H(\hat{Q},\mathbb{H}) \equiv \mathbb{H}_{\text{phys}} \subset \mathbb{H}$[^ommit]. This is the standard BRST formalism in the quantum regime. However, our adjoint model implies the opposite, $\langle \bar{s}\xi \rangle_0 = \langle 0| [\bar{Q}, \xi] |0 \rangle \neq 0$. This can only be due to the topological BRST spontaneously breaking alongside the gauge symmetry[^only-possibility]. In other words, $\exists \; | \Omega \rangle \in \bar{\mathbb{H}} \;;\; \bar{Q}| \Omega \rangle \neq 0$. This is a new vacuum state, degenerated with $| 0 \rangle$, encapsulating new physics. Why and How? $\mathbb{H}$ and $\bar{\mathbb{H}}$ define disconnected vacuum sectors since we are at the infinite volume limit, with $\mathbb{H}$ unstable and $\bar{\mathbb{H}}$ stable according to $\langle \bar{\mathbb{E}}_{\text{aFH}} \rangle_\Omega$. $\mathbb{\bar{H}}$ is a new representation space for the BRST algebra, but $H(\bar{Q}, \bar{\mathbb{H}})$ fails to properly define $\bar{\mathbb{H}}_{\text{phys}}$[^fail]. Again, despite $H(Q,\mathbb{H}) \sim H(\bar{Q}, \bar{\mathbb{H}})$ remaining true[^analogue], $H(\bar{Q}, \bar{\mathbb{H}}) \nsim \bar{\mathbb{H}}_{\text{phys}}$. Thus, $\mathbb{H}_{\text{phys}} \nsim \bar{\mathbb{H}}_{\text{phys}}$[^adj-population]. The lesson here is that the topological BRST is classically stable, but quantum mechanically unstable. The latter means such a symmetry is inadequate to establish the physical content of the quantum model in the stable vacuum sector. Essentially, new (local) physics emerge because, in this regime, the model is not cohomologically forced to behave as a TQFT. Its effective (quantum) observables are not classified by $H(s) \sim H(\bar{s})$; they are not the Donaldson polynomials. In fact, they have no reason to be topological at all and, in principle, can depend on $[A], [\psi], [\phi]$ _and_ $[\varphi], [\eta], [\xi], [b]$. Ultimately, also exhibiting $B_0$-dependence.

To finish our discussion, we acknowledge that the argument above --- also present in the manuscript, albeit in a shorter form --- has a heuristic nature. And, we agree that only explicit quantum mechanical computations can unequivocally settle this issue. However, these computations are out of the scope of the current manuscript for the following reason. The adjoint model presents a novel dynamics, with spontaneously broken gauge and BRST symmetries. Its formal perturbative definition requires a careful analysis. For instance, renormalizable gauges are not known _a priori_; instead, they have to be proven. We are currently addressing this issue for the (A)SDL gauge in a separate manuscript. And, we intend to also extend the proof for t' Hooft-like ones as well due to their importance in spontaneously broken scenarios.

We opted, instead, to proceed by defining a theory in which gauge _and_ BRST symmetries spontaneously break --- visibly --- in the classical limit, _i.e._, $\bar{s}(B_0, \Phi_0) \neq (0,0)$. Remarkably, it was enough to simply change the representation of the FH fields from the adjoint to the (realified) fundamental one. Eqs. (31-33) are explicit computations in this model, demonstrating the emergence of new (local) physics via the generation of the Nambu-Goldstone fermion $(\eta, \xi)$, and the concurrent lack of $\bar{s}$-symmetry in (31) --- the effective dynamics in the stable/minima sector. In particular, Reviewer\#1 can notice that the arguments made for this (realified) fundamental model, present in the manuscript after (33), are analogous to the ones made in the last bullet point above; for the adjoint one. Ultimately, in both cases, the $B_0$-dependence of observables is possible not because $H(s)$ changes, but because it fails to classify them in the stable vacuum sector of the theory.

[^adj-population]: $\bar{\mathbb{H}}_{\text{phys}}$ is the space "generically populated with local degrees of freedom: massless and massive gauge field states, Higgs-like bosonic field states, and Nambu-Goldstone fermionic field states".

[^ommit]: From now on, we ommit $\hat{\phantom{x}}$ on operators since the context is sufficiently clear.

[^intentional]: This was, of course, intentional as we did not want to explicitly spoil the topological nature of the theory.

[^analogue]: This is the quantum mechanical analogue of $H(s) \sim H(\bar{s})$.

[^fail]: The spontaneously broken condition, $\bar{Q}| \Omega \rangle \neq 0$, means $H(\bar{Q}, \bar{\mathbb{H}})$ fails to account for $| \Omega \rangle$, and many other effective physical states living in $\bar{\mathbb{H}}_{\text{phys}}$, including the Nambu-Goldstone fermionic state $\bar{Q}| \Omega \rangle$ associated with the breaking --- notice the former is not $\bar{Q}$-closed, and the latter is $\bar{Q}$-exact.

[^only-possibility]: Such non-vanishing VEVs can only originate from: (i) gauge anomalies; (ii) explicit or; (iii) spontaneous BRST symmetry breakings. In our case, scenario (i) is impossible because $H(\bar{s}) \sim H(s)$ is trivial at ghost number 1 and form rank 4; scenario (ii) is also impossible since $\bar{s}\bar{S}_{\text{aFH}}=0$; thus, it has to be due to (iii).

[^higgs]: In the traditional Higgs, the BRST is also stable; and $H(s) \sim H(\bar{s})$ also holds. However, the Higgs field is not introduced via a $s$-doublet structure. So, functions of $[\Phi]$ can be in $H(s)$ as long as they are $s$-closed but not $s$-exact, and its class representatives will change under the shift $\Phi \mapsto \Phi_0 + \varphi$. The biggest example being the Lagrangian itself.

[^orig-coho]: $H(s)$ is assumed to be over the algebra of local functions of the original fields $A, \psi, \phi, \Phi, \eta, \xi, B$, not the fluctuations $A, \psi, \phi, \varphi, \eta, \xi, b$.

[^collapse]: The exactness of $E_2$ means, in terms of the descent equations, that every solution that survived the lift from ground to 1st floor of the tower, can now be trivially lifted _ad infinitum_ until it reaches the top $E_\infty \sim H(s_1+s_2)$. Saying it differently, all obstructions are concentrated on the 1st flight of stairs, and are enough to completely remove all the excess previously in $H(s_i)$, ultimately resulting in the one-to-one correspondence with $H(s_1+s_2)$.

[^rig]: This is the rigorous version of statement "$s_1$ is the non-trivial part of $s_1+s_2$" which, at times, is reproduced without proper nuance. Notice, in particular, that the cohomologies in the LHS and RHS of the isomorphism ($\sim$) are evaluated over different algebras/field spaces --- the former over $\mathcal{A}_{loc}(J^k\mathcal{F})$; the latter over $\mathcal{A}_{loc}(J^k\mathcal{F}_1)$. In general, cohomologies depend on their differentials _and_ on the algebras they are evaluated. So, for instance, $s_1$ is non-topological over $\mathcal{A}_{loc}(J^k\mathcal{F})$, but it is topological over $\mathcal{A}_{loc}(J^k\mathcal{F}_1)$ --- coinciding with the $s$ in pure TYM theories in eq. (5).

## Summary of changes

We have restricted changes to the original manuscript to those that improve clarity and/or fix typos. Below, an exhaustive list is presented in order of page appearance. Mind, the page numbers regard the new PDF version; not the old one.

Captions: ~~deletions~~; **additions**.

- (p1): Physical observables can then be consistently defined in the classical and quantum realm through its **local** cohomology groups;

- (p5): (ii) also already mentioned, the **local** cohomology groups it defines forbids the presence of g metric-contaminated observables;

- (p5): Assuming BRST stability, all non-trivial ~~local~~ observables are ~~elements~~ **classified by non-trivial classes** in the **local** $s$-cohomology modulo $d$-boundaries;

- (p5): In other words, "topological BRST symmetries" force all ~~local~~ **non-trivial** observables to be topological in nature;

- (p7): In this sense, QTYM and classical TYM represent the same physical ~~theories~~ **theory**;

- (p8): living ~~outside~~ **"outside"** the **local** $s$-cohomology groups$^{\bf{15}}$;

- (p8): $^{\bf{15}}$**More rigorously, $s$-boundaries live as trivial classes in the $s$-cohomology groups**;

- (p8): and also implies that the **local** $s$-cohomology groups are explicitly preserved:~~no~~ new **non-trivial** observables are **not** introduced;

- (p10-11): the original topological features are still present in ~~the~~ **this** classical ~~realm~~ **limit**. **In fact, the representatives of non-trivial classes in the local s-cohomology remain unaffected by this process$^{\bf{18}}$. So, the non-trivial effective observables are still the Donaldson polynomials. Saying it differently, nothing physically significant happened thus far**;

- (p11): $^{\bf{18}}$**This is quite a departure from the traditional Higgs, not introduced via an $\bf s$-doublet. There, local functions of $\bf\Phi$ can also represent non-trivial classes in the local $\bf s$-cohomology, changing under the shift $\bf\Phi \mapsto \Phi_0 + \varphi$**;

- (p11): ~~Nevertheless, if $\langle 0 \rvert b \lvert 0 \rangle=0$, then (19c) implies $\langle 0 \rvert \bar{s}\xi \lvert 0 \rangle=B_0$~~ **Upon quantization, however, and assuming $\bf \langle b \rangle_{\Omega}=0$ with respect to the effective vacuum state $\bf \lvert \Omega \rangle$, then (19c) implies $\bf \langle \bar{s}\xi \rangle_{\Omega}=B_0$**. As long as $B_0=0$, this ~~is a sufficient condition for~~ **can only be due to the** spontaneous BRST symmetry breaking, $\bf \bar{Q} \lvert \Omega \rangle \neq 0^{19}$. In turn, Nambu-Goldstone fermionic states\textbf{, associated with $\bf \bar{Q} \lvert \Omega \rangle$,} must necessarily be present **in the Hilbert subspace of effective physical states, $\bf \bar{\mathbb{H}}_{phys} \subset \bar{\mathbb{H}}$** \[1–3, 74, 75\]. Since such degrees of freedom are absent at tree-level, they must be **fully** generated by loop corrections or non-perturbative effects. ~~Saying it differently~~ **In other words**, the lack of a Nambu-Goldstone fermion in (18) implies that the Higgs-phase aTYMH theories must ~~be quantum mechanically non-trivial~~ **have quite interesting QFT structures**. This is a remarkably different scenario from what we started and, interestingly, one which blurs the line between spontaneous and dynamical symmetry breakings. Ultimately, we can conclude that the $\mathcal{G}$-equivariant cohomology of $\mathcal{A}$ no longer fully captures the complete set of Higgs-phase physical states~~:~~\textbf{, i.e., the $\bf \bar{Q}$-cohomology over $\bf \bar{\mathbb{H}}$ fails to define $\bf \bar{\mathbb{H}}_{\text{phys}}$;} we are no longer dealing with cohomological TQFTs\textbf{; $\bf \bar{\mathbb{H}}_{\text{phys}}$ is not solely populated by (topologically inequivalent) vacua};

- (p11): $^{\bf 19}$**Such non-vanishing vacuum expectation value can only originate from: (i) gauge anomalies; (ii) explicit or; (iii) spontaneous BRST symmetry breakings. In our case, scenario (i) is impossible because the local $\bf \bar{s}$-cohomology is trivial at form rank 4 and ghost number 1; scenario (ii) is also impossible since (17) is $\bf \bar{s}$-symmetric; thus, it has to be due to (iii)**;

- (p11): the situation around the trivial ~~vacuum~~ **extremum** is quite similar to pure TYM theories;

- (p11): we fully expect ~~$\langle 0 \rvert \bar{\mathbb{E}}_{\text{aFH}} \lvert 0 \rangle$~~ $\bf \langle \bar{\mathbb{E}}_{\text{aFH}} \rangle_\Omega$ to be bulk non-trivial;

- (p12): the ~~effective~~ inequivalent gauge vacua form the entire gauge moduli;

- (12): Contributions from all these ~~vacua~~ **minima** can potentially destabilize Higgs sector solitons;

- (p12): seems to be unavoidable in the classical ~~realm~~ **limit**;

- (p12): the quantum ~~realm~~ **regime** does suffer from BRST instability, implying ~~$\langle 0 \rvert \bar{\mathbb{E}}_{\text{aFH}} \lvert 0 \rangle \neq 0$~~ $\bf \langle \bar{\mathbb{E}}_{\text{aFH}} \rangle_{\Omega} \neq 0$ in the bulk;

- (p12): This latter fact localizes the **inequivalent** gauge vacua;

- (p15): Recalling the standard Higgs, with non-trivial ~~vacua~~ **minima** $\Phi_0$;

- (p15): This is the usual symmetry breaking pattern: in the trivial ~~vacuum~~ neighborhood;

- (p15): Interestingly, realification amplifies$^{\cancel{27}}$ the gauge symmetry breaking, increasing the number of massive gauge fields components by $2N-2$$^{\bf 27}$;

- (p15): the neighborhood of the non-trivial ~~vacuum~~ **minima** $(B_0,\Phi_0)$;

- (p16): Dramatically, the BRST instability of TYMH$_{\mathbb{R}}$ theories is a tree-level phenomenon$^{\bf 28}$;

- (p16): $^{\bf 28}$**The non-trivial minima $\bf (B_0,\Phi_0)$ break gauge \textit{and} BRST symmetries. In particular, $\bf \bar{s}(B_0, \Phi_0) \neq (0,0)$**;

- (p16): Even more dramatically, (31) is not a $\bar{s}$-cycle, automatically implying it also not a $\bar{s}$-boundary. **Thus, unsurprisingly, tree-level BRST instability implies that neither the local $s$- nor the local $\bf \bar{s}$-cohomology classifies the classical Higgs-phase observables, \textit{i.e.}, these have no reason to be topological in nature**;

- (p16): The Higgs-phase effective theories defined by (31) have lost every trace of topological BRST invariance\textbf{.} ~~--- the~~\textbf{T}he non-topological features hidden in the quantum regime of aTYMH theories, are here **fully** exposed at ~~tree-level~~ **the classical limit**;

- (p16): together imply local ~~(non-topological)~~ degrees of freedom are ~~now~~ present and physically relevant in the bulk;

- (p16): In other words, in this region of the moduli, $\text{TYMH}_{\mathbb{R}}$ theories ~~are~~ clearly **behave as** standard local field theories. **And, of course, this feature remains true upon quantization as the argument present in Section 3 also applies here, _i.e._, the $\bf\bar{Q}$-cohomology over $\bf\bar{\mathbb{H}}$ fails to define $\bf\bar{\mathbb{H}}_{\text{phys}}$**;

- (p17): Our ~~analysis~~ **analyses** have demonstrated;

- (p17): this is a surprising result in the context of topological field theories since they ~~are supposed~~ **were assumed** to be scale invariant theories **in all regimes**;

- (p17): precisely what **quantum** aTYMH and TYMH$_{\mathbb{R}}$ lack in their Higgs phases;

- (p17): We have ~~shown that~~ **argued for** the BRST instability ~~of~~ **in** aTYMH theories ~~happens~~ beyond **the** tree-level, and feature resembling the Coleman-Weinberg mechanism if loop corrections are to blame;

- (p17): quantum ~~realm~~ **regime**;

- (p17): the ~~tree-level~~ Higgs-phase energy functional $\bar{\mathbb{E}}_{\text{aTYMH}}$ is bulk trivial, but ~~$\langle 0 \rvert \bar{\mathbb{E}}_{\text{aTYMH}} \lvert 0 \rangle$~~ $\bf \langle \bar{\mathbb{E}}_{\text{aTYMH}} \rangle_{\Omega}$ is not;

- (p17): We ~~conclude~~ **infer** that Higgs-phase quantum aTYMH theories are generically populated with massless and massive gauge field states, Higgs-like bos onic field states, Nambu-Goldstone fermionic field states, as well as vertex or monopole non-local states depending on whether the metric structure of spacetime is Riemannian or Lorentzian, respectively;

- (p17): implying the emergence of a physical mass scale at **the** classical level;

- (p17): Similarly, the ~~tree-level~~ Higgs-phase energy functional $\bar{\mathbb{E}}_{\text{TYMH}_{\mathbb{R}}}$ is bulk non-trivial;

- (p17): Upon quantization, ~~the~~ **we infer that** Higgs-phase effective TYMH$_{\mathbb{R}}$ theories are generically populated with massless and massive gauge field states, Higgs-like field states, and Nambu-Goldstone fermionic field states;

- (p18): ~~topological~~ **cohomological** field theories.

## References
