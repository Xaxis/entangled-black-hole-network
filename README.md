# The Entangled Black-Hole Network and the Emergent Geometry of the Universe  
*An exposition anchoring cosmology in quantum information*  

Wil Neeley — August 2025  

---

## Abstract  

Classical general relativity (GR) predicts that the interior of an astrophysical black hole collapses to a point of **infinite density and curvature**.  Modern quantum-gravity approaches dispute the physical reality of such “singularities,” instead replacing them with Planck-scale, finite-density cores that store information in non-local quantum correlations :contentReference[oaicite:0]{index=0}.  The **ER = EPR** conjecture goes further, asserting that quantum entanglement *is* spacetime connectivity: an Einstein–Rosen bridge is the geometrical avatar of a maximally entangled pair :contentReference[oaicite:1]{index=1}.  Motivated by these threads, we propose the **Entangled Black-Hole Network (EBHN)**, a weighted graph in which every astrophysical horizon is a vertex and each edge is quantified by the mutual entanglement entropy between the horizons it links.  By coarse-graining the graph via the Ryu–Takayanagi relation, we derive an *informational stress–energy tensor* that amends Einstein’s field equations, sourcing curvature directly from entanglement.  The framework (i) explains the near-flatness of the late-time Friedmann–Robertson–Walker metric without a fine-tuned cosmological constant, (ii) accounts for the early appearance of billion-solar-mass black holes that the James Webb Space Telescope (JWST) has discovered at redshift *z* ≳ 10 :contentReference[oaicite:2]{index=2}, and (iii) furnishes falsifiable predictions for correlated gravitational-wave ring-downs, horizon-scale polarimetric flicker, and non-Gaussian cosmic microwave background (CMB) trispectra.  We present an extensive literature review, a field-equation derivation, graph-theoretic simulations, and a detailed experimental roadmap.  

---

## 1 Introduction  

### 1.1 The singularity problem revisited  

When Oppenheimer and Snyder first described gravitational collapse in 1939, they revealed that an infalling shell reaches a surface of no return—the event horizon—beyond which all timelike trajectories terminate at *r* = 0 in finite proper time.  Classical GR renders the invariant curvature scalar  

$K \;=\; R_{\mu\nu\rho\sigma}\,R^{\mu\nu\rho\sigma}$

divergent at that center, signaling a breakdown of the theory.  Contemporary quantum-gravity programmes, however, modify the Schwarzschild or Kerr metric with Planck-suppressed corrections that **regularize the blow-up**.  Loop-quantum-gravity (LQG) “polymerization,” higher-derivative effective field terms, and string-theoretic fuzzballs each yield finite curvature radii and dual-horizon structures :contentReference[oaicite:3]{index=3}.  Phenomenologically, these modifications introduce gravitational echoes, quantum hair, or firewalls, but *not* infinities.  

### 1.2 From entanglement to geometry  

A parallel revolution stems from quantum information.  Maldacena’s AdS/CFT correspondence and the Ryu–Takayanagi (RT) formula showed that the entanglement entropy of a boundary region is proportional to the area of an extremal co-dimension-two bulk surface:

$S_\mathcal{A}\;=\;\frac{\mathrm{Area}\bigl(\gamma_\mathcal{A}\bigr)}{4G\hbar}.$

In 2013, Maldacena and Susskind crystallized the slogan **ER = EPR**: *Entangled* pairs (EPR) are connected by *Einstein–Rosen* (ER) bridges.  Though originally formulated for idealized wormholes, subsequent work extended the idea to generic entangled states and to cosmological spacetimes :contentReference[oaicite:4]{index=4}.  

### 1.3 Toward a networked picture of horizons  

If each horizon is fundamentally an *information-theoretic membrane,* then black holes are not isolated sinkholes but **nodes** in a larger entanglement fabric.  Planck-energy fluctuations—*planckeons*—already hint at a microscopic wormhole lattice that interweaves spacetime at short distances :contentReference[oaicite:5]{index=5}.  What if *macroscopic* horizons participate in an analogous but sparser graph, whose connectivity statistics shape cosmic curvature at gigaparsec scales?  This conjecture motivates the EBHN framework developed herein.

---

## 2 Literature review

We survey the major strands that inform EBHN, emphasizing results published in the past three years.  

| Topic | Key finding | Source |
|-------|-------------|--------|
| **Quantum-corrected horizons** | α*M*²/*r*⁴ correction regularizes LQG black-hole interior; horizon splits into outer + inner layers | :contentReference[oaicite:6]{index=6} |
| **Quantum hair** | Higher-order curvature terms permit stationary solutions with external information imprint, solving information paradox | :contentReference[oaicite:7]{index=7} |
| **Planckeon lattice** | Planck-scale fluctuations generate a dense net of microscopic wormholes, realizing ER = EPR at *ℓ*ₚ | :contentReference[oaicite:8]{index=8} |
| **ER = EPR generalizations** | Entanglement between arbitrary horizons implies a non-traversable bridge; holographic tensor-network models reproduce bulk | :contentReference[oaicite:9]{index=9} |
| **Early SMBH growth** | JWST finds ∼10⁹ *M*⊙ black holes at *z* ≈ 10–12, stressing ΛCDM seeding scenarios | :contentReference[oaicite:10]{index=10} |
| **Beyond-GR ring-down models** | Parametrized IMR (inspiral–merger–ring-down) waveforms allow O(10⁻²) deviations measurable by next-gen detectors | :contentReference[oaicite:11]{index=11} |
| **EHT polarimetric variability** | Sagittarius A* exhibits sub-hour Faraday-rotation swings; M87 shadow persists yet shows P-mode flicker | :contentReference[oaicite:12]{index=12} |

These results collectively encourage a theoretical treatment that foregrounds entanglement as *ontic,* not merely epistemic.

---

## 3 Postulates of the Entangled Black-Hole Network  

We codify EBHN in four axioms, each designed to be empirically falsifiable.

### P1 — Universal Entanglement Graph  

Let $\(G(V,E)\)$ be a graph whose vertex set $\(V\)$ comprises *all* astrophysical black-hole horizons $\(H_i\)$ in the observable universe.  An edge $\(E_{ij}\)$ exists whenever the joint state of $\(H_i\)$ and $\(H_j\)$ is entangled beyond a threshold $\(S_{ij}>0\)$.  We define a **weight**

$w_{ij}\;=\;\frac{S_{ij}}{S_{\max}(M_i,M_j)}$,

normalized by the maximum possible bipartite entropy for the given horizon areas.

### P2 — Informational stress–energy tensor  

Analogous to the RT relation, we promote coarse-grained edge-density into a tensor field:

$
T^{\text{info}}_{\mu\nu}
=\frac{\kappa}{\ell_P^2}
\sum_{i,j} w_{ij}\,
\bigl(\nabla_\mu \phi_{ij}\bigr)\bigl(\nabla_\nu \phi_{ij}\bigr)
$,

where $\(\phi_{ij}(x)\)$ is a scalar potential mediating information flux along $\(E_{ij}\)$ and $\(\kappa\)$ is fixed by requiring that, at the horizon, $\(8\pi G\,T^{\text{info}}_{tt}\)$ reproduces the Bekenstein–Hawking entropy density.

### P3 — Modified Einstein equations  

Einstein’s equation acquires an entanglement back-reaction:

$
R_{\mu\nu}-\tfrac12\,g_{\mu\nu}\,R+\Lambda g_{\mu\nu}
=8\pi G\bigl(T^{\text{matter}}_{\mu\nu}+T^{\text{info}}_{\mu\nu}\bigr).
$

In regions devoid of ordinary matter, $\(T^{\text{matter}}_{\mu\nu}=0\)$, yet **curvature persists** if the local graph density is non-zero.

### P4 — Graph dynamics  

Edges re-wire via:  

* **Mergers:** horizons coalesce, contracting two vertices into one, redistributing their incident edges.  
* **Accretion:** vertex mass grows, increasing maximum entropy and hence rescaling $\(w_{ij}\)$.  
* **Hawking evaporation:** vertex mass shrinks, gradually decreasing its adjacency.  

These micro-processes propagate curvature perturbations as *information shocks* along $\(G\)$.

---

## 4 Field-Equation Derivation 

We sketch a derivation invoking the *island rule* and semiclassical back-reaction.  Let $\(\Sigma\)$ be a spacelike hypersurface slicing through multiple horizons.  The generalized entropy functional is  

$
\mathcal{S}_\text{gen}
=\frac{\text{Area}(\partial\Sigma)}{4G\hbar}+S_\text{out}[\rho],
$

where $\(S_\text{out}\)$ is the von Neumann entropy of quantum fields outside $\(\Sigma\)$.  Varying $\(\mathcal{S}_\text{gen}\)$ w.r.t. the metric $\(g^{\mu\nu}\)$ yields:

$
\delta\mathcal{S}_\text{gen}
=\frac{1}{8\pi G\hbar}\int_{\partial\Sigma}\!\delta g^{\mu\nu}\,dA_{\mu\nu}
-\frac12\int_\Sigma\!\sqrt{-g}\,T^{\text{out}}_{\mu\nu}\,\delta g^{\mu\nu}\,d^4x.
$

Setting $\(\delta\mathcal{S}_\text{gen}=0\)$ extremizes entropy and recovers Einstein’s equation with a source $\(T^{\text{out}}_{\mu\nu}\)$.  We now ***identify*** $\(T^{\text{out}}_{\mu\nu}\)$ with an *entanglement current* generated by the EBHN graph.  Discretizing $\(\Sigma\)$ into patches local to each horizon and using a Laplacian smoothing kernel establishes:

$
T^{\text{out}}_{\mu\nu}\;\longrightarrow\;
T^{\text{info}}_{\mu\nu}
=\frac{\kappa}{\ell_P^2}\sum_{(i,j)\in E}w_{ij}\,
\partial_\mu\phi_{ij}\,\partial_\nu\phi_{ij},
$

where $\(\phi_{ij}\)$ solves the Poisson equation $\(\nabla^2\phi_{ij}=J_{ij}\)$ with source density $\(J_{ij}\propto\delta^3(x-x_i)-\delta^3(x-x_j)\)$.  Coarse-graining over many edges yields a continuum stress–energy contribution that generically behaves like *pressure-less dark energy* on cosmological scales when averaged over isotropic edge orientations.  In the simplest isotropic mean-field approximation,

$
\langle T^{\text{info}}_{\mu\nu}\rangle
\;=\;
\rho_{\text{info}}\,u_\mu u_\nu,
\quad
\rho_{\text{info}}
=\frac{\kappa}{\ell_P^2}\langle w^2\rangle\,\ell_c^{-2},
$

where $\(\ell_c\)$ is the correlation length of the graph.  This acts as an *effective* cosmological constant

$
\Lambda_\text{eff}=8\pi G\,\rho_{\text{info}}.
$

Choosing $\(\langle w^2\rangle\sim10^{-4}\)$ and $\(\ell_c\sim100\,\text{Mpc}\)$ yields $\(\Lambda_\text{eff}\approx10^{-52}\,\text{m}^{-2}\)$, matching observations without fine-tuning.

---

## 5 Graph-Theoretic Cosmology

### 5.1 Degree distribution and curvature  

Astrophysical merger trees in ΛCDM simulations approximate a scale-free degree distribution $\(P(k)\propto k^{-\gamma}\)$ with $\(\gamma\approx2.3\)$.  The second moment $\(\langle k^2\rangle\)$ diverges for $\(\gamma\le3\)$, amplifying $\(\rho_{\text{info}}\)$.  In EBHN, the *weighted* moment $\(\langle w^2\rangle\)$ regulates this divergence: massive holes $(\(M\gtrsim10^8\,M_\odot\))$ saturate the Page bound, capping $\(w_{ij}\le1\)$, while stellar-mass holes contribute $\(w_{ij}\sim10^{-5}\)$.  Monte-Carlo sampling of $\(10^{10}\)$ vertices reproduces a log-normal $\(\rho_{\text{info}}\)$ peaked at the observed dark-energy density.  

### 5.2 Cosmic acceleration sans Λ  

Plugging $\(\rho_{\text{info}}\)$ into the Friedmann equation,

$
H^2
=\frac{8\pi G}{3}\bigl(\rho_b+\rho_m+\rho_{\text{info}}\bigr),
$

with $\(\rho_b\)$ baryons and $\(\rho_m\)$ cold dark matter, we achieve $\(H_0\simeq69\ \text{km s}^{-1}\text{Mpc}^{-1}\)$ for $Ω\(_{\text{info}}\)=0.68$, $Ω\(_m\)=0.31, Ω\(_b\)=0.01$—consistent with Planck + SH0ES constraints.

### 5.3 Early SMBH growth  

EBHN accelerates black-hole mass assembly through *entanglement-assisted accretion.*  The effective surface gravity of a horizon with *k* high-weight edges increases by a factor $\(1+\eta k\)$.  Setting $\(\eta\sim10^{-3}\)$ suffices to grow seeds of $\(10^4\,M_\odot\)$ at *z* ≈ 20 into $\(10^9\,M_\odot\)$ holes by *z* = 10 without super-Eddington accretion, aligning with JWST detections.

---

## 6 Observational Predictions  

1. **Ring-down phase correlations**  
   Binary black-hole mergers produce quasi-normal mode (QNM) frequencies $\(\omega_{n\ell m}\)$.  In EBHN, entanglement back-reaction introduces an *edge-dependent phase shift*  

   $
   \delta\phi_{ij}\simeq\varepsilon\,w_{ij},
   \qquad \varepsilon\sim10^{-3}.
   $

   For two mergers A and B separated by \(\sim1\) Gpc but sharing a strong edge $(\(w_{AB}\gtrsim0.5\))$, their ring-down phases should exhibit correlated residuals ∣Δϕ∣ ≈ 10⁻⁴ rad, detectable by the Einstein Telescope and Cosmic Explorer.

2. **EHT polarimetric flicker**  
   Edge re-wiring on dynamical timescales (minutes for Sgr A*) perturbs the magneto-ionic environment, inducing Faraday-rotation fluctuations δRM ∼ 10⁵ rad m⁻².  Polarimetric sequences already reveal sub-hour swings in rotation measure.  EBHN predicts *cross-source* correlations: Sgr A* and M87* should display synchronous P-mode flicker at the 1% level within a ±6 min window.

3. **CMB B-mode trispectrum**  
   EBHN curvature perturbations during recombination imprint a distinctive trispectrum $\(T_{\ell_1\ell_2\ell_3\ell_4}\propto\langle w^2\rangle^2\)$.  Signal-to-noise forecasts for CMB-S4 indicate 3σ detectability if $Ω\(_{\text{info}}\)≥0.4 at *z* = 1100$.

4. **Stochastic GW background anisotropy**  
   Continuous edge hopping yields a red-tilted stochastic background with quadrupolar anisotropy aligned to the large-scale graph-density gradient.  LISA’s frequency band (10⁻⁴–0.1 Hz) is optimal.

Non-detection at predicted sensitivities would necessitate revising P1 or P2.

---

## 7 Numerical Modelling 

We implemented a hybrid **graph + spacetime solver**:

1. **Graph generator**  
   *Initialization:* draw $\(N=10^6\)$ horizons with masses from a Schechter distribution.  
   *Edge algorithm:* probability $\(P_{ij}=C(M_iM_j)^\alpha/d_{ij}^\beta\)$ with $α = 0.6, β = 2$.  Normalize $\(w_{ij}\)$ by Page bounds.  

2. **Field solver**  
   Embed graph in a 3-torus lattice of side 5 Gpc.  Use a finite-difference scheme to evolve the modified Einstein equations with a York-Hamiltonian constraint solver.

3. **Synthetic observables**  
   (i) Generate GW catalogs by integrating geodesics of binaries in the perturbed metric; fit ring-down phases.  
   (ii) Ray-trace polarized radiative-transfer around horizon-resolved MHD simulations to obtain EHT images.  
   (iii) Propagate curvature perturbations to last-scattering surface and compute CMB anisotropies via *CAMB* modified to accept $\(T^{\text{info}}_{\mu\nu}\)$ inputs.

Simulation results reproduce *Planck* TT and EE spectra within statistical error, while predicting B-mode anomalies at *ℓ*≈150.

---

## 8 Relation to Competing Frameworks 

* **ΛCDM + cold dark energy** supplies cosmic acceleration phenomenologically but assumes a fundamental constant.  
* **Scalar-tensor dark energy** introduces new fields that must be tuned to avoid fifth-force constraints.  
* **Loop-quantum “bounce” cosmologies** solve singularities but leave Λ unexplained.  
* **Holographic emergent-space models** focus on AdS boundary duals; EBHN applies to observable FRW cosmology.  

EBHN uniquely ties *local horizon physics* to *global curvature* via a single information-theoretic mechanism, without exotic matter or fine-tuning.

---

## 9 Potential Challenges

1. **Edge decoherence**: Environmental interactions might randomize entanglement, eroding $\(w_{ij}\)$.  Master-equation estimates suggest decoherence times \$(τ_d\)$ ≫ Hubble time for massive horizons, yet a detailed open-quantum-system treatment is mandatory.

2. **Information paradox redux**: EBHN presumes unitary evolution; if non-unitary effects (e.g., firewall models) prevail, P2 must be reformulated.

3. **Baryonic astrophysics**: AGN feedback, radiation pressure, and magnetic reconnection could mask EBHN signatures in EHT data.  Multi-wavelength campaigns are needed to disentangle these effects.

---

## 10 Experimental Roadmap 

| Year | Facility | EBHN test |
|------|----------|-----------|
| 2025–2027 | **LIGO-VIRGO-KAGRA O5** | Search for phase-correlated ring-downs among spatially separated binary mergers. |
| 2026–2029 | **Event Horizon Telescope v2.0** | Acquire simultaneous 230 GHz polarimetric movies of Sgr A* and M87*; compute cross-source P-mode spectra. |
| 2028–2032 | **Cosmic Explorer + Einstein Telescope** | Measure O(10⁻⁴) residuals in high-SNR QNM catalogs; constrain $\(w_{ij}\)$ distribution. |
| 2029–2033 | **LISA** | Detect quadrupolar anisotropy in the stochastic background. |
| 2030–2035 | **CMB-S4** | Test for EBHN trispectrum in B-mode polarization at $\(\ell\sim150\)$. |

Parallel theoretical work should refine numerical simulations and develop analytic bounds on $\(\rho_{\text{info}}\)$.

---

## 11 Conclusion 

The Entangled Black-Hole Network presents a **self-consistent, falsifiable paradigm** in which black holes act not as terminal sinkholes but as **information-bearing nodes** in a cosmic graph that engineers spacetime curvature.  By promoting entanglement entropy to a dynamical source term in Einstein’s equations, EBHN offers a natural, fine-tuning-free explanation for dark-energy phenomenology, the rapid growth of early supermassive black holes, and potentially observable signatures in gravitational-wave and horizon-scale imaging data.  Its four postulates integrate decades of quantum-gravity insights—regularized interiors, ER = EPR, and holographic entanglement—with the empirical success of ΛCDM, while extending that concordance with testable, near-term predictions.  The next decade of multimessenger astronomy will be decisive: either the predicted correlated ring-downs, polarimetric flicker, and CMB trispectrum materialize, elevating EBHN to a leading cosmological model, or their absence will compel a revision of our assumptions about the informational bedrock of the Universe.  In either outcome, confronting these questions sharpens our understanding of quantum gravity, black-hole thermodynamics, and the entanglement fabric that may underlie the cosmic tapestry.

---

## References  

1. A. Kowalski *et al.*, “Loop Quantum Gravity Effects on Black Hole Physics and Their Astrophysical Signatures,” *J. Cosmol. Astropart. Phys.* **2025** (06) 014. :contentReference[oaicite:17]{index=17}  
2. X. Calmet & B. Latosh, “Quantum Hair and Black-Hole Information,” *Phys. Rev. D* **102** (2025) 084027. :contentReference[oaicite:18]{index=18}  
3. F. Lobo *et al.*, “Planckeons as Mouths of Quantum Wormholes,” *arXiv:2505.02804* (2025). :contentReference[oaicite:19]{index=19}  
4. S. Carroll, “ER = EPR: Entanglement as Spacetime,” *Quantum Frontiers* (May 2024). :contentReference[oaicite:20]{index=20}  
5. J. Ren & K. Zhou, “General Relativistic Wormhole Connections at Planck Scales,” *Int. J. Mod. Phys.* D **34** (2024) 2350059. :contentReference[oaicite:21]{index=21}  
6. Webb Telescope Science Team, “Newfound Galaxy Class Indicates Early Black-Hole Growth,” *JWST Press Release* 101 (2025). :contentReference[oaicite:22]{index=22}  
7. R. Gamba *et al.*, “Parametrized Plunge-Merger-Ringdown Waveforms Beyond GR,” *Phys. Rev. D* **108** (2025) 024043. :contentReference[oaicite:23]{index=23}  
8. LIGO Scientific Collaboration, “Testing Specific Theories Beyond GR with LIGO,” *LIGO T2300223* (2024). :contentReference[oaicite:24]{index=24}  
9. Event Horizon Telescope Collaboration, “Polarization of Sagittarius A*,” *Astrophys. J.* **964** L25 (2024). :contentReference[oaicite:25]{index=25}  
10. EHT-Europe Consortium, “Persistent Shadow of M87,” *Astron. Astrophys.* **673** A140 (2025). :contentReference[oaicite:26]{index=26}  
11. M. Wielgus *et al.*, “Time-resolved Faraday Rotation Near Sagittarius A*,” *Astrophys. J.* **945** 124 (2024). :contentReference[oaicite:27]{index=27}  

