This repository contains the source of **No Quartic Graviton Dispersion from the Local Covariant Four-Derivative
Truncation** (paper III of the spectral gravity sub-programme).

This note settles one question about a posited kernel: whether the local covariant four-derivative
transverse-traceless kernel deforms the dispersion of the graviton. It does not. This is a negative result, and
its scope is exactly that.

## The operator considered

The projective spectral action assigns to a **Riemannian** metric the renormalized functional
$S_\Pi[g] = \tfrac12\log\det{}'A_g$.

A Lorentzian counterpart of that functional is **not available**: obtaining one requires an in-in construction on
a closed time path, which is open (see [Open problems](#open-problems)). The Lorentzian transverse-traceless
kernel is therefore **posited** here, not derived, and every statement below is conditional on that posit.

Assume that, linearized about Minkowski spacetime and restricted to the transverse-traceless sector, the local
Lorentzian quadratic kernel truncated at four derivatives is

$$\mathcal{O}_{\mathrm{TT}} = c_{\mathrm{EH}}\Box + \beta\Box^2 ,$$

with $c_{\mathrm{EH}}$ and $\beta$ real constants, non-local form factors and all terms of order $\Box^3$ and
higher being discarded. The results therefore have the form: *if* the local Lorentzian transverse-traceless kernel
is $\Box(c_{\mathrm{EH}} + \beta\Box)$, *then* the stated conclusions follow. They are not statements about
$S_\Pi$ itself, nor about the full renormalized kernel, and the difference matters wherever the discarded terms
are not negligible — in particular in the ultraviolet.

**Conventions.** Signature $(-,+,+,+)$ and units with $c = 1$. For a plane wave $e^{ik\cdot x}$ with
$k^\mu = (\omega, \vec{k})$, $\Box \to -k^2$ with $k^2 = -\omega^2 + |\vec{k}|^2$.

## Solution structure: a direct sum

Write $P = \Box$ and $Q = c_{\mathrm{EH}} + \beta\Box$, so that $\mathcal{O}_{\mathrm{TT}} = PQ = QP$.

Let $\mathcal{V}$ be any complex vector space of transverse-traceless tensor fields on which $\Box$ acts and which
is stable under it — smooth fields, or tempered distributions, indifferently. All kernels below are taken in
$\mathcal{V}$: the argument is algebraic and uses no property of $\mathcal{V}$ beyond stability.

For $c_{\mathrm{EH}} \neq 0$ the two factors are **coprime**, by the Bézout identity

$$Q - \beta P = c_{\mathrm{EH}} ,$$

a nonzero constant. The solution space is then the **direct sum**

$$\ker\mathcal{O}_{\mathrm{TT}} = \ker\Box \,\oplus\, \ker(c_{\mathrm{EH}} + \beta\Box) ,$$

and the decomposition of any $h^{\mathrm{TT}} \in \ker\mathcal{O}_{\mathrm{TT}}$ as $h^{\mathrm{TT}} = h_0 + h_m$
with $h_0 \in \ker P$ and $h_m \in \ker Q$ is unique. If in addition $\beta \neq 0$, then $\ker Q$ is
characterized by $\Box h_m = -(c_{\mathrm{EH}}/\beta)\,h_m$.

**The kernel is not a union.** Let $c_{\mathrm{EH}} \neq 0$, let $\beta \neq 0$, and suppose that **both**
$\ker P \neq \lbrace 0 \rbrace$ and $\ker Q \neq \lbrace 0 \rbrace$ in $\mathcal{V}$. These are hypotheses on
$\mathcal{V}$, not consequences of $c_{\mathrm{EH}} \neq 0$ and $\beta \neq 0$: a stable space may contain no
solution of either factor equation. They hold in the tempered distributions, where $\ker P$ carries the plane
waves with $k^2 = 0$ and $\ker Q$ those with $k^2 = c_{\mathrm{EH}}/\beta$.

Then the kernel is **strictly larger** than $\ker P \cup \ker Q$. Given nonzero $h_0 \in \ker P$ and
$h_m \in \ker Q$, the sum $h_0 + h_m$ solves $\mathcal{O}_{\mathrm{TT}} h^{\mathrm{TT}} = 0$ while satisfying
**neither** factor equation: $\Box(h_0+h_m) = -(c_{\mathrm{EH}}/\beta)h_m \neq 0$ and
$(c_{\mathrm{EH}} + \beta\Box)(h_0+h_m) = c_{\mathrm{EH}} h_0 \neq 0$. A generic solution is a superposition of
the two sectors, not a member of either.

Both hypotheses are needed. For $\beta = 0$ the operator reduces to $c_{\mathrm{EH}}\Box$ and
$\ker Q = \lbrace 0 \rbrace$: the direct-sum identity still holds, trivially, and the union coincides with the
kernel. Symmetrically, $\ker Q$ is itself stable under $\Box$ — if $Qh = 0$ then
$\Box h = -(c_{\mathrm{EH}}/\beta)h \in \ker Q$ — so $\mathcal{V} = \ker Q$ is an admissible choice; there
$\ker P = \lbrace 0 \rbrace$ by the Bézout argument, and the union again coincides with the kernel. Strictness is
a statement about a space containing **both** sectors.

**Degenerate case.** If $c_{\mathrm{EH}} = 0$ the Bézout identity fails and the decomposition is unavailable:
$\mathcal{O}_{\mathrm{TT}} = \beta\Box^2$, and $\ker\Box^2$ contains generalized solutions annihilated by
$\Box^2$ but not by $\Box$.

## Absence of a quartic graviton dispersion

For $c_{\mathrm{EH}} \neq 0$ the massless summand lies in $\ker\Box$ by construction, and $\ker\Box$ does not
depend on $\beta$. Hence for plane waves $h_0 \sim e^{ik\cdot x}$,

$$\omega^2 = |\vec{k}|^2 ,$$

**with no correction at any order in $|\vec{k}|$**.

A relation $\omega^2 = |\vec{k}|^2 - \gamma\,\ell_\chi^2 |\vec{k}|^4 + \mathcal{O}(|\vec{k}|^6)$ describes a
single branch whose massless dispersion is deformed at quartic order. The truncation has no such branch.
Expanding $(c_{\mathrm{EH}} + \beta z)^{-1}$ in powers of $z$ about $z = 0$ generates a series of terms
**analytic at the origin** — contact terms, in position space — added to the massless pole; it does not move that
pole, whose location is the zero of $\Box$ and is independent of $\beta$. Reading the resulting series as a
deformed dispersion relation mistakes an analytic background for a shift of the pole.

Gravitational-wave catalogues test modified dispersion through the phenomenological relation

$$E^2 = p^2c^2 + A_\alpha\,p^\alpha c^\alpha ,$$

constraining $A_\alpha$ for a range of exponents $\alpha$. The case $\alpha = 4$ is what a quartic deformation of
the massless branch would populate; the case $\alpha = 0$ corresponds instead to a mass term, so the
parametrization is **not blind to massive branches**.

Under the truncation with $c_{\mathrm{EH}} \neq 0$, the undeformed massless sector gives $A_4 = 0$ on the massless
branch. There is therefore **no mapping $A_4 \leftrightarrow \ell_\chi$**, and any bound on the pre-geometric
scale $\ell_\chi$ obtained by identifying an interferometric limit on $A_4$ with a quartic spectral coefficient
does not hold.

**What is *not* claimed.** This does not say that these data cannot constrain this framework. The $\alpha = 0$
sector bears on massive branches, and the pole of the next section is one. Turning that into an actual constraint
would require its mass, its coupling to the detector, and its excitation in the source — none of which is supplied
here. The negative result concerns the $A_4$ route only.

**No front-velocity claim.** $\omega^2 = |\vec{k}|^2$ is a statement about the truncation, not about signal
fronts. A front velocity is governed by the large-$k$ behaviour of the full kernel, precisely where the discarded
non-local and $\mathcal{O}(\Box^3)$ terms are not negligible. No statement about front propagation is made here,
in either direction.

## Pole content

Writing $z$ for the momentum-space image of $\Box$, the transverse-traceless propagator is, for
$c_{\mathrm{EH}} \neq 0$ **and** $\beta \neq 0$ — the partial fractions below divide by $\beta$ —

$$\frac{1}{z(c_{\mathrm{EH}} + \beta z)}
= \frac{1}{c_{\mathrm{EH}}}\left( \frac{1}{z} - \frac{1}{z + c_{\mathrm{EH}}/\beta} \right).$$

Two facts follow, and they are **independent of one another**:

1. **Ghost character.** The two residues have opposite signs, whatever the signs of $c_{\mathrm{EH}}$ and $\beta$.
   The second pole is therefore a ghost relative to the massless one. This does **not** depend on
   $c_{\mathrm{EH}}/\beta$.
2. **Tachyonic character.** The second pole sits at $z = -c_{\mathrm{EH}}/\beta$, so the sign of
   $c_{\mathrm{EH}}/\beta$ fixes the sign of the corresponding mass squared, and with it whether the mode is
   tachyonic. This is a separate question from (1) and has a separate answer.

For $\beta \neq 0$ the second pole sits at $k^2 = c_{\mathrm{EH}}/\beta$, that is at

$$m_2^2 = -\,\frac{c_{\mathrm{EH}}}{\beta} ,$$

in the conventions above.

This **resembles** the pole content of quadratic gravity, where a massless graviton is accompanied by a massive
spin-2 ghost (Stelle 1977; Calmet–Capozziello–Pryer 2017). The resemblance is a **comparison, not an
identification**: the transverse-traceless calculation establishes a helicity-2 pole with opposite residue,
whereas the massive spin-2 multiplet is a statement about all five polarizations. The scalar and vector sectors
are not treated here, so the full multiplet structure is not established.

**The scalar sector is not settled.** The minimal $a_4$ carries an $R^2$ sector alongside $C^2$. In the effective
action at second order in curvature this generically supports a massive scalar in addition to the massive spin-2
mode. Excluding it requires a matching condition on the $R^2$ coefficient, so the mode content of the truncation
is not fully determined here.

## What is matching data

The Seeley–DeWitt coefficient $a_4$ controls a **logarithmic contribution to the running** of the four-derivative
couplings. It does not fix the finite value of $\beta^{\mathrm{ren}}$.

The normalization and sign of $\tfrac12\log\det{}'A_g$ are **not** at issue: they are fixed by the definition of
the functional. What leaves $\beta^{\mathrm{ren}}$ undetermined is the finite parts of the counterterms, the
complete operator content, the continuation to Lorentzian signature, and the renormalization condition. An
identification $\beta = -2\alpha_C$ read off the Weyl-squared part of $a_4$ supplies none of these, and is not a
determination of $\beta^{\mathrm{ren}}$.

The same holds for $c_{\mathrm{EH}}^{\mathrm{ren}}$. Consequently the **signed mass squared**

$$m_2^2 = -\,\frac{c_{\mathrm{EH}}^{\mathrm{ren}}}{\beta^{\mathrm{ren}}}$$

— equivalently the pole scale $|c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}|$ together with its sign —
is a **matching datum, not derivably tied to $\ell_\chi$**.

## Open problems

- **The in-in construction.** A Schwinger–Keldysh effective action is built from doubled field configurations on a
  closed time path, with the branches coupled by the boundary condition at the turning point (Jordan 1986;
  Calzetta–Hu 2008). Substituting a retarded Green operator for $A_g^{-1}$ in an ordinary single-field Hessian is
  not that construction and does not follow from it. Whether the projective spectral action admits a
  closed-time-path formulation, and whether the quadratic form it would yield agrees with the truncation, is open.
- **The vector sector.** The linearized vector equation carries a $\Box\bar h_{0i}$ term, hence a second time
  derivative that harmonic gauge does not remove. Only under a stationarity assumption does it reduce to an
  elliptic constraint. A derivation from the full linear system with spin projectors, and the fate of the
  four-derivative correction within it, are open.
- **Beyond the truncation.** The truncation discards non-local form factors and $\mathcal{O}(\Box^3)$ terms.
  Whether the absence of a quartic graviton dispersion survives their inclusion is not addressed here.

## Interpretive status

In its transverse-traceless sector, the posited kernel resembles quadratic gravity. It is tempting to read that
resemblance as support for the spectral construction; the reading is available but weak, since any construction
generating $C^2$ and $R^2$ sectors would resemble it equally well — and the resemblance is established here only
for one helicity-2 pole, not for the full mode content. The defensible statement is narrower: the posited kernel
is compatible with the known infrared structure and predicts nothing beyond it that is presently observable.

What this note contributes is a **boundary**. Several inputs are missing before gravitational waves can test this
framework at all, and they are **not interchangeable**:

1. a Lorentzian construction from which the kernel actually follows, rather than being posited;
2. a renormalization condition fixing $m_2^2$;
3. the coupling of that mode to a detector, and its excitation in a source;
4. a treatment of the scalar and vector sectors sufficient to settle the mode content.

Naming them is what makes them addressable, and none of them is supplied here.

## Keywords

Quadratic gravity, graviton dispersion, four-derivative truncation, pole structure, ghost residue, renormalization
matching, heat-kernel expansion, effective field theory

## Repository Contents
```
lorentz-paper/
├── out/          # Compiled PDF (generated by compile.sh, git-ignored)
├── tex/          # LaTeX sources and bibliography
├── compile.sh    # pdflatex -> bibtex -> pdflatex x2
└── README.md
```

## Links

- 🌐 Website: [cosmochrony.org](https://cosmochrony.org)
- 🔗 DOI: [10.5281/zenodo.18826644](https://doi.org/10.5281/zenodo.18826644)

## Citation

If you reference this work, please cite:

> J. Beau, *No Quartic Graviton Dispersion from the Local Covariant Four-Derivative Truncation*, 2026.
> [doi:10.5281/zenodo.18826644](https://doi.org/10.5281/zenodo.18826644)

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with
large language models used as analytical assistants for exploring alternative
formulations and checking internal consistency.  
All claims, derivations, and interpretations remain the sole responsibility
of the author.

## Contributions

This repository is intended as a research reference.

Critical feedback, independent analyses, and phenomenological scrutiny are welcome.
Please open an issue to discuss the direct-sum decomposition, the matching conditions fixing
$c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}$, the $R^2$ sector and its mode content,
or the closed-time-path construction.
