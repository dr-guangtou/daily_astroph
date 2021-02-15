# ArXiv astrop-ph Journal 

- #arxiv

## 2021 Feb 

### Feb 2 

#### Relevant / Important / Useful

##### [A Photometric and Kinematic Analysis of UDG1137+16: Probing Ultra-Diffuse Galaxy Formation in a Group Environment](https://arxiv.org/abs/2102.00598)

- #galaxy/dwarf #galaxy/udg 
- Our new analyses confirm both its environmental association with the low density UGC 6594 group, along with its large size of 3.3 kpc and status as a UDG.
	- The new imaging reveals two distinct stellar components for UDG1137+16, indicating that a central stellar body is surrounded by an outer stellar envelope undergoing tidal interaction.
- We measure a stellar velocity dispersion within the half-light radius (15 ± 4 km s−1) and find that UDG1137+16 is similar to some other UDGs in that it is likely dark matter dominated.

##### [Rapid sorting of radio galaxy morphology using Haralick features](https://arxiv.org/abs/2102.00843)

- #galaxy/morphology
- The set of thirteen Haralick features represent an extremely compact non-parametric representation of image texture, and are calculated directly from imagery using the Grey Level Co-occurrence Matrix (GLCM)
- 基于LoTSS数据：we demonstrate that Haralick features are highly efficient, rotationally invariant descriptors of radio galaxy morphology.
- 同时利用HDBSCAN技术进行分类
- 关于Haralick特征：
	- Haralick features were introduced by Haralick et al. (1973) as a statistical method of examining image texture.  They consider the relationship between the intensity of neighbouring pixels and are useful in classifying similar regions in an image given the local spatial distribution of pixel intensities.
	-  Haralick features are based on the so-called Grey Level Co-occurrence Matrix (GLCM). To compute the Haralick features, one must first compute the GLCM, which can then be used to evaluate the Haralick coefficients.
- Code used in this work: [`HaralickFeatures` - Use of Haralick features for galaxy morphology through HDBSCAN algorithm](https://github.com/KushathaNtwaetsile/HaralickFeatures)

##### [Mock Lightcones and Theory Friendly Catalogs for the CANDELS Survey](https://arxiv.org/abs/2102.00108)

- #galaxy/sam #galaxy/sem #galaxy_halo
- 基于Bolshoi Planck + SAM/UM做的mock catalog: have geometries that encompass the footprints of observations associated with the five CANDELS fields.
- We find poorer agreement for colors and star formation rate distributions.
- Data are available through [flathub](http://flathub.flatironinstitute.org/group/candels)

#### Interesting / Keep in Mind

##### [Constraining the Baryon Abundance with the Kinematic Sunyaev-Zel'dovich Effect: Projected-Field Detection Using Planck, WMAP, and unWISE](https://arxiv.org/abs/2102.01068)

- #cosmology/sz 
- We measure the kSZ effect due to ionized gas traced by infrared-selected galaxies from the \\emph{unWISE} catalog. 
	- We employ the "projected-field" kSZ estimator, which does not require spectroscopic galaxy redshifts.
- Using a new "asymmetric" estimator that combines different foreground-cleaned CMB maps to maximize the signal-to-noise, we measure the kSZ2\-galaxy cross-power spectrum
	- 对z=0.6, 1.1, 1.5的三个样本得到了探测
	- We discuss possible explanations for the excess kSZ signal associated with the z≈1.1 sample, and show that foreground contamination in the CMB maps is very unlikely to be the cause.

#### Others

##### [Delensing the CMB with the cosmic infrared background: the impact of foregrounds](https://arxiv.org/abs/2102.01045)

- 关于CMB B-mode偏振探测中的去除lensing效应的影响：the lensing effects can be partially removed by combining high-resolution E\-mode measurements with an estimate of the projected matter distribution. 
	- For near-future experiments, the best estimate of the latter will arise from co-adding internal reconstructions (derived from the CMB itself) with external tracers of the large-scale structure such as the cosmic infrared background (CIB).
- Mitigation techniques based on multi-frequency cleaning appear to be very effective.
- By means of an analytic model, that the bias arising from the higher-point functions of the CIB itself ought to be negligible.
- [`MultitracerSims4Delensing` - Generate Gaussian simulations of LSS tracer which are appropriately correlated with each other and with an input convergence](https://github.com/abaleato/MultitracerSims4Delensing)
- [`curved_sky_B_template` - Fast implementation of a curved-sky template for linear-order lensing B-modes](https://github.com/abaleato/curved_sky_B_template)

##### [Structured Variational Inference for Simulating Populations of Radio Galaxies](https://arxiv.org/abs/2102.01007)

- We present a model for generating postage stamp images of synthetic Fanaroff-Riley Class I and Class II radio galaxies suitable for use in simulations of future radio surveys such as those being developed for the SKA
- 很详尽的VAE图像重构工作，技术上有参考意义
- Code used in this work: [`RAGA`](https://github.com/joshen1307/RAGA) 

##### [A Search for correlations between turbulence and star formation in LITTLE THINGS dwarf irregular galaxies](https://arxiv.org/abs/2102.00040)

- We looked for relationships between SF traced by FUV images, and gas turbulence traced by kinetic energy density (KED) and velocity dispersion
- The excess KED associated with SF implies a ∼0.5% efficiency for supernova energy to pump local HI turbulence on the scale of resolution here, which is a factor of ∼2 too small for all of the turbulence on a galactic scale.
	- The excess vdisp in SF regions is also small
- The local excess in ΣHI corresponding to an excess in ΣSFR is consistent with an HI consumption time of ∼1.6 Gyr in the inner parts of the galaxies.

##### [A Graphical Interpretation of Circumgalactic Precipitation](https://arxiv.org/abs/2102.00056)

- #galaxy/cgm 
- 目前关于CGM的一个假设： a self-regulating feedback loop suspends the gas density of the ambient CGM close to the galaxy in a state with a ratio of cooling time to freefall time >10.
	- 当这个比值小于10，冷气体会从CGM中凝结出来，集中落向星系中心，触发新的feedback
	- The astrophysical origin of this so-called precipitation limit is not simple but is critical to understanding the CGM and its role in galaxy evolution
- 本文尝试从概念上解释：It illustrates how the precipitation limit can depend on both the global configuration of a galactic atmosphere and the degree to which dynamical disturbances drive CGM perturbations.

##### [The central parsec of NGC 3783: a rotating broad emission line region, asymmetric hot dust structure, and compact coronal line region](https://arxiv.org/abs/2102.00068)

- SINFONI + GRAVITY: We find the BLR probed through broad Brγ emission is well described by a rotating, thick disk with a radial distribution of clouds peaking in the inner region
- In our BLR model the physical mean radius of 16 light days is nearly twice the 10 day time lag that would be measured, which matches very well the 10 day time lag that has been measured by reverberation mapping.
- 看到的热尘埃结构有offset迹象：可能是正被吸积的团块
- We directly measure the FWHM size of the nuclear CLR as traced by the \[CaVIII\] and narrow Brγ line. We find a FWHM size of 2.2 mas (0.4 pc), fully in line with the expectation of the CLR located between the BLR and narrow line region.

##### [A new analytic ram pressure profile for satellite galaxies](https://arxiv.org/abs/2102.00132)

- 冲压剥离理论模型的比较：传统的beta-profile缺乏对halo质量和距离halo中心距离的依赖
- we introduce a new universal analytic model for the profiles consisting in a damped power law, and we provide a new set of fitted parameters which can recover the ram pressure dependence on halo mass and redshifts.
- We find the number of galaxies experiencing large amounts of accumulated ram pressure stripping have low stellar mass
	- Their specific star formation rates depend significantly on the ram pressure modelling, particularly at high redshifts (z\>1.5).

##### [Detection of an ionized gas outflow in the extreme UV-luminous star-forming galaxy BOSS-EUVLG1 at z=2.47](https://arxiv.org/abs/2102.00774)

- 目前探测到的UV和Lya最亮的星系，SFR接近1000 Msun/yr
	- We report the detection of a broad Hα component carrying 25% of the total Hα flux. 指示了一个大质量的高速外流；外流速度接近600km/s
	- 外流可以用SF解释，不需要AGN; 而且mass loading factor显示外流不足以quench SF；只有少部分外流能超过逃逸速度
- The ionized phase of the outflow does not carry the mass and energy to play a relevant role neither in the evolution of the host galaxy nor in the enrichment of the intergalactic medium.


### Feb 3 

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

#### Others

##### [Properties of clumps and filaments around galaxy clusters](https://arxiv.org/abs/2102.01096)

##### [Cosmological cross-correlations and nearest neighbor distributions](https://arxiv.org/abs/2102.01184)

##### [Scrutinizing FR 0 Radio Galaxies as Ultra-High-Energy Cosmic Ray Source Candidates](https://arxiv.org/abs/2102.01087)

##### [Catalog-free modeling of galaxy types in deep images: Massive dimensional reduction with neural networks](https://arxiv.org/abs/2102.01086)

##### [Applying the Tremaine-Weinberg Method to Nearby Galaxies: Stellar Mass-Based Pattern Speeds, and Comparisons with ISM Kinematics](https://arxiv.org/abs/2102.01091)

##### [The large-scale distribution of highly ionized metals in IllustrisTNG](https://arxiv.org/abs/2102.01092)

##### [The physics of gas phase metallicity gradients in galaxies](https://arxiv.org/abs/2102.01234)

##### [A Catalog of High-Velocity CIV Mini-BALs in the VLT-UVES and Keck-HIRES Archive](https://arxiv.org/abs/2102.01362)

##### [Physical properties of Brightest Cluster Galaxies up to redshift 1.80 based on HST data](https://arxiv.org/abs/2102.01557)

- #galaxy/bcg #cluster/galaxy 
- For a sample of 137 clusters with HST images in the optical and/or infrared, we analyse the BCG properties by applying GALFIT with one or two Sersic components.
- The major axes of the cluster elongations and of the BCGs agree within 30 degrees for 73% of our clusters at redshift z <= 0.9.

### Feb 4 

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

##### [Australian Square Kilometre Array Pathfinder: I. System Description](http://arxiv.org/abs/2102.01870) [(PDF)](http://arxiv.org/pdf/2102.01870.pdf)

- ASKAP is one of the first radio telescopes to deploy phased array feed (PAF) technology on a large scale, giving it an instantaneous field of view that covers 31 square degrees at 800 MHz.
- As a two-dimensional array of 36x12m antennas, with baselines ranging from 22m to 6km, ASKAP also has excellent snapshot imaging capability and 10 arcsecond resolution.
- It is an excellent telescope for surveys between 700 MHz and 1800 MHz and is expected to facilitate great advances in our understanding of galaxy formation, cosmology and radio transients while opening new parameter space for discovery of the unknown.

##### [Toward a more stringent test of gravity with redshift space power spectrum: simultaneous probe of growth and amplitude of large-scale structure](http://arxiv.org/abs/2102.01785) [(PDF)](http://arxiv.org/pdf/2102.01785.pdf)

- #cosmology/rsd #ssst/cos
- In the presence of galaxy bias, however, the RSD measurement at large scales, where the linear theory prediction is safely applied, is known to exhibit a degeneracy between the parameters of structure growth f and fluctuation amplitude sigma8, and one can only constrain the parameters in the form of fsigma8.
- In order to disentangle this degeneracy, in this paper, we go beyond the linear theory, and consider the model of RSD applicable to a weakly nonlinear regime.
- We show that upcoming galaxy survey of the stage-IV class can unambiguously determine sigma8 at the precision down to 10% at higher redshifts even if we restrict the accessible scales to k<0.16h/Mpc

#### Others

##### [Information Content of Higher-Order Galaxy Correlation Functions](http://arxiv.org/abs/2102.01696) [(PDF)](http://arxiv.org/pdf/2102.01696.pdf)

- Constraints available from joint analysis of the galaxy power spectrum and bispectrum (Fourier-space analog of the 3-Point Correlation Function) can, in some cases, exceed those offered by the initial power spectrum even when the reconstruction is perfect.
- In particular, we show that for the z = 0 real-space matter field in the limit of vanishing shot noise, taking modes up to k_max = 0.2 h/Mpc, using the bispectrum alone offers a factor of two reduction in the variance on the cosmic distance scale relative to that available from the power spectrum.

##### [The Cosmological Trajectories Method: Modelling cosmic structure formation in the non-linear regime](http://arxiv.org/abs/2102.01698) [(PDF)](http://arxiv.org/pdf/2102.01698.pdf)

- We introduce a novel approach, the Cosmological Trajectories Method (CTM), to model nonlinear structure formation in the Universe by expanding gravitationally-induced particle trajectories around the Zel'dovich approximation.
- [`CTM` - Cosmological Trajectories Method](https://github.com/franlane94/CTM)

##### [Living with Neighbors. III. The Origin of the Spin$-$Orbit Alignment of Galaxy Pairs: A Neighbor versus the Large-scale Structure](http://arxiv.org/abs/2102.01701) [(PDF)](http://arxiv.org/pdf/2102.01701.pdf)

- #galaxy_halo
- "the spin$-$orbit alignment (SOA)"  - a coherence between the spin vector of a galaxy and the orbital motion of its neighbors.
- 在Illustris模拟中:
	- (a) There exists a clear preference for prograde orientations (i.e., SOA) for galaxy pairs, qualitatively consistent with observations.
	- (b) The SOA is significant for both baryonic and dark matter spins, being the strongest for gas and the weakest for dark matter.
	- (c) The SOA is stronger for less massive targets and for targets having closer neighbors.
	- (d) The SOA strengthens for galaxies in low-density regions, and the signal is dominated by central$-$satellite pairs in low-mass halos.
	- (e) There is an explicit dependence of the SOA on the duration of interaction with its current neighbor.
- Taken together, we propose that the SOA witnessed at $z = 0$ has been developed mainly by interactions with a neighbor for an extended period of time, rather than tidal torque from the ambient large-scale structure.

##### [Early Science from POSSUM: Shocks, turbulence, and a massive new reservoir of ionised gas in the Fornax cluster](http://arxiv.org/abs/2102.01702) [(PDF)](http://arxiv.org/pdf/2102.01702.pdf)

- ASKAP / POlarisation Sky Survey of the Universe's Magnetism (POSSUM) 
	- Probe the extended magnetoionic structure of the cluster in unprecedented detail.
- The Faraday-active plasma比发射X-ray的ICM气体质量大，可能对应的是WHIM成分
- The morphology of the Faraday depth enhancement exhibits the classic morphology of an astrophysical bow shock on the southwest side of the main Fornax cluster, and an extended, swept-back wake on the northeastern side.
	- Our favoured explanation is an ongoing merger between the main cluster and a sub-cluster to the southwest.
- [`Aegean` - Radio source finding](https://github.com/PaulHancock/Aegean)
- [`rm-synthesis` - Faraday Rotation Measure Synthesis in Python](https://github.com/brentjens/rm-synthesis)
- [[Radio Astronomy Software]]

##### [Substructure at High Speed I: Inferring the Escape Velocity in the Presence of Kinematic Substructure](http://arxiv.org/abs/2102.01704) [(PDF)](http://arxiv.org/pdf/2102.01704.pdf)

- In this paper, we introduce a strategy that for the first time takes into account the presence of kinematic substructure.
	- We model the tail of the velocity distribution as a sum of multiple power laws without imposing strong priors.

##### [On the relation between Lya absorbers and local galaxy filaments](http://arxiv.org/abs/2102.01713) [(PDF)](http://arxiv.org/pdf/2102.01713.pdf)

- #galaxy/igm
- We aim at characterising the relation between Lya absorbers and nearby overdense cosmological structures (galaxy filaments) at recession velocities Delta v \leq 6700 km/s by using archival observational data from various instruments.
- Along the 91 sightlines that pass close to a filament, we identify 215 (227) Lya absorption systems (components).
	- Among these, 74 Lya systems are aligned in position and velocity with the galaxy filaments, indicating that these absorbers and the galaxies trace the same large-scale structure.
- The strongest Lya absorbers are preferentially found near galaxies or close to the axis of a filament, although there is substantial scatter in this relation.

##### [Improved Treatment of Host-Galaxy Correlations in Cosmological Analyses With Type Ia Supernovae](http://arxiv.org/abs/2102.01776) [(PDF)](http://arxiv.org/pdf/2102.01776.pdf)

- Using a spectroscopically-confirmed sample of $\sim$1600 SNIa, we develop the first empirical model of underlying populations for SNIa light-curve properties that includes their dependence on host-galaxy stellar mass.
- These populations are important inputs to simulations that are used to model selection effects and correct distance biases within the BEAMS with Bias Correction (BBC) framework.
- Here we improve BBC to also account for SNIa-host correlations, and we validate this technique on simulated data samples.
- We recover the input relationship between SNIa luminosity and host-galaxy stellar mass (the mass step, $\gamma$) to within 0.004 mags, which is a factor of 5 improvement over the previous method that results in a $\gamma$-bias of ${\sim}0.02$.
- We adapt BBC for a novel dust-based model of intrinsic brightness variations, which results in a greatly reduced mass step for data ($\gamma = 0.017 \pm 0.008$), and for simulations ($\gamma =0.006 \pm 0.007$).
- Analysing simulated SNIa, the biases on the dark energy equation-of-state, $w$, vary from $\Delta w = 0.006(5)$ to $0.010(5)$ with our new BBC method; these biases are significantly smaller than the $0.02(5)$ $w$-bias using previous BBC methods that ignore SNIa-host correlations.

##### [Orphan galaxies in semi-analytic models](http://arxiv.org/abs/2102.01837) [(PDF)](http://arxiv.org/pdf/2102.01837.pdf)

- #galaxy/sam #galaxy_halo
- The model proposed takes into account the dynamical friction drag, mass loss by tidal stripping and a proximity merger criterion, also it is simple enough to be inexpensive from a computational point of view.
- We show that while the halo mass function fails to put tight constraints on the dynamical friction, the addition of clustering information helps to better define the parameters of the model related to the spatial distribution of subhalos.
- Using the model with the best fit parameters allows us to reproduce the halo mass function to a precision better than 5 per cent, and the two point correlation function at a precision better than 10 per cent.

##### [The AMBRE Project: Origin and evolution of sulfur in the Milky Way](http://arxiv.org/abs/2102.01961) [(PDF)](http://arxiv.org/pdf/2102.01961.pdf)

- Sulfur is a volatile chemical element that plays an important role in tracing the chemical evolution of galaxies.
- We find that the [S/M] abundances ratio is compatible with a plateau-like distribution in the metal-poor regime, and then starts to decrease continuously at [M/H]~-1.0dex.
	- This decrease continues towards negative values for supersolar metallicity stars as recently reported for Mg and as predicted by Galactic chemical evolution models.
	- Moreover, sulfur-rich stars having [M/H] in the range [-1.0,-0.5] have very different kinematical and orbital properties with respect to more metal-rich and sulfur-poor ones.

##### [A new panchromatic classification of unclassified Burst Alert Telescope active galactic nuclei](http://arxiv.org/abs/2102.02044) [(PDF)](http://arxiv.org/pdf/2102.02044.pdf)

- Focusing on the 36 sources with measured redshift, we compute their spectral energy distribution (SED) from radio to $\gamma$-rays with the aim to classify these objects.
- We found a large fraction of absorbed radio-quiet AGNs (31 out of 36) and some additional rare radio-loud sources (5 out of 36), since the jet emission in hard X-rays is important for aligned jets owing to the boost produced by the beaming effect.
- With our work we can confirm the hypothesis that a number of galaxies, whose optical spectra lack AGN emission features, host an obscured active nucleus.

##### [3D Modelling and Visualisation of Observed Galaxies](http://arxiv.org/abs/2102.02141) [(PDF)](http://arxiv.org/pdf/2102.02141.pdf)

- We present a novel approach to reconstruct and visualise 3D representations of galaxies based on observational data, using the scientific visualisation software `Splotch` to generate high quality visual representations that provide a new perspective of galaxies nearby the Milky Way.
- [`Splotch`](https://wwwmpa.mpa-garching.mpg.de/~kdolag/Splotch/)

##### [AlFoCS + F3D II: unexpectedly low gas-to-dust ratios in the Fornax galaxy cluster](http://arxiv.org/abs/2102.02148) [(PDF)](http://arxiv.org/pdf/2102.02148.pdf)

- #cluster/icm #cluster/galaxy
- ALMA, ATCA, MUSE, Herschel; gas-to-dust ratios in 15 Fornax cluster galaxies 大部分是矮星系
- Gas-to-dust ratios in Fornax galaxies are systematically lower than those in field galaxies at fixed stellar mass/metallicity.
- This implies that a relatively large fraction of the metals in these Fornax systems is locked up in dust, which is possibly due to altered chemical evolution as a result of the dense environment.
- 不仅是HI气体比例低，分子气体也很缺乏; 和Virgo cluster不一样
- We propose various explanations for the low H$_2$-to-dust ratios in the Fornax cluster, including the more efficient stripping of H$_2$ compared to dust, more efficient enrichment of dust in the star formation process, and altered ISM physics in the cluster environment.

### Feb 5 

#### Relevant / Important / Useful

##### [The nature and origins of the low surface brightness outskirts of massive, central galaxies in Subaru HSC](http://arxiv.org/abs/2102.02241) [(PDF)](http://arxiv.org/pdf/2102.02241.pdf)

- #galaxy/bcg #galaxy/halo
- We explore the stellar mass density and colour profiles of 118 low redshift, 
- Our visual morphological classification reveals that $\sim 42$ percent of our sample displays tidal features, similar to previous studies, $\sim 43$ percent of the remaining sample display a diffuse stellar halo and only $\sim 14$ percent display no features, down to a limiting $\mu_{r\mathrm{-band}}$ $\sim$ 28 mag arcsec$^{-2}$.
- However, we also see a flattening of the profile ($\Sigma_* \sim 10^{7.5}$ M$_\odot$ kpc$^{-2}$) in the outskirts (up to 10 R$_{\mathrm{e}}$), which is revealed by our method of specifically targeting tidal/accretion features.
	- 这个变平很可能和PDR2 sky background的under-subtraction有关
- The stellar material in the outskirts contributes on average $\sim 10^{10}$ M$_\odot$ or a few percent of the total stellar mass and has similar colours to SDSS satellites of similar stellar mass.

##### [A Massive, Clumpy Molecular Gas Distribution and Displaced AGN in Zw 3146](http://arxiv.org/abs/2102.02300) [(PDF)](http://arxiv.org/pdf/2102.02300.pdf)

- #galaxy/bcg #cluster/galaxy #cluster/icm
- ALMA observation of the CO(1-0) line emission in the central galaxy of the Zw 3146 galaxy cluster ($z=0.2906$).
- The $5\times 10^{10} M_{\odot}$ supply of molecular gas, which is confined to the central 4 kpc, is marginally resolved into three extensions that are reminiscent of the filaments observed in similar systems.
	- 都和X-ray空腔有联系，可能是rising气体泡尾部凝结出来的
- 没有规则运动的迹象; It is the molecular gas, not the continuum source, that lies at the gravitational center of the brightest cluster galaxy.

##### [The Fornax3D project: Assembly histories of lenticular galaxies from a combined dynamical and population orbital analysis](http://arxiv.org/abs/2102.02449) [(PDF)](http://arxiv.org/pdf/2102.02449.pdf)

- #cluster/galaxy #galaxy/etg
- Three edge-on lenticular galaxies from the Fornax3D project -- FCC 153, FCC 170, and FCC 177 -- in order to infer their mass assembly histories individually and in the context of the Fornax cluster.
	- We find that the galaxies studied here have all been able to form dynamically-cold (intrinsic vertical velocity dispersion $\sigma_z \lesssim 50\ {\rm km}\ {\rm s}^{-1}$) stellar disks after cluster infall.
	- The pre-existing (old) high angular momentum components have retained their angular momentum (orbital circularity $\lambda_z > 0.8$) through to the present day.
- 和NGC3115这种低密度环境下的星系比，可以看到因为cluster环境导致的恒星吸积和并合过程的减少
- There is tentative evidence for enhancement in the luminosity-weighted intrinsic vertical velocity dispersion due to the cluster environment.
	- But importantly, there is an indication that metallicity may be a key driver of this relation.

#### Interesting / Keep in Mind

##### [Variational Inference for Deblending Crowded Starfields](http://arxiv.org/abs/2102.02409) [(PDF)](http://arxiv.org/pdf/2102.02409.pdf)

- #photometry #machine_learning 
- We propose StarNet, a fully Bayesian method to deblend sources in astronomical images of crowded star fields.
- Wake-sleep, which minimizes forward KL divergence, has significant benefits compared to traditional variational inference, which minimizes a reverse KL divergence.
- 在SDSS M2球状星团图像上表现比PCAT和DAOPHOT好; 而且要快很多

#### Others

##### [Which AGN Jets Quench Star Formation in Massive Galaxies?](http://arxiv.org/abs/2102.02206) [(PDF)](http://arxiv.org/pdf/2102.02206.pdf)

- #quenching 
- 不确定的jet参数: jet energy form (kinetic, thermal, and cosmic ray (CR) energy), energy, momentum, and mass flux, magnetic field strength and geometry, jet precession angle and period, opening-angle, and duty cycle.
- 基于FIRE模拟：CR-dominated jets can most efficiently quench the central galaxy through a combination of CR pressure support and a modification of the thermal instability.
	- For a fixed energy flux, jets with higher specific energy (longer cooling times) quench more effectively.
- 磁场的影响不大

##### [A deep search for decaying dark matter with XMM-Newton blank-sky observations](http://arxiv.org/abs/2102.02207) [(PDF)](http://arxiv.org/pdf/2102.02207.pdf)

- In this work, we perform the most sensitive search to date for this and other decaying DM scenarios across the mass range from 5 to 16 keV using archival XMM-Newton data.
- No evidence is found for unassociated X-ray lines, leading us to produce the strongest constraints to date on decaying DM in this mass range.

##### [Accurate Identification of Galaxy Mergers with Stellar Kinematics](http://arxiv.org/abs/2102.02208) [(PDF)](http://arxiv.org/pdf/2102.02208.pdf)

- 模拟MaNGA观测到的恒星运动学map：基于linear discriminant analysis (LDA)进行分类; 和图像分类比，在识别post-merger上精确一些
- The major mergers are best identified by predictors that trace global kinematic features, while the minor mergers rely on local features that trace a secondary stellar component.

##### [Substructure at High Speed II: The Local Escape Velocity and Milky Way Mass with Gaia DR2](http://arxiv.org/abs/2102.02211) [(PDF)](http://arxiv.org/pdf/2102.02211.pdf)

- In Necib $\&$ Lin (2021), we introduced a strategy to robustly measure the escape velocity. 本文加入了对银河系子结构的考虑
- Based on a fit with three bound components to account for the disk, relaxed halo, and the Gaia Sausage, we find the escape velocity of the Milky Way at the solar position to be $v_{\rm{esc}}= 484.6^{+17.8}_{-7.4}$ km/s.
- Assuming a Navarro-Frenck-White dark matter profile, and taken in conjunction with a recent measurement of the circular velocity at the solar position of $v_c = 230 \pm 10$ km/s, we find a Milky Way concentration of $c_{200} = 13.8^{+6.0}_{-4.3}$ and a mass of $M_{200} = 7.0^{+1.9}_{-1.2} \times 10^{11} M_{\odot}$, which is considerably lighter than previous measurements.

##### [Gamma-ray detection toward the Coma cluster with Fermi-LAT: Implications for the cosmic ray content in the hadronic scenario](http://arxiv.org/abs/2102.02251) [(PDF)](http://arxiv.org/pdf/2102.02251.pdf)
- We confirm that a significant gamma-ray signal is observed within the characteristic radius $\theta_{500}$ of the Coma cluster, with a test statistic TS~27 for our baseline model. Coma星系团中的Gamma-ray信号
- The presence of a possible point source may account for most of the observed signal.
- However, this source could also correspond to the peak of the diffuse emission of the cluster itself and extended models match the data better.
- Assuming an hadronic origin of the signal, our results provide the first quantitative measurement of the cosmic ray proton content in a cluster.

##### [Epoch of reionization parameter estimation with the 21-cm bispectrum](http://arxiv.org/abs/2102.02310) [(PDF)](http://arxiv.org/pdf/2102.02310.pdf)

- [`21CMMC` - Constrain 21cmFAST parameters using MCMC](https://github.com/21cmfast/21CMMC)
- [`bifft` - Fast code to measure the bispectrum](https://bitbucket.org/caw11/bifft/src/master/)
- We extend the MCMC sampler 21cmMC to use the fast bispectrum code, BiFFT, when computing the likelihood.
- We create mock 1000h observations with SKA1-low, using PyObs21 to account for uv-sampling and thermal noise.
- Assuming the spin temperature is much higher than that of the CMB, we consider two different reionization histories for our mock observations: fiducial and late-reionization.

##### [Self-Interacting Dark Matter and the Excess of Small-Scale Gravitational Lenses](http://arxiv.org/abs/2102.02375) [(PDF)](http://arxiv.org/pdf/2102.02375.pdf)

- We propose a self-interacting dark matter (SIDM) scenario, where a population of subhalos in the clusters experiences gravothermal collapse.
- Our results indicate that strong gravitational lensing can provide a promising test of the self-interacting nature of dark matter.

##### [Probing the physical properties of the intergalactic medium using gamma-ray bursts](http://arxiv.org/abs/2102.02530) [(PDF)](http://arxiv.org/pdf/2102.02530.pdf)

- #galaxy/igm
- We use Gamma-ray burst (GRB) spectra total continuum absorption to estimate the key intergalactic medium (IGM) properties of hydrogen column density ($\mathit{N}\textsc{hxigm}$), metallicity, temperature and ionisation parameter over a redshift range of $1.6 \leq z \leq 6.3$, using photo-ionisation (PIE) and collisional ionisation equilibrium (CIE) models for the ionised plasma.
- We find that the IGM property results are similar, regardless of whether the model assumes all PIE or CIE.
- The PIE model implies a less rapid decline in average metallicity with redshift compared to CIE.
- Using our model, we conclude that the IGM contributes substantially to the total absorption seen in GRB spectra and that this contribution rises with redshift, explaining why the hydrogen column density inferred from X-rays is substantially in excess of the intrinsic host contribution measured in UV.

##### [Jellyfish galaxy candidates in MACS J0717.5+3745 and thirty-nine other clusters of the DAFT/FADA and CLASH surveys](http://arxiv.org/abs/2102.02595) [(PDF)](http://arxiv.org/pdf/2102.02595.pdf)

- #cluster/galaxy 
- We searched for jellyfish galaxy candidates in a sample of 40 clusters from the DAFT/FADA and CLASH surveys covering the redshift range 0.2<z<0.9.
	- We found 81 jellyfish candidates in the extended region around MACS0717, and 97 in 22 other clusters.
	- We find that jellyfish candidates tend to be star forming objects, with blue colours, young ages, high star formation rates and specific star formation rates.
- Jellyfish galaxy candidates in MACS0717 tend to avoid the densest regions of the cluster, while this does not appear to be the case in the other clusters.

##### [The Infrared Emission and Vigorous Star Formation of Low-redshift Quasars](http://arxiv.org/abs/2102.02695) [(PDF)](http://arxiv.org/pdf/2102.02695.pdf)

- 从红外SED上估计QSO的SFR
	- From comparison with an independent star formation rate indicator based on [Ne II] 12.81 $\mu m$ and [Ne III] 15.56 $\mu m$, that the torus-subtracted, total infrared ($8-1000 \mu m$) emission yields robust star formation rates in the range $\sim 1-250 M_\odot {\rm yr^{-1}}$.
- Combined with available stellar mass estimates, the vast majority ($\sim 75\%-90\%$) of the quasars lie on or above the main sequence of local star-forming galaxies, including a significant fraction ($\sim 50\%-70\%$) that would qualify as starburst systems.

##### [Evolution of subhalo orbits in a smoothly-growing host halo potential](http://arxiv.org/abs/2102.02786) [(PDF)](http://arxiv.org/pdf/2102.02786.pdf)

- #galaxy_halo
- We study subhalo orbital evolution using numerical calculations in which subhaloes are modelled as massless particles orbiting in a time-varying spherical potential.
- We find that the radial action of the subhalo orbit decreases over the first few orbits, indicating that the response to the growth of the host halo is not adiabatic during this phase. The subhalo orbits can shrink by a factor of $\sim$1.5 in this phase.
- Given these results, we consider the spatial distribution of the population of subhaloes identified in high-resolution cosmological simulations.
	- We find that it is consistent with this population having been accreted at z < 3, indicating that any subhaloes accreted earlier are unresolved in the simulations. 过早吸积进来的subhalo已经无法分辨
- 可以解释NGC1052-DF2这类星系，但不改变这些星系很罕见的结论

##### [Galactic Isotopic Decomposition for the Sculptor Dwarf Spheroidal Galaxy](http://arxiv.org/abs/2102.02790) [(PDF)](http://arxiv.org/pdf/2102.02790.pdf)

- We present an isotopic history model for the Sculptor dSph galaxy based on astrophysical processes, which is a complementary approach to GCE models.
	- 能估计每种物理过程的元素产出贡献
	- We estimate the isotopic composition of Sculptor's late stage evolution using OMEGA, and we use BBN as the other boundary condition.
		- OMEGA GCE code (Côté et al. 2017)
	- We find that Type 1a SNe contribute approximately 86 per cent to the late stage evolution Fe abundance, which is greater than typical MW solar values of approximately 70 per cent, and in agreement with other dSph chemical evolution studies.
- The model also finds that NSMs only contribute approximately 30 per cent to the late stage evolution Eu abundance, further suggesting that CCSNe are the more dominant r-process progenitor in dSphs. 中子星并合对Eu丰度的贡献不是最重要的


### Feb 8 

#### Relevant / Important / Useful

#### Interesting / Keep in Mind 

#### Others

##### [deeplenstronomy: A dataset simulation package for strong gravitational lensing](http://arxiv.org/abs/2102.02830) [(PDF)](http://arxiv.org/pdf/2102.02830.pdf)

- This work introduces and summarizes deeplenstronomy, an open-source Python package that enables efficient, large-scale, and reproducible simulation of images of astronomical systems.
- A full suite of unit tests, documentation, and example notebooks are available at https://deepskies.github.io/deeplenstronomy/ .

##### [On the Observational Difference Between the Accretion Disk-Corona Connections among Super- and Sub-Eddington Accreting Active Galactic Nuclei](http://arxiv.org/abs/2102.02832) [(PDF)](http://arxiv.org/pdf/2102.02832.pdf)

- Using high-state observations with simultaneous X-ray and UV/optical measurements, we investigate whether super-Eddington accreting AGNs exhibit different accretion disk-corona connections compared to sub-Eddington accreting AGNs.
- We find tight correlations between the X-ray-to-UV/optical spectral slope parameter ($\alpha_{\rm OX}$) and the monochromatic luminosity at $2500~\r{A}$($L_{\rm 2500~\r{A}}$) for both the super- and sub-Eddington subsamples.
- Super-Eddington accreting AGNs are not particularly X-ray weak in general compared to sub-Eddington accreting AGNs.
- A fraction of super-Eddington accreting AGNs show strong X-ray variability, probably due to small-scale gas absorption, and we highlight the importance of employing high-state (intrinsic) X-ray radiation to study the accretion disk-corona connections in AGNs.

##### [SIGAME v3: Gas Fragmentation in Post-processing of Cosmological Simulations for More Accurate Infrared Line Emission Modeling](http://arxiv.org/abs/2102.02868) [(PDF)](http://arxiv.org/pdf/2102.02868.pdf)

- SImulator of GAlaxy Millimeter/submillimeter Emission (S\'IGAME): model higher gas densities by parametrizing the gas density probability distribution function (PDF) in higher resolution simulations for use as a look-up table, allowing for more adaptive PDFs than in previous work.
- S\'IGAME v3 is tested on redshift z = 0 galaxies drawn from the SIMBA cosmological simulation for eight FIR emission lines tracing vastly different interstellar medium phases.
- Including dust radiative transfer with SKIRT and high resolution photo-ionization models with Cloudy
- We attribute the remaining disagreement with observations to the lack of precise attenuation of the interstellar light on subgrid scales (<200 pc).

##### [Radio multifrequency observations of galaxy clusters. The Abell 399$-$401 pair](http://arxiv.org/abs/2102.02900) [(PDF)](http://arxiv.org/pdf/2102.02900.pdf)

- Galaxy clusters are assembled via merging of smaller structures, in a process that generates shocks and turbulence in the intra cluster medium and produces radio emission in the form of halos and relics.
- The cluster pair A 399-A 401 represents a special case: both clusters host a radio halo and recent LOFAR observations at 140~MHz revealed the presence of a radio bridge connecting the two clusters and two candidate relics, one South of A 399 and the other in between the two clusters in proximity of a shock front detected in X-ray observations.
- In this paper we present Westerbork observations at 1.7, 1.4 and 1.2~GHz and 346~MHz of the A 399-A 401 cluster pair.
- We detected the radio halo in the A 399 cluster at 346~MHz, extending up to $\sim 650$~kpc and with a $125 \pm 6$~mJy flux density.
- Its spectral index between 1.4~GHz and 346~MHz and between 140~MHz and 346~MHz is $\alpha = 1.47 \pm 0.05$, and $\alpha = 1.75 \pm 0.14$respectively.
- The two candidate relics are also seen at 346~MHz and we determined their spectral index to be $\alpha = 1.10 \pm 0.14$and $\alpha = 1.46 \pm 0.14$.
- The low surface brightness bridge connecting the two clusters is below the noise level at 346~MHz, therefore we constrained the bridge average spectral to be steep, i.e $\alpha > 1.5$at $2\sigma$confidence level.
- This result favours the scenario where dynamically-induced turbulence is a viable mechanism to reaccelerate a population of mildly relativistic particles and amplify magnetic fields even in cluster bridges, i.e on scales of a few Mpcs.

##### [Bar-like galaxies in IllustrisTNG](http://arxiv.org/abs/2102.03076) [(PDF)](http://arxiv.org/pdf/2102.03076.pdf)

- We study a sample of bar-like galaxies in the Illustris TNG100 simulation, in which almost the whole stellar component is in the form of a prolate spheroid.
- The sample is different from the late-type barred galaxies studied before.
- In addition to the requirement of a high enough stellar mass and resolution, the 277 galaxies were selected based on the single condition of a low enough ratio of the intermediate to long axis of the stellar component.
- We followed the mass and shape evolution of the galaxies as well as their interactions with other objects and divided them into three classes based on the origin of the bar and the subsequent history.
- In galaxies of class A (comprising 28% of the sample), the bar was induced by an interaction with a larger object, most often a cluster or group central galaxy, and the galaxies were heavily stripped of dark matter and gas.
- In classes B and C (27% and 45% of the sample, respectively) the bars were induced by a merger or a passing satellite, or they were formed by disk instability.
- Class B galaxies were then partially stripped of mass, while those of class C evolved without strong interactions, thus retaining their dark matter and gas in the outskirts.
- We illustrate the properties of the different classes with three representative examples of individual galaxies.
- In spite of the different evolutionary histories, the bars are remarkably similar in strength, length, and formation times.
- The gas fraction in the baryonic component within two stellar half-mass radii at the time of bar formation is always below 0.4 and usually very low, which confirms in the cosmological context the validity of this threshold, which has previously been identified in controlled simulations.
- Observational counterparts of these objects can be found among early-type fast rotators, S0 galaxies, or red spirals with bars.

##### [A new approach for the statistical denoising of Planck interstellar dust polarization data](http://arxiv.org/abs/2102.03160) [(PDF)](http://arxiv.org/pdf/2102.03160.pdf)

- Dust emission is the main foreground to Cosmic Microwave Background (CMB) polarization.
- Its statistical characterization must be derived from the analysis of observational data because the precision required for a reliable component separation is far greater than currently achievable with physical models of the turbulent magnetized interstellar medium.
- This letter takes a significant step towards this goal by proposing a method that retrieves non-Gaussian statistical characteristics of dust emission from noisy Planck polarization observations at 353 GHz.
- We devise a statistical denoising method based on the Wavelet Phase Harmonics (WPH) statistics, which characterize the coherent structures in non-Gaussian random fields and define a generative model of the data.
- The method is validated on mock data combining a dust map from a magnetohydrodynamic simulation and Planck noise maps.
- The denoised map reproduces the true power spectrum down to scales where the noise power is an order of magnitude larger than that of the signal.
- It remains highly correlated to the true emission and retrieves some of its non-Gaussian properties.
- Applied to Planck data, the method provides a new approach towards building a generative model of dust polarization that will characterize the full complexity of the dust emission.

##### [Deep reinforcement learning for smart calibration of radio telescopes](http://arxiv.org/abs/2102.03200) [(PDF)](http://arxiv.org/pdf/2102.03200.pdf)

- Hyperparameters of these pipelines need to be tuned by hand to produce optimal results.
- We use a reinforcement learning technique called twin delayed deep deterministic policy gradient (TD3) to train an autonomous agent to perform this fine tuning.
- The autonomous agent trained in this manner is able to determine optimal settings for diverse observations and is therefore able to perform 'smart' calibration, minimizing the need for human intervention.

### Feb 9 

#### Relevant / Important / Useful

#### Interesting / Keep in Mind 

#### Others

##### [The strength and structure of the magnetic field in the galactic outflow of M82](http://arxiv.org/abs/2102.03362) [(PDF)](http://arxiv.org/pdf/2102.03362.pdf)

- We estimate the strength and structure of the fields in the starburst galaxy M82 using thermal polarized emission observations from SOFIA/HAWC+ and a potential field extrapolation.
- We modified the Davis-Chandrasekhar-Fermi method to account for the large-scale flow and the turbulent field.
- Results show that the observed magnetic fields arise from the combination of a large-scale ordered potential field associated with the outflow and a small-scale turbulent field associated with bow-shock-like features.
- Within the central $900$pc radius, the potential field accounts for $53\pm4$% of the observed turbulent magnetic energy with a median field strength of $305\pm15$$\mu$G, while small-scale turbulent magnetic fields account for the remaining $40\pm5$% with a median field strength of $222\pm19$$\mu$G.
- We estimate that the turbulent kinetic and turbulent magnetic energies are in close equipartition up to $\sim2$kpc (measured), while the turbulent kinetic energy dominates at $\sim7$kpc (extrapolated).
- We conclude that the fields are frozen into the ionized outflowing medium and driven away kinetically.
- This indicates that the magnetic field lines in the galactic wind of M82 are 'open,' providing a direct channel between the starburst core and the intergalactic medium.
- Our novel approach offers the tools needed to quantify the effects of outflows on galactic magnetic fields as well as their influence on the intergalactic medium and evolution of energetic particles.

##### [S-PLUS: LEnticular Galaxies in Stripe 82](http://arxiv.org/abs/2102.03365) [(PDF)](http://arxiv.org/pdf/2102.03365.pdf)

- #galaxy/etg 
- It aims at investigating the structural properties of Lenticular galaxies in the Stripe 82 using a combination of S-PLUS (Southern Photometric Local Universe Survey) and SDSS data.
- The morphological classification and study of the galaxies' stellar population will be performed combining the Bayesian Spectral type (from BPZ) and Morfometryka (MFMTK) parameters.
- The preliminary results, presented in this work, show how this new data set opens a new window on our understanding of the nearby universe.

##### [Evidence for r-process delay in very metal-poor stars](http://arxiv.org/abs/2102.03368) [(PDF)](http://arxiv.org/pdf/2102.03368.pdf)

- Currently, various types of astrophysical sites including neutron star mergers, magneto-rotational supernovae, and collapsars, are suggested as the origin of r-process elements.
	- The time delay between the star formation and the production of r-process elements is the key to distinguish these scenarios with the caveat that the diffusion of r-process elements in the interstellar medium also induces the delay in r-process enrichment because r-process events are rare.
- Here we study the observed Ba abundance data of very metal-poor stars as the tracer of the early enrichment history of r-process elements.
	- We find that the gradual increase of [Ba/Mg] with [Fe/H] requires a significant time delay (100 Myr -- 1 Gyr) of r-process events from star formation rather than the diffusion-induced delay.

##### [The origin of metal-poor stars on prograde disk orbits in FIRE simulations of Milky Way-mass galaxies](http://arxiv.org/abs/2102.03369) [(PDF)](http://arxiv.org/pdf/2102.03369.pdf)

- In hierarchical structure formation, metal-poor stars in and around the Milky Way (MW) originate primarily from mergers of lower-mass galaxies.
- A common expectation is therefore that metal-poor stars should have isotropic, dispersion-dominated orbits that do not correlate strongly with the MW disk.
- However, recent observations of stars in the MW show that metal-poor ([Fe/H] < -2) stars are preferentially on prograde orbits with respect to the disk.
- Using the FIRE-2 suite of cosmological zoom-in simulations of MW/M31-mass galaxies, we investigate the prevalence and origin of prograde metal-poor stars.
- Almost all (11 of 12) of our simulations have metal-poor stars preferentially on prograde orbits today and throughout most of their history: we thus predict that this is a generic feature of MW/M31-mass galaxies.
- The typical prograde-to-retrograde ratio is ~ 2:1, which depends weakly on stellar metallicity at [Fe/H] < -1.
- These trends predicted by our simulations agree well with MW observations.
- Prograde metal-poor stars originate largely from a single LMC/SMC-mass gas-rich galaxy merger, typically 7-12.5 Gyr ago, which deposited both existing metal-poor stars and significant gas on an orbital vector that sparked the formation of and/or shaped the orientation of a long-lived stellar disk, giving rise to a prograde bias for all low-metallicity stars.
- We also find sub-dominant contributions from in-situ stars formed in the host galaxy before this merger, and in some cases, additional massive mergers.
- We find few clear correlations between any properties of our MW/M31-mass galaxies at z=0 and the degree of this prograde bias as a result of diverse merger scenarios.

##### [SDSS-IV MaNGA: The Radial Profile of Enhanced Star Formation in Close Galaxy Pairs](http://arxiv.org/abs/2102.03398) [(PDF)](http://arxiv.org/pdf/2102.03398.pdf)

- We compare the radial profiles of the specific star formation rate (sSFR) in a sample of 169 star-forming galaxies in close pairs with those of mass-matched control galaxies in the SDSS-IV MaNGA survey.
- We find that the sSFR is centrally enhanced (within one effective radius) in interacting galaxies by ~0.3 dex and that there is a weak sSFR suppression in the outskirts of the galaxies of ~0.1 dex.
- We stack the differences profiles for galaxies in five stellar mass bins between log(M/Mstar) = 9.0-11.5 and find that the sSFR enhancement has no dependence on the stellar mass.
- The same result is obtained when the comparison galaxies are matched to each paired galaxy in both stellar mass and redshift.
- In addition, we find that that the sSFR enhancement is elevated in pairs with nearly equal masses and closer projected separations, in agreement with previous work based on single-fiber spectroscopy.
- We also find that the sSFR offsets in the outskirts of the paired galaxies are dependent on whether the galaxy is the more massive or less massive companion in the pair.
- The more massive companion experiences zero to a positive sSFR enhancement while the less massive companion experiences sSFR suppression in their outskirts.
- Our results illustrate the complex tidal effects on star formation in closely paired galaxies.


##### [Wandering of the central black hole in a galactic nucleus and correlation of the black hole mass with the bulge mass](http://arxiv.org/abs/2102.03478) [(PDF)](http://arxiv.org/pdf/2102.03478.pdf)

- We investigate a mechanism for a super-massive black hole at the center of a galaxy to wander in the nucleus region.
- A situation is supposed in which the central black hole tends to move by the gravitational attractions from the nearby molecular clouds in a nuclear bulge but is braked via the dynamical frictions by the ambient stars there.
- We estimate the approximate kinetic energy of the black hole in an equilibrium between the energy gain rate through the gravitational attractions and the energy loss rate through the dynamical frictions, in a nuclear bulge composed of a nuclear stellar disk and a nuclear stellar cluster as observed from our Galaxy.
- The wandering distance of the black hole in the gravitational potential of the nuclear bulge is evaluated to get as large as several 10 pc, when the black hole mass is relatively small.
- The distance, however, shrinks as the black hole mass increases and the equilibrium solution between the energy gain and loss disappears when the black hole mass exceeds an upper limit.
- As a result, we can expect the following scenario for the evolution of the black hole mass: When the black hole mass is smaller than the upper limit, mass accretion of the interstellar matter in the circum-nuclear region, causing the AGN activities, makes the black hole mass larger.
- However, when the mass gets to the upper limit, the black hole loses the balancing force against the dynamical friction and starts spiraling downward to the gravity center.
- From simple parameter scaling, the upper mass limit of the black hole is found to be proportional to the bulge mass and this could explain the observed correlation of the black hole mass with the bulge mass.

##### [Halo shapes constrained from a pure sample of central galaxies in KiDS-1000](http://arxiv.org/abs/2102.03549) [(PDF)](http://arxiv.org/pdf/2102.03549.pdf)

- We present measurements of $f_h$, the ratio of the aligned components of the projected halo and galaxy ellipticities, for a sample of central galaxies using weak gravitational lensing data from the Kilo-Degree Survey (KiDS).
- Using a lens galaxy shape estimation that is more sensitive to outer galaxy regions, we find $f_{\rm h}=0.50\pm0.20$for our full sample and $f_{\rm h}=0.55\pm0.19$for an intrinsically red (and therefore higher stellar-mass) sub-sample, rejecting the hypothesis of round halos and/or galaxies being un-aligned with their parent halo at $2.5\sigma$and $2.9\sigma$, respectively.
- We quantify the 93.4% purity of our central galaxy sample using numerical simulations and overlapping spectroscopy from the Galaxy and Mass Assembly survey.
- This purity ensures that the interpretation of our measurements is not complicated by the presence of a significant fraction of satellite galaxies.
- Restricting our central galaxy ellipticity measurement to the inner isophotes, we find $f_{\rm h}=0.34\pm0.17$for our red sub-sample, suggesting that the outer galaxy regions are more aligned with their dark matter halos compared to the inner regions.
- Our results are in agreement with previous studies and suggest that lower mass halos are rounder and/or less aligned with their host galaxy than samples of more massive galaxies, studied in galaxy groups and clusters.

##### [CNN Architecture Comparison for Radio Galaxy Classification](http://arxiv.org/abs/2102.03780) [(PDF)](http://arxiv.org/pdf/2102.03780.pdf)

- The morphological classification of radio sources is important to gain a full understanding of galaxy evolution processes and their relation with local environmental properties.
- Furthermore, the complex nature of the problem, its appeal for citizen scientists and the large data rates generated by existing and upcoming radio telescopes combine to make the morphological classification of radio sources an ideal test case for the application of machine learning techniques.
- One approach that has shown great promise recently is Convolutional Neural Networks (CNNs).
- Literature, however, lacks two major things when it comes to CNNs and radio galaxy morphological classification.
- Firstly, a proper analysis of whether overfitting occurs when training CNNs to perform radio galaxy morphological classification using a small curated training set is needed.
- Secondly, a good comparative study regarding the practical applicability of the CNN architectures in literature is required.
- Both of these shortcomings are addressed in this paper.
- Multiple performance metrics are used for the latter comparative study, such as inference time, model complexity, computational complexity and mean per class accuracy.
- As part of this study we also investigate the effect that receptive field, stride length and coverage has on recognition performance.
- For the sake of completeness, we also investigate the recognition performance gains that we can obtain by employing classification ensembles.
- A ranking system based upon recognition and computational performance is proposed.
- MCRGNet, Radio Galaxy Zoo and ConvXpress (novel classifier) are the architectures that best balance computational requirements with recognition performance.

##### [A direct and robust method to observationally constrain the halo mass function via the submillimeter magnification bias: Proof of concept](http://arxiv.org/abs/2102.03890) [(PDF)](http://arxiv.org/pdf/2102.03890.pdf)

- The main purpose of this work is to provide a method to derive tabulated observational constraints on the halo mass function (HMF) by studying the magnification bias effect on high-redshift submillimeter galaxies.
- Under the assumption of universality, we parametrize the HMF according to two traditional models, namely the Sheth and Tormen (ST) and Tinker fits and assess their performance in explaining the measured data within the {\Lambda} cold dark matter ({\Lambda}CDM) model.
- We also study the potential influence of the halo occupation distribution (HOD) parameters in this analysis and discuss two important aspects regarding the HMF parametrization.
- Methods.
- We measure the cross-correlation function between a foreground sample of GAMA galaxies with redshifts in the range $0.2<z<0.8$and a background sample of H-ATLAS galaxies with redshifts in the range $1.2<z<4.0$and carry out an MCMC algorithm to check this observable against its mathematical prediction within the halo model formalism.
- Results.
- If all HMF parameters are assumed to be positive, the ST fit only seems to fully explain the measurements by forcing the mean number of satellite galaxies in a halo to increase substantially from its prior mean value.
- The Tinker fit, on the other hand, provides a robust description of the data without relevant changes in the HOD parameters, but with some dependence on the prior range of two of its parameters.
- When the normalization condition for the HMF is dropped and we allow negative values of the $p_1$parameter in the ST fit, all the involved parameters are better determined, unlike the previous models, thus deriving the most general HMF constraints.
- While all cases are in agreement with the traditional fits within the uncertainties, the last one hints at a slightly higher number of halos at intermediate and high masses, raising the important point of the allowed parameter range.

##### [The physical properties of local (U)LIRGs: a comparison with nearby early- and late-type galaxies](http://arxiv.org/abs/2102.03913) [(PDF)](http://arxiv.org/pdf/2102.03913.pdf)

- In order to pinpoint the place of the (U)LIRGs in the local Universe we examine the properties of a sample of 67 such systems and compare them with those of 268 ETGs and 542 LTGs from the DustPedia database.
- We make use of multi-wavelength photometric data and the CIGALE SED fitting code to extract their physical parameters.
- The median SEDs as well as the values of the derived parameters were compared to those of the local ETGs and LTGs.
- In addition to that, (U)LIRGs were divided into seven classes, according to the merging stage of each system, and variations in the derived parameters were investigated.
- (U)LIRGs occupy the 'high-end' on the dust and stellar mass, and SFR in the local Universe with median values of 5.2$\times10^7~M_{\odot}$, 6.3$\times10^{10}~M_{\odot}$and 52$~M_{\odot}$yr$^{-1}$, respectively.
- The PDR-dust emission in (U)LIRGs is 11.7% of the total dust luminosity, significantly higher than ETGs (1.6%) and the LTGs (5.2%).
- The median value of the dust temperature in (U)LIRGs is 32 K, which is higher compared to both the ETGs (28 K) and the LTGs (22 K).
- Small differences, in the derived parameters, are seen for the seven merging classes of our sample of (U)LIRGs with the most evident one being on the star-formation rate, where in systems in late merging stages the median SFR reaches up to 99 M$_{\odot}$yr$^{-1}$compared to 26 M$_{\odot}$yr$^{-1}$for the isolated ones.
- In contrast to the local normal galaxies where old stars dominate the stellar emission, the young stars in (U)LIRGs contribute with 64% of their luminosity to the total stellar luminosity.
- The fraction of the dust-absorbed stellar luminosity is extremely high in (U)LIRGs (78%) compared to 7% and 25% in ETGs and ETGs, respectively.
- The fraction of the stellar luminosity used to heat up the dust grains is very high in (U)LIRGs, while 74% of the dust emission comes from the young stars.

##### [Gravitation And the Universe from large Scale-Structures: The GAUSS mission concept](http://arxiv.org/abs/2102.03931) [(PDF)](http://arxiv.org/pdf/2102.03931.pdf)

- The mission concept, described in this White Paper, GAUSS, aims at being a mission to fully map the cosmic web up to the reionization era, linking early and late evolution, to tackle and disentangle the crucial degeneracies persisting after the Euclid era between dark matter and inflation properties, dark energy, structure growth and gravitation at large scale.

##### [Weak lensing mass reconstruction using sparsity and a Gaussian random field](http://arxiv.org/abs/2102.04127) [(PDF)](http://arxiv.org/pdf/2102.04127.pdf)

- 宇宙物质密度分布分成两个成分：
	- A sparsity-based component that captures the non-Gaussian structure of the field, such as peaks or halos at different spatial scales
	- A Gaussian random field, which is known to well represent the linear characteristics of the field.
- [MCALens](https://github.com/CosmoStat/cosmostat)
	- MCAlens is based on an alternating minimization incorporating both sparse recovery and a proximal iterative Wiener filtering.

##### [Galaxy Lookback Evolution Models - a Comparison with Magneticum Cosmological Simulations and Observations](http://arxiv.org/abs/2102.04135) [(PDF)](http://arxiv.org/pdf/2102.04135.pdf)

- We construct empirical models of star-forming galaxy evolution assuming that individual galaxies evolve along well-known scaling relations between stellar mass, gas mass and star formation rate following a simple description of chemical evolution.
- We test these models by a comparison with observations and with detailed Magneticum high resolution hydrodynamic cosmological simulations.
- Galaxy star formation rates, stellar masses, gas masses, ages, interstellar medium and stellar metallicities are compared.
- It is found that these simple lookback models capture many of the crucial aspects of galaxy evolution reasonably well.
- Their key assumption of a redshift dependent power law relationship between galaxy interstellar medium gas mass and stellar mass is in agreement with the outcome of the complex Magneticum simulations.
- Star formation rates decline towards lower redshift not because galaxies are running out of gas, but because the fraction of the cold ISM gas, which is capable of producing stars, becomes significantly smaller.
- Gas accretion rates in both model approaches are of the same order of magnitude.
- Metallicity in the Magneticum simulations increases with the ratio of stellar mass to gas mass as predicted by the lookback models.
- The mass metallicity relationships agree and the star formation rate dependence of these relationships is also reproduced.
- We conclude that these simple models provide a powerful tool for constraining and interpreting more complex models based on cosmological simulations and for population synthesis studies analyzing integrated spectra of stellar populations.

##### [Galaxy and Mass Assembly (GAMA): Tracing galaxy environment using the marked correlation function](http://arxiv.org/abs/2102.04177) [(PDF)](http://arxiv.org/pdf/2102.04177.pdf)

- We investigate how different galaxy properties - luminosities in u, g, r, J, K-bands, stellar mass, star formation rate and specific star formation rate trace the environment in the local universe.
- We also study the effect of survey flux limits on galaxy clustering measurements.
- We measure the two-point correlation function (2pCF) and marked correlation functions (MCFs) using the aforementioned properties as marks.
- We use nearly stellar-mass-complete galaxy sample in the redshift range 0.1 < z < 0.16 from the Galaxy And Mass Assembly (GAMA) survey with a flux limit of r < 19.8.
- Further, we impose a brighter flux limit of r < 17.8 to our sample and repeat the measurements to study how this affects galaxy clustering analysis.
- We compare our results to measurements from the Sloan Digital Sky Survey (SDSS) with flux limits of r < 17.8 and r < 16.8.
- We show that the stellar mass is the best tracer of galaxy environment, the K-band luminosity being a good substitute, although such a proxy sample misses close pairs of evolved, red galaxies.
- We also confirm that the u-band luminosity is a good, but not a perfect proxy of star formation rate in the context of galaxy clustering.
- We observe an effect of the survey flux limit on clustering studies - samples with a higher flux limit (smaller magnitude) miss some information about close pairs of starburst galaxies.

##### [Stellar Dynamical Modeling - Accuracy of 3D Density Estimation for Edge-on Axisymmetric Galaxies](http://arxiv.org/abs/2102.04189) [(PDF)](http://arxiv.org/pdf/2102.04189.pdf)

- From Rybicki's analysis using the Fourier slice theorem, mathematically it is possible to reproduce uniquely an edge-on axisymmetric galaxy's 3D light distribution from its 2D surface brightness.
- Utilizing galaxies from a cosmological simulation, we examine the ability of Syer and Tremaine's made-to-measure method and Schwarzschild's method for stellar dynamical modeling to do so for edge-on oblate axisymmetric galaxies.
- Overall, we find that the methods do not accurately recover the 3D distributions, with the made-to-measure method producing more accurate estimates than Schwarzschild's method.
- Our results have implications broader than just luminosity density, and affect other luminosity-weighted distributions within galaxies, for example, age and metallicity.

##### [Simulating the transport of relativistic electrons and magnetic fields injected by radio galaxies in the intracluster medium](http://arxiv.org/abs/2102.04193) [(PDF)](http://arxiv.org/pdf/2102.04193.pdf)

- Radio galaxies play an important role in the seeding of cosmic rays and magnetic fields in galaxy clusters.
- Here, we simulate the evolution of relativistic electrons injected into the intracluster medium by radio galaxies.
- Using passive tracer particles added to magnetohydrodynamical adaptive-mesh simulations, we calculate the evolution of the spectrum of relativistic electrons taking into account energy losses and re-acceleration mechanisms associated with the dymamics of the intracluster medium.
- Re-acceleration can occur at shocks via diffusive shock acceleration, and in turbulent flows via second-order Fermi re-acceleration.
- Relativistic electrons from radio galaxies are found to fill the intracluster medium over scales of several $100 \rm ~Myr$, and they create a stable reservoir of fossil electrons which remains available for further re-acceleration by shock waves and turbulent gas motions.
- In the near future, deep radio observations (especially at low frequencies) are likely to probe such mechanisms in galaxy clusters.

##### [An Unbiased Estimator of the Full-sky CMB Angular Power Spectrum using Neural Networks](http://arxiv.org/abs/2102.04327) [(PDF)](http://arxiv.org/pdf/2102.04327.pdf)

- Accurate estimation of the Cosmic Microwave Background (CMB) angular power spectrum is enticing due to the prospect for precision cosmology it presents.
- Galactic foreground emissions, however, contaminate the CMB signal and need to be subtracted reliably in order to lessen systematic errors on the CMB temperature estimates.
- Typically bright foregrounds in a region lead to further uncertainty in temperature estimates in the area even after some foreground removal technique is performed and hence determining the underlying full-sky angular power spectrum poses a challenge.
- We explore the feasibility of utilizing artificial neural networks to predict the angular power spectrum of the full sky CMB temperature maps from the observed angular power spectrum of the partial sky in which CMB temperatures in some bright foreground regions are masked.
- We present our analysis at large angular scales with two different masks.
- We produce unbiased predictions of the full-sky angular power spectrum and the underlying theoretical power spectrum using neural networks.
- Our predictions are also uncorrelated to a large extent.
- We further show that the multipole-multipole covariances of the predictions of the full-sky spectra made by the ANNs are much smaller than those of the estimates obtained using the method of pseudo-$C_l$.

##### [The Kinematic Richness of Star Clusters - II. Stability of Spherical Anisotropic Models with Rotation](http://arxiv.org/abs/2102.04383) [(PDF)](http://arxiv.org/pdf/2102.04383.pdf)

- We study the bar instability in collisionless, rotating, anisotropic, stellar systems, using N-body simulations and also the matrix technique for calculation of modes with the perturbed collisionless Boltzmann equation.
- These methods are applied to spherical systems with an initial Plummer density distribution, but modified kinematically in two ways: the velocity distribution is tangentially anisotropic, using results of Dejonghe, and the system is set in rotation by reversing the velocities of a fraction of stars in various regions of phase space, a la Lynden-Bell.
- The aim of the N-body simulations is first to survey the parameter space, and, using those results, to identify regions of phase space (by radius and orbital inclination) which have the most important influence on the bar instability.
- The matrix method is then used to identify the resonant interactions in the system which have the greatest effect on the growth rate of a bar.
- Complementary series of N-body simulations examine these processes in relation to the evolving frequency distribution and the pattern speed.
- Finally, the results are synthesised with an existing theoretical framework, and used to consider the old question of constructing a stability criterion.

##### [BAT AGN Spectroscopic Survey-XXIII. A New Mid-Infrared Diagnostic for Absorption in Active Galactic Nuclei](http://arxiv.org/abs/2102.04412) [(PDF)](http://arxiv.org/pdf/2102.04412.pdf)

- In this study, we use the SWIFT/BAT AGN sample, which has received extensive multiwavelength follow-up analysis as a result of the BAT AGN Spectroscopic Survey (BASS), to develop a diagnostic for nuclear obscuration by examining the relationship between the line-of-sight column densities ($N_{\rm{H}}$), the 2-10 keV-to-$12 \rm{\mu m}$luminosity ratio, and WISE mid-infrared colors.
- We demonstrate that heavily obscured AGNs tend to exhibit both preferentially ''redder'' mid-infrared colors and lower values of $L_{\rm{X, Obs.
- }}$/$L_{12 \rm{\mu m}}$than less obscured AGNs, and we derive expressions relating $N_{\rm{H}}$to the $L_{\rm{X, Obs.
- }}$/$L_{12 \rm{\mu m}}$and $L_{22 \rm{\mu m}}$/$L_{4.6 \rm{\mu m}}$luminosity ratios as well as develop diagnostic criteria using these ratios.
- Our diagnostic regions yield samples that are $\gtrsim80$% complete and $\gtrsim60$% pure for AGNs with log($N_{\rm{H}})\geq24$, as well as $\gtrsim85$% pure for AGNs with $\rm{log}(N_{\rm{H}})\gtrsim23.5$.
- We find that these diagnostics cannot be used to differentiate between optically star forming galaxies and active galaxies.
- Further, mid-IR contributions from host galaxies that dominate the observed $12~\rm{\mu m}$emission can lead to larger apparent X-ray deficits and redder mid-IR colors than the AGNs would intrinsically exhibit, though this effect helps to better separate less obscured and more obscured AGNs.
- Finally, we test our diagnostics on two catalogs of AGNs and infrared galaxies, including the XMM-Newton XXL-N field, and we identify several known Compton-thick AGNs as well as a handful of candidate heavily obscured AGNs based upon our proposed obscuration diagnostics.

##### [Probing the innermost regions of AGN jets and their magnetic fields with RadioAstron IV. The quasar 3C 345 at 18 cm: Magnetic field structure and brightness temperature](http://arxiv.org/abs/2102.04441) [(PDF)](http://arxiv.org/pdf/2102.04441.pdf)

- We study the innermost jet morphology and magnetic field strength in the AGN 3C 345 with an unprecedented resolution using images obtained within the framework of the key science programme on AGN polarisation of the Space VLBI mission RadioAstron.
- Methods.
- We observed the flat spectrum radio quasar 3C 345 at 1.6 GHz on 2016 March 30 with RadioAstron and 18 ground-based radio telescopes in full polarisation mode.
- Results.
- Our images, in both total intensity and linear polarisation, reveal a complex jet structure at 300 $\mu$as angular resolution, corresponding to a projected linear scale of about 2 pc or a few thousand gravitational radii.
- We identify the synchrotron self-absorbed core at the jet base and find the brightest feature in the jet 1.5 mas downstream of the core.
- Several polarised components appear in the Space VLBI images that cannot be seen from ground array-only images.
- Except for the core, the electric vector position angles follow the local jet direction, suggesting a magnetic field perpendicular to the jet.
- This indicates the presence of plane perpendicular shocks in these regions.
- Additionally, we infer a minimum brightness temperature at the largest $(u,v)$-distances of $1.1\times 10^{12}$K in the source frame, which is above the inverse Compton limit and an order of magnitude larger than the equipartition value.
- This indicates locally efficient injection or re-acceleration of particles in the jet to counter the inverse Compton cooling or the geometry of the jet creates significant changes in the Doppler factor, which has to be $>11$to explain the high brightness temperatures.

### Feb 10 

#### Relevant / Important / Useful

##### [The Age of the Universe with Globular Clusters: Reducing Systematic Uncertainties](http://arxiv.org/abs/2102.04486) [(PDF)](http://arxiv.org/pdf/2102.04486.pdf)

- #cosmology
- 如何解决GC年龄测量中与金属丰度简并的问题: if the metal content, distance and extinction are known, the position and morphology of the red giant branch in a color-magnitude diagram are mostly sensitive to the value of the depth of the convective envelope.
	- We demonstrate that globular cluster red giant branches are well fitted by values of the depth of the convection envelope consistent with those obtained for the Sun and this finding is robust to the adopted treatment of the stellar physics.
- This results in an age of the Universe $t_{\rm U}=13.5^{+0.16}_{-0.14} {\rm (stat.)} \pm 0.23(0.33) ({\rm sys.})$at 68\% confidence level, accounting for the formation time of globular clusters and its uncertainty.

##### [The VST Early-type GAlaxy Survey (VEGAS) data release 1](http://arxiv.org/abs/2102.04950) [(PDF)](http://arxiv.org/pdf/2102.04950.pdf)

- #galaxy/etg #galaxy/lsb #cluster/galaxy 
- We present the first data release (DR1) of the VST Early-type GAlaxy Survey (VEGAS): 43 targets (groups and clusters of galaxies) covering a total area on the sky of about 95 square degrees.
- With the DR1, we provide the reduced VST mosaics of 10 targets, which have been presented in the VEGAS publications.
- The data products are available via the [ESO Science Portal](http://www.eso.org/sci/observing/phase3/news.html#VEGAS-DR1).

##### [Resolved HI in two ultra-diffuse galaxies from contrasting non-cluster environments](http://arxiv.org/abs/2102.04564) [(PDF)](http://arxiv.org/pdf/2102.04564.pdf)

- #galaxy/udg #galaxy/lsb
- GMRT观测两个blue-UDG:
	- SdI-2 has an unusually large MHI/M* ratio =28.9, confirming a previous single dish HI observation.
	- Both galaxies display HI morphological and kinematic signatures consistent with a recent tidal interaction, which is also supported by observations from other wavelengths, including optical spectroscopy.
- Within the limits of the observations' resolution, our analysis indicates that SdI-2 is dark matter-dominated within its HI radius and this is also likely to be the case for UDG-B1.

##### [How Many Elements Matter?](http://arxiv.org/abs/2102.04992) [(PDF)](http://arxiv.org/pdf/2102.04992.pdf)

- #ssst/mw #machine_learning [[ML - Normalizing Flows]]
- We adopt a technique known as normalizing flow to reconstruct the probability distribution of Milky Way disk stars in the space of 15 elemental abundances measured by APOGEE.
- After conditioning on [Fe/H] and [Mg/H], the residual scatter for the best measured APOGEE elements is $\sigma_{[X/{\rm H}]} \lesssim 0.02$dex, consistent with APOGEE's reported statistical uncertainties of $\sim 0.01 - 0.015$dex and intrinsic scatter of $0.01-0.02$dex.
- Despite the small scatter, residual abundances display clear correlations between elements, which are too large to be explained by measurement uncertainties or by the statistical noise from our finite sample size.
- We must condition on at least seven elements (e.g., Fe, Mg, O, Si, Ni, Ca, Al) to reduce residual correlations to a level consistent with observational uncertainties, and higher measurement precision for other elements would likely reveal additional dimensions.
- We conclude that many elements have an independent story to tell, even for a "mundane" sample of disk stars and elements produced mainly by core-collapse and Type Ia supernovae.

##### [On the variation in stellar alpha-enhancements of star-forming galaxies in the EAGLE simulation](http://arxiv.org/abs/2102.04561) [(PDF)](http://arxiv.org/pdf/2102.04561.pdf)

- #galaxy/spop #galaxy/simulation #stellar_population 
- We elucidate two definitions - termed 'mean' and 'galactic' $\alpha$-enhancement - in more detail.
	- While a star-forming galaxy has a high 'mean' $\alpha$-enhancement when its stars formed rapidly, a galaxy with a large 'galactic' $\alpha$-enhancement generally had a delayed star formation history.
- We find that absorption-line strengths of Mg and Fe correlate with variations in $\alpha$-enhancement.
	- These correlations are strongest for the 'galactic' $\alpha$-enhancement.
	- 但在SF星系中年龄的变化极大的影响了alpha/Fe的测量
- The ambiguity is not severe for passive galaxies and we confirm that spectral variations in these galaxies are caused by measurable variations in $\alpha$-enhancements.

#### Interesting / Keep in Mind 

##### [Improving $z\sim7-11$ Galaxy Property Estimates with JWST/NIRCam Medium-Band Photometry](http://arxiv.org/abs/2102.04469) [(PDF)](http://arxiv.org/pdf/2102.04469.pdf)

- #csst
- We show that adding NIRCam images through a strategically chosen medium-band filter to common wide-band filters sets adopted by ERS and GTO programs delivers tighter constraints on these galactic properties.
- We find that adding $>4.1 \mu$m medium filters at comparable depth to the broad-band filters can significantly improve photo-$z$s and yield close to order-of-magnitude improvements in the determination of quantities such as stellar ages, metallicities, SF-related quantities and emission line fluxes at $z\sim8$.

##### [CMB/kSZ and Compton-$y$ Maps from 2500 square degrees of SPT-SZ and Planck Survey Data](http://arxiv.org/abs/2102.05033) [(PDF)](http://arxiv.org/pdf/2102.05033.pdf)

- #cluster/sze
- We present component-separated maps of the primary cosmic microwave background/kinematic Sunyaev-Zel'dovich (SZ) amplitude and the thermal SZ Compton-$y$parameter, created using data from the South Pole Telescope (SPT) and the Planck satellite.
- In this work we detail the construction of these maps using linear combination techniques, including our method for limiting the correlation of our lowest-noise Compton-$y$map products with the cosmic infrared background.
- Recognizing the potential utility of these data products for a wide range of astrophysical and cosmological analyses, including studies of the gas properties of galaxies, groups, and clusters, we make these products publicly available at http://pole.uchicago.edu/public/data/sptsz_ymap and on the NASA/LAMBDA website.

##### [PyAutoFit: A Classy Probabilistic Programming Language for Model Composition and Fitting](http://arxiv.org/abs/2102.04472) [(PDF)](http://arxiv.org/pdf/2102.04472.pdf)

- #statistics #inference 
- PyAutoFit is a Python-based PPL which interfaces with all aspects of the modeling (e.g., the model, data, fitting procedure, visualization, results) and therefore provides complete management of every aspect of modeling.
- [`PyAutoFit`](https://pyautofit.readthedocs.io/en/latest/)

#### Others

##### [The GN-z11-Flash Event Can be a Satellite Glint](http://arxiv.org/abs/2102.04466) [(PDF)](http://arxiv.org/pdf/2102.04466.pdf)

- Here we show that reflection of sunlight from a high-orbit satellite or a piece of space debris is a valid and reasonable explanation.
	- At higher declinations the rate is 5--50 times lower, but still significant: about four orders of magnitudes higher than the rate estimated for GRBs.

##### [The first measurement of the quasar lifetime distribution](http://arxiv.org/abs/2102.04477) [(PDF)](http://arxiv.org/pdf/2102.04477.pdf)

- The extent of the He II Ly$\alpha$ proximity zones in the absorption spectra of $z_{\rm qso}\sim3-4$ quasars constitutes a unique probe, providing sensitivity to lifetimes up to $\sim 30$Myr.
	- Our recent analysis of $22$archival He II proximity zone spectra reveals a surprisingly broad range of emission timescales, indicating that some quasars turned on $\lesssim 1$Myr ago, whereas others have been shining for $\gtrsim 30$Myr. 但推断QLD有难度
- We combine a semi-numerical He II reionization model, hydrodynamical simulations post-processed with ionizing radiative transfer, and a novel statistical framework to infer the QLD from an ensemble of proximity zone measurements.
	- Our results allow us to estimate the probability of detecting young quasars with $t_{\rm Q}\leq0.1$Myr from their proximity zone sizes yielding $p\left(\leq 0.1~{\rm Myr}\right)=0.19^{+0.11}_{-0.09}$, which is broadly consistent with recent determination at $z\sim 6$.

##### [A homogeneous comparison between the chemical composition of the Large Magellanic Cloud and the Sagittarius dwarf galaxy](http://arxiv.org/abs/2102.04516) [(PDF)](http://arxiv.org/pdf/2102.04516.pdf)

- The LMC and Sgr stars, in the considered metallicity range ([Fe/H]>-1.1 dex), show very similar abundance ratios for almost all the elements, with differences only in the heavy s-process elements Ba, La and Nd, suggesting a different contribution by asymptotic giant branch stars.
- On the other hand, the two galaxies have chemical patterns clearly different from those measured in the Galactic stars, especially for the elements produced by massive stars.

##### [How does the Polar Dust affect the Correlation between Dust Covering Factor and Eddington Ratio in Type 1 Quasars Selected from the Sloan Digital Sky Survey Data Release 16?](http://arxiv.org/abs/2102.04620) [(PDF)](http://arxiv.org/pdf/2102.04620.pdf)

- The CF is converted from a ratio of infrared (IR) luminosity contributed from AGN dust torus ($L_{\rm IR}^{\rm torus}$) and AGN bolometric luminosity ($L_{\rm bol}$), by assuming a non-linear relation between luminosity ratio and intrinsic CF.
	- As a result, anti-correlations for CF-$L_{\rm bol}$, CF-$M_{\rm BH}$, and CF-$\lambda_{\rm Edd}$are confirmed.
- We find that incorporating the AGN polar dust emission makes those anti-correlations stronger which are compared to those without considering it.

##### [A detailed study of X-ray cavities in the intracluster environment of the cool core cluster Abell~3017](http://arxiv.org/abs/2102.04650) [(PDF)](http://arxiv.org/pdf/2102.04650.pdf)

- #cluster/icm
- Using various image processing techniques, such as unsharp masking, 2-d fits using Beta models, contour binning and the use of surface brightness profiles, we show the existence of a pair of X-ray cavities, at a projected distance of ~$\sim$20\arcsec (70 kpc) and ~$\sim$16\arcsec (57 kpc), respectively from the core of Abell~3017.
	- We also detect an excess of X-ray emission, relatively hotter than that of the surroundings, towards the south, at $\sim$25\arcsec (88 kpc) from the core of the cluster, indicating the existence of an in-falling galaxy group.
	- The radio lobes are responsible for the observed X-ray cavities detected in this system.
- The lower values of mid-IR WISE color [W1-W2] and [W2-W3] imply that the central BCG of Abell~3017 is a star-forming galaxy.
- We detect, for the first time, a radio phoenix $\sim$150 kpc away from the radio core

##### [Hot graphite dust in the inner regime of NGC 4151](http://arxiv.org/abs/2102.04662) [(PDF)](http://arxiv.org/pdf/2102.04662.pdf)

- We model the near infrared SED of NGC 4151 with a 3-D radiative transfer SKIRT code, using which torus only (TO) and Ring And Torus (RAT) scenarios are studied.
	- All the models are able to explain the flat NIR SED of NGC 4151 with minor differences in the derived parameters.
	- The $R_{\rm in, t}$from the TO model does not agree with the NIR observations ($\sim 0.04$pc).
- Hence, the most likely scenario is that a hot graphite ring is located at a distance 0.04 pc from the centre, composed of a smooth distribution of dust followed by a dusty torus at 0.1 pc with ISM type of grains.

##### [Geometrical constraints on curvature from galaxy-lensing cross-correlations](http://arxiv.org/abs/2102.04802) [(PDF)](http://arxiv.org/pdf/2102.04802.pdf)

- Accurate constraints on curvature that are independent on assumptions for dark energy.
	- We study comprehensively the cross-correlations of galaxy with magnification, measured from type Ia supernovae's brightnesses ("$g\kappa^{\rm SN}$"), with shear ("$g\kappa^{\rm g}$"), and with CMB lensing ("$g\kappa^{\rm CMB}$"). 在LSST+CMB-S4时代很有用

##### [BALRoGO: Bayesian Astrometric Likelihood Recovery of Galactic Objects -- Global properties of over one hundred globular clusters with Gaia EDR3](http://arxiv.org/abs/2102.04841) [(PDF)](http://arxiv.org/pdf/2102.04841.pdf)

- We present BALRoGO: Bayesian Astrometric Likelihood Recovery of Galactic Objects, a public code to measure the centers, effective radii, and bulk proper motions of Milky Way globular clusters and Local Group dwarf spheroidals, whose data are mixed with Milky Way field stars.
- [`BALRoGo`](https://gitlab.com/eduardo-vitral/balrogo)

##### [HI constraints from the cross-correlation of eBOSS galaxies and Green Bank Telescope intensity maps](http://arxiv.org/abs/2102.04946) [(PDF)](http://arxiv.org/pdf/2102.04946.pdf)

- #intensity_mapping 
- We present the joint analysis of Neutral Hydrogen (HI) Intensity Mapping observations with three galaxy samples: the Luminous Red Galaxy (LRG) and Emission Line Galaxy (ELG) samples from the eBOSS survey, and the WiggleZ Dark Energy Survey sample.
	- The HI intensity maps are Green Bank Telescope observations of the redshifted 21cm emission on 100deg2 covering the redshift range $0.6<z<1.0$.
- The cross-correlations constrain the quantity $\Omega_{{HI}} b_{{HI}} r_{{HI},{opt}}$at an effective scale $k_{eff}$, where $\Omega_{HI}$is the HI density fraction, $b_{HI}$is the HI bias, and $r_{{HI},{opt}}$the galaxy-hydrogen correlation coefficient, which is dependent on the HI content of the optical galaxy sample.
- With little information on HI parameters beyond our local Universe, these are amongst the most precise constraints on neutral hydrogen density fluctuations in an underexplored redshift range.


### Feb 11 

#### Relevant / Important / Useful

##### [Evidence for gas-phase metal deficiency in massive protocluster galaxies at z~2.2](http://arxiv.org/abs/2102.05637) [(PDF)](http://arxiv.org/pdf/2102.05637.pdf)

- #cluster/galaxy
- We study the mass-metallicity relation for 19 members of a spectroscopically-confirmed protocluster in the COSMOS field at $z=2.2$(CC2.2)
- Protocluster galaxies with $10^{9.9} \rm M_\odot \leq M_* \leq 10^{10.9} \rm M_\odot$are metal deficient by $0.10 \pm 0.04$dex ($2.5\sigma$significance) compared to their coeval field galaxies.
	- 金属缺乏只在质量较大的星系中存在; 可能与原初气体吸积导致的dilution有关; 也可能和星系相互作用有关

#### Interesting / Keep in mind

##### [Weak-lensing Mass Reconstruction of Galaxy Clusters with Convolutional Neural Network](http://arxiv.org/abs/2102.05403) [(PDF)](http://arxiv.org/pdf/2102.05403.pdf)

- #weak_lensing #cluster/lensing
- We find that the mass reconstruction by our multi-layered CNN with the architecture of alternating convolution and trans-convolution filters significantly outperforms the traditional reconstruction methods.
- The CNN method provides better pixel-to-pixel correlations with the truth, restores more accurate positions of the mass peaks, and more efficiently suppresses artifacts near the field edges.
- In addition, the CNN mass reconstruction lifts the mass-sheet degeneracy when applied to sufficiently large fields.

##### [The MUSE Extremely Deep Field: the Cosmic Web in Emission at High Redshift](http://arxiv.org/abs/2102.05516) [(PDF)](http://arxiv.org/pdf/2102.05516.pdf)

- #galaxy/cgm #galaxy/igm
- We report the discovery of diffuse extended Ly-alpha emission from redshift 3.1 to 4.5, tracing cosmic web filaments on scales of 2.5-4 comoving Mpc.
- These structures have been observed in overdensities of Ly-alpha emitters in the MUSE Extremely Deep Field
- Remarkably, 70% of the total Ly-alpha luminosity from these filaments comes from beyond the circumgalactic medium of any identified Ly-alpha emitters.
- Fluorescent Ly-alpha emission powered by the cosmic UV background can only account for less than 34% of this emission at z$\approx$3 and for not more than 10% at higher redshift.
- We find that the bulk of this diffuse emission can be reproduced by the unresolved Ly-alpha emission of a large population of ultra low luminosity Ly-alpha emitters ($\mathrm{<10^{40} erg s^{-1}}$), provided that the faint end of the Ly-alpha luminosity function is steep ($\alpha \lessapprox -1.8$), it extends down to luminosities lower than $\mathrm{10^{38} - 10^{37} erg s^{-1}}$and the clustering of these Ly-alpha emitters is significant (filling factor $< 1/6$).
- If these Ly-alpha emitters are powered by star formation, then this implies their luminosity function needs to extend down to star formation rates $\mathrm{< 10^{-4} M_\odot yr^{-1}}$.

#### Others

##### [Revisiting the complex kinematics of ionized gas at the central region of NGC 1068: evidence of an additional active galactic nucleus?](http://arxiv.org/abs/2102.05043) [(PDF)](http://arxiv.org/pdf/2102.05043.pdf)

- NGC1068的外流不是简单的 biconical outflows: finding a morphologically symmetric pair of approaching and receding gas blobs in the northeast region.
	- The midpoint of the two blobs is located at a distance of 180 pc from the nucleus in the projected plane.
- The ionized gas at the midpoint shows zero velocity and high velocity dispersion, which are characteristics of an outflow-launching position, as the two sides of a bicone, i.e, approaching and receding outflows are superposed on the line of sight, leading to no velocity shift but high velocity dispersion.
- While there are other possibilities, i.e, X-ray binary or supernova shock, the results from optical spectropolarimetry analysis are consistent with the presence of an additional AGN, which likely originates from a minor merger.

##### [Detecting neutrino mass by combining matter clustering, halos, and voids](http://arxiv.org/abs/2102.05049) [(PDF)](http://arxiv.org/pdf/2102.05049.pdf)

- #cosmology #ssst/cos
- 联合 non-linear matter power spectrum, the halo mass function, and the void size function, 可以更好的限制中微子质量和其他宇宙学参数
- The multiplicative improvement of the constraints on the cosmological parameters obtained by combining all three probes compared to using the power spectrum alone are: 137, 5, 8, 20, 10, and 43, for $\Omega_m$, $\Omega_b$, $h$, $n_s$, $\sigma_8$, and $M_\nu$, respectively.

- Furthermore, the improved constraints on other cosmological parameters, notably $\Omega_m$, may also be competitive with CMB-based measurements.

##### [A Machine Learning Approach to Measuring the Quenched Fraction of Low-Mass Satellites Beyond the Local Group](http://arxiv.org/abs/2102.05050) [(PDF)](http://arxiv.org/pdf/2102.05050.pdf)

- #galaxy/quenching #galaxy/environment 
- Observations suggest that satellite quenching plays a major role in the build-up of passive, low-mass galaxies at late cosmic times.
- Using a statistically-driven approach, we are able to push beyond the limits of existing spectroscopic data sets, measuring the satellite quenched fraction down to satellite stellar masses of ${\sim}10^7~{\rm M}_{\odot}$in group environments (${M}_{\rm{halo}} = 10^{13-14}~h^{-1}~{\rm M}_{\odot}$).
- Pushing to lower masses, we find that the fraction of passive satellites increases, potentially signaling a change in the dominant quenching mechanism at ${M}_{\star} \sim 10^{9}~{\rm M}_{\odot}$.

##### [Forming massive seed black holes in high-redshift quasar host progenitors](http://arxiv.org/abs/2102.05051) [(PDF)](http://arxiv.org/pdf/2102.05051.pdf)

- We investigate, by combining dark-matter only N-body simulations with a semi-analytic framework, whether the conditions for the formation of massive seed BHs from synchronised atomic-cooling halo pairs and/or dynamically-heated mini-haloes are fulfilled in the overdense regions where the progenitors of a typical high-redshift quasar host form and evolve.
- 关键条件 i.e strong halo clustering and high star formation rates, are crucial to produce a non-negligible number of massive seed BH host candidates: we find $\approx1400$dynamically heated metal-free mini-haloes, including one of these which evolves to a synchronised pair and ends up in the massive quasar-host halo by $z=6$.
- Our results further suggest that multiple massive seed BHs may form in or near the quasar host's progenitors, potentially merging at lower redshifts and yielding gravitational wave events.

##### [Synergies between low- and intermediate-redshift galaxy populations revealed with unsupervised machine learning](http://arxiv.org/abs/2102.05056) [(PDF)](http://arxiv.org/pdf/2102.05056.pdf)

- 用成团性的方法研究星系在color-bimodility上的演化
	- One from the second edition of the GALEX-SDSS-WISE Legacy Catalogue (GSWLC-2; $z \sim 0.06$), and the other from the VIMOS Public Extragalactic Redshift Survey (VIPERS; $z \sim 0.65$).
- Both samples are similarly partitioned into seven clusters, breaking down into four of mostly star-forming galaxies (including the vast majority of green valley galaxies) and three of mostly passive galaxies.
- The samples are closely related, with star-forming/green-valley clusters at both epochs forming morphological sequences, capturing the gradual internally-driven growth of galaxy bulges.
- At high stellar masses, this growth is linked with quenching.
- Fisher Expectation-Maximisation algorithm, which estimates the parameters of the Discriminative Latent Mixture model. Bouveyron & Brunet(2012)
	- The Discriminative Latent Mixture (DLM) model is a clustering approach that incorporates dimensionality reduction on the fly to determine a frugal fit to the structure of an input sample

##### [It's Cloud's Illusions I Recall: Mixing Drives the Acceleration of Clouds from Ram Pressure Stripped Galaxies](http://arxiv.org/abs/2102.05061) [(PDF)](http://arxiv.org/pdf/2102.05061.pdf)

- This interaction is generally thought of as a contact force per area, however we point out that these gases must interact in a hydrodynamic fashion, and argue that this will lead to mixing of the galactic gas with the ICM wind.
	- We develop an analytic framework for how mixing is related to the acceleration of stripped gas from a satellite galaxy.
- Focusing on the dense clumps in the stripped tails, we find that they are nearly uniformly mixed with the ICM, indicating that all gas in the tail mixes with the surroundings, and dense clumps are not separate entities to be modeled differently than diffuse gas.
- We find that while mixing drives acceleration of stripped gas, the density and velocity of the surrounding wind will determine whether the mixing results in the heating of stripped gas into the ICM, or the cooling of the ICM into dense clouds.

##### [Pair Lines of Sight Observations of Multiphase Gas Bearing O VI in a Galaxy Environment](http://arxiv.org/abs/2102.05065) [(PDF)](http://arxiv.org/pdf/2102.05065.pdf)

- Using $HST$/COS observations of the twin quasar lines of sight Q$0107-025$A $\&$Q$0107-025$B, we report on the physical properties, chemical abundances and transverse sizes of gas in a multiple galaxy environment at $z = 0.399$across a transverse separation of $520$kpc.
- The absorber towards Q$0107-025$B has $\log N(H I)/cm^{-2} \approx 16.8$(partial Lyman limit) while the absorber towards the other sightline has $N(H I) \approx 2$dex lower.
- The O VI along both sightlines have comparable column densities and broad $b$-values, whereas the low ionization lines are considerably narrower.
- The low ionization gas is inconsistent with the O VI when modelled assuming photoionization in a single phase.
- Along both the lines-of-sight, O VI and coinciding broad H I are best explained through collisional ionization in a cooling plasma with solar metallicity.
- Ionization models infer $1/10$-th solar metallicity for the pLLS and solar metallicity for the lower column density absorber along the other sightline.
- Within $\pm~250~km~s^{-1}$and $2$Mpc of projected distance from the sightlines 12 galaxies are identified, of which 3 are within $300$kpc.
- One of them is a dwarf galaxy while the other two are intermediate mass systems at impact parameters of $\rho \sim (1-4)R_{vir}$.
- The O VI along both lines-of-sight could be either tracing narrow transition temperature zones at the interface of low ionization gas and the hot halo of nearest galaxy, or a more spread-out warm gas bound to the circumgalactic halo/intragroup medium.
- This latter scenario leads to a warm gas mass limit of $M \gtrsim 4.5 \times 10^{9}$M$_\odot$.

##### [The trouble beyond $H_0$ and the new cosmic triangles](http://arxiv.org/abs/2102.05066) [(PDF)](http://arxiv.org/pdf/2102.05066.pdf)

- #cosmology/h0 #hubble_tension  
- 不能简单的希望一个新模型只改变H0，对其他参数也有影响：比如宇宙年龄
- The value of $H_0$inferred from the CMB and galaxy surveys is related to the sound horizon at CMB decoupling (or at radiation drag), but it is also related to the matter density and to $t_{\rm U}$.
- We propose the use of ternary plots to simultaneously visualize independent constraints on key quantities related to $H_0$like $t_{\rm U}$, the sound horizon at radiation drag, and the matter density parameter.

##### [Confirming ALMA Calibration using Planck and ACT Observations](http://arxiv.org/abs/2102.05079) [(PDF)](http://arxiv.org/pdf/2102.05079.pdf)

- We find the ALMA flux density scale (based on observations of Uranus) is consistent with Planck; for instance ALMA flux densities in Band 3 ($\sim$100 GHz) average $0.99 \pm 0.02$times those measured by Planck.
- We also test the absolute calibration of both ACT and the South Pole Telescope (SPT), again with reference to Planck, as well as the internal consistency of Planck, ACT and SPT measurements of compact sources.

##### [Measuring anisotropic stress with relativistic effects](http://arxiv.org/abs/2102.05086) [(PDF)](http://arxiv.org/pdf/2102.05086.pdf)

- #cosmology
- Whereas large classes of dark energy models preserve this equality, theories of modified gravity generally create a difference between the potentials, known as anisotropic stress.
- 提出一个新的更直接的方法 Our method uses relativistic effects in the galaxy number counts to provide a direct measurement of the time component of the metric.

##### [A Deep Learning Approach for Characterizing Major Galaxy Mergers](http://arxiv.org/abs/2102.05182) [(PDF)](http://arxiv.org/pdf/2102.05182.pdf)

- #machine_learning 
- We demonstrate a CNN-based regression model that is able to predict, for the first time, using a single image, the merger stage relative to the first perigee passage with a median error of 38.3 million years (Myrs) over a period of 400 Myrs.
- We show that our model provides reasonable estimates on real observations, approximately matching prior estimates provided by detailed dynamical modeling.

##### [Physical and kinematic conditions of the local merging galaxy NGC 1487](http://arxiv.org/abs/2102.05244) [(PDF)](http://arxiv.org/pdf/2102.05244.pdf)

- MUSE观测：We measured flat and sometimes inverted oxygen abundance gradients in the subsystems composing NGC 1487, explained by metal mixing processes common in merging galaxies.
- The kinematic map revealed a rotating pattern in the gas in the northern tail of the system, suggesting that the galaxy may be in the process of rebuilding a disc.
- The gas located in the central region has larger velocity dispersion ($\sigma\approx 50$km s$^{-1}$) than the remaining regions, indicating kinematic heating, possibly owing to the ongoing interaction.
- Based on all our measurements and findings, and specially on the mass estimates, metallicity gradients and velocity fields of the system, we propose that NGC 1487 is the result of an ongoing merger event involving smallish dwarf galaxies within a group, in a pre-merger phase, resulting in a relic with mass and physical parameters similar to a dwarf galaxy.

##### [Narrowing the mass range of Fuzzy Dark Matter with Ultra-faint Dwarfs](http://arxiv.org/abs/2102.05300) [(PDF)](http://arxiv.org/pdf/2102.05300.pdf)

- We use a sample of 18 UFDs to place the strongest constraints to date on the mass of the FDM particle, updating on previous bounds using a subset of the sample used here.
	- We find that most of the sample UFDs prefer a FDM particle mass heavier than $10^{-21}\mathrm{eV}$.
	- In particular, Segue 1 provides the strongest constraint, with $m_\psi=1.1^{+8.3}_{-0.7}\times10^{-19}\mathrm{eV}$.
- The constraints found here are the first that are compatible with various other independent cosmological and astrophysical bounds found in the literature, in particular with the latest bounds using the Lyman-$\alpha$forest.
	- UFD给出的限制和更亮的dwarf给出的不一样

##### [Evaluation of New Submillimeter VLBI Sites for the Event Horizon Telescope](http://arxiv.org/abs/2102.05482) [(PDF)](http://arxiv.org/pdf/2102.05482.pdf)

- Out of more than forty candidate new locations analyzed, approximately half have 230 GHz opacity comparable to the existing EHT sites, and at least seventeen of the candidate sites would be comparably good for 345 GHz observing.
- A group of new sites with favorable transmittance and geographic placement leads to greatly enhanced imaging and science on horizon scales.

##### [A self-supervised, physics-aware, Bayesian neural network architecture for modelling galaxy emission-line kinematics](http://arxiv.org/abs/2102.05520) [(PDF)](http://arxiv.org/pdf/2102.05520.pdf)

- For SKA: we explore the use of a self-supervised, physics aware neural network capable of Bayesian kinematic modelling of galaxies
	- The model is able to recover rotation curves, inclinations and disc scale lengths for both CO and HI data which match well with those found in the literature.
- This work represents the first steps in applying such models for kinematic fitting and we propose that variants of our model would seem especially suitable for enabling emission-line science from upcoming surveys with e.g. the SKA, allowing fast exploitation of these large datasets.
- [2dbat](https://github.com/seheonoh/2dbat)


### Feb 12 

#### Relevant / Important / Useful

##### [Dynamical properties of z $\sim 4.5$ dusty star-forming galaxies and their connection with local early type galaxies](http://arxiv.org/abs/2102.05671) [(PDF)](http://arxiv.org/pdf/2102.05671.pdf)

- #galaxy/ism #galaxy/structure High-z bulge
- 一批被透镜放大的高红移DSFG的ALMA观测: We found that all galaxies in the sample are dynamically cold, with rotation-to-random motion ratios, $V/\sigma$, between 7 to 15.
- SFR v.s. 气体速度弥散度: 恒星feedback足以维持气体湍动，不需要其他机制
- In particular, we found that five out of six galaxies of the sample show the dynamical signature of a bulge, indicating that the spheroidal component is already in place at $z \sim 4.5$.

#### Interesting / Keep in Mind

##### [A massive stellar bulge in a regularly rotating galaxy 1.2 billion years after the Big Bang](http://arxiv.org/abs/2102.05957) [(PDF)](http://arxiv.org/pdf/2102.05957.pdf)

- #galaxy/structure 
- Here we present submillimeter observations (with spatial resolution of 700 parsecs) of ALESS 073.1, a starburst galaxy at redshift z~5, when the Universe was 1.2 billion years old.
	- This galaxy's cold gas forms a regularly rotating disk with negligible noncircular motions.
	- The galaxy rotation curve requires the presence of a central bulge in addition to a star-forming disk.
- We conclude that massive bulges and regularly rotating disks can form more rapidly in the early Universe than predicted by models of galaxy formation.

##### [No Evidence for Orbital Clustering in the Extreme Trans-Neptunian Objects](https://arxiv.org/abs/2102.05601)

- We consider 14 ETNOs discovered by the Dark Energy Survey, the Outer Solar System Origins Survey, and the survey of Sheppard and Trujillo. 
- Using each survey's published pointing history, depth, and TNO tracking selections, we calculate the joint probability that these objects are consistent with an underlying parent population with uniform distributions in ϖ and Ω. 
- We find that the mean scaled longitude of perihelion and orbital poles of the detected ETNOs are consistent with a uniform population at a level between 17% and 94%, and thus conclude that this sample provides no evidence for angular clustering.
- [`spacerocks` - A suite of tools for performing observational and theoretical tasks in solar system dynamics.](https://github.com/kjnapier/spacerocks)

#### Others

##### [The post-Herschel view of intrinsic AGN emission: constructing templates for galaxy and AGN emission at IR wavelengths](http://arxiv.org/abs/2102.05663) [(PDF)](http://arxiv.org/pdf/2102.05663.pdf)

- We present a new set of AGN and galaxy infrared templates, and introduce the spectral energy distribution fitting code IRAGNSEP.
- To build these, we used a sample of 100 local ($z$< 0.3), low-to-high luminosity AGNs (i.e $L_{\rm bol}~\sim~10^{42--46}~\rm erg~s^{-1}$), selected from the 105-month Swift - BAT X-ray survey, which have archival Spitzer - IRS spectra and Herschel photometry.
- We further demonstrate that we can reduce the diversity in the intrinsic shapes of AGN spectral energy distributions down to a set of three AGN templates, of which two represent AGN continuum, and one represents silicate emission.
- AGN在远红外波段的贡献没有之前认为的多；需要两个templates可能与central obscuration有关

##### [The 450 days X-ray monitoring of the changing-look AGN 1ES 1927+654](http://arxiv.org/abs/2102.05666) [(PDF)](http://arxiv.org/pdf/2102.05666.pdf)

- 1ES 1927+654 is a nearby active galactic nucleus (AGN) which underwent a changing-look event in early 2018, 出现了新的宽线区
	- In the X-rays, 1ES 1927+654 shows a behaviour unlike any previously known AGN. 有快速光变，X-ray和UV光变没有相关
	- After the outburst the power-law component almost completely disappeared, and the source showed an extremely soft continuum dominated by a blackbody component.
- The spectra show evidence of ionized outflows, and of a prominent feature at $\sim 1$keV, which can be reproduced by a broad emission line.

##### [The Kinematics of z ~ 6 Quasar Host Galaxies](http://arxiv.org/abs/2102.05679) [(PDF)](http://arxiv.org/pdf/2102.05679.pdf)

- We explore the kinematics of 27 z~6 quasar host galaxies observed in [CII]-158 micron ([CII]) emission with the Atacama Large Millimeter/sub-millimeter Array at a resolution of ~0.25''.
	- We find that nine of the galaxies show disturbed [CII] emission, either due to a close companion galaxy or recent merger.
	- Ten galaxies have smooth velocity gradients consistent with the emission arising from a gaseous disk.
	- The remaining eight quasar host galaxies show no velocity gradient, suggesting that the gas in these systems is dispersion-dominated.
	- All galaxies show high velocity dispersions with a mean of 129+-10 km/s.
- Comparison between the dynamical mass and the mass of the supermassive black hole reveals that the sample falls above the locally derived bulge mass--black hole mass relation at 2.4sigma significance.
- Using several different estimators for the molecular mass, we estimate a gas mass fraction of >10%, indicating gas makes up a large fraction of the baryonic mass of z~6 quasar host galaxies.

##### [The Physics of Galactic Winds Driven by Cosmic Rays I: Diffusion](http://arxiv.org/abs/2102.05696) [(PDF)](http://arxiv.org/pdf/2102.05696.pdf)

- We elucidate the physics of CR-driven galactic winds for CR transport dominated by diffusion.
	- We use analytic estimates validated by time-dependent spherically-symmetric simulations to derive expressions for the mass-loss rate, momentum flux, and speed of CR-driven galactic winds, suitable for cosmological-scale or semi-analytic models of galaxy formation.
- For CR diffusion coefficients $\kappa \gtrsim r_0 c_i$where $r_0$is the base radius of the wind and $c_i$is the isothermal gas sound speed, the asymptotic wind energy flux is comparable to that supplied to CRs, and the outflow rapidly accelerates to supersonic speeds.
- By contrast, for $\kappa \lesssim r_0 c_i$, CR-driven winds accelerate more slowly and lose most of their energy to gravity, a CR analogue of photon-tired stellar winds.
- Given CR diffusion coefficients estimated using Fermi gamma-ray observations of pion decay, we predict mass-loss rates in CR-driven galactic winds of order the star formation rate for dwarf and disc galaxies.
- The dwarf galaxy mass-loss rates are small compared to the mass-loadings needed to reconcile the stellar and dark matter halo mass functions.
- For nuclear starbursts (e.g., M82, Arp 220), CR diffusion and pion losses suppress the CR pressure in the galaxy and the strength of CR-driven winds.

##### [A systematic search for lensed X-ray sources in the CLASH fields](http://arxiv.org/abs/2102.05788) [(PDF)](http://arxiv.org/pdf/2102.05788.pdf)

- We search for unresolved X-ray emission from lensed sources in the FOV of 11 CLASH clusters with Chandra data.
	- We detect X-ray emission only in 9 out of 849 lensed/background optical sources.
	- The stacked emission of the sources without detection does not reveal any signal in any band.
- Based on the untargeted detection, we find 66 additional X-ray sources that are consistent with being lensed sources.
	- 可以利用透镜探测高红移AGN；但需要更多的cluster fields才能和CDFS比较

##### [FIRST J153350.8+272729: the radio afterglow of a decades-old tidal disruption event](http://arxiv.org/abs/2102.05795) [(PDF)](http://arxiv.org/pdf/2102.05795.pdf)

- We present the discovery of the fading radio transient FIRST J153350.8+272729.
- The source had a maximum observed 5-GHz radio luminosity of $8\times10^{39}$erg s$^{-1}$in 1986, but by 2019 had faded by a factor of nearly 400.
- We show that a tidal disruption event (TDE) is the preferred scenario for FIRST J153350.8+272729, although it could plausibly be interpreted as the afterglow of a long-duration gamma-ray burst. 第二个在射电波段发现的TDE

##### [Deep learning model for multiwavelength emission from low-luminosity active galactic nuclei](http://arxiv.org/abs/2102.05809) [(PDF)](http://arxiv.org/pdf/2102.05809.pdf)

- In this work, we used machine learning (ML) methods to generate model SEDs and fit sparse observations of LLAGNs.
	- The ML method performs the fit $4 \times 10^5$times faster than previous semianalytic models.
	- As a proof-of-concept, we used the ML model to reproduce the SEDs of the LLAGNs M87, NGC 315 and NGC 4261.

##### [Spectropolarimetry of low redshift Quasars: origin of the polarization and implications for black hole mass estimates](http://arxiv.org/abs/2102.05935) [(PDF)](http://arxiv.org/pdf/2102.05935.pdf)

- 1. The broad line region (BLR) and continuum polarization are both produced by a single scattering medium.
- 2. The scattering medium is equatorial, and at right angle to the system axis.
- 3. The scattering medium is located at or just outside the BLR.
- The observed line width is found to be affected by inclination, which can lead to an underestimate of the black hole mass by a factor of $\sim 5$for a close-to face-on view.
	- The line width measured in the polarized flux overcomes the inclination bias, and provides a close-to equatorial view of the BLR in all AGN, which allows to reduce the inclination bias in the BLR based black hole mass estimates.


### Feb 15 

#### Relevant / Important / Useful

##### [The Lack of Non-Thermal Motions in Galaxy Cluster Cores](http://arxiv.org/abs/2102.06324) [(PDF)](http://arxiv.org/pdf/2102.06324.pdf)

- #cluster/icm #cluster/halo 
- The non-thermal pressure fraction (Pnt/Ptot) obtained from a three-dimensional triaxial analysis of 16 galaxy clusters in the CLASH sample
	- 星系团中心250kpc以内，非热压力的比值接近于0; indicating that heating from active galactic nuclei and other relevant processes does not produce significant deviations from hydrostatic equilibrium (HSE). HSE模型给出的星系团中心区域的质量是很可靠的
	- 在250kpc以外的平均比例在20%左右: as expected from simulations, due to newly accreted material thermalizing via a series of shocks.
- Also in agreement with simulations, we find significant cluster-to-cluster variation in Pnt/Ptot and little difference in the ensemble average Pnt/Ptot based on dynamical state.

##### [Accelerated galaxy growth and environmental quenching in a protocluster at z=3.24](http://arxiv.org/abs/2102.06499) [(PDF)](http://arxiv.org/pdf/2102.06499.pdf)

- #cluster/galaxy #galaxy/environment 
- D4UD01 @ z = 3.24: 450 Ks-selected galaxies with photo-z at 3.0 < z < 3.4, among which ~ 12% are classified as quiescent galaxies.
	- The quiescent galaxies are largely concentrated in the overdense protocluster region with a higher quiescent fraction, showing a sign of environmental quenching.
- Galaxies in the protocluster are forming faster than the field counterparts as seen in the stellar mass function, suggesting early and accelerated mass assembly in the overdense regions.
- Our work shed light on how the formation of massive galaxies is affected in the dense region of a protocluster when the Universe was only 2 Gyr old.

##### [SDSS-IV MaNGA: Radial Gradients in Stellar Population Properties of Early-Type and Late-Type Galaxies](http://arxiv.org/abs/2102.06703) [(PDF)](http://arxiv.org/pdf/2102.06703.pdf)

- #galaxy/spop #stellar_population #survey/manga
- We study a large sample of 1900 galaxies spanning $8.6 - 11.3 \log M/M_{\odot}$in stellar mass, through key absorption features in stacked spectra from the SDSS-IV/MaNGA survey.
- We find flat age and negative metallicity gradients for ETGs and negative age and negative metallicity gradients for LTGs.
- Age gradients in LTGs steepen with increasing galaxy mass, from $-0.05\pm0.11~\log$Gyr/R$_e$for the lowest mass galaxies to $-0.82\pm0.08~\log$Gyr/R$_e$for the highest mass ones. This strong gradient-mass relation has a slope of $-0.70\pm0.18$.
- Comparing local age and metallicity gradients with the velocity dispersion $\sigma$within galaxies against the global relation with $\sigma$shows that internal processes regulate metallicity in ETGs but not age, and vice versa for LTGs.
- Both galaxy types display flat [C/Fe] and [Mg/Fe], and negative [Na/Fe] gradients, whereas only LTGs display gradients in [Ca/Fe] and [Ti/Fe].
- ETGs have increasingly steep [Na/Fe] gradients with local $\sigma$reaching $6.50\pm0.78$dex/$\log$km/s for the highest masses.
	- [Na/Fe] ratios are correlated with metallicity for both galaxy types across the entire mass range in our sample, providing support for metallicity dependent supernova yields.
	
##### [Pre-processing of Galaxies in the Early Stages of Cluster Formation in Abell 1882 at $z$=0.139](http://arxiv.org/abs/2102.06612) [(PDF)](http://arxiv.org/pdf/2102.06612.pdf)

- #galaxy/environment #cluster/galaxy 
- We identify three prominent filaments along which galaxies seem to be entering the Supergroup (mostly in E-W directions).
	- Thus, galaxy evolution responds to the external environment as strongly in these unrelaxed systems as we find in rich and relaxed clusters.
- From these data, local density remains the primary factor with a secondary role for distance from the inferred center of the entire structure's potential well.
- We see changes in lower-mass galaxies (M $<$$10^{10.5}$$M_{sun}$) at four times the virial radius of major substructures, while the more massive $NUV$Green Valley galaxies show low levels of star formation within two virial radii.
	- Suppression of star formation ("quenching") occurs in the infall regions of these structures even before galaxies enter the denser group environment.

#### Interesting / Keep in Mind

##### [A Machine Learning Approach to Integral Field Unit Spectroscopy Observations: II. HII Region LineRatios](http://arxiv.org/abs/2102.06230) [(PDF)](http://arxiv.org/pdf/2102.06230.pdf)

- #machine_learning 
- In the first paper of this series (Rhea et al 2020), we demonstrated that neural networks can robustly and efficiently estimate kinematic parameters for optical emission-line spectra taken by SITELLE at the Canada-France-Hawaii Telescope.
- This paper expands upon this notion by developing an artificial neural network to estimate the line ratios of strong emission-lines present in the SN1, SN2, and SN3 filters of SITELLE. 用CNN模型估计发射线比值
- [Mexican Million Model database](https://sites.google.com/site/mexicanmillionmodels/home?authuser=0)
- Although standard fitting routines do consistently well depending on the signal-to-noise ratio of the spectral features, the neural network can also excel at predictions in the low signal-to-noise regime within the controlled environment of the training set as well as on observed data when the source spectral properties are well constrained by models.
- [`Pamplemousse`](https://github.com/sitelle-signals/Pamplemousse)

##### [The Stars of the HETDEX Survey. I. Radial Velocities and Metal-Poor Stars from Low-Resolution Stellar Spectra](http://arxiv.org/abs/2102.06224) [(PDF)](http://arxiv.org/pdf/2102.06224.pdf)

- #ssst/mw
- The new catalog contains 120,571 low-resolution spectra for 98,736 unique stars between $10 < G < 22$spread across the HETDEX footprint at relatively high ($b\sim60^\circ$) Galactic latitudes.
- Since these RVs are for faint ($G\geq16$) stars, they will be complementary to Gaia.
- Using t-Distributed Stochastic Neighbor Embedding (t-SNE), we also demonstrate that the HETDEX spectra can be used to determine a star's T${\rm{eff}}$, and log g and its [Fe/H].

##### [Core Mass Estimates in Strong Lensing Galaxy Clusters Using a Single-Halo Lens Model](http://arxiv.org/abs/2102.06351) [(PDF)](http://arxiv.org/pdf/2102.06351.pdf)

- #cluster/halo #strong_lensing 
- Here, we evaluate the use of a Single-Halo model (SHM) as an efficient method to estimate the strong lensing cluster core mass, testing it with ray-traced images from the 'Outer Rim' simulation.
- We find that the projected core mass estimated with this method, M$_{\rm SHM}$, has a scatter of $8.52\%$and a bias of $0.90\%$compared to the "true" mass within the same aperture.
- We find that the SHM success depends on the lensing geometry, with single giant arc configurations accounting for most of the failed cases due to their limiting constraining power.
- Finally, we find that when the source redshift is unknown, the model-predicted redshifts are overestimated, and the M$_{\rm SHM}$is underestimated by a few percent, highlighting the importance of securing spectroscopic redshifts of background sources.

#### Others

##### [Probing within the Bondi radius of the ultramassive black hole in NGC 1600](http://arxiv.org/abs/2102.06216) [(PDF)](http://arxiv.org/pdf/2102.06216.pdf)

- #smbh #galaxy/etg
- The exceptionally large mass of the black hole coupled with its low redshift makes it one of only a handful of black holes for which spatially resolved temperature and density profiles can be obtained within the Bondi radius with the high spatial resolution of Chandra.
- Within a $\sim\!3$kpc radius, we find two temperature components with statistical significance.
	- Both the single temperature and two temperature models show only a very slight rise in temperature towards the centre, and are consistent with being flat.
- The density profile follows a relatively shallow $\rho\propto~r^{-[0.61\pm0.13]}$relationship within the Bondi radius, which suggests that the true accretion rate on to the black hole may be lower than the classical Bondi accretion rate.

##### [Unravelling cosmic velocity flows: a Helmholtz-Hodge decomposition algorithm for cosmological simulations](http://arxiv.org/abs/2102.06217) [(PDF)](http://arxiv.org/pdf/2102.06217.pdf)

- In the context of intra-cluster medium turbulence, it is essential to be able to split the turbulent velocity field in a compressive and a solenoidal component.
- We describe and implement a new method for this aim, i.e, performing a Helmholtz-Hodge decomposition, in multi-grid, multi-resolution descriptions, focusing on (but not being restricted to) the outputs of AMR cosmological simulations.

##### [3-D gas-phase elemental abundances across the formation histories of Milky Way-mass galaxies in the FIRE simulations: initial conditions for chemical tagging](http://arxiv.org/abs/2102.06220) [(PDF)](http://arxiv.org/pdf/2102.06220.pdf)

- FIRE-2 simulations to examine 3-D variations of gas-phase elemental abundances of [O/H], [Fe/H], and [N/H] in 11 Milky Way (MW) and M31-mass galaxies across their formation histories at $z \leq 1.5$($t_{\rm lookback} \leq 9.4$Gyr), motivated by characterizing the initial conditions of stars for chemical tagging.
- Over time negative radial gradients of abundance become steeper while azimuthal variations become weaker (more homogeneous).
- Furthermore, elemental abundances are measurably homogeneous (to $\lesssim 0.05$dex) across a radial range of $\Delta R \approx 3.5$kpc at $z \gtrsim 1$and $\Delta R \approx 1.7$kpc at $z = 0$.
- We also measure full distributions of elemental abundances, finding typically negatively skewed normal distributions at $z \gtrsim 1$that evolve to typically Gaussian distributions by $z = 0$.

##### [Super-resolving Herschel imaging: a proof of concept using Deep Neural Networks](http://arxiv.org/abs/2102.06222) [(PDF)](http://arxiv.org/pdf/2102.06222.pdf)

- #machine_learning 
- Wide-field sub-millimetre surveys have driven many major advances in galaxy evolution in the past decade, but without extensive follow-up observations the coarse angular resolution of these surveys limits the science exploitation.
- Here we present an autoencoder with a novel loss function to overcome this problem in the sub-millimeter wavelength range.
- This approach is successfully demonstrated on Herschel SPIRE COSMOS data, with the super-resolving target being the JCMT SCUBA-2 observations of the same field.

##### [The EDGE-CALIFA survey: The local and global relations between $\Sigma_\ast$ , $\Sigma_{SFR}$ and $\Sigma_{mol}$ that regulate star-formation](http://arxiv.org/abs/2102.06226) [(PDF)](http://arxiv.org/pdf/2102.06226.pdf)

- Characterization of the relations between star-formation rate, stellar mass and molecular gas mass surface densities at different spatial scales across galaxies (from galaxy wide to kpc-scales).
	- Those relations are the same at the different explored scales, sharing the same distributions for the explored data
- We propose that these relations are the projection of a single relation between the three properties that follows a distribution well described by a line in the three-dimension parameter space.

##### [Black Hole Weather Forecasting with Deep Learning: A Pilot Study](http://arxiv.org/abs/2102.06242) [(PDF)](http://arxiv.org/pdf/2102.06242.pdf)

- #machine_learning 
- In this pilot study, we investigate the use of a deep learning (DL) model to temporally evolve the dynamics of gas accreting onto a black hole in the form of a radiatively inefficient accretion flow (RIAF).
- We have trained a machine to forecast such a spatiotemporally chaotic system -- i.e black hole weather forecasting -- using a convolutional neural network (CNN) and a training dataset which consists of numerical solutions of the hydrodynamical equations, for a range of initial conditions.

##### [The Physical Drivers of the Luminosity-Weighted Dust Temperatures in High-Redshift Galaxies](http://arxiv.org/abs/2102.06250) [(PDF)](http://arxiv.org/pdf/2102.06250.pdf)

- It has been claimed in the literature that a galaxy's dust temperature -- observed as the wavelength where the dust SED peaks ($\lambda_{peak}$) -- is traced most closely by its specific star-formation rate (sSFR) or parameterized 'distance' to the SFR-M$_\star$relation (the galaxy 'main sequence').
- We conclude that the more fundamental tracer of galaxies' luminosity-weighted integrated dust temperatures are indeed their star-formation surface densities in line with local Universe results, which relate closely to the underlying geometry of dust in the ISM.

##### [High angular resolution polarimetric imaging of the nucleus of NGC 1068: Disentangling the polarising mechanisms](http://arxiv.org/abs/2102.06339) [(PDF)](http://arxiv.org/pdf/2102.06339.pdf)

- SPHERE/VLT观测NGC1068
- We are able to separate the dominant polarising mechanisms in the three regions of the ionisation cone, the extended envelop of the torus and the very central bright source of the AGN.
	- Dichroic absorption is estimated to be responsible for about 99 % of the polarised flux coming from the photo-centre.
- However, this contribution would be restricted to this location only, double scattering process being the most important contributor to polarisation in the equatorial plane of the AGN and single scattering being dominant in the polar outflow bi-cone.

##### [Gamma-ray image reconstruction of the Andromeda galaxy](http://arxiv.org/abs/2102.06447) [(PDF)](http://arxiv.org/pdf/2102.06447.pdf)

- We analyze about 12 years of Fermi-LAT data in the direction of the Andromeda galaxy (M31).
- We reconstruct the gamma-ray image of M31 in a template-independent way, and we show that flat spatial models are preferred by data, indicating an extension of the $\gamma$-ray emission of about 0.3-0.4 degree for the bulge of M31.
- This study also suggests that a second component, extending to at least 1 degree, contributes to the observed total emission.

##### [Downstream depolarization in the Sausage relic: a 1-4 GHz Very Large Array study](http://arxiv.org/abs/2102.06631) [(PDF)](http://arxiv.org/pdf/2102.06631.pdf)

- We present the first high-resolution and high-sensitivity polarimetry study of the merging galaxy cluster CIZA J2242.8+5301 in the 1-4 GHz frequency band.
- For the first time in a radio relic, we observe a decreasing polarization fraction in the downstream region.
	- Possibly explained by geometrical projections and/or by decreasing of the magnetic field anisotropy towards the cluster center.
- From the amount of depolarization of the only detected background radio galaxy, we estimate a turbulent magnetic field strength of $B_{\rm turb}\sim5.6~\mu$Gauss in the relic.
