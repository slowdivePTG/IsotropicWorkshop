# Cosmic reionisation

## Historical preface

- Spectra of quasars
  - Strong radio radiation
  - Strangely placed, broad emission lines - hydrogen Balmer (principle quantum number *n* → 2) series lines redshifted by 16%
  - No strong absorption blueward of Ly$\alpha$ - IGM was **highly ionised** when
    the universe was only one-quarter of its present age of 13.8 billion years
- Cosmic reionisation
  - The process in which the IGM becomes ionised and heated
  - As the first generations of galaxies form, reionisation of IGM occurs everywhere in the IGM within a billion years after the Big Bang

## Background astrophysics

### Cosmology

### Large-scale structure

- The universe is homogeneous and isotropic at scales above 300 Mpc
  but below which forms large-scale structures (clusters, filaments, walls, and voids)

- Dark matter halos - building blocks of cold dark matter (CDM) paradigm

  - Gravitationally collapsed and decoupled from the expansion of the universe - DM and gas reach equilibrium between gravitational potential and its thermal and kinetic energy

  - A spherically symmetric halo collapsing in an expanding universe to find that its mean density of $18\pi^2$ times the critical density $ρ_c$ at the collapse time
    $$
    \rho_{\mathrm{h}}=18 \pi^{2} \rho_{\mathrm{c}}(1+z)^{3}
    $$

  - Halo radius
    $$
    r_{\mathrm{h}}=\left[\frac{M_{\mathrm{h}}}{(4 \pi / 3) \rho_{\mathrm{c}}(1+z)^{3}}\right]^{1 / 3}
    $$

  - Circular velocity
    $$
    V_{\mathrm{c}}=\sqrt{\frac{G M_{\mathrm{h}}}{r_{\mathrm{h}}}}
    $$

  - Virial temperature
    $$
    T_{\mathrm{vir}}=\frac{m V_{\mathrm{c}}^{2}}{2 k_{\mathrm{b}}}
    $$

### Ionisation and recombination

$$
\ce{H + \gamma <-> H+ + e-}
$$

- Cosmological H II regions - The radiation from the first luminous objects will ionise and heat the surrounding IGM once it escapes from their host halos
- Ionisation fraction estimation - equate these two rates and solve for the ionisation fraction $x_\text{e} \equiv n_\text{e}/n_\ce{H}$ of the gas at equilibrium
  - Recombination rate
    - The rate will be proportional to the product of the number density of protons and electrons
    - The gas is pure hydrogen ($n_\text{e} = n_\ce{p}$)
    - The rate depends on the temperature and into which quantum state *n* it recombines
    - On-the-spot approximation - ignore the recombination onto the ground state

### Evolution of an H II region

- Strömgren radius $R_\rm{S}$
  - Ionisation front of an H II region around a massive star where no more flux left
  - Determined by balancing the total number of ionisations and recombinations in a region
- Evolution
  - Initial stage - a newborn star (or a galaxy) ionizes and heats the surrounding dense medium to form a highly ionized H II region *with high pressure*
  - Intermediate stage - the high-pressure region expands and shocks with the ambient medium to sweep up most of the gas in its way and *the density thus decreases*
  - Final stage - the recombination rate decreases accordingly and finally reach an equilibrium state (in hundreds of millions of years >> lifetimes of massive stars) - **final Strömgren radius**

## Ending the Cosmic Dark Ages

- Galaxies were first assembling during the epoch of reionisation
- DM halos - massive enough to support the formation of galaxies
  - Gravitational potential - deeper
  - Viral temperature - higher
- Reionisation phases
  - Pre-overlap: each galaxy produces its own H II regions, divided by IGM
  - Overlap: H II regions start to combine with each other
  - Post-overlap: Most of the IGM is ionized, leaving some 'patches' neutral

### The Dark Ages (after recombination)

- **Streaming velocity** - supersonic relative velocities between DM and gas
  - Before recombination, gas and radiation are coupled, while DM is not affected - after recombination, gas and DM have different velocities
    - $\overline{\Delta v^2}\sim30$ km/s
    - Fluctuates on comoving scales between 3 and 200 Mpc
    - Decays as $a^{-1}$
- Temperature - thermal pressure (sufficient cooling gives lower massive DM halos for galaxy formation)
  - Mean gas temperature decays as $a^{-2}$ when cooling adiabatically
  - The cosmological Jeans mass depends on the temperature - $M_\mathrm{J}\sim a^{-3/2}$

### The first stars

- Population III star

  - Metal-free
  - Massive (tens of solar mass)

- Dominant cooling mechanism - $\ce{H2}$ cooling (cooling in the formation of $\ce{H2}$ in gas phase)
  $$
  \ce{H + e- -> H- + \gamma}\\
  \ce{H- + H -> H2 + e-}
  $$

  - $\ce{H2}$ is vulnerable to photons in Lyman-Werner bands
  - $\ce{H-}$ can be destroyed through photo-detachment

- UV escape fraction - increase with stellar mass

### The first galaxies

- Dominant cooling mechanism - atomic (Ly$\alpha$) cooling
- Pre-galactic halos
  - Gas poor (gas has been blowed away)
  - Below the atomic cooling limit - bursty star formation
  - Above the atomic cooling limit - continuous star formation
- UV escape fraction
  - Radiation hydrodynamics simulations
  - Ionising radiation generally escapes in the directions with small neutral column densities - UV escape fraction can be thought as the solid angular fraction that these 'ionized channels' cover - decrease with galactic mass

### The first black holes

- Strong UV and X-ray radiation during accretion, the latter can penetrate deep into IGM to change the thermal and ionization state of IGM
- Massive Pop III stars ending with BHs may be seeds for SMBHs



## Observational constrains

- QSO. Gunn-Peterson trough indicates an elevated neutral hydrogen fraction. By observing high-z QSO with Gunn-Peterson trough, we can determine when the trough disappeared, then further determine the ending of reionisation. Btw, a tiny amount of neutral hydrogen will be optically thick enough and absorb all light at $$1216(1+z)$$ angstrom. Anyway, QSO spectra probe the end of cosmic reionisation.
- CMB. CMB photons can be scattered by free electrons (Thomson scattering). By measuring the total amount of CMB photons and calculating the total amount of CMB photos theoretically, an optical depth could be calculated. Then the time of reionisation can be worked out by assuming some reionisation models. Planck data indicates $$z=7.82\pm0.71$$ when the universe is half-ionized.
- 21-cm lines. We can define a spin temperature $$T_s = T_* \ln(3n_0 / n_1) $$, where $$T_* = E_{21}/k_B$$. This temperature depicts the distribution of states on hyperfine levels. Before everything got ionized, the spin temperature is tightly bonded with CMB temperature. Absorption and emission will change the spin temperature slightly for $$\delta T_b$$. Stars began to form after $$z\sim30$$, decrease $$\delta T_b$$. X-ray sources will increase $$\delta T_b$$. Overall, $$\delta T_b$$ would decrease to negative and smoothly converge to zero. We have observed a trough from EDGES centering at $$z\sim 18$$, indicating many interesting new physics. 