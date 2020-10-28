# Astro-ph Notes

---- Song Huang ----

## 2020-October

----

### Oct 1

- [Can galaxy evolution mimic cosmic reionization?](https://arxiv.org/abs/2010.00023)
    - LAE在z>6的下降是否是再电离的影响。其中一个重要假设是星系本身在这阶段演化不大
    - 如果星系内的HI气体随红移增加，或者外流强度随红移下降，都可以模仿出这种效果；但可以通过Lya线的特征来区分
    - Using the CANDELSz7 survey measurements which indicate slightly broader lines at z∼6, we can rule out the scenario of a mere increase in the galactic column density towards higher z. We also show that a decrease in outflow velocity is not ruled out by existing data but leads to more prominent blue peaks at z>6.

- [Line confusion in spectroscopic surveys and its possible effects: Shifts in Baryon Acoustic Oscillations position](https://arxiv.org/abs/2010.00047)
    - Misidentifying Hβ emitter as [O III] emitter will cause a shift in the inferred radial position of the galaxy by approximately 90 Mpc/h. This length scale is similar to the Baryon Acoustic Oscillation (BAO) scale and could shift and broaden the BAO peak, possibly introduce errors in determining the BAO peak position.

- [Tightening weak lensing constraints on the ellipticity of galaxy-scale dark matter haloes](https://arxiv.org/abs/2010.00311)
    - **Relevant**
    - we combine data from five surveys (NGVSLenS, KiDS/KV450, CFHTLenS, CS82, and RCSLenS) in order to tighten observational constraints on galaxy-scale halo ellipticity for photometrically selected lens sample
    - fh , the average ratio between the aligned component of the halo ellipticity and the ellipticity of the light distribution, finding fh=0.303+0.080−0.079 for red lenses and fh=0.217+0.160−0.159 for blue lenses
    - Our measurements imply an average dark matter halo ellipticity for the studied red galaxy samples of ⟨|ϵh|⟩=0.174±0.046, where |ϵh|=(1−q)/(1+q) relates to the ratio q=b/a of the minor and major axes of the projected mass distribution.

- [Galaxy clustering in the Legacy Survey and its imprint on the CMB](https://arxiv.org/abs/2010.00466)
    - Cross-correlation of the tomographic galaxy maps with Planck maps of temperature and lensing convergence probe the growth of structure since z=0.8
    - Within ΛCDM, our low amplitude for the lensing cross-correlation requires a reduction either in fluctuation normalization or in matter density compared to the Planck results, so that Ω0.78mσ8=0.297±0.009.

- [A significant excess in major merger rate for AGNs with the highest Eddington ratios at z<0.2](https://arxiv.org/abs/2010.00022)
    - Using ESO VLT/FORS2 B-, V- and color images, we examine the morphologies of 17 galaxies hosting AGNs with Eddington ratios >0.3, and 25 mass- and redshift-matched control galaxies.
    - With a best estimate of 0.41 ± 0.12 for the AGN host galaxies and 0.08 ± 0.06 for the inactive galaxies our results imply that our AGN host galaxies have a significantly higher merger rate
    - We conclude that although major mergers are an essential mechanism to trigger local high Eddington ratio AGNs at z<0.2, the origin of >=50% of this specific AGN subpopulation still remains unclear.

- [A new high-precision strong lensing model of the galaxy cluster MACS J0416.1-2403](https://arxiv.org/abs/2010.00027)
    - MUSE观测：We spectroscopically identify 182 multiple images from 48 background sources at 0.9< z<6.2, and 171 cluster member galaxies.
    - 能更好的给出SF clumps的位置：By defining a new metric, which is sensitive to the gradients of the deflection field, we show that we can accurately reproduce the positions of these star-forming knots despite their vicinity to the model critical lines.
    - The high signal-to-noise spectra of the MDLF enables the measurement of the internal velocity dispersion of 64 cluster galaxies, down to m(F160W)=22. This allows us to independently estimate the contribution of the subhalo mass component of the lens model from the measured Faber-Jackson scaling relation

- [A novel black-hole mass scaling relation based on Coronal lines and supported by accretion predictions](https://arxiv.org/abs/2010.00075)
    - 用发射线比： [Si VI] 1.963 micron/Brγbroad 建立黑洞质量的标度关系; 和黑洞质量有反相关
    - we believe that a key parameter driving this anti-correlation is the effective temperature of the accretion disc, this being effectively sampled by the coronal line gas. 吸积盘温度与黑洞质量的-1/4次方成比例

- [The Faint End of the Quasar Luminosity Function at z∼5 from the Subaru Hyper Suprime-Cam Survey](https://arxiv.org/abs/2010.00481)
    - HSC-Wide中用Lyman-break挑选的z~5 QSO：we derived the quasar luminosity function at z∼5 covering a wide luminosity range of −28.76<M1450<−22.32 mag.
    - The inferred number density of low-luminosity quasars is lower, and the derived faint-end slope, −1.22+0.03−0.10, is flatter than those of previous studies at z∼5.

----

### Oct 4

- [Self-calibration of weak lensing systematic effects using combined two- and three-point statistics](https://arxiv.org/abs/2010.00614)
    - We investigate the prospects for using the weak lensing bispectrum alongside the power spectrum to control systematic uncertainties in a Euclid-like survey.
    - Varying all three systematics simultaneously, a joint power spectrum and bispectrum analysis reduces the area of credible regions for the cosmological parameters Ωm and σ8 by a factor of 90
    - We also demonstrate that including the bispectrum self-calibrates all three systematic effects to the stringent levels required by the forthcoming generation of weak lensing surveys, thereby reducing the need for external calibration data.

- [The CAMELS project: Cosmology and Astrophysics with MachinE Learning Simulations](https://arxiv.org/abs/2010.00619)
    - CAMELS is a suite of 4,233 cosmological simulations of (25 h−1Mpc)3 volume each: 2,184 state-of-the-art (magneto-)hydrodynamic simulations run with the AREPO and GIZMO codes 重子物理采用了TNG和SIMBA的模型
    - We show that the IllustrisTNG and SIMBA suites produce roughly similar distributions of galaxy properties over the full parameter space but significantly different halo baryon fractions and baryonic effects on the matter power spectrum.
    - 对探索ML在宇宙学里的应用很有帮助

- [Pix2Prof: fast extraction of sequential information from galaxy imagery via deep learning](https://arxiv.org/abs/2010.00622)
    - **Relevant, Useful**
    - "Pix2Prof", a deep learning model that eliminates manual steps in the measurement of galaxy surface brightness (SB) profiles.
    - 把从星系图像中获取profile的过程与给图片加caption等同起来，在SDSS图像上测试，效率很高

- [Wide-field ultra-narrow-bandpass imaging with the Dragonfly Telephoto Array](https://arxiv.org/abs/2010.00686)
    - Dragonfly Filter-Tilter, a device which places ultra-narrow bandpass interference filters (Δλ≈1 nm) in front of each of the lenses that make up the array.
    - The filters are at the entrance pupil of the optical system, rather than in a converging beam, so their performance is not degraded by a converging light cone.
    - By tilting the filters, the central wavelength of the transmission curve can be tuned over a range of 7 nm, corresponding to a physical distance range of about 20 Mpc of extragalactic targets.

- [The Lyman Continuum Escape Survey: Connecting Time-Dependent [OIII] and [OII] Line Emission with Lyman Continuum Escape Fraction in Simulations of Galaxy Formation](https://arxiv.org/abs/2010.00592)
    - 模拟研究：we find that the largest fesc values occur at elevated O32∼3−10 and that the combination of high fesc and low O32 is extremely rare. 但是O32和fesc之间并不一定有因果联系,large O32 does not necessarily imply efficient Lyman continuum escape.
    - Large O32 values fluctuate on short (∼1 Myr) timescales during the Wolf-Rayet-powered phase after the formation of star clusters, while channels of low absorption are established over tens of megayears by collections of supernovae.

- [Space Telescope and Optical Reverberation Mapping Project. XII. Broad-Line Region Modeling of NGC 5548](https://arxiv.org/abs/2010.00594)
    - We find an extended disk-like Hβ BLR with a mixture of near-circular and outflowing gas trajectories, while the C IV and Lyα BLRs are much less extended and resemble shell-like structures.
    - 三条线给出的SMBH质量是一致的；且V  band is a suitable proxy for the ionizing continuum when exploring the BLR structure and kinematics.

- [HOLISMOKES -- IV. Efficient Mass Modeling of Strong Lenses through Deep Learning](https://arxiv.org/abs/2010.00602)
    - We train a CNN on images of galaxy-scale lenses to predict the parameters of the SIE mass model (x,y,ex,ey, and θE).
    - Our CNN is able to predict the SIE parameters in fractions of a second on a single CPU and with the output we can predict the image positions and time delays in an automated way, such that we are able to process efficiently the huge amount of expected lens detections in the near future.

- [Biases and Cosmic Variance in Molecular Gas Abundance Measurements](https://arxiv.org/abs/2010.00609)
    - 目前的mm-波高红移CO巡天的视场都很小：fields ≲10 arcmin2 alter the recovered shape of the luminosity function, causing underestimates of the number of bright objects. Our models suggest that current surveys are sensitive enough to detect sources responsible for approximately half of the cosmic molecular gas density at high redshift.
    - As a result, the field size needed to detect redshift evolution in the molecular gas at high confidence may be more than an order of magnitude larger than what current surveys

- [Tracing Dark Matter Halos with Satellite Kinematics and Central Stellar Velocity Dispersion of Galaxies](https://arxiv.org/abs/2010.00693)
    - **Relevant**
    - SDSS中挑选的isolated和satellite星系，分成red和blue，看速度弥散度的标度关系：The central stellar velocity dispersions of the primary galaxies are proportional to the luminosities and stellar masses of the same galaxies. Stacking the sample based on the central velocity dispersion of the primary galaxies, we derive velocity dispersions of their satellite galaxies, which trace dark matter halo mass of the primary galaxies.
    - 星系周围的卫星星系的运动学与中心星系的速度弥散度关系很好: his tight relation suggests that the central stellar velocity dispersion of galaxies is indeed an efficient and robust tracer for dark matter halo mass.

- [RAiSERed: radio continuum redshifts for lobed AGNs](https://arxiv.org/abs/2010.00790)
    - 未来射电巡天发现的大部分射电星系都没有红移，本文提出一种只需要射电数据测红移的方法：our algorithm uses the lobe flux density, angular size and width, and spectral shape to derive probability density functions for the most likely source redshift based on the Radio AGN in Semi-analytic Environments (RAiSE) dynamical model.
    - We find that upper bounds on the angular size, as expected for unresolved sources, are sufficient to yield accurate redshift measurements at z > 2.

- [Deep Learning for Line Intensity Mapping Observations: Information Extraction from Noisy Maps](https://arxiv.org/abs/2010.00809)
    - 以SPHEREx为目标进行的模型训练：We develop conditional generative adversarial networks (cGANs) that extract designated signals and information from noisy maps.
    - The overall reconstruction performance depends on the pixel size and on the survey volume assumed for the training data.

- [Spectral energy distributions of dust and PAHs based on the evolution of grain size distribution in galaxies](https://arxiv.org/abs/2010.00922)
    - Based on a one-zone evolution model of grain size distribution in a galaxy, we calculate the evolution of infrared spectral energy distribution (SED), considering silicate, carbonaceous dust, and polycyclic aromatic hydrocarbons (PAHs).
    - 模型的主要参数是星际辐射场强度，恒星形成时标，以及ISM中致密气体的比例
    - 星系演化早期的尘埃颗粒尺寸较大，SED中的MIR成分较弱；At an intermediate stage (t∼1 Gyr for τSF=5 Gyr), the MIR emission grows rapidly because the abundance of small grains increases drastically by the accretion of gas-phase metals.
    - We find that small ηdense (i.e. the ISM dominated by the diffuse phase) is favoured to reproduce the 8 μm intensity dominated by PAHs both for the nearby and the z∼2 samples.

- [Mass-Velocity Dispersion Relation in HIFLUGCS Galaxy Clusters](https://arxiv.org/abs/2010.00992)
    - **Relevant**
    - HIghest X-ray FLUx Galaxy Cluster Sample (HIFLUGCS): measure the spatially resolved, line-of-sight velocity dispersion profiles of these clusters, which we find to be mostly flat at large radii, reminiscent of the rotation curves of galaxies.
    - Discover a tight empirical relation between the baryonic mass Mbar and the flat velocity dispersion σ of the member galaxies, i.e. MVDR
    - The residuals of the MVDR are uncorrelated with other cluster properties like temperature, cluster radius, baryonic mass surface density, and redshift.

----

### Oct 5

- [Dark Energy Survey Year 1 Results: Cosmological Constraints from Cluster Abundances, Weak Lensing, and Galaxy Correlations](https://arxiv.org/abs/2010.01138)
    - **Important**
    - 联合宇宙学限制： From a joint analysis of cluster abundances, three cluster cross-correlations, and auto correlations of galaxy density, we obtain Ωm=0.305+0.055−0.038 and σ8=0.783+0.064−0.054.
    - We thus combine cluster abundances and all two-point correlations from three cosmic tracer fields and find improved constraints on cosmological parameters as well as on the cluster observable--mass scaling relation.

- [On the "Lensing is Low" of BOSS Galaxies](https://arxiv.org/abs/2010.01143)
    - **Relevant**
    - Halo Occupation Distribution (HOD) modelling of the SMF, clustering, and lensing of BOSS LOWZ and CMASS samples at Planck cosmology. 对central和satellite星系用不同方式处理
    - The best-fitting HOD successfully describes all three observables without over-predicting the small-scale lensing signal. This indicates that the model places BOSS galaxies into dark matter halos of the correct halo masses, thereby eliminating the discrepancy in the one-halo regime where the signal-to-noise of lensing is the highest. 1Mpc/h以内的lensing is low可以被正确的模型解决
    - The observed lensing amplitude above 1 Mpc/h remains inconsistent with the prediction, which is however firmly anchored by the large-scale galaxy bias measured by clustering at Planck cosmology.

- [Determination of the Local Hubble Constant from Virgo Infall Using TRGB Distances](https://arxiv.org/abs/2010.01364)
    - A new determination of H0 using velocities and Tip of the Red Giant Branch (TRGB) distances to 33 galaxies located between the Local Group and the Virgo cluster. We obtain H0= 65.9 ± 3.5(stat) ± 2.4(sys) km s−1 Mpc−1

- [Statistical modelling of the cosmological dispersion measure](https://arxiv.org/abs/2010.01560)
    - 基于TNG300的：The free-electron power spectrum turns out to be consistent with the dark matter power spectrum at large scales, but it is strongly damped at small scales (≲1Mpc) owing to the stellar and active galactic nucleus feedback.
    - We have also obtained the probability distribution of source redshift for a given DM, which helps in identifying the host galaxies of FRBs from the measured DMs

- [IQ Collaboratory II: The Quiescent Fraction of Isolated, Low Mass Galaxies Across Simulations and Observations](https://arxiv.org/abs/2010.01132)
    - **Interesting**
    - 比较EAGLE, TNG, SIMBA: All three simulations show a decrease in the number of quiescent, isolated galaxies in the mass range M∗=109−10 M⊙, in broad agreement with observations.
    - 但是，None of the simulations reproduce the observed absence of quiescent field galaxies below 10^9-10 Msun, 都高估了

- [The clustering of submillimeter galaxies detected with ALMA](https://arxiv.org/abs/2010.01133)
    - **Interesting**
    - 利用ALESS巡天测量SMG的clustering：We constrain upper limits for the median mass of halos hosting SMGs at 1< z<3, finding Mhalo ≤2.4×10^12M⊙ for SMGs with flux densities S870≥4.0mJy 比之前单镜观测得到的成团性要低很多
    - 说明之前对SMG的halo质量也过高估计了：We conclude that only the brightest (S870≳5−6mJy) SMGs would trace massive structures at z∼2 and only SMGs with S870≳6mJy may be connected to massive local elliptical galaxies, quasars at intermediate redshifts and high-redshift star-forming galaxies, whereas fainter SMGs are unlikely linked to these populations.

- [Dust Attenuation Curves at z ∼ 0.8 from LEGA-C: Precise Constraints on the Slope and 2175Å Bump Strength](https://arxiv.org/abs/2010.01147)
    - We find that the attenuation curves in the rest-frame 3000−4500A range are typically almost twice as steep as the Milky Way, LMC, SMC, and Calzetti attenuation curves
    - The attenuation at 4500A and the slope strongly correlate with the galaxy inclination: face-on galaxies show less attenuation and steeper curves compared to edge-on galaxies 星系盘的指向对消光的影响最大
    - 在260/485个星系里看到了2175 bump，bump的强度似乎和星系性质关系不大；但bump确实多在低质量，正向星系里面出现

- [The dependence of the galaxy stellar-to-halo mass relation on galaxy morphology](https://arxiv.org/abs/2010.01186)
    - **Relevant**
    - SDSS:
        - At fixed halo mass in the mass range 10^11.7−10^12.9M⊙, the median stellar masses of SDSS disc galaxies are up to a factor of 1.4 higher than the median masses of their elliptical counterparts. 但这个结论与采用的恒星质量估计有关
        - For halo masses larger than 10^13M⊙, discs are less massive than ellipticals in same-mass haloes, regardless of whose stellar mass estimates we use.
    - EAGLE:
        - The EAGLE simulation predicts that discs are up to a factor of 1.5 more massive than elliptical galaxies residing in same-mass haloes less massive than 10^13M⊙ 这些质量不大，host盘星系的halo比同样质量host Elliptical的halo的assembly time要早
        - This suggests that the discs are more massive because they had more time for gas accretion and star formation.

- [Dust and gas in the central region of NGC 1316 (Fornax A) -- Its origin and nature](https://arxiv.org/abs/2010.01606)
    - HST color map; MUSE NaD absorption and velocity measurements: The velocity field of the ionised gas (and thus of the dust) is characterised by small-scale turbulent movements that indicate short lifetimes. At the very centre, a bipolar velocity field of the ionised gas is observed, which we interpret as an outflow
    - Our findings are strongly suggestive of a dusty outflow. Nuclear outflows may be important dust-producing machines in galaxies.

- [ALMaQUEST -- IV. The ALMA-MaNGA QUEnching and STar formation (ALMaQUEST) Survey](https://arxiv.org/abs/2010.01751)
    - ALMA观测46个sSFR分布很宽的MaNGA星系：the sSFR depends on both the star formation efficiency (SFE) and the molecular gas fraction (fH2), although the correlation with the latter is slightly weaker.
    - On kpc scales, the variations in both SFE and fH2 within individual galaxies can be as large as 1-2 dex thereby demonstrating that the availability of spatially-resolved observations is essential to understand the details of both star formation and quenching processes.

- [A Virgo Environmental Survey Tracing Ionised Gas Emission. VESTIGE VIII. Bridging the cluster-ICM-galaxy evolution at small scales](https://arxiv.org/abs/2010.02202)
    - VESTIGE Hα, Herschel SPIRE far-infrared, and VIVA HI data: We measure FIR emission from tails of stripped dust following the ionised and atomic gas components in galaxies undergoing ram pressure stripping
    - Along the stripped component, the dust distribution closely follows the HI and Hα emitting gas, all extending beyond the optical disc. 这些区域的Dust-to-gas mass ratios (DGRs)比星系盘上要低很多
    - We also find a negative trend in the DGR as a function of the metallicity that can be explained in terms of a dust component more centrally concentrated in more metal-rich systems.
    - Our results support an outside-in stripping scenario of the galaxy interstellar medium.

----

### Oct 6

- [Listening to the BOSS: the galaxy power spectrum take on spatial curvature and cosmic concordance](https://arxiv.org/abs/2010.02230)
    - Planck似乎限制Omega_K < 0; 但BAO支持Omega_K = 0;
    - Using measurements of the full-shape (FS) galaxy power spectrum, P(k), from the Baryon Oscillation Spectroscopic Survey DR12 CMASS sample. By combining Planck data with FS measurements, we break the geometrical degeneracy and find ΩK=0.0023±0.0028.
    - However, as with BAO, the overall increase in the best-fit χ2 suggests a similar level of tension between Planck and P(k) under the assumption of a curved Universe.

- [Fast analytical random pair counts calculation for realistic survey geometry](https://arxiv.org/abs/2010.02793)
    - Because pair counting scales as O(N2), where N is the number of points, the computational time to measure random pair counts cn be very expensive for large surveys.
    - We present an alternative approach for estimating those counts that does not rely on the use of a random catalogue. We derive an analytical expression for the anisotropic random-random pair counts that accounts for the galaxy radial distance distribution, survey geometry, and possible galaxy weights.

- [Overdensities of Submillimetre-Bright Sources around Candidate Protocluster Cores Selected from the South Pole Telescope Survey](https://arxiv.org/abs/2010.02909)
    - We find a total of 98 sources above a threshold of 3.7 sigma in the observed area of 1300 square arcminutes, where the bright central cores resolve into multiple components.
    - The large overdensities of bright submm sources surrounding these fields suggest that they could be candidate protoclusters undergoing massive star-formation events.

- [How the Population III Initial Mass Function Governs the Properties of the First Galaxies](https://arxiv.org/abs/2010.02212)
    - ENZO模拟：We find that a top-heavy Pop III IMF results in earlier star formation but dimmer galaxies than a more conventional Salpeter-type IMF because explosions of massive Pop III stars produce more turbulence that suppresses high-mass second-generation star formation

- [Dark-matter-deficient dwarf galaxies form via tidal stripping of dark matter in interactions with massive companions](https://arxiv.org/abs/2010.02219)
    - NewHorizon模拟：sustained stripping of dark matter, in tidal interactions between a massive galaxy and a dwarf satellite, naturally produces dwarfs that are dark-matter deficient, even though their initial dark-matter fractions are normal.
    - The process of dark matter stripping is responsible for the large scatter in the stellar-to-halo mass relation in the dwarf regime. The degree of stripping is driven by the closeness of the orbit of the dwarf around its massive companion

- [Galaxies with kinematically distinct cores in Illustris](https://arxiv.org/abs/2010.02222)
    - Illustris模拟里面KDC星系的分析：KDCs can be long-lived features, with their formation epochs roughly uniformly distributed in look-back times 0-11.4 Gyr, and they can survive even major or multiple subsequent mergers.
    - 没有单一的形成渠道，并合占60%，大质量星系中主要来自major merger
    - The mean mass-weighted stellar age inside the KDC radius is either about the same as the look-back time of the KDC formation or older.

- [Exemplary Merging Clusters: Weak-lensing and X-ray Analysis of the Double Radio Relic Merging Galaxy Clusters MACS 1752.0+4440 and ZWCL 1856.8+6616](https://arxiv.org/abs/2010.02226)
    - Our weak-lensing mass estimates show that each cluster is a major merger with approximately 1:1 mass ratio.
    - 尽管质量差别很大，但是WL和X-ray特征很相近
    - From the likeness of the X-ray morphologies and the remarkable symmetry of the radio relics, we propose that both systems underwent nearly head-on collisions.

- [Creating a galaxy lacking dark matter in a dark matter dominated universe](https://arxiv.org/abs/2010.02245)

- [An ALMA survey of the S2CLS UDS field: Optically invisible submillimetre galaxies](https://arxiv.org/abs/2010.02250)
    - **Interesting, Relevant**
    - We estimate that K>25.3 submillimetre galaxies represent 15+/-2 per cent of the total population brighter than S870=3.6mJy, with an expected surface density of ~450/deg^2 above S870>1mJy. 但只是Submm星系分布的tail；只是和K<25.3 mag的比，红移分布更高，尘埃消光更高; 消光高可能与其compact size有关
    - 可能成为高红移quiescent星系和LBG搜索的contamination
    - The concentrated, intense star-formation activity in these systems is likely to be associated with the formation of spheroids in compact galaxies at high redshifts, but as a result of their high obscuration these are completely missed in UV, optical and even near-infrared surveys.

- [Is there enough star formation in simulated protoclusters?](https://arxiv.org/abs/2010.02259)
    - **Relevant**
    - 现代模拟和SAM中的proto-cluster中没有足够的SF，比观测低了一个量级
    - 认为和模拟分辨率有关：We show that a large part of the discrepancy can be attributed to a dependence of SFR on the numerical resolution of the simulations, with a roughly factor of 3 drop in SFR when the spatial resolution decreases by a factor of 4.
    - 可以用proto-cluster的模型校准来限制星系演化模型，确保z=0的大质量星系的模型是正确的

- [Probing the Warm-Hot Circumgalactic Medium with broad OVI and X-rays](https://arxiv.org/abs/2010.02312)
    - OVI吸收线中的窄线成分指示的是logT=5.5的较冷的成分，而宽OVI吸收指示的是占CGM大部分的warm-hot成分
    - About 800ks of XMM-Newton observations will detect the expected absorption lines of OVII and OVIII unequivocally. Future missions like XRISM, Arcus and Athena will revolutionize the CGM science.

- [Investigating the Effect of Galaxy Interactions on AGN Enhancement at 0.5<z<3.0](https://arxiv.org/abs/2010.02710)
    - COSMOS+CANDELS: While we see a slight increase in AGN fraction with decreasing projected separation, overall, we find no significant enhancement relative to the control sample at any separation.

- [Scaling relations and baryonic cycling in local star-forming galaxies: II. Gas content and star-formation efficiency](https://arxiv.org/abs/2010.02919)
    - A sample of 392 galaxies (dubbed MAGMA, Metallicity and Gas for Mass Assembly)
    - We find the metallicity (Z) dependence of alpha_CO to be shallower than previous estimates
    - Molecular gas mass MH2 is found to be strongly correlated with Mstar and star-formation rate (SFR), enabling predictions of MH2 good to within ∼0.2 dex.
    - If Mgas is considered to depend on MHI, together with Mstar and SFR, we obtain a relation that predicts Mgas to within ∼0.05 dex.
    - Dwarf galaxies tend to be overwhelmed by (HI) accretion, while for galaxies in the intermediate Mstar "gas-equilibrium" bin, star formation proceeds apace with gas availability. In the most massive "gas-poor, bimodality" galaxies, HI does not apparently participate in star formation, although it generally dominates in mass over H2

----

### Oct 7

- [Learning effective physical laws for generating cosmological hydrodynamics with Lagrangian Deep Learning](https://arxiv.org/abs/2010.02926)
    - 针对生成模拟方法在高维度空间的不足：we propose Lagrangian Deep Learning (LDL) for this purpose, applying it to learn outputs of cosmological hydrodynamical simulations -- The model uses layers of Lagrangian displacements of particles describing the observables to learn the effective physical laws.
    - The displacements are modeled as the gradient of an effective potential, which explicitly satisfies the translational and rotational invariance.
    - The computational cost of LDL is nearly four orders of magnitude lower than the full hydrodynamical simulations, yet it outperforms it at the same resolution.

- [A Self-Calibrating Halo-Based Group Finder: Application to SDSS](https://arxiv.org/abs/2010.02946)
    - **Useful, Important** https://www.galaxygroupfinder.net/catalogs
    - This algorithm introduces new freedom to assign halos to galaxies that is self-calibrated by comparing the catalog to complementary data. These include galaxy clustering data and measurements of the total satellite luminosity from deep imaging data.
    - The transition halo mass scale, where half of halos contain quiescent central galaxies, is at M_h~10^12.4 Msol/h, significantly higher than other constraints.
    - Quiescent central galaxies in low-mass halos are significantly more massive than star-forming centrals at the same halo mass, but this difference reverses above the transition halo mass.
    - We find that the scatter in logM* at fixed M_h is ~0.2 dex for massive halos, in agreement with previous estimates, but rises sharply at lower halo masses.

- [The eROSITA X-ray telescope on SRG](https://arxiv.org/abs/2010.03477)
    - **Important**
    - By the end of 2023, eight complete scans of the celestial sphere will have been performed, each lasting six months
    - eROSITA all-sky survey in the soft X-ray band (0.2--2.3,keV) will be about 25 times more sensitive than the ROSAT All-Sky Survey, while in the hard band (2.3--8,keV) it will provide the first ever true imaging survey of the sky.

- [The Lyman Alpha Spectral Database (LASD)](https://arxiv.org/abs/2010.02927)
    - **Useful** 适合学习peak detection算法和复杂光谱的测量; https://gist.github.com/sixtenbe/1178136
    - We have compiled a large sample of Lyα spectra, at both low and high redshift, and created a publicly available online database, at: http://lasd.lyman-alpha.com/
    - 不仅包括光谱，还有大量谱线和运动学测量

- [Stellar splashback: the edge of the intracluster light](https://arxiv.org/abs/2010.02937)
    - **Relevant, Important, Interesting**
    - C-EAGLE模拟：the stellar distribution (or intracluster light, ICL) also has a well-defined edge, which is directly related to the splashback radius of the halo.
    - We show that these caustics can also be seen in the projected density profiles, but care must be taken to account for the influence of substructures and other non-diffuse material, which can bias and/or weaken the signal of the steepest slope.
    - We show that the "stellar splashback" feature is located beyond current observational constraints on the ICL, but these large projected distances (>>1 Mpc) and low surface brightnesses (mu >> 32 mag/arcsec^2)

- [How well can we determine ages and chemical abundances from spectral fitting of integrated light spectra?](https://arxiv.org/abs/2010.02940)/
    - **Useful**
    - WAGGS + Schiavon et al. (2005) GGCLib
    - Starlight拟合GC：
        - (1) The inferred parameters change with the wavelength range used;
        - (2) The method in general retrieves good reddening estimates, specially when a wider wavelength range is fitted;
        - (3) The ideal spectral regions for determination of age, [Fe/H], and [alpha/Fe] are: 4170-5540A, 5280-7020A, and 4828-5364A, respectively;
        - (4) The retrieved age values for old metal-poor objects can be several Gyr younger than those resulting from isochrone fitting.

- [Morphological and Rotation Structures of Circumgalactic Mg II Gas in the EAGLE Simulation and the Dependence on Galaxy Properties](https://arxiv.org/abs/2010.02944)
    - MgII指示的是logT~4的冷CGM气体；低红移气体的CGM中的MgII冷气体中可能有很高的角动量
    - 用EAGLE模拟进行研究：Mg II gas has an axisymmetric instead of a spherical distribution, and the axis of symmetry aligns with that of the Mg II gas rotation. 在Quiescent星系周围旋转则不多见
    - 实际观测中用视向速度cut可能会包含virial radii以外的气体：While the corotating Mg II gas generally extends beyond 0.5rvir, the Mg II gas outside of the virial radius contaminates the corotation signal and makes observers less likely to conclude that gas at large impact parameters (e.g., ≳0.25rvir) is corotating.

- [The AGN-galaxy-halo connection: The distribution of AGN host halo masses to z=2.5](https://arxiv.org/abs/2010.02957)
    - 传统的用AGN clustering估算其halo质量的方法可能受到AGN fraction随恒星质量变化等选择效应影响，而且从clustering的推断方法可能产生bias
    - We use AGN specific accretion rate distribution functions determined as a function of stellar mass and redshift for star-forming and quiescent galaxies separately, combined with the latest galaxy-halo connection models, to determine the parent and sub-halo mass distribution function of AGN
    - 平均质量 2x10^12 Msun; 随AGN吸积率，光度，红移的变化不大
    - While the AGN satellite fraction rises with increasing parent halo mass, we find that the central galaxy is often not an AGN.
    - We further show that AGN clustering is most easily interpreted and understood in terms of the relative bias to galaxy samples, not from absolute bias measurements alone.

- [Mysterious Globular Cluster System of the Peculiar Massive Galaxy M85](https://arxiv.org/abs/2010.03041)
    - **Relevant**
    - 89 GCs at 8 kpc <R< 160 kpc using the MMT/Hectospec: 按颜色分成red, green, blue，都很年老，但金属丰度不同
    - Red GCs有很明显的旋转：We find that the inner GC system exhibits a strong overall rotation that is entirely due to a disk-like rotation of the RGC system. Blue GC基本无旋转，不同population的运动学差异很大，可能是最近并合的结果
    - The GGCs show kinematic properties clearly distinct among the GC subpopulations, having higher mean velocities than the BGCs and RGCs and being aligned along the major axis of M85.

- [Unravelling the enigmatic ISM conditions in Minkowski's Object](https://arxiv.org/abs/2010.03139)
    - NGC541的jet路径上的dwarf星系：Minkowski's Object primarily consists of a young stellar population ∼10 Myr old, confirming that the bulk of the object's stellar mass formed during a recent jet interaction.
    - 发射线基本可以用SF解释；气体金属丰度变化范围很大：Strong-line diagnostics reveal a significant variation in the gas-phase metallicity within the object, with log(O/H)+12 varying by ∼0.5 dex
    - We hypothesise that Minkowski's Object either (a) was formed as a result of jet-induced star formation in pre-existing gas clumps in the stellar bridge, or (b) is a gas-rich dwarf galaxy that is experiencing an elevation in its star formation rate due to a jet interaction 能形成类似UDG的星系吗？

----

### Oct 8

- [Comparing different mass estimators for a large subsample of the {\it Planck}-ESZ clusters](https://arxiv.org/abs/2010.03582)
    - **Relevant**
    - The mean ratio between our X-ray masses and the weak-lensing masses in the LC2-single catalog is 1-b=0.74±0.06. However, the mean mass ratios inferred from the WL masses of different projects vary by a large amount, with APEX-SZ showing a bias consistent with zero (1-b=1.02±0.12), LoCuSS and CCCP/MENeaCS showing a significant difference (1-b=0.76±0.09 and 1-b=0.77±0.10, respectively), and WtG pointing to the largest deviation (1-b=0.61±0.12)
    - 动力学质量估计和X-ray质量估计符合得更好

- [Exploring the hydrostatic mass bias in MUSIC clusters: application to the NIKA2 mock sample](https://arxiv.org/abs/2010.03634)
    - **Relevant**
    - We analyzed a set of 260 synthetic clusters from the MUSIC simulation project, at redshifts 0≤z≤0.82.
    - The biases are of the order of 20%. We find that using the temperature instead of the pressure leads to a smaller bias, although the two values are compatible within 1σ.
    - We also present a study of the correlation between the mass bias and the dynamical state of the clusters. A clear correlation is shown between the relaxation state of the clusters and the bias factor.

- [Peculiar Velocity Estimation from Kinetic SZ Effect using Deep Neural Networks](https://arxiv.org/abs/2010.03762)
    - We simplify the calculation of peculiar velocities of galaxy clusters using deep learning frameworks trained on numerical simulations to avoid the estimation of the optical depth.
    - The deep learning algorithm displays robustness in estimating peculiar velocities from kinetic SZ effect by an improvement in accuracy of about 17% compared to the analytical approach.

- [Why reducing the cosmic sound horizon can not fully resolve the Hubble tension](https://arxiv.org/abs/2010.04158)
    - 解决H0 tension：Many of them introduce new physics, such as early dark energy, modifications of the standard model neutrino sector, extra radiation, primordial magnetic fields or varying fundamental constants, with the aim of reducing the sound horizon at recombination r⋆.
    - We demonstrate here that any model which {\it only} reduces r⋆ can never fully resolve the Hubble tension while remaining consistent with other cosmological datasets. We show explicitly that models which operate at lower matter density Ωmh2 run into tension with the observations of baryon acoustic oscillations, while models operating at higher Ωmh2 develop tension with galaxy weak lensing data.

- [Simulating cosmic structure formation with the GADGET-4 code](https://arxiv.org/abs/2010.03567)
    - **Useful**
    - The new version offers improvements in force accuracy, in time-stepping, in adaptivity to a large dynamic range in timescales, in computational efficiency, and in parallel scalability through a special MPI/shared-memory parallelization and communication strategy, and a more-sophisticated domain decomposition algorithm.
    - Two different flavours of smoothed particle hydrodynamics, a classic entropy-conserving formulation and a pressure-based approach, are supported for dealing with gaseous flows.
    - The GADGET-4 code is publicly released to the community and contains infrastructure for on-the-fly group and substructure finding and tracking, as well as merger tree building, a simple model for radiative cooling and star formation, a high dynamic range power spectrum estimator, and an initial conditions generator based on second-order Lagrangian perturbation theory.

- [MMT Spectroscopy of Lyman-alpha at z≃7: Evidence for Accelerated Reionization Around Massive Galaxies](https://arxiv.org/abs/2010.03566)
    - To better understand why Lyα is anonymously strong in a subset of massive z≃7−9 galaxies, we have initiated an MMT/Binospec survey targeting a larger sample (N=22) of similarly luminous (≃1−6 L∗UV) z≃7 galaxies
    - We confidently (>7σ) detect Lyα in 78% (7/9) of galaxies with strong [OIII]+Hβ emission (EW>800 A˚) as opposed to only 8% (1/12) of galaxies with more moderate (EW=200−800 A˚) [OIII]+Hβ.
    - We argue that the higher Lyα EWs of the strong [OIII]+Hβ population likely reflect enhanced ionizing photon production efficiency owing to their large sSFRs
    - 大质量星系的Lya透过率演化较小，可能居住在较大的电离区域内

- [From haloes to galaxies -- II. The fundamental relations in star formation and quenching](https://arxiv.org/abs/2010.03579)
    - We show the integrated MH2-SFR, SFR-M∗ and MH2-M∗ relation can be simply transformed from the μ-sSFR, SFE-μ and SFE-sSFR relation; μ是分子气体与恒星质量比；这三个关系的scatter更小
    - We propose the sSFR-μ-SFE relation as the Fundamental Formation Relation (FFR), which governs the star formation and quenching process, and provides a simple framework to study galaxy evolution.

- [The QuaStar Survey: Detecting Hidden Low-Velocity Gas in the Milky Way's Circumgalactic Medium](https://arxiv.org/abs/2010.03610)
    - **Interesting**
    - The content of the Milky Way's circumgalactic medium (CGM) is poorly constrained at |vLSR| ≲ 150 km s−1
    - The QuaStar Survey applies a spectral differencing technique using paired quasar-star sightlines to measure the obscured content of the Milky Way's CGM for the first time.
    - We present measurements of the CIV doublet (λλ 1548 \r{A}, 1550 \r{A}), a rest-frame UV metal line transition detected in HST/COS spectra of 30 halo-star/quasar pairs evenly distributed across the sky at Galactic latitudes |b|>30∘
    - We argue that the difference in absorption between the quasar and stellar sightlines originates primarily in the Milky Way's extended CGM beyond ∼10 kpc.

- [HI Deficiencies and Asymmetries in HIPASS Galaxies](https://arxiv.org/abs/2010.03720)
    - Previous studies of galaxy HI deficiency using HIPASS were sensitive to galaxies that are extremely HI rich or poor. We use an updated binning statistic for measuring the global sky distribution of HI deficiency that is sensitive to the average deficiencies.
    - Galaxies residing in denser environments, such as Virgo, are on average more HI deficient than galaxies at lower densities.
    - Many other individual groups and clusters are not found to be on average significantly HI poor
    - We also investigate the correlation between HI asymmetry and deficiency, but find no variation in the mean asymmetry of galaxies that are HI rich, normal or poor.

- [Resolving the Disc-Halo Degeneracy II: NGC 6946](https://arxiv.org/abs/2010.03991)
    - This mismatch between the scale height and the velocity dispersion can lead to underestimates of the disc surface density and a misleading conclusion of the sub-maximality of galaxy discs.
    - We present the study of the stellar velocity dispersion of the disc galaxy NGC 6946 using integrated star light and individual planetary nebulae as dynamical tracers. We demonstrate the presence of two kinematically distinct populations of tracers which contribute to the total stellar velocity dispersion.
    - We find the disc of NGC 6946 to be closer to maximal with the baryonic component contributing most of the radial gravitational field in the inner parts of the galaxy (Vmax(bar) = 0.76(±0.14)Vmax).

- [More insights into bar quenching. Multi-wavelength analysis of four barred galaxies](https://arxiv.org/abs/2010.04005)
    - We found that for three galaxies, the region between the nuclear or central sub-kiloparsec region and the end of the bar (bar region) is devoid of neutral and molecular hydrogen.
    - While the detected neutral hydrogen is very negligible, we note that molecular hydrogen is present abundantly in the nuclear or central sub-kiloparsec regions of all four galaxies.
    - The study presented here supports a scenario in which gas redistribution as a result of the action of stellar bar clears the bar region of fuel for further star formation and eventually leads to star formation quenching in the bar region.

- [Sustained formation of progenitor globular clusters in a giant elliptical galaxy](https://arxiv.org/abs/2010.04046)
    - **Relevant**
    - We show that many thousands of compact and massive (~5×103−3× 106M⊙) star clusters have formed at an approximately steady rate over, at least, the past ~1Gyr around NGC 1275
    - Their number distribution exhibits a similar dependence with luminosity and mass as the GCs, whereas their spatial distribution resembles a filamentary network of multiphase gas associated with cooling of the intracluster gas.
    - The progenitor GCs have minimal masses well below the maximal masses of Galactic open star clusters, affirming a common formation mechanism for star clusters over all mass scales irrespective of their formative pathways.

----

### Oct 11

- [Mitigating the effects of undersampling in weak lensing shear estimation with metacalibration](https://arxiv.org/abs/2010.04164)
    - **CSST**
    - We investigate the accuracy of shear measured with metacalibration from fitting elliptical Gaussians to undersampled galaxy images. In this case, metacalibration introduces aliasing effects leading to an ensemble multiplicative shear bias about 0.01 for Euclid, and even larger for the Roman Space Telescope
    - 克服的方法: computing shapes from weighted moments with wider Gaussians as weight functions, thereby trading bias for a slight increase in variance of the measurements

- [Super-sample covariance of the thermal Sunyaev-Zel'dovich effect](https://arxiv.org/abs/2010.04174)
    - **Interesting**
    - The statistical errors in the tSZ power spectrum measurements are dominated by the presence of massive clusters in a survey volume that are easy to identify on individual cluster basis. tSZ功率谱中最大的统计误差来源：最大质量的星系团
    - The sample variance is dominated by the connected non-Gaussian (cNG) covariance arising mainly from Poisson number fluctuations of massive clusters in the survey volume. 移除这些能被单独探测到的大质量星系团能降低variance
    - The power spectrum measured from the remaining, diffuse tSZ effects can be used to obtain tight constraints on cosmological parameters as well as the hydrostatic mass bias parameter.

- [Elucidating Galaxy Assembly Bias in SDSS](https://arxiv.org/abs/2010.04176)
    - **Relevant, SSST**
    - SDSS加ELUCID模拟：we develop an extended HOD model that includes the assembly bias of central and satellite galaxies
    - We discover that in many cases the level of cosmic variance between the two simulations can produce biased constraints that lead to an erroneous detection of galaxy assembly bias if the non-constrained simulation is used.
    - Our fiducial ELUCID constraint, for galaxies above a stellar mass threshold M∗=10^10.2h−1M⊙, is Qcen=−0.06±0.09 and Qsat=0.08±0.12, indicating no evidence for a significant galaxy assembly bias in the local Universe probed by SDSS.

- [Accounting for object detection bias in weak gravitationallensing studies](https://arxiv.org/abs/2010.04178)
    - We study the impact of object detection for a Euclid-like survey and show that it leads to biases that exceed requirements for the next generation of cosmic shear surveys. In realistic scenarios, blending of galaxies is an important source of detection bias.
    - We find that MetaDetection is able to account for blending, leading to average multiplicative biases that meet requirements for Stage IV surveys, provided a sufficiently accurate model for the point spread function is available.

- [Evidence for galaxy assembly bias in BOSS CMASS redshift-space galaxy correlation function](https://arxiv.org/abs/2010.04182)
    - **Relevant**
    - Recent studies have found that halo concentration by itself cannot capture the full galaxy assembly bias effect and that the local environment of the halo can be an excellent indicator of galaxy assembly bias. 建立了一个HOD模型包含了这两个因素
    - 观测上基于BOSS CMASS：We find that the inclusion of both assembly bias terms is strongly favored by the data and the standard 5-parameter HOD is strongly rejected. 并且能解决Lensing is low问题
    - We also showcase a consistent 3-5sigma preference for a positive environment-based assembly bias that persists over variations in the fit.

- [From "universal" profiles to "universal" scaling laws in X-ray galaxy clusters](https://arxiv.org/abs/2010.04192)
    - **Relevant**
    - We use a semi-analytic model based on a "universal" pressure profile in hydrostatic equilibrium within a cold dark matter halo with a defined relation between mass and concentration to reconstruct the scaling laws between the X-ray properties of galaxy clusters.
    - We also quantify any deviation from the self-similar predictions in term of temperature dependence of few physical quantities like the gas mass fraction, the relation between spectroscopic temperature and its global value, and, if present, the hydrostatic mass bias.
    - By combining these results with the constraints on the observed YSZ−T relation, we show how we can quantify the level of gas clumping affecting the studied sample, estimate the clumping-free gas mass fraction, and suggest the average level of hydrostatic bias present.

- [Cross-Correlation of Planck CMB Lensing with DESI-Like LRGs](https://arxiv.org/abs/2010.04698)
    - We detect a cross-correlation between DESI-like luminous red galaxies (LRGs) selected from DECaLS imaging and CMB lensing maps reconstructed with the Planck satellite at a significance of S/N=27.2 over scales ℓmin=30, ℓmax=1000
    - 利用 LRG cumulative magnitude function at the faint limit进行放大效应改正
    - We fit the large-scale galaxy bias at the effective redshift of the cross-correlation zeff≈0.68 using two different bias evolution agnostic models: a HaloFit times linear bias model where the bias evolution is folded into the clustering-based estimation of the redshift kernel, and a Lagrangian perturbation theory model of the clustering evaluated at zeff

- [Did Sgr cause the vertical waves in the solar neighbourhood?](https://arxiv.org/abs/2010.04165)
    - We find that we are unable to reproduce the observed asymmetry in the vertical number counts and its concomitant breathing mode in velocity space for any plausible combination of Sgr and Milky-Way properties.

- [The critical dark matter halo mass for Population III star formation: dependence on Lyman-Werner radiation, baryon-dark matter streaming velocity, and redshift](https://arxiv.org/abs/2010.04169)
    - Pop III形成的临界Halo质量：能包含足够多致密分子气体的最小halo质量，The presence of Lyman-Werner (UV) radiation, which can dissociate molecular hydrogen, and the baryon-dark matter streaming velocity both delay the formation of Pop III stars by increasing Mcrit
    - 基于Enzo模拟给出Mcrit对LW流量和Baryon-DM streaming，以及红移的模型; 综合几种依赖的效应比较复杂

- [The Hα Dots Survey. II. A Second List of Faint Emission-Line Objects](https://arxiv.org/abs/2010.04252)
    - The second catalog of serendipitously discovered compact extragalactic emission-line sources - Hα Dots
    - The sample includes Hα-detected blue compact dwarf galaxies at low redshift, [\ion{O}{3}]-detected Seyfert 2 and Green Pea-like galaxies at intermediate redshifts, and QSOs detected via one of several UV emission lines, including Lyα.

- [Changing-look active galactic nuclei: close binaries of supermassive black holes in action](https://arxiv.org/abs/2010.04417)
    - We demonstrate the extreme case that close binaries of supermassive black holes (CB-SMBHs) with high eccentricities are able to trigger the CL transition through one orbit. 用双黑洞解释CL-AGN
    - Binary black holes build up their own mini-disks via peeling gas off inner edges of the circumbinary disk during the apastron phase after then they tidally interact with the disks during the periastron phase to efficiently exchange angular momentum (AM) within one orbital period.
    - For mini-disks with rotation retrograde to the orbit, the tidal torque rapidly squeezes the tidal parts of the mini-disks into much smaller radius, resulting in an elevated accretion rapidly and short flares before declining into type-2 AGNs. In case of prograde mini-disks, they gain AM from the binary and rotate outward, giving rise to a rapid turn-off from type-1 to -2.

- [The Impact of Disturbed Galaxy Clusters on the Kinematics of Active Galactic Nuclei](https://arxiv.org/abs/2010.04498)
    - 33个BAX clusters，进行member sub-structure分类：8 dynamically active (merging) and 25 dynamically relaxed (non-merging) states.
    - 用WHAN diagram挑选AGN：70 merging and 225 non-merging AGN sub-populations.
    - AGN-hosting cluster galaxies have recently coalesced onto a common potential7
    - Non-merging AGN-hosting sub-populations have, on average, already been accreted and predominantly lie within backsplash regions of the projected phase-space.

- [Evaluating Galaxy Dynamical Masses From Kinematics and Jeans Equilibrium in Simulations](https://arxiv.org/abs/2010.04629)
    - **Useful**
    - 基于VELA模拟：We find that Jeans or hydrostatic equilibrium is approximately valid for galaxies of stellar masses above M⋆∼10^9.5M⊙ out to 5 effective radii (Re).
    - 给出了用旋转速度和视向速度弥散度结合测动力学质量的方法，对Spheroid和Disc不太一样，需要不同的改正系数 alpha；在Spheroid里，alpha和Sersic index反相关；在盘星系里，alpha和半径正相关
    - The correction in α for the stars due to the gradient in σr(r) is roughly balanced by the effect of the aspherical potential, while the effect of anisotropy is negligible.

- [The AGN fuelling/feedback cycle in nearby radio galaxies III. 3D relative orientations of radio jets and CO discs and their interaction](https://arxiv.org/abs/2010.04685)
    - 11 low-excitation radio galaxies (LERGs)的研究：JVLA+ALMA，a full 3D analysis of the relative orientations of jet and disc rotation axes in six FR I LERGs.
    - This analysis shows (albeit with significant uncertainties) that the relative orientation angles span a wide range (≈30∘−60∘). There is no case where both axes are accurately aligned and there is a marginally significant tendency for jets to avoid the disc plane.
    - 在NGC 3100中看到了Jet和CO气体相互作用的证据

- [Spatially resolved CIII\]λ1909 emission in Haro 11](https://arxiv.org/abs/2010.04685)
    - CIII\]1909半禁线，是除了Lya之外最强的紫外发射线 It is thought that C III\] emission is strongest in galaxies with subsolar metallicity and low mass, however, spectral observations of numerous such galaxies at high and low redshift produce inconclusive or even contradictory results.
    - STIS对Haro11的观测：Cluster parameters like stellar mass, dust fraction and dust attenuation, and ionization parameter, obtained through spectral energy distribution fitting, show no correlation with the CIII\] equivalent width (EW), which may be due to a combination of the limitation of the models and the age-homogeneity of the cluster population
    - We find that the clusters with the highest EW(C III\]) can be reconciled only with Cloudy models with an extremely high C/O ratio of ≥ 1.4(C/O)⊙ for an ionizing population of single stars, binary stars, or a mixture of binary stars and active galactic nuclei.

----

### Oct 12

- [A Novel Estimator for the Equation of State of the IGM by Lyα Forest Tomography](https://arxiv.org/abs/2010.05606)
    - 根据QSO光谱观测估计ISM的状态方程： Our estimation is based on a full tomographic inversion of the line of sight.
    - We model the temperature-density relation with a power law and observe for the temperature at mean density T0=13000+1300−1200K and for the slope of the power-law (polytropic index) γ=1.44±0.09 for the power-law parameters
    - We invert the data with two different inversion algorithms, the iterative Gauss-Newton method and the regularized probability conservation approach, which depend on different priors and compare the inversion results in flux space and in density space.

- [The HectoMAP Redshift Survey: First Data Release](https://arxiv.org/abs/2010.05817)
    - **Useful**
    - 55 deg^2; r=21.3 mag; 只释放了一部分： 17,313 redshifts in a first data release covering 8.7 square degrees.
    - 8117 constitute a 79% complete red-selected subsample with r≤20.5 and an additional 4318 constitute a 68\% complete red-selected subsample with 20.5 < r <21.3.

- [The Number Densities and Stellar Populations of Massive Galaxies at 3 < z < 6: A Diverse, Rapidly Forming Population in the Early Universe](https://arxiv.org/abs/2010.04725)
    - **Relevant**
    - UltraVista中M>10^11 Msun的高红移星系：≈100  and ≈20 high-confidence candidates at 3<z<4 and 4<z<6
    - The 3< z <4 population is comprised of post-starburst, UV star-forming and dusty-star forming galaxies in roughly equal fractions, while UV-star-forming galaxies dominate at 4< z<6
    - 在SED拟合中考虑发射线很重要
    - z~4是大质量星系出现的关键时期，这些星系的形成可以追溯至z~7; 星系都很compact
    - ≈15−25% of the population showing evidence of suppressed star-formation rates

- [Galaxy evolution across environments as probed by the ages, stellar metallicities and [alpha/Fe] of central and satellite galaxies](https://arxiv.org/abs/2010.04733)
    - **Relevant**
    - 基于Yang catalog；color-M/L based stellar mass; Lick index-based stellar population
    - Below log(Mstar/Msun)=10.5 satellites are older and metal-richer than equally-massive central galaxies. 但alpha/Fe没有区别
    - We also find that the differences in the median age and metallicity of satellites and centrals at stellar mass below 10^{10.5}Msun are largely due to the higher fraction of passive galaxies among satellites and as a function of halo mass.
    - When accounting for the varying quiescent fraction, small residual excess in age, metallicity and [alpha/Fe] emerge for satellites dominated by old stellar populations and residing in halos more massive than 10^{14}Msun, compared to equally-massive central galaxies. This excess in age, metallicity and [alpha/Fe] pertain to ancient infallers, i.e. satellites that have accreted onto the current halo more than 5 Gyr ago.

- [SQuIGGLE Survey: Massive z∼0.6 Post-Starburst Galaxies Exhibit Flat Age Gradients](https://arxiv.org/abs/2010.04734)
    - **Relevant**
    - Gemini观测，质量大于10^11 Msun: Using HδA absorption as a proxy for stellar age, we constrain five of the galaxies to have young (∼600 Myr) light-weighted ages at all radii and find that the sample on average has flat age gradients.
    - Find that galaxies with flat HδA profiles are inconsistent with formation via a central secondary starburst. This implies that the mechanism responsible for shutting off this dominant episode of star formation must have done so uniformly throughout the galaxy.

- [Investigating The Growing Population of Massive Quiescent Galaxies at Cosmic Noon](https://arxiv.org/abs/2010.04741)
    - **Relevant**
    - 28,469 massive (M⋆≥10^11M⊙) galaxies at redshifts 1.5< z<3.0, drawn from a 17.5 deg2 area
    - 通过三种方法估计Quiescent fraction：
        - 在1.5 < z < 2.0: 三个方法结果一致；quiescent fraction随恒星质量增加
        - 在2.0 < z < 3.0: 不同方法结果出现差别；UVJ给出的最高，sSFR给出的最低
        - 在z~2: the universe has quenched ∼25% of M⋆=10^11M⊙ galaxies and ∼45% of M⋆=10^12M⊙ galaxies
    - 和模拟比较：The quiescent fraction from IllustrisTNG is higher than our empirical result by a factor of 2−5, while those from SIMBA and the three SAMs are lower by a factor of 1.5−10 at 1.5< z< 3.0.

- [The environmental dependence of X-ray AGN activity at z∼0.4](https://arxiv.org/abs/2010.04832)
    - 0.35< z<0.45的7个大质量星系团中的Chandra X-ray确认的AGN
    - Studying the subset of AGN with 0.5-8 keV luminosities >6.8×10^42 erg s−1, within r≤2r500
    - The cluster AGN space density scales with cluster mass as ∼M−2.0+0.8−0.9 基本能确认有环境依赖
    - The cluster AGN fraction is significantly suppressed relative to the field when considering the brightest galaxies with V<21.5.
    - No evidence for enhanced X-ray obscuration of cluster member AGN.

- [All the PAHs: an AKARI-Spitzer Cross Archival Spectroscopic Survey of Aromatic Emission in Galaxies](https://arxiv.org/abs/2010.05034)
    - AKARI-Spitzer Extragalactic Spectral Survey (ASESS): 113个SF星系的2.5-38 micron的PAH研究
    - 3.3 micron PAH:
        - We find LPAH3.3/LIR ∼ 0.1% and the 3.3 μm PAH feature contributes ∼1.5-3% to the total PAH power
        - 可以trace SFR；但是在高光度和低金属丰度时不可靠
        - 3.3 μm is susceptible to attenuation, leading to a factor of ∼ 3 differences in the inferred star formation rate at high obscuration
        - The smallest PAHs are better able to survive under intense radiation fields than presumed, or that PAH emission is shifted to shorter wavelengths in intense and high energy radiation environments.

- [YZiCS: On the Mass Segregation of Galaxies in Clusters](https://arxiv.org/abs/2010.05304)
    - **Relevant**
    - Using deep optical observations of 14 Abell clusters (KYDISC) and a set of hydrodynamic simulations (YZiCS), we find in some cases a hint of mass segregation inside the virial radius. 通过大质量星系比例可以看出；在模拟里更明显
    - Satellites that get accreted at earlier epochs or galaxies in more massive clusters go through more tidal stripping. These effects in combination result in a correlation between the host halo mass and the degree of stellar mass segregation.

- [On the origin of X-ray oxygen emission-lines in obscured AGN](https://arxiv.org/abs/2010.05412)
    - 基于XMM archive的：Catalog of High REsolution Spectra of Obscured Sources (CHRESOS)
    - We concentrate on the soft X-ray OVII(f) and OVIII Ly_alpha emission；看和AGN以及SF的关系
    - 和其他线，以及模型比较：[OIII]5007A, [OIV]25.89mic emission lines, and MIR-12mic, FIR-60mic, FIR-100mic, 2-10 keV and 14-195 keV continuum bands, we conclude that the AGN radiation field is mainly responsible of the soft X-ray oxygen excitation.

- [Global HI asymmetries in IllustrisTNG: a diversity of physical processes disturb the cold gas in galaxies](https://arxiv.org/abs/2010.05422)
    - 基于TNG100：more than 50% of the sample has at least a 10% difference in integrated flux between the high- and low-velocity half of the spectrum, thus the typical TNG100 galaxy has an HI profile that is not fully symmetric.
    - 卫星星系的HI比centrals的更不对称；this trend appears to be driven by the satellite population within the virial radius of haloes more massive than 10^13M⊙, typical of medium/large groups.
    - Ram pressure stripping很重要，但是有同时作用于中心和卫星星系物理机制导致了不对称

- [The host galaxy of OJ 287 revealed by optical and near-infrared imaging](https://arxiv.org/abs/2010.05487)
    - z=0.3; 有12年周期性爆发，被认为可能有双黑洞的BL Lac
    - 很深的GTC光学和NOT NIR观测：We find the broad-band photometry of the host to be consistent with an early type galaxy with M_R = -22.5 and M_K = -25.2
    - The central supermassive black hole is clearly overmassive for a host galaxy of that luminosity, but not unprecedented

- [The infrared-radio correlation of star-forming galaxies is strongly M⋆-dependent but nearly redshift-invariant since z∼4](https://arxiv.org/abs/2010.05510)
    - qTIR == L_TIR/L_1.4Ghz; infrared-radio correlation (IRRC)
    - We re-calibrate qTIR as a function of both stellar mass (M∗) and redshift, starting from an M∗-selected sample of >400,000 star-forming galaxies in the COSMOS field, identified via (NUV-r)/(r-J) colours, at redshifts 0.1< z<4.5.
    - We find that the IRRC evolves primarily with M∗, with more massive galaxies displaying systematically lower qTIR. 对红移也有依赖，但是较弱
    - Adding the UV dust-uncorrected contribution to the IR as a proxy for the total SFR, would further steepen the qTIR dependence on M∗.
    - The lower IR/radio ratio in more massive galaxies could be possibly linked to higher SFR surface density, which induces larger cosmic-ray scale heights. 不是因为大质量星系的SFR变弱

- [Does NGC 6397 contain an intermediate-mass black hole or a more diffuse inner sub-cluster?](https://arxiv.org/abs/2010.05532)
    - MUSE观测和建模：We consider different priors on velocity anisotropy and on the size of the central mass, and also separate stars into components of different mean mass to allow for mass segregation.
    - 作者认为可以排除IMBH：The velocity ellipsoid is very isotropic throughout the cluster, and we argue that this must have been acquired early on. The data prefer the existence of a dark component in this cluster center of 0.8 to 2 percent of the total mass of the cluster 而是一个diffuse dark cluster
    - We argue that stellar-mass black holes should dominate the mass of this diffuse dark component.

- [Individual optical variability of Active Galactic Nuclei from the MEXSAS2 sample](https://arxiv.org/abs/2010.05624)
    - Multi-Epoch XMM Serendipitous AGN Sample 2 (MEXSAS2)
    - 基于单独AGN的统计：We find a significant decrease of variability amplitude with increasing bolometric, optical and X-ray luminosity.
    - When comparing optical to X-ray variability properties, we find that X-ray variability amplitude is approximately the same for those AGNs with larger or smaller variability amplitude in the optical.

- [The Infrared Medium-deep Survey. VIII. Quasar Luminosity Function at z∼5](https://arxiv.org/abs/2010.05859)
    - UKIRT WFCam: Infrared Medium-deep Survey (IMS), a near-infrared imaging survey covering an area of 85 deg2
    - 统计z~5的较暗的QSO；这些QSO可能对再电离之后的电离背景比较重要
    - We find that the faint-end slope of the QLF is very flat：imply that quasars are responsible for only 10-20% (up to 50% even in the extreme case) of the photons required to completely ionize the IGM at z∼5, disfavoring the idea that quasars alone could have ionized the IGM at z∼5.

----

### Oct 13

- [The LSST DESC DC2 Simulated Sky Survey](https://arxiv.org/abs/2010.05926)
    - **Useful, Important, CSST**
    - This effort encompasses a full end-to-end approach: starting from a large N-body simulation, through setting up LSST-like observations including realistic cadences, through image simulations, and finally processing with Rubin's LSST Science Pipelines.
    - The simulated DC2 sky survey covers six optical bands in a wide-fast-deep (WFD) area of approximately 300 deg^2 as well as a deep drilling field (DDF) of approximately 1 deg^2.

- [Active learning with RESSPECT: Resource allocation for extragalactic astronomical transients](https://arxiv.org/abs/2010.05941)
    - **SSST**
    - The Recommendation System for Spectroscopic follow-up (RESSPECT) project aims to enable the construction of optimized training samples for the Rubin Observatory Legacy Survey of Space and Time (LSST)
    - Our experiment takes into account the evolution of training and pool samples, different costs per object, and two different sources of budget. 比random sampling效率要高

- [Star-Galaxy Separation via Gaussian Processes with Model Reduction](https://arxiv.org/abs/2010.06094)
    - **Useful**
    - We present a novel approach to the star-galaxy separation problem that uses GPs and reap their benefits while solving many of the issues traditionally affecting them for classification of high-dimensional celestial image data.
    - We greatly improve the accuracy of the classification over a basic application of GPs while improving the computational efficiency and scalability of the method.

- [Imprint of baryons and massive neutrinos on velocity statistics](https://arxiv.org/abs/2010.05911)
    - 在TNG, EAGLE, OWLS里看重子物理过程对moments of pairwise velocity的影响
    - 假设 “mean pairwise velocity of the gas component follows that of the dark matter” 在10-20Mpc的尺度上是有bias的
    - Large scale velocity bias is mainly driven by stellar rather than AGN feedback; 如果不考虑，会影响kSZ效应的宇宙学限制
    - we examine how the first and the second moment of the pairwise velocity are affected by both the baryonic and the neutrino free-streaming effects for both the matter and gas components. 能够区分出来

- [DES Y1 results: Splitting growth and geometry to test ΛCDM](https://arxiv.org/abs/2010.05924)
    - To constrain a cosmological model where a subset of parameters -- focusing on Ωm -- are split into versions associated with structure growth (e.g. Ωgrowm) and expansion history (e.g. Ωgeom).
    - 用DES Year 1 (Y1) galaxy clustering and weak lensing来检验Lambda-CDM：We find no significant disagreement with Ωgrowm=Ωgeom.

- [Two Candidate High-Redshift X-ray Jets Without Coincident Radio Jets](https://arxiv.org/abs/2010.06535)
    - 两个高红移的radio QSO的延展X-ray探测：The extended X-ray emission is located along the line connecting the core to a radio knot or hotspot, favoring the interpretation of X-ray jets.
    - In the scenario of inverse Compton scattering of the cosmic microwave background (CMB), X-ray jets without a coincident radio counterpart may be common, and should be readily detectable to redshifts even beyond 3.2 due to the (1+z)4 increase of the CMB energy density compensating for the (1+z)−4 cosmological diminution of surface brightness.

- [Weighing Milky Way Satellites with LISA](https://arxiv.org/abs/2010.05918)
    - 利用LISA探测的双白矮星产生的引力波信号：Numerous and widespread DWDs have the potential to probe shapes, masses and formation histories of the stellar populations in the Galactic neighbourhood
    - Using a fiducial binary population synthesis model we find that for large satellites the stellar masses can be recovered to within 1) a factor two if the star formation history is known and 2) an order of magnitude when marginalising over different star formation history models.

- [Dust evolution in zoom-in cosmological simulations of galaxy formation](https://arxiv.org/abs/2010.05919)
    - 盘星系形成模拟中的尘埃演化：We couple an improved version of our previous treatment of dust evolution, which adopts the two-size approximation to estimate the grain size distribution, with the MUPPI star formation and feedback sub-resolution model.
    - Metal depletion and dust cooling affect the evolution of the system, causing substantial variations in its stellar, gas and dust content.

- [LoCuSS: The splashback radius of massive galaxy clusters and its dependence on cluster merger history](https://arxiv.org/abs/2010.05920)
    - **Relevant**
    - 用cluster member的stacked luminosity density profile探测到了SP特征
    - 看SP特征与星系团形成历史的相关：the most significant dependence of the splashback feature location and scale according to the presence or absence of X-ray emitting galaxy groups in the cluster infall regions.
    - Cluster that do not show massive infalling groups present the splashback feature at a smaller clustercentric radius rsp/r200,m=1.158±0.071 than clusters that are actively accreting groups rsp/r200,m=1.291±0.062, suggesting a correlation between the properties of the cluster potential and its accretion rate and merger history.
    - Clusters that are classified as old and dynamically inactive present stronger signatures of the splashback feature, with respect to younger, more active clusters.

- [Associations of dwarf galaxies in a ΛCDM Universe](https://arxiv.org/abs/2010.05922)
    - 在SMDP中看只有dwarf的星系系统，by applying the semi-analytic model of galaxy formation SAG
    - We analyse three different samples defined by log10(Mmax[M⊙h−1])=8.5,9.0 and 9.5. On average, our systems have typical sizes of ∼0.2Mpch−1, velocity dispersion of ∼30kms−1 and estimated total mass of ∼10^11M⊙h−1
    - Such large typical sizes suggest that individual members of a given dwarf association reside in different dark matter haloes and are generally not substructures of any other halo. 不是一个结构
    - Λ CDM model can naturally reproduce the existence and properties of dwarf galaxies associations without much difficulty.

- [Constraining the formation of NGC1052-DF2 from its unusual globular cluster population](https://arxiv.org/abs/2010.05930)
    - We apply a theoretical model that predicts the initial cluster mass function as a function of the galactic environment to investigate the origin of DF2's peculiar GC system
    - We predict that the GCs formed in an environment with very high gas surface density, 和现在的diffuse形态对比强烈
    - we propose that the GCs plausibly formed during a major merger at z∼1.3. The merger remnant must have undergone significant expansion of its stellar (and perhaps also its dark matter) component to reach its low present surface brightness

- [Spectroscopic classification of a complete sample of astrometrically-selected quasar candidates using Gaia DR2](https://arxiv.org/abs/2010.05934)
    - **Relevant**
    - We have built a complete candidate sample including 104 Gaia-DR2 point sources brighter than G<20 mag within one degree of the north Galactic pole (NGP), all with proper motions consistent with zero within 2σ uncertainty.
    - 其中大概60%是真的QSO：The selection efficiency of the zero-proper-motion criterion at high Galactic latitudes is thus ≈60%.
    - We find that the surface density of quasars is 20 deg−2, the redshift distribution peaks at z∼1.5, and that only eight systems (13+5−3%) show significant dust reddening.
    - Finally, we discuss how the astrometric selection can be improved to an efficiency of ≈70% by including an additional cut requiring parallaxes of the candidates to be consistent with zero within 2σ.

- [The parsec-scale HI outflows in powerful radio galaxies](https://arxiv.org/abs/2010.05996)
    - 射电星系中的HI吸收可能反应了AGN反馈的外流，也可能是喷流和ISM的相互作用
    - VLBI+VLA+WSRT观测：we find evidence for a clumpy structure of both the outflowing and the quiescent gas, consistent with predictions from numerical simulations.
    - The outflows include at least a component of relatively compact clouds (10^4-10^5Msun) often observed already at a few tens of pc (in projection) from the core

- [The End of Galaxy Surveys](https://arxiv.org/abs/2010.06064)
    - **Interesting**
    - Using an exposure time calculator, we define nominal surveys for extracting the useful information for three science cases: dark energy cosmology, galaxy evolution, and supernovae.
    - For optimistic assumptions, a 280m telescope with a marginally resolved focal plane of 20 deg2 operating at L2 could potentially exhaust the cosmological information content of galaxies in a 10 year survey.
    - We present scaling relations that show how we can progress toward the goal of exhausting the information content encoded in the shapes, positions, and colors of galaxies.

- [A catalog of broad morphology of Pan-STARRS galaxies based on deep learning](https://arxiv.org/abs/2010.06073)
    - We describe the design and implementation of a data analysis process for automatic broad morphology annotation of galaxie
    - Our analysis shows that a CNN combined with several filters is an effective approach for annotating the galaxies and removing unclean images

- [Effects of spin on constraining the seeds and growth of ≳10^9M⊙ supermassive black holes in z>6.5 Quasars](https://arxiv.org/abs/2010.06128)
    - We use the observations of 14 Quasars at z>6.5 with mass estimates to constrain their seeds and early growth, by self-consistently considering the spin evolution and the possibility of super-Eddington accretion.
    - If the accretion is coherent with single (or a small number of) episode(s), leading to high spins for the majority of accretion time, then the SMBH growth is relatively slow; and if the accretion is chaotic with many episodes and in each episode the total accreted mass is much less than the SMBH mass, leading to moderate/low spins, then the growth is relatively fast.

- [Double-peaked Lyman-α emission at z=6.803: a reionisation-era galaxy self-ionising its local HII bubble](https://arxiv.org/abs/2010.06241)
    - 红蓝峰的速度差距：suggests an extremely high escape fraction of ionising photons >59(51)%(2σ).
    - 非常年轻的星族，50Myr，有显著的[OIII]+Hbeta线；自身的电离辐射就可以产生一个可以解释蓝峰的电离泡
    - 可能在高红移有一定代表性

----

### Oct 14

- [AI-assisted super-resolution cosmological simulations](https://arxiv.org/abs/2010.06608)
    - 借鉴机器学习技术：Neural networks have been developed to learn from high-resolution (HR) image data, and then make accurate super-resolution (SR) versions of different low-resolution (LR) images
    - We are able to enhance the simulation resolution by generating 512 times more particles and predicting their displacements from the initial positions.
    - Furthermore, the generation process is stochastic, enabling us to sample the small-scale modes conditioning on the large-scale environment.

- [Targeted Likelihood-Free Inference of Dark Matter Substructure in Strongly-Lensed Galaxies](https://arxiv.org/abs/2010.07032)
    - We present here a new analysis pipeline that tackles these diverse challenges by bringing together many recent machine learning developments in one coherent approach, including variational inference, Gaussian processes, differentiable probabilistic programming, and neural likelihood-to-evidence ratio estimation
    - 可以实现：(a) fast reconstruction of the source image and lens mass distribution, (b) variational estimation of uncertainties, (c) efficient optimization of source regularization and other hyperparameters, and (d) marginalization over stochastic model components like the distribution of substructure.

- [Globular clusters as tracers of the dark matter content of dwarfs in galaxy clusters](https://arxiv.org/abs/2010.06590)
    - Dwarf中的GC未必满足球对称和动力学平衡的假设
    - 在Illustris模拟中找到9个星系团，进行particle tagging研究：Our results indicate that mass estimates are, on average, quite accurate in systems with GC numbers NGC≥10 and where the uncertainty of individual GC line-of-sight velocities is smaller than the inferred velocity dispersion, σGC. 但如果GC数量<10，bias就会比较常见
    - 也找到了一下 NGC1052-DF2 analogs: These DF2 analogs correspond to relatively massive systems at their infall time which have retained only 3-17 GCs and have been stripped of more than 95% of their dark matter.

- [Tracing the evolution of dust-obscured activity using sub-millimetre galaxy populations from STUDIES and AS2UDS](https://arxiv.org/abs/2010.06605)
    - STUDIES 450-μm SMG样本和AS2UDS 850-micron挑选的SMG的比较
    - The fainter 450-μm sample has ∼14 times higher space density than the brighter 850-μm sample at z ≲2, and a comparable space density at z = 2-3, before rapidly declining, suggesting LIRGs are the main obscured population at z ∼ 1-2, while ULIRGs dominate at higher redshifts
    - Using far-infrared luminosity, dust masses and an optically-thick dust model, we suggest that higher-redshift sources have higher dust densities due to inferred dust continuum sizes which are roughly half of those for the lower-redshift population at a given dust mass, leading to higher dust attenuation.

- [HI 21-centimetre emission from an ensemble of galaxies at an average redshift of one](https://arxiv.org/abs/2010.06617)
    - uGMRT观测：z=0.74-1.45 DEEP2 feild的观测; 叠加了7,653 blue, star-forming galaxies
    - We report a measurement of the average HI mass of star-forming galaxies at a redshift z≈1, by stacking their individual HI 21 cm emission signals. We obtain an average HI mass similar to the average stellar mass of the sample.
    - We also estimate the average star-formation rate of the same galaxies from the 1.4 GHz radio continuum, and find that the HI mass can fuel the observed star-formation rates for only ≈1−2 billion years in the absence of fresh gas infall.
    - Gas accretion onto galaxies at z<1 may have been insufficient to sustain high star-formation rates in star-forming galaxies. This is likely to be the cause of the decline in the cosmic star-formation rate density at redshifts below 1.

- [A Fully General, Non-Perturbative Treatment of Impulsive Heating](https://arxiv.org/abs/2010.06632)
    - **Interesting**
    - Impulsive encounters between astrophysical objects are usually treated using the distant tide approximation (DTA) for which the impact parameter, b, is assumed to be significantly larger than the characteristic radii of the subject, rS, and the perturber, rP. The perturber potential is then expanded as a multipole series and truncated at the quadrupole term.
    - 但当b很小，和subject的尺度差不多时，这个方法会高估交汇引起的速度变化, impulse.
    - This paper presents a fully general, non-perturbative treatment of impulsive encounters which is valid for any impact parameter

- [A correlation between the dark content of elliptical galaxies and their ellipticity](https://arxiv.org/abs/2010.06692)
    - **Relevant**
    - 14年一篇文章的详细内容；关于椭圆星系椭率和暗物质晕质量的关系
    - Such a correlation is either spurious --in which case it signals an ubiquitous systematic bias in elliptical galaxy observations or their analysis-- or genuine --in which case it implies in particular that at equal luminosity, flattened medium-size elliptical galaxies are on average five times heavier than rounder ones, and that the non-baryonic matter content of medium-size round galaxies is small

- [Clustering of red and blue galaxies around high-redshift 3C radio sources as seen by the Hubble Space Telescope](https://arxiv.org/abs/2010.06752)
    - Galaxy surface density maps reveal the clustering of red and blue galaxies around 3C radio galaxies and quasars at 1< z<2.5.
    - At z<1.5, the overdensity is dominated by red galaxies, while blue galaxies are more frequent in the periphery. With a few exceptions, the fainter galaxies contributing to the overdensity are bluer than the brighter galaxies
    - This and the brightness and color segregation of candidate cluster member galaxies leads us to conclude that at 1 < z < 1.5 the 3C sources are not just becoming galaxy groups. Rather we suggest that the foundation of a galaxy cluster with luminous red galaxies has largely been set, and the formation of the red sequence is still going on from a reservoir of blue galaxies in the periphery.
    - At z>1.5, overdensities are less frequent and progressively composed of blue galaxies.

- [The X-SHOOTER/ALMA sample of Quasars in the Epoch of Reionization. I. NIR spectral modeling, iron enrichment and broad emission line properties](https://arxiv.org/abs/2010.06902)
    - 有ALMA CII观测的38 luminous (M1450=−29.0 to −24.4) quasars at 5.78< z<7.54
    - The measured FeII/MgII flux ratio suggests that the broad line regions of all quasars in the sample are already enriched in iron. 和CII线比，MgII线有蓝移的证据
    - While we find all other broad emission line properties not to be evolving with redshift, the median CIV-MgII blueshift is much larger than found in low-redshift, luminosity-matched quasars

----

### Oct 15

- [Mixture Models for Photometric Redshifts](https://arxiv.org/abs/2010.07319)
    - **Useful**
    - We aim at estimates of the full photo-z probability distributions, and their uncertainties. We perform a probabilistic photo-z determination using Mixture Density Networks (MDN).
    - 基于SDSS-WISE观测：We use Infinite Gaussian Mixture models to classify the objects in our data-set as stars, galaxies or quasars, and to determine the number of MDN components to achieve optimal performance.
    -  Infinite Gaussian Mixture Models:
        - The IGMM is the GMM case with an undefined number of components, which will be optimised by the model itself, depending on the photometric data-set used
        - The IGMM describes a mixture of Gaussian distributions on the data population with an infinite (countable) number of components, using a Dirichlet process
    - Mixture Density Network
        - MDNs are a form of ANNs, which are capable of arbitrarily accurate approximation to a function and its derivatives based on the Universal Approximation Theorem

- [Probing dark energy with tomographic weak-lensing aperture mass statistics](https://arxiv.org/abs/2010.07376)
    - We forecast and optimize the cosmological power of various weak-lensing aperture mass (Map) map statistics for future cosmic shear surveys, including peaks, voids, and the full distribution of pixels 主要优点是可以探测质量分布的non-Gaussian区域
    - We develop a new tomographic formalism which exploits the cross-information between redshift slices (cross-Map) in addition to the information from individual slices (auto-Map) probed in the standard approach.
    - This demonstrates that the complementary cosmological information explored by non-Gaussian Map map statistics not only offers the potential to improve the constraints on the recent σ8 - Ωm tension, but also constitutes an avenue to understand the accelerated expansion of our Universe.

- [Removing the giants and learning from the crowd: a new SZ power spectrum method and revised Compton y-map analysis](https://arxiv.org/abs/2010.07797)
    - We devise a new method for analysing the y-map by introducing the survey completeness function, conventionally only used in the CNC analysis, in the yy-PS modeling 做两个分析，一个是包含了单独探测到的clusters的，一个是排除的
    - We carefully propagate the effect of completeness cuts on the non-Gaussian error contributions in the yy-PS analysis, highlighting the benefits of masking massive clusters.
    - Our analysis of the Planck yy-PS for the unresolved component yields a mass bias of b=0.15±0.04, consistent with the standard value (b≈0.2), in comparison to b=0.4±0.05 for the total yy-PS.
    - We find indications for this drift being driven by the CIB-tSZ cross correlation, which dominantly originates from clusters in the resolved component of the y-map.

- [The Effect of Impact Parameter on Tidal Disruption Events](https://arxiv.org/abs/2010.07318)
    - TDE数值模拟，用的代码叫MANGA: 改变碰撞参数beta，看fallback rate和peak光度如何变化
    - We show that the spread of energy in the debris and peak luminosity time (tpeak) are both directly related to the impact parameter. In particular, we find a β1/2 scaling for the energy spread for β=2−10 and a frozen evolution for β≳10

- [Constraints on the [CII] luminosity of a proto-globular cluster at z~6 obtained with ALMA](https://arxiv.org/abs/2010.07302)
    - 被星系团放大的一个z=6.16的球状星团前身：identify a 4-sigma tentative detection of [CII] emission with intrinsic luminosity L_CII=(2.9 +/- 1.4) 10^6 L_sun, one of the lowest values ever detected at high redshift
    - Our weak detection indicates a deficiency of [CII] emission, possibly ascribed to various explanations, such as a low-density gas and/or a strong radiation field caused by intense stellar feedback, and a low metal content.

- [The Launching of Cold Clouds by Galaxy Outflows. IV. Cosmic-Ray-Driven Acceleration](https://arxiv.org/abs/2010.07308)
    - 2-D数值模拟：cosmic-ray (CR) driven, radiatively-cooled cold clouds embedded in hot material, as found in galactic outflows
    - Thus the CR ray pressure in the bottleneck region has sufficient time to accelerate the cold clouds efficiently. Furthermore, radiative cooling has relatively little impact on these interactions.

- [IllustrisTNG and S2COSMOS: possible conflicts in the evolution of neutral gas and dust](https://arxiv.org/abs/2010.07309)
    - 强行让模拟和观测在z=0符合，看尘埃的演化：We find a lack of evolution in the DMFs derived from the simulations, in conflict with the rapid evolution seen in empirically derived estimates of the low redshift DMF
    - 观测上尘埃质量和恒星质量的比例也有很强的演化，但是TNG中的演化很少；可能和TNG中中性气体成分的演化也不够有关

- [The Dragonfly Wide Field Survey. II. Accurate Total Luminosities and Colors of Nearby Massive Galaxies and Implications for the Galaxy Stellar Mass Function](https://arxiv.org/abs/2010.07310)
    - **Relevant, Useful**
    - We construct a sample of 1188 massive galaxies with logM∗/M⊙>10.75 based on the Galaxy Mass and Assembly (GAMA) survey and measure their total luminosities and g−r colors.
    - We find that galaxies are brighter in the r band by an average of ∼0.05 mag and bluer in g−r colors by ∼0.06 mag compared to the GAMA measurements. 对恒星质量估计的影响不同
    - The total luminosities are larger by 5% but the mass-to-light ratios are lower by ∼10%.

- [LYRA I: Simulating the multi-phase ISM of a dwarf galaxy with variable energy supernovae from individual stars](https://arxiv.org/abs/2010.07311)
    - 基于AREPO的模型：It forms individual stars sampled from the initial mass function (IMF), and tracks their lifetimes and death pathways individually. Single supernova (SN) blast waves with variable energy are followed within the hydrodynamic calculation to interact with the surrounding interstellar medium (ISM)
    - 模拟一个孤立的10^10 Msun的暗物质晕：We demonstrate that the majority of supernovae are Sedov-resolved at our fiducial gas mass resolution of 4M⊙. 能产生外流
    - Clustered SN play a major role in enhancing the effectiveness of feedback, because the majority of explosions occur in low density material.
    - Accounting for variable SN energy affects the metallicity distribution function by altering the efficiency of metal mixing. Additionally, it alters the outflow behaviour, reducing the mass loading by a factor of 2-3 with respect to fixed energy models, thus allowing the galaxy to retain a higher fraction of mass and metals.

- [Stellar Velocity Dispersion and Dynamical Mass of the Ultra-Diffuse Galaxy NGC 5846_UDG1 from the Keck Cosmic Web Imager](https://arxiv.org/abs/2010.07313)
    - **Relevant**
    - VEGAS中找到的一个有很多球状星团的UDG：KCWI给出GC速度弥散度分布：σGC  = 17 ± 2 km/s.
    - 较高的速度弥散度意味着比较高的DM贡献；We find no evidence that the galaxy is rotating and is thus likely pressure-supported.
    - A cored mass profile is favoured when compared to our dynamical mass. 暗物质晕质量在2x10^11 Msun, overly massive halo

- [A Complex Luminosity Function for the Anomalous Globular Clusters in NGC1052-DF2 and NGC1052-DF4](https://arxiv.org/abs/2010.07324)
    - **Relevant**
    - 新的Keck和HST观测：The new analysis shows that the peak of the combined GC luminosity function remains at MV≈−9 mag. In addition, we find a subpopulation of less luminous GCs at MV≈−7.5 mag, where the near-universal GCLF peak is located.
    - The updated total number of GCs in both galaxies is 37+11.08−6.54. The number of GCs do not scale with the halo mass in either DF2 or DF4, suggesting that NGC is not directly determined by the merging of halos.

- [An extremely metal-deficient globular cluster in the Andromeda Galaxy](https://arxiv.org/abs/2010.07395)
    - **Interesting**
    - We report a massive GC in the Andromeda Galaxy (M31) that is extremely depleted in heavy elements. Its iron abundance is about 800 times lower than that of the Sun, and about three times lower than in the most iron-poor GCs previously known. It is also strongly depleted in magnesium.

- [SUPER III. Broad Line Region properties of AGN at z∼2](https://arxiv.org/abs/2010.07443)
    - SINFONI巡天：a blind search for AGN-driven outflows on X-ray selected AGN at redshift z∼2 with high (∼2 kpc) spatial resolution
    - We estimate BH masses in the range Log(MBH/M⊙)=8.4-10.8 and Eddington ratios λEdd =0.04-1.3. We confirm that the CIV line width does not correlate with the Balmer lines and the peak of the line profile is blue-shifted with respect to the [OIII]-based systemic redshift. CIV更多指示的是BLR中的外流
    - We confirm the strong dependence of the BLR wind velocity with the UV-to-Xray continuum slope, LBol and λEdd. 质量外流率在0.005-3 Msun/yr
    - We found an anti-correlation between the equivalent width of the [OIII] line with respect to the CIV shift, and a positive correlation with [OIII] outflow velocity.

- [On the broad line region configuration of the supermassive binary black hole candidate PG1302-102 in the relativistic Doppler boosting scenario](https://arxiv.org/abs/2010.07512)
    - We investigate several broad emission lines of PG1302-102 using archived UV spectra obtained by IUE, GALEX, and Hubble, to reveal the broad line emission region (BLR) properties of this BBH system under the Doppler boosting scenario.
    - We find that the broad lines Lyα, NV, CIV, and CIII] all show Gaussian-like profiles, and none of these lines exhibits obvious periodical variation.
    - If the Doppler boosting interpretation is correct, then the BLR is misaligned with the BBH orbital plane by an angle ∼51∘, which suggests that the Doppler boosted continuum variation has little effect on the broad line emission and thus does not lead to periodical line variation.

- [Broad-band selection, spectroscopic identification, and physical properties of a population of extreme emission line galaxies at 3<z<3.7](https://arxiv.org/abs/2010.07545)
    - Extreme emission line galaxies (EELGs) at 3< z <3.7
    - 19个有极强[OIII]发射线，2个有极强Halpha发射线的EELG：show, on average, higher specific star formation rates (sSFR) than the star-forming main sequence, low dust attenuation of E(B−V)≲0.1 mag, and high [OIII]/[OII] ratios of ≳3. 有很高的电离效率
    - 很可能是LyC leaker：they are low metallicity galaxies with higher ionization parameters and harder UV spectra than normal SFGs

- [Link between radio-loud AGNs and host-galaxy shape](https://arxiv.org/abs/2010.07622)
    - **Relevant**
    - LoTSS DR1 + SDSS分析15000个宁静星系中RLAGN对星系形态的影响
    - 在固定恒星质量，速度弥散度等性质上，RLAGN比例和星系的椭率没有关系；在非常高的150MHz光度上。RLAGNs are more likely to be found in massive, round galaxies
    - We argue that our results support the picture that high-power RLAGNs are more easily triggered in galaxies with a merger-rich history, while low-power RLAGNs can be triggered in galaxies growing mainly via secular processes
    - 把星系团里面和外面的RLAGN比较，发现上面结论与环境关系也不大

- [The nature of sub-millimetre galaxies I: A comparison of AGN and star-forming galaxy SED fits](https://arxiv.org/abs/2010.07934)
    - WHDF中的12个 LABOCA/ALMA 870micron SMG: 7/12 SMGs are best fitted with an obscured quasar model, a further 3/12 show no preference between AGN and star-forming templates, leaving only a z=0.046 spiral galaxy and one unidentified source
    - The vast majority (10/12) of bright SMGs are at least as likely to fit an AGN as a star-forming galaxy template.

----

### Oct 18

- [Morphometry as a probe of the evolution of jellyfish galaxies](https://arxiv.org/abs/2010.07944)
    - A901/A902星系团里的RPS星系：Our morphometric analysis shows that the ram pressure stripping candidates have peculiar concave regions in their surface brightness profiles
    - These profiles are less concentrated (lower S\'ersic indices) than other star forming galaxies that do not show morphological features of ram pressure stripping.

- [The volumetric star formation law for nearby galaxies -- Extension to dwarf galaxies and low-density regions](https://arxiv.org/abs/2010.07948)
    - This volumetric star formation (VSF) law is a single power-law with no break and a smaller intrinsic scatter with respect to the star formation laws based on the surface density. 在低金属丰度，低密度，HI主导的矮星系里测试VSF律
    - 依然成立：rho_SFR \propto rho_gas^2

- [Intrinsic Alignments in IllustrisTNG and their implications for weak lensing: Tidal shearing and tidal torquing mechanisms put to the test](https://arxiv.org/abs/2010.07951)
    - We find a significant alignment signal for elliptical galaxies (linear model), that increases with mass and redshift. Spiral galaxies (quadratic model) on the other hand exhibit a significant signal only for the most massive objects at z=1.
    - We show the quadratic model for spiral galaxies to break down at its fundamental assumptions, and simultaneously obtain a significant signal of spiral galaxies to align according to the linear model.

- [Hubble Space Telescope Observations of [O~III] Emission in Nearby QSO2s: Physical Properties of the Ionised Outflows](https://arxiv.org/abs/2010.08050)
    - A sample of twelve nearby (z < 0.12) luminous (L_bol > 1.6 x 10^45 erg s^-1) QSO2s: For the sample, masses are several times 10^3 - 10^7 solar masses and peak outflow rates are 9.3 x 10^-3 Msun/yr to 10.3 Msun/yr. The peak kinetic luminosities are 3.4 x 10^-8 to 4.9 x 10^-4 of the bolometric luminosity

- [The specific star formation rate function at different mass scales and quenching: A comparison between cosmological models and SDSS](https://arxiv.org/abs/2010.08173)
    - The eddington bias corrected Specific Star Formation Rate Function (sSFRF) at different stellar mass scales
    - 在质量大于10^10 Msun的地方，sSFR分布是bi-model的：The bi-modal form of the sSFRFs is not reproduced by a range of cosmological simulations (e.g. Illustris, EAGLE, Mufasa, IllustrisTNG) which instead generate mostly the star-forming population, while a bi-modality emerges in others (e.g. L-Galaxies, Shark, Simba).

- [Extinction-free Census of AGNs in the AKARI/IRC North Ecliptic Pole Field from 23-band Infrared Photometry from Space Telescopes](https://arxiv.org/abs/2010.08225)
    - 利用AKARI的9-band观测找AGN: we take advantage of the state-of-the-art spectral energy distribution (SED) modelling software, CIGALE, to find AGNs in mid-IR. We found 126 AGNs in the NEP-Wide field with this method.
    - We found that the AGN contribution is larger at higher redshifts for a given IR luminosity.

- [Velocity-inverted three-dimensional distribution of the gas clouds in the Type 2 AGN NGC1068](https://arxiv.org/abs/2010.08403)
    - 利用AGN附近1-10 pc内的有分辨的veloctiy map重构3-D几何分布
    - HST观测的NGC1068: this inner narrow-line region has indeed a hollow-cone structure, consistent with previous modeling results
    - The AGN obscuring "torus" is argued to be the inner optically thick part of this hollow-cone outflow, and its shadowed side would probably be associated with the molecular outflow seen in certain sub-mm lines.

- [The assembly bias of emission line galaxies](https://arxiv.org/abs/2010.08500)
    - **Relevant, Useful**
    - 基于MAPPINGS的根据SFH预测发射线性质的程序：https://github.com/aaorsi/get_emlines
    - We consider fixed number density samples where galaxies are selected by either their Hα, [OIII]λ5007 or [OII]λλ3727−3729 emission line luminosities. We investigate the assembly bias signatures of these samples 看和用恒星质量选的有什么不同。
    - Interestingly, we find that the [OIII]- and [OII]-selected samples display scale-dependent bias on large scales and that their assembly bias signatures are also scale-dependent.
    - The [OIII] and [OII] emitters that contribute most to the scale dependence tend to have a low gas-phase metallicity and are preferentially found in low-density regions.
    - 对宇宙学有影响：We find a slight tendency for the BAO peak to shift toward smaller scales for [OII] emitters and that β is scale-dependent at large scales

- [Extracting HI Astrophysics from Interferometric Intensity Mapping](https://arxiv.org/abs/2010.07985)
    - **Useful** 是Halomod的一个extension
    - Constraints on the small-scale HI power spectrum can break the degeneracy between the HI density ΩHI and the HI bias bHI.
    - 预测SKA的观测能力：For z∼0.1, we forecast that an accurate measurement of ΩHI up to 6% level precision and the large scale HI bias b0HI up to 1% level precision
    - Furthermore, given the number density of HI galaxies above a certain HI mass threshold, future surveys will also be able to constrain the HI Mass Function using only the HI shot noise

----

### Oct 19

- [Combining strong and weak lensing estimates in the Cosmos field](https://arxiv.org/abs/2010.08680)
    - We develop a framework to predict the covariance of strong lensing and galaxy shape measurements of cosmic shear on the basis of the small scale matter power-spectrum.
    - With a sample of three strong lensing shear measurements we present a 2-sigma detection of the cross-correlation signal between the two complementary measurements of cosmic shear along the identical line of sight.

- [The Third Data Release of the KODIAQ Survey](https://arxiv.org/abs/2010.09061)
    - KODIAQ DR3 consists of a fully-reduced sample of 727 quasars at 0.1 < z < 6.4 observed with ESI at moderate resolution (4000 < R < 10000).

- [Dynamical evolution of massive perturbers in realistic multi-component galaxy models I: implementation and validation](https://arxiv.org/abs/2010.08555)
    - We expand the semi-analytical framework developed in Bonetti et al. (2020) by including both a detailed implementation of the gravitational potential of exponential disc (modelled with a sech2 and an exponential vertical profile) and an accurate prescription for the dynamical friction experienced by massive perturbers in composite galaxy models featuring rotating disc structures.

- [WISDOM project -- VI. Exploring the relation between supermassive black hole mass and galaxy rotation with molecular gas](https://arxiv.org/abs/2010.08565)
    - We investigate the correlation between CO line widths and SMBH masses for two samples of galaxies with dynamical SMBH mass measurements, with respectively spatially-resolved and unresolved CO observations.
    - A tight correlation is also found between the de-projected CO line widths and the stellar velocity dispersions averaged within one effective radius. We apply our correlation to the COLD GASS sample to estimate the local SMBH mass function.

- [Planes of satellites around Milky Way/M31-mass galaxies in the FIRE simulations and comparisons with the Local Group](https://arxiv.org/abs/2010.08571)
    - We find that MW-like planes as spatially thin and/or kinematically coherent as observed are uncommon, but they do exist in our simulations. Spatially thin planes occur in 1-2 per cent of snapshots during z=0−0.2, and kinematically coherent planes occur in 5 per cent of snapshots. 在模拟中一般都不长寿, <500 Myr
        - 但如果存在group accretion的情况，plane则更频发，而且更长寿一些
    - We find that M31's satellite distribution is much more common: M31's satellites lie within about 1 sigma of the simulation median for every plane metric we consider.
    - Baryonic and dark matter-only simulations exhibit similar levels of planarity, even though baryonic subhalos are less centrally concentrated within their host halos.

- [Physical Explanation for the Galaxy Distribution on the (λR,ε) and (V/σ,ε) Diagrams or for the Limit on Orbital Anisotropy](https://arxiv.org/abs/2010.08586)
    - **Relevant**
    - 利用JAM模型探索fast-rotator在运动学关系上的分布：We use JAM to build mock samples of axisymmetric galaxies, assuming on average an oblate shape for the velocity ellipsoid (as required to reproduce the rotation of real galaxies), and limiting the radial anisotropy β to the range allowed by physical solutions.
    - The empirical anisotropy upper limit in real galaxies, and the corresponding observed distributions in the (λR,ε) and (V/σ,ε) diagrams, are due to the lack of physical axisymmetric equilibrium solutions at high β anisotropy when the velocity ellipsoid is close to oblate.

- [An updated detailed characterization of planes of satellites in the MW and M31](https://arxiv.org/abs/2010.08624)
    - 新的确定盘的方向的方法：finds the normal directions to the predominant planar configurations of satellites of a system, yielding for each a collection of planes of increasing member satellites
    - 对银河系：we identify a new plane with Nsat=39 as thin as the VPOS-3 (c/a∼0.2), and with roughly the same normal direction; so far the most populated plane that thin reported in the Local Group.
    - In M31 we discover a plane with Nsat=18 and c/a∼0.15, i.e., quality comparable to the GPoA, and perpendicular to it.

- [Investigating orientation effects considering angular resolution for a sample of radio-loud quasars using VLA observations](https://arxiv.org/abs/2010.08668)
    - 低分辨率影响射电星系的core光度测量，导致高估：at FIRST spatial resolution, core flux measurements are indeed systematically high even after considering the core-variability.
    - Our results empirically confirm that determination of radio core dominance requires high-spatial resolution data.

- [Extracting Galaxy Merger Timescales II: A new fitting formula](https://arxiv.org/abs/2010.08786)
    - **Useful**
    - We build on this previous work and propose a new model for τmerge that draws on insights derived from these simulations.
    - 旧模型的不足：tend to underpredict τmerge inside the host virial radius (R200) because tidal stripping is neglected, and overpredict it outside R200 because the host mass is underestimated.
    - We find that models that account for orbital angular momentum via the circular radius Rcirc underpredict (overpredict) τmerge for bound (unbound) systems.

- [Integral-Field Spectroscopy of Fast Outflows in Dwarf Galaxies with AGN](https://arxiv.org/abs/2010.09008)
    - An integral-field spectroscopic study of a sample of eight dwarf galaxies with known AGN and suspected outflows. 7个里面都看到了外流，且速度很快，median速度是240 km/s; 能延伸到几百pc和几kpc
    - The outflows appear to be primarily photoionized by the AGN rather than shocks or young, massive stars. 主要是AGN驱动的
    - A small but non-negligible portion of the outflowing material likely escapes the main body of the host galaxy and contributes to the enrichment of the circumgalactic medium.

- [A Framework for Multiphase Galactic Wind Launching using TIGRESS](https://arxiv.org/abs/2010.09090)
    - **Useful**
    - TIGRESS模拟外流：<10^4 K的冷气体成分携带大部分质量；>10^6 K的高温气体成分携带大部分能量
    - Both components have a broad distribution of outflow velocity, and especially for cool gas this implies a varying fraction of escaping material depending on the halo potential.
    - Develop straightforward analytic formulae for the joint probability density functions (PDFs) of mass, momentum, energy, and metal loading as distributions in outflow velocity and sound speed. 提供了一个模型：https://github.com/changgoo/Twind

- [Brightest Cluster Galaxies: the centre can(not?) hold](https://arxiv.org/abs/2010.09617)
    - **Relevant**
    - 很多BCG都不在X-ray气体的中心，且相对于星系团平均系统速度存在peculiar velocity;dan BCG依然与星系团质量分布有很好的alignment
    - To account for these observations BCGs must undergo mergers preferentially along their major axis, the main infall direction. Such BCGs may be oscillating within the cluster potential after having been displaced by mergers or collisions
    - 样本：Andrade-Santos et al. (2017), 164 clusters in Planck SZ sample at z<0.35; and 100 clusters with z<=0.30 都有Chandra观测

- [The PAU Survey: Intrinsic alignments and clustering of narrow-band photometric galaxies](https://arxiv.org/abs/2010.09696)
    - Measure the projected 3D clustering and IA for flux-limited, faint galaxies (i<22.5) out to z∼0.8
    - We make robust null detections of IA for blue galaxies and tentative detections of radial alignments for red galaxies (∼1−2σ), over scales 0.1−18h−1Mpc. 和利用光谱的GAMA巡天的结论类似

----

### Oct 20

- [Active Galactic Nuclei as Factories for Eccentric Black Hole Mergers](https://arxiv.org/abs/2010.09765)
    - Here we show that AGN-disk environments naturally lead to a very high fraction of highly eccentric mergers, if interactions between binaries and singles are frequent, and the interactions are constrained to a plane representing the AGN-disk.
    - We find in our fiducial AGN-disk model that up to ∼70% of all black hole mergers could appear with an eccentricity >0.1 in LIGO/Virgo.

- [Cosmic shear power spectra in practice](https://arxiv.org/abs/2010.09717)
    - https://github.com/xC-ell/ShearCl
    - Lensing shear, however, is only sampled at the positions of galaxies with measured shapes in the catalog, making its associated sky window function one of the most complicated amongst all projected cosmological probes of inhomogeneities, as well as giving rise to inhomogeneous noise. 所以Cosmic shear大都是在real space空间进行，而不是在傅里叶空间用Power spectrum
    - This paper contains a study of the main complications associated with estimating and interpreting shear power spectra, and presents fast and accurate methods to estimate two key quantities needed for their practical usage: the noise bias and the Gaussian covariance matrix, fully accounting for survey geometry

- [κTNG: Effect of Baryonic Processes on Weak Lensing with IllustrisTNG Simulations](https://arxiv.org/abs/2010.09731)
    - **Relevant**
    - https://www.columbialensing.org
    - https://github.com/0satoken/kappaTNG
    - We quantify the baryonic effects on the WL angular power spectrum, one-point probability distribution function (PDF), and number counts of peaks and minima.
    - We find that baryonic processes reduce the small-scale power, suppress the tails of the PDF, peak and minimum counts, and change the total number of peaks and minima.
    - The κTNG suite includes 10,000 realisations of 5×5deg2 maps for 40 source redshifts up to zs=2.6, well covering the range of interest for existing and upcoming weak lensing surveys.

- [Abell 1430: A merging cluster with exceptional diffuse radio emission](https://arxiv.org/abs/2010.10331)
    - LoTSS+JVLA观测：We find that Abell 1430 consists of two components, namely A1430-A and A1430-B. We speculate that the two components undergo an off-axis merger. The more massive component shows diffuse radio emission which can be classified as radio halo showing a low radio power given the mass of the cluster.
    - There is extended diffuse radio emission, dubbed as the `Pillow', which is apparently related to A1430-B and thus related to low density intracluster or intergalactic medium.

- [Extended Fast Action Minimisation method: application to SDSS-DR12 Combined Sample](https://arxiv.org/abs/2010.10456)
    - The first application of the extended Fast Action Minimization method (eFAM) to a real dataset, the SDSS-DR12 Combined Sample, to reconstruct galaxies orbits back-in-time, their two-point correlation function (2PCF) in real-space, and enhance the baryon acoustic oscillation (BAO) peak.
    - eFAM successfully removes the anisotropies due to redshift-space distortion at all redshifts including that of the survey, allowing us to decrease the number of free parameters in the model and fit the full-shape of the back-in-time reconstructed 2PCF well beyond the BAO peak.

- [The galaxy "missing dark matter" NGC1052-DF4 is undergoing tidal disruption](https://arxiv.org/abs/2010.09719)
    - **Relevant**
    - Deep optical imaging of the system has detected tidal tails in this object caused by its interaction with its neighbouring galaxy NGC1035.
    - As stars are more centrally concentrated than the dark matter, the tidal stripping will remove a significant percentage of the dark matter before affecting the stars of the galaxy. Only ~7% of the stellar mass of the galaxy is in the tidal tails, suggesting that the stars of NGC1052-DF4 are starting only now to be affected by the interaction

- [The impact of the halo spin-concentration relation on disc scaling laws](https://arxiv.org/abs/2010.09727)
    - 为什么经典标度关系：TF, mass-size, mass-j关系的residual和spin以及concentration等halo参数关系不大
    - We show that a possible solution is that such secondary parameters are correlated amongst themselves, in a way that removes correlations in observable space. 如果halo spin和concentration有反相关，那么可以解释这种现象

- [Magnetogenesis around the first galaxies: the impact of different field seeding processes on galaxy formation](https://arxiv.org/abs/2010.09729)
    - Study the evolution of magnetic fields generated by charge segregation ahead of ionization fronts during the Epoch of Reionization; 并和Biermann battery, injection from supernovae, and an imposed seed field at redshift z≳127等机制比较
    - 所有的机制都能产生磁场并影响星系演化，而且在z<1.5后几乎无法区分
    - 在小质量星系的低密度气体中可能可以区分：Low-density gas and haloes below a seed-dependent mass threshold retain memory of the initial magnetic field.
    - 可能还是Biermann电池机制更有效: Magnetic fields can be created by the vorticity-induced relative motion of ions and electrons, a process dubbed Biermann battery (Biermann 1950).

- [GASP XXIX -- Unwinding the arms of spiral galaxies via ram-pressure stripping](https://arxiv.org/abs/2010.09733)
    - 看RPS机制对盘星系旋臂的unwinding作用：We first confirm the unwinding nature, finding the spiral arm pitch angle increases radially in 10 stripped galaxies and also simulated face-on and edge-on stripped galaxies
    - We find only younger stars in the unwound component, while older stars in the disc remain undisturbed.
    - Unwinding can occur due to differential ram-pressure caused by the disc rotation, causing stripped material to slow and "pile-up".
    - The pattern is fairly short-lived (<0.5Gyr) in the stripping process, occurring during first infall and eventually washed out by the ICM wind into the tail of the jellyfish galaxy.

- [Confirmation of stellar masses and potential light IMF in massive quiescent galaxies at 3<z<4 using velocity dispersions measurements with MOSFIRE](https://arxiv.org/abs/2010.09738)
    - **Relevant, Interesting**
    - MOSFIRE观测4个3.2 < z < 3.7的大质量quiscent星系，利用恒星速度弥散度限制动力学质量:We find high velocity dispersions of order σe∼250 km/s based on strong Balmer absorption lines
    - Investigating the evolution at constant velocity dispersion between z∼3.5 and z∼2, we find a large increase in effective radius 0.35±0.12 dex and in dynamical-to-stellar mass ratio < log(Mdyn/M*)> of 0.25±0.08 dex, with low expected contribution from dark matter.
    - The dynamical masses for our z∼3.5 sample are consistent with the stellar masses for a Chabrier initial mass function (IMF), with the ratio < log(Mdyn/M∗Ch) > = -0.13±0.10 dex suggesting an IMF lighter than Salpeter is common for massive quiescent galaxies at z>3

- [Bayesian AGN Decomposition Analysis for SDSS Spectra: A Correlation Analysis of [OIII]λ5007 Outflow Kinematics with AGN and Host Galaxy Properties](https://arxiv.org/abs/2010.09748)
    - Bayesian AGN Decomposition Analysis for SDSS Spectra (BADASS)
    - We use BADASS to perform a correlation analysis of 63 SDSS type 1 AGNs with evidence of strong non-gravitational outflow kinematics in the [OIII]λ5007 emission feature.
    - We confirm findings from previous studies that show the core of the [OIII] profile is a suitable surrogate for stellar velocity dispersion σ∗, however there is evidence that the core experiences broadening that scales with outflow velocity.
    - We find sufficient evidence that σ∗, [OIII] core dispersion, and the non-gravitational outflow dispersion of the [OIII] profile form a plane whose fit results in a scatter of ∼0.1 dex.

- [Hydrodynamic simulations of an isolated star-forming gas cloud in the Virgo cluster](https://arxiv.org/abs/2010.09758)
    - 试图用模拟解释SECCO-1：We present a suite of three-dimensional, high-resolution hydrodynamic simulations that follow the evolution of a massive (10^7 M_sun) pressure confined, star-forming neutral gas cloud moving through a hot intra-cluster medium (ICM)
    - The survivability of the cold gas in the simulated clouds is granted on timescales of the order of 1 Gyr, with final cold gas fractions generally >0.75. 最终的结果是在外部热气体包围下达到压力平衡的对称气体云
    - In our simulation with star formation, star formation begins immediately, it peaks at the earliest times and decreases monotonically with time. Inhomogeneous supernova explosions are the cause of an asymmetric shape of the gas cloud, facilitating the development of instabilities and the decrease of the cold gas fraction.

- [Wolf-Rayet stars in the Antennae unveiled by MUSE](https://arxiv.org/abs/2010.09781)
    - Up to 38 young star-forming complexes with evident contribution from Wolf-Rayet (WR) stars are unveiled.
    - The total estimated number of WR stars in the Antennae is 4053 ± 84, of which there are 2021 ± 60 WNL and 2032 ± 59 WC-types.

- [Improvements to Pan-STARRS1 Astrometry Using Gaia](https://arxiv.org/abs/2010.09798)
    - **Useful**
    - The cross match between Gaia and PS1 reveals residuals that are correlated on a scale of about 1 arcmin. We apply a spatially adaptive correction algorithm for all PS1 objects having more than two detections to reduce these residuals and align the object positions to Gaia.
    - The residuals for the corrected positions are smallest for objects with the most point-like morphologies and with intermediate magnitudes of about 17 mag. The residual errors in declination are systematically larger than those in right ascension; the declination errors increase with zenith angle in proportion to the air mass of the observations. Declination positional residuals at a given declination generally vary with color and are consistent with the effects of differential atmospheric refraction.

- [Evidence for Two Distinct Broad-Line Regions from Reverberation Mapping of PG 0026+129](https://arxiv.org/abs/2010.09871)
    - Hbeta宽线有两个成分，中等宽度IC和极宽的成分VBC：The velocity-resolved delays show consistent results: lags of ∼30--50 days at the core of the broad Hβ line and roughly zero lags at the wings. HβIC has a redshift of ∼400 km s−1 which seems to be stable for nearly 30 years by comparing with archived spectra, and may originate from an infall.
    - Both the double-peaked profile and the near-zero lag suggest that HβVBC comes from a region associated with the part of the accretion disc that emits the optical continuum.

----

### Oct 21

- [Eccentric Black Hole Mergers in Active Galactic Nuclei](https://arxiv.org/abs/2010.10526)
    - We derive the eccentricity distribution of BH mergers in AGN disks
    - We find that eccentricity is mainly due to binary-single (BS) interactions, which lead to most BH mergers in AGN disks having a significant eccentricity at 0.01Hz,

- [TDE Hosts are Green and Centrally Concentrated: Signatures of a Post-Merger System](https://arxiv.org/abs/2010.10738)
    - 19个ZTF TDE的研究：We find that the ZTF sample of TDE hosts is dominated by compact "green valley" galaxies.
    - We present host galaxy spectra which show that E+A galaxies are overrepresented in the ZTF sample by a factor of ≈22
    - The combination of both green colors and high S\'ersic index of the typical TDE host galaxy could be explained if the TDE rate is temporarily enhanced following a merger that leads to a higher central concentration of stars.

- [Degeneracies between baryons and dark matter: the challenge of constraining the nature of dark matter with JWST](https://arxiv.org/abs/2010.10520)
    - We use a semi-empirical model of galaxy formation to investigate the extent to which uncertainties in the implementation of baryonic physics may be degenerate with the predictions of two different models of dark matter -- Cold Dark Matter (CDM) and a 7 keV sterile neutrino
    - 看z=4的UVLF：We find that while at fixed star formation efficiency, ε, there are marked differences in the abundance of faint galaxies in the two dark matter models at high-z, these differences are mimicked easily by varying ε in the same dark matter model.
    - Our results suggest that JWST will likely be more informative in constraining baryonic processes operating in high-z galaxies than it will be in constraining the nature of dark matter.

- [Linking globular cluster formation at low and high redshift through the age-metallicity relation in E-MOSAICS](https://arxiv.org/abs/2010.10522)
    - 比较大质量星团的 age-metallicity relation (AMR)；看YMC，中等年龄星团，GC是否有相同的物理形成机制
    - We also find that the metallicity at which the AMR saturates increases with galaxy mass, which is also found for the field star AMRs. This suggests that relatively low-metallicity clusters can still form in dwarfs galaxies.
    - We suggest that ancient GCs share their formation mechanism with IACs and YMCs, in which GCs are the result of a universal process of star cluster formation during the early episodes of star formation in their host galaxies.

- [The Landscape of Galaxies Harboring Changing-Look Active Galactic Nuclei in the Local Universe](https://arxiv.org/abs/2010.10527)
    - We find that CL AGN hosts primarily reside in the so-called green valley that is located between spiral-like star-forming galaxies and dead elliptical 和TDE hosts有类似之处
    - CL AGN hosts have low galaxy asymmetry indicators, suggesting that secular evolutionary processes (the influence of bars and spirals, and possibly minor mergers) might be the primary mechanism for transporting gas to the vicinity of the supermassive black hole (SMBH) rather than major mergers 星系内的久期演化对提供气体很重要
    - We find that CL AGN hosts are associated with SMBHs residing in high density pseudo-bulges and appear to overlap most significantly with the population of low-ionization nuclear emission-line region (LINER) galaxies. 和TDE host也很类似

- [The stochastic enrichment of Population II stars](https://arxiv.org/abs/2010.10532)
    - 用stochastic chemical enrichment模型研究银河系中贫金属恒星的Mg, Ca, Ni, and Fe丰度的scatter
    - For our choice of stellar yields, our model suggests that the most metal-poor stars were enriched, on average, by N*=5^{+13}_{-3} (1 sigma) Population III stars. 与高红移DLA给出的推断类似
    - The inferred IMF is consistent with that of a Salpeter distribution and there is a preference towards ejecta from minimally mixed hypernovae.
    - We suggest that this method has the potential to constrain the multiplicity of the first generation of stars, but this will require: (1) a stellar sample whose systematic errors are well understood; and, (2) documented uncertainties associated with nucleosynthetic yields.

- [The sensitivity of stellar feedback to IMF averaging versus IMF sampling in galaxy formation simulations](https://arxiv.org/abs/2010.10533)
    - 模拟里使用的feedback机制是IMF平均过的：star particles are assumed to represent single stellar populations that fully sample the IMF.
    - We find that if supernovae are the only form of feedback, triggering individual supernovae from IMF averaged rates gives identical results to IMF sampling.
    - We find that photoionization is more effective at regulating star formation when IMF averaged rates are used, creating more, smaller H II regions than the rare, bright sources produced by IMF sampling.

- [Dependence of the IRX-β dust attenuation relation on metallicity and environment](https://arxiv.org/abs/2010.10538)
    - z=2.0-2.5的field和proto-cluster星系比较：We find no significant dependence of the IRX-β trend on environment.
    - We find that at a given β, IRX is highly correlated with metallicity, and less correlated with mass, age, and sSFR.
    - 金属丰度才是主因：We conclude that, of the physical properties tested here, metallicity is the primary physical cause of the IRX-β scatter, and the IRX correlation with mass is presumably due to the mass dependence on metallicity.
    - UV attenuation curve steepens with decreasing metallicity, and spans the full range of slope possibilities from a shallow Calzetti-type curve for galaxies with the highest metallicity in our sample (12+log(O/H)~8.6) to a steep SMC-like curve for those with 12+log(O/H)~8.3. 使用的消光率不对会对总UV消光和SFR的估计产生很大的影响

- [The CGM-GRB Study II: Outflow-Galaxy Connection at z ~ 2-6](https://arxiv.org/abs/2010.10540)
    - 看GRB host里的外流性质：outflow column density (Nout), maximum outflow velocity (Vmax), and normalized maximum velocity (Vnorm = Vmax/Vcirc,halo, where Vcirc,halo is the halo circular velocity).
    - Observe clear trends of Nout and Vmax with increasing SFR in high-ion-traced outflows, with a stronger (> 3σ) Vmax−SFR correlation 高电离气体的外流可以SF挂钩
    - The kinematic correlations of warm outflows (traced by high-ions) with SFR are similar to those observed for star-forming galaxies at low redshifts. The correlations with SFR are weaker in low-ion species

- [Mg II and Fe II fluxes of luminous quasars at z ~ 2.7 and the Baldwin effect in flux-to-abundance conversion for chemical evolution of quasars at high redshifts](https://arxiv.org/abs/2010.10548)
    - NTT上的WINERED光谱仪观测：we proposed a method to derive the [Mg/Fe] abundance ratio and the [Fe/H] abundance by correcting the dependence of EW(Mg II) and EW(Fe II) on the Eddington ratio.
    - Baldwin effect对丰度测量也有影响：we further investigated the dependence of EWs on luminosity, which is known as the Baldwin effect (BEff). Additional correction for the BEff significantly affects the derived chemical abundances for the six luminous quasars at z ~ 2.7

- [uGMRT detection of associated HI 21 cm absorption at z = 3.5](https://arxiv.org/abs/2010.10565)
    - uGMRT detection of Hi 21-cm absorption associated with the radio source 8C 0604+728, at z = 3.52965
    - The luminosity and photon rate at later epochs are approx 6.2 and approx 1.7 times higher than thresholds suggested in the literature above which all the neutral hydrogen in the AGN host galaxy is expected to be ionised. The detection demonstrates that neutral hydrogen can survive in the host galaxies of AGNs with high ultraviolet luminosities.

- [Fast Outflows in Hot Dust-Obscured Galaxies with Keck/NIRES](https://arxiv.org/abs/2010.10641)
    - NIRES观测24个Hot-DOGS： Of the 17 targets with a clear detection of the [O III]λ5007A emission line, 15 display broad blueshifted and asymmetric line profiles, with widths ranging from 1000 to 8000 km s−1 and blueshifts up to 3000 km s−1. 存在大质量电离外流；星系具有非常高的SFR
    - The combination of ongoing star formation, massive outflows, and high Eddington ratios suggest Hot DOGs are a transitional phase in galaxy evolution.

- [On the Presence of a Universal Acceleration Scale in Elliptical Galaxies](https://arxiv.org/abs/2010.10779)
    - **Relevant**
    - MaNGA和ATLAS：15 MaNGA and 4 ATLAS3D slow-rotator E0 (i.e. nearly spherical) galaxies. 看速度弥散度轮廓
    - Bayesian inference indicates that all 19 galaxies are consistent with a universal acceleration of g†=1.5+0.9−0.6×10−10~m~s−2
    - This universality remains if we include 12 additional non-E0 slow-rotator elliptical galaxies from ATLAS3D. Finally, the universal acceleration from MaNGA and ATLAS3D is consistent with that for rotationally supported galaxies

- [A Large Massive Quiescent Galaxy Sample at z~1.2](https://arxiv.org/abs/2010.10941)
    - **Relevant**
    - 基于HSC数据：a simple color-magnitude selection and obtain a large sample of 33,893 massive quiescent galaxies at intermediate redshifts (1< z<1.5), have high stellar masses at log(M*/M_sun)>10.5, with a median of log(M*/M_sun)=11.0
    - 利用和HST CANDELS重合的部分验证了Early type morphogloy
    - ur sample is 7-20 times larger at the massive end (log(M*/M_sun)>10.5) than any existing samples obtained in previous surveys

- [Dual Effects of Ram Pressure on Star Formation in Multi-phase Disk Galaxies with Strong Stellar Feedback](https://arxiv.org/abs/2010.11028)
    - Radiation-hydrodynamics simulations of an isolated disk galaxy embedded in a 10^11 Msun dark matter halo with various ICM winds mimicking the cluster outskirts (moderate) and the central environment (strong).
    - RP既能quench也能trigger SF; depending on the strength of the winds. HI and H2 in the outer galactic disk are significantly stripped in the presence of the moderate winds, whereas turbulent pressure provides support against ram pressure in the central region where star formation is active.
    - Moderate ICM winds能加速气体坍缩，提升SFR；Strong wind能快速移除气体, suppressing the star formation by a factor of two within ~200 Myr.

----

### Oct 22

- [C3-Cluster Clustering Cosmology I. New constraints on the cosmic growth rate at z~0.3 from redshift-space clustering anisotropies](https://arxiv.org/abs/2010.11206)
    - **Relevant**
    - SDSS里的光谱挑选的clusters，We measure the transverse and radial wedges of the two-point correlation function of the selected clusters. Modelling the redshift-space clustering anisotropies, we provide the first constraints on the linear growth rate from cluster clustering. 星系团质量可以作为linear bias的prior
    - We get the value of the growth rate times the matter power spectrum normalisation parameter fσ8=0.46±0.03, at an effective redshift z~0.3.

- [Preliminary Target Selection for the DESI Quasar (QSO) Sample](https://arxiv.org/abs/2010.11280)
- [Preliminary Target Selection for the DESI Emission Line Galaxy (ELG) Sample](https://arxiv.org/abs/2010.11281)
- [Preliminary Target Selection for the DESI Luminous Red Galaxy (LRG) Sample](https://arxiv.org/abs/2010.11282)
- [Preliminary Target Selection for the DESI Bright Galaxy Survey (BGS)](https://arxiv.org/abs/2010.11283)
    - **Relevant, SSST**
    - 3个Research notes，关于DESI选源的
    - https://data.desi.lbl.gov/public/ets/target/catalogs/
    - https://desidatamodel.readthedocs.io/en/latest/
    - QSO：he DESI survey will measure large-scale structure using quasars as direct tracers of dark matter in the redshift range 0.9< z<2.1 and using quasar Ly-α forests at z>2.1. We present two methods to select candidate quasars for DESI based on imaging in three optical (g,r,z) and two infrared (W1,W2) bands.
    - ELG：The selection consists of a g-band magnitude cut and a (g−r) vs. (r−z) color box, which we validate using HSC/PDR2 photometric redshifts and DEEP2 spectroscopy. The ELG target density should be ∼2400 deg−2, with ∼65% of ELG redshifts reliably within a redshift range of 0.6< z<1.6.
    - LRG：Here we present a preliminary version of the DESI LRG target selection developed using Legacy Surveys Data Release 8 g, r, z and W1 photometry. This selection yields a sample with a uniform surface density of ∼600 deg−2and very low predicted stellar contamination and redshift failure rates.
    - BGS: DESI BGS will comprise two target classes: (i) BRIGHT (r<19.5~mag), and (ii) FAINT (19.5< r<20~mag). The selection results in a total density of ∼800 objects/deg2 for the BRIGHT and ∼600 objects/deg2 for the FAINT selections.

- [Euclid preparation: IX. EuclidEmulator2 -- Power spectrum emulation with massive neutrinos and self-consistent dark energy perturbations](https://arxiv.org/abs/2010.11288)
    - **CSST**
    - EuclidEmulator2 - a fast and accurate predictor for the nonlinear correction of the matter power spectrum.
    - Percent-level accurate emulation is now supported in the eight-dimensional parameter space of w0waCDM+∑mνmodels between redshift z=0 and z=3 for spatial scales within the range 0.01 h/Mpc ≤k≤ 10 h/Mpc.
    - https://github.com/miknab/EuclidEmulator2

- [Measuring Cosmological Distances Using Cluster Edges as a Standard Ruler](https://arxiv.org/abs/2010.11324)
    - **Relevant, Interesting**
    - 关于最近从redMaPPer cluster中相空间里看到的edge：Because the spatial extent of a cluster is correlated with the amplitude of the velocity dispersion profile, we can utilise this feature as a gravity-calibrated standard ruler. Specifically, the amplitude of the velocity dispersion data allows us to infer the physical cluster size.
    - Assuming the relation between cluster radius and cluster velocity dispersion can be calibrated from simulations, we forecast that with existing data from the Sloan Digital Sky Survey (SDSS) we will be able to measure the Hubble constant with 3% precision.

- [Photometric redshifts for galaxies in the Subaru Hyper Suprime-Cam and unWISE and a catalogue of identified clusters of galaxies](https://arxiv.org/abs/2010.11551)
    - **Relevant**
    - HSC PDR2 + unWISE photo-z for 14.68M galaxies: we identify 21,661 clusters of galaxies, among which 5537 clusters have redshifts z>1 and 642 clusters have z>1.5
    - Cluster richness and mass are estimated, and these clusters have an equivalent mass of M_{500} > 0.7*10^{14} Msun.

- [FlowPM: Distributed TensorFlow Implementation of the FastPM Cosmological N-body Solver](https://arxiv.org/abs/2010.11847)
    - https://github.com/modichirag/flowpm
    - Mesh-TensorFlow for GPU-accelerated, distributed, and differentiable simulations
    - We also demonstrate how this novel tool can be used for efficiently solving large scale cosmological inference problems, in particular reconstruction of cosmological fields in a forward model Bayesian framework with hybrid PM and neural network forward model

- [STARFORGE: Toward a comprehensive numerical model of star cluster formation and feedback](https://arxiv.org/abs/2010.11254)
    - We use the GIZMO code with the MFM mesh-free Lagrangian MHD method, augmented with new algorithms for gravity, timestepping, sink particle formation and accretion, stellar dynamics, and feedback coupling.
    - Modules for mass-injecting feedback (winds, SNe, and jets) inject new gas elements on-the-fly, eliminating the lack of resolution in diffuse feedback cavities otherwise inherent in Lagrangian methods.

- [DeepGalaxy: Deducing the Properties of Galaxy Mergers from Images Using Deep Neural Networks](https://arxiv.org/abs/2010.11630)
    - https://github.com/maxwelltsai/DeepGalaxy
    - We propose DeepGalaxy, a visual analysis framework trained to predict the physical properties of galaxy mergers based on their morphology. Based on an encoder-decoder architecture, DeepGalaxy encodes the input images to a compressed latent space z, and determines the similarity of images according to the latent-space distance.
    - Without having to carry out expensive numerical simulations, DeepGalaxy makes inferences of the physical properties of galaxy mergers directly from images

- [Parsec-scale properties of the radio brightest jetted AGN at z > 6](https://arxiv.org/abs/2010.11193)
    - The milliarcsecond angular resolution of our VLBA observations at 1.5, 5 and 8.4 GHz unveils a bright one-sided jet extended for ∼500 parsecs in projection. This high-z radio-loud AGN is resolved into multiple compact sub-components, embedded in a more diffuse and faint radio emission
    - If PSO J0309+27 is a genuine blazar, as suggested by its X-ray properties, then we find that its bulk Lorentz factor must be relatively low (less than 5). Such value would be in favour of a scenario currently proposed to reconcile the paucity of high-z blazars with respect to current predictions

- [The MURALES survey. III. Completing the MUSE observations of 37 3C low-z radio galaxies](https://arxiv.org/abs/2010.11195)
    - These observations reveal emission line regions (ELRs) extending several tens of kiloparsec in most objects. The gas velocity shows ordered rotation in 25 galaxies, but in several sources it is highly complex.
    - 射电形态和发射线性质可能有联系：In the ten FRI sources the line emission region is generally compact, only a few kpc in size, and only in one case it exceeds the size of the host. Conversely, all but two of the FRII galaxies show large-scale structures of ionized gas.
    - The median extent is 16 kpc with the maximum reaching a size of ~80 kpc.

- [The quiescent fraction of isolated low surface brightness galaxies: Observational constraints](https://arxiv.org/abs/2010.11210)
    - **Relevant**
    - 基于HSC PDR2，但没有做到很深的SB；we present a new catalogue of 479 LSBGs, identified in deep optical imaging data from the Hyper Suprime-Cam Subaru Strategic Program (HSC-SSP)
    - We estimate environmental densities for a subsample of 215 sources by statistically associating them with nearby spectroscopic galaxies from the overlapping GAMA spectroscopic survey. We find that the blue LSBGs are statistically consistent with being spatially randomised with respect to local spectroscopic galaxies, implying they exist predominantly in low-density environments. However, the red LSBG population is significantly spatially correlated with local structure.
    - We find that 26+/-5% of isolated, local LSBGs belong to the red population

- [The Radio Galaxy Population in the SIMBA SImulations](https://arxiv.org/abs/2010.11225)
    - Simba grows black holes via gravitational torque limited accretion from cold gas and Bondi accretion from hot gas, and employs AGN feedback including jets at low Eddington ratios.
    - Within RLAGN we define high and low excitation radio galaxies (HERGs and LERGs) based on their dominant mode of black hole accretion: torque limited accretion representing feeding from a cold disk, or Bondi representing advection-dominated accretion from a hot medium.
    - Quiescent galaxies with AGN-dominated radio flux dominate the RLF at > ∼10^22−23 W Hz−1, while star formation dominates at lower radio powers
    - While LERGs dominate among most massive galaxies with the largest black holes and HERGs dominate at high specific star formation rates, they otherwise largely populate similar-sized dark matter halos and have similar host galaxy properties

- [Evaluating hydrodynamical simulations with green valley galaxies](https://arxiv.org/abs/2010.11232)
    - 比较EAGLE/TNG100; 用4000A break来定义Red-Green-Blue: Both simulations match the fraction of AGN in the green-valley. However, they over-produce quiescent GV galaxies with respect to observations, with IllustrisTNG yielding a higher fraction of quiescent GV galaxies than EAGLE
    - We find EAGLE GV galaxies quench their star formation early, but undergo later episodes of star formation, matching observations. In contrast, IllustrisTNG GV galaxies have a more extended SFH, and quench more effectively at later cosmic times, producing the excess of quenched galaxies in GV compared with SDSS

- [STARFORGE: The effects of protostellar outflows on the IMF](https://arxiv.org/abs/2010.11249)
    - Follow the formation of individual stars in giant molecular clouds (GMCs) using the GIZMO code
    - Outflow的作用：Outflows disrupt the accretion flow around the protostar, allowing gas to fragment and additional stars to form, thereby lowering the mean stellar mass to a value similar to that observed.
    - Jet的作用：The effect of jets upon global cloud evolution is most pronounced for lower-mass GMCs and dense clumps, so while jets can disrupt low-mass clouds, they are unable to regulate star formation in massive GMCs. Jets are also unable to stop the runaway accretion of massive stars
    - We conclude that protostellar jets play a vital role in setting the mass scale of stars, but additional physics are necessary to reproduce the observed IMF.

- [Strong Mg II and Fe II Absorbers at 2.2 < z < 6.0](https://arxiv.org/abs/2010.11432)
    - Compared with strong Mg II absorbers detected in damped Lyα systems at 2 < z< 4, our absorbers are potentially less saturated and show much larger rest-frame velocity widths. This suggests that the gas traced by our absorbers are potentially affected by galactic superwinds.
    - By using our observed dN/dX of strong Mg II absorbers and galaxy candidates median luminosity, we suggest that at high redshift, strong Mg II absorbers tend to have a more disturbed environment but smaller halo size than that at z< 1.

- [Extreme kinematic misalignment in IllustrisTNG galaxies: the origin, structure and internal dynamics of galaxies with a large-scale counterrotation](https://arxiv.org/abs/2010.11581)
    - We have found 25 galaxies with substantial stellar counterrotation in the stellar mass range of 2×10^9−3×10^10~\Msun. In our sample the stellar counterrotation is a result of an external gas infall happened ≈2−8~Gyr ago.
    - We show that ≈90% of the stellar counterrotation formed in-situ, in the counterrotating gas.

- [The kinematics of young and old stellar populations in nuclear rings of MUSE TIMER galaxies](https://arxiv.org/abs/2010.11815)
    - We report a correlation of the colour excess with the difference in the kinematic parameters of the Hβ line and the Ca II Triplet range, which are dominated by young and old stellar populations
    - Our study demonstrates that kinematic differences caused by different stellar populations can be identified in the central regions of nearby galaxies even from intermediate resolution spectroscopy.

----

### Oct 25

- [Constraining cosmology with weak lensing voids](https://arxiv.org/abs/2010.11954)
    - We use a recently proposed weak lensing observable - weak lensing voids - to make parameter constraint forecasts for an LSST-like survey
    - We find that the void abundance is more constraining than the tangential shear profiles, though the combination of the two gives additional constraining power.

- [The Cluster HEritage project with XMM-Newton: Mass Assembly and Thermodynamics at the Endpoint of structure formation. I. Programme overview](https://arxiv.org/abs/2010.11972)
    - **Relevant**
    - http://xmm-heritage.oas.inaf.it/
    - CHEX-MATE: a three mega-second Multi-Year Heritage Programme to obtain X-ray observations of a minimally-biased, signal-to-noise limited sample of 118 galaxy clusters detected by Planck through the Sunyaev-Zeldovich effect.
    - The programme will yield an accurate vision of the statistical properties of the underlying population, measure how the gas properties are shaped by collapse into the dark matter halo, uncover the provenance of non-gravitational heating, and resolve the major uncertainties in mass determination that limit the use of clusters for cosmological parameter estimation.

- [Euclid: impact of nonlinear prescriptions on cosmological parameter estimation from weak lensing cosmic shear](https://arxiv.org/abs/2010.12382)
    - For a given prescription for the nonlinear power spectrum, using different corrections for baryon physics does not significantly impact the precision of Euclid, but neglecting these correction does lead to large biases in the cosmological parameters.
    - In order to extract precise and unbiased constraints on cosmological parameters from Euclid cosmic shear data, it is therefore essential to improve the accuracy of the recipes that account for nonlinear structure formation, as well as the modelling of the impact of astrophysical processes that redistribute the baryons.

- [Current and Next Generation Survey Filter Conversions with ProSpect](https://arxiv.org/abs/2010.12228)
    - **Useful**
    - https://rpubs.com/asgr/567881
    - We compute a reasonably comprehensive set of tables for current and next generation survey facility filter conversions

- [The Cosmic Ultraviolet Baryon Survey (CUBS) II: Discovery of an H2-Bearing DLA in the Vicinity of an Early-Type Galaxy at z = 0.576](https://arxiv.org/abs/2010.11958)
    - The diffuse molecular gas is found in two velocity components separated by dv = 60 km/s, with >99.9% of the total H2 column density concentrated in one component. At a metallicity of ≈ 40% of solar, there is evidence for Fe enhancement and dust depletion, with a dust-to-gas ratio κO≈0.4
    - The closest is a massive, early-type galaxy at d = 41 pkpc which contains 70% of the total stellar mass identified at d <= 310 pkpc of the H2 absorber. The close proximity of the H2-bearing gas to the quiescent galaxy and the Fe-enhanced chemical abundance pattern of the absorber suggest a physical connection.

- [ROGER: Reconstructing Orbits of Galaxies in Extreme Regions using machine learning techniques](https://arxiv.org/abs/2010.11959)
    - **Relevant**
    - MDPL2 + SAG SAM模型：选大质量星系团中的>10^8.5Msun星系进行机器学习预测，we train ROGER to retrieve the original classification of the galaxies out of their projected phase-space positions.
    - ROGER gives as output the probability of being a cluster galaxy, a galaxy that has recently fallen into a cluster, a backsplash galaxy, an infalling galaxy, or an interloper.

- [Active galactic nuclei ghosts: A systematic search for faded nuclei](https://arxiv.org/abs/2010.11962)
    - We present a catalog of 88 AGN candidates showing hints on the fading and rising of their activity in the nearby Universe
    - We find that 96% of our candidates are fading sources. This result suggests a scenario where the Universe had its peak of AGN activity somewhere in the past and is dominated by a fading phase at the present time.
    - Around 50% of these fading candidates are associated with merging or interacting systems.

- [Runaway stars masquerading as star formation in galactic outskirts](https://arxiv.org/abs/2010.11965)
    - Runaway stars, produced by collisional dynamics in young stellar clusters, can travel kilo-parsecs during their main sequence life time.
    - Using galactic-scale hydrodynamic simulations including a treatment of individual stars, we demonstrate that this mechanism enables the ejection of young massive stars into environments where the gas is not dense enough to trigger star formation.

----

### Oct 26

- [Environmental dependence of X-ray and optical properties of galaxy clusters](https://arxiv.org/abs/2010.12671)
    - **Relevant**
    - 看星系团性质与大尺度结构的关系：use both observational and simulation cluster and void catalogues, i.e. XCS and redMaPPer clusters, BOSS voids, and Magneticum simulations
    - We use the Kolmogorov-Smirnov two-sample test to discover that richer and more massive clusters are more prevalent in overdense regions and outside of voids.
    - We also find that clusters of matched richness and mass in overdense regions and outside voids tend to have higher X-ray luminosities and temperatures.

- [Hunting for Dark Matter Subhalos in Strong Gravitational Lensing with Neural Networks](https://arxiv.org/abs/2010.12960)
    - We discuss the possibility of using deep neural networks to detect dark matter subhalos, and showing some preliminary results with simulated data.

- [The impact of mass map truncation on strong lensing simulations](https://arxiv.org/abs/2010.13650)
    - We use mock observations to demonstrate the viability of a forward modelling approach to extract information on the cosmological number density of low-mass dark matter haloes along the line-of-sight to galaxy-galaxy strong lenses
    - With 50 strong lenses at Hubble Space Telescope resolution and signal-to-noise (similar to the existing SLACS survey), the expected 2σ constraint for CDM is mDM>3.7keV.
    - 提供了一个基于ABC的方法

- [Reducing ground-based astrometric errors with Gaia and Gaussian processes](https://arxiv.org/abs/2010.13742)
    - **Useful**
    - Stochastic field distortions caused by atmospheric turbulence are a fundamental limitation to the astrometric accuracy of ground-based imaging.
    - We develop the use of Gaussian process regression (GPR) to interpolate the distortion field to arbitrary locations in each exposure. We introduce an extension to standard GPR techniques that exploits the knowledge that the 2-dimensional distortion field is curl-free.

- [The First Gamma-ray Emitting BL Lacertae Object at the Cosmic Dawn](https://arxiv.org/abs/2010.12907)
    - Here we report the identification of the first γ-ray emitting BL Lac object, 4FGL~J1219.0+3653 (J1219), beyond z=3
    - The optical and near-infrared spectra of J1219 taken from 10.4 m Gran Telescopio Canarias exhibit no emission lines down to an equivalent width of ∼3.5 A supporting its BL Lac nature.
    - The detection of a strong Lyman-α break at ∼5570 A, on the other hand, confirms that J2119 is indeed a high-redshift (z∼3.59) quasar. 这类天体应该非常的稀有

- [Tightly coupled morpho-kinematic evolution for massive star-forming and quiescent galaxies across 7 Gyr of cosmic time](https://arxiv.org/abs/2010.12586)
    - **Relevant, Interesting**
    - LEGA-C, 1400 >10^10.5 Msun的星系的运动学测量：we find a strong evolution in Mdyn/Lg with redshift.
    - We find only a weak dependence of the mean value of Mdyn/M∗ on the specific star formation rate, and a redshift evolution that likely is explained by systematics.
    - Star-forming and quiescent galaxies lie on the same, stable mass FP across 0< z<1, and that the decrease in Mdyn/Lg toward high redshift can be attributed entirely to evolution of the stellar populations.

- [Revealing the Impact of Quasar Luminosity on Giant Lyα Nebulae](https://arxiv.org/abs/2010.12589)
    - **Interesting**
    - 12个z=3.15的QSO，比之前的Lya星云样本更暗：We detect HI Lyα nebulae around 100% of our target quasars, with emission extending to scales of at least 60 physical kpc, and up to 190 pkpc.
    - We show that the surface brightness profiles of the nebulae are similar to those of nebulae around bright quasars, but with a lower normalization.
    - QSO比之前的样本暗约30倍；但Lya Nebulae在20-50 pkpc内只暗了大约4-5倍
    - We find significant correlations between the surface brightness of the nebula and the luminosity of the quasar in both UV continuum and Lyα

- [Ubiquitous Molecular Outflows in z > 4 Massive, Dusty Galaxies I. Sample Overview and Clumpy Structure in Molecular Outflows on 500pc Scales](https://arxiv.org/abs/2010.12591)
    - We have conducted the first survey of molecular outflows at z > 4, targeting 11 strongly-lensed dusty, star-forming galaxies (DSFGs) with ALMA using OH 119um absorption as an outflow tracer
    - We find unambiguous evidence for outflows in 8/11 (73%) galaxies, more than tripling the number known at z > 4. This implies that molecular winds in z > 4 DSFGs must have both a near-unity occurrence rate and large opening angles to be detectable in absorption. 外流非常常见
    - 外流中有很多clump结构：Lensing reconstructions reveal that 500pc-scale clumpy structures in the outflows are common.
    - [CII] 可能不是非常好的外流tracer

- [Coronal Line Forest AGN I: physical properties of the emission-line regions](https://arxiv.org/abs/2010.12595)
    - Coronal-Line Forest Active Galactic Nuclei (CLiF AGN) are characterized by strong high-ionization lines, which contrast to what is found in most AGNs
    - By comparing coronal emission-line ratios we conclude that there are no differences between CLiF and non-CLiF AGNs. 并不是那么特殊。
    - We suggest a NLR dominated by matter-bounded clouds to explain the high-ionization line spectrum observed.

- [Turbulent density and pressure fluctuations in the stratified intracluster medium](https://arxiv.org/abs/2010.12602)
    - The ICM is density-stratified, with the gas density being highest at the centre of the cluster and decreasing radially outwards. Kolmogorov的湍动理论不适用，因为要求均匀和各向同
    - The gas motions are instead explained by anisotropic stratified turbulence with the stratification quantified by the perpendicular Froude number (Fr⊥).

- [Powerful t-SNE technique leading to clear separation of type-2 AGN and HII galaxies in BPT diagrams](https://arxiv.org/abs/2010.13037)
    - Based on powerful t-SNE technique applied to the local narrow emission-line galaxies in SDSS DR15, type-2 AGN and HII galaxies can be clearly separated in the t-SNE determined two-dimensional projected map

- [Probing the CGM of Low-redshift Dwarf Galaxies Using FIRE Simulations](https://arxiv.org/abs/2010.13606)
    - 和观测比较，进行了halo质量，恒星质量，红移的match：The FIRE equivalent width (EW) distributions and covering fractions for the C IV ion are broadly consistent with observations inside 0.5Rvir, but are under-predicted for O VI, Mg II, and Si III.
    - The structure and composition of the gas from the simulations exhibit three zones around dwarf galaxies characterized by distinct ion column densities: the disky ISM, the inner CGM (the wind-dominated regime), and the outer CGM (the IGM accretion-dominated regime).
        - Outer CGM已经不完全是由thermal pressure支持的，并不处于流体静力学平衡
    - The net gas inflow rates are comparable to the SFR of the galaxy, but the bulk inflow and outflow rates are greater by an order of magnitude, with velocities comparable to the virial velocity of the halo.
    - This supports a picture for dwarf galaxies in which the dynamics of the CGM at large scales are coupled to the small-scale star formation activity near the centre of their halos.

----

### Oct 27

- [Chandra Observations of Abell 2261 Brightest Cluster Galaxy, a Candidate Host to a Recoiling Black Hole](https://arxiv.org/abs/2010.13980)
    - We found no X-ray emission arising from a point source in excess of the cluster gas and can place limits on the accretion of any black hole in the central region
    - Thus there is either no 1010 M⊙ black hole in the core of A2261-BCG, or it is accreting at a low level.

- [The stratified disk wind of MCG-03-58-007](https://arxiv.org/abs/2010.14204)
    - Past Suzaku, XMM and NuSTAR observations of the nearby (z=0.0323) bright Seyfert 2 galaxy MCG-03-58-007 revealed the presence of two deep and blue-shifted Fe K-shell absorption line profiles. These could be explained with the presence of two phases of a highly ionized, high column density accretion disk wind outflowing
    - Overall the multi-epochs observations show that the disk wind in MCG-03-58-007 is not only powerful, but also extremely variable

- [The flaring X-ray corona in the quasar PDS 456](https://arxiv.org/abs/2010.14295)
    - PDS 456: 光变中的radio quite QSO: A bright X-ray flare was captured in September 2018, the flux increasing by a factor of 4 and with a doubling time-scale of 2 days.
    - A hardening of the X-ray emission accompanied the flare, with the photon index decreasing from Γ=2.2 to Γ=1.7 and back again. The flare is produced in the X-ray corona, the lack of any optical or UV variability being consistent with a constant accretion rate.
    - These caught PDS 456 in a bright, bare state, where no disc wind absorption features are apparent.
    - The deduced coronal temperature, of kT=13 keV, is one of the coolest measured in any AGN and PDS 456 lies well below the predicted pair annihilation line in X-ray corona. The spectral variability, becoming softer when fainter following the flare, is consistent with models of cooling X-ray coronae.

- [Hierarchical Inference With Bayesian Neural Networks: An Application to Strong Gravitational Lensing](https://arxiv.org/abs/2010.13787)
    - **Useful**
    - https://github.com/swagnercarena/ovejero
    - We incorporate BNNs with flexible posterior parameterizations into a hierarchical inference framework that allows for the reconstruction of population hyperparameters and removes the bias introduced by the training distribution. 应对不确定training sample是否representative的问题
    - We show that our hierarchical inference framework mitigates the bias introduced by an unrepresentative training set's interim prior. Simultaneously, given a sufficiently broad training set, we can precisely reconstruct the population hyperparameters governing our test distributions.

- [Cosmological Constraints from DES Y1 Cluster Abundances and SPT Multi-wavelength data](https://arxiv.org/abs/2010.13800)
    - **Relevant**
    - DES Y1 redMaPPer + SPT mass-richness calibration: To explore possible systematics related to the modeling of projection effects, we consider two calibrations of the observational scatter on richness estimates: a simple Gaussian model which account only for the background contamination (BKG), and a model which further includes contamination and incompleteness due to projection effects (PRJ) 开始考虑projection效应了
    - This result demonstrates that the DES Y1 and SPT cluster counts provide consistent cosmological constraints, if the same mass calibration data set is adopted.
    - 将Optical和SZ clusters结合起来：Besides providing a mild improvement of the cosmological constraints, this data combination serves as a stricter test of our scatter models: the PRJ model, providing scaling relations consistent between the two abundance and multi-wavelength follow-up data, is favored over the BKG model.

- [Photometric selection and redshifts for quasars in the Kilo-Degree Survey Data Release 4](https://arxiv.org/abs/2010.13857)
    - In 45 million objects of the KiDS data limited to 9-band detections, we define inference subsets based on a feature space built from magnitudes, their combinations, and shape classifiers. We show that projections of a feature space on two dimensions can be successfully used instead of the standard color-color plots
    - The catalog is tested using number counts and Gaia parallaxes. Based on these tests, we calibrate the purity vs. completeness trade-off with minimum classification probability for quasar candidates: p(QSO_cand)>0.9 for the safe inference subset at r<22, and p(QSO_cand)>0.98 for the reliable extrapolation at 22< r <23.5

- [Pre-supernova feedback mechanisms drive the destruction of molecular clouds in nearby star-forming disc galaxies](https://arxiv.org/abs/2010.13788)
    - We apply a novel statistical method to ∼1" resolution maps of CO and Ha emission across a sample of nine nearby disc galaxies, in order to measure the time over which GMCs are dispersed by feedback from young, high-mass stars, as a function of the galactic environment.
    - 在GMC内大质量恒星出现后3Myr内GMC开始消散; 和距离星系中心的距离关系不大
    - 早期非SN反馈机制很重要: Comparison with analytical predictions demonstrates that, independently of the environment, early feedback mechanisms (particularly photoionisation and stellar winds) play a crucial role in dispersing GMCs and limiting their star formation efficiency in nearby galaxies.

- [Detection of the LMC-induced sloshing of the Galactic halo](https://arxiv.org/abs/2010.13789)
    - LMC的质量较大，会对银河系产生影响：One consequence of having such a nearby and massive neighbour is that the inner Milky Way is expected to be accelerated with respect to our Galaxy's outskirts (beyond ∼30 kpc).
    - We find that stars in the Southern hemisphere are on average blueshifted, while stars in the North are redshifted, consistent with the expected, mostly downwards acceleration of the inner halo due to the LMC.
    - We compare these results with simulations and find the signal is consistent with the infall of a 1.5×10^11M⊙ LMC.

- [The mass of the Milky Way out to 100 kpc using halo stars](https://arxiv.org/abs/2010.13801)
    - 100 kpc内的halo star的分布函数研究给出星系质量：The LMC biases the (pre-LMC infall) halo mass estimates towards higher values, while realistic stellar halos from cosmological simulations tend to underestimate the true halo mass.
    - 移除了LMC产生的影响，移除了Sgr星流里的恒星
    - Our mass estimate favours a total (pre-LMC infall) Milky Way mass of M_200c = 1.05 +/- 0.25 x 10^12 M_Sun, or (post-LMC infall) mass of M_200c = 1.20 +/- 0.25 x 10^12 M_Sun when a 1.5 x 10^11 M_Sun mass of a rigid LMC is included.

- [A new feedback cycle in the archetypal cooling flow group NGC 5044](https://arxiv.org/abs/2010.13804)
    - **Relevant**
    - NGC5044适合研究星系群尺度上的冷气体和AGN反馈的关系：With the largest known reservoir of cold molecular gas of any group-dominant galaxy and three epochs of AGN activity visible as cavities in its hot gas
    - We find a compact core and two small jets aligned almost in the plane of the sky, and in the orthogonal direction to the location of cavities.
    - We find that below 5 GHz the spectrum is best fit by a self-absorbed continuous injection model representing emission coming from the jets, while the higher frequencies show clear signs of an advection dominated accretion flow

- [Significant Suppression of Star Formation in Radio-Quiet AGN Host Galaxies with Kiloparsec-Scale Radio Structures](https://arxiv.org/abs/2010.13806)
    - 100 radio-quiet X-ray selected AGN from the Swift-BAT survey的JVLA观测：find AGN-driven kiloparsec-scale radio structures inconsistent with pure star formation in 11 AGN
    - The host galaxies of these AGN lie significantly below the star-forming main sequence, indicating suppressed star formation.
    - We conclude that it is more likely that the observed suppression of star formation in the global host galaxy is due to ISM interactions of a radiative outflow, rather than a small-scale radio jet.

- [Disk dominated galaxies retain their shapes below z=1.0](https://arxiv.org/abs/2010.13845)
    - 关于Disk星系3-D shape的推断：Applying the 3D shape reconstruction method on COSMOS data, we find no significant dependence of the inferred 3D shape distribution on redshift. 说明盘星系从z~1的演化比较平静
    - The relative disk thickness shows a significant mass dependence which can be accounted for by the scaling of disk radius with galaxy mass.

- [Stars and gas in the most metal-poor galaxies I: COS and MUSE observations of SBS 0335-052E](https://arxiv.org/abs/2010.13963)
    - Previous attempts to reproduce its He II 4686 emission luminosity found that X-ray sources, shocks, and single Wolf-Rayet stars are not main contributors to the He II-ionizing budget; and that only metal-free single rotating stars or binary stars with a top-heavy IMF and an unphysically-low metallicity can reproduce it.
    - Nebular He II, [C III], C III], C IV, and O III] UV emission lines with equivalent widths between 1.7 and 5 {\AA}, and a C IV 1548, 1551 P-Cygni like profile are detected.
    - Recent extremely-metal poor shock + precursor models and binary models fail to reproduce the observed optical emission-line ratios. 想同时拟合这些观测还是很有难度的
    - We obtain 12+log(O/H)=7.45\pm0.04 and log(C/O)=-0.45(+0.03)(-0.04) for the galaxy

- [Measuring Dark Matter in Galaxies: The Mass Fraction Within 5 Effective Radii](https://arxiv.org/abs/2010.14372)
    - **Relevant**
    - 利用X-ray热气体观测定总质量和DM比例：We use this technique for 102 early-type galaxies (ETGs) with stellar masses M_* > 10^10 M_Sun, to evaluate the mass fraction of dark matter (DM) within the fiducial radius r = 5 r_e, denoted f_5
    - On average, these systems have a median f_5 = 0.8 - 0.9 with a typical galaxy-to-galaxy scatter +-0.15.
    - We find that many of the disk galaxies (S0/SA0/SB0) have a significantly higher mean f5 than do the pure ellipticals, by Delta f_5 = 0.1. We suggest that this higher level may be a consequence of sparse stellar haloes and quieter histories with fewer major episodes of feedback or mergers.
    - Lastly, we find that the group galaxies with stellar masses near M_* ~ 10^11 M_Sun have relatively more outliers at low f5 than in other mass ranges, possibly the result of especially effective AGN feedback in that mass range leading to expansion of their dark matter halos.

- [Hierarchical star formation in nearby galaxies](https://arxiv.org/abs/2010.14419)
    - We used ACS/HST photometry and the "path-linkage criterion" in order to obtain a catalog of young stellar groups (YSGs) in the galaxy NGC 2403
    - We find that the vast majority of the YSGs in NGC 2403, NGC 300 and NGC 253 present inner clumpings, following the same hierarchical behavior that we observed in the young stellar structures on larger scales in these galaxies.
    - These values are very similar to those obtained in other star forming galaxies and in the interstellar medium, suggesting that the star formation process is regulated by supersonic turbulence.

- [A Closer Look at Two of the Most Luminous Quasars in the Universe](https://arxiv.org/abs/2010.14433)
    - 对两个高红移超亮类星体的SED分析：NOEMA 3 millimeter observations of J0341+1720 reveal a highly star-forming (SFR≈1500M⊙yr−1), ultra-luminous infrared galaxy (LTIR≈1.0×10^13L⊙) host, which, based on an estimate of its dynamical mass, is only ∼30 times more massive than the SMBH it harbors at its center.
    - As examples of luminous super-Eddington accretion, these two quasars provide support for theories, which explain the existence of billion solar mass SMBHs ∼700 million years after the Big Bang by moderate super-Eddington growth from standard SMBH seeds.