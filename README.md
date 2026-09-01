

# Proper Time Cosmology#
Redshift, distance, and the Hubble tension as effects of local phase accumulation
All physical measurements reduce to comparing counted phase cycles. Every redshift, every distance, every second we define is a ratio of phase accumulation between an emitter and an observer. Cosmology already depends on this, but it assumes the phase rate—what we call a "second"—is the same everywhere. It isn't.

When we compare light from distant galaxies, we are comparing processes that evolved at different rates. What we call redshift already encodes that difference. Recognizing that different regions of the universe accumulate phase at different rates resolves key cosmological tensions—the Hubble discrepancy and the early-galaxy problem—without invoking new physics.

The proposed fix is not a new model. It is to take the existing one literally: time is proper, seconds are local, and we have always been measuring phase. It is time we said so.
---## 01 Overview
Every measuring stick is local. A second is not a mystical slice of time floating in space—it is us counting a fixed number of cycles of a cesium-133 transition in a lab. A meter is not a cosmic ruler—it is the distance light travels during a fixed fraction of that locally counted second. Seconds and meters are counts of phase cycles; that is literally how the SI system defines them.

Gravity changes how fast those cycles tick. Put the same kind of atom deeper in a gravitational well and its tick rate slows; place it higher and it speeds up. This is not controversial—it is how GPS works, and why satellite clocks are corrected. So if clocks tick at different rates in different places, what happens when we compare something that happened "there" to the standard we use "here"?

Any time we make that comparison we are crossing domains: using our local counting system to interpret a signal born in a different gravitational environment. If we do not first match those clocks, we build in a bias—sometimes tiny, sometimes not.

Parallax, the standard method for nearby stars, is largely a geometry trick performed entirely with our own tools: we watch a star shift against the background as Earth moves and turn that angle, plus our baseline, into a distance. Every input is a local count—our baseline, our detector timing, our sky angle—so the star's own tick rate never enters the result. Parallax is locally consistent; it is simply insensitive to the clock mismatch. It is like using two microphones on the same stage to find where a singer stands—no need for the singer's wristwatch.

Cosmology is different. Its primary observable, redshift, is literally a comparison of how fast a photon's phase was cycling at emission versus how fast it is cycling at detection—a cross-domain comparison by definition. If that raw comparison is converted directly into miles or years in our units, without first aligning "their second" to "our second," the mismatch ripples into every distance we publish, every look-back time we quote, and every age we assign to a galaxy. This is exactly where the current tensions show up most strongly.

The fix is not to discard the physics; it is to tighten the bookkeeping. Before turning any cross-domain measurement into numbers in our units, match the clocks—the way GPS applies a clock correction before navigation. In practice this means publishing two columns: the standard values in use today, and a clock-matched set in which the source's clock has been aligned to ours. Start where it matters most—redshift-based distances, gravitational-lens time delays, and any method that mixes a remote timing process with our local standard. Parallax can stay as is, since it is largely insensitive, while still acknowledging the underlying principle.

SI units are local. Gravity makes clocks domain-specific. Whenever we compare "there" to "here," we should treat it as a cross-domain comparison of clocks. Parallax mostly gets away with skipping that step; redshift does not.
---## 02 The Unit Problem in Redshift Interpretation
In the interpretation of cosmological redshift we compare a photon's emitted and observed frequencies—quantities defined as phase rates per unit of proper time in their respective spacetimes. Yet the entire analysis is carried out in observer-defined units: a second defined by 9,192,631,770 transitions of cesium-133 in our gravitational potential, and a meter defined as the distance light travels in 1/299,792,458 of that second, also within our potential. Both units used in cosmological inference are grounded entirely in the observer's local spacetime conditions.

The emitter's proper time—and the number of cesium-133 transitions that constitute a "second" in its own gravitational and cosmological context—need not be numerically equivalent to ours. Because the meter is defined through time, the emitter's local unit of length may differ as well. Despite this, redshift interpretation treats $\lambda_{emit}$ and $\nu_{emit}$ as if expressed in the observer's unit system, without ever performing the transformation between the two.

It is not a resolution to say that redshift is dimensionless. The ratio $z$ is unitless, but its interpretation—in terms of scale factor, time dilation, distance, and velocity—relies on dimensioned constants and frame-specific clocks. Saying "we use the laboratory rest-frame frequency" does not avoid the issue; it substitutes a hypothetical clock already defined in our units for the emitter's actual local clock, then assumes the two are dimensionally equivalent. The emitter's local time standard is never recovered, referenced, or transformed—it is effectively erased.

The same is true of the general-relativistic formalism:

$$1 + z = \frac{(P_\mu u^\mu)_{emit}}{(P_\mu u^\mu)_{obs}}$$

which reduces redshift to a geometric ratio—but the interpretation is still carried out entirely in the observer's unit system; the emitter's seconds and meters are never computed or translated. Using a comoving observer's proper time in place of the emitter's own local clock is a substitution, not a correction—it assumes away the dimensional question.

Standard cosmology interprets redshifted measurements across curved spacetime using only the observer's local unit system, without transforming emitter-defined seconds and meters into observer-defined ones. This is a structural assumption embedded in the interpretation of every redshift-based cosmological quantity. Because the observed redshift is a ratio between the emitter's and observer's ticking clocks, it encodes not just cosmological expansion but any difference in local gravitational potential—so the total observed redshift should decompose as:

$$1 + z_{total} = (1 + z_{local})(1 + z_{path})$$

where $z_{local}$ arises from gravitational time dilation at the emitter, and $z_{path}$ reflects the cosmological redshift from the change in scale factor along the photon's trajectory. Treating $z_{total}$ as purely cosmological implicitly sets $z_{local} = 0$—a simplification, not a necessity.

We do not need direct access to an emitter's local time standard to test this. We can detect the influence of $z_{local}$ empirically by comparing two galaxies with the same total $z$ but different gravitational potentials: a deeper potential well slows the emitter's clock, increasing $z_{local}$ and implying a smaller $z_{path}$—which yields a different inferred cosmological distance, and thus a measurable difference in distance-sensitive observables such as surface brightness. This lets us preserve dimensional consistency and test for gravitational-redshift effects by leveraging relative comparisons across astrophysical environments, without reconstructing the emitter's local metrology directly.

Cosmology has not fully accounted for the operational nature of time as local phase accumulation. It has projected time and distance across cosmic epochs as if oscillator rates were universal rather than domain-specific—causing clock-rate differentials to be misread as new physics, giving rise to the Hubble tension and the appearance of dark energy. If all clocks and rulers are phase-based, and phase rates evolve with curvature, what we observe is not a contradiction but a correction waiting to be made. Because distances are inferred from redshift and apparent brightness using formulas that assume universal clock rates, any evolution in fundamental oscillator phases systematically distorts the cosmic distance ladder—making the universe appear to expand at an accelerating rate when we are, in fact, comparing rulers and clocks that evolved at different cosmic epochs.
---## 03 Time as Phase Accumulation
In the operational framework, time is not an independent continuum but the counted accumulation of phase cycles of a reference oscillator. Let $\phi$ denote accumulated phase (radians) and $\dot{\phi} = d\phi/dt$ the phase-accumulation rate. Measured time is the ratio between accumulated phase and the local phase rate of the reference oscillator:

$$t = \frac{\phi}{\dot{\phi}_{ref}}$$
### The second as a phase countThe SI second is defined by the hyperfine transition of cesium-133:
$$\text{1 s} \equiv 9,192,631,770 \text{ oscillations of the Cs-133 transition}$$

In terms of phase, $\dot{\phi}_{ref} = 2\pi \times 9,192,631,770 \text{ rad} \cdot \text{s}^{-1}$, so that:


$$\text{1 s} \equiv \frac{\Delta\phi_{ref}}{\dot{\phi}{ref}} = \frac{9,192,631,770 \times 2\pi}{\dot{\phi}{ref}}$$
an operational count of phase cycles per local phase rate.
## Locality of the second
Because $\dot{\phi}_{ref}$ depends on gravitational potential through proper-time dilation,
$$\dot{\phi}_{ref}(r) = \dot{\phi}_0 \sqrt{1 - \frac{2GM}{rc^2}}$$
each observer defines their own local second. Seconds in different gravitational domains are inequivalent units of phase accumulation. Normalizing so $\dot{\phi}_{ref} = 1$ gives $t = \phi$: one unit of time is one complete phase cycle. At the fundamental scale, the Planck oscillator sets the invariant rate $\dot{\phi}_P = 2\pi/t_P$, so one Planck time is one Planck-phase cycle of $2\pi$ radians.
Time is not something clocks measure; it is the count of phase cycles clocks accumulate. Differences in local phase-accumulation rates between domains underlie gravitational time dilation and, uncorrected, introduce systematic bias into cosmological redshift measurements.
------------------------------
## 04 Redshift as a Ratio of Local Phase Rates
Every redshift is a comparison between the local phase-accumulation rates of two gravitational domains—not a comparison of absolute frequencies, but of how fast the emitter's and observer's identical reference oscillators accumulate phase relative to their own proper time:
$$1 + z_{total} = \frac{(\dot{\phi}/2\pi){emit}}{(\dot{\phi}/2\pi){obs}} = \frac{\dot{\phi}{emit}}{\dot{\phi}{obs}}$$
## Factorization
As the photon propagates through evolving spacetime, the total redshift factorizes into a path component (cosmological expansion) and a local component (domain-specific clock rate):
$$1 + z_{total} = (1 + z_{path})(1 + z_{local})$$
$$1 + z_{path} = \frac{\dot{\phi}{emit,coord}}{\dot{\phi}{emit,proper}}, \quad 1 + z_{local} = \frac{\dot{\phi}{emit,proper}}{\dot{\phi}{obs,proper}}$$
The first term is the geometric stretching of phase along the trajectory; the second corrects for the difference in intrinsic local phase-accumulation rate between domains.
## Consistency with General Relativity
In the metric formulation, a clock's proper-time rate at position $r$ is $d\tau/dt = \sqrt{g_{00}(r)}$, so $\dot{\phi}(r) \propto \sqrt{g_{00}(r)}$. Substituting into the redshift ratio reproduces the standard gravitational redshift:
$$1 + z_{local} = \sqrt{\frac{g_{00}(obs)}{g_{00}(emit)}}$$
confirming the phase-based formulation is fully consistent with General Relativity, and giving the correction:
$$1 + z_{path} = \frac{1 + z_{total}}{1 + z_{local}}$$
Because every observed redshift implicitly compares emitter and observer phase rates, applying a single clock standard (the observer's) across domains with differing $\dot{\phi}$ causes $z_{total}$ to overestimate the geometric contribution—biasing inferred distances, luminosities, and lookback times. Expressing all quantities in phase rates lets cosmological comparisons be made clock-matched, restoring domain locality and eliminating the implicit assumption of universal seconds.
------------------------------
## 05 Observed Flux and真实 Luminosity Distance
Let the emitter release $N$ cycles of radiation over proper-time interval $\Delta t_{emit}$. These arrive at the observer over:
$$\Delta t_{obs} = \Delta t_{emit} \frac{\dot{\phi}{emit}}{\dot{\phi}{obs}} = \Delta t_{emit}(1+z)$$
so the observed power is:
$$P_{obs} = \frac{E_{emit}}{\Delta t_{obs}} = \frac{h\dot{\phi}{emit}}{\Delta t{emit}(1+z)} = \frac{P_{emit}}{1+z}$$
Assuming geometric spreading over a phase-defined area $A_\phi \sim D_\phi^2$, the observed flux is:
$$F = \frac{P_{obs}}{4\pi D_\phi^2} = \frac{L}{4\pi D_\phi^2 (1+z)^2}$$
giving the phase-defined luminosity distance:
$$D_L^{(\phi)}(z) = D_\phi (1+z)$$
------------------------------
## 06 Angular Diameter Distance
Let the emitter span $N_{spatial}$ spatial phase cycles, so its proper size is $L = N_{spatial} \cdot \lambda_{emit} = N_{spatial} \cdot 2\pi / k_{emit}$. Subtending angle $\theta$ at the observer, the angular diameter distance becomes:
$$D_A^{(\phi)} = \frac{L}{\theta} = \frac{N_{spatial}}{\theta} \frac{2\pi}{k_{emit}}$$
Because $k_{emit}$ is curvature-dependent, this expression departs from the standard FLRW derivation.
------------------------------
## 07 The Hubble Tension as Oscillator Drift
The Hubble parameter expressed through phase is:
$$H(z) = \frac{1}{a}\frac{da}{dt} = \frac{1}{a}\frac{da}{d\phi}\dot{\phi}$$
Comparing early- and late-universe clocks (CMB versus Cepheids), the phase rate differs: $\dot{\phi}{CMB} \neq \dot{\phi}{local}$, so Hubble-parameter estimates diverge not from observational conflict but from the false assumption of a constant phase rate:
$$H_{CMB} - H_{local} \sim \Delta\dot{\phi}$$
This reframes the Hubble tension as a calibration error induced by domain-specific oscillator evolution.
------------------------------
## 08 Phase Dependence of Length, Radius, and Physical Constants
Not only time but length and every derivative quantity inherit their definitions from the local phase-accumulation rate $\dot{\phi}_{ref}$. By definition of the SI second and meter:
$$t_{local} = \frac{\phi}{\dot{\phi}{ref,local}}, \quad 1\text{ m}{local} = \frac{c_{local}}{299,792,458}\text{ s}_{local}$$
so the local meter is directly proportional to the local phase-accumulation rate: $1\text{ m}{local} \propto 1/\dot{\phi}{ref,local}$. If a gravitational potential modifies $\dot{\phi}_{ref}$, both the local second and meter shift in the same proportion, making every length scale—radii, distances, wavelengths—a phase-dependent quantity.
## Radius as an operational count
A radius is not an absolute geometric distance; it is the number of local light-travel intervals accumulated during a given proper time:
$$r_{local} = c_{local} t_{local} = \frac{c_{local}}{\dot{\phi}_{ref,local}}\phi$$
If $\dot{\phi}{ref}$ slows in a gravitational potential, the local second lengthens and $r{local}$ expands correspondingly—even though no absolute geometric change occurred. Apparent size differences between domains reflect differing local phase rates, not intrinsic geometry.
## Phase standards embedded in G and c
Because the meter and second both depend on $\dot{\phi}{ref}$, the constants $G$ and $c$ carry local phase-rate information: $G{local} \propto 1/\dot{\phi}{ref,local}^2$ and $c{local} \propto \dot{\phi}_{ref,local}$. The Schwarzschild factor $2GM/rc^2$ already carries phase dependence through every term it contains—so even the standard expression
$$\frac{d\tau}{dt} = \sqrt{1 - \frac{2GM}{rc^2}}$$
compares $d\tau$ and $dt$ across inequivalent phase standards. Every cosmological measurement that assumes universality of $G$, $c$, and the meter implicitly neglects the bias:
$$\frac{\dot{\phi}{emit}}{\dot{\phi}{obs}} = \frac{1}{1 + z_{local}}$$
## Numerical illustration
Let $\Lambda_\phi = \dot{\phi}{emit}/\dot{\phi}{obs} = 1/(1 + z_{local})$. Every quantity built from time or length rescales by a power of $\Lambda_\phi$ matching the number of seconds or meters in its dimensional structure:

| Quantity | Operational Definition | Scaling with $\Lambda_\phi$ |
|---|---|---|
| Local second, $t$ | $t = \phi/\dot{\phi}$ | $\Lambda_\phi^{-1}$ |
| Local meter, $L$ | $L = ct$ | $\Lambda_\phi^0$ |
| Frequency, $f$ | $f = d\phi/dt$ | $\Lambda_\phi^1$ |
| Speed of light, $c$ | $c = L/t$ | $\Lambda_\phi^1$ |
| Gravitational constant, $G$ | $G \sim L^3/(MT^2)$ | $\Lambda_\phi^{-2}$ |
| Radius, $r$ | $r = ct$ | $\Lambda_\phi^0$ |
| Potential factor, $2GM/(rc^2)$ | — | $\Lambda_\phi^{-4}$ |
| Energy, $E = hf$ | $E \propto f$ | $\Lambda_\phi^1$ |
| Momentum, $p = h/\lambda$ | $\lambda = c/f$ | — |

Table 1. Phase-rate scaling of representative physical quantities. The meter's definition already couples $c_{local}$ and $t_{local}$, so its numerical value is fixed within a domain but differs across domains.
Take an emitter galaxy with $z_{local} = 0.9 \implies \Lambda_\phi = 1/1.9 \approx 0.526$, and an observed total redshift $z_{total} = 12.6$. The path component is:
$$1 + z_{path} = \frac{1 + z_{total}}{1 + z_{local}} = \frac{13.6}{1.9} = 7.16$$
Using standard cosmology ($\Omega_m = 0.3, \Omega_\Lambda = 0.7$), the distance and lookback time derived from $z_{path}$ are the corrected, clock-matched quantities:

| Quantity | Standard ($z_{local} = 0$) | Phase-Corrected | Ratio/Bias |
|---|---|---|---|
| Comoving distance $D_c$ (Mpc) | 9,920 | 8,310 | 1.19$\times$ overestimate |
| Lookback time (Gyr) | 13.13 | 12.58 | +0.55 Gyr apparent age gain |
| Potential factor $2GM/(rc^2)$ | $2.0 \times 10^{-6}$ | $1.3 \times 10^{-5} \ (\times \Lambda_\phi^{-4})$ | 6.5$\times$ enhanced |
| Energy scale $E = hf$ | 1.0 (normalized) | 0.53 | 0.53$\times$ lower |

Table 2. Phase-based correction for a galaxy with $z_{local} = 0.9$. The same physical system, analyzed under mismatched phase standards, appears farther, older, and less energetic than it truly is—its apparent dimming encoding both cosmological stretching and the uncorrected phase mismatch.
Because radius and time are co-defined by the same phase standard, comparing two domains implicitly assumes $\Lambda_\phi = 1$. Relaxing that assumption reveals a hidden multiplicative bias across all derived observables, $\text{bias} = (1+z_{local})^n$, where $n$ is the number of local seconds entering the quantity's dimensional structure: $n = 1$ for frequency or energy, $n = 2$ for acceleration or gravitational terms, $n = 4$ for luminosity or surface-brightness dimming. This single scaling law unifies the apparent overestimation of distances, ages, and dimming seen in high-redshift galaxies under one operational principle: the local definition of the second.
------------------------------
## 09 Proper Time Radio Astronomy
Proper Time Radio Astronomy (PTRA) is an observational program built on this framework: it treats every atomic and molecular transition in the universe as a clock measuring local proper time, and maps subtle frequency variations across the cosmos to directly measure spacetime curvature through its effect on fundamental oscillator rates—rather than inferring gravity from matter dynamics or light deflection.
Conventional astronomy maps where matter is and infers gravity from it. PTRA maps how time flows and measures gravity directly. Where standard cosmology reads redshift as cosmic expansion, PTRA reads it as differential clock rates between cosmic domains—turning the observable universe into a network of synchronized clocks, revealing gravitational structure through temporal rather than spatial measurement.
------------------------------
## 10 Implications and Path Forward
Standard cosmology projects time across redshift as if every clock, from recombination to the present, ticks at a uniform phase rate. In physical reality, time and space are operationally defined through the local accumulation of phase cycles of a reference oscillator, and every cosmic epoch carries its own oscillator rate, set by local curvature and prevailing conditions.
By assuming a global second—and therefore a global meter—modern cosmology has embedded phase-rate differentials into its distance-redshift relations, then read those differentials back out as evidence for new physics. What currently appears as the Hubble tension and dark energy is, on this account, the shadow of a broken projection: domain-specific clocks and rulers compared under a false assumption of universality. Our cosmological distance measures are, by this construction, biased by a calibration standard that silently drifts with cosmic curvature—and the proposed remedy is not new physics, but clock-matched bookkeeping.


***

### 🛠 Quick Tips for GitHub Pages Integration
* **For Docsify/Standard Jekyll**: The mathematical equations are fully enclosed in standard `$$ ... $$` block syntax and `$ ... $` inline syntax. To make them render flawlessly on GitHub Pages, make sure your page template theme loads a parser extension like **KaTeX** or **MathJax**.
* **Tables**: The scaling matrix and calculations look exceptionally crisp inside basic markdown pipe tables, adjusting perfectly to widescreen monitors and mobile screens alike.

<FollowUp>
Let me know if you would like me to write the code for the **Docsify configuration scripts (`index.html`)** or set up a clean, customized **custom style sheet (CSS)** to accompany this file.
</FollowUp>


