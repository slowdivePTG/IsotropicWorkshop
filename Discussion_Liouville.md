### [Applying Liouville’s Theorem to Gaia Data](http://arxiv.org/abs/1907.00987)

1. Introduction

   **Galactic archaeology** 

   - Investigating 'former blocks' of the MW (former dwarf galaxies and global clusters)
   - The internal stellar dynamics of MW satellite systems depends strongly on the distribution of dark matter in these substructures and should therefore provide stronger constraints on the physics and nature of dark matter.

   - Most of these 'building blocks' were or are being *tidally disrupted* by the Galaxy, taking objects that were initially *compact* in position-space and distributing their mass throughout the Milky Way.

   - Tidal debris and substructures are no longer gravitationally bound and are therefore dispersed in position-space, so most techniques for mass measurement are not applicable:

     - Rotational curves
     - Virial theorem

     and the conservation laws are not valid either, for both the disrupting system and the disrupter have to be taken into account.

   **Liouville theorem**

   In adiabatic processes, the phase-space density $f$ is conserved
   $$
   \frac{d f(\vec{w})}{d t}=0
   $$
   where $\vec{\omega}$ is a six-dimensional set of canonical coordinates and momenta.

   - For mergers of smaller halos ($< \mathcal{O}(0.1)$ of the MW mass), the mergers are adiabatic

   - The total phase-space volume of a gravitationally bound relaxed system is related to the total mass ($V_{6} \propto M^{3 / 2}$) - from the phase-space density of a tidally disrupted system, we can derive the configuration of the original gravitationally bound system, including mass

   - Details

     - In a set of tracer star, the phase-space density of each remains the same

     - The density distribution $f(\vec\omega,\vec\xi)$ depends on certain scalar parameters $\vec\xi$ , including total mass, scale lengths and profile shapes (NFW or King)

     - Given certain parameter $\vec\xi$, the possibility of measuring each $f_i$ ($P_i(f_i|\vec\xi)$) can be derived

     - By minimizing the negative log-likelihood (varying unknown components of $\vec\xi$ on the support of $P_i$)
       $$
       \lambda(\vec{\xi})=-2 \sum_{i} \ln P_{i}\left(f_{i} | \vec{\xi}\right)
       $$
       we can obtain estimates of $\vec\xi$

   - Entropy

     - Inevitable realities of measurement errors and uncertainty in the stellar orbits act as injections of **entropy** into the system, which will completely swamp the phase space measurement
       - Decrease the phase-space density
       - Increase the phase-space volume
       - Can be corrected for

2. Phase Space Volume and Mass

   According to the methods explained above, they first calculated the mass of Global Cluster M4 assuming *no errors in measurements*

   - Measurements: spatial position, proper velocity
   - Assumptions: spherical symmetry, King profile

3. Entropy from Measuremant Errors

4. Entropy from Orbital Errors



