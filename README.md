This repository contains the source of the  
[paper on causal propagation and gravitational waves from projective spectral dynamics](pdf/Lorentz.pdf)  
(paper III de gravity / Lorentzian completion of the spectral entropy framework).

This work develops the **Lorentzian and causal completion** of the spectral entropy
program, extending the elliptic (Riemannian) formulation in which the renormalized
variation of

$S_\Pi[g] = \tfrac12 \log \det{}' A_g$

yields an infrared Einstein response.

Starting from the hyperbolic operator $D_g$ and defining the Lorentzian spectral action

$S_\Pi^{(L)}[g] = \tfrac12 \,\mathrm{Re}\,\log \det{}' D_g$,

we construct a **causal and retarded quadratic kernel** via a
Schwinger–Keldysh prescription. The inverse operator entering the second variation
is the retarded Green operator $G_R$, ensuring physical propagation.

We then show that:

- in the regime $R \ell_\chi^2 \ll 1$ and $\omega \ll \ell_\chi^{-1}$,
  the theory propagates exactly **two transverse-traceless tensor modes**
  of helicity $\pm 2$,
- scalar and vector sectors remain non-dynamical in the infrared,
- higher-derivative corrections generate an additional pole at
  $k^2 \sim \ell_\chi^{-2}$, beyond current observational reach,
- the polarization content therefore coincides with that of general relativity
  in the accessible domain.

Beyond the Einstein sector, the ratio of Seeley–DeWitt coefficients fixes a universal
$k^4$ correction to the dispersion relation:

$\omega^2 = c^2 k^2 - \gamma \ell_\chi^2 k^4 + O(k^6),$

with $\gamma = 1/(180\zeta)$ and $\zeta = O(1)$ encoding scheme-dependent
normalization factors. In the natural spectral scheme one finds $\gamma = 1/30$.

This structure maps directly onto the parametrizations used in gravitational-wave
catalogues and yields a bound on the pre-geometric scale $\ell_\chi$
from interferometric data.

## Conceptual Overview

The paper proceeds in four logical steps:

1. **Lorentzian completion of the spectral entropy functional**  
   The elliptic operator $A_g$ is embedded into a normally hyperbolic operator
   $D_g$ whose spatial restriction reproduces $A_g$.
   The action is defined through the real part of the hyperbolic determinant,
   ensuring causality and retarded propagation.

2. **Second variation and quadratic operator**  
   The quadratic kernel obtained from $\delta^2 S_\Pi^{(L)}$
   has the schematic structure

   $O = c_{EH}\Box + \beta \Box^2 + \text{(non-local terms)} + O(R\ell_\chi^2).$

   In the infrared regime, the Einstein kinetic term dominates.

3. **Infrared propagation theorem**  
   Linearization about Minkowski spacetime shows that:
    - exactly two transverse-traceless tensor modes propagate,
    - scalar and vector sectors remain constrained,
    - the additional higher-derivative pole lies at
      $k^2 \sim \ell_\chi^{-2}$ and decouples for
      $\omega \ll \ell_\chi^{-1}$.

4. **Modified dispersion and observational mapping**  
   The Weyl-squared contribution fixed by the $a_4$ Seeley–DeWitt coefficient
   induces a modified dispersion relation of the form

   $\omega^2 = c^2 k^2 - \gamma \ell_\chi^2 k^4 + O(k^6).$

   Comparison with LVK gravitational-wave parametrizations
   constrains the pre-geometric scale $\ell_\chi$.

## Core Claims

The paper establishes the following statements:

1. **Causal completion is consistent and well-defined**  
   The Lorentzian spectral action admits a real and retarded quadratic kernel.

2. **Infrared polarization content matches general relativity**  
   Only two helicity-$\pm2$ tensor modes propagate below the spectral cutoff.

3. **Higher-derivative modes are ultraviolet**  
   The additional pole appears at $k^2 \sim \ell_\chi^{-2}$ and is
   suppressed in the observational domain.

4. **Modified dispersion is spectrally fixed**  
   The $k^4$ correction coefficient is determined by the ratio of
   Seeley–DeWitt coefficients, not by an arbitrary parameter.

5. **Gravitational waves probe the pre-geometric scale**  
   Interferometric bounds translate directly into constraints on $\ell_\chi$.

## What This Paper Does Not Assume

To avoid conflating dynamical and structural claims, the paper does not assume:

- fundamental gravitational dynamics beyond the spectral entropy functional,
- additional propagating scalar or vector degrees of freedom,
- Lorentz violation at leading order,
- arbitrary higher-derivative coefficients,
- ad hoc dispersion modifications.

All corrections arise from the spectral heat-kernel hierarchy.

## Keywords

Spectral geometry, Lorentzian completion, gravitational waves,
causal propagation, modified dispersion relation, effective field theory,
Seeley–DeWitt coefficients, emergent gravity, hyperbolic operators

## Repository Contents
```
paper/
├── pdf/ # Compiled paper PDF
├── tex/ # LaTeX sources
└── README.md
```

## Links

- 📄 [Paper PDF](https://github.com/Cosmochrony/lorentz-paper/blob/main/pdf/Lorentz.pdf)
- 🌐 Website: [cosmochrony.org](https://cosmochrony.org)

## Citation

If you reference this work, please cite:

> J. Beau, *Causal Propagation and Gravitational Waves from Projective Spectral Dynamics*, 2026.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with
large language models used as analytical assistants for exploring alternative
formulations and checking internal consistency.  
All claims, derivations, and interpretations remain the sole responsibility
of the author.

## Contributions

This repository is intended as a research reference.

Critical feedback, independent analyses, phenomenological scrutiny,
and confrontation with observational data are welcome.
Please open an issue to discuss dispersion parametrizations,
normalization schemes, or infrared consistency conditions.
