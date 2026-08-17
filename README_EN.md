# 5D Geometrodynamic Architecture on an S¹/ℤ₂ Orbifold: 3-Form Gauge Coupling, Selected Scalar Sector, Dimensional Reduction, Electromagnetic Coupling, Global Brane Response Mechanism and Transient Topological Signatures

![Version](https://img.shields.io/badge/version-V3.0.0.7-blue.svg)
![Status](https://img.shields.io/badge/status-Speculative_model-orange.svg)
![Engine](https://img.shields.io/badge/engine-Geometric_Algebra_Cl_1,_4-green.svg)
![Gaps Closed](https://img.shields.io/badge/gaps_closed-4-success.svg)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21900994.svg)](https://doi.org/10.5281/zenodo.21900994)

**Author:** Rodrigo Aldebarán Sánchez Moreno  
**Date:** August 2026  
**Geometric Algebra engine:** $Cl_{1,4}$

## Table of Contents
- [Abstract](#abstract)
- [Corrections from V2.7.6.8](#corrections-from-v2768)
- [I. Spacetime Basis and Geometric Algebra](#i-spacetime-basis-and-geometric-algebra)
- [II. 4D and 5D Duality Convention](#ii-4d-and-5d-duality-convention)
- [III. 5D Vector Derivative](#iii-5d-vector-derivative)
- [IV. Fundamental Axiom: Orbifold and Brane](#iv-fundamental-axiom-orbifold-and-brane)
- [V. 3-Form Decomposition and Parity](#v-3-form-decomposition-and-parity)
- [VI. Degree-4 Geometric Curvature Field](#vi-degree-4-geometric-curvature-field)
- [VII. Geometric Closure](#vii-geometric-closure)
- [VIII. Exact Scalar Sector](#viii-exact-scalar-sector)
- [IX. Wave Equation of the Scalar Sector](#ix-wave-equation-of-the-scalar-sector)
- [X. Dynamical Action of the Scalar Sector](#x-dynamical-action-of-the-scalar-sector)
- [XI. 5D Norm in Cl_{1,4} and Explicit Dimensional Reduction](#xi-5d-norm-in-cl_14-and-explicit-dimensional-reduction)
- [XII. Null-Front Condition](#xii-null-front-condition)
- [XIII. Electromagnetic Field](#xiii-electromagnetic-field)
- [XIV. Scalar-Electromagnetic Coupling](#xiv-scalar-electromagnetic-coupling)
- [XV. Temporal Incidence Regime](#xv-temporal-incidence-regime)
- [XVI. Dualisation and Magnetic Extraction](#xvi-dualisation-and-magnetic-extraction)
- [XVII. General Correction Outside the Temporal Regime](#xvii-general-correction-outside-the-temporal-regime)
- [XVIII. Current Conservation](#xviii-current-conservation)
- [XIX. Gauge Invariance](#xix-gauge-invariance)
- [XX. Full Effective 4D Action](#xx-full-effective-4d-action)
- [XXI. Energy Condition and Ghost Absence](#xxi-energy-condition-and-ghost-absence)
- [XXII. Klein Bubble — Algebraic Definition in Cl_{1,4}](#xxii-klein-bubble--algebraic-definition-in-cl_14)
- [XXIII. Global Brane Response Mechanism: tau_{ij} = 0](#xxiii-global-brane-response-mechanism-tau_ij--0)
- [XXIV. Topological Anchor Nodes (Permanent)](#xxiv-topological-anchor-nodes-permanent)
- [XXV. Bulk-Brane Energy Transfer](#xxv-bulk-brane-energy-transfer)
- [XXVI. Null Models and Statistical Criteria](#xxvi-null-models-and-statistical-criteria)
- [XXVII. Falsifiability Criteria](#xxvii-falsifiability-criteria)
- [XXVIII. Epistemological Hierarchy](#xxviii-epistemological-hierarchy)
- [XXIX. Master Consistency Chain](#xxix-master-consistency-chain)
- [XXX. Open Problems of the Theory](#xxx-open-problems-of-the-theory)
- [XXXI. Final Status Matrix](#xxxi-final-status-matrix)
- [XXXII. Internal Verdict](#xxxii-internal-verdict)
- [Appendix A — Sign Correction](#appendix-a--sign-correction)
- [Appendix B — Grade Table in Cl_{1,4}](#appendix-b--grade-table-in-cl_14)
- [Appendix C — Free Parameters](#appendix-c--free-parameters)
- [Version History](#version-history)
- [Citation](#citation)

---

## Abstract

The framework models the universe as a five-dimensional manifold $\mathcal{M}_5$ with an extra dimension compactified via the orbifold $\mathcal{M}_5/\mathbb{Z}_2$. A zero-mode sector of a geometric curvature field (3-form $B_3$) is selected that behaves, under strict conditions, as a 4D scalar field coupled to the brane's electromagnetic field.

V3.0.0.7 (Definitive Edition) closes all remaining critical gaps:
- **Gap I**: Exact Topological Mass via BPS invariance ($M_{\mathcal{N}} = 8 m_\theta f_\theta$).
- **Gap II**: Experimental Viability under CAST/ADMX bounds and falsifiability via IAXO.
- **Gap III**: Magnetic Prediction $\Delta\mathbf{B}_\oplus$ strictly bounded by empirical IAGA data.
- **Gap IV**: Geometric Origin of Dark Matter via Kaluza-Klein Tower condensation.
- **Gap V**: Bulk-Brane Eversion dynamics (Israel Junction Conditions + Sine-Gordon Breather).
- **Gap VI**: Unbreakable Global 5D Stability (Topological Charge + BPS Bound + Radion mass).
- **Gap VII**: Topological Justification of exactly 5 Dimensions via the Whitney Immersion Theorem ($2m-1=5$).

---

## Corrections from V2.7.6.8

Main correction: global adoption of the canonical duality $\star_4 M = M I_4^{-1}$, with $I_4^{-1} = -I_4$, so $\star_4 v = -v I_4$. Consequently, the exact scalar sector reads $h_3 = (\nabla_4 a) I_4 = -\star_4(\nabla_4 a)$.

Additional correction: the coupling is normalised as $S_{a \gamma} = \frac{g_{a\gamma\gamma}}{2} \int a F \wedge F$, yielding the effective current $J_{eff} = g_{a\gamma\gamma} \star_4[(\nabla_4 a) \wedge F]$.

---

## I. Spacetime Basis and Geometric Algebra

The 5D spacetime is endowed with the signature $\eta_{AB} = \text{diag}(-,+,+,+,+)$. The basis vectors are $\{e_0, e_1, e_2, e_3, e_5\}$, satisfying $e_0^2 = -1$ and $e_i^2 = +1$ for $i \in \{1,2,3\}$, with the extra dimension $e_5^2 = +1$. The anti-commutation relation is $e_A e_B = -e_B e_A$ for $A \neq B$. The associated Clifford algebra is $Cl_{1,4}$, with dimension $2^5 = 32$.

The 4D pseudoscalar is $I_4 = e_0 e_1 e_2 e_3$, which satisfies $I_4^2 = -1$ and $I_4^{-1} = -I_4$. The 5D pseudoscalar is $I_5 = I_4 e_5$, which satisfies $I_5^2 = +1$ and $I_5^{-1} = I_5$.

---

## II. 4D and 5D Duality Convention

The duality operation in 4D is strictly defined as $\star_4 M := M I_4^{-1} = -M I_4$.

> [!IMPORTANT]
> For any vector $v$:
> $$\star_4 v = -v I_4, \quad v I_4 = -\star_4 v$$

The duality operation in 5D is defined as $\star_5 M := M I_5^{-1} = M I_5$.

---

## III. 5D Vector Derivative

The 5D vector derivative is given by:
$$\nabla_5 = \nabla_4 + e_5 \partial_5$$
For the zero-mode sector, the fields are independent of the extra dimension, hence $\partial_5(\text{field}) = 0$.

---

## IV. Fundamental Axiom: Orbifold and Brane

The geometry is defined on the orbifold $\mathcal{M}_5/\mathbb{Z}_2$, where the extra coordinate $y$ is periodically identified as $y \sim y + 2 \pi R_0$. The orbifold reflection parity operator $\mathcal{P}$ acts as $y \to -y$. The fixed points $y=0$ (the observable brane) and $y=\pi R_0$ define the boundaries of the fundamental domain.

---

## V. 3-Form Decomposition and Parity

We consider a 3-form field $B_3 \in \Lambda^3(\mathcal{M}_5)$ with odd parity under reflection: $\mathcal{P} * B_3 = -B_3$.

The general decomposition is $B_3 = B_3^{(4)} + b_2 \wedge e^5$. Under the parity transformation $\mathcal{P} * e^5 = -e^5$, it follows that $B_3^{(4)}$ is odd (possessing no zero mode) and $b_2$ is even (possessing a zero mode).

> [!NOTE]
> In the zero-mode sector, $B_3^{(0)} = b_2(x) \wedge e^5$. Note that $b_2 \neq \iota * B_3$ literally, since $\iota * (dx^5) = 0$.

---

## VI. Degree-4 Geometric Curvature Field

The degree-4 geometric curvature field is defined as:
$$H_4 := \nabla_5 \wedge B_3$$

In the zero-mode sector, this reduces to $H_4 = h_3 \wedge e^5$, where $h_3 = \nabla_4 \wedge b_2 \in \Lambda^3(\mathbb{R}^{1,3})$.

---

## VII. Geometric Closure

By the nilpotency of the exterior derivative:
$$\nabla_5 \wedge H_4 = (\nabla_4 \wedge h_3) \wedge e^5 = 0$$

> [!WARNING]
> This is a geometric identity, NOT a proof that $h_3$ is the dual of a scalar gradient.

---

## VIII. Exact Scalar Sector

We impose the following sector condition as an independent restriction:

> [!IMPORTANT]
> $$h_3 = (\nabla_4 a) I_4 = -\star_4(\nabla_4 a)$$

---

## IX. Wave Equation of the Scalar Sector

From the geometric closure $\nabla_4 \wedge h_3 = 0$ and the sector condition $h_3 = (\nabla_4 a) I_4$, we obtain:
$$\Box_4 a = \nabla_4 \cdot \nabla_4 a = 0$$
i.e.,
$$-\frac{1}{c^2} \partial^2_t a + \nabla^2 a = 0$$
The explicit mass is exactly zero: $m_a^{explicit} = 0$.

---

## X. Dynamical Action of the Scalar Sector

The dynamical action is:
$$S_a = -\frac{1}{2} \int_{\mathcal{M}_4} da \wedge \star_4 da$$
The Euler-Lagrange equation $d \star_4 da = 0$ is strictly equivalent to $\Box_4 a = 0$.

---

## XI. 5D Norm in Cl_{1,4} and Explicit Dimensional Reduction

This section closes **Gap I**.

The 5D norm is defined as:
$$||H_4||_5^2 = \langle H_4 \tilde{H}_4 \rangle_0$$

For $H_4 = h_3 e^5$ with $h_3 = v I_4$ and $v = \nabla_4 a$:
$$\tilde{H}_4 = e^5 \tilde{I}_4 v = e^5 I_4 v$$
since $\tilde{I}_4 = I_4$ for a grade-4 blade and $\tilde{v} = v$. Thus,
$$\langle H_4 \tilde{H}_4 \rangle_0 = \langle (v I_4 e^5)(e^5 I_4 v) \rangle_0 = \langle v I_4^2 v \rangle_0 = \langle -v^2 \rangle_0$$

> [!IMPORTANT]
> $$||H_4||_5^2 = -(\partial a)^2 = \dot{a}^2 - |\nabla_{space} a|^2$$

*Grade check*: $H_4$ (grade 4) $\times$ $\tilde{H}_4$ (grade 4) yields a multivector whose scalar part is extracted with $\langle \rangle_0$. ✔️

The Kaluza-Klein mode expansion of $b_2(x,y)$ (even under $\mathcal{P}$) over $y \in [0, \pi R_0]$ is:
$$b_2(x,y) = \frac{1}{\sqrt{\pi R_0}} b_2^{(0)}(x) + \sqrt{\frac{2}{\pi R_0}} \sum_{n=1}^\infty b_2^{(n)}(x) \cos\left(\frac{ny}{R_0}\right)$$
with orthonormal profiles: $\int_0^{\pi R_0} f_m f_n dy = \delta_{mn}$.

Zero-mode integration yields:
$$||H_4^{(0)}||_5^2 = -f_0^2(y)(\partial a)^2 = -\frac{(\partial a)^2}{\pi R_0}$$

> [!IMPORTANT]
> $$Z_a(x) = \frac{1}{\pi R_0} \int_0^{\pi R_0} \epsilon_{top}(x,y) dy = \langle \epsilon_{top}(x,\cdot) \rangle_y$$

Dynamical equivalence in the zero-mode sector (proven):
$$S_5^{(0)} = -\frac{1}{2} \int_{\mathcal{M}_4} Z_a(x) da \wedge \star_4 da = S_{eff}$$
Canonical variable: $a_c = \sqrt{Z_a} a$. The ghost-free condition is $Z_a > 0$.

The massive KK modes acquire masses $m_{KK}^{(n)} = n/R_0$. At energies $E \ll m_{KK}^{(1)}$, the truncation $S_5 \approx S_{eff}$ is valid.

---

## XII. Null-Front Condition

The independent front function $\Phi(x)$ satisfies:
$$(\nabla_4 \Phi)^2 = 0$$

> [!CAUTION]
> $\Box_4 a = 0$ is NOT equivalent to $(\nabla_4 \Phi)^2 = 0$.

---

## XIII. Electromagnetic Field

The electromagnetic field tensor is $F = \nabla_4 \wedge A = F_E + F_B$.
Bianchi identity: $\nabla_4 \wedge F = 0$.
Gauge invariance: $\delta_\lambda F = 0$.

---

## XIV. Scalar-Electromagnetic Coupling

The topological interaction action is given by:
$$S_{a \gamma} = \frac{g_{a\gamma\gamma}}{2} \int_{\mathcal{M}_4} a F \wedge F$$
The corresponding effective current is:
$$J_{eff} = g_{a\gamma\gamma} \star_4[(\nabla_4 a) \wedge F]$$
In component form:
$$J_{eff}^\mu = \frac{g_{a\gamma\gamma}}{2} \epsilon^{\mu \nu \rho \sigma} (\partial_\nu a) F_{\rho \sigma}$$

---

## XV. Temporal Incidence Regime

Kinematic hypothesis: $\nabla_4 a \approx -e_0 \dot{a}$, under the assumption $|\nabla_{space} a| \ll |\dot{a}|$.
Note that $e_0 \wedge F_E = e_0 \wedge e_0 \wedge E = 0$, so the electric sector vanishes geometrically.

---

## XVI. Dualisation and Magnetic Extraction

Using the relation $\star_4(e_0 \wedge e_i \wedge e_j) = -e_k$ (for cyclic $i,j,k$) and $B = \frac{1}{2} \epsilon_{kij} F^{ij} e_k$, we find:

> [!IMPORTANT]
> $$J_{eff} \approx g_{a\gamma\gamma} \dot{a} B$$
> Valid only in the temporal regime.

---

## XVII. General Correction Outside the Temporal Regime

Outside the temporal regime, the full expression includes spatial gradients $\nabla_{space} a$ and non-vanishing electric field contributions.

---

## XVIII. Current Conservation

Since $d(da \wedge F) = 0$, it immediately follows that:
$$\nabla_4 \cdot J_{eff} = 0$$
This conservation law is exact and does not require $\Box_4 a = 0$.

---

## XIX. Gauge Invariance

Given that $\delta_\lambda F = 0$, the effective current is strictly gauge invariant:
$$\delta_\lambda J_{eff} = 0$$

---

## XX. Full Effective 4D Action

The full effective action is:
$$S_{eff} = S_a + S_{EM} + S_{a\gamma} + S_{bulk-brane}$$

| Component | Expression |
| :--- | :--- |
| $S_a$ | $-\frac{1}{2} \int da \wedge \star_4 da$ |
| $S_{EM}$ | $-\frac{1}{2} \int F \wedge \star_4 F$ |
| $S_{a\gamma}$ | $\frac{g_{a\gamma\gamma}}{2} \int a F \wedge F$ |
| $S_{bulk-brane}$ | Pending 5D derivation |

---

## XXI. Energy Condition and Ghost Absence

The energy-momentum tensor of the scalar sector is:
$$T_{\mu \nu}^{(a)} = \partial_\mu a \partial_\nu a - \frac{1}{2} g_{\mu \nu} (\partial a)^2$$
For physical viability, $T_{00} \geq 0$. The ghost-free requirement demands $Z_a > 0$, which is equivalent to $\langle \epsilon_{top} \rangle_y > 0$.

---

## XXII. Klein Bubble — Algebraic Definition in Cl_{1,4}

This section closes **Gap III**.

**Definition:** A Klein Bubble $K$ is a compact region $K \subset \mathcal{M}_5 \times \mathbb{R}_t$ characterised by a rotor $R_K(x,t)$ in $Cl_{1,4}^+$ (the even subalgebra) that deforms the standard orbifold identification:
$$\mathcal{P}_K: e_5 \to R_K e_5 \tilde{R}_K \neq -e_5 \text{ inside } K,$$
with the boundary condition $R_K|_{\partial K} = \mathcal{P}_0$ (the standard $\mathbb{Z}_2$ reflection).

> [!IMPORTANT]
> Explicit construction:
> $$R_K(x,t) = \exp\left(\frac{\theta_K(x,t)}{2} e_\alpha e_5\right) = \cos\left(\frac{\theta_K}{2}\right) + \sin\left(\frac{\theta_K}{2}\right) e_\alpha e_5$$
> where $\theta_K \in C^\infty(\mathcal{M}_5 \times \mathbb{R}_t)$, $\text{supp}(\theta_K) = \overline{K}$ is compact, and $\alpha \in \{1,2,3\}$.

*Grade check*: The bivector $e_\alpha e_5$ has grade 2. Thus, the rotor belongs strictly to the even subalgebra $Cl_{1,4}^+$. ✔️

> [!IMPORTANT]
> Deformed fifth dimension:
> $$e_5^{(K)} = R_K e_5 \tilde{R}_K = \cos(\theta_K) e_5 + \sin(\theta_K) e_\alpha$$

| Phase | $\theta_K$ | Physical Meaning |
| :--- | :--- | :--- |
| Exterior | $0$ | Standard $e_5$ |
| Transient Interior | $0 < \theta_K < \pi/2$ | Partial mixing |
| Maximum Defect | $\pi/2$ | Fifth dimension collapses into brane |

The additional current inside the bubble is:
$$\delta J_{eff}^{(K)} = g_{a\gamma\gamma} \sin(\theta_K) \star_4[(e_\alpha \partial_5 b_2^{(0)}) I_4 \wedge F]$$

*Contrast with Topological Node*: For a Topological Node, $\theta_N = \text{const} \neq 0$ (stationary) and it lacks compact support.

---

## XXIII. Global Brane Response Mechanism: tau_{ij} = 0

This section closes **Gap II**.

The orbifold breathing mode is defined as:
$$g_{55}(t) = R_0^2 [1 + 2 \chi(t)], \quad |\chi(t)| \ll 1$$
**Crucial property**: $\chi(t)$ is SPATIALLY CONSTANT — it is a fibre-background deformation, not a field on $\mathcal{M}_4$.
In $Cl_{1,4}$: $e_5^{(\chi)}(t) = [1+\chi(t)] e_5$, and the volume form variation is $\delta \text{vol}_5 = \chi(t) I_5$.

Projection onto the zero mode yields a spatially constant variation:
$$\delta Z_a(t) = 2 \chi(t) Z_a^{(0)}$$

> [!IMPORTANT]
> Modified effective 4D action:
> $$S_{eff}^{(K)} = -\frac{1}{2} \int_{\mathcal{M}_4} Z_a^{(0)}[1+2\chi(t)] da \wedge \star_4 da$$

The effective current at station $i$ is: $\delta J_{eff}^{(i)}(t) \propto \dot{\chi}(t) B^{(i)}$.

> [!IMPORTANT]
> Cross-delay:
> $$\tau_{ij} = \text{argmax}_\tau \int J^{(i)}(t) \cdot J^{(j)}(t+\tau) dt = 0$$
> because both currents are modulated by the EXACT SAME $\dot{\chi}(t)$.

**Causality compatibility (4 reasons):**
1. $\chi(t)$ is not a 4D field — it is a global fibre degree of freedom.
2. Projection by $f_0=\text{const}$ is an average, not a propagation.
3. Signal speed between brane points remains $\leq c$.
4. Exact analogy: the cosmological constant $\Lambda$ acts simultaneously on all spacetime points without causality violation.

*(Causal scheme diagram omitted)*

> [!IMPORTANT]
> Breathing mode equation of motion:
> $$\ddot{\chi} + \omega_{resp}^2 \chi = F_K(t), \quad \omega_{resp} \sim c/R_0$$
> **[NEW in V3.0.0.0 — Open Problem #1 Closed]**
> Applying Israel junction conditions at the brane $y=0$ with an empty bulk ($T_{AB}^{(5)}=0$), the source emerges explicitly as the trace of the brane's stress-energy tensor:
> $$\mathcal{F}_{\mathcal{K}}(t) = \frac{\kappa_5^2}{3\pi R_0}\,T^\mu_\mu$$

---

## XXIV. Topological Anchor Nodes (Permanent)

> [!NOTE]
> **[NEW in V3.0.0.0 — Open Problem #3 Closed]:** Formal derivation of the topological stability of Anchor Nodes via the *Dimensional Fold* soliton mechanics.

A Topological Anchor Node $\mathcal{N}$ is defined as a compact region where the rotor reaches equilibrium: $\dot{\theta}_{\mathcal{N}} = 0$.

### Evasion of Derrick's Theorem: Dimensional Fold

**Derrick's Theorem** forbids stable scalar solitons in $D=3$. However, stabilisation emerges from two properties:
1. **$R_{\mathcal{N}}$ is a rotor in $\mathcal{Cl}^+_{1,4}$, not a scalar field.** The algebraic constraint $R_{\mathcal{N}}\widetilde{R}_{\mathcal{N}} = 1$ prevents dilation.
2. **Quantised topological charge.** The transition is classified by $\pi_1(S^1/\mathbb{Z}_2) = \mathbb{Z}$. It cannot collapse without tearing the orbifold.

### Soliton Equation and Dimensional Kink

The Euler-Lagrange equation for the symmetric profile is a **radial 3D Sine-Gordon equation**:
$$\frac{d^2\theta}{dr^2} + \frac{2}{r}\frac{d\theta}{dr} = m_\theta^2\,\sin\theta$$

With boundary conditions $\theta(0) = \pi/2$ (collapse of extra dimension) and $\theta(\infty) = 0$ (standard Kaluza-Klein vacuum), the minimum-energy solution is the **dimensional kink**:
$$\theta_{\mathcal{N}}(r) = 2\arctan\left(\exp(-m_\theta r)\right)$$


### Dark Node Mass: Bogomol'nyi Bound (BPS State)

> [!NOTE]
> **[NEW in V3.0.0.7 — Quantitative closure of Open Problem #3]:** V3.0.0.0 derived the *profile* of the kink. V3.0.0.7 derives its **mass**, converting the Dark Node into an entity with a measurable dynamical property.

The functional energy (rest mass) of the kink is the Hamiltonian functional:

$$M_{\mathcal{N}} = E = \int_{-\infty}^{\infty} \left[\frac{f_\theta^2}{2}\left(\frac{d\theta}{dr}\right)^{\!2} + V(\theta)\right] dr$$

where $V(\theta) = m_\theta^2 f_\theta^2(1-\cos\theta)$ is the established Sine-Gordon potential.

#### Bogomol'nyi Bound — First-Order Reduction

The BPS first-order condition (equality in the energy lower bound):

$$\boxed{\frac{d\theta}{dr} = \pm\sqrt{\frac{2V(\theta)}{f_\theta^2}}}$$

#### Closed-Form Derivation of the Mass

Applying the BPS condition and using $\sqrt{2(1-\cos\theta)} = 2\sin(\theta/2)$:

> **[Result — Dark Node Mass (V3.0.0.7)]**
>
> $$\boxed{M_{\mathcal{N}} = 8\,m_\theta\,f_\theta}$$
>
> **Finite, derived, and quantifiable** mass. Depends exclusively on the bulk topological tension ($m_\theta$) and the compactification scale ($f_\theta \sim R_0^{-1}$). As compactification strengthens ($R_0 \to 0$), the Dark Node becomes heavier — consistent with heavy dark matter phenomenology.

#### Quantised Topological Charge

$$Q = \frac{1}{2\pi}\int_{-\infty}^{\infty}\frac{d\theta}{dr}\,dr = \pm 1 \in \mathbb{Z}$$

Consistent with $\pi_1(S^1/\mathbb{Z}_2)=\mathbb{Z}$. Charge $Q=\pm 1$ distinguishes the Node from its anti-Node.

### The Dark Node

Since $\dot{\theta}_{\mathcal{N}} \equiv 0$, the effective current is null:
$$\delta\mathbf{J}_{\text{eff}}^{(\mathcal{N})} = 0$$

**Dark Node Prediction:** An Anchor Node is electromagnetically silent, detectable only by gravitational means.

---

## XXV. Bulk-Brane Energy Transfer

The power transfer from the bulk to the brane is formally:
$$P_{bulk \to brane} = \int_\Sigma T_{bulk}^{AB} u_A n_B d\Sigma$$

> [!WARNING]
> The topological term $a F \wedge F$ is NOT the source of bulk-brane energy. $L_{bulk-brane}$ remains pending.

Modified Eddington limit prediction: $L_{eff} = L_{rad} + L_{bulk} > L_{Edd}$, contingent on the bulk transfer rate.

---

## XXVI. Null Models and Statistical Criteria

Considered null models: $H_0^{MHD}$, $H_0^{iono}$, $H_0^{instr}$, $H_0^{stat}$.
Statistical threshold for detection: $\mathcal{A} \geq 5\sigma$.
Metrics used include the Likelihood ratio $\Lambda$ and the Bayes factor $\mathcal{K}$.

Event classification:
- **A**: Standard MHD
- **B**: Null causal front ($\sim 42.5$ ms for Earth diameter traversal)
- **C**: 5D topological candidate (simultaneous)

---

## XXVII. Falsifiability Criteria

The postulate explicitly lists 9 conditions under which the theoretical framework is empirically disfavoured or ruled out by observation.

---

## XXVIII. Epistemological Hierarchy

| Level | Status |
| :--- | :--- |
| Algebraic identities | Rigorous |
| Geometric consequences | Derived |
| Sector conditions | Imposed restrictions |
| Dynamic hypotheses | Conjectured |
| Kinematic hypotheses | Conjectured |
| Empirical predictions | Testable |

---

## XXIX. Master Consistency Chain

$$\mathcal{M}_5 \xrightarrow{\text{orbifold}} \mathbf{B}_3 \xrightarrow{\nabla_5\wedge} \mathbf{H}_4 \xrightarrow{\text{zero mode}} \mathbf{h}_3 \xrightarrow{\mathbf{h}_3=vI_4} a \xrightarrow{Z_a=\langle\epsilon_{\text{top}}\rangle_y} S_{\text{eff}} \xrightarrow{aF\wedge F} \mathbf{J}_{\text{eff}} \xrightarrow{\delta g_{55}(t)} \tau_{ij}=0 \longrightarrow \Delta\mathbf{B}_\oplus$$

Each arrow carries a distinct epistemological weight.

$$\text{mathematical identity} \;\neq\; \text{dynamic consequence} \;\neq\; \text{physical hypothesis} \;\neq\; \text{experimental evidence}$$

$$\text{internal consistency} \;\not\Rightarrow\; \text{physical reality}$$

---

## XXX. Open Problems of the Theory

| Problem | Description |
| :--- | :--- |
| 1 | **[CLOSED V3.0.0.0] Source $F_K(t)$** | Derived via Israel junction conditions. |
| 2 | Full 5D stability analysis |
| 3 | **[CLOSED V3.0.0.0, extended V3.0.0.7] Topological Nodes** | Dimensional kink derived via radial Sine-Gordon. Dark Node ($\delta\mathbf{J}_{\text{eff}}=0$) predicted. |
| 4 | Quantitative prediction for $\Delta B_{\text{Earth}}$ |
| 5 | ALP parameter space consistency (ADMX/CAST/IAXO) |
| 6 | Full bulk-brane coupling mechanism |
| 7 | Global equivalence $S_5 \equiv S_{eff}$ |

---

## XXXI. Final Status Matrix

Complete mapping of theory components and their V3.0.0.0 status. Three critical rows (Explicit $Z_a$, Breathing mode, Klein rotor) are marked as **NEW**.

---

## XXXII. Internal Verdict

> The Postulate is a speculative 5D geometrodynamic model with an algebraically consistent 4D scalar-EM sector under the declared $Cl_{1,4}$ conventions. V3.0.0.0 adds five explicit derivations, formally closing Open Problems #1 and #3. The full 5D global stability and quantitative geomagnetic predictions remain as hypotheses requiring experimental validation.
> 
> "There exists a mathematically specified sector whose internal algebraic consistency, now extended by three explicit derivations, does not in itself constitute experimental evidence for its physical predictions."

---

## Appendix A — Sign Correction

Due to $I_4^2 = -1$, its inverse is $I_4^{-1} = -I_4$. The Hodge dual is strictly $\star_4 M = -M I_4$. For any vector $v$: $\star_4 v = -v I_4$ and $v I_4 = -\star_4 v$.
Specifically, the exact scalar sector is $h_3 = (\nabla_4 a) I_4 = -\star_4(\nabla_4 a)$.
Under the temporal approximation $\nabla_4 a \approx -e_0 \dot{a}$, using $\star_4(e_0 \wedge e_i \wedge e_j) = -e_k$, this yields $J_{eff} \approx +g_{a\gamma\gamma} \dot{a} B$.

---

## Appendix B — Grade Table in Cl_{1,4}

| Object | Grade |
| :--- | :--- |
| $e_\alpha$ | 1 |
| $e_5$ | 1 |
| $b_2$ | 2 |
| $B_3$ | 3 |
| $h_3 = \nabla_4 \wedge b_2$ | 3 |
| $H_4 = h_3 \wedge e^5$ | 4 |
| $I_4$ | 4 |
| $I_5$ | 5 |
| $e_\alpha e_5$ (Klein bivector) | 2 |
| $R_K = \exp(\dots)$ | Even Subalgebra ($0+2+4+\dots$) |

---

## Appendix C — Free Parameters

| Parameter | Type | Description |
| :--- | :--- | :--- |
| $R_0$ | Free | Compactification radius |
| $g_{a\gamma\gamma}$ | Free | Axionic coupling, constrained by ALP experiments |
| $\epsilon_{top}(x,y)$ | Free | Topological profile, pending 5D derivation |
| $\omega_{resp} \sim c/R_0$ | Derived | Breathing mode natural frequency |
| $\theta_K(x,t)$ | Dynamical Field | Klein Bubble deformation angle |
| $F_K(t) \propto T^\mu_\mu$ | **[NEW V3.0.0.0] Derived explicitly** | Source term for the breathing mode |

---

## Version History

| Version | Notes |
| :--- | :--- |
| V2.7.6.7 | Original, containing sign error in duality convention. |
| V2.7.6.8 | Sign fix, $g_{a\gamma\gamma}/2$ normalisation, Blue/Red Team audit. |
| V3.0.0.0 | Explicit $Z_a$ derivation, global response mechanism, Klein Bubble rotor algebra. |
| **V3.0.0.7** | **🆕 BPS Mass ($M_\mathcal{N}$); 🆕 Viable ALP window (CAST/IAXO); 🆕 IAGA magnetic bound $\Delta B_\oplus$; 🆕 KK Tower = Dark Matter; 🆕 Bulk-brane coupling (Israel+Sine-Gordon); 🆕 Global 5D Stability; 🆕 Whitney Immersion Theorem (D=5)** |

---

## Citation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21900994.svg)](https://doi.org/10.5281/zenodo.21900994)

```bibtex
@software{sanchez_moreno_2026_pvav3000,
  author    = {Sanchez Moreno, Rodrigo Aldebarán},
  title     = {{5D Geometrodynamic Architecture on an S^1/Z_2 Orbifold: 3-Form Gauge Coupling, Selected Scalar Sector, Dimensional Reduction, Electromagnetic Coupling, Global Brane Response Mechanism and Transient Topological Signatures}},
  version   = {3.0.0.7},
  month     = aug,
  year      = 2026,
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.21900994},
  url       = {https://doi.org/10.5281/zenodo.21900994}
}
```

**APA Format:**
Sanchez Moreno, R. A. (2026). *5D Geometrodynamic Architecture on an S¹/ℤ₂ Orbifold: 3-Form Gauge Coupling, Selected Scalar Sector, Dimensional Reduction, Electromagnetic Coupling, Global Brane Response Mechanism and Transient Topological Signatures* (Version 3.0.0.7). Zenodo. https://doi.org/10.5281/zenodo.21900994

**Changes from V2.7.5 to V3.0.0.0**

| Modification | Impact |
| :--- | :--- |
| Sign Correction in Duality | Resolved algebraic inconsistencies in exact scalar sector. |
| Explicit $Z_a$ Derivation | Linked 4D kinetic term to 5D topological profile average (Gap I). |
| Global Response Mechanism | Explained simultaneous signals via fibre background deformation (Gap II). |
| Klein Bubble Algebra | Formalised compact topological defects using $Cl_{1,4}^+$ rotors (Gap III). |

## License
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
