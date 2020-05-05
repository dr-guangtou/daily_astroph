# Astro-ph Notes

---- Song Huang ----

## 2020-May

----

### May 3

- [A hydrodynamical halo model for weak-lensing cross correlations](https://arxiv.org/abs/2005.00009)
  - **Relevant** 关于baryonic effect
  - We develop a cosmology-dependent model for the matter distribution that simultaneously accounts for the clustering of dark matter, gas and stars.
  - We present two variants; one that matches the feedback-induced suppression seen in the matter-matter power spectrum at the per-cent level and a second that matches the matter-matter data slightly less well (~2 per cent), but that is able to simultaneously model the matter-electron pressure spectrum at the ~15 per-cent level.
  - 将tSZ观测和lensing correlation测量功率谱结合起来

- [Euclid: The importance of galaxy clustering and weak lensing cross-correlations within the photometric Euclid survey](https://arxiv.org/abs/2005.00055)
  - **csst, ssst**
  - We aim at understanding the amount of additional information that cross-correlation can provide for parameters encoding systematic effects, such as galaxy bias or intrinsic alignments (IA).
  - We show that XC improves the dark energy Figure of Merit (FoM) by a factor ∼5, whilst it also reduces the uncertainties on galaxy bias by ∼17% and the uncertainties on IA by a factor ∼4.
  - We also show that XC can help in distinguishing between different IA models, and that if IA terms are neglected then this can lead to significant biases on the cosmological parameters.

- [Star formation and morphological properties of galaxies in the Pan-STARRS 3π survey- I. A machine learning approach to galaxy and supernova classification](https://arxiv.org/abs/2005.00155)
  - We train and test two Random Forest (RF) classifiers using photometric features (colors and moments)
  - 给出每个星系是High SF星系和是旋涡星系的概率：We show that by selecting on PHSFF or Pspiral it is possible to significantly enhance or suppress the fraction of core-collapse SNe (or thermonuclear SNe) in the sample with respect to random guessing.

- [The Fornax Deep Survey with VST. VIII. Connecting the accretion history with the cluster density](https://arxiv.org/abs/2005.00025)
  - **Relevant**
  - 19个明亮的ETG：We performed multi-component fits to the azimuthally averaged surface brightness profiles available for all sample galaxies.
  - We find that in the most massive and reddest ETGs the fraction of light in, probably accreted, halos is much larger than in the other galaxies.
  - Inside the virial radius of the cluster, the total luminosity of the intra-cluster light, compared with the total luminosity of all cluster members, is about 34%.

- [Flat Rotation Curves of z∼1 Star-Forming Galaxies and Evidence of Disk-Scale Length Evolution](https://arxiv.org/abs/2005.00279)
  - **Interesting**
  - K-band Multi-Object Spectrograph (KMOS) for Redshift One Spectroscopic Survey (KROSS): 409个0.6< z <1.0的SF星系，平均恒星质量10^10Msun
  - 3DBarolo方法提取Halpha旋转曲线：考虑beam smearing effect和压力梯度效应 (ADC方法)
  - Nearly all objects (0.1< v/σ <15) are affected by the pressure gradient, and we noticed that ADC improves the rotation velocity of these systems by ∼10−87%.  
  - We do not see any change in the shape of RCs with respect to the local star-forming disk-type galaxies. In contrast, we do find a significant evolution in the stellar-disk length (RD) of the galaxies. 

- [Galaxy Merger Rates up to z ∼ 3 using a Bayesian Deep Learning Model − A Major-Merger classifier using IllustrisTNG Simulation data](https://arxiv.org/abs/2005.00476)
  - We classify major mergers and measure galaxy merger rates up to z ∼ 3 in all five CANDELS fields (UDS, EGS, GOODS-S, GOODS-N, COSMOS) using deep learning convolutional neural networks (CNNs) trained with simulated galaxies from the IllustrisTNG cosmological simulation. 
  - We finish by demonstrating that our model is capable of measuring galaxy merger rates, that are consistent with results found for CANDELS galaxies using close pairs statistics, with R(z)=0.02±0.004×(1+z)^2.76±0.21.

----

### May 4

- [Predicting Cosmological Observables with PyCosmo](https://arxiv.org/abs/2005.00543)
  - **Useful**
  - `PyCosmo` is a Python-based framework providing solutions to the Einstein-Boltzmann equations and accurate predictions for cosmological observables

- [X-ray absorption in INTEGRAL AGN: Host galaxy inclination](https://arxiv.org/abs/2005.01028)
  - For our hard X-ray selected sample a deficit of edge-on galaxies hosting type 1 AGN is present.
  - In our hard X-ray selected sample there is a deficit of 24% (+/- 5%) of type 1 AGN.
  - Our findings clearly indicate that material located in the host galaxy on scales of hundreds of parsecs and not aligned with the putative absorbing torus of the AGN can contribute to the total amount of column density.

- [The SAMI Galaxy Survey: stellar population gradients of central galaxies](https://arxiv.org/abs/2005.00541)
  - **Relevant**
  - Stellar population radial gradients (age, metallicity and [α/Fe]) of ∼ 100 passive central galaxies up to ∼2Re.
  - We find negative metallicity radial gradients, which become shallower with increasing stellar mass. The age and [α/Fe] gradients are consistent with zero or slightly positive.
  - We do not observe a significant difference between the stellar population gradients of central and satellite galaxies, at fixed stellar mass.
  - This evidence suggests that the central region of central passive galaxies form in a similar fashion to satellite passive galaxies, in agreement with a two-phase formation scenario.

- [Dynamical Modeling of Galaxies and Supermassive Black Holes: Axisymmetry in Triaxial Schwarzschild Orbit Superposition Models](https://arxiv.org/abs/2005.00542)
  - **Relevant**
  - We show that in order to achieve (oblate) axisymmetry in a triaxial code, care needs to be taken to axisymmetrize the short-axis tube orbits and to exclude both the long-axis tube and box orbits from the orbit library
  - Using up to 12 Gauss-Hermite moments of the line-of-sight velocity distributions as constraints, we demonstrate the effects of orbit types on the best-fit MBH in orbit modeling of the massive elliptical galaxy NGC 1453 reported in Liepold et al. (2020).

- [The formation of dusty cold gas filaments from galaxy cluster simulations](https://arxiv.org/abs/2005.00549)
  - **Relevant**
  - We report a radiation hydrodynamic simulation of AGN feedback in a galaxy cluster, in which cold filaments form from the warm, AGN-driven outflows with temperatures between 10^4 and 10^7 K as they rise in the cluster core.
  - Our analysis reveals a new mechanism, which, through the combination of radiative cooling and ram pressure, naturally promotes outflows whose cooling time is shorter than their rising time, giving birth to spatially extended cold gas filaments.

- [Low Mass Group Environments have no Substantial Impact on the Circumgalactic Medium Metallicity](https://arxiv.org/abs/2005.00779)
  - Explore how environment affects the metallicity of the circumgalactic medium (CGM) using 13 low mass galaxy groups (2-5 galaxies) at ⟨zabs⟩=0.25
  - Both group and isolated CGM metallicities span a wide range (−2<[Si/H]<0), where the mean group (−0.54±0.22) and isolated (−0.77±0.14) CGM metallicities are similar.
  - Contrary to isolated galaxies, we do not find an anti-correlation between {\HI} column density and the nearest group galaxy impact parameter.
  - We conclude that either environmental effects have not played an important role in the metallicity of the CGM at this stage and expect that this may only occur when galaxies are strongly interacting or merging, or that some isolated galaxies have higher CGM metallicities due to past interactions.

- [The XXL Survey. XLI. Radio AGN luminosity functions based on the GMRT 610 MHz continuum observations](https://arxiv.org/abs/2005.01162)
  - GMRT 610MHz XXL-North巡天，30.4 deg^2, 6.5 arcsec beam size
  - The multi-component sources were matched visually with the aid of a computer code: Multi-Catalog Visual Cross-Matching (MCVCM).
  - We constructed the rest-frame 1.4 GHz radio luminosity functions of these sources using the maximum volume method. This survey allows us to probe luminosities of 23≲log(L1.4 GHz[W/Hz])≲28 up to redshifts of z≈2.1.

- [Dynamical evidence of the sub-parsec counter-rotating disc for a close binary of supermassive black holes in the nucleus of NGC 1068](https://arxiv.org/abs/2005.01220)
  - 关于ALMA在NGC1068中心0.2-7 pc处看到的逆向旋转的盘：we find that the Kelvin-Helmholtz (KH) instability (KHI) results in an unavoidable catastrophe of the disc developed at the interface between the reversely rotating parts, and demonstrate that a close binary of supermassive black holes provides tidal torques as the unique external sources to prevent the disc from the KH catastrophe.
  - 作者认为中心一定有双黑洞:the KHI leads to an efficient annihilation of the orbital angular momentum and speed up merge of the binary, providing a new paradigm of solving the long term issue of "final parsec problem".

- [The Next Generation Fornax Survey (NGFS): VII. A MUSE view of the nuclear star clusters in Fornax dwarf galaxies](https://arxiv.org/abs/2005.01532)
  - **Relevant**
  - This work presents the analysis of the NSCs in a sample of 12 dwarf galaxies in the Fornax Cluster observed with MUSE.
  - 有多星族的证据；金属丰度普遍比host星系低 which is consistent with a scenario for mass-assembly through mergers with infalling globular cluster
  - We conclude that the NSCs in these dwarf galaxies likely originated as globular clusters that migrated to the core of the galaxy which have built up their mass mainly through mergers with other infalling clusters, with gas-inflow leading to in-situ star formation playing a secondary role.