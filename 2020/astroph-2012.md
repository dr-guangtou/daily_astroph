# ArXiv astrop-ph Journal 

- #arxiv

## 2020 December 

### Dec 1 

#### Relevant / Important / Useful

##### [The BACCO Simulation Project: A baryonification emulator with Neural Networks](https://arxiv.org/abs/2011.15018)
- #emulator #ssst_cos #baryonic_effect
- [BACCO Simulation Project](http://www.dipc.org/bacco/)
- A neural-network emulator for baryonic effects in the non-linear matter power spectrum
- Baryonic physics is described through a baryonification algorithm, that has been shown to accurately capture the relevant effects on the power spectrum and bispectrum in state-of-the-art hydrodynamical simulations.
	- 7 parameters for  extent of the ejected gas, density profiles of the hot gas and its mass fraction, and the characteristic halo mass scale for central galaxies.
- We show also that only one baryonic parameter, namely Mc, which set **the gas fraction retained per halo mass**, is enough to have accurate and realistic predictions of the baryonic feedback at a given epoch.
- **Baryon correction model, or baryonification** (Schneider & Teyssier 2015; Schneider et al. 2019; Arico et al. 2020b)

##### [On the TP-AGB contribution to the light of nearby disk galaxies](https://arxiv.org/abs/2011.13989)
- #stellar_population
- 84个近邻盘星系 pixel-by-pixel SED拟合
- For 30-40 % of the pixels in our sample a high luminosity contribution (hence low mass-to-light ratio in the NIR) from TP-AGB stars is favored.
- 具体贡献随Hubble type有变化: This may be a consequence of the variation of the TP-AGB mass-loss rate with metallicity, if metal-poor stars begin losing mass earlier than metal-rich stars, because of a pre-dust wind that precedes the dust-driven wind. 低金属丰度的TP-AGB星可能更早地开始质量损失

##### [Frequency of Tidal Features Correlates with Age and Internal Structure of Early-type Galaxies](https://arxiv.org/abs/2011.14689)
- #early_type_galaxy
- Stripe82 659 ETGs with Mr≤−19.5 in 0.015≤z≤0.055 附近tidal features的研究
- 年轻，compact的ETG有更高的 tidal frequency: We find that tidal features are more frequent in younger ETGs and more compact ETGs, so that compact young ETGs with ages ≲6 Gyr have high fT of ∼0.7
- 有 dust lane 的ETG的tidal frequency更高: ETGs with dust lanes have ∼4 times higher fT than those without dust lanes.
- 支持：compact young ETGs especially with blue cores and ETGs with dust lanes are involved in recent mergers.

#### Interesting / Keep in mind

##### [Ultra-fast model emulation with PRISM; analyzing the `Meraxes` galaxy formation model](https://arxiv.org/abs/2011.14530)
- #sam #inference #emulator 
- [`Meraxes`](https://ui.adsabs.harvard.edu/abs/2016MNRAS.462..250M/abstract) is a semi-analytic model, purposefully built to study the growth of galaxies during the Epoch of Reionization (EoR).
	- `Meraxes` walks through the aforementioned static halo trees of an N-body simulation horizontally instead of vertically. This means that for each snapshot (time instance), all halos at that snapshot within all trees are processed simultaneously, such that interactions between the different trees can be taken into account
- [`PRISM`](https://github.com/1313e/PRISM) a Python emulator: We demonstrate the power of using PRISM instead of a full Bayesian analysis when dealing with highly correlated model parameters and a scarce set of observational data.
- `PRISM` can detect when model parameters are too correlated or cannot be constrained effectively.
- [Model Dispersion with PRISM: An Alternative to MCMC for Rapid Analysis of Models](https://ui.adsabs.harvard.edu/abs/2019ApJS..242...22V/abstract)
- [PRISM: Probabilistic Regression Instrument for Simulating Models](https://ui.adsabs.harvard.edu/abs/2019ascl.soft07021V/abstract)

##### [The Cosmic Dispersion Measure in the EAGLE Simulations](https://arxiv.org/abs/2011.14547)
- #fast_radio_burst
- 不同宇宙学模型的DM-z关系不同；差别主要是在z<0.5的低红移宇宙
- DM-z关系的scatter也很重要：The scatter around the DM−z relation is highly asymmetric, especially at low redshift (z<0.5), and becomes more Gaussian as redshift approaches z∼3
- We investigated two techniques to estimate line-of-sight DM: pixel scrambling and box transformations. We find that using box transformations (a technique from the literature) causes strong correlations due to repeated replication of structure. 至少需要100Mpc box的模拟来研究DM
- Comparing a linear and non-linear model, we find that the non-linear model with cosmological parameters, provides a better fit to the DM−z relation
- 基本关系：$\left\langle\mathrm{DM}_{\text {cosmic }}\right\rangle=\left(934.5 \pm 0.3 \mathrm{pc} \mathrm{cm}^{-3}\right) \int_{0}^{2} \frac{1+z}{\sqrt{(1+z) \Omega_{m}+\Omega_{\Lambda}}} \mathrm{d} z$
- [`fruitbat` - Fast Radio Burst (FRB) Redshift Estimation](https://github.com/abatten/fruitbat)

#### Others

##### [Fundamental physics with Espresso: Towards an accurate wavelength calibration for a precision test of the fine-structure constant](https://arxiv.org/abs/2011.13963)
- #ssst_phy 超高分辨光谱仪做QSO观测测量基础物理参数的变化
- We compare the default wavelength solution, based on the combination of Thorium-Argon arc lamp spectra and a FP interferometer to the fully independent calibration obtained from a laser frequency comb. We find wavelength-dependent discrepancies of up to 24m/s. This substantially exceeds the photon noise and highlights the presence of different sources of systematics which we characterize in detail as part of this study
	
	
##### [Analysing the Epoch of Reionization with three-point correlation functions and machine learning techniques](https://arxiv.org/abs/2011.14157)
- We present 3PCF-Fast, an optimized code for estimating the three-point correlation function of 3D pixelised data such as the outputs from numerical and semi-numerical simulations.
- 假设前景移除没有问题，we use machine learning techniques to recover the mean bubble size and global ionization fraction from correlations in the outputs of the publicly available 21cmFAST code.
- Find that using the three-point correlation function outperforms the power spectrum at predicting both global ionisation fraction and mean bubble size.

##### [Accelerating MCMC algorithms through Bayesian Deep Networks](https://arxiv.org/abs/2011.14276)
- #machine_learning
- We show an alternative way of performing adaptive MCMC, by using the outcome of Bayesian Neural Networks as the initial proposal for the Markov Chain.
	
##### [Intergalactic medium dispersion measures of fast radio bursts estimated from IllustrisTNG simulation and their cosmological applications](https://arxiv.org/abs/2011.14494)
- #fast_radio_burst
- The probability distribution of DMIGM can be well fitted by a quasi-Gaussian function with a long tail. The tail is caused by the structures along the line of sight in IGM.
- Subtracting DM contributions from the Milky Way and host galaxy for localized FRBs, the DMIGM value is close to the derived DM_IGM−z relation.
- 高红移FRB可以帮助限制再电离历史：The derived DM_IGM−z relation at high redshifts can be well fitted by a tanh reionization model with the reionization redshift z=5.95,

##### [The First IFU Spectroscopic View of Shocked Cluster Galaxies](https://arxiv.org/abs/2011.13935)
- #cluster_galaxies 
- CIZA J2242.8+5301 (nicknamed the Sausage) 中5个位于shock fronts尾部的Halpha发射星系的GMOS-N观测
- While the galaxies show evidence for rotational support, the flux and velocity maps have complex features like tails and gas outflows aligned with the merger axis of the cluster. 
- With gradients incompatible with inside-out disk growth, the metallicity maps are consistent with sustained SF throughout and outside of the galactic disks.

##### [Fast-spinning bars in the ΛCDM cosmological paradigm](https://arxiv.org/abs/2011.13942)
- The angular velocity with which galactic bars rotate is intimately linked to the amount of dark matter in the inner regions of their host galaxies. DM对棒有减速作用，通过动力学摩擦作用；但是观测中看到的bar的旋转速度较快
- 通过模拟发现：bars form in galaxies that have higher stellar-to-dark matter ratios and are more baryon-dominated than in previous cosmological simulations; this suggests that in order **for bars to remain fast, massive spiral galaxies must lie above the commonly used abundance matching relation. **

##### [The Second Data Release of the Survey of the MAgellanic Stellar History (SMASH)](https://arxiv.org/abs/2011.13943)
- #merian #decam
- DECam巡天： ∼50 nights to sample over ∼2400 deg2; ~24 mag depth in _ugriz_ bands
- SMASH public data release (DR2), which contains all 197 fully-calibrated DECam fields including the main body fields in the central regions.

##### [The impact of magnetic fields on cosmological galaxy mergers. I: Reshaping gas and stellar discs](https://arxiv.org/abs/2011.13947)
- Arepo模拟：磁场的影响对整体星系性质不大，但对major merger remnant有显著影响
- MHD simulations consistently form remnants with extended discs and well-developed spiral structure, whilst hydrodynamic simulations form more compact remnants that display distinctive ring morphology
- We argue that this is due to the more efficient excitement of a small-scale dynamo in higher resolution simulations, resulting in a more strongly amplified field that is better able to influence gas dynamics.

##### [Connecting turbulent velocities and magnetic fields in galaxy cluster simulations with active galactic nuclei jets](https://arxiv.org/abs/2011.13964)
- We investigate the inherent relationship between large-scale gas kinematics and magnetic fields through non-radiative magnetohydrodynamical simulations of the creation, evolution and disruption of AGN jet-inflated lobes in an isolated Perseus-like galaxy cluster, with and without pre-existing turbulence.
- For single jet outbursts, we find only a local impact on the velocity field, i.e. the associated increase in velocity dispersion is not volume-filling. 如果有pre-existing turbulence的话，基本看不到速度弥散度的改变
- 在X-ray观测角分的尺度上，速度弥散度主要是有已经存在的大尺度湍动决定的，Jet的影响很小

##### [How robustly can we constrain the low-mass end of the z∼6−7 stellar mass function? -- The limits of lensing models and stellar population assumptions in the Hubble Frontier Fields](https://arxiv.org/abs/2011.13991)
- FrontierField内高红移低质量星系的研究，Our sample probes stellar masses down to M⋆>10^6M⊙ and we find the z∼6−7 GSMF to be best parametrized by a modified Schechter function which allows for a turnover at very low masses
- SMF的形式与假设的SFH和尘埃性质关系很大

##### [Understanding the radio relic emission in the galaxy cluster MACS J0717.5+3745: spectral analysis](https://arxiv.org/abs/2011.14436)
- uGMRT+VLA+LOFAR  high spatial resolution spectral analysis of the relic
- The integrated spectrum of the relic closely follows a power-law between 144 MHz and 5.5 GHz with a mean spectral slope α=−1.16±0.03
- Assuming Diffusive Shock Acceleration, we estimate a dominant Mach number of ∼3.7 for the shocks that make up the relic.
- 投影效应很重要：We conclude that projection effects and inhomogeneities in the shock Mach number dominate the observed spectral properties of the relic in this complex system.

##### [Active Galactic Nucleus Feedback in an Elliptical Galaxy with the Most Updated AGN Physics: Parameter Explorations](https://arxiv.org/abs/2011.15024)
- We find that the velocity of AGN wind in the hot mode is the most important quantity to control the typical accretion rate and luminosity of AGN, and the mass growth of the BH.
- Within the limited parameter range explored in the current work, a stronger AGN wind suppresses star formation within ~100 pc but enhances star formation beyond this radius, while the star formation integrated over the evolution time and the whole galaxy roughly remain unchanged.
- A smaller initial BH mass results in a more violent evolution of the BH accretion rate. 

##### [A Spitzer survey of Deep Drilling Fields to be targeted by the Vera C. Rubin Observatory Legacy Survey of Space and Time](https://arxiv.org/abs/2011.15030)
- #csst-deep
- LSST-DDFs的Spitzer观测：The combined DeepDrill and SERVS data cover the footprints of the LSST DDFs in the Extended Chandra Deep Field-South field (ECDFS), the ELAIS-S1 field (ES1), and the XMM Large-Scale Structure Survey field (XMM-LSS).
- 深度可以看到z~5的10^11 Msun的星系；The dual-band catalogues contain a total of 2.35 million sources
- We also identify a population of sources with extremely red ([3.6]−[4.5] >1.2) colours which we show mostly consists of highly-obscured active galactic nuclei.

##### [The hyperluminous, dust-obscured quasar W2246-0526 at z=4.6: detection of parsec-scale radio activity](https://arxiv.org/abs/2011.15063)
- To search for the evidence of the jet activity launched by the SMBH in W2246-0526, we performed very long baseline interferometry (VLBI) observations of its radio counterpart with the EVN, e-MERLIN, VLBA
- The resolved-out radio emission possibly come from a diffuse jet, quasar-driven winds, or both, while the contribution by star formation activity is negligible

##### [Systematic Study of AGN Clumpy Tori with Broadband X-ray Spectroscopy: Updated Unified Picture of AGN Structure](https://arxiv.org/abs/2011.13931)
- X-ray clumpy torus model (XCLUMPY; Tanimoto et al. 2019)
- The relation between the Eddington ratio and the torus covering factor determined from the X-ray torus parameters of each object follows the trend found by Ricci et al. (2017) based on a statistical analysis
- (1) the torus angular widths determined by the infrared data are larger than those by the X-ray data and that (2) the ratios of the hydrogen column density to V-band extinction (NH/AV) along the line of sight in obscured AGNs are similar to the Galactic value on average.

##### [The Awakening Beast in the Seyfert 1 Galaxy KUG 1141+371 I](https://arxiv.org/abs/2011.14254)
- The significant multi-wavelength luminosity change is likely due to a boost of mass accretion rate from approximately 0.6% of the Eddington limit to 3.2%, assuming a black hole mass of 10^8M⊙
- SED models also suggest a simultaneous increase of disc temperature and a decreasing inner disc radius along with the increasing accretion rate.

---- 

### Dec 2 

#### Relevant / Important / Useful

##### [The splashback boundary of haloes in hydrodynamic simulations](https://arxiv.org/abs/2012.00025)
- #splashback #cluster_cosmology #galaxy_halo 
- We calculate Rsp for haloes with masses between 10^{13−15}M⊙ as a function of halo mass, accretion rate and redshift. Rsp decreases with mass and with redshift for haloes of similar M200m in agreement with previous work. We also find that Rsp/R200m decreases with halo accretion rate. 
- The radius of steepest slope in gas profiles is consistently smaller than the value calculated from dark matter profiles. The steepest slope in galaxy profiles, which are often used in observations, tends to agree with dark matter profiles but is lower for less massive haloes
- 和DM-only run比较，发现重子物理过程影响不大

##### [Clustering of CODEX clusters](https://arxiv.org/abs/2012.00090)
- #cluster_galaxies #cluster_cosmology #ssst_cos
- These clusters were X-ray selected using the RASS survey and then identified as galaxy clusters using the code redMaPPer run on the photometry of the SDSS.
- We computed the two-point autocorrelation function of galaxy clusters in the 0.1<z<0.3 and 0.3<z<0.5 redshift bins.  测量 cluster bias，和模拟比较，估计宇宙学常数
- We illustrate the complementarity of clustering constraints by combining them with CODEX cosmological constraints based on the X-ray luminosity function, deriving Ωm0=0.25±0.01 and σ8=0.81+0.01−0.02

##### [Modeling assembly bias with machine learning and symbolic regression](https://arxiv.org/abs/2012.00111)
- #galaxy_halo #assembly_bias #machine_learning 
- 背景是未来21cm巡天所需的Halo模型：TNG模拟中halo中的HI成分对环境的依赖很强；在21cm模拟中必须要考虑
- We then use machine learning techniques to show that this effect can be 1) modeled by these algorithms and 2) parametrized in the form of novel analytic equations.

##### [dm2gal: Mapping Dark Matter to Galaxies with Neural Networks](https://arxiv.org/abs/2012.00186)
- #galaxy_halo #machine_learning 
- [`dm2gal` - painting stellar mass on top of gravity-only simulations with convolutional neural networks](https://github.com/nkasmanoff/dm2gal)
- We use convolutional neural networks to paint galaxy stellar masses on top of the dark matter field generated by gravity-only simulations. Stellar mass of galaxies are important for galaxy selection in surveys and thus an important quantity that needs to be predicted. Our model outperforms the state-of-the-art benchmark model and allows the generation of fast and accurate models of the observed galaxy distribution.

#### Interesting / Keep in mind

##### [Ancient Very Metal-Poor Stars Associated With the Galactic Disk in the H3 Survey](https://arxiv.org/abs/2012.00036)
- #milky_way #ssst_mw
- >70% of VMP stars near the disk are on prograde orbits and this fraction increases toward lower metallicities. This result unexpected if metal-poor stars are predominantly accreted from many small systems with no preferred orientation, as such a scenario would imply a mostly isotropic distribution. 
- We find there is some evidence for higher fractions of prograde orbits amongst stars with lower [α/Fe]. 而且这些贫金属星都很年老；说明这些贫金属星是在一个well-mixed disk上形成的；
- We speculate that the VMP population has a heterogeneous origin, including both in-situ formation in the ancient disk and accretion from a satellite with the same direction of rotation as the ancient disk at early times.

##### [Large-Scale Gravitational Lens Modeling with Bayesian Neural Networks for Accurate and Precise Inference of the Hubble Constant](https://arxiv.org/abs/2012.00042)
- #machine_learning 
- [`h0rton` - Hierarchical inference of H0 using Bayesian neural networks](https://github.com/jiwoncpark/h0rton)
- The use of [approximate Bayesian neural networks (BNNs)](https://arxiv.org/pdf/2007.06823.pdf) in modeling hundreds of time-delay gravitational lenses for Hubble constant (H0) determination.
	- Bayesian neural networks (BNNs) offer an efficient alternative to forward-modeling (Denker & LeCun 1991)
- The BNN can accurately characterize the posterior PDFs of model parameters governing the elliptical power-law mass profile in an external shear field.
- A simple combination of 200 test-set lenses results in a precision of 0.5 km s−1 Mpc−1 (0.7%), with no detectable bias in this H0 recovery test.

#### Others

##### [On the duration of the embedded phase of star formation](https://arxiv.org/abs/2012.00019)
- We measure how long massive stellar populations remain embedded within their natal cloud, by applying a statistical method to six nearby galaxies at 20-100 pc resolution, using CO, Spitzer 24μm, and Hα emission as tracers of molecular clouds, embedded star formation, and exposed star formation
- Embeded阶段持续2-7 Myr，占cloud lifetime的17-47%
- 这个阶段的前一半时间里在Halpha波段上不可见；For the second half of this phase, the region also emits in Hα and is partially exposed. 
- 当Cluster被feedback打散后，24微米发射就不再准确示踪正在进行的SF了
- The short duration of massive star formation suggests that pre-supernova feedback (photoionization and winds) is important in disrupting molecular clouds.

##### [Distinguishing AGN from starbursts as the origin of double peaked Lyman-Alpha Emitters in the reionization era](https://arxiv.org/abs/2012.00014)
- 最近在有些高红移的LAE中看到了双峰发射线，看这些线的起源会不会是有遮挡的AGN
- Combining the extent of the Lyman-α near-zones estimated from the blue peak velocity offset in these galaxies, with the ionizing emissivity of quasars at z≳6, we forecast the intrinsic UV and X-ray luminosities of the AGN needed to give rise to their double-peaked profiles
- Maximum radius of Lya near-zone: $\begin{aligned} R_{\alpha, \max }=& 3.14\left(\frac{N_{\text {ion }}}{2 \times 10^{57} s^{-1}}\right)^{1 / 2}\left[\frac{\left(\alpha_{\nu}\right)^{-1}\left(\alpha_{\nu}+3\right)}{3}\right]^{-1 / 2} \\ & \times\left(\frac{1+z_{\alpha}}{7}\right)^{-9 / 4} \mathrm{pMpc} \end{aligned}$

##### [PINT: A Modern Software Package for Pulsar Timing](https://arxiv.org/abs/2012.00074)
- [`pint`  - PINT is not TEMPO3 - New software for high-precision pulsar timing](https://github.com/nanograv/PINT)

##### [Mass-gap Mergers in Active Galactic Nuclei](https://arxiv.org/abs/2012.00011)
- The high BH masses in GW190521 are consistent with mergers of high-generation (high-g) BHs where the initial progenitor stars had high metallicity, 2g BHs if the original progenitors were metal-poor, or 1g BHs that had gained mass via super-Eddington accretion. 
- Furthermore, mergers in the lower mass gap or those with low mass ratio as found in GW190814 and GW190412 are also reproduced by mergers of 2g-1g or 1g-1g objects with significant accretion in AGN disks.

##### [Constraints on the rate of supernovae lasting for more than a year from Subaru/Hyper Suprime-Cam](https://arxiv.org/abs/2012.00171)
- #ssst_tdm
- HSC transient survey: We observed the same 1.75 deg2 field repeatedly using the g, r, i, and z band filters with the typical depth of 26 mag for 4 seasons (from late 2016 to early 2020). 找能持续一年以上的transients
- Two supernovae were detected in 2 continuous seasons, one supernova was detected in 3 continuous seasons, but no transients lasted for all 4 seasons searched.
- No plausible pair-instability supernova candidates lasting for more than a year are discovered. 

##### [NuSTAR Observations of Abell 2163: Constraints on Non-thermal Emission](https://arxiv.org/abs/2012.00236) 
- RXTE detected IC emission in one of the hottest known clusters, Abell 2163 (A2163), a massive merging cluster with a giant radio halo--the presumed source of relativistic electrons IC scattering CMB photons to X-ray energies.
- We find the 3-30 keV spectrum can be described by purely thermal emission, with a global average temperature of kT = (11.8 ± 0.2) keV. 
- Combining these limits with 1.4 GHz diffuse radio data from the VLA, we find the average magnetic field strength to be > 0.22μG and > 0.35μG, respectively, providing the strongest constraints on these values in A2163 to date.

##### [Cloud-by-cloud, multiphase, Bayesian modeling: Application to four weak, low ionization absorbers](https://arxiv.org/abs/2012.00021) 
- We carry out cloud-by-cloud, multiphase modeling making use of CLOUDY and Bayesian methods to extract physical properties from an ensemble of absorption profiles.

##### [Relationships between the Stellar, Gaseous, and Star Formation Disks in LITTLE THINGS Dwarf Irregular Galaxies: Indirect Evidence for Substantial Fractions of Dark Molecular Gas](https://arxiv.org/abs/2012.00146) 
- We find that the HI radial profiles are generally flatter in the center and fall faster in the outer regions than the V-band profiles, while young stars are more centrally concentrated, especially if the HI is more centrally flat. 说明HI在中心被转化成了可以形成恒星的分子气体
- A model that assumes the molecular surface density is proportional to the total gas surface density to a power of 1.5 or 2, in analogy with the Kennicutt-Schmidt relation, reproduces the relationship between the ratio of the visible to the HI scale length and the HI Sersic index.

##### [Identifying radio active galactic nuclei among radio-emitting galaxies](https://arxiv.org/abs/2012.00367) 
- ROGUE I, a catalog of over 32,000 radio sources associated with optical galaxies, we provide two diagnostics to select the galaxies where the radio emission is due to an active galactic nucleus (AGN).
- The first one, dubbed MIRAD, compares the flux FW3 in the W3 mid-infrared band of the WISE telescope, with the radio flux at 1.4 GHz
- The second diagnostic, dubbed DLM, relates the 4000 \AA\ break strength, Dn(4000), with the radio luminosity per unit stellar mass.

##### [Spatial Distribution of OVI Covering Fractions in the Simulated Circumgalactic Medium](https://arxiv.org/abs/2012.00727) 
- 用模拟研究OVI吸收气体在CGM中的分布：Using [`Mockspec`](https://github.com/jrvliet/MOCKSPEC), an absorption line analysis pipeline, we generate synthetic quasar absorption line observations of the simulated CGM.
- We find that the OVI covering fraction obtained for the simulated galaxies agrees well with the observed value for the inner halo (D/Rvir≤0.375) and is within 1.1σ in the outer halo (D/Rvir>0.75), but is underproduced within 0.375<D/Rvir≤0.75.
- The observed bimodal distribution of OVI covering fraction with azimuthal angle, showing higher frequency of absorption along the projected major and minor axes of galaxies, is not reproduced in the simulations.

### Dec 3

#### Relevant / Important / Useful

##### [Shock and Splash: Gas and Dark Matter Halo Boundaries around LambdaCDM Galaxy Clusters](https://arxiv.org/abs/2012.00977)
- #splashback #galaxy_halo #galaxy_cluster
- 65 massive dark matter halos extracted from the Omega500 simulation
- 和自相似模型预测的不同，accretion shock的位置和SP半径位置不同：The accretion shock radius is larger than all definitions of the splashback radius in the literature by 20-100%.
- The accretion shock radius defined using the steepest drop in the entropy pressure profiles is approximately 2 times larger than the splashback radius defined by the steepest slope in the dark matter density profile

##### [The mass-size relation of galaxy clusters](https://arxiv.org/abs/2012.01336)
- #splashback #galaxy_halo #galaxy_cluster
- We also show that the depth of the splashback feature correlates well with the direction of filaments and, surprisingly, the orientation of the brightest cluster galaxy. 
- Our findings suggest that galaxy profiles and weak-lensing masses can define an observationally viable mass-size scaling relation for galaxy clusters, which can be used to extract cosmological information.

#### Interesting / Keep in mind

##### [Most of the cool CGM of star-forming galaxies is not produced by supernova feedback](https://arxiv.org/abs/2012.00770)
- #CGM
- We developed semi-analytical parametric models to describe the cool CGM as an outflow of gas clouds from the central galaxy, as a result of supernova explosions in the disc 和COS观测比较
- Our findings clearly show that a supernova-driven outflow model is not suitable to describe the dynamics of the cool circumgalactic gas.
- This strongly suggests that, since the outflows cannot reproduce most of the cool gas absorbers, the latter are likely the result of cosmological inflow in the outer galaxy halos, in analogy to what we have previously found for early-type galaxies.

##### [Distances to PHANGS Galaxies: New Tip of the Red Giant Branch Measurements and Adopted Distances](https://arxiv.org/abs/2012.00757)
- #nearby_galaxies [[Nearby Galaxies Surveys]]
- 20Mpc的38个旋涡星系的HST观测，ACS F606W/F814W观测：we use these parallel fields to derive tip of the red giant branch (TRGB) distances to these galaxies.
- We also provide a compilation of distances for the 118 galaxies in the full PHANGS sample, which have been adopted for the first PHANGS-ALMA public data release.

#### Others

##### [Probing Large-scale UV Background Inhomogeneity Associated with Quasars using Metal Absorption](https://arxiv.org/abs/2012.00772)
- Overall stronger high ionization species absorption is seen closer to quasars at 2.4<z<3.1. O VI absorption shows a particularly strong change, with effects in C IV evident in some cases
- Demonstrate that UV background inhomogeneities exist on scales of several 10s of comoving megaparsecs associated with quasars and that they can be measured with precision by examining metal absorption in the intergalactic medium.

##### [The Rapid ASKAP Continuum Survey I: Design and First Results](https://arxiv.org/abs/2012.00747)
- #radio_survey [[Radio Surveys]]
- RACS will provide a shallow model of the ASKAP sky that will aid the calibration of future deep ASKAP surveys. RACS will cover the whole sky visible from the ASKAP site in Western Australia. 
- Will cover the full ASKAP band of 700−1800 MHz
- The RACS images are generally deeper than the existing NRAO VLA Sky Survey (NVSS) and Sydney University Molonglo Sky Survey (SUMSS) radio surveys and have better spatial resolution.
- [Survey website](https://research.csiro.au/racs/) and the[data Release here](https://data.csiro.au/collections/domain/casdaObservation/results/PRAS110%20-%20The%20Rapid%20ASKAP%20Continuum)

##### [AGN Triality of Triple Mergers: Detection of Faint X-ray Point Sources](https://arxiv.org/abs/2012.00761)
- We conclude that 1 triple merger has one X-ray point source (SDSS J0858+1822, although it's unlikely to be an AGN); 5 triple mergers are likely composed of two X-ray point sources (NGC 3341, SDSS J1027+1749, SDSS J1631+2352, SDSS J1708+2153, and SDSS J2356−1016); and one system is composed of three X-ray point sources (SDSS J0849+1114)
- The dual and triple point source systems are found to have physical separations between 3-9 kpc and flux ratios between 2x10^-3 - 0.84.

##### [AGN Triality of Triple Mergers: Multi-wavelength Classifications](https://arxiv.org/abs/2012.00769)
- Analyzing the multi-wavelength observations of 7 triple galaxy mergers, we find that 1 triple merger has a single AGN (NGC 3341); we discover, for the first time, 4 likely dual AGN (SDSS J1027+1749, SDSS J1631+2352, SDSS J1708+2153, and SDSS J2356-1016); we confirm one triple AGN system, SDSS J0849+1114
- Higher levels of nuclear gas are more likely to activate AGN in mergers

##### [Identification of AKARI infrared sources by Deep HSC Optical Survey: Construction of New Band-Merged Catalogue in the NEP-Wide field](https://arxiv.org/abs/2012.00750)
- We present newly identified AKARI sources by the HSC survey, along with multi-band photometry for 91,861 AKARI sources observed over the NEPW field.

##### [Morphological evolution of supermassive black hole merger hosts and multimessenger signatures](https://arxiv.org/abs/2012.00775)
- 基于Illustris模拟中的SMBH并合：We find that these mergers take place in typical galaxies along the MBH−M∗ relation, and that between LISA and PTA detections we can expect to probe the full range of galaxy masses.
- We do find that galaxies hosting low-mass black hole mergers tend to show a slight increase in star formation rates compared to a mass-matched sample
- We further find that incorporating a realistic timescale delay for the black hole mergers could shift the distribution of merger masses toward higher-mass mergers, decreasing the rate of LISA detections while increasing the rate of PTA detections.

##### [The delay time distribution of Type-Ia supernovae in galaxy clusters: the impact of extended star-formation histories](https://arxiv.org/abs/2012.00793)
- 关于星系团中SNIa的DTD，之前的结论是和Field中不同：DTD has a power-law form whose normalisation is at least several times higher than measured in field-galaxy environments, implying that SNe Ia are produced in larger numbers by the stellar populations in clusters.
- We re-derive the DTD from the cluster SN Ia data, but now relax the single-burst assumption. 
- The derived cluster-environment DTD remains higher (at 3.8σ significance) than the field-galaxy DTD, by a factor ∼2−3. Cluster and field DTDs both have consistent slopes of α≈−1.1.

##### [A KMOS survey of the nuclear disk of the Milky Way I: Survey design and metallicities](https://arxiv.org/abs/2012.00918)
- KMOS low resolution spectroscopic survey of the stars in the nuclear disk reaching the old populations.
- We obtain spectra of 3113 stars with a median S/N of 67. We measure velocities for 3051 stars. Of those, 2735 sources have sufficient S/N to estimate temperatures and metallicities.
- Our data set complements Galactic surveys such as Gaia and APOGEE for the inner 200 pc radius of the Milky Way which is not readily accessible by those surveys due to extinction.

##### [Spatially resolved direct method metallicity in a high-redshift analogue local galaxy: temperature structure impact on metallicity gradients](https://arxiv.org/abs/2012.01113)
- We investigate how HII region temperature structure assumptions affect "direct-method" spatially-resolved metallicity observations using multispecies auroral lines
- The spatial metallicity trends show significant differences among the three direct methods. We conclude that overlooked assumptions about the internal temperature structure of HII regions in the direct method can lead to large discrepancies in metallicity gradient studies. 

##### [Attention-gating for improved radio galaxy classification](https://arxiv.org/abs/2012.01248)
- We present an attention-based model that performs on par with previous classifiers while using more than 50% fewer parameters than the next smallest classic CNN application in this field.
- We show that while the selection of normalisation and aggregation may only minimally affect the performance of individual models, it can significantly affect the interpretability of the respective attention maps and by selecting a model which aligns well with how astronomers classify radio sources by eye, a user can employ the model in a more effective manner. 

----

### Dec 4

#### Relevant / Important / Useful

##### [Stellar Population Inference with Prospector](https://arxiv.org/abs/2012.01426)
- #stellar_population 
- [Code for Prospector paper examples](https://github.com/bd-j/exspect)
- We present prospector, a flexible code for inferring stellar population parameters from photometry and spectroscopy spanning UV through IR wavelengths.

##### [Cosmology with galaxy cluster weak lensing: statistical limits and experimental design](https://arxiv.org/abs/2012.01956)
- #cluster_cosmology #weak_lensing #galaxy_halo #csst-deep 
- We advocate an approach, analogous to galaxy-galaxy lensing, in which the observables in each redshift bin are the mean number counts and the mean weak lensing profile of clusters above a mass proxy threshold.
- The primary astrophysical nuisance parameter is the logarithmic scatter between the mass proxy and true mass near the threshold.
- 预测DES, Roman/HLS, LSST的预测能力：we forecast aggregate precision on sigma_8 of 0.26%, 0.24%, and 0.10%
- These constraints would be degraded by about 20% for a 0.05 prior on scatter in the case of DES or HLS and for a 0.016 prior for LSST.
- A one-month observing program with Roman Space Telescope targeting approximately 2500 massive clusters could achieve a 0.5% constraint on sigma_8(z=0.7) on its own, or a ~0.33% constraint in combination with the HLS.

##### [What does (not) drive the variation of the low-mass end of the stellar initial mass function of early-type galaxies](https://arxiv.org/abs/2012.01431)
- #stellar_population #early_type_galaxy #initial_mass_function
- NGC 3311 is characterized by old and metal-rich stars, like other massive ETGs, but has unusual increasing stellar velocity dispersion and [α/Fe] profiles
- MUSE + Full spectrum fitting: 
- IMF和local stellar velocity dispersion不相关：NGC 3311, we unambiguously invalidate the previously observed direct correlation between the IMF slope and the local stellar velocity dispersion, confirming some doubts already raised in the literature
- We also show robust evidence that the proposed IMF-metallicity relation is contaminated by the degeneracy between these two parameters.
- The tightest correlations we found are those between stellar age and IMF and between galactocentric radius and IMF. 
- We speculate that IMF might be dwarf-dominated in the "red-nuggets" formed at high redshifts that ended up being the central cores of today's giant ellipticals.

##### [ALMA measures rapidly depleted molecular gas reservoirs in massive quiescent galaxies at z~1.5](https://arxiv.org/abs/2012.01433)
- #massive_galaxy #early_type_galaxy 
- ALMA CO(2-1) spectroscopy of 6 massive (log10M∗/M⊙>11.3) quiescent galaxies at z∼1.5
- We detect one galaxy at 4σ significance and place upper limits on the molecular gas reservoirs of the other 5, finding molecular gas mass fractions MH2/M∗=fH2<2−6% (3σ upper limits).  比同质量同红移的SF星系低1-2个量级
- This indicates that their molecular gas reservoirs were rapidly and efficiently used up or destroyed, and that gas fractions are uniformly low (<6%) despite the structural diversity of our sample
- We find that our low gas fractions are instead in agreement with predictions from both the recent SIMBA cosmological simulation, and from analytical "bathtub" models for gas accretion onto galaxies in massive dark matter halos 说明了在z~4的时候已经有很高的Halo质量了
	- 另外的解释：we cannot rule out that these galaxies reside in lower mass halos, and low gas fractions may instead reflect either stronger feedback, or more efficient gas consumption.

#### Interesting / Keep in mind

##### [Predictions for the FAST telescope's CRAFTS Extra-Galactic HI Survey](https://arxiv.org/abs/2012.01683)
- #radio_survey 
- Our results suggest that a two-pass extragalactic HI survey will be able to detect nearly 4.8×10^5 galaxies, from which the 'faint end' slope of the HI Mass Function (HIMF) can be recovered to 10^7M⊙ and the 'knee mass' of the HIMF can be measured to a redshift of 0.1.
- Considering the radio frequency interference status and sensitivity limitation, CRAFTS will be efficient in detecting HI galaxies at redshifts below 0.1

#### Others

##### [Close-up view of a luminous star-forming galaxy at z=2.95](https://arxiv.org/abs/2012.01448)
- HerBS-89a, at z=2.95的NOEMA观测
- HerBS-89a is a powerful star forming galaxy with a dust-to-gas ratio delta(GDR)~80, a SFR = 614 +/- 59 Msun/yr and a depletion timescale tau(depl) = (3.4 +/- 1.0) 1e8 years.
- The OH+ and CH+ absorption lines, all have their main velocity component red-shifted by \Delta(V)~100 km/s relative to the global CO reservoir. We argue that these absorption lines trace a rare example of gas inflow towards the center of the galaxy.

##### [Exploring the link between C IV outflow kinematics and sublimation-temperature dust in quasars](https://arxiv.org/abs/2012.01425)

##### [Cosmic Ray Diffusion Suppression in Star-Forming Regions Inhibits Clump Formation in Gas-Rich Galaxies](https://arxiv.org/abs/2012.01427)

##### [The Formation of the First Quasars. I. The Black Hole Seeds, Accretion and Feedback Models](https://arxiv.org/abs/2012.01458)

##### [Host Galaxy Mass Combined with Local Stellar Age Improve Type Ia Supernovae Distances](https://arxiv.org/abs/2012.01460)

##### [Deviations from tidal torque theory: evolution of the halo spin-filament alignment](https://arxiv.org/abs/2012.01638)

##### [Anomalous gas in ESO 149-G003: A MeerKAT-16 View](https://arxiv.org/abs/2012.01751)
- Our more sensitive radio observations confirm the presence of anomalous gas in ESO 149-G003, and further confirm the formerly tentative detection of an extraplanar HI component in the galaxy.
- We investigate a number of global scaling relations and find that, besides being gas-dominated with a neutral gas-to-stellar mass ratio of 1.7, the galaxy does not show any obvious global peculiarities.
- We conclude that the galaxy is likely currently acquiring neutral gas. It is either re-accreting gas expelled from the galaxy or accreting pristine intergalactic material.

##### [Chemical abundances in Seyfert galaxies -- V. The discovery of shocked emission outside the AGN ionization axis](https://arxiv.org/abs/2012.02013)
- In Mrk 79 and Mrk 348, we find direct evidence for shock-ionization with overall orientation orthogonal to the ionization axis, where shocks can be easily observed as the AGN radiation field is shielded by the nuclear dusty torus.


#### Gaia EDR3
- #gaia

- [Gaia Collaboration 2020a - Gaia Early Data Release 3: Summary of the contents and survey properties](https://arxiv.org/abs/2012.01533)
	- Gaia EDR3 contains celestial positions and the apparent brightness in G for approximately 1.8 billion sources. For 1.5 billion of those sources, parallaxes, proper motions, and the (G_BP-G_RP) colour are also available.
	- Gaia EDR3 represents a significant advance over Gaia DR2, with parallax precisions increased by 30 percent, proper motion precisions increased by a factor of 2, and the systematic errors in the astrometry suppressed by 30--40 percent for the parallaxes and by a factor ~2.5 for the proper motions.

- [Lindegren et al. 2020 - Gaia Early Data Release 3: Parallax bias versus magnitude, colour, and position](https://arxiv.org/abs/2012.01742)
	- Inspection of the EDR3 data for sources identified as quasars reveals that their parallaxes are biased, that is systematically offset from the expected distribution around zero, by a few tens of microarcsec.
	- The parallax bias is found to depend in a non-trivial way on (at least) the magnitude, colour, and ecliptic latitude of the source. Different dependencies apply to the five- and six-parameter solutions in EDR3.
	
- [Riello et al. 2020 - Gaia Early Data Release 3: Photometric content and validation](https://arxiv.org/abs/2012.01916)	
	- The treatment of the BP and RP background has been updated to include a better estimation of the local background, and the detection of crowding effects has been used to exclude affected data from the calibrations.
	- Using one passband over the whole colour and magnitude range leaves no systematics above the 1% level in magnitude in any of the bands, and a larger systematic is present for a very small sample of bright and blue sources
	
- [Rowell et al. 2020 - Gaia Early Data Release 3: Modelling and calibration of Gaia's point and line spread functions](https://arxiv.org/abs/2012.02069)
	- Gaia Early Data Release 3 (EDR3) will, for the first time, use a PSF calibration that models several of the strongest dependences, leading to signficantly reduced systematic errors.
	- We develop models of the 1D line spread function (LSF) and 2D PSF profiles based on a linear combination of basis components. 
	- The PSF calibration shows strong time and colour dependences that accurately reproduce the varying state of the Gaia astrometric instrument.
	
- [Gaia Early Data Release 3: Structure and properties of the Magellanic Clouds](https://arxiv.org/abs/2012.01771)
	- We derive radial and tangential velocity maps and global profiles for the LMC for the several subsamples we defined.
	- We show that the Gaia EDR3 data allows clearly resolving the Magellanic Bridge, and we trace the density and velocity flow of the stars from the SMC towards the LMC not only globally, but also separately for young and evolved populations.
	
- [Gaia Early Data Release 3: Acceleration of the solar system from Gaia astrometry](https://arxiv.org/abs/2012.02036)
	- Our best estimate of the acceleration based on Gaia EDR3 is (2.32±0.16)×10^{−10} m s−2 (or 7.33±0.51 km s−1 Myr−1) towards α=269.1∘±5.4∘, δ=−31.6∘±4.1∘, corresponding to a proper motion amplitude of 5.05±0.35 μas yr−1.

- [Gaia Early Data Release 3: The Gaia Catalogue of Nearby Stars](https://arxiv.org/abs/2012.02061)
	- We have produced a catalogue of 331 312 objects that we estimate contains at least 92% of stars of stellar type M9 within 100 pc of the Sun.
	- We detected local manifestations of several streams, superclusters, and halo objects, in which we identified 12 members of Gaia Enceladus. 
	
----

### Dec 7

#### Relevant / Important / Useful

##### [Compact, bulge dominated structures of spectroscopically confirmed quiescent galaxies at z~3](https://arxiv.org/abs/2012.02766)
- #early_type_galaxy #massive_galaxy #red_nugget
- Ten 10.8<log(M⋆/M⊙)<11.3 galaxies at 2.4<z<3.2 in the COSMOS field whose redshifts and quiescence are confirmed by HST grism spectroscopy
- We find typically high S\'ersic indices and axis ratios (medians ≈4.5 and 0.73, respectively) suggesting that, at odds with some previous results, the first massive quiescent galaxies may largely be already bulge-dominated systems
- This work confirms the existence of a population of compact, bulge dominated, massive, quiescent sources at z≈3, providing one of the first statistical estimates of their structural properties, and further constraining the early formation and evolution of the first quiescent galaxies.

##### [HST grism spectroscopy of z~3 massive quiescent galaxies: Approaching the metamorphosis](https://arxiv.org/abs/2012.02767)
- #early_type_galaxy #massive_galaxy #red_nugget
- Hubble Space Telescope WFC3/G141 grism spectra of 10 quiescent galaxy candidates selected at 2.5<z<3.5 in the COSMOS field. 
- Broad spectral indices are consistent with the presence of young A-type stars flagging the last major episode of star formation to have taken place no earlier than ∼300-800 Myr prior to observation.
- Median stack emission from 3GHz data constrains the level of residual obscured SFR to be globally below 50 M⊙ yr−1, hence three times below the scatter of the coeval main sequence. 但还是有SF活动的
- 或者也可以用AGN解释射电探测 The very same radio detection suggests a widespread radio-mode feedback by active galactic nuclei (AGN) four times stronger than in z∼1.8 massive QGs.

##### [On the Flaring of Thick Disc of Galaxies: Insights from Simulations](https://arxiv.org/abs/2012.02741)
- #edge_on_galaxy
- 利用模拟看单年龄星族(MAP)对厚盘结构的影响，以及什么情况下薄盘-厚盘的区分是有物理意义的：
- We find that flat thick discs are created when MAPs barely flare or have low surface density at the radius where they start flaring.  薄盘厚盘是连续结构，且并合历史较平静
- Flared thick discs, on the other hand, are created when the MAPs that flare have a high surface density at the radius where they start flaring.
- Flared thick discs have diverse radial age gradients and merger histories, with galaxies that are more massive or that have undergone massive mergers showing flatter age radial gradients in their thick disc.

#### Interesting / Keep in mind

##### [An extended halo around an ancient dwarf galaxy](https://arxiv.org/abs/2012.02309)
- #ssst_mw #ssst_lg
- Here we identify members of the Tucana II ultra-faint dwarf galaxy in its outer region (up to 9 half-light radii), demonstrating the system to be dramatically more spatially extended and chemically primitive than previously found.
- These distant stars are extremely metal-poor (<[Fe/H]>=-3.02; less than ~1/1000th of the solar iron abundance), affirming Tucana II as the most metal-poor known galaxy. 
- We observationally establish, for the first time, an extended dark matter halo surrounding an ultra-faint dwarf galaxy out to one kiloparsec, with a total mass of >10^7 solar masses. 

##### [Galaxy Alignments with Surrounding Structure in the Sloan Digital Sky Survey](https://arxiv.org/abs/2012.02254)
- #intrinsic_alignment
- 包含了关于计算星系alignment的有用过程
- 只用测光数据：We find that galaxies from the red sequence have a statistically significant tendency for their images to align parallel to the projected surrounding structure. Red galaxies brighter than the median of our sample (Mr<−21.05) have a mean alignment angle ⟨Φ⟩<45∘, indicating preferred parallel alignment
- Faint red星系的alignment较弱；Blue galaxies没有和大尺度结构align的迹象

##### [Detecting episodes of star formation using Bayesian model selection](https://arxiv.org/abs/2012.02285)
- #inference #bayesian 
- Bayesian model comparison frameworks can be used when fitting models to data in order to infer the appropriate model complexity in a data-driven manner: Our results indicate that the ratio of evidences (the Bayes factor) is able to identify the correct underlying model in the vast majority of cases.
- We also compare the Bayes factors obtained using the evidence to those obtained via the Savage-Dickey Density Ratio (SDDR), an analytic approximation which can be calculated using samples from regular Markov Chain Monte Carlo methods. We show that the SDDR ratio can satisfactorily replace a full evidence calculation provided that the sampling density is sufficient.

#### Others

##### [Constraining Mν with the Bispectrum II: The Total Information Content of the Galaxy Bispectrum](https://arxiv.org/abs/2012.02200)
- Massive neutrinos suppress the growth of structure on small scales and leave an imprint on large-scale structure that can be measured to constrain their total mass, Mν.
- bispectrum 可以解除2PCF在限制Mv上的简并
- We construct the Molino suite of 75,000 mock galaxy catalogs from the Quijote N-body simulations using the halo occupation distribution (HOD) model, which provides a galaxy bias framework well-suited for simulation-based approaches.

##### [Cosmic Shear Cosmology Beyond 2-Point Statistics: A Combined Peak Count and Correlation Function Analysis of DES-Y1](https://arxiv.org/abs/2012.02777)
- A joint cosmic shear analysis of peak-counts and the two-point shear correlation function
- In our simulation-based method we determine the expected DES-Y1 peak-count signal for a range of cosmologies sampled in four wCDM parameters (Ωm, σ8, h, w0).
- Accurate modelling for the impact of intrinsic alignments on the tomographic peak-count remains a challenge, currently limiting our exploitation of cross-correlated peak counts between high and low redshift bins.
- [`GPR_Emulator` - General code package to perform Gaussian process regression emulation. Comes with training and trial set examples](https://github.com/benjamingiblin/GPR_Emulator/)

##### [Simulated Observations of Multiphase Galactic Winds](https://arxiv.org/abs/2012.02212)
- Cholla模拟：a simulated interaction between a hot T∼10^7K supernova-driven wind and a cool T∼10^4K cloud of interstellar material
- 模拟观测：optical depth and covering fraction of six commonly observed ions (Si II, C II, Si IV, C IV, N V, and O VI) as a function of gas velocity.
- We find that the empirically computed values tend to underestimate the "true" value of τ for ions with high optical depth, and overestimate the "true" value of τ for ions with low optical depth, relative to the simulated data.

##### [Magnetic fields in elliptical galaxies: an observational probe of the fluctuation dynamo action](https://arxiv.org/abs/2012.02329)
- We propose that observations of magnetic fields in elliptical galaxies would directly probe the fluctuation dynamo action.
- 和旋涡星系比，主要优势在于：the conventional large-scale dynamo is absent and the fluctuation dynamo is responsible for controlling the magnetic field strength and structure.
- By considering turbulence injected by Type Ia supernova explosions and possible magnetic field amplification by cooling flows, we estimate expected magnetic field strengths of 0.2 − 1μG in quiescent elliptical galaxies.
- We analyse a sample of radio sources that exhibit the Laing-Garrington (LG) effect (radio polarization asymmetry in jets) and infer magnetic field strengths between 0.14 − 1.33μG for a uniform thermal electron density and between 1.36 − 6.21μG for the thermal electron density following the King profile.

##### [SDSS-IV MaNGA: galaxy gas-phase metallicity gradients vary across the mass-size plane](https://arxiv.org/abs/2012.02362)
- We find that gradients vary systematically such that above 10^10M⊙, smaller galaxies display flatter gradients than larger galaxies at a given stellar mass.
- This mass--size behaviour cannot be explained by instrumental effects, nor is it simply a reflection of known trends between gradients and morphology.

##### [Photometric Redshifts in the North Ecliptic Pole Wide Field based on a Deep Optical Survey with Hyper Suprime-Cam](https://arxiv.org/abs/2012.02421)
- NEP field的HSC+AKARI-IR, Spitzer, WISE数据的测光红移
- At z < 1.5, we achieve a weighted photo-z dispersion of σΔz/(1+z) = 0.053 with η = 11.3% catastrophic errors.

##### [Looking down the barrel of a multiphase quasar outflow at high redshift: VLT/X-shooter observations of the proximate molecular absorber at z=2.631 towards SDSS J001514+184212](https://arxiv.org/abs/2012.02487)
- We conjecture that we are witnessing different manifestations of a same AGN-driven multi-phase outflow, where approaching gas is intercepted by the line of sight to the nucleus.

##### [The Evolution of Magellanic-like Galaxy Pairs and The Production of Magellanic Stream Analogues in Simulations with Tides, Ram Pressure, and Stellar Feedback](https://arxiv.org/abs/2012.02716)
- 基于模拟：The dwarfs interact with each other through tidal forces, distorting their morphologies and triggering star formation. A stream is naturally produced as outflows, induced by feedback and interactions, are stretched by tidal forces.
- A combination of ongoing star-formation and entrained low-metallicity gas causes the stream to have a complex chemical structure, with an average metallicity that is generally lower than that of the dwarfs.

----

### Dec 8

#### Relevant / Important / Useful

##### [The ThreeHundred: the structure and properties of cosmic filaments in the outskirts of galaxy clusters](https://arxiv.org/abs/2012.02850)
- #galaxy_cluster #cluster_galaxies #cluster_cosmology 
- We have studied the filamentary structure in zoom-in resimulations centred on 324 clusters from The ThreeHundred project, focusing on differences between dark and baryonic matter. 
- We find that filaments increase their thickness closer to nodes and detect signatures of gas turbulence at a distance of ∼2h^{−1}Mpc from the cluster.
- We see that gas preferentially enters the cluster as part of filaments, and leaves the cluster centre outside filaments 但DM没有这种倾向，可能和turbulent环境有关

##### [Gaia Early Data Release 3: The astrometric solution](https://arxiv.org/abs/2012.03380)
- #gaia 
- For the first time in the Gaia data processing, colour-dependent calibrations of the line- and point-spread functions have been used for sources with well-determined colours from DR2.
- In the astrometric processing these sources obtained five-parameter solutions, whereas other sources were processed using a special calibration that allowed a pseudocolour to be estimated as the sixth astrometric parameter.
- The median uncertainty in parallax and annual proper motion is 0.02-0.03 mas at magnitude G = 9 to 14, and around 0.5 mas at G = 20. Extensive characterisation of the statistical properties of the solutions is provided, including the estimated angular power spectrum of parallax bias from the quasars.

#### Interesting / Keep in mind

##### [The Ursa Major Association of Galaxies. VI: A relative dearth of gas-rich dwarf galaxies](https://arxiv.org/abs/2012.03648)
- #dwarf_galaxy
- VLA-D观测来测量HIMF；The high-mass end is determined by a complementary, targeted WSRT survey, the low-mass end is determined by the blind VLA survey.
- The slope is significantly shallower than the slopes of the HIPASS and ALFALFA
- There is a relative lack of low HI mass galaxies in the Ursa Major region.

##### [Galaxy And Mass Assembly (GAMA): the interplay between galaxy mass, SFR and heavy element abundance in paired galaxy sets](https://arxiv.org/abs/2012.02922)
- #gama_survey
- We explore variations in SFR and Z from three point of views: multiplicity, pair separation and dynamics.
- For pairs with higher multiplicity, we find SFR enhancements from 0.025-0.15 dex, that would shift the M-SFR relation of single pairs by 27% to higher SFRs. 在金属丰度的效果上不明显
- We find SFR enhancements of up to 2 and 4 times with respect to their control sample, for major and minor pairs.

##### [Cosmic distributions of stellar tidal disruptions by massive black holes at galactic centers](https://arxiv.org/abs/2012.03811)
- #tidal_disruption_event
- We investigate the rates of stellar consumption by central MBHs and their cosmic distributions, including the effects of triaxial galaxy shapes in enhancing the reservoir of low-angular-momentum stars and incorporating realistic galaxy distributions. 三轴形状产生的TDE发生率的增加可能是比较显著的
- Only for MBH≲10^7Msun are the stellar consumption rates significantly higher in galaxies with steeper inner surface brightness profiles.
- 给出了一个基本的TDE的发生率：$\sim 3 \times 10^{-5} {\rm yr}^{-1} {\rm Mpc}^{-3}$ for 10^5-10^8 Msun SMBH
- The volumetric stellar consumption rates decrease with increasing redshift, and the decrease is relatively mild for MBH∼10^5-10^7Msun and stronger for higher MBH.

#### Others

##### [An observational determination of the evolving extragalactic background light from the multiwavelength HST/CANDELS survey in the Fermi and CTA era](https://arxiv.org/abs/2012.03035)
- 用一个非常完备和丰富的多波段星系数据集讨论EBL的SED演化：Our calculations use multiwavelength observations from the UV to the far-IR of a sample of approximately 150,000 galaxies detected up to z∼6
- These unprecedented resources allow us to derive the overall EBL evolution up to z∼6 and its uncertainties. Our results agree with cosmic observables estimated from galaxy surveys and γ-ray attenuation

##### [Tracing dark energy history with gamma ray bursts](https://arxiv.org/abs/2012.03392)
- We apply the Combo-relation to a sample of 174 gamma ray bursts to investigate possible evidence of evolving dark energy parameter w(z).
	- **Combo relation**, which is characterized by a small data scatter and involves prompt and afterglow GRB parameters (Bernardini et al. 2012; Margutti et al. 2013).
	- The “candle” is provided by the plateau X-ray afterglow luminosity L0, which is related to its rest-frame duration τ, to the late power-law decay index α of the X-ray afterglow luminosity, and to the rest-frame peak energy of the GRB prompt emission Ep,i 
	- $\log \left(\frac{L_{0}}{\mathrm{erg} / \mathrm{s}}\right)=\log \left(\frac{A}{\mathrm{erg} / \mathrm{s}}\right)+\gamma \log \left(\frac{E_{\mathrm{p}, \mathrm{i}}}{\mathrm{keV}}\right)-\log \left(\frac{\tau / \mathrm{s}}{|1+\alpha|}\right)$
- We show our new sample provides tighter constraints on Ωm since at z≤1.2 we see that w(z) agrees within 1σ with the standard value w=−1.
- We investigate the w(z) evolution through a piecewise formulation over seven redshift intervals. From our fitting procedure we show that at z≥1.2 the case w<−1 cannot be fully excluded, indicating that dark energy's influence is not negligible at larger z. 

##### [Identification of Cosmic Voids as Massive Cluster Counterparts](https://arxiv.org/abs/2012.03511)
- #cosmic_void
- Voids are the counterpart of massive clusters. 模拟验证，一对儿模拟，reverse initial condition
- We find a power-law scaling relation between the void size and the corresponding cluster mass. Voids with corresponding cluster mass above 10^15h−1M⊙ occupy ∼1% of the total simulated volume
- It is also found that the density profile of the identified voids follows a universal functional form.

##### [Identifying Cosmological Information in a Deep Neural Network](https://arxiv.org/abs/2012.03778)
- #machine_learning 
- We demonstrate the use of a convolutional neural network (CNN) for constraining the mass of dark matter particle. For this purpose, we perform a suite of N-body simulations with different dark matter particle masses to train CNN and estimate dark matter mass using a density-contrast map.

##### [Evolution of Galaxy Star Formation and Metallicity: Impact on Double Compact Objects Mergers](https://arxiv.org/abs/2012.02800)
- We find that when the Fundamental Metallicity Relation is exploited, the bulk of the star formation occurs at relatively high metallicities even at high redshift; the opposite holds when the Mass Metallicity Relation is employed, since in this case the metallicity at which most of the star formation takes place strongly decreases with redshift.

##### [SLITronomy: towards a fully wavelet-based strong lensing inversion technique](https://arxiv.org/abs/2012.02802)
- #strong_lensing
- As there is no reason for either the lens or the source to be simple, we need methods that both invert the lens equation with a large number of degrees of freedom and also enforce a well-controlled regularisation that avoids the appearance of spurious structures.
- Building on the Sparse Lens Inversion Technique (SLIT), in this work we present an improved sparsity-based method that describes lensed sources using wavelets and optimises over the parameters given an analytical lens mass profile.
- A new plug-in of `Lenstronomy`
	- [`SLITronomy` - Updated version of the Sparse Lens Inversion Technique (SLIT) for use within the lens modelling code lenstronomy](https://github.com/aymgal/SLITronomy)
	- [`pysap` - Python Sparse data Analysis Package](https://github.com/CEA-COSMIC/pysap)

##### [Multi-wavelength Selected Compton-thick AGNs in Chandra Deep Field-South Survey](https://arxiv.org/abs/2012.03233)
- We select 51 AGNs with abundant multi-wavelength data. Using the method of the mid-infrared (mid-IR) excess, we select hitherto unknown 8 CT AGN candidates in our sample.
- Seven of these candidates can confirm as CT AGN based on the multi-wavelength identification approach, and a new CT AGN (XID 133) is identified through the mid-IR diagnostics.
- We also find that CT AGNs have a higher Eddington ratio than non-CT AGNs, and that both CT AGNs and non-CT AGNs show similar properties of host galaxies.

##### [The properties and environment of very young galaxies in the local Universe](https://arxiv.org/abs/2012.03880)
- We analyzed 280 000 SDSS spectra to identify a surprisingly large sample of more massive Very Young Galaxies (VYGs), defined to have formed at least 50% of their stellar mass within the last 1 Gyr.
- We find that VYGs tend to have higher surface brightness and to be more compact, dusty, asymmetric, and clumpy than the control sample.
- These results suggest that gas-rich interactions and mergers are the main mechanisms responsible for the recent triggering of star formation in low-redshift VYGs

----

### Dec 9

#### Relevant / Important / Useful

##### [Ultramassive black holes in the most massive galaxies: MBH−σ versus MBH−Rb](https://arxiv.org/abs/2012.04471)
- #early_type_galaxy #smbh #massive_galaxy 
- Our sample of 144 galaxies with dynamically determined MBH encompasses 24 core-Sersic galaxies, thought to be products of gas-poor mergers, and reliably identified based on high-resolution HST imaging
- We find that MBH correlates remarkably well with Rb such that $M_{\rm BH} \propto R_{b}^{1.20 \pm 0.14}$
- Separating the sample into Sersic, normal-core and large-core galaxies, we find that Sersic and normal-core galaxies jointly define a single log-linear MBH−σ relation
- Large-core spheroids have magnitudes MV≤−23.50 mag, half-light radii Re > 10 kpc and are extremely massive M∗≥10^12M⊙

#### Interesting / Keep in mind

##### [GLACE survey: galaxy activity in ZwCl0024+1652 cluster from strong optical emission lines](https://arxiv.org/abs/2012.04422)
- #cluster_galaxies 
- ZwCl0024+1652 galaxy cluster at z∼0.4
- Using Hα priors, we identified [OIII] and Hβ in 35 (∼20%) and 59 (∼34%) sources, respectively, with 21 of them having both emission lines, and 20 having in addition [NII].
- We observed that the cluster centre to ∼1.3Mpc is devoid of SF galaxies and AGN
- We observed a strong decline in SF fraction in high M∗, confirming that star formation is highly suppressed in high-mass cluster galaxies.

##### [A massive blow for ΛCDM − the high redshift, mass, and collision velocity of the interacting galaxy cluster El Gordo contradicts concordance cosmology](https://arxiv.org/abs/2012.03950)
- #galaxy_cluster 
- El Gordo是两个质量很大的cluster的高速碰撞，这个碰撞速度在z=0.87对LCDM模型是个挑战
- 在一个6 h^{-1} Gpc的Jubilee模拟中找类似的系统：Detecting one pair with its mass and redshift rules out ΛCDM cosmology at 6.16σ.
- We also use the results of Kraljic & Sarkar (2015) to show that the Bullet Cluster is in 2.78σ tension once the sky coverage of its discovery survey is accounted for
- Related to the work by [Congyao Zhang, Qingjuan Yu, and Youjun Lu](https://iopscience.iop.org/article/10.1088/0004-637X/813/2/129)

##### [Out of sight, out of mind? The impact of correlated clustering in substructure lensing](https://arxiv.org/abs/2012.03958)
- #strong_lensing 
- We examine the role of local, lens-proximate clustering in boosting the lensing probability relative to contributions from substructure and unclustered line-of-sight (LOS) halos.
- We demonstrate that clustering in the vicinity of the lens host produces a clear enhancement relative to an assumption of unclustered halos that persists to >20Rvir
- This enhancement exceeds estimates that use a two-halo term to account for clustering, particularly within 2−5Rvir.
- We find that local clustering boosts the expected count of 10^9 M⊙ perturbing halos by ∼35% compared to substructure alone, a result that will significantly enhance expected signals for low-redshift (zl≃0.2) lenses, where substructure contributes substantially compared to LOS halos.
- Lens星系的指向也对信号有影响

##### [Simulating intergalactic gas for DESI-like small scale Lymanα forest observations](https://arxiv.org/abs/2012.04008)
- #desi #ssst_cos #emulator 
- A main summary statistic derived from those measurements is the one-dimensional power spectrum, P1D, of the Lyα absorption. 但数值模拟非常昂贵
- Datasets from upcoming surveys such as DESI will push observational accuracy near the 1%-level and probe even smaller scales.
- We use a Gaussian process emulation scheme to reduce the number of simulations required for exploration of parameter space without sacrificing the model accuracy.
- We advocate for the usage of **adaptive sampling** schemes as opposed to using a fixed Latin hypercube design.
- [`Nyx` - An adaptive mesh, N-body hydro cosmological simulation code](https://github.com/AMReX-Astro/Nyx)

#### Others

##### [From the Fermi blazar sequence to the relation between Fermi blazars and gamma-ray Narrow-line Seyfert 1 Galaxies](https://arxiv.org/abs/2012.04286)

##### [Galaxy shape statistics in the effective field theory](https://arxiv.org/abs/2012.04114)
- #intrinsic_alignment 
- The general bias expansion for galaxy sizes and shapes in three dimensions has been recently described by Vlah, Chisari & Schmidt using the general perturbative effective field theory (EFT) framework
- We present a formalism that uses the properties of spherical tensors to project galaxy shapes onto the observed sky in the flat-sky approximation and compute the two-point functions at next-to-leading order as well as the leading-order three-point functions of galaxy shapes and number counts. 
- **We find that that nonlinear intrinsic alignment contributions to galaxy shape correlations become relevant at angular wavenumbers l≳100.**

##### [The Astrophysical Distance Scale III: Distance to the Local Group Galaxy WLM using Multi-Wavelength Observations of the Tip of the Red Giant Branch, Cepheids, and JAGB Stars](https://arxiv.org/abs/2012.04536)
- To help elucidate possible sources of systematic error causing the tension, we show in this study the recently developed distance indicator, the J-region Asymptotic Giant Branch (JAGB) method (arXiv:2005.10792), can serve as an independent cross-check and comparison with other local distance indicators.
- Using the Local Group galaxy, WLM we present distance comparisons between the JAGB method, a TRGB measurement at near-infrared (JHK) wavelengths, a TRGB measurement in the optical I band, and a multi-wavelength Cepheid period-luminosity relation determination.
- All four methods are in good agreement, confirming the local self-consistency of the four distance scales at the 3% level, and adding confidence that the JAGB method is as accurate and as precise a distance indicator as either of the other three astrophysically-based methods.
- **JAGB method** [[Asymptotic Giant Branch]]
	- JAGB stars are Thermally-Pulsating Asymptotic Giant Branch (TP-AGB) stars with considerable amounts of carbon in their atmospheres (i.e., carbonto-oxygen ratios of C/O> 1) (Habing & Olofsson 2003).
	- JAGB stars also undergo ‘dredge-up’ events, where with each thermal pulse the convective envelope penetrates into deeper and deeper layers of the star’s interior.
	- During the third dredge-up phase (and beyond), the convective envelope of the star penetrates deep enough that it encounters carbon, produced by the He-burning shell, and brings that enriched material to the surface
	- For the younger, more massive AGB stars (1.6 × 10^8 years), the temperature at the bottom of the convective envelope becomes so hot that during the third dredge-up phase, the recently-formed carbon is quickly converted into nitrogen before it can be convected to the surface. This places an upper limit on the luminosity of a JAGB star (Iben 1973; Sackmann et al. 1974).
	- For older, less massive AGB stars, the third dredge-up phase (and beyond) becomes ineffective in transporting carbon to the surface. This imposes a lower limit on the luminosities of stars entering the JAGB region (Iben & Renzini 1983)
	- These theoretical limits are reflected in the observed properties JAGB stars, which are well-defined in their near-infrared (NIR) colors and luminosities. JAGB stars are redder and quite distinct from the bluer oxygen-rich AGB stars, especially at near and mid-infrared wavelengths: a direct result of the large amounts of carbon in their atmospheres (Marigo & Girardi 2007).
	- 所以JAGB stars有明确的绝对星等和颜色的界限: A review of carbon stars by Battinelli & Demers (2005) demonstrated that the mean luminosity of the distribution of JAGB stars is relatively constant from galaxy to galaxy

##### [Responses of Halo Occupation Distributions: a new ingredient in the halo model & the impact on galaxy bias](https://arxiv.org/abs/2012.04640)
- We introduce and study HOD response functions $R_O^g$ that describe the response of the HODs to long-wavelength perturbations $O$. The linear galaxy bias parameters $b_O^g$ are a weighted version of $b_O^h + R_O^g$, where $b_O^h$ is the halo bias, but the contribution from $R_O^g$ is routinely ignored in the literature.
- The $R_O^g$ are not negligible in general and their size should be estimated on a case-by-case basis.

##### [Resolved galactic superwinds reconstructed around their host galaxies at z>3](https://arxiv.org/abs/2012.03959)
- 被前景星系团放大的两个高红移Lya arcs：The Lya nebulae revealed in deep MUSE observations exhibit a double-peak profile with a dominant red peak that indicates expansion/outflowing motions
	- One of the arcs stretches over 1' around the Einstein radius of the cluster, resolving the velocity field of the line-emitting gas on kpc scales around a group of three star-forming galaxies of 0.3-1.6L* at z=3.038.
- All three galaxies in the z=3.038 group exhibit prominent damped Lya absorption (DLA) and several metal absorption lines, in addition to nebular emission lines such as HeII1640 and CIII]1906,1908
- Lya面亮度在星系中心更低，说明可能有dusty outflowing cones
- There are significant spatial variations in the Lya line profile, consistent with the presence of a steep negative velocity gradient in a continuous flow of high column density gas from star-forming regions into a low-density halo environment.

##### [The Massive M31 Cluster G1: Detailed Chemical Abundances from Integrated Light Spectroscopy](https://arxiv.org/abs/2012.03971)
- #globular_cluster #compact_dwarfs
- G1，质量，椭率，位置都与former nuclear star cluster的形成机制符合
- G1 is found to be a moderately metal-poor cluster, with [Fe/H]=-0.98+/-0.05.
- G1 also shows signs of alpha-enhancement (based on Mg, Ca, and Ti) and lacks the s-process enhancements seen in dwarf galaxies (based on comparisons of Y, Ba, and Eu), indicating that it originated in a fairly massive galaxy. 
- G1 also exhibits signs of Na and Al enhancement, a unique signature of GCs 和GC的形成也有关联
- G1's high [Na/Fe] also extends previous trends with cluster velocity dispersion to an even higher mass regime, implying that higher mass clusters are more able to retain Na-enhanced ejecta.
- [`linemake` - stellar absorption linelist generator](https://github.com/vmplacco/linemake)

##### [Sphenix: Smoothed Particle Hydrodynamics for the next generation of galaxy formation simulations](https://arxiv.org/abs/2012.03974)
- We introduce the Sphenix SPH scheme, which was designed with three key goals in mind: to work well with sub-grid physics modules that inject energy, be highly computationally efficient (both in terms of compute and memory), and to be Lagrangian.
- Sphenix is shown to solve many difficult test problems for traditional SPH, including fluid mixing and vorticity conservation, and it is shown to produce convergent behaviour in all tests where this is appropriate.

##### [The Origin of the Dust Extinction Curve in Milky Way-like Galaxies](https://arxiv.org/abs/2012.03978)
- 建立一个尘埃颗粒大小分布的演化模型来理解MW消光率的起源
- Galaxies in our cosmological model with masses comparable to the Milky Way's at z~0 exhibit a diverse range of extinction laws, though with slopes and bump strengths comparable to the range observed in the Galaxy
- The progenitors of the Milky Way have steeper slopes, and only flatten to slopes comparable to the Galaxy at z≈1 主要是因为在晚期高金属丰度环境中尘埃颗粒增长加快
- The UV bump strengths depend primarily on the graphite to silicate ratio, and remain broadly constant in MW-like galaxies between z=3 and z=0
- 模型已经可以解释低金属丰度星系，如LMC，SMC中较陡的消光曲线；但bump strength match的不好，可能是因为模型里面石墨和硅尘埃的演化是同步的

##### [On the physics of UV absorption lines and their relations with Lyman continuum escape fractions](https://arxiv.org/abs/2012.03984)
- Low-ionization state absorption lines are a common feature in the spectrum of galaxies, showing a diversity of strengths and shapes. Since these lines indicate the presence of neutral gas in front of the stars, they have been proposed to carry information on the escape of ionizing radiation from galaxies. 本文看哪些物理过程影响这些吸收线的轮廓; 看能否用这些线来预测光子逃逸比例
- 基于模拟：mock CII 1334 and LyB lines of a virtual galaxy at redshift 3 as seen from many directions of observation.
- 吸收线主要受到气体速度和尘埃的影响；和逃逸比例关系不大；逃逸比例随LOS变化很大
- After correcting the continuum for attenuation by dust to recover the intrinsic continuum, the residual flux of CII 1334 correlates well with the escape fraction for directions with a dust corrected residual flux larger than 30%.
- [RASCAS (for RAdiative SCattering in Astrophysical Simulations)](http://rascas.univ-lyon1.fr/)

##### [Evidence for the Accretion of Gas in Star-Forming Galaxies: High N/O Abundances in Regions of Anomalously-Low Metallicity](https://arxiv.org/abs/2012.04073)
- 基于MaNGA: We measure both the O/H and N/O abundance ratios in regions previously identified as having anomalously low values of O/H
- The N/O vs. O/H plane indicate that they have been created through the mixing of disk gas having higher metallicity with accreted gas having lower metallicity.
- Accretion of metal-poor gas can probably sustain star formation in present-day late-type galaxies.


----

### Dec 10

#### Relevant / Important / Useful

##### [Globular Cluster Systems of Relic Galaxies](https://arxiv.org/abs/2012.04783)
- #globular_cluster #red_nugget #early_type_galaxy 
- 15个massive relic星系的GC系统， WFC3观测
- We find lower specific frequencies (SN<2.5 with a median of SN=1) than ETGs of comparable mass. This is consistent with a scenario of rapid, early dissipative formation, with relatively low levels of accretion of low-mass, high-SN satellites. 
- The GC half-number radii are compact, but follow the relations found in normal ETGs.
- We identify an anticorrelation between the specific angular momentum (lambda_R) of the host galaxy and the (I-H) colour distribution width of their GC systems GC系统的颜色分布和星系的单位角动量有反相关

#### Interesting / Keep in mind

##### [Joint Suzaku and Chandra observations of the MKW4 galaxy group out to the virial radius](https://arxiv.org/abs/2012.05160)
- #galaxy_group
- Its entropy profile follows a power-law of ∝r^1.1 between R500 and R200 in all directions, as expected from the purely gravitational structure formation model.
- The well-behaved entropy profiles at the outskirts of MKW4 disfavor the presence of gas clumping or thermal non-equilibrium between ions and electrons in this system.
- We note that the enclosed gas fractions at R200 are systematically smaller for groups than for clusters from existing studies in the literature.
	- Shallower gravitational potential well may make them more vulnerable to baryon losses due to AGN feedback or galactic winds.
	
##### [MusE GAs Flow and Wind (MEGAFLOW) VI. A study of CIV and MgII absorbing gas surrounding [OII] emitting galaxies](https://arxiv.org/abs/2012.04935)
- #CGM #bayesian #inference 
- MUSE and UVES observations of 22 quasar fields selected to contain strong MgII absorbers
- Bayesian logistic regression method on unbinned data to estimate the covering fraction of MgII and CIV
	- The covering fractions of CIV (MgII) absorbers with mean Wr≈0.7{\AA} (1.0{\AA}), exceeds 50% within 30 (45) kpc, with a mild redshift evolution
- For absorption systems that have CIV but not MgII, we find in 80% of the cases no [OII] counterpart. This may indicate that the CIV, in these cases, come from the intergalactic medium (IGM), i.e. beyond 250 kpc, or that it is associated with lower-mass or quiescent galaxies.

##### [Not all peaks are created equal: the early growth of Supermassive Black Holes](https://arxiv.org/abs/2012.04714)
- #smbh 
- Constrained Gaussian realization technique to study the early growth of SMBH in simulation: 看黑洞和initial density peaks on large scales, ~1 Mpc/h的关系
- We find that initial density peaks with high compactness and low tidal field induce the most rapid BH growth at early epochs.
	- Compact density peaks with a more spherical large scale matter distribution lead to the formation of high density gas clumps in the centers of halos, and thus boost early BH accretion.
- Such initially compact density peaks in low tidal field regions also lead to a more compact BH host galaxy morphology. This can explain the tight correlation between BH growth and host galaxy compactness seen in observations.
- [`gaussianCR` - implementation of the constrained gaussian realization](https://github.com/yueyingn/gaussianCR)

##### [Black Hole Mass Measurements of Radio Galaxies NGC 315 and NGC 4261 Using ALMA CO Observations](https://arxiv.org/abs/2012.04669)
- #smbh
- ALMA观测：CO(2−1) and CO(3−2) emission at 0.2''−0.3'' resolution
- The data resolve CO emission that extends within their black hole (BH) spheres of influence (rg), tracing regular Keplerian rotation down to just tens of parsecs from the BHs
- The BH masses are broadly consistent with the relations between BH masses and host galaxy properties. 
- These are among the first ALMA observations to map dynamically cold gas kinematics well within the BH-dominated regions of radio galaxies, resolving the respective rg by factors of ∼5−10.

#### Others

##### [Euclid: Forecasts for k-cut 3×2 Point Statistics](https://arxiv.org/abs/2012.04672)
- #csst
- k-cut cosmic shear has recently been proposed as a method to optimally remove sensitivity to these scales while preserving usable information.
- Fisher matrix analysis: we assess the degradation in constraining power for different k-cuts.
- We find that taking a k-cut at 2.6 h Mpc−1 yields a dark energy Figure of Merit (FOM) of 1018. This is comparable to taking a weak lensing cut at ℓ=5000 and a galaxy clustering and galaxy-galaxy lensing cut at ℓ=3000 in a traditional 3×2 point analysis.

##### [First multi-redshift limits on post-Epoch of Reionization (post-EoR) 21 cm signal from z = 1.96 - 3.58 using uGMRT](https://arxiv.org/abs/2012.04674)
- Measurement of fluctuations in diffuse HI 21 cm background radiation from the post-reionization epoch (z < 6) is a promising avenue to probe the large-scale structure of the Universe and understand the evolution of galaxies
- ELAIS-N1观测：we find the most stringent upper limits on the spherically averaged 21 cm power spectra at k~1.0 Mpc^-1

##### [Star-Gas Misalignment in Galaxies: II. Origins Found from the Horizon-AGN Simulation](https://arxiv.org/abs/2012.04659)
- Horizon-AGN模拟中质量较大的星系中恒星和气体成分misalignment: We have identified four main formation channels of misalignment and quantified their level of contribution: 
	- Mergers (35%), interaction with nearby galaxies (23%), interaction with dense environments or their central galaxies (21%), and secular evolution including smooth accretion from neighboring filaments (21%).
	- 而且对动力学扰动气体更脆弱，misalignment主要是气体的旋转主轴的改变造成的
- The decay timescale of the misalignment shows a strong anti-correlation with the kinematic morphology (V/σ) and the cold gas fraction of the galaxy.
	- 星系越是旋转主导，或者冷气体越多，misalignment消失的时标也越短

##### [Galaxies within galaxies in the TIMER survey: stellar populations of inner bars are scaled replicas of main bars](https://arxiv.org/abs/2012.04661)
- #stellar_population 
- MUSE观测星系的inner bar: The results indicate that inner bars can be distinguished based on their stellar population properties alone.
	- Inner bar: 金属丰度升高，[alpha/Fe]低
	- Although they exhibit slightly younger stellar ages compared to the nuclear disc, the typical age differences are small,
	- 可以在棒端看到年轻的星族，结构可能和bar ansae有关
- Radial profiles of metallicity and [α/Fe] enhancements are flat along the inner bar major axis, but show significantly steeper slopes along the minor axis.
- Inner bars appear to be scaled down versions of the main bars seen in galaxies.

##### [Auto-identification of unphysical source reconstructions in strong gravitational lens modelling](https://arxiv.org/abs/2012.04665)
- We consider a Convolutional Neural Network (CNN) that analyses the outputs of semi-analytic methods which parametrically model the lens mass and linearly reconstruct the source surface brightness distribution. 
	- We show the unphysical source reconstructions that arise as a result of incorrectly initialised lens models can be effectively caught by our CNN.
- The CNN predictions can be used to automatically re-initialise the parametric lens model, avoiding unphysical source reconstructions.

##### [MusE GAs FLOw and Wind (MEGAFLOW) VII: A NOEMA pilot program to probe molecular gas in galaxies with measured circumgalactic gas flows](https://arxiv.org/abs/2012.04667)
- Probe the molecular gas reservoirs of six z=0.6−1.1 star-forming galaxies whose circumgalactic medium has been observed in absorption along quasar lines-of-sight
- This program is motivated by testing the quasi equilibrium model and the compaction scenario describing the evolution of galaxies along the main sequence of star formation, which imply tight relations between the gas content, the star formation activity, and the amount of gas flowing in and out.
- Extending the sample to more galaxies and deeper observations will enable to quantify how the molecular gas fraction and depletion time depend on the inflow and ouflow rates.

##### [A Large Population of Luminous Active Galactic Nuclei Lacking X-ray Detections: Evidence for Heavy Obscuration?](https://arxiv.org/abs/2012.04668)
- 大量有红外探测，但是没有X-ray detection的AGN; 可能是尘埃遮挡极其严重的星系
- Using the ratio of intrinsic-to-observed X-ray luminosity (RLX), we find a significant fraction of sources with column densities approaching NH> 10^{24} cm−2, suggesting that multiwavelength observations are necessary to account for the population of heavily obscured AGNs.
- We simulate the underlying NH distribution for the X-ray non-detected sources in our sample through survival analysis, and confirm the presence of AGN activity via X-ray stacking. 

##### [A search for dust and molecular gas in enormous Lyα nebulae at z≈2](https://arxiv.org/abs/2012.04675)
- IRAM Plateau de Bure Interferometer observations of the enormous Lyα nebulae 'Slug' (z=2.282) and 'Jackpot' (z=2.041).
- Our data reveal bright, synchrotron emission associated with the two radio-loud AGN embedded in the targeted nebulae, as well as molecular gas, as traced via the CO(3-2) line, in three galaxies
- Our observations place limits on the molecular gas emission in the nebulae: The molecular gas surface density is ΣH2<12−25 M⊙ pc−2 for the Slug nebula and ΣH2<34−68 M⊙ pc−2 for the Jackpot nebula.
	- Are consistent with the expected molecular gas surface densities, as predicted via photoionization models of the rest-frame UV line emission in the nebulae, and via Lyα absorption in the Jackpot nebula. 

##### [Lyman-alpha spectroscopy of extreme [OIII] emitting galaxies at z≃2−3: Implications for Lyα visibility and LyC leakage at z>6](https://arxiv.org/abs/2012.04697)
- #ssst_sci #ssst_gal
- MMT and Magellan 观测 2<z<3的有很高的[OIII] + Hbeta EW的星系的Lya发射线
	- 在高红移星系中，高[OIII] + Hbeta EW意味着很高的Lya探测率
- Our results demonstrate that strong Lyα emission (EW >20 AA) becomes more common in galaxies with larger [OIII]+Hβ EW, reflecting a combination of increasingly efficient ionizing photon production and enhanced transmission of Lyα. 
- Among the galaxies with the most extreme [OIII]+Hβ emission (EW ∼1500 AA), we find that strong Lyα emission is not ubiquitous, with only 50% of our population showing Lyα EW >20
- Edge-on的系统的Lya探测率更低

##### [The ALMaQUEST Survey: V. The non-universality of kpc-scale star formation relations and the factors that drive them](https://arxiv.org/abs/2012.04771)
- rSK: resolved Schmidt-Kennicutt relation
- rSFMS: resolved SF main sequence
- rMGMS: resolved molecular gas main sequence
- Our results therefore indicate that the rSK and rMGMS are independent relations, whereas the rSFMS is a result of their combination.

##### [The ALMaQUEST Survey: VI. The molecular gas main sequence of "retired" regions in galaxies](https://arxiv.org/abs/2012.04772)
- 在有空间分辨的前提下看分子气体的“MS”：恒星面密度和H2分子气体面密度的关系 (rMGMS)
- We find that retired spaxels form a rMGMS that is distinct from that of star-forming spaxels, offset to lower Sigma_H2 at fixed Sigma_* by a factor of ~5.
- Molecular gas is detected in 40-100% of retired spaxels in the eight galaxies in our sample. Both the star-forming and retired rMGMS show a diversity in normalization from galaxy-to-galaxy.
- We conclude that quenching is associated with a depletion (but not absence) of molecular gas via a mechanism that typically begins in the centre of the galaxy.

##### [The Hierarchical Structure of Galactic Haloes: Classification and characterisation with Halo-OPTICS](https://arxiv.org/abs/2012.04823)
- Ordering Points To Identify Clustering Structure (OPTICS), a hierarchical clustering algorithm well-known to be a robust data-miner
- Halo-OPTICS, an algorithm designed for the automatic detection and extraction of all meaningful clusters between any two arbitrary sizes
- We conclude that Halo-OPTICS is a robust hierarchical halo finder, although its determination of lower spatial-density features such as the tails of streams could be improved with the inclusion of extra localised information such as particle kinematics and stellar metallicity into its distance metric.

##### [Large-scale magnetic field structure of NGC 3627 based on magnetic vector map](https://arxiv.org/abs/2012.04889)
- The structure of the magnetic field was well aligned with the spiral arm
- NGC 3627 has a mode of two spiral arms that were clearly visible in an optical image. The ratio of the mode of spiral arms to that of magnetic field is 2:1. In terms of NGC 3627, the large-scale magnetic field may be generated via the parametric resonance induced by the gravitational potential of the spiral arms.

##### [The kpc Scale Fe Kα Emission in the Compton Thin Seyfert 2 Galaxy NGC 4388 resolved by Chandra](https://arxiv.org/abs/2012.04900)
- Three extended X-ray structures around the nucleus on kpc scale are well imaged
- Significant differences in equivalent width of the Fe Kα emission line are found for the nuclear and extended regions, which could be ascribed to different column densities or scattering angles with respect to the line of sight, rather than variations in iron abundances.
- The morphology implies that the kpc-scale radio outflow may have compressed the interstellar gas and produced clumps working as the reflector to enhance line emission.
- Using [OIV] emission as a proxy of the AGN intrinsic luminosity, we find that both of the extended Fe Kα emission and reflection continuum are linearly correlated with the [OIV] luminosity

##### [Dust Reverberation Mapping of Z229-15](https://arxiv.org/abs/2012.04906)
- Considering the lag between V and Ks bands to represent the inner edge of the dust torus, the torus in Z229-15 lies at a distance of 0.017 pc from the central ionizing continuum.
- This is smaller than that expected from the radius luminosity (R-L) relationship


### Dec 11

#### Relevant / Important / Useful

##### [Globular Cluster Systems of Relic Galaxies](https://arxiv.org/abs/2012.04783)
- #red_nugget #globular_cluster #massive_galaxy 
- HST I-band  + H-band 观测：15 massive, compact early-type galaxies (ETGs), 13 of which have already been identified as good relic galaxy candidates 
- We find lower specific frequencies (SN<2.5 with a median of SN=1) than ETGs of comparable mass. This is consistent with a scenario of rapid, early dissipative formation, with relatively low levels of accretion of low-mass, high-SN satellites
- We identify an anticorrelation between the specific angular momentum (lambda_R) of the host galaxy and the (I-H) colour distribution width of their GC systems. 角动量越高，说明dissipative过程越剧烈，GC的颜色分布就越窄

##### [MIGHTEE: Are giant radio galaxies more common than we thought?](https://arxiv.org/abs/2012.05759)
- #massive_galaxy 
- MeerKAT在COSMOS field里找到两个新的GRGs：They have redshifts of z=0.1656 and z=0.3363 and physical sizes of 2.4Mpc and 2.0Mpc
- The GRGs occupy a unpopulated region of radio power - size parameter space. 
- 弥散的射点辐射在之前的VLA数据中看不到；说明GRG的数密度可能显著被低估了

#### Interesting / Keep-in-mind

##### [Hybrid analytic and machine-learned baryonic property insertion into galactic dark matter haloes](https://arxiv.org/abs/2012.05820)
- #machine_learning #galaxy_halo #baryonic_effect 
- We explore the merging of an extended version of the equilibrium model, an analytic formalism describing the evolution of the stellar, gas, and metal content of galaxies, into a machine learning framework.
- We demonstrate that this novel hybrid system enables the fast completion of dark matter-only information by mimicking the properties of a full hydrodynamic suite to a reasonable degree, and discuss the advantages and disadvantages of hybrid versus machine learning-only frameworks.
- 用的机器学习算法：Extremely randomised tree ensembles

##### [Detection of large-scale X-ray bubbles in the Milky Way halo](https://arxiv.org/abs/2012.05840)
- We report soft-X-ray-emitting bubbles that extend approximately 14 kiloparsecs above and below the Galactic centre and include a structure in the southern sky analogous to the North Polar Spur. The sharp boundaries of these bubbles trace collisionless and non-radiative shocks, and corroborate the idea that the bubbles are not a remnant of a local supernova but part of a vast Galaxy-scale structure closely related to features seen in gamma-rays.

#### Others

##### [Learning the Evolution of the Universe in N-body Simulations](https://arxiv.org/abs/2012.05472)
- #machine_learning 
- We employ a deep neural network model to predict the nonlinear N-body simulation at an intermediate time step given two widely separated snapshots. Our results outperform the cubic Hermite interpolation benchmark method in interpolating N-body simulations

##### [The evolution of the low-density HI intergalactic medium from z=3.6 to 0: Data, transmitted flux and HI column density](https://arxiv.org/abs/2012.05861)
- HST/COS+STIS数据的综合分析：Two flux statistics at 0<F<1, the mean HI flux and the flux probability distribution function (PDF), show that considerable evolution occurs from z=3.6 to z=1.5, after which it slows down to become effectively stable for z<0.5.
- However, there are large sightline variations. 
- High-N(HI) absorbers evolve more rapidly than low-N(HI) absorbers to decrease in number or cross-section with time.

##### [Binning is Sinning (Supernova Version): The Impact of Self-Calibration in Cosmological Analyses with Type Ia Supernovae](https://arxiv.org/abs/2012.05900)

##### [Elliptical accretion disk as a model for TDEs](https://arxiv.org/abs/2012.05552)
- #tidal_disruption_event 
- we further investigate the properties of the elliptical accretion disk of nearly uniform distribution of eccentricity within disk plane. 椭圆吸积盘的动力学结构不同，对应的TDE的SED也不同
- Elliptical accretion disks predict sub-Eddington luminosities and emit mainly at the photon-trapping radius of thousands of Schwarzschild radii with a blackbody spectrum of nearly single temperature of typically about 3x10^4 K.

##### [Thermal Instability and Multiphase Gas in the Simulated Interstellar Medium with Conduction, Viscosity and Magnetic Fields](https://arxiv.org/abs/2012.05252)

##### [Revisiting the Integrated Star Formation Law. II. Starbursts and the Combined Global Schmidt Law](https://arxiv.org/abs/2012.05363)
- 153 nearby non-starbursting disk galaxies


##### [Near infrared and optical continuum emission region size measurements in the gravitationally lensed quasars Q0957+561 and SBS0909+532](https://arxiv.org/abs/2012.05856)
- 3波段探测两个SL-QSO的显著微引力透镜效应，可以限制黑洞吸积盘半径和波长的power-law关系


### Dec 14

#### Relevant / Important / Useful

##### [A machine learning approach to galaxy properties: Joint redshift - stellar mass probability distributions with Random Forest](https://arxiv.org/abs/2012.05928)
- #machine_learning #inference #photo-z
- 基于RF的photo-z和恒星质量联合推断：we use the Dark Energy Survey (DES), combined with the COSMOS2015 catalogue for redshifts and stellar masses.
- We validate our joint PDFs for 10,699 test galaxies by utilising the copula probability integral transform (copPIT) and the Kendall distribution function, and their univariate counterparts to validate the marginals.
- As part of this work we have developed GALPRO, a highly intuitive and efficient Python package to rapidly generate multivariate PDFs on-the-fly. GALPRO is documented and available for researchers to use in their cosmology and galaxy evolution studies at
- [`galpro` - Random Forest based code for estimating multivariate PDF of redshift and stellar mass](https://galpro.readthedocs.io/)

##### [The Fundamental Plane of Massive Quiescent Galaxies at z~2](https://arxiv.org/abs/2012.05931)
- #massive_galaxy #early_type_galaxy #red_nugget 
- For a very massive, log(M∗/M⊙)>11.26, subset of 8 quiescent galaxies at z>2, from Stockmann et al. (2020), we show that they cannot passively evolve to the local Coma cluster relation alone and must undergo significant structural evolution to mimic the sizes of local massive galaxies.
- Modeling the luminosity evolution from minor merger added stellar populations favors a history of merging with "dry" quiescent galaxies.

##### [Gaia Early Data Release 3 -- Catalogue validation](https://arxiv.org/abs/2012.06242)
- #gaia
- The goal of this paper is to describe the validation results in terms of completeness, accuracy, and precision for the Gaia EDR3 data and to provide recommendations for the use of the catalogue data. 
- Gaia EDR3 represents a major step forward, compared to Gaia DR2, in terms of precision, accuracy, and completeness for both astrometry and photometry.

#### Interesting / Keep-in-mind

##### [Statistical methods on Type Ia supernova luminosity evolution](https://arxiv.org/abs/2012.06215)
- #inference 基于Bayesian的统计相关分析
- 看SNIa的peak光度是否和其所在星族的年龄有关系: Our analysis follows a principled approach that properly accounts for regression dilution and critically (and unlike both prior studies) utilises the Bayesian-model-produced SN environment age estimates (posterior samples) instead of point estimates.
- We find the Pearson correlation between the HR and local (global) age to be in excess of 4σ (3σ).

##### [Multi-dimensional population modelling using frbpoppy: magnetars can produce the observed Fast Radio Burst sky](https://arxiv.org/abs/2012.06396)
- Here we show that multi-dimensional FRB population synthesis can find a single, self-consistent population of FRB sources that can reproduce the real-life results of the major ongoing FRB surveys.
- The characteristics of our best-fit model for one-off FRBs agree with a population of magnetars. We extrapolate this model and predict the number of FRBs future surveys will find.
- [`frbpoppy` - Fast Radio Burst Population Synthesis in Python](https://github.com/davidgardenier/frbpoppy)

#### Others

##### [On the relationship between Type Ia supernova luminosity and host-galaxy properties](https://arxiv.org/abs/2012.06217)
- An analysis of ~200 low-redshift SNe Ia in which we measure the separation of Hubble residuals (HR; as probes of luminosity) between two host-galaxy morphological types (as a probe of both age and mass).
- Our results are consistent with the previously known HR-mass step (or slope), but inconsistent with newly proposed HR-age slopes, which we find to significantly overstate what amounts only to a slight trend.
- While our result clearly rejects the recently proposed large HR-age slope, the correlations between mass, age, morphology, and HR values are evident, keeping the HR-age slope relevant as an interesting topic for discussion.

##### [Sufficiency of a Gaussian power spectrum likelihood for accurate cosmology from upcoming weak lensing surveys](https://arxiv.org/abs/2012.06267)
- We investigate whether a Gaussian likelihood is sufficient to obtain accurate parameter constraints from a Euclid-like combined tomographic power spectrum analysis of weak lensing, galaxy clustering and their cross-correlation.
- Our results indicate that a Gaussian likelihood will be sufficient for robust parameter constraints with power spectra from Stage IV weak lensing surveys.
- Wishart distribution:
	- For correlated Gaussian fields observed on the full sky, the set of observed 𝐶ℓs follows a Wishart distribution, independently for each ℓ (see Percival & Brown 2006 for a derivation in the case of cosmic microwave background temperature and polarisation)
- [`NPEET` - Non-parametric Entropy Estimation Toolbox](https://github.com/gregversteeg/NPEET)

##### [Gaia Early Data Release 3. Building the Gaia DR3 source list -- Cross-match of Gaia observations](https://arxiv.org/abs/2012.06267)
- #gaia
- As a first step, onboard detections that were deemed spurious were discarded. The remaining detections were then preliminarily associated with one or more sources in the existing source list in an observation-to-source match. All candidate matches that directly or indirectly were associated with the same source form a match candidate group. The detections from the same group were then subject to a cluster analysis. Each cluster was assigned a source identifier that normally was the same as the identifiers from Gaia DR2.

##### [A dearth of young and bright massive stars in the Small Magellanic Cloud](https://arxiv.org/abs/2012.05913)
- Our results imply that the SMC hosts only 30 very luminous main-sequence stars (M > 40 Msol; L > 10^5 Lsol), which are far fewer than expected from the number of stars in the luminosity range 3*10^4 < L/Lsol < 3*10^5 and from the typically quoted star formation rate in the SMC.
- Even more striking, we find that for masses above M > 20 Msol, stars in the first half of their hydrogen-burning phase are almost absent.
- We argue that a declining star formation rate or a steep initial mass function are unlikely to be the sole explanations for the dearth of young bright stars. Instead, many of these stars might be embedded in their birth clouds, although observational evidence for this is weak.

##### [Simulations of the star-forming molecular gas in an interacting M51-like galaxy: cloud population statistics](https://arxiv.org/abs/2012.05919)
- We present a catalogue of giant molecular clouds resolved down to masses of ∼10~M⊙ from a simulation of the entire disc of an interacting M51-like galaxy and a comparable isolated galaxy
- In the disc of our simulated galaxies, spiral arms seem to act merely as snowplows, gathering gas and clouds without dramatically affecting their properties.
- While the galaxy interaction has little effect on cloud masses and sizes, it does promote the formation of counter-rotating clouds.
- The common observation that clouds appear to be virialised entities may therefore be due to CO bright emission highlighting a specific level in this hierarchical binding sequence. The small fraction of gravitationally bound structures found suggests that low galactic star formation efficiencies may be set by the process of cloud formation and initial collapse.

##### [Redshift space three-point correlation function of IGM at z<0.48](https://arxiv.org/abs/2012.05926)
- We report the first detections of longitudinal three-point (ζ) and reduced three-point (Q) correlations of low-z (i.e z<0.48) Lyα clouds over a scale of r∥≤4 pMpc
- We show the amplitude of ζ increases with increasing HI column density (NHI) while Q does not show any NHI dependence.

##### [Dwarf Galaxies and the Black-Hole Scaling Relations](https://arxiv.org/abs/2012.06258)
- #smbh 
- SMBH和矮星系的M-sigma关系基本就是大星系的extrapolation，这和“simply a statistical consequence of assembly through repeated mergers“的预期不符
- This predicts black hole masses significantly larger than those observed in dwarf galaxies unless the initial distribution of uncorrelated seed black hole and stellar masses is confined to much smaller masses than earlier assumed.
- In contrast black hole feedback predicts that black hole masses tend towards a universal M∝σ^4 relation in all galaxies, and correctly gives the properties of powerful outflows recently observed in dwarf galaxies.


### Dec 15

#### Relevant / Important / Useful

#### Interesting / Keep in mind

##### [A flexible subhalo abundance matching model for galaxy clustering in redshift space](https://arxiv.org/abs/2012.06596)
- #galaxy_halo #assembly_bias #sham
- 基于考虑了orphan和卫星星系潮汐瓦解的DM模拟；并有比较灵活的galaxy assembly bias考虑
- 有一点类似SEM的地方：考虑了SFR和DM halo吸积率的关系
- Simultaneously, the SHAM results also retrieve the correct halo occupation distribution, the level of galaxy assembly bias, and higher-order statistics present in the TNG300 galaxy catalogues.
- This SHAM extension can be used to get accurate clustering prediction even when using low and moderate-resolution simulations.

##### [The bias from hydrodynamic simulations: mapping baryon physics onto dark matter fields](https://arxiv.org/abs/2012.06795)
- #assembly_bias #baryonic_effect #ssst_cos  
- Using the Bias Assignment Method (BAM) we find that non-local bias plays a central role.
- The gas density bias relation can be directly mapped onto the dark matter density field to high precision exploiting the strong correlation between them.
- The neutral hydrogen is mapped based on the dark matter and the gas density fields. Finally, the temperature is mapped based on the previous quantities.
- 可以为未来的光谱巡天提供IGM的mock

##### [MADLens, a python package for fast and differentiable non-Gaussian lensing simulations](https://arxiv.org/abs/2012.07266)
- [`MADLens` - a differentiable lensing simulator](https://github.com/VMBoehm/MADLens)
- We present MADLens a python package for producing non-Gaussian lensing convergence maps at arbitrary source redshifts with unprecedented precision.
- This is made possible by a combination of a highly parallelizable particle-mesh algorithm, a sub-evolution scheme in the lensing projection, and a machine-learning inspired sharpening step
- MADLens is fully differentiable with respect to the initial conditions of the underlying particle-mesh simulations and a number of cosmological parameters.
- Another use case for MADLens is the production of large, high resolution simulation sets as they are required for training novel deep-learning-based lensing analysis tools.

##### [Evidence for GN-z11 as a luminous galaxy at redshift 10.957](https://arxiv.org/abs/2012.06936)
- 江林华's work
- GN-z11: Follow-up HST near-infrared grism observations detected a continuum break that was explained as the Ly-alpha break corresponding to z = 11.09 (+0.08-0.12).
- Here we report a probable detection of three ultraviolet (UV) emission lines from GN-z11, which can be interpreted as the [C III] 1907, C III] 1909 doublet and O III] 1666 at z = 10.957+/-0.001 (when the Universe was only ~420 Myr old, or ~3% of its current age).
- Its UV lines likely originate from dense ionized gas that is rarely seen at low redshifts, and its strong [C III] and C III] emission is partly due to an active galactic nucleus (AGN) or enhanced carbon abundance.

#### Others

##### [Systematic uncertainties in models of the cosmic dawn](https://arxiv.org/abs/2012.06588)
- We examine three commonly-ignored sources of uncertainty in models for the mean reionization and thermal histories of the IGM: the underlying cosmology, the halo mass function (HMF), and the choice of stellar population synthesis (SPS) model.
- 宇宙学影响较小，主要影响汤普森散射截面，在 few percent level
- HMF和SPS模型影响很大：comparable to the 1σ error-bar on τe and a ∼20 mK effect on the global 21-cm signal amplitude.
- Our work highlights the need for dedicated efforts to reduce the uncertainties in common modeling ingredients in order to enable precision inference with future datasets.
- [`ares` - Accelerated Reionization Era Simulations](https://github.com/mirochaj/ares)

##### [The Dark Energy Survey Supernova Program: Modelling selection efficiency and observed core collapse supernova contamination](https://arxiv.org/abs/2012.07180)
- We use published SN time-series spectrophotometric templates, rates, luminosity functions and empirical relationships between SNe and their host galaxies to construct a framework for simulating photometric SN surveys.
- After testing different modelling choices and astrophysical assumptions underlying our simulation, we find that the predicted contamination varies from 5.8 to 9.3 per cent, with an average of 7.0 per cent and r.m.s. of 1.1 per cent. 
- [`SNANA` - Supernova Analysis package](https://github.com/RickKessler/SNANA)
- [`pippin` - Pipeline for photometric SN analysis](https://github.com/Samreay/Pippin)

##### [Self-calibration and robust propagation of photometric redshift distribution uncertainties in weak gravitational lensing](https://arxiv.org/abs/2012.07707)
- #photo-z 
- We present a method that accurately propagates residual uncertainties in photometric redshift distributions into the cosmological inference from weak lensing measurements
- By iteratively fitting cosmological and nuisance parameters arising from the redshift distribution model, we perform a self-calibration of the redshift distributions via the tomographic cosmic shear measurements.

##### [Understanding Type Ia Supernova Distance Biases by Simulating Spectral Variations](https://arxiv.org/abs/2012.07811)
- Characterizing the underlying spectroscopic evolution of SN Ia remains a major systematic uncertainty in current cosmological analyses, motivating a new simulation tool for the next era of SN Ia cosmology: Build Your Own Spectral Energy Distribution (BYOSED).
- BYOSED is used within the SNANA framework to simulate light curves by applying spectral variations to model SEDs
- By using BYOSED for SN Ia cosmology simulations, future analyses (e.g., Rubin and Roman SN Ia samples) will have greater flexibility to constrain or reduce such SN Ia modeling uncertainties.
- [`BYOSED` - Build Your Own Spectral Energy Distribution  for SNIa Cosmology](https://github.com/jpierel14/BYOSED)
- [`kaepora` - An open-source SQL relational database for Type Ia Supernova spectra](https://github.com/msiebert1/kaepora)

##### [Mapping Diffuse Emission in Lyman UV band](https://arxiv.org/abs/2012.07384)
- 纪丽老师关于：CAFE (Census of warm-hot intergalactic medium, Accretion, and Feedback Explorer) and LyRIC (Lyman UV Radiation from Interstellar medium and Circum-galactic medium) 的介绍
- LyRIC是中国空间站载荷

##### [Final assembly, metrology, and testing of the WEAVE fibre positioner](https://arxiv.org/abs/2012.07734)
- #ssst_dev
- 960根fiber：A completely new z-gantry for each positioner robot was acquired, with measurements showing a marked improvement in positioning repeatability.

##### [Galaxy Morphology Classification using Neural Ordinary Differential Equations](https://arxiv.org/abs/2012.07735)
- #machine_learning 
- We use a continuous depth version of the Residual Network (ResNet) model known as Neural ordinary differential equations (NODE) for the purpose of galaxy morphology classification.
- Through various metrics, we conclude that the performance of NODE matches that of other models, despite using only one-third of the total number of parameters as compared to these other models.

##### [A possible bright ultraviolet flash from a galaxy at redshift z ~ 11](https://arxiv.org/abs/2012.06937)
- 江林华's work
- Here we report a near-infrared transient with an observed duration shorter than 245 s coincident with the luminous star-forming galaxy GN-z11 at z ~ 11.
- Since some long-duration GRBs are associated with a bright ultraviolet (UV) or optical flash, we investigate the possibility that the detected signal arose from a rest-frame UV flash associated with a long GRB from GN-z11
- Despite the very low probability of being a GRB, we find that the spectrum, brightness, and duration of the transient are consistent with such an interpretation

##### [Unravelling the physics of multiphase AGN winds through emission line tracers](https://arxiv.org/abs/2012.06592)
- We find that the hot bubble compresses the line-emitting gas, resulting in higher pressures than in the ambient ISM or that would be produced by the AGN radiation pressure. This implies that observed emission line ratios such as OIV 25 μm / NeII 12 μm , NeV 14 μm / NeII 12 μm and NIII 57 μm / NII 122 μm constrain the presence of the bubble and hence the outflow driving mechanism.
- 不能对hot bubble外流中的电离气体使用equilibrium condition
- We also find that >50 per cent of the mass outflow rate, momentum flux and kinetic energy flux of the outflow are traced by lines such as NII 122 μm and NeIII 15 μm (produced in the 10^4 K phase) and CII 158 μm (produced in the transition from 10^4 K to 100 K).

##### [Mid-InfraRed Outburst in Nearby Galaxies (MIRONG) I: Sample Selection and Characterization](https://arxiv.org/abs/2012.06806)
- #tidal_disruption_event 
- USTC AGN组; 蒋凝的工作
- mid-infrared outburst in nearby galaxies (MIRONG) 基于WISE数据
- A total of 137 galaxies have been selected by requiring a brightening amplitude of 0.5 magnitude in at least one WISE band with respect to their quiescent phases. 大部分都没有光学flare对应
- We propose that these MIR outburst are dominated by the dust echoes of transient accretion onto supermassive black holes, such as tidal disruption events (TDEs) and turn-on (changing-look) AGNs.
- Moreover, the inferred peak MIR luminosity function is generally consistent with the X-ray and optical TDEs at high end albeit with large uncertainties.

##### [Ionized outflows from active galactic nuclei as the essential elements of feedback](https://arxiv.org/abs/2012.06945)
- #review

##### [The Lifetimes of Star Clusters Born with a Top-heavy IMF](https://arxiv.org/abs/2012.07095)
- Using the state-of-the-art NBODY6 code, we perform a comprehensive series of direct N-body simulations to study the evolution of star clusters, starting with a top-heavy IMF and undergoing early gas expulsion. 
- We find that the lifetimes of clusters with different IMFs moving on the same orbit are proportional to the relaxation time to a power of x that is in the range of 0.8 to 1. The observed correlation between concentration and the mass function slope in Galactic GCs can be accounted for excellently in models starting with a top-heavy IMF and undergoing an early phase of rapid gas expulsion.

##### [A sharp rise in the detection rate of broad absorption line variations in a quasar SDSS J141955.26+522741.1](https://arxiv.org/abs/2012.07254)
- USTC AGN组
- The strong correlation between the equivalent widths of BAL and the continuum luminosity, reveals that the variation of BAL trough is dominated by the photoionization.
- The photoionization model predicts that when the time interval ΔT between two observations is longer than the recombination timescale trec, the BAL variations can be detected. This can be characterized as a "sharp rise" in the detection rate of BAL variation at ΔT=trec

##### [Constraining the quasar radio-loud fraction at z∼6 with deep radio observations](https://arxiv.org/abs/2012.07301)
- 王然组
- Deep Karl G. Jansky Very Large Array (VLA) S-band observations of a sample of 21 quasars at z∼6
- We report the detections of two new radio-loud quasars: CFHQS J2242+0334 (hereafter J2242+0334) at z=5.88 and CFHQS J0227−0605 (hereafter J0227−0605) at z=6.20
- 估计高红移的Radio loud fraction: The final derived RLF is 9.4±5.7% for the optically selected quasars at z∼6. RLF红移演化不明显

##### [Spatially Resolved Properties of Galaxies with a Kinematically Distinct Core](https://arxiv.org/abs/2012.07345)
- We find a distinct difference in kinematic and stellar population properties in galaxies with a counter-rotating stellar core, depending on its classification using spatially resolved emission line diagnostics.

##### [A Virgo Environmental Survey Tracing Ionised Gas Emission (VESTIGE).IX. The effects of ram pressure stripping down to the scale of individual HII regions in the dwarf galaxy IC 3476](https://arxiv.org/abs/2012.07377)
- The deep narrow-band (NB) image reveals a very pertubed ionised gas distribution, characterised by a prominent banana-shaped structure in the front of the galaxy formed of giant HII regions crossing the stellar disc
- The NB image also shows that the star formation activity is totally quenched in the leading edge of the disc, where the gas has been removed during the interaction. 
- The increase of the star formation activity is due to the compression of the gas along the stellar disc of the galaxy, which is able to increase its mean electron density and boost the star formation process producing bright HII regions.

##### [Discovery of a damped Lyα galaxy at z ∼ 3 towards the quasar SDSS J011852+040644](https://arxiv.org/abs/2012.07422)
- We report the detection of the host galaxy of a damped Lyα system (DLA) with log N(HI) [cm−2] = 21.0±0.10 at z≈3.0091 towards the background quasar SDSS J011852+040644
- We detect Lyα emission in the dark core of the DLA trough at a 3.3σ confidence level
- The Lyα emission is blueshifted with respect to the systemic redshift derived from metal absorption lines by 281±43 km/s.
- The associated galaxy is at very small impact parameter of ≲12 kpc from the background quasar

##### [An old stellar population or diffuse nebular continuum emission discovered in green pea galaxies](https://arxiv.org/abs/2012.07668)
- #stellar_population 
- 挑选特定的HST filter，避开发射线区域来观测Green Pea星系
- While these galaxies are typically very blue in color, our analysis reveals that it is only the dominant stellar clusters that are blue. Each GPG does clearly show the presence of at least one bright and compact star-forming region, but these are invariably superimposed on a more extended and lower surface brightness emission.
- Moreover, the colors of the star forming regions are on average bluer than those of the diffuse emission, reaching up to 0.6 magnitudes bluer.

### Dec 16

#### Relevant / Important / Useful

##### [The diverse nature and formation paths of slow rotator galaxies in the EAGLE simulations](https://arxiv.org/abs/2012.08060)
- #massive_galaxy 
- SRs that have had major or minor mergers (mass ratios ≥0.3 and 0.1−0.3, respectively) tend to have a higher triaxiality parameter and ex-situ stellar fractions than those that had exclusively very minor mergers or formed in the absence of mergers ("no-merger" SRs). 在EAGLE模拟里有不需要经过major merger的SR
- No-merger SRs are more compact, have lower black hole-to-stellar mass ratios and quenched later than other SRs  
- By splitting SRs into kinematic sub-classes, we find that flat SRs prefer major mergers; round SRs prefer minor or very minor mergers; prolate SRs prefer gas-poor mergers.

##### [Identifying and Repairing Catastrophic Errors in Galaxy Properties Using Dimensionality Reduction](https://arxiv.org/abs/2012.07855)
- #machine_learning #photo-z 
- 主要是关于识别出哪些星系是photo-z的catastrophic errors
- We develop a novel method to identify these objects by combining the astronomical codes which infer galaxy properties with the dimensionality reduction algorithm t-SNE, which groups similar objects to determine which inferred properties are out of place.
- 基于t-SNE算法，5000 iterations with perplexity 35

##### [The Abell 3391/95 galaxy cluster system: A 15 Mpc intergalactic medium emission filament, a warm gas bridge, infalling matter clumps, and (re-) accelerated plasma discovered by combining SRG/eROSITA data with ASKAP/EMU and DECam data](https://arxiv.org/abs/2012.08491)
- #galaxy_cluster 
- 

#### Interesting / Keep in mind

##### [The coherent motion of Cen A dwarf satellite galaxies remains achallenge for ΛCDM cosmology](https://arxiv.org/abs/2012.08138)
- We study the satellite system of Cen A adding twelve new galaxies with line-of-sight velocities from VLT/MUSE observations. 
- We find 21 out of 28 dwarf galaxies with measured velocities share a coherent motion. Similarly flattened and coherently moving structures are found only in 0.2% of Cen A analogs
	- These analogs are not co-orbiting, and arise only by chance projection, thus they are short-lived structures in such simulations.

#### Others

##### [New Evidence for Extended HeII Reionization at z>3.5 from HeII Lyman Alpha and Beta Transmission Spikes](https://arxiv.org/abs/2012.07876)
- New high-resolution (R~14,000) spectra of the two brightest HeII-transparent quasars in the far-UV (FUV) at z>3.5
- In the predominantly saturated HeII absorption spectra, both sightlines show several isolated resolved (full width at half maximum FWHM>50 km/s) transmission spikes in HeII Lyα and HeII Lyβ.
- The incidence of such spikes decreases with increasing redshift, but both sightlines show significant spikes at z>3.5, signaling the presence of fully ionized regions in the z>3.5
- Because the transmission spikes indicate fully ionized regions at z>3.5 along both lines of sight, our observations provide further evidence that HeII reionization had substantially progressed at these redshifts.
- [`FaintCOS` - Improved background subtraction and co-adding code for CALCOS](https://github.com/kimakan/FaintCOS)

##### [Organised Randoms: learning and correcting for systematic galaxy clustering patterns in KiDS using self-organising maps](https://arxiv.org/abs/2012.08467)
- We then create 'organised' randoms, i.e. random galaxy catalogues with spatially variable number densities, mimicking the learnt systematic density modes in the data.
- Using realistically biased mock data, we show that these organised randoms consistently subtract spurious density modes from the two-point angular correlation function
- `FLASK`: (Xavier et al. 2016) is a public code designed to simulate lognormal (or Gaussian) random fields on the celestial sphere, with configurable tomography and preservation of all relevant correlations between galaxy density and weak lensing convergence fields, to the sub-percent level

##### [The Simons Observatory: the Large Aperture Telescope Receiver (LATR) Integration and Validation Results](https://arxiv.org/abs/2012.07862)
- #cmb
- The observatory consists of three 0.5 m Small Aperture Telescopes (SATs) and one 6 m Large Aperture Telescope (LAT), covering six frequency bands centering around 30, 40, 90, 150, 230, and 280 GHz.
- As a critical instrument, the Large Aperture Telescope Receiver (LATR) is designed to cool ∼ 60,000 transition-edge sensors (TES) to < 100 mK on a 1.7 m diameter focal plane.

##### [Speed limits for radiation driven SMBH winds](https://arxiv.org/abs/2012.07877)
- We investigate the impact of special relativity effects on the radiative pressure exerted onto the outflow.
- The radiation received by the wind decreases for increasing outflow velocity v, implying that the standard Eddington limit argument has to be corrected according to v.
- We find that the inclusion of relativistic effects leads to sizeable differences in the wind dynamics and that v is reduced up to 50% with respect to the non-relativistic treatment.
- We compare our results with a sample of UFO from the literature, and we find that the relativistic-corrected velocities are systematically lower than the reported ones, indicating the need for an additional mechanism, such as magnetic driving, to explain the highest velocity component

##### [LOFAR Detection of 110-188 MHz Emission and Frequency-Dependent Activity from FRB 20180916B](https://arxiv.org/abs/2012.08372)
- FRB20180916B，有16天周期的FRB：Here we report on the detection of 18 bursts using LOFAR at 110-188 MHz, by far the lowest-frequency detections of any FRB to date.
- These observations provide an order-of-magnitude stronger constraint on the optical depth due to free-free absorption in the source's local environment. The absence of circular polarization and nearly flat polarization angle curves are consistent with burst properties seen at 300-1700 MHz.
- Simultaneous observations show 5 CHIME/FRB bursts when no emission is detected by LOFAR. We find that the burst activity is systematically delayed towards lower frequencies by ~3 days from 600 MHz to 150 MHz.
- [`ionFR` - A code that allows you to predict the ionospheric Faraday rotation for a specific line-of-sight, geographic location, and epoch](https://github.com/csobey/ionFR)
- [`RM-Tools` - RM-synthesis, RM-clean and QU-fitting on polarised radio spectra](https://github.com/CIRADA-Tools/RM-Tools)

##### [Baryonic effects on the detectability of annihilation radiation from dark matter subhaloes around the Milky Way](https://arxiv.org/abs/2012.07846)
- In the full-physics case, formation of the stellar galaxy enhances annihilation radiation from the dominant smooth component of the galactic halo by a factor of three, and its central concentration increases substantially.
- In contrast, subhalo fluxes are reduced by almost an order of magnitude, partly because of changes in internal structure, partly because of increased tidal effects; they drop relative to the flux from the smooth halo by 1.5 orders of magnitude.

##### [Pushing automated morphological classifications to their limits with the Dark Energy Survey](https://arxiv.org/abs/2012.07858)
- #machine_learning 
- 基于CNN的：The classification scheme separates: (a) early-type galaxies (ETGs) from late-types (LTGs); and (b) face-on galaxies from edge-on.
- We obtain secure classifications for ∼ 87% and 73% of the catalog for the ETG vs. LTG and edge-on vs. face-on models, respectively.

##### [Dissecting the stellar content of Leo I: a dwarf irregular caught in transition](https://arxiv.org/abs/2012.07863)
- Leo I is considered one of the youngest dwarf spheroidals (dSph) in the Local Group. Its isolation, extended star formation history (SFH), and recent perigalacticon passage (~1 Gyr ago) make Leo~I one of the most interesting nearby stellar systems.
- HST观测：We find global star formation enhancements in Leo I ~13, 5.5, 2.0, and 1.0 Gyr ago, after which it was substantially quenched.
- We also distinguish two clear spatial regions: the inner ~190 pc presents an homogeneous stellar content (size of the gaseous star forming disc in LeoI from ~4.5 to 1 Gyr ago), whereas the outer regions display a clear positive age gradient.

##### [Orbital pericenters and the inferred dark matter halo structure of satellite galaxies](https://arxiv.org/abs/2012.07865)
- We show that subhalo orbital pericenters, rperi, correlate with their dark matter halo structural properties.
- At fixed maximum circular velocity, Vmax, subhalos with smaller rperi are more concentrated (have smaller rmax values) and have lost more mass, with larger peak circular velocities, Vpeak, prior to infall.
- We illustrate this using published pericenter estimates enabled by Gaia for the nine classical Milky Way dwarf spheroidal satellites. The two densest dSph satellites (Draco and Ursa Minor) have relatively small pericenters: r_max和V_max可能会比预期更低
- Such a shift exacerbates the traditional Too Big to Fail problem.
- Over the full population of classical dwarf spheroidals, we find no correlation between Vpeak and stellar mass today, indicative of a high level of stochasticity in galaxy formation at stellar masses below ∼10^7 M⊙

##### [SUPER IV. CO(J=3-2) properties of active galactic nucleus hosts at cosmic noon revealed by ALMA](https://arxiv.org/abs/2012.07965)

##### [The survival of globular clusters in a cuspy Fornax](https://arxiv.org/abs/2012.08058)
- E-MOSAICS模拟看Fornax这样的dwarf里的GC分布是否意味着DM halo有core：Dynamical friction causes 33 per cent of GCs with masses MGC≥4×10^4 M⊙ to sink to the centre of their host where they are tidally disrupted.
- Fornax中观测到的GC数量很多：we find that only 3 per cent of the Fornax analogues have five or more GCs, while 30 per cent have only one and 35 per cent have none.
- 卫星星系中的GC分布比Field中的更集中；而且in situ形成的比accreted进来的更集中
- The present-day radial distribution of GCs in E-MOSAICS turns out to be indistinguishable from that in Fornax, demonstrating that, contrary to claims in the literature, the presence of five GCs in the central kiloparsec of Fornax does not exclude a cuspy DM halo.

##### [MUSE reveals extended circumnuclear outflows in the Seyfert 1 NGC 7469](https://arxiv.org/abs/2012.08094)
- We find evidence of two outflow kinematic regimes: one slower regime extending across most of the star formation ring -- possibly driven by the massive star formation -- and a faster regime (with a maximum velocity of −715 km s−1), only observed in [O III], in the western region between the AGN and the massive star forming regions of the ring, likely AGN-driven.

##### [Determining star-formation rates in Active Galactic Nuclei hosts via stellar population synthesis](https://arxiv.org/abs/2012.08472)
- We investigate the use of SFR derived from the stellar population and its relation with that derived from the gas for a sample of 170 AGN hosts and a matched control sample of 291 galaxies
- 用气体和恒星星族得到最近的SFR，进行比较： We find that the SFRstars over the last 20~Myrs closely reproduces the SFRg, although a better match is obtained via the transformation: log(SFRstars) = (0.872+/-0.004) log(SFRg) -(0.075+/-0.006
- We interpret the difference as being due to the fact that the reddening of the stars is dominated by that affecting the less obscured underlying older population, while the reddening of the gas is larger as it is associated to a younger stellar population buried deeper in the dust.

##### [COLDz: Deep 34 GHz Continuum Observations and Free-free Emission in High-redshift Star-forming Galaxies](https://arxiv.org/abs/2012.08499)
- #radio_survey 
- We present deep continuum observations at 34 GHz in the COSMOS and GOODS-North fields from JVLA
- We present the deepest 34 GHz radio number counts to date, with five and thirteen continuum detections in COSMOS and GOODS-N, respectively. Nine galaxies show 34 GHz continuum emission that is originating from star-formation
- We determine free-free star-formation rates (SFRs), and show that these are in agreement with SFRs from spectral energy distribution fitting and the far-infrared/radio correlation

### Dec 17

#### Relevant / Important / Useful

##### [Does Concentration Drive the Scatter in the Stellar-to-Halo Mass Relation of Galaxy Clusters?](https://arxiv.org/abs/2012.08629)
- #galaxy_cluster #weak_lensing #galaxy_halo 
- SDSS redMaPPer, 按照固定richness上的BCG质量分成两个样本：The weak lensing profiles ΔΣ of the two cluster subsamples exhibit different slopes on scales below 1 Mpc/h.
- 基于X-ray数据考虑了mis-centering，进行DeltaSigma轮廓的建模：We find that the two subsamples have the same average halo mass of 1.74×10^{14}M⊙/h, but the concentration of the low-M∗ clusters is 5.87+0.77−0.60, ∼1.5σ smaller than that of their high-M∗ counterparts~(6.95+0.78−0.66). 
- 而且基于galaxy-cluster cross-correlation的分析发现：large-scale bias of the low-M∗, low-concentration clusters are ∼10% higher than that of the high-M∗, high-concentration systems
- Our results reveal a remarkable physical connection between the stellar mass within 20{-}30 kpc/h, the dark matter mass within ∼ 200 kpc/h, and the cosmic overdensity on scales above 10 Mpc/h

##### [Radio observations of the merging galaxy cluster system Abell 3391-Abell 3395](https://arxiv.org/abs/2012.08775)
- #galaxy_cluster #intra_cluster_medium #radio_galaxy
- ASKAP/EMU Early Science observation: While the eROSITA observations provide clear indications of a bridge of thermal gas between the clusters, neither ASKAP nor MWA observations show any diffuse radio emission coinciding with the X-ray bridge. 对粒子加速机制有一定的限制
- We identified 20 Giant Radio Galaxies, plus 7 candidates, with linear projected sizes greater than 1 Mpc. 
- 大尺度射电星系的数密度比想象要高：The sky density of field radio galaxies with largest linear sizes of >0.7 Mpc is ≈1.7 deg−2, three times higher than previously reported. We find no evidence for a cosmological evolution of the population of Giant Radio Galaxies.

##### [Dark Energy Survey Year 3 Results: Redshift Calibration of the Weak Lensing Source Galaxies](https://arxiv.org/abs/2012.08566)
- #des #photo-z #weak_lensing 
- We describe the methods used to assign individual weak lensing source galaxies from the Dark Energy Survey Year 3 Weak Lensing Source Catalogue to four tomographic bins and to estimate the redshift distributions in these bins.
- Our method consists of combining information from three independent likelihood functions: Self-Organizing Map p(z) (SOMPZ), a method for constraining redshifts from galaxy photometry; clustering redshifts (WZ), constraints on redshifts from cross-correlations of galaxy density functions; and shear ratios (SR), which provide constraints on redshifts from the ratios of the galaxy-shear correlation functions at small scales.

##### [DES Y3 results: Blending shear and redshift biases in image simulations](https://arxiv.org/abs/2012.08567)
- #des #photo-z #weak_lensing 
- To capture the coupled effects of blending in both shear and photometric redshift calibration, we define the effective redshift distribution for lensing, nγ(z), and describe how to estimate it using image simulations. 
- 进行了非常细致的图像模拟：Blending的影响最大，blending-related effects are the dominant contribution to the mean multiplicative bias of approximately −2%
- We provide corrected effective redshift distributions that incorporate statistical and systematic uncertainties, ready for use in DES Year 3 weak lensing analyses.

##### [Dark Energy Survey Year 3 Results: Clustering Redshifts -- Calibration of the Weak Lensing Source Redshift Distributions with redMaGiC and BOSS/eBOSS](https://arxiv.org/abs/2012.08569)
- #des #photo-z #weak_lensing 
- 通过DES WL source星系和redMaGiC以及BOSS星系的交叉相关来校准红移分布
- 用了两种方法：The first uses the clustering information independently to estimate the mean redshift of the source galaxies within a redshift window, as done in the DES Y1 analysis. The second method establishes a likelihood of the clustering data as a function of n(z), which can be incorporated into schemes for generating samples of n(z) subject to combined clustering and photometric constraints 第二种明显更好

#### Interesting / Keep in Mind

##### [Too dense to go through: The importance of low-mass clusters for satellite quenching](https://arxiv.org/abs/2012.08593)
- #quenching #galaxy_cluster #galaxy_group
- C-EAGLE模拟：We find that the majority of galaxies that are quenched at z=0 (≳ 80%) reached this state in a dense environment (log10M200[M⊙]≥13.5)
- Galaxies quenched inside the cluster that they reside in at z=0 are the dominant population in low-mass clusters, while galaxies quenched in a different halo dominate in the most massive clusters.
- This suggests that galaxies are quenched inside the first cluster they fall into.

##### [Cosmic Distances Calibrated to 1% Precision with Gaia EDR3 Parallaxes and Hubble Space Telescope Photometry of 75 Milky Way Cepheids Confirm Tension with LambdaCDM](https://arxiv.org/abs/2012.08534)
- #hubble_tension #gaia
- 75 Milky Way Cepheids with Hubble Space Telescope (HST) photometry and Gaia EDR3 parallaxes
- The resulting geometric calibration of Cepheid luminosities has 1.0% precision, better than any alternative geometric anchor. Applied to the calibration of SNe~Ia, it results in a measurement of the Hubble constant of 73.0 +/- 1.4 km/sec/Mpc
- We expect to reach ~1.3% precision in the near term from an expanded sample of ~40 SNe Ia in Cepheid hosts.

#### Others

##### [Dark Energy Survey Year 3 Results: Covariance Modelling and its Impact on Parameter Estimation and Quality of Fit](https://arxiv.org/abs/2012.08568)
- #des 
- 测试各种情况下协方差矩阵modeling的情况：These include the assumption of a Gaussian likelihood, the trispectrum contribution to the covariance, the impact of evaluating the model at a wrong set of parameters, the impact of masking and survey geometry, deviations from Poissonian shot-noise, galaxy weighting schemes and other, sub-dominant effects. 
- The largest impact on best-fit figure-of-merit arises from the so-called fsky approximation for dealing with finite survey area
- For parameter estimation, our ignorance of the exact parameters at which to evaluate our covariance model causes the dominant effect. We find that it increases the scatter of maximum posterior values for Ωm and σ8 by about 3% and for the dark energy equation of state parameter by about 5%.

##### [A Swift Fix for Nuclear Outbursts](https://arxiv.org/abs/2012.08521)
- #tidal_disruption_event 
- Swift更新了UV波段的校准，to correct for the loss of sensitivity over time
-  As UV photometry is critical to characterizing tidal disruption events (TDEs) and other peculiar nuclear outbursts, we re-computed published Swift data for TDEs and other singular nuclear outbursts
- With updated bolometric light curves, we recover the relationship of Hinkle20a, where more luminous TDEs decay more slowly than less luminous TDEs with decreased scatter as compared to the original relationship.

##### [CO Multi-line Imaging of Nearby Galaxies (COMING). IX. 12CO(J=2-1)/12CO(J=1-0) line ratio on kiloparsec scales](https://arxiv.org/abs/2012.08523)
- Nobeyama-45m + IRAM 30-m 观测: 看假设R2/1 - 12 CO(J=2-1)/12CO(J=1-0)比值为常数是否正确
- 24个近邻星系：The radial variation of R2/1 shows that it is high (~0.8) in the inner ~1 kpc while its median in disks is nearly constant at 0.60 when all galaxies are compiled
- In the case that the constant R2/1 of 0.7 is adopted, we found that the total molecular gas mass derived from 12CO(J=2-1) is underestimated/overestimated by ~20%, and at most by 35%.
- R2/1  has good positive correlations with star-formation rate and infrared color, and a negative correlation with molecular gas depletion time. There is a clear tendency of increasing R2/1 with increasing kinetic temperature

##### [The Red Supergiant Binary Fraction as a Function of Metallicity in M31 and M33](https://arxiv.org/abs/2012.08531)
- LMC中RSG中的双星比例在15-30%左右；大多数都是un-evolved B-type stars
- 延伸到M31和M33中去：Recent near-IR photometric surveys of M31 and M33 have lead to the identification of a complete sample of RSGs down to a limiting logL/L⊙≥4.2
- The resulting RSG binary fraction in M33 shows a strong dependence on galactocentric distance with the inner regions having a much higher binary fraction (41.2+12.0−7.3%) than the outer regions (15.9+12.4−1.9%). Such a trend is not seen in M31; instead, the binary fraction in lightly reddened regions remains constant at 33.5+8.6−5.0%.

##### [The SAMI Galaxy Survey: Kinematics of stars and gas in brightest group galaxies; the role of group dynamics](https://arxiv.org/abs/2012.08634)
- #early_type_galaxy #galaxy_group #ifu
- We find that the misalignment between the rotation axis of gas and stellar components is more frequent in the BGGs in unrelaxed groups, although with quite low statistical significance.
- Amongst the halo relaxation probes, the group BGG offset appears to play a stronger role than the luminosity gap on the stellar kinematic differences of the BGGs. However, both the group BGG offset and luminosity gap appear to roughly equally drive the misalignment between the gas and stellar component of the BGGs in one direction. 

##### [Exploring the Dust Content of Galactic Halos with Herschel III. NGC 891](https://arxiv.org/abs/2012.08686)
- The maps confirm the detection of thermal emission from the inner circumgalactic medium (halo) and spatially resolve a dusty superbubble and a dust spur (filament).
- The dust temperature of the halo component is lower than that of the disk but increases across a region of diameter ~8.0 kpc extending at least 7.7 kpc vertically from one side of the disk
- 外流正在发展成一个尺度比较大的星系风
- We conclude that the star formation surface density is sufficient for superbubble blowout into the halo, but the cosmic ray electrons may play a critical role in determining whether this outflow develops into a fountain or escapes from the gravitational potential.

##### [A gaint central red disk candidate at redshift z=0.76](https://arxiv.org/abs/2012.08798)
- #red_nugget #massive_galaxy #early_type_galaxy 
- CFHTLS + BOSS + HSC: 10^11.6 Msun的大质量，年老disk星系
- We also analyze its environment based on the VIMOS Public Extragalactic Redshift Survey (VIPERS) photometric catalog, and find that its close neighbors are all less massive 可能是一个中心星系

##### [Measuring the structure of high-redshift galaxies with deep learning](https://arxiv.org/abs/2012.09081)
- #machine_learning 
- We train CNNs to predict C and A from individual images of ∼150,000 galaxies at 0<z<7 in the CANDELS fields, using Bayesian hyperparameter optimisation to select suitable network architectures
- Our approach is thus not only able to reproduce standard measurements of non-parametric quantities, but gives superior results in substantially less time.

##### [Probing Cosmic Reionization and Molecular Gas Growth with TIME](https://arxiv.org/abs/2012.09160)
- #intensity_mapping [[Line Intensity Mapping Projects]] 
- The Tomographic Ionized-carbon Mapping Experiment (TIME) will measure the star formation rate (SFR) during cosmic reionization by observing the redshifted [CII] 158μm line at 6 < z < 9
- TIME will simultaneously study the abundance of molecular gas during the era of peak star formation by observing the rotational CO lines emitted by galaxies at 0.5≲z≲2.
- Probes: Line luminosity function; the auto- and cross-correlation power spectra, including synergies with external galaxy tracers. 


### Dec 18

#### Relevant / Important / Useful

##### [Globular cluster numbers in dark matter haloes: an empirical model within EMERGE](https://arxiv.org/abs/2012.09172)
- #globular_cluster 
- We confirm previous works that reported the observed linear correlation as being a consequence of hierarchical merging and its insensitivity to the exact GC formation processes at higher virial masses.
- We find that the scatter of the linear relation is strongly correlated with the relative amount of smooth accretion: the more dark matter is smoothly accreted, the fewer GCs a halo has compared to other haloes of the same mass. Smooth accretion 降低了特定halo质量上的GC数量
- Finally, we successfully reproduce the observed general trend of GCs being old and the tendency of more massive haloes hosting older GC systems, while failing to obtain the younger GC populations found in some galaxies, clearly indicating the need for an additional GC formation mechanism.

#### Interesting / Keep in mind

##### [The Last Journey. II. SMACC -- Subhalo Mass-loss Analysis using Core Catalogs](https://arxiv.org/abs/2012.09262)
- #galaxy_halo 
- SMACC adds a mass model to substructure merger trees based on halo “core tracking.” Our approach avoids the need for running expensive subhalo finding algorithms and instead uses subhalo mass-loss modeling to assign masses to halo cores
- We apply SMACC to the 1.24 trillion-particle Last Journey simulation and construct core catalogs with the additional mass information.

##### [Assessing tension metrics with Dark Energy Survey and Planck data](https://arxiv.org/abs/2012.09554)
- #cosmic_tension
- 用仿真数据比较不同的估计tension的方法：We find that the parameter differences, Eigentension, and Suspiciousness metrics all yield similar results on both simulated and real data, while the Bayes ratio is inconsistent with the rest due to its dependence on the prior volume.
- We calculate the tension between DES Year 1 3×2pt and Planck, finding the surveys to be in ∼2.3σ tension under the ΛCDM paradigm.
- Section 4介绍了各种Tension metrics
	- 有Evidence-based methods以及Parameter-space method
	- 介绍了Bayesian evidence ratio; Bayesian Suspiciousness;  Parameter differences; Eigentension 等方法

##### [Observational Evidence for Enhanced Black Hole Accretion in Giant Elliptical Galaxies](https://arxiv.org/abs/2012.09168)
- #massive_galaxy #smbh
- 星系群或星系团中心星系，SF和BHAR的燃料都是冷却的热气体：We present a study of the relationship between black hole accretion rate (BHAR) and star formation rate (SFR) in a sample of giant elliptical galaxies. 
- A a mean ratio of log(BHAR/SFR) = -1.45 +/- 0.2, 比field星系的值要高
- 作者认为主要是由于黑洞吸积率的升高驱动的：气体角动量更低，可以有效的径向吸积；We propose that angular momentum of the cool gas is the primary driver in suppressing BHAR in lower mass galaxies, with massive galaxies accreting gas that has condensed out of the hot phase on nearly radial trajectories.
- In general, active galaxies selected by typical techniques have sBHAR/sSFR ~ 10, while galactic nuclei with no clear AGN signatures have sBHAR/sSFR ~ 1, consistent with a universal M_BH--M_spheroid relation.

#### Others

##### [The importance of galaxy formation histories in models of reionization](https://arxiv.org/abs/2012.09189)
- We explore the extent to which resolving and modeling individual galaxy formation histories affects predictions both for the galaxy populations accessible to upcoming surveys and the signatures of reionization accessible to upcoming 21-cm experiment
- 不能简单假定一个Halo mass-光度关系：The diversity of galaxy formation histories also results in scenarios in which the brightest galaxies do \textit{not} always reside in the centers of large ionized regions, as there are often relatively low-mass halos undergoing dramatic, but short-term, growth.

##### [An EAGLE view of the missing baryons](https://arxiv.org/abs/2012.09203)
- Results from EAGLE suggest that the missing baryons are strongly concentrated towards the filament axes.
	- While the filaments occupy only 5% of the full simulation volume, the diffuse hot intergalactic medium in filaments amounts to 23% − 25% of the total baryon budget, or 79% − 87% of all the hot WHIM.
- 找Filament的算法：Bisous formalism; MMF/NEXUS+ 

##### [Cosmology Without Windows: Quadratic Estimators for the Galaxy Power Spectrum](https://arxiv.org/abs/2012.09389)
- We directly estimate the unwindowed power spectrum multipoles using quadratic estimators akin to those introduced in the late 1990s. Under Gaussian assumptions, these are optimal and free from the leading-order effects of pixellization and non-Poissonian shot-noise. 
- The technique is shown to be efficient and robust, and shows significant potential for measuring the windowless power spectrum and bispectrum in the presence of weak non-Gaussianity.

##### [Impact of baryons in cosmic shear analyses with tomographic aperture mass statistics](https://arxiv.org/abs/2012.09614)
- #baryonic_effect #weak_lensing 
- Non-Gaussian cosmic shear statistics based on weak-lensing aperture mass (Map) maps can outperform the classical shear two-point correlation function (γ-2PCF) in terms of cosmological constraining power. 但需要对小尺度的重子物理过程更了解
- 基于hydro模拟，We compute the bias due to baryons on the lensing PDF and the distribution of peaks and voids in Map maps 然后放到N-body模拟上使用
- We report a negative bias of a few percents on S8 and Ωm and also measure a positive bias of the same level on w0 when including a tomographic decomposition. These biases are increased to the order of ∼5% when combining Map statistics with the γ-2PCF as these estimators show similar dependency on the AGN feedback

##### [Hubble Space Telescope Observations of Two Faint Dwarf Satellites of Nearby LMC Analogs from MADCASH](https://arxiv.org/abs/2012.09174)
- Our HST data reach >3.5 mag below the tip of the red giant branch (TRGB) of each dwarf, allowing us to derive their structural parameters and assess their stellar populations. 
	- MADCASH-1 is a predominantly old, metal-poor stellar system
	- MADCASH-2's CMD suggests that it contains mostly ancient, metal-poor stars (age ~13.5 Gyr, [M/H] ~ -2.0), but that ~10% of its stellar mass was formed 1.1--1.5 Gyr ago, and ~1% was formed 400--500 Myr ago.
- GBT得到了MADCASH-2中HI气体的上限：< 5 x 10^4 Msun

##### [Shape noise and dispersion in precision weak lensing](https://arxiv.org/abs/2012.09175)
- #weak_lensing 
- We analyse the first measurements from precision weak lensing (PWL): a new methodology for measuring individual galaxy-galaxy weak lensing through velocity information.
- We identify two possible sources of scatter to explain the observed distribution: a shape noise term associated with the underlying assumption of circular stable rotation, and an astrophysical signal consistent with a log-normal dispersion around the stellar-to-halo mass relation (SHMR).
- **PWL方法**: 
	- Aiming to avoid the need for stacking, a new way to perform WL with the potential to be sensitive to individual galaxies was proposed by Blain (2002), followed by Morales (2006) and de Burgh-Day et al. (2015, 2016), and first applied to data by Gurri et al. (2020, hereafter Paper I). The new methodology, PWL, builds on the assumption that the velocity fields of stably-rotating galaxies can be fitted accurately by pure circular rotation motions (e.g. Mo et al. 2010). Under that assumption, the observed velocity fields of galaxies must be axisymmetric (their maximum and minimum velocity gradients must be orthogonal). As lensing shears the shape of galaxies, their observed velocity maps get distorted as well and are no longer axisymmetric. The amount of non-axisymmetry is proportional to the shear, and thus, can be related to the halo mass of the lens.

##### [The birth of intermediate-mass black holes in primordial galaxies](https://arxiv.org/abs/2012.09177)
- #smbh
- 看中等强度的Lyman-Werner辐射背景下的PopIII SF和黑洞形成：At the onset of collapse, Lyα cooling dominates in the outer regions of the halo but H2 cooling regulates the collapse of the core, at rates that are 10 - 50 times those in minihaloes because of higher virial temperatures
- Supercharged H2 cooling leads to the formation of 1800 - 2800 Msun primordial stars, with radiative feedback from the star halting accretion and setting its upper limit in mass. Such stars may lead to a population of less-massive, lower luminosity quasars

##### [A possible sub-kpc dual AGN buried behind the galaxy curtain](https://arxiv.org/abs/2012.09184)
- SDSSJ1431+4358: LBT观测，We found that most of the prominent optical emission lines are characterized by a double-peaked profile, mainly produced by AGN photoionization. Our spectroscopical analysis disfavors the hypothesis that the double-peaked emission lines in the source are the signatures of outflow kinematics, leaving open the possibility that we are detecting either the rotation of a single Narrow Line Region (NLR) or the presence of two SMBHs orbiting around a common central potential.

##### [Compaction-Driven Black Hole Growth](https://arxiv.org/abs/2012.09186)
- #smbh
- 因为SN反馈移除气体，黑洞成长在10^12 Msun质量以下的Halo中较慢；在这个质量以上能快速成长：Rapid BH growth is allowed when the halo is massive enough to lock in the SN ejecta by its deep potential well and its heated circum-galactic medium (CGM). The onset of BH growth between these two zones is triggered by a wet-compaction event, caused
- The compaction events are confined to the golden mass by the same mechanisms of SN feedback and hot CGM. The onset of BH growth is associated with its sinkage to the center due to the compaction-driven deepening of the potential well and the associated dynamical friction.
- AGN feedback is not causing the onset of quenching; they are both caused by a compaction event when the mass is between the SN and hot-CGM zones.

##### [Dust, gas, and metal content in star-forming galaxies at z∼3.3 revealed with ALMA and Near-IR spectroscopy](https://arxiv.org/abs/2012.09447)
- Comparing gas mass fraction and gas-phase metallicity between the star-forming galaxies at z∼3.3 and at lower redshifts, star-forming galaxies at z∼3.3 appear to be more metal-poor than local galaxies with similar gas mass fractions.
- Using the gas regulator model to interpret this offset, we find that it can be explained by a higher mass-loading factor, suggesting that the mass-loading factor in outflows increases at earlier cosmic times.

##### [The Arecibo Ultra-Deep Survey](https://arxiv.org/abs/2012.09516)
- ALFA L-band巡天：1.35~deg2 to a redshift depth of 0.16
- We detect 247 galaxies in the survey, more than doubling the number already detected in AUDS60. The mass range of detected galaxies is log(MHI [h−270M⊙])=6.32−10.76.
- 估计低红移和高红移的HIMF：No change in low-mass slope α was measured, but an increased characteristic mass M∗, was noted in the higher-redshift sample. 

##### [SEEDisCS II. Molecular gas in galaxy clusters and their large scale structure: the case of CL1411.1−1148 at z∼0.5](https://arxiv.org/abs/2012.09592)
- #galaxy_cluster
- Spatially Extended ESO Distant Cluster Survey (SEEDisCS): ALMA观测一个z=0.5的星系团里的27个SF星系；和相同红移，相同质量的Plateau de Bure high-z Blue Sequence Survey (PHIBSS2)星系比较
- While the majority of our galaxies, 63\%, are consistent with PHIBSS2, the remainder falls below the relation between μH2 and Mstar of the PHIBSS2 galaxies at z∼0.5. 而且这些缺少气体的星系不能用一个Gauss分布的low-mass tail来解释
- A new population of galaxies, with normal SFRs but low gas content and low depletion times ≲1 Gyr

##### [A deep radio view of the evolution of the cosmic star-formation rate density from a stellar-mass selected sample in VLA-COSMOS](https://arxiv.org/abs/2012.09797)
- VLA-COSMOS 3-GHz 1.4GHz RLFs: 在10个红移bin上考虑AGN和SFG的贡献
- 在纯光度演化模型下： We show that the evolution strength is similar to literature values up to z∼1.6.
- 把样本分成小质量 (< 10^10 Msun) 和大质量星系：We find that the SFRD is dominated by sources in the high stellar masses bin, at all redshifts.
- We find that the form of the relation between radio luminosity and SFR is therefore crucial in measuring the cosmic SFRD from radio data.


### Dec 21

#### Relevant / Important / Useful

##### [Recent Star-formation in a Massive Slowly-Quenched Lensed Quiescent Galaxy at z=1.88](https://arxiv.org/abs/2012.09864)
- #massive_galaxy #red_nugget #stellar_population 
- While the global photometry and spatially-resolved outskirts of MRG-S0851 imply an early-formation scenario with a slowly decreasing or constant star-formation history, a joint fit of 2D grism spectroscopy and photometry reveals a more complex scenario: MRG-S0851 is likely to be experiencing a centrally-concentrated rejuvenation in the inner ∼1 kpc in the last ∼100 Myr of evolution.
- 过程中形成了0.5%的恒星质量
- Using our criteria with MRG-S0851 as a prototype, we estimate that ∼1\% of massive quiescent galaxies at 1<z<2 are potentially rejuvenating.

#### Interesting / Keep in mind

##### [Anomalous Stellar Populations in LSB Galaxies](https://arxiv.org/abs/2012.09811)
- #stellar_population #lsb 
- HST WFC3 near-IR observations: F575-3 has the bluest RGB of any CMD in the literature, indicating an extremely low mean metallicity. F615-1 has unusually wide RGB and AGB sequences suggesting multiple episodes of star formation from metal-poor gas, possibly infalling material.
- Both galaxies have an unusual population of stars to the red of the RGB and lower in luminosity than typical AGB stars.

#### Others

##### [Mock halo catalogs: assigning unresolved halo properties using correlations with local halo environment](https://arxiv.org/abs/2012.10170)
- 解决如何在mock catalog里加入assembly bias的问题：Our algorithm exploits the fact that halo assembly bias is unchanged as long as correlations between halo property c and the intermediate-scale tidal environment α are preserved.
- Knowledge of α is sufficient to assign small-scale, otherwise unresolved properties to a halo in a way which preserves its large-scale assembly bias accurately.

##### [The NANOGrav 12.5-Year Data Set: Monitoring Interstellar Scattering Delays](https://arxiv.org/abs/2012.09884)
- We were able to measure scintillation bandwidths for 28 pulsars at 1500 MHz and 15 pulsars at 820 MHz.
 
##### [The role of faint population III supernovae in forming CEMP stars in ultra-faint dwarf galaxies](https://arxiv.org/abs/2012.10012)
- CEMP-no stars: (CEMP) stars ([C/Fe]≥0.7 and [Fe/H]≲−1)
- cosmological hydrodynamic zoom-in simulations of isolated UFDs 看能否重现增丰的[C/Fe]
- We find that a majority of CEMP-no stars in the observed UFDs and the MW halo can be explained by Pop~III SNe with normal explosion energy (ESN=1.2×10^51~erg) and Pop~II enrichment, but faint SNe might also be needed to produce CEMP-no stars with [C/Fe]≳2, corresponding to the absolute carbon abundance of A(C)≳6.0.

##### [A Redshift for the First Einstein Ring, MG 1131+0456](https://arxiv.org/abs/2012.10044)
- 关于1988年用射电发现的第一个Einstein ring：The lensing galaxy is at z(lens) = 0.844. However, to date, no spectroscopic redshift had been reported for the lensed source.
- We report the robust detection of a single narrow emission line at 5438 Angstroms, which we associate with CIII] 1909 from a type-2 quasar at z(source) = 1.849. Support for this redshift identification comes from weaker emission associated with CIV 1549 and HeII 1640, typical of type-2 quasars

##### [Gaia GraL: Gaia DR2 Gravitational Lens Systems. VI. Spectroscopic Confirmation and Modeling of Quadruply-Imaged Lensed Quasars](https://arxiv.org/abs/2012.10051)
- This paper reports on the 12 quadruply-imaged quasars identified by this effort to date, which is approximately a 20% increase in the total number of confirmed quadruply-imaged quasars.

##### [Far-Infrared Line Diagnostics: Improving N/O Abundance Estimates for Dusty Galaxies](https://arxiv.org/abs/2012.10054)
- The N/O ratio is arguably measured better through far-infrared (far-IR) fine-structure lines. Here we show that the [N III]57μm/[O III]52μm line ratio, denoted N3O3, is a physically robust probe of N/O.
- This parameter is insensitive to gas temperature and only weakly dependent on electron density. Though it has a dependence on the hardness of the ionizing radiation field, we show that it is well corrected by including the [Ne III]15.5μm/[Ne II]12.8μm line ratio.
- We find evidence for a systematic offset between the far-IR and optically derived N/O ratio. We argue this is likely due to that our far-IR method is biased towards younger and denser H II regions, while the optical methods are biased towards older H II regions as well as diffuse ionized gas.

##### [Unraveling the complex structure of AGN-driven outflows: V. Integral-field spectroscopy of 40 moderate-luminosity Type-2 AGNs](https://arxiv.org/abs/2012.10065)
- The shallow slope of the kinematic outflow size-luminosity relation indicates that while ionizing photons can reach out further, kinetic energy transfer is much less efficient due to various effects, demonstrating the importance of kinematical analysis in quantifying the outflow size and energetics. By comparing the outflow kinematics with the host galaxy properties, we find that AGNs with strong outflows have higher star formation rate and higher HI gas fraction than those AGNs with weak outflows.

##### [The role of AGN in the structure, kinematics and evolution of ETGs in the Horizon simulations](https://arxiv.org/abs/2012.10182)
- Galaxies formed in absence of AGN feedback show differences with observations such as the departure from the Fundamental Plane (FP) of a group of galaxies that have an excess of stellar surface density, and a shallower mass-size relation populated by galaxies with young stellar ages.

### Dec 22

#### Relevant / Important / Useful

#### Interesting / Keep in mind

##### [Host and Trigger of AGNs in local Universe](https://arxiv.org/abs/2012.10640)
- #galaxy_halo 
- 用SDSS WL-catalog测量AGN的typical halo mass: The typical halo mass is about 10^12h−1M⨀, similar to the characteristic mass in the stellar mass-halo mass relation (SHMR).
- For given stellar mass, AGN host galaxies and star-forming galaxies share the same SHMR, while quiescent galaxies have more massive halos. 
- Clustering analysis on halo scales reveals that AGNs are surrounded by a larger number of satellites (with stellar mass down to 1/1000 of the mass of the central galaxy) than star-forming galaxies
- The feedback from the starburst and AGN reduces the amount of cold gas for fueling the central black hole, producing a characteristic halo mass scale, ∼10^12h−1M⨀, where the AGN fraction peaks.
- [`mcfit` - multiplicatively convolutional fast integral transforms](https://github.com/eelregit/mcfit/)

#### Others

##### [Position-dependent Voronoi probability distribution functions for matter and halos](https://arxiv.org/abs/2012.10508)
- Voronoi density probability distribution function (PDF)
	- For the dark matter, Voronoi densities represent the matter density field smoothed on a uniform mass scale, which approximates the Lagrangian density field. 
	- For halos, the Voronoi densities contain information about the local environment of each halo.	
- We demonstrate that the spatial variation of the position-dependent PDF is due to large-scale density fluctuations, indicating that the position-dependent PDF is a biased tracer of large-scale structure

##### [Mitigating the Noise-Source Coupling Effect in Shear Measurement](https://arxiv.org/abs/2012.10899)
- #weak_lensing 
- Previously, it has been demonstrated that the shear estimators defined in the Fourier_Quad (FQ) method can achieve sub-percent accuracy at the very faint end (SNR≲5) through ensemble averaging
- Later, it is found that we can approach the minimum statistical error (the Cramer-Rao Bound) by symmetrizing the full PDF of the FQ shear estimators (the PDF_SYM approach), instead of taking ensemble averages
- With a large amount of mock galaxy images, we are able to identify some small amount of shear biases in the PDF_SYM approach at the faint end.
- We find that these biases originate from the noise-source coupling in the galaxy power spectrum. It turns out that this problem can be largely fixed by adding additional terms to the FQ shear estimators

##### [Optical Design of the EXperiment for Cryogenic Large-Aperture Intensity Mapping (EXCLAIM)](https://arxiv.org/abs/2012.10481)
- #intensity_mapping [[Line Intensity Mapping Projects]]
- EXCLAIM is a balloon-borne telescope that will measure integrated line emission from carbon monoxide (CO) at redshifts z < 1 and ionized carbon ([CII]) at redshifts z = 2.5-3.5 to probe star formation over cosmic time in cross-correlation with galaxy redshift surveys.
- Off-axis reflective optics use a 90-cm primary mirror to provide 4.2' full-width at half-maximum (FWHM) resolution at the center of the EXCLAIM band over a field of view of 22.5

##### [Physical effects on compact high-velocity clouds in the circumgalactic medium](https://arxiv.org/abs/2012.10535)
- FLASH模拟：the evolution of compact high-velocity clouds (CHVCs) passing through a hot, tenuous gas representing the highly-ionized circumgalactic medium (CGM)
- Self-gravity stabilizes clouds against Rayleigh-Taylor instability which are disrupted within 10 sound-crossing times without
- Clouds can develop Jeans-instable regions internally even though they are initially below Jeans mass
- 云团通过冲压和K-H不稳定性来损失质量; thermal conduction leads to continuous, filamentary stripping, while the removed gas is heated up quickly and mixes efficiently with the ambient CGM 热传导也很重要
- Conclusively, only sophisticated modelling of CHVCs as non-homogeneous and non-isothermal clouds with thermal conduction and self-gravity explains observed morphologies and naturally leads to the suppression of star formation.

##### [A Comparison of Star-Forming Clumps and Tidal Tails in Local Mergers and High Redshift Galaxies](https://arxiv.org/abs/2012.10765)
- 把HST观测的近邻星系的图像人工红移到高红移上去: Most redshifted tails have surface brightnesses that would be visible at z=0.5 or 1 but not at z=2 due to cosmological dimming. 但很多SF clumps依然可见，并合高红移巡天中看到的观测性质类似
- These results suggest that some clumpy high-z galaxies without observable tidal features could be the result of mergers.
- A total of 1596 star clusters brighter than MV = -9 were identified within the boundaries of the local clumps. The cluster magnitude distribution function is a power law with approximately the same slope (approximately -1 for a number-log luminosity plot) for all the galaxies

##### [AGN jets and a fanciful trio of black holes in the Abell 85 Brightest Cluster Galaxy](https://arxiv.org/abs/2012.10774)
- VLA高分辨A85图像: Chandra X-ray data and the new high-resolution radio map show no evidence that the Abell 85 BCG harbors a binary black hole.
- SDSS J004150.75-091824.3 was postulated to be "a third" SMBH associated with the BCG. In the optical and X-rays, SDSS J004150.75-091824.3 is a point-like source located ~14" away from the nucleus of the Abell 85 BCG. 实际上是一个background QSO

### Dec 23

#### Relevant / Important / Useful

##### [A preserved red nugget in the heart of the BCG of the Hydra I cluster revealed with MUSE 2D stellar population analysis](https://arxiv.org/abs/2012.11609)
- #cluster_galaxies #early_type_galaxy #massive_galaxy #stellar_population #ifu 
- We model the observed spectra using full-spectrum fitting and produce 2D maps of the stellar velocity dispersion, age, total metallicity, α-element, sodium abundance, and the initial mass function (IMF) slope.
- The core, which we identify as a red nugget, dominates the light budget within R≲1.5 kpc, has a relatively small velocity dispersion (σ∗≈180 km s−1), is old (ages≳11 Gyr), metal-rich ([Z/H]∼0.2 and [Na/Fe]∼0.4), and has a bottom-heavy IMF (with slope Γb∼2.4).
- In the outer region, stars become increasingly hotter, younger, metal and sodium poorer, α-element richer, and the IMF slope becomes Chabrier-like with increasing galactocentric distances.

#### Interesting / Keep in mind

##### [Discovery of a Supercluster in the eROSITA Final Equatorial Depth Survey: X-ray Properties, Radio Halo, and Double Relics](https://arxiv.org/abs/2012.11607)
- #cluster_galaxies #intra_cluster_medium 
- In the 140 deg2 eROSITA Final Equatorial Depth Survey (eFEDS) field we detect a previously unknown supercluster consisting of a chain of eight galaxy clusters at z=0.36.
- We further investigate the gas in the bridge region between the cluster members for a potential WHIM detection. Radio follow-up observations with LOFAR and uGMRT are used to search for diffuse emission and constrain the dynamic state of the system.
- 对eROSITA全天巡天的预测：Our forecasts show that we will be able to detect 450 superclusters with 3000 member clusters

##### [Tempestuous life beyond R_500: X-ray view on the Coma cluster with SRG/eROSITA. I. X-ray morphology, recent merger, and radio halo connection](https://arxiv.org/abs/2012.11627)
- #intra_cluster_medium #cluster_galaxies 
- We discuss the rich morphology revealed by the X-ray observations (also in combination with the SZ data) and argue that the most salient features can be naturally explained by a recent (on-going) merger with the NGC 4839 group.
- we identify a faint X-ray bridge connecting the group with the cluster, which is convincing proof that NGC 4839 has already crossed the main cluster. The gas in the Coma core went through two shocks, first through the shock driven by NGC 4839 during its first passage through the cluster some Gyr ago, and, more recently, through the "mini-accretion shock" associated with the gas settling back to quasi-hydrostatic equilibrium in the core.

#### Others

##### [Peering Into the Extended X-ray Emission on Megaparsec Scale in 3C 187](https://arxiv.org/abs/2012.11610)
- The diffuse X-ray emission around 3C 187 is elongated along the radio axis, and enhanced in correspondence of the radio lobes, indicating a morphological connection between the emission in the two energy bands, and thus suggesting a dominating IC/CMB mechanism in these regions

##### [The Collapse of Atomically-Cooled Primordial Haloes. I. High Lyman-Werner Backgrounds](https://arxiv.org/abs/2012.11612)
- We have now performed cosmological simulations of baryon collapse in atomically-cooled haloes for times that are sufficient for supermassive stars to form and die as direct-collapse black holes (DCBHs). Our simulations reveal that fragmentation of the accretion disk at the center of the halo after ∼ 500 kyr is nearly ubiquitous and in most cases leads to the formation of binary or multiple supermassive stellar systems.

##### [A High-Resolution View of Fast Radio Burst Host Environments](https://arxiv.org/abs/2012.11617)
- #fast_radio_burst 
- HST/WFC3观测：We quantify their spatial distributions and locations with respect to their host galaxy light distributions, finding that they occur at moderate host normalized-offsets of 1.4 re, occur on fainter regions of their hosts in terms of IR light, but overall trace the radial distribution of IR light in their galaxies
- The FRBs in our tested distribution do not clearly trace the distributions of any other transient population with known progenitors
- We further find that most FRBs are not in regions of elevated local star formation rate and stellar mass surface densities in comparison to the mean global values of their hosts.
- Our results do not strongly support the primary progenitor channel of FRBs being connected either with the most massive (stripped-envelope) stars, or with events which require kicks and long delay times (neutron star mergers).

##### [The delay time distribution of supernovae from integral-field spectroscopy of nearby galaxies](https://arxiv.org/abs/2012.11958)
- #ssst_gal 如果SSST有IFU可以做更大的样本
- Statistical analysis of a sample of 116 supernovae in 102 galaxies, we evaluate different DTD models for SN types Ia (73), II (28) and Ib/c (15).
- This analysis demonstrates that integral field spectroscopy opens a new way of studying SN DTD models in the local universe.

##### [Angular clustering and host halo properties of [OII] emitters at z>1 in the Subaru HSC survey](https://arxiv.org/abs/2012.12224)
- HSC DUD场里的NB816 and NB921挑选的[OII]发射星系
- 看到了很明确的相关信号：We also find the clear deviation of the correlation from a simple power-law form. 试图用HOD模型进行解释
- The satellite fraction of the \[OII\] emitter sample is found to be fsat∼0.15.


### Dec 23

#### Relevant / Important / Useful

##### [AMICO galaxy clusters in KiDS-DR3: cosmological constraints from counts and stacked weak-lensing](https://arxiv.org/abs/2012.12273)
- #cluster_cosmology #weak_lensing 值得学习
- 377 deg^2; 3652 galaxy clusters; 0.1 < z < 0.6
- Simultaneously modelling the comoving number density of galaxy clusters and the scaling relation between the intrinsic richnesses and the cluster masses, assessed through a stacked weak-lensing profile modelling.
- We obtained Ωm=0.24+0.04−0.03, σ8=0.89+0.06−0.05, S8=0.80+0.04−0.04. The constraint on S8 is consistent within 1σ with the results from WMAP and Planck. 
- [`PySSC` - A Python implementation of the fast super-sample covariance](https://github.com/fabienlacasa/PySSC)
	- Reference [Lacasa & Grain 2019 - Fast and easy super-sample covariance of large scale structure observables](https://arxiv.org/abs/1809.05437)

##### [Dark Energy Survey Year 3 Results: Deep Field Optical + Near-Infrared Images and Catalogue](https://arxiv.org/abs/2012.12824)
- #des #photometry 
- The DES Deep Fields comprise 11 fields (10 DES supernova fields plus COSMOS), with a total area of ∼30  square degrees in ugriz bands and reaching a maximum i-band depth of 26.75 (AB, 10σ, 2").
- 为DES Y3准备了object catalog：The catalogue is constructed in order to provide a sample of effectively noiseless galaxies, to be used as a prior on the population of objects observed in the DES and their moments in light distribution
- 在多波段deblending和modeling上有值得参考之处

##### [Stellar Halo Morphology from TNG50: Twisted and Twisted-Stretched Halos](https://arxiv.org/abs/2012.12284)
- #stellar_halo
- Using a local in shell iterative method (LSIM) as the main approach, we explicitly show evidence of twisting (in about 52% of halos) and stretching (in 48% of them) in the real space. 
- This implies that the DM halo is somewhat aligned with the stellar disk in response to the baryonic potential. The level of alignment mostly decreases away from the center.

##### [CFHTLenS: Galaxy bias as function of scale, stellar mass, and colour. Conflicts with predictions by semi-analytic models](https://arxiv.org/abs/2012.12299)
- #weak_lensing #galaxy_halo 
- We measured the scale-dependent galaxy bias factor b(k) and correlation factor r(k) from linear to non-linear scales of k≈10h^-1Mpc at two redshifts z¯=0.35,0.51 for galaxies with stellar mass between 5×10^9 and 3×10^11 h^-1M⊙.
- 和Munich以及Durham SAM比较：Despite a reasonable model agreement for the relative change with both scale and galaxy properties, there is a clear conflict for b(k) with no model preference: the model galaxies are too weakly clustered.

##### [Bulge and disk colors in the cluster core and outskirts](https://arxiv.org/abs/2012.12480)
- #early_type_galaxy 
- 研究星系团中不同位置上的S0星系：we find that bulges are redder than their surrounding disks, show a significant color-magnitude trend, and have colors that do not correlate with environment metrics
- On the other hand, the disks associated with our cluster S0s become significantly bluer with increasing cluster-centric radius, but show no evidence for a color-magnitude relation. 
	- No significant difference is found for the disk colors of backsplash and infalling galaxies in the projected phase space.

#### Interesting / Keep in mind

##### [Dark Energy Survey Year 3 Results: Measuring the Survey Transfer Function with Balrog](https://arxiv.org/abs/2012.12825)
- #photometry  #des
- We systematically inject onto the single-epoch images of a random 20% subset of the DES footprint an ensemble of nearly 30 million realistic galaxy models derived from DES Deep Field observations.
- The recovered Balrog injections are shown to closely match the photometric property distributions of the Y3 GOLD catalog, particularly in color, and capture the number density fluctuations from observing conditions of the real data within 1% for a typical galaxy sample.
- We find that Y3 colors are extremely well calibrated, typically within ~1-8 millimagnitudes, but for a small subset of objects we detect significant magnitude biases correlated with large overestimates of the injected object size due to proximity effects and blending
- [`Balrog-GalSim` - Modules for GalSim that will be useful for DES images in conjunction with Balrog](https://github.com/sweverett/Balrog-GalSim)

##### [Dark Energy Survey Year 3 Results: Calibration of Lens Sample Redshift Distributions using Clustering Redshifts with BOSS/eBOSS](https://arxiv.org/abs/2012.12826)
- #des #photo-z 
- We find general agreement between clustering redshift and photometric redshift estimates, with differences on the inferred mean redshift to be below |Δz|=0.01 in most of the bins.
- Our typical uncertainties on the mean redshift ranged from 0.003 to 0.008, while our uncertainties on the width ranged from 4 to 9%

##### [Results of the Photometric LSST Astronomical Time-series Classification Challenge (PLAsTiCC)](https://arxiv.org/abs/2012.12392)
- The strong performance of the top three classifiers on Type Ia supernovae and kilonovae represent a major improvement over the current state-of-the-art within astronomy

##### [Development of the ROSIE Integral Field Unit on the Magellan IMACS Spectrograph](https://arxiv.org/abs/2012.12293)
- #ifu
- Reformatting Optically-Sensitive IMACS Enhancement IFU, or ROSIE IFU. The 50.4" x 53.5" field of view will be pre-sliced into four 12.6" x 53.5" subfields, and then each subfield will be divided into 21 0.6" x 53.5" slices
- The four main image slicers will produce four pseudo-slits spaced six arcminutes apart across the IMACS f/2 camera field of view, providing a wavelength coverage of 1800 Angstroms at a spectral resolution of 2000.

#### Others

##### [The first light from tidal disruption events](https://arxiv.org/abs/2012.12271)
- #tidal_disruption_event 
- TDE的数值模拟：we find that the injected matter has its trajectories promptly circularized by secondary shocks taking place near the black hole.
- The generated internal energy efficiently diffuses away in the form of radiation, which results in a thin vertical profile of the formed disc.
- Matter launched to large distances continuously gains energy through radiation pressure, which can cause a significant fraction to become unbound. 

##### [Time Delay of MgII Emission Response for the Luminous Quasar HE 0435-4312: Towards Application of High-Accretor Radius-Luminosity Relation in Cosmology](https://arxiv.org/abs/2012.12409)
- 6年的监测：rest-frame time-delay of 296+13−14 days between the MgII broad-line emission and the ionizing continuum using seven different time-delay inference methods.
- The MgII emission is considerably variable with the fractional variability of ∼5.4%, which is comparable to the continuum variability.
- The high-accreting subsample that has an RMS scatter of ∼0.2 dex is considered. This opens up a possibility to use the high-accretor MgII-based radius-luminosity relation for constraining cosmological parameters.

##### [SDSS-IV/MaNGA: Can impulsive gaseous inflows explain steep oxygen abundance profiles \& anomalously-low-metallicity regions?](https://arxiv.org/abs/2012.12887)
- We use integral-field spectroscopic measurements of gas-phase metallicity and single-dish radio measurements of total atomic gas mass to estimate the magnitude and frequency of gaseous inflows incident on star-forming galaxies. 
- We reveal a mutual correlation between steep oxygen abundance profiles between 0.25−1.5Re, increased variability of metallicity between 1.25−1.75Re, and elevated HI content at fixed total galaxy stellar mass
- 10^10 Msun质量以下的星系的O丰度轮廓符合由内流增丰的模型；大质量星系内的证据不明显
- The large diversity of HI mass implies that inflow-associated gas ought to reside far from the star-forming disk.

### Dec 25

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

##### [Self-Supervised Representation Learning for Astronomical Images](https://arxiv.org/abs/2012.13083)
- #machine_learning 
- Without the need for labels, self-supervised learning recovers representations of sky survey images that are semantically useful for a variety of scientific tasks.
- We apply a contrastive learning framework on multi-band galaxy photometry from the Sloan Digital Sky Survey (SDSS) to learn image representations.
- We outperform the supervised state-of-the-art results, and we show that our approach can achieve the accuracy of supervised models while using 2-4 times fewer labels for training.
	
##### [The CatWISE2020 Catalog](https://arxiv.org/abs/2012.13084)
- WISE + NEOWISE, from 2010-2018
- The other major change from the CatWISE Preliminary Catalog is that the detection list for the CatWISE2020 Catalog was generated using crowdsource (Schlafly et al. 2019)
- The 90% completeness depth for the CatWISE2020 Catalog is at W1=17.7 mag and W2=17.5 mag, 1.7 mag deeper than in the CatWISE Preliminary Catalog.
	
##### [Best licensing practices](https://arxiv.org/abs/2012.12994)

#### Others

##### [Wide-angle effects on galaxy ellipticity correlations](https://arxiv.org/abs/2012.13290)
- We show an efficient way to compute wide-angle or all-sky statistics of galaxy intrinsic alignment in three-dimensional configuration space.

##### [Driving galactic winds with magnetic fields at low and high redshift](https://arxiv.org/abs/2012.12905)
- We present a simple toy model that can provide insight on how non-axis-symmetric instabilities in galaxies (bars, spiral-arms, warps) can lead to local exponential magnetic field growth by a radial flows beyond the equipartition value by at least two orders of magnitude on a time-scale of a few 100 Myr.
- Our predictions show that the process can lead to galactic outflows in barred spiral galaxies with a mass loading factor η≈0.1, in agreement with our numerical simulations.

##### [ALMA detects molecular gas in the halo of the powerful radio galaxy TXS 0828+193](https://arxiv.org/abs/2012.12923)
- ALMA/SMA观测：CO(3-2) line observations of the HzRG TXS 0828+193 (z=2.57)
- We detect CO emission associated with the HzRG and derive a molecular gas mass of (0.9±0.3)×10^10M
- The newly found CO sources do not have counterparts in any other observing band and could be high-density clouds in the halo of TXS 0828+193 and thus potentially linked to the large-scale filamentary structure of the cosmic web.

##### [First Co-spatial Comparison of Stellar, Neutral-, and Ionized-gas Metallicities in a metal-rich galaxy: M83](https://arxiv.org/abs/2012.12933)
- 多成分丰度比较分析：stellar, neutral-gas, and ionized-gas
- Our co-spatial metallicity comparison of the multi-phase gas and stellar populations shows excellent agreement outside of the nucleus of the galaxy hinting at a scenario where the mixing of newly synthesized metals from the most massive stars in the star clusters takes longer than their lifetimes (∼10 Myr)

### Dec 29

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

##### [Triaxiality in galaxy clusters: Mass versus Potential reconstructions](https://arxiv.org/abs/2012.13413)
- #cluster_cosmology 
- 用PCA和elliptical fitting方法看星系团X-ray图像contour；We then analyze how the choice of the substructure removal algorithm and the representation of the data (cumulative vs thin shell) affect the results
- Cluster shape，包括指向和轴比都和substructure有简并
- We observe that as the derived cluster shape depends on the method used for removing the substructures, thermodynamic properties extracted from, for instance, the X-ray emissivity profile, suffer from this additional, and often underestimated, bias
- 引力势的情况要好很多: by characterizing galaxy clusters by their potential rather than by their mass, dynamically active and relaxed clusters could be combined in cosmological studies, improving statistics and lowering scatter.

##### [Optimization of telescope focal ratios for MLA-fiber coupled Integral Field Units](https://arxiv.org/abs/2012.13704)
- #ifu #ssst-dev
- We have developed an analytic model for generic image transfer using microlens-coupled fibers to determine the telescope input beam speed that optimizes the lenslet clear aperture and minimizes fiber focal-ratio degradation.

#### Others

##### [Physical insights from the spectrum of the radio halo in MACS J0717.5+3745](https://arxiv.org/abs/2012.14373)
- #radio_galaxy 
- LOFAR + uGMRT + VLA观测：a largest linear size of ∼2.2Mpc. The halo shows a steep spectrum (α1.5GHz-144MHz∼−1.4) and a steepening (α5.5GHz-1.5GHz∼−1.9) above 1.5 GHz. We find a strong scattering in spectral index maps on scales of 50−100 kpc.
	- The spectral index becomes steeper and shows an increased curvature in the outermost regions of the halo.
- 和X-ray观测比较：Despite a significant substructure in the halo emission, the radio brightness correlates strongly with the X-ray brightness at all observed frequencies.
- The compelling evidence for a steep spectral index, the existence of a spectral break above 1.5 GHz, and the dependence of radio and X-ray surface brightness correlation on frequency are interpreted in the context of turbulent reacceleration models.

##### [The emergence of the X-ray luminosity/cluster richness relation for radio galaxies](https://arxiv.org/abs/2012.13748)
- #cluster_galaxies #radio_galaxy 
- 观测中：接近爱丁顿吸积率的AGN的密度和环境星系密度没有正相关，反而可能反相关，Broken down by radio galaxy subgroup, recent work has explored connections between low excitation radio galaxies with Fanaroff-Riley II jet morphology (FRII LERGs) and other radio galaxies 本文加入了FR0的讨论
- We describe how to understand the observed X-ray luminosity/cluster richness relation as a fundamental correlation on the nature of the jet-disk connection.

##### [Jet collimation and acceleration in the giant radio galaxy NGC 315](https://arxiv.org/abs/2012.14154)
- We find that the jet geometry transitions from a semi-parabolic shape into a conical/hyperbolic shape at a distance of ≈105 gravitational radii
- These results suggest that the jets are collimated by the pressure of the surrounding medium and accelerated by converting Poynting flux to kinetic energy flux.
- We discover limb-brightening of the jet in a limited distance range where the angular resolution of our data is sufficient to resolve the jet transverse structure. This indicates that either the jet has a stratified velocity field of fast-inner and slow-outer layers or the particle acceleration process is more efficient in the outer layer due to the interaction with the surroundings on pc-scales.
