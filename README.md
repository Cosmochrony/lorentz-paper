This repository contains the source of **No Quartic Graviton Dispersion from the Local Covariant Four-Derivative
Truncation** (paper III of gravity / Lorentzian completion of the spectral entropy framework).

This note settles one question about the local covariant four-derivative truncation of the projective spectral
action: whether it deforms the dispersion of the graviton. It does not. This is a negative result about a
truncation, and its scope is exactly that.

## The operator considered

The projective spectral action assigns to a metric the renormalized functional
$S_\Pi[g] = \tfrac12\log\det{}'A_g$. Its metric variation carries a local Einstein term together with
higher-derivative local terms, non-local form factors, and contributions of higher order in $\Box$.

The object studied here is a **truncation** of that structure, and the truncation is an assumption, not a result.
Linearizing about Minkowski spacetime, restricting to the transverse-traceless sector, retaining the local terms
of the quadratic form up to four derivatives, and **discarding the non-local form factors and all terms of order
$\Box^3$ and higher** leaves

$$\mathcal{O}_{\mathrm{TT}} = c_{\mathrm{EH}}\Box + \beta\Box^2 ,$$

with $c_{\mathrm{EH}}$ and $\beta$ constants. Every statement below is a statement about this truncated operator.
None of them is a statement about the full renormalized kernel, and the difference matters wherever the discarded
terms are not negligible — in particular in the ultraviolet.

## Solution structure: a direct sum

Write $P = \Box$ and $Q = c_{\mathrm{EH}} + \beta\Box$, so that $\mathcal{O}_{\mathrm{TT}} = PQ = QP$. For
$c_{\mathrm{EH}} \neq 0$ the two factors are **coprime**, by the Bézout identity

$$Q - \beta P = c_{\mathrm{EH}} ,$$

a nonzero constant. The solution space is then the **direct sum**

$$\ker\mathcal{O}_{\mathrm{TT}} = \ker\Box \,\oplus\, \ker(c_{\mathrm{EH}} + \beta\Box) ,$$

and the decomposition of any $h^{\mathrm{TT}} \in \ker\mathcal{O}_{\mathrm{TT}}$ is unique:
$h^{\mathrm{TT}} = h_0 + h_m$ with $\Box h_0 = 0$ and $\Box h_m = -(c_{\mathrm{EH}}/\beta)\,h_m$.

The kernel is **strictly larger** than the set of solutions of the individual factor equations. Given nonzero
$h_0 \in \ker P$ and $h_m \in \ker Q$, the sum $h_0 + h_m$ solves
$\mathcal{O}_{\mathrm{TT}} h^{\mathrm{TT}} = 0$ while satisfying **neither** factor equation:
$\Box(h_0+h_m) = -(c_{\mathrm{EH}}/\beta)h_m \neq 0$ and
$(c_{\mathrm{EH}} + \beta\Box)(h_0+h_m) = c_{\mathrm{EH}} h_0 \neq 0$. A generic solution is a superposition of
the two sectors, not a member of one of them.

**Degenerate case.** If $c_{\mathrm{EH}} = 0$ the Bézout identity fails and the decomposition is unavailable:
$\mathcal{O}_{\mathrm{TT}} = \beta\Box^2$, and $\ker\Box^2$ contains generalized solutions annihilated by
$\Box^2$ but not by $\Box$.

## Absence of a quartic graviton dispersion

For $c_{\mathrm{EH}} \neq 0$ the massless summand lies in $\ker\Box$ by construction, and $\ker\Box$ does not
depend on $\beta$. Hence for plane waves $h_0 \sim e^{ik\cdot x}$,

$$\omega^2 = c^2 k^2 ,$$

**with no correction at any order in $k$**.

A relation $\omega^2 = c^2k^2 - \gamma\,\ell_\chi^2 k^4 + \mathcal{O}(k^6)$ describes a single branch whose
massless dispersion is deformed at quartic order. The truncation has no such branch. Expanding
$(1 + (\beta/c_{\mathrm{EH}})\Box)^{-1}$ in powers of $\Box$ rearranges the residues of the propagator; it does
not move the zero of $\Box$, which is where the massless pole sits. A quartic coefficient obtained that way is an
artefact of treating a two-pole propagator as one deformed pole.

Gravitational-wave catalogues constrain $\omega^2 = c^2k^2 + A_4 k^4$ on the propagating graviton. The truncation
induces no such $A_4$. There is consequently **no mapping of this construction onto that parametrization, and no
bound on the pre-geometric scale $\ell_\chi$ from interferometric dispersion data**.

**No front-velocity claim.** $\omega^2 = c^2k^2$ is a statement about the truncation, not about signal fronts. A
front velocity is governed by the large-$k$ behaviour of the full kernel, precisely where the discarded non-local
and $\mathcal{O}(\Box^3)$ terms are not negligible. No statement about front propagation is made here, in either
direction.

## Pole content

Writing $z$ for the momentum-space image of $\Box$, the transverse-traceless propagator is, for
$c_{\mathrm{EH}} \neq 0$,

$$\frac{1}{z(c_{\mathrm{EH}} + \beta z)}
= \frac{1}{c_{\mathrm{EH}}}\left( \frac{1}{z} - \frac{1}{z + c_{\mathrm{EH}}/\beta} \right).$$

Two facts follow, and they are **independent of one another**:

1. **Ghost character.** The two residues have opposite signs, whatever the signs of $c_{\mathrm{EH}}$ and $\beta$.
   The second pole is therefore a ghost relative to the massless one. This does **not** depend on
   $c_{\mathrm{EH}}/\beta$.
2. **Tachyonic character.** The second pole sits at $z = -c_{\mathrm{EH}}/\beta$, so the sign of
   $c_{\mathrm{EH}}/\beta$ fixes the sign of the corresponding mass squared, and with it whether the mode is
   tachyonic. This is a separate question from (1) and has a separate answer.

This is the standard pole content of quadratic gravity — a massless graviton accompanied by a massive spin-2 ghost
(Stelle 1977; Calmet–Capozziello–Pryer 2017). The truncation reproduces a known structure.

**The scalar sector is not settled.** The minimal $a_4$ carries an $R^2$ sector alongside $C^2$. In the effective
action at second order in curvature this generically supports a massive scalar in addition to the massive spin-2
mode. Excluding it requires a matching condition on the $R^2$ coefficient, so the mode content of the truncation
is not fully determined here.

## What is matching data

The Seeley–DeWitt coefficient $a_4$ controls a **logarithmic contribution to the running** of the four-derivative
couplings. It does not fix the finite value of $\beta^{\mathrm{ren}}$, which depends in addition on the overall
normalization and sign of the determinant and on the renormalization prescription. An identification
$\beta = -2\alpha_C$ read off the Weyl-squared part of $a_4$ omits all three, and is not a determination of
$\beta^{\mathrm{ren}}$.

The same holds for $c_{\mathrm{EH}}^{\mathrm{ren}}$: its finite value and sign are fixed by a renormalization
condition together with the complete operator content. Consequently the pole mass
$c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}$ is a **matching datum, not derivably tied to $\ell_\chi$**.

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

The truncation lands on the known pole content of quadratic gravity. It is tempting to read that agreement as
support for the spectral construction; the reading is available but weak, since any construction generating $C^2$
and $R^2$ sectors would agree equally well. The defensible statement is narrower: the truncation is compatible
with the known infrared structure and predicts nothing beyond it that is presently observable.

What this note contributes is a **boundary**. It removes a putative interferometric handle on the pre-geometric
scale and isolates what a genuine one would require — two inputs that must be supplied before gravitational waves
can test this framework at all:

1. a condition fixing the pole mass $c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}$;
2. an observable sensitive to a **massive companion** rather than to a deformed massless branch — the catalogue
   parametrization is not of that type, and the $R^2$ sector must be settled before the mode content is even known.

Naming them precisely is what makes them addressable.

## Keywords

Quadratic gravity, graviton dispersion, four-derivative truncation, pole structure, ghost residue, renormalization
matching, heat-kernel expansion, effective field theory

## Repository Contents
```
paper/
├── pdf/ # Compiled paper PDF
├── tex/ # LaTeX sources
└── README.md
```

## Links

- 📄 [Paper PDF](https://github.com/Cosmochrony/lorentz-paper/blob/main/out/Lorentz.pdf)
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
