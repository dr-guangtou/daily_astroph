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

----

### May 5

- [Orphan GRB afterglow searches with the Pan-STARRS1 COSMOS survey](https://arxiv.org/abs/2005.01730)
  - There is extensive theoretical and observational evidence suggesting that GRBs are collimated jets; the direct observation of orphan GRB afterglows would further support this model.
  - 目前的极限星等是R~23, 然后用HSC找host，可以做到R~26 mag
  - 目前没有找到：The null result implies that the consideration of jet structures is essential for further orphan GRB afterglow surveys.

- [High-resolution, 3D radiative transfer modelling IV. AGN-powered dust heating in NGC 1068](https://arxiv.org/abs/2005.01720)
  - DustPedia: detailed, 3D radiative transfer simulations of face-on spiral galaxies
  - 看AGN对尘埃的影响：We find a strong wavelength dependency of AGN contamination to the broadband fluxes. It peaks in the MIR, drops in the FIR, but rises again at submm wavelengths.
  - The AGN contribution is measurable at the percentage level in the disc, but quickly increases in the inner few 100 pc, peaking above 90%.

- [Massive disc galaxies in cosmological hydrodynamical simulations are too dark matter-dominated](https://arxiv.org/abs/2005.01724)
  - **Relevant**
  - 比较EAGLE和IllustrisTNG与SPARC比较：the simulated discs inhabit halos that are a factor ~4 (in EAGLE) and ~2 (in IllustrisTNG) more massive than those derived from the rotation curve analysis of the observed dataset.
  - We also use synthetic rotation curves of the simulated discs to demonstrate that the recovery of the halo masses from rotation curves are not systematically biased
  - 可能还是因为Feedback导致的问题，盘星系恒星形成效率太低

- [Probing the AGN Unification Model at redshift z ∼ 3 with MUSE observations of giant Lyα nebulae](https://arxiv.org/abs/2005.01732)
  - We use the morphology of giant Lyα nebulae around AGNs at redshift z∼3 to probe AGN emission and therefore the validity of the AGN unification model at this redshift.
  - 19个Type-I AGN周围的，4个Type-II周围的Lya星云：Type-II周围的在30 pkpc之外更在不对称
  - We discuss how the lack of asymmetry in the inner parts (r≲30 pkpc) and the associated high values of the HeII to Lyα ratios in these regions could indicate additional sources of (hard) ionizing radiation originating within or in proximity of the AGN host galaxies.

- [ALMACAL VII: First Interferometric Number Counts at 650 μm](https://arxiv.org/abs/2005.01733)
  - We present interferometric 650μm submillimetre number counts. Using the Band 8 data from the ALMACAL survey, we have analysed 81 ALMA calibrator fields together covering a total area of 5.5~arcmin2.
  - Using a signal-to-noise threshold of 4.5σ, we find 21 dusty, star-forming galaxies with 650μm flux densities of ≥0.7mJy. At the detection limit we resolve ≃100 per cent of the CIB at 650μm
  - We have therefore identified all the sources contributing to the EBL at 650 microns and predict that the contribution from objects with flux 0.7< mJy will be small.

- [Star Formation in Massive Galaxies at Redshift z∼0.5](https://arxiv.org/abs/2005.01738)
  - **Relevant**
  - z=0.5的>10^11.3 Msun的星系，用u-z颜色看SF：20%有SF，其中大部分都有不对称结构，可能有并合引起; 越不对称，颜色越蓝
  - We find two blue and symmetric galaxies, candidates for massive blue disks, in our observed sample, which indicates that about ∼10% of massive SF galaxies are forming stars in the normal mode of disk star formation

- [New Methods for Identifying Lyman Continuum Leakers and Reionization-Epoch Analogues](https://arxiv.org/abs/2005.01734)
  - 用模拟看low-z Lya Leaker是不是真的和高红移星系很像：We find that the simulated galaxies with high LyC escape fractions (fesc) often exhibit high O32 and populate the same regions of the R23-O32 plane as z∼3 LyC leakers.
  - Viewing angle, metallicity, and ionisation parameter can all impact where a galaxy resides on the O32-fesc plane
  - We find that identifying low-redshift galaxies based on [SII] deficiencies does not seem to produce true analogues.
  - We show that our model using only [CII]158μm and [OIII]88μm can identify potential leakers from non-leakers from the local Dwarf Galaxy Survey.

- [The MOSDEF Survey: the Variation of the Dust Attenuation Curve with Metallicity](https://arxiv.org/abs/2005.01742)
  - We constrain the shape of the attenuation curve by comparing the average flux densities of galaxies sorted into bins of dust obscuration using Balmer decrements
  - 大质量，高金属丰度的符合Calzetti law; 2176A bump强度是银河系的一半左右
  - 低金属丰度星系的消光曲线中没有看到2175 bump：缺少小尘埃颗粒 (?) 和SMC类似
  - 对低金属丰度星系，星云气体消光一般是恒星成分消光的2倍左右；高金属丰度星系中无差别

- [Implications of the mild gas motion found with Hitomi in the core of the Perseus cluster](https://arxiv.org/abs/2005.01883)
  - **Relevant, Interesting**
  - Through (magneto)hydrodynamic and gravitational channels, the moving galaxies are expected to drag the ICM around them, and transfer to the ICM some fraction of their dynamical energies on cosmological time scales.
  - Further assuming that the energy lost by the galaxies is first converted into ICM turbulence and then dissipated, this picture can explain the subsonic and uniform ICM turbulence
  - The scenario may also explain several other unanswered problems regarding clusters of galaxies, including what prevents the ICM from the expected radiative cooling, how the various mass components in nearby clusters have attained different radial distributions, and how a thermal stability is realized between hot and cool ICM components that co-exist around cD galaxies.

- [Examining supernova events in Type 1 active galactic nuclei](https://arxiv.org/abs/2005.02052)
  - A statistical study of intermediate Palomar Transient Factory supernovae (SNe) in Type 1 AGN has shown a major deficit of supernovae around Type 1 AGN host galaxies, with respect to Type 2 AGN hosts. (What?)
  - The findings are supportive of a deficiency of SNe near Type 1 AGN, although we cannot with certainty assess the overall detection fractions of SNe in Type 1 AGN relative to other SN host galaxies
  - Type 1 AGN has equal detection fractions of thermonuclear vs core-collapse SNe. However, we note the possibility of a higher detection rate of core-collapse supernovae in Type-1 AGN with insecure AGN classifications.

- [Atomic Hydrogen Clues to the Formation of Counterrotating Stellar Discs](https://arxiv.org/abs/2005.02355)
  - Interferometric HI observations of six double-disc stellar counterrotator ("2σ") galaxies from the Atlas3D sample.
  - This is the first direct evidence that a double-disc stellar counterrotator could be formed through the accretion of retrograde gas. However, the dominant formation pathway for the formation of 2σ galaxies is still unclear.

- [An obscured AGN population hidden in the VIPERS galaxies: identification through spectral energy distribution decomposition](https://arxiv.org/abs/2005.02361)
  - We aim to identify the obscured AGN population in the VIPERS survey in the CFHTLS W1 field through SED modelling. We construct SEDs for 6,860 sources and identify 160 AGNs at a high confidence level using a Bayesian approach.
  - Our AGN sample is highly complete (~92%) compared to mid-IR colour selected AGNs, including a significant number of galaxy-dominated systems with lower luminosities. In addition to the lack of X-ray emission (80%), the SED fitting results suggest that the majority of the sources are obscured.
  - Interestingly, only 35% of the most luminous mid-IR selected AGNs have X-ray counterparts suggesting strong absorption.