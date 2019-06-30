### [An introduction to astrophysical observables in gravitational wave detections](https://arxiv.org/abs/1906.03643)

1. Introduction

   - GW170817 (double NS) provides clues for the formation of elements heavies than iron (gold and platinum observed in the spectrum). It is also accompanied by a short GRB.
   - GW only transfers very small amount of energy, hence it can penetrate very dense matter field.

2. Long story short

   - The maximum observed NS is 2.1 solar mass. How did they form if single degenerate SN model is correct and Chandrasekhar is total right.
   - NS is not totally made of neutron. It has lighter elements and iron (predominate) on the surface, and then heavier elements with more neutron, and then compact exotic matter (strange quark matter? [@xrx](http://www.phy.pku.edu.cn/~xurenxin/index.html)) The EoS of NS has not been understood yet.
   - A rotating BH comes from stellar collapse which has non-zero angular momentum before collapsing. There are many problems related to BH which remain mysteries now: mass function, mid-mass BH, etc.

3. Ground-based laser interferometers

   - After the failure of Weber bar and knowing that strain from astronomical events is of magnitude of $$h\sim 10^{-22}$$, people began to build interferometers, including LIGO (USA, 4-km), Virgo (France and Italy, 3-km) and GEO (UK and Germany). More will be built in the near future (LISA, Tianqin, DECIGO, etc.)
   - The interferometers are set up to make the interference destructive at the photodetector. Note that interferometer is only sensible to strain ($$h\sim 1/r$$), not to radiation power ($$P\sim1/r^2$$).
   - LIGO is built to be sensitive in 20-20000 Hz, the noises are dominated by seismic on low-frequency end and quantum effects on high-frequency end. 
   - Optical system makes use of "Fabry-Perot cavities" to increase the distance light travels and "power recycling mirrors" to increase the power of laser light. LIGO uses 1064 nm infrared laser with ~40 W power. Mirrors are well designed, they only absorb one photon out of 300,000 photons, avoiding mirror heating, which could change the shapes of mirrors.
   - The test masses are suspended by a passive damping system. LIGO also uses active (and kind of adaptive) damping system to fight against human-generated vibrations.

4. Double BH merger: GW150914

   - GW150914 is the first GW event detected by human!! A brand new era of astrophysics started!
   - LIGO people generate 250000 templates based on post-Newtonian and numerical relativity to fit the detected signals. Templates range from 1 solar mass to 90 solar masses. The S/N of GW150914 is 24.
   - Based on Newtonian mechanics, during the inspiral process, we could estimate the chirp mass by $$\omega$$ and $$\dot{\omega}$$. And it turns out $$\mathcal{M} \sim 30 M_\odot$$. The coalescence stage begins when the Schwarzchild radius of two BHs contact with each other. For GW150914 the coalescence begins at $$\nu\sim 330\ \text{Hz}$$, so the total mass of two BHs can be estimated $$M\sim 70 M_\odot$$. Given chirp mass and total mass, the mass of two BH can be worked out:  $$m_1^{obs} = 42M_\odot,\ m_2^{obs} = 28 M_\odot$$.
   - The flux and total luminosity of binary BH merger can be given by GR. Hence we could derive the luminosity distance for this event $$D_L = 400\ \text{Mpc}$$. If we know the redshift (say from possible EM counterpart), we could yield a Hubble constant. Also, given this luminosity distance and LCDM cosmology, the redshift $$z\sim 0.1$$. Notice that cosmological effects (redshift and time dilution) affect the measurement of mass. In source coordinate, the mass is $$m = m^{obs} / (1+z)$$. 
   - GW150914 emits 4 solar mass energy within a tenth of second, however our sun emits 0.01 solar mass in 10 Gyr.
   - After the ringdown process, a Kerr BH will be formed. Notice that a Kerr BH has smaller horizon area than a Schwarzchild BH of the same mass. Hence Kerr BH is more compact. The study of Kerr BH after ringdown could give us insights to strong field regime of gravity and further inspection of the validity of GR.
   - The sky location resolution of LIGO is $$\Delta \theta = \lambda / L \sim 28^{\circ}$$ for this event.

5. GW170817, GRB170817A, AT 2017gfo

   - Respectively - the GW event, the gamma-ray burst 1.7 s later, the afterglow in different wavelengths (kilonova).
   - GW170817 - toward the end of the data run of O2 of aLIGO and aVirgo
     - NS binary - produce a GW signal observable by **ground-based** detectors in the final minutes before the massive objects collide.
       - Detection rate for advanced detectors (per year) - $\mathcal{O}(0.1)\sim\mathcal{O}(100)$ (astrophysical uncertainty).
       - First indirect observation of GW - **the Hulse and Taylor pulsar**.
     - Position localization - 28 deg$^2$ (purely GW signal restriction).
     - Again, the chirp mass $\mathcal{M}$ ($\sim1.1\ M_\odot$ in the source frame and $\mathcal{M}^{d e t}=1.1977 M_{\odot}$ in the detectors frame when $z=0.008$ which) and the radius $R$ of the system are directly determined by observed $\omega$ and $\dot\omega$ during the inspiral phase. The amplitude $h$ is $\sim10^{-22}$ so we can derive a luminosity distance and redshift, which are consistent with the known results of NGC 4993
     - As $R$ approaches the size of the bodies, PN theory is no longer valid, relativistic effects related to the mass ratio $q=m_2/m_1$ (where $m_2>m_1$) as well as spin-orbit and spin-spin couplings become more significant. The derived chirp mass $\mathcal{M}$ differs from values at early times, which means the details of the objects' internal structure become important.
     - Individual masses are more difficult to determined. By assuming high/low spins, the masses of both objects are approximately $1.4M_\odot$.
     - The inclination of the system $\Theta \leq 28^{\circ}$.
     - Tidal effects are important for NS binaries (not important for BHs because they are **bald** as astronomers always do) especially when the two objects get really close, which corresponds to a high frequency $\nu_{g w} \simeq 600\ \mathrm{Hz}$. This is at present too hard for a ground-base interferometer to achieve, but once it is detected, we would gain a better understanding of the EoS of a NS.
     - The final state depends on individual masses. It can be a NS with a torus, a supra-massive/hypermassive NS which turns into a BH with a torus soon, or directly a BH with a torus.
   - GRB170817A - the prompt emission is attributed to internal energy dissipation inside a relativistic jet (**relativistic expanding fireballs**)
     - Short GRB ($\Delta t \leq 2\ \mathrm{s}$) - first direct observation evidence.
     - 1.7 s later than the GW, which is consistent with models of NS mergers
     - The luminosity assuming an isotropic radiation is $\sim 4 \times 10^{46} \text { erg}$, which three orders of magnitude lower than a typical short GRB - a beamed emisson
   - AT 2017gfo - afterglow of GRB170817A caused by forward shocks propagating in the surrounding ambient material and the related elemental decays
     - Atoms heavier than $\ce{Fe}$ are now able to form in *r-process*, where an atom captures neutrons *rapidly* enough to exceed the decay of neutrons. The complex absorption lines come from these new atoms.
     - The newly formed atoms then decay to emit thermal radiation, which leads to the afterglow.
     - By assuming all heavy atoms come from NS mergers and applying the heavy elements producing rate of AT 2017gfo ($\sim 0.05M_\odot$), we can estimate the event rate of (detectable) NS mergers, which is of $\mathcal{O}(1)\sim\mathcal{O}(10)$ within $\sim200$ Mpc. If too many similar events are detected, some refinements regarding the theoretical models would be necessary. If we are not able to detect such events that much, other mechanisms of heavy elements production may also be important.

6. Astrophysics of stellar BHs after GW150914

   Until now we have detected a couple dozens of BH mergers. They are typically more massive that our past observed BHs (typically X-ray binaries). This challenges the formation theories of stellar mass BHs. We also observed a gap in the BH mass spectrum between 2.5 solar mass (below which are all neutron stars) and 5 solar mass. Also, we don't find many intermediate-mass BHs.

