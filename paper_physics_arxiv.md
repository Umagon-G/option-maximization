# Option maximization across scales: evolvability, the arrow of time, and a refuted solenoid prediction for quantum-gravity dimensional reduction

**Author**: Akito Shiraishi
**Draft**: arXiv physics version, EN v0.1 (2026-06-03). Target: gr-qc / physics.gen-ph (perspective). Companion philosophy version on PhilArchive.
**Stance**: A unifying perspective with a deliberately three-layer honesty structure: established results, an observationally decidable point, and an openly metaphysical organizing idea. Predictions are stated with their refutations included.

---

## Abstract

We present a unifying perspective in which a single control quantity—the number of future reachable states, or "option quantity" $\Omega$—organizes several established results across scales. (i) **Established**: in fluctuating environments the optimal evolvability rises with environmental volatility (Ishii et al. 1989), and a population's relative entropy to its stationary distribution contracts monotonically (a numerically verified arrow of time, max per-step increase $\sim10^{-16}$); a diffusion H-theorem yields an exact law for complexity-growth rate $\propto e^{-2H_{\rm init}}$ (numerically, slope $-1.978$ vs predicted $-2$). (ii) **Geometric**: across scales, integrable dynamics live on invariant tori (KAM; electron and planetary orbits), and an infinite nesting of tori is a Smale–Williams solenoid with Čech invariant $\check H^1=\mathbb Z[1/k]$. (iii) **Observable**: the cosmological reach is confined to the empirically decidable question of cosmic topology (is the spatial topology a 3-torus?). We then state, test, and **refute** a sharp prediction—that a solenoid's spectral dimension runs to 2 at small scales, matching quantum-gravity dimensional reduction—reporting the negative numerical result honestly so that specialists can carry out the rigorous calculation. The contribution is not a new quantitative law (the central monotonicity is due to Ishii 1989) but an integrative frame with an explicit observational hook and a fully disclosed failed prediction.

---

## 1. Introduction

The second law predicts decay of order, yet complexity grows (life, cognition). Several principles each capture a fragment—maximum entropy production (Dewar 2003), dissipative adaptation (England 2013; bound refuted by Kolchinsky 2024), causal entropic forces (Wissner-Gross & Freer 2013), Wagner's evolvability (2008). We organize them by **option maximization**: selection toward maximizing future reachable states $\Omega$, controlled by environmental volatility $\nu$ via a time horizon $\tau$. We are explicit about what is established, what is observationally decidable, and what is metaphysical—and we include a refuted prediction rather than hiding it.

## 2. Established layer

**2.1 Evolvability vs volatility.** Let the long-term growth rate (geometric-mean log-fitness / dominant Lyapunov exponent) be
$$\Lambda(\mu,\nu)=\lim_{T\to\infty}\tfrac1T\sum_{t=1}^T\log\Big[\sum_x f(x,e_t)p_t(x)\Big],$$
maximized over evolvability $\mu$. Ishii–Matsuda–Iwasa–Sasaki (1989) solved $\mu^*\approx\nu$ in the strong-selection limit. A toy model ($K=11$ phenotypes, Gaussian fitness, jump environment) reproduces monotone $\mu^*(\nu)$ with scaling exponent $\beta=1$ (prefactor model-dependent). *We note honestly that a "three-phase law" we initially conjectured (efficiency/option/saturation phases) was found to be a grid/threshold artifact under refinement and is withdrawn.*

**2.2 Arrow of time (numerically verified).** Under a fixed environment, the selection–mutation operator has a unique stationary $p^*$ (Perron–Frobenius); the relative entropy $D(p_t\|p^*)$ decreases monotonically to zero for all tested $(\mu,\sigma)$, maximum per-step *increase* $\sim10^{-16}$ (numerical noise). The selection-inclusive nonlinear dynamics preserves the contraction. *We retract an earlier claim that a fluctuation-theorem symmetry unifies growth rate and arrow: replicator dynamics is time-irreversible, so the Crooks-type symmetry is not expected; the arrow rests on relative-entropy contraction, the large-deviation principle (numerically convex SCGF) on growth-rate fluctuations—two distinct statements.*

**2.3 Past Hypothesis, conditional law.** For pure diffusion $\partial_t p=D\partial_x^2 p$, $dH/dt=D\,I_{\rm Fisher}[p]\ge0$ (de Bruijn). The Gaussian solution gives $dH/dt|_0=D/\sigma_0^2\propto e^{-2H_{\rm init}}$. Numerically the slope of $\log(dH/dt|_0)$ vs $H_{\rm init}$ is $-1.978$ (predicted $-2$). This is a conditional statement (given a low-entropy initial state); it does **not** explain why that state obtained (initial-condition problem). Penrose's conformal cyclic cosmology offers a cyclic closure (aeons supply the next low-entropy state), but CCC is itself contested.

## 3. Geometric layer: tori across scales

Integrable Hamiltonian systems live on invariant tori (Liouville–Arnold; KAM under perturbation). Hydrogen (Kepler) and planets alike: **micro and macro share the same invariant-torus structure**. Bohr–Sommerfeld quantization $\oint_{\gamma_i}p\,dq=n_ih$ is action quantization on torus cycles. The "stage-4" experience of pervasive access corresponds to irrational-winding dense orbits (Weyl equidistribution). An infinite nesting "torus within torus" is precisely the **Smale–Williams solenoid** $\Sigma_k=\varprojlim(T^n\xleftarrow{\times k}T^n)$, locally Cantor$\times$interval, with $\check H^1(\Sigma_k)=\mathbb Z[1/k]$ distinguishing it from a manifold torus.

## 4. Observable layer: cosmic topology

The only empirically decidable cosmological claim is whether the spatial topology is non-trivial (e.g. 3-torus): a multiply connected universe imprints "circles in the sky" (matched circle pairs) on the CMB. Planck shows no clear pairs (shortest loop $>98.5\%$ of the last-scattering diameter), but 2024 analyses (COMPACT collaboration; arXiv:2403.09221) report weak hints of non-trivial topology. This is the single point where the framework touches falsifiable observation.

## 5. A sharp prediction—and its refutation

**Prediction (stated, then tested).** Quantum gravity (causal sets, CDT, asymptotic safety, Hořava–Lifshitz, spin foams) near-universally predicts a running spectral dimension $d_s:4\to2$ toward the Planck scale—spacetime becomes non-manifold/fractal, so the "smooth-manifold" premise that excludes solenoids breaks. We therefore predicted: *spacetime has solenoidal structure at the Planck scale, with $d_s\to2$ at small scales.*

**Test (numerical).** We computed $d_s(t)=-2\,d\log P/d\log t$ from the heat trace of a discrete Smale–Williams solenoid (twisted circle bundle, graph Laplacian). Result: $d_s\to0$ at small scales (k=2: 0.36, k=3: 0.48), $d_s\to1$ at large scales (circle dominates), with a mid-scale peak ($d_s\approx2.05$ at k=3).

**Refutation.** The small-scale behavior ($d_s\to0$) is **opposite** to the quantum-gravity prediction ($d_s\to2$). The mid-scale $d_s\approx2$ is at the wrong location and is not claimed as a match. **The prediction is not supported by this calculation.** The discrete model is coarse (last-digit diffusion; higher hierarchy only via monodromy), so a rigorous solenoid heat-kernel could differ—but the present result is negative. We report it in full and invite specialists to perform the rigorous computation. *(This is the honesty the three-layer structure demands: a stated, tested, refuted prediction, disclosed rather than buried.)*

## 6. Discussion: three-layer honesty

- **Established** (§2–3): evolvability, arrow of time, Past-Hypothesis conditional law, KAM tori—standard or numerically verified.
- **Observable** (§4): cosmic topology—decidable by future CMB analysis.
- **Metaphysical/refuted** (§5 and the companion OMCC perspective): the option-maximizing co-constitution organizing idea is evaluated by unifying economy, not truth; the solenoid–spacetime prediction is refuted as stated.

The contribution is **integrative**: a single $\Omega$-maximization lens, with $\tau$ interpolating dissipation ($\tau\to0$) and option ($\tau>0$) regimes, containing MEP/England/Wagner/causal-entropic-force as limits. We claim no new quantitative law; the value is the unifying frame plus an explicit observational hook (§4) and disclosed failure (§5).

## 7. Conclusion

Option maximization organizes evolvability, the arrow of time, and a cross-scale torus geometry into one perspective, touches falsifiable observation at cosmic topology, and—tested honestly—does **not** support a solenoid model of Planck-scale spacetime. We publish the frame, the observational hook, and the refuted prediction together, inviting external verification and the rigorous solenoid spectral-dimension computation we could not complete.

## References
Ishii, Matsuda, Iwasa & Sasaki (1989) *Genetics* 121:163; Wagner (2008) *Proc. R. Soc. B*; Wissner-Gross & Freer (2013) *PRL* 110:168702; Dewar (2003) *J. Phys. A*; England (2013) *J. Chem. Phys.*; Kolchinsky (2024) arXiv:2404.01130; de Bruijn / Carroll–Chen (2004); Penrose (2010) *Cycles of Time*; Arnold, *Mathematical Methods of Classical Mechanics*; Smale (1967) *Bull. AMS*; Williams (1974); COMPACT collaboration, arXiv:2210.11426, 2403.09221; Ambjørn–Jurkiewicz–Loll (CDT); Reuter (asymptotic safety); companion: OMCC philosophy version (PhilArchive).
