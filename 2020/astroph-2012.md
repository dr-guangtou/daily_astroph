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