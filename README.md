This repository contains the source of **No Quartic Graviton Dispersion from the Covariant Spectral
Operator** (paper III of gravity / Lorentzian completion of the spectral entropy framework).

This is a **correction**. It determines the linearized infrared spectrum supported by the covariant spectral
operator, and establishes what does *not* follow from it. It is a negative result, and it withdraws the
gravitational-wave constraint claimed in the earlier treatment of this operator (see
[Withdrawn claims](#withdrawn-claims) below).

## What the operator supports

In the transverse-traceless sector the quadratic operator factorizes **exactly**:

$$\mathcal{O}_{\mathrm{TT}} = c_{\mathrm{EH}}\Box + \beta\Box^2
= c_{\mathrm{EH}}\Box\left(1 + \frac{\beta}{c_{\mathrm{EH}}}\Box\right).$$

Because this is a product of two commuting factors, its kernel is the **union of the kernels of the factors** —
there is no third branch, and in particular no branch obtained by expanding the bracket in powers of $k$. Every
solution of $\mathcal{O}_{\mathrm{TT}} h^{\mathrm{TT}} = 0$ satisfies exactly one of:

- **(a) the massless branch**, $\Box h^{\mathrm{TT}} = 0$, a graviton of helicity $\pm 2$ whose dispersion is
  $\omega^2 = c^2 k^2$ **exactly**, with no correction at any order in $k$;
- **(b) a massive branch**, $\Box h^{\mathrm{TT}} = -\dfrac{c_{\mathrm{EH}}}{\beta}\, h^{\mathrm{TT}}$, a pole at
  $k^2 = c_{\mathrm{EH}}/\beta$.

**Neither branch carries a quartic correction to the massless dispersion.** The massless factor is undeformed, and
the second factor is a distinct pole rather than a correction to the first. The massless front is **luminal**, not
subluminal.

This is the standard spectrum of quadratic gravity — a massless graviton together with additional massive degrees of
freedom (Stelle 1977; Calmet–Capozziello–Pryer 2017). The covariant spectral operator reproduces a known structure
rather than predicting a new one.

## No gravitational-wave bound follows

Gravitational-wave catalogues constrain modified dispersion relations of the form $\omega^2 = c^2k^2 + A_4 k^4$ on
the propagating graviton. Such a constraint applies to a branch carrying a quartic deformation of the massless
dispersion. The present operator has no such branch.

There is therefore **no mapping onto the $A_4$ parametrization, no induced value of $A_4$, and no bound on the
pre-geometric scale $\ell_\chi$ from interferometric data.** The luminal propagation is consistent with the observed
coincidence of gravitational and electromagnetic arrival times, but that consistency is shared with general
relativity and carries no information about $\ell_\chi$.

## Matching data, not predictions

The renormalized coefficients $c_{\mathrm{EH}}^{\mathrm{ren}}$ and $\beta^{\mathrm{ren}}$ — and hence the mass scale
of the non-massless poles, set by their ratio — are **matching data**. They are fixed by a renormalization condition
together with the complete operator content; they are not predicted by the minimal determinant, and the pole scale is
**not derivably tied to $\ell_\chi$**. No identification of the renormalization scale with a cutoff supplies them:
the power-sensitive and the finite/logarithmic statements belong to different schemes and are not interchangeable.

The mode content is likewise not fixed. The minimal $a_4$ carries an $R^2$ sector alongside $C^2$, which generically
supports a **massive scalar mode** in addition to the massive spin-2 one. Excluding it requires a matching condition
on the $R^2$ coefficient that the minimal determinant does not supply.

## The causal construction is an open programme

The Lorentzian action $S_\Pi^{(L)}[g] = \tfrac12\,\mathrm{Re}\,\log\det{}'\mathcal{D}_g$, with the retarded Green
operator $G_R$ entering the second variation, is a **working definition, not a derivation**. A Schwinger–Keldysh
in-in effective action is built from doubled field configurations on a closed time path, with the two branches
coupled by the boundary condition at the turning point (Jordan 1986; Calzetta–Hu 2008). Substituting $G_R$ for
$A^{-1}$ in an ordinary single-field Hessian is not equivalent to that construction and does not follow from it.

## What is retained, conditionally

- The exact factorization of the transverse-traceless operator.
- The massless helicity-$\pm 2$ branch with luminal dispersion.
- The existence of a massive pole whose scale is a matching datum.
- The **elliptic gravitomagnetic constraint** of the sourced vector sector, conditional on the projected matter
  current $T^{(\Pi)}_{0i}$. Once that current is supplied, the vector sector fixes the frame-dragging potential
  $g_{0i}$ as in linearized general relativity; the gap sits entirely upstream. Retaining the subleading
  $\beta\Box^2$ operator gives a short-range correction of range
  $\sim\sqrt{|\beta^{\mathrm{ren}}/c_{\mathrm{EH}}^{\mathrm{ren}}|}$ — a matching datum, **not** $\ell_\chi$.

## Withdrawn claims

An earlier treatment of this operator read the factorized quadratic form as a single perturbed branch and expanded
it in $k$, obtaining a quartic correction to the graviton dispersion. That step is not licensed by the operator: a
product of commuting factors has no branch other than the zero sets of its factors, and the massless factor is
undeformed. The same treatment fixed the Einstein prefactor by identifying the renormalization scale with the
cutoff and reading a coefficient off $a_2$, which conflates two regularization schemes and assigns a derived value
to a quantity that a renormalization condition must supply.

The following claims are withdrawn:

1. that the covariant spectral operator generates a dispersion relation
   $\omega^2 = c^2 k^2 - \gamma\,\ell_\chi^2 k^4 + \mathcal{O}(k^6)$ on the graviton branch;
2. that the ratio of Seeley–DeWitt coefficients fixes a universal value $\gamma = 1/(180\zeta)$, and
   $\gamma = 1/30$ in a "natural spectral scheme";
3. that this structure maps onto the $A_4$ parametrization of gravitational-wave catalogues and yields a bound
   $\ell_\chi \lesssim \sqrt{180\,\zeta\,A_4^{\mathrm{obs}}}$;
4. that gravitational-wave propagation is subluminal in this framework;
5. that the scalar sector is non-dynamical in the infrared;
6. that the non-massless pole lies at $k^2 \sim \ell_\chi^{-2}$ as a consequence of the construction;
7. that the real part of the hyperbolic determinant is equivalent to a Schwinger–Keldysh prescription.

## Interpretive status

What the covariant spectral operator supports in the infrared is a known structure, not a new observable. Reading
the appearance of the standard quadratic-gravity spectrum as evidence for the spectral substrate is a weak reading:
reproducing a known structure is a consistency check, and any construction generating an $R^2$ and $C^2$ sector
would pass it. The defensible statement is narrower — the covariant spectral operator is compatible with the known
infrared spectrum, and predicts nothing beyond it that is presently observable.

The value of this result is **diagnostic**. Two independent inputs are missing before gravitational waves can probe
this framework at all:

1. a condition fixing $c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}$, which sets the mass of the
   non-massless pole;
2. an observable sensitive to a massive pole rather than to a deformed massless dispersion — the catalogue
   parametrization is not of that type, and the $R^2$ sector must be settled before the mode content is even known.

Until both are supplied, this framework makes no gravitational-wave prediction. Naming these inputs precisely is
what makes them addressable, and is what this paper contributes in place of the constraint it withdraws.

## Keywords

Spectral geometry, emergent gravity, Lorentzian geometry, quadratic gravity, graviton dispersion, pole structure,
renormalization matching, heat-kernel expansion, Seeley–DeWitt coefficients, closed time path

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

> J. Beau, *No Quartic Graviton Dispersion from the Covariant Spectral Operator*, 2026.
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
Please open an issue to discuss the factorization, the matching conditions fixing
$c_{\mathrm{EH}}^{\mathrm{ren}}/\beta^{\mathrm{ren}}$, the $R^2$ sector and its mode content,
or the closed-time-path construction.
