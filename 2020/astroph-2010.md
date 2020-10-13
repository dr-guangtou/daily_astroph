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