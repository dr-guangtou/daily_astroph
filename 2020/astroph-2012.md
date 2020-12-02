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
