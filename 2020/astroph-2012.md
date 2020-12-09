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

----

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
- #nearby_galaxies [[Surveys of Nearby Galaxies]]
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

### Dec 8

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

