# gc_model_mw

This is a mock catalog of globular clusters calculated with a model for the formation and evolution of globular cluster systems. This catalog and the current version of the model are published in [Chen & Gnedin (2023b)](https://arxiv.org/abs/2309.13374). It is based on the earlier versions developed in [Muratov & Gnedin (2010)](https://ui.adsabs.harvard.edu/abs/2010ApJ...718.1266M/abstract), [Li & Gnedin (2014)](https://ui.adsabs.harvard.edu/abs/2014ApJ...796...10L/abstract), [Choksi et al. 2018](https://ui.adsabs.harvard.edu/abs/2018MNRAS.480.2343C/abstract),
[Choksi & Gnedin 2019a](https://ui.adsabs.harvard.edu/abs/2019MNRAS.486..331C/abstract),
[Choksi & Gnedin 2019b](https://ui.adsabs.harvard.edu/abs/2019MNRAS.488.5409C/abstract),
[Chen & Gnedin (2022)](https://ui.adsabs.harvard.edu/abs/2022MNRAS.514.4736C/abstract),
[Chen & Gnedin (2023a)](https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.5638C/abstract).

The catalog matches the observed mass function, radial and velocity dispersion profiles, and the age-metallicity distribution (as much as possible) of the globular cluster systems in the MW and M31. The spatial and kinematic information is based on tagging particles from the [Illustris TNG50 simulation](https://www.tng-project.org/data/downloads/TNG50-1/) or the [Local Group simulation](https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.5638C/abstract).

The catalog of clusters remaining gravitationally bound to redshift $z=0$ provides the information on cluster age, mass at formation and at $z=0$, Cartesian coordinates and velocities at $z=0$, orbital actions in the best-fitting halo+disk galaxy potential, apocenter and pericenter radii, value of the potential, cluster iron metallicity, total and stellar mass of host galaxy at formation, and total and stellar mass of host galaxy at $z=0$. The catalog also contains tags `host_id_form` and `host_id_accrete` to mark clusters formed in the central halo (_in-situ_) and in satellite galaxies (_ex-situ_), and gives the time of accretion for the _ex-situ_ clusters.

The catalog of disrupted clusters contains also the time of disruption. The coordinates and other orbital information is for the center of mass of the resulting stellar stream. The model generates clusters with a minimum initial mass of $10^4$ Msun. Less massive clusters are expected to be disrupted by the present time.

The MW catalog contains 3 systems most resembling the Milky Way in their mass assembly history and in the properties of the GC system. Each galaxy provides an alternative possible history of the assembly of the MW globular cluster system. GC systems can be analyzed for all 3 galaxies combined, or for each galaxy separately.

The M31 catalog similarly contains 3 systems most resembling the Andromeda galaxy in their mass assembly history and in the properties of the GC system. Each galaxy provides an alternative possible history of the assembly of the M31 globular cluster system. The adjustable model parameters are the same as for the MW catalog.

The source code of the model is available in [this repository](https://github.com/ybillchen/GC_formation_model).
