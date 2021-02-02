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
