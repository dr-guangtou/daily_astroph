# ArXiv astrop-ph Journal 

- #arxiv

## 2021 Jan 

### Jan 1 

#### Relevant / Important / Useful

##### [An Extended Halo-based Group/Cluster finder: application to the DESI legacy imaging surveys DR8](https://arxiv.org/abs/2012.14998)
- #cluster_galaxies #cluster_cosmology [[Galaxy Cluster Finders]]
- 主要特点是同时利用光谱和测光红移
- 构建了mock survey：For galaxies with magnitude z≤21 and redshift 0<z≤1.0 in the DESI legacy imaging surveys (The Legacy Surveys), our group finder successfully identifies more than 60% of the members in about 90% of halos with mass $>10^{12.5} M_{\odot}$.
- Groups with more than 10 members have a redshift accuracy of ∼0.008. We apply this group finder to the Legacy Surveys DR8 and find 6.4 Million groups with at least 3 members. About 500,000 of these groups have at least 10 members.
- [Public DR8 catalog](https://gax.sjtu.edu.cn/data/data1/DESI_DR8/groups.tar.gz)

#### Interesting / Keep in mind

##### [JAXNS: a high-performance nested sampling package based on JAX](https://arxiv.org/abs/2012.15286)
- #inference #statistics #bayesian [[Bayesian Sampling Tools]]
- We present JAX-based nested sampling (JAXNS), a high-performance nested sampling package written in XLA-primitives using JAX, and show that it is several orders of magnitude faster than the currently available nested sampling implementations of PolyChord, MultiNEST, and dynesty
- 值得尝试

##### [A hybrid Fourier--Real Gaussian Mixture method for fast galaxy--PSF convolution](https://arxiv.org/abs/2012.15797)
- #photometry [[References of Photometric Methods]]
- Fast convolution of a model galaxy profile by a point-spread function (PSF) model represented as a pixel grid.
- 方法基于如下三点：
	- 1. ost simple radial galaxy profiles of common interest (deVaucouleurs, exponential, Sersic) can be approximated as mixtures of Gaussians.
	- 2. The Fourier transform of a Gaussian is a Gaussian, thus the Fourier transform of a mixture-of-Gausssian approximation of a galaxy can be directly evaluated as a mixture of Gaussians in Fourier space.
	- 3. If a mixture component would result in Fourier-space aliasing, that component can be evaluated in real space.
- The method is fast and exact (to the extent that the mixture-of-Gaussians approximation of the galaxy profile is exact) as long as the pixelized PSF model is well sampled
- This Fourier method can be seen as a way of applying a perfect low-pass filter to the (typically strongly undersampled) galaxy profile before convolution by the PSF, at exactly the Nyquist frequency of the PSF pixel model grid.
- 展示代码在: https://github.com/dstndstn/fft-gal-convolution
- 方法已经在Tractor中使用；A lot of the computational cost of this method is in evaluating the exp function rather than in the FFT or inverseFFT, so [fast exp approximations](https://github.com/herumi/fmath) could provide significant speedups

##### [Principled point-source detection in collections of astronomical images](https://arxiv.org/abs/2012.15836)
- #photometry 
- We review the well-known matched filter method for the detection of point sources in astronomical images. This is shown to be optimal (that is, to saturate the Cramer--Rao bound) under stated conditions that are very strong: an isolated source in background-dominated imaging with perfectly known background level, point-spread function, and noise models.
- We show that the matched filter produces a maximum-likelihood estimate of the brightness of a purported point source, and this leads to a simple way to combine multiple images---taken through the same bandpass filter but with different noise levels and point-spread functions---to produce an optimal point source detection map.
- 给出了基于SED的matched filter方法，能优先探测到特定颜色的点源

#### Others

##### [Stability of Cool Cores During Galaxy Cluster Growth: A Joint Chandra/SPT Analysis of 67 Galaxy Clusters Along a Common Evolutionary Track Spanning 9 Gyr](https://arxiv.org/abs/2012.14669)
- #intra_cluster_medium #cluster_galaxies [[Intra-Cluster Medium - 2021]]
- We develop a new procedure in order to tackle the analysis challenge that is estimating the intracluster medium (ICM) properties of low-mass and high-redshift clusters with ∼150 X-ray counts.
- We show that we can decrease the uncertainty on the density profile by a factor ∼5 with a joint deprojection of the X-ray surface brightness profile measured by Chandra and the SZ integrated Compton parameter available in the SPT cluster catalog.
- We confirm that the evolution of the gas density profile is well modeled by the combination of a fixed core and a self-similarly evolving non-cool core profile
- 尽管cluster质量不断增长，但Cool Core cluster比例基本不变

##### [The Fast Radio Burst Dispersion Measure Distribution](https://arxiv.org/abs/2012.15051)
- #fast_radio_burst 
- We compare the dispersion measure (DM) statistics of FRBs detected by the ASKAP and Parkes radio telescopes. We jointly model their DM distributions, exploiting the fact that the telescopes have different survey fluence limits but likely sample the same underlying population.
- Assuming a one-to-one mapping between DM and redshift for an homogeneous intergalactic medium (IGM), we determine the best-fit parameters of the population spectral index and the power-law index of the burst energy distribution for different redshift evolutionary models.
- We find no evidence that the FRB population evolves faster than linearly with respect to the star formation rate over the DM (redshift) range for the sampled population.

##### [MERGHERS Pilot: MeerKAT discovery of diffuse emission in nine massive Sunyaev-Zel'dovich-selected galaxy clusters from ACT](https://arxiv.org/abs/2012.15088)
- #intra_cluster_medium #radio_galaxy 
- Test the feasibility of using MeerKAT for a large cluster study using short (0.2--2.1 hour) integration times.
- 观测13个ACT DR5中的大质量星系团：With a 70 per cent detection rate (9/13 clusters), this pilot study validates our proposed MERGHERS observing strategy and provides twelve detections of diffuse emission, eleven of them new

##### [Jet collimation in NGC 315 and other nearby AGN](https://arxiv.org/abs/2012.14831)
- These results suggest that disk winds play an important role in the jet collimation mechanism, particularly in high-luminosity sources. The impact of winds for the origin of the FRI/FRII dichotomy in radio galaxies is also discussed.

##### [Properties of a Previously Unidentified Instrumental Signature in Kepler/K2 that was Confused for AGN Variability](https://arxiv.org/abs/2012.14452)
- Weakly illuminated pixels are dominated by low frequency trends that are both non-astrophysical and correlated from object to object.
- A critical clue to understanding this instrumental noise is that different targets observed in the same channels of Campaign 8 (rear facing) and Campaign 16 (forward facing) had nearly identical light curves after time reversal of one of the campaigns
	- The underlying problem relates to the relative Sun-spacecraft-field orientation, which was approximately the same on day 1 of Campaign 8 as the last day of Campaign 16.

##### [Satellites and central galaxies in SDSS: the influence of interactions on their properties](https://arxiv.org/abs/2012.14782)
- We find that central galaxies showing signs of interactions present evidence of enhanced star formation activity and younger stellar populations. As a counterpart, satellite samples show these galaxies presenting older stellar populations with a lower star formation rate than the control sample

##### [Reverberation Mapping of Changing-look Active Galactic Nucleus NGC 3516](https://arxiv.org/abs/2012.15572)
- Lijiang 2.4m 6个月的检测: These RM results are consistent with other observations before the spectral type change, indicating a basically constant BLR structure during the changing-look process.


### Jan 4 

#### Relevant / Important / Useful

##### Miyatake et al. 2021 - [Cosmological inference from emulator based halo model I: Validation tests with HSC and SDSS mock catalogs](https://arxiv.org/abs/2101.00113)

- [[Cosmology Emulator]] - #emulator 
- We present validation tests of emulator-based halo model method for cosmological parameter inference based on the Dark Emulator developed by Nishimichi et al. 基于SDSS和HSC-Y1观测
- Adopting the halo occupation distribution, the emulator allows us to obtain model predictions of ΔΣ and wp for the SDSS-like galaxies at a few CPU seconds for an input set of parameters. 
- Even for the assembly bias mock, we demonstrate that the cosmological parameters can be recovered _if_ the analysis is restricted to scales R≳10 h−1Mpc.

#### Interesting / Keep in mind

##### [High-redshift SMBHs can grow from stellar-mass seeds via chaotic accretion](https://arxiv.org/abs/2101.00209)

- #smbh
- Even the most extreme black hole known can grow from a 10M⊙ seed black hole via Eddington-limited luminous accretion, provided that accretion proceeds almost continuously, but is composed of a large number of episodes with individually-uncorrelated initial directions.
- 混沌的吸积 --> SMBH的spin很低 --> 辐射效率很低

#### Others

##### [VLT Spectroscopy of Ultra-Faint Dwarf Galaxies. 1. Boötes I, Leo IV, Leo V](https://arxiv.org/abs/2101.00013)

 - After removing binary stars, we recalculate the velocity dispersions of Bootes I and Leo IV to be 5.1+0.6−0.7 and 3.6+1.0−1.1 km s−1
 - Combining the VLT data with previous literature, we re-analyze the Bootes I metallicity distribution function and find that a model including infall of pristine gas while Bootes I was forming stars best fits the data

##### [Physical conditions and redshift evolution of optically thin C III absorbers: Low-z sample](https://arxiv.org/abs/2101.00032)

- 99 optically thin C III absorption systems at redshift, 0.2≤z≤0.9 associated with neutral hydrogen column densities in the range 光致电离模型得到n_H, C-丰度，LOS厚度 - 和高红移的系统比有很强的演化
- We find that the slope of \[C/H\] vs. z for C III absorbers is steeper compared to the redshift evolution of cosmic metallicity of the

##### [PKS1830-211: OH and HI at z=0.89 and the first MeerKAT UHF spectrum](https://arxiv.org/abs/2101.00188)

- 科学展示：90分钟on-source观测得到了透镜射电源PKS1830-211的HI和OH吸收信号，信噪比很高
- We decompose the OH lines into a thermal and a stimulated contribution, where the 1720 and 1612 MHz lines are conjugate. The total OH 1720 MHz emission line luminosity is 6100 L\_sun 已知最强的OH Maser信号

##### [The MUSE-Faint survey. II. The dark matter-density profile of the ultra-faint dwarf galaxy Eridanus 2](https://arxiv.org/abs/2101.00253)

- We constrain models of cold dark matter, self-interacting dark matter, and fuzzy dark matter with these tracers, using CJAM and pyGravSphere for the dynamical analysis.
- We find substantial evidence for cold dark matter over self-interacting dark matter and also substantial evidence for fuzzy dark matter over cold dark matter.
- We do not resolve a core (rc≲35pc, 68-% level) or soliton

##### [A Nearby Galaxy Perspective on Dust Evolution. Scaling relations and constraints on the dust build-up in galaxies with the DustPedia and DGS samples](https://arxiv.org/abs/2101.00456)

- #inference #dust
- 800个近邻星系的尘埃SED性质的Hierarchical Bayesian分析：we have inferred the timescales of dust condensation in core-collapse supernova ejecta, grain growth in cold clouds and dust destruction by shock waves
- Dust-to-metal质量比例随金属丰度变化极大，可达2个数量级
- 在低金属丰度上核坍缩超新星对生成尘埃很有效；~1/5 Zsun金属丰度以上主要靠尘埃颗粒的生长
- Shock destruction is relatively efficient, a single supernova clearing dust on average in at least ~1200 Msun/SN of gas
- We show that early-type galaxies are outliers in several scaling relations. This feature could result from grain thermal sputtering in hot X-ray emitting gas

##### [The prospects for observing \[OIII\] 52 micron emission from galaxies during the Epoch of Reionization](https://arxiv.org/abs/2101.00662)

- The \[OIII\] 88 μm line observations leave, however, a degeneracy between the gas density and metallicity in these systems 用 \[OIII\] 52 μm line 解简并
- 给出一些预测：We suggest SXDF-NB1006-2 as a promising first target for 52 μm line measurements.

##### [The relation between AGN type and host galaxy properties](https://arxiv.org/abs/2101.00724)

- We find that the correlation between LX and SFRnorm, follows approximately the same trend for both absorbed and unabsorbed sources, a result that favours the standard AGN unification models

##### [IGM Transmission Bias for z ≥ 2.9 Lyman Continuum Detected Galaxies](https://arxiv.org/abs/2101.00727)

- 研究LyC光子逃逸率与高红移观测到的$f_{\rm esc}$分布的关系：We show that LyC detected galaxies are more likely to be found in sightlines with higher-than-average transmission of LyC photons.
	- 如果对这些LyC detected星系假设一个平均的transmission function，会高估$f_{\rm esc}$
- We quantify this IGM transmission bias for LyC detections in photometric and spectroscopic surveys in the literature and show that the bias is stronger for both shallower observations and for fainter parent samples

##### [Compact Molecular Gas Distribution in Quasar Host Galaxies](https://arxiv.org/abs/2101.00764)

- ALMA观测6个低红移P-G QSO: the quasar host galaxies possess exceptionally compact, disky molecular gas distributions with a median half-light radius of 1.8 kpc and molecular gas mass surface densities ≳22 M⊙pc−2.
- With rotation velocity-to-velocity dispersion ratio ≳9, the nuclear region displays substantial kinematic complexity associated with small-scale substructure in the gas distribution.

##### [Estimation of the size and structure of the broad line region using Bayesian approach](https://arxiv.org/abs/2101.00802)

- We performed systematic modeling of the continuum and emission line light curves using a Markov Chain Monte Carlo method based on Bayesian statistics implemented in PBMAP (Parallel Bayesian code for reverberation-MAPping data) code to constrain BLR geometrical parameters and recover velocity integrated transfer function.
- We found a non-linear response of emission line fluxes to the ionizing optical continuum for 93\% objects. The estimated virial factors for the AGN studied in this work range from 0.79 to 4.94 having a mean at 1.78 (+/-) 1.77 consistent with the values found in the literature.

##### [Ultra-faint \[CII\] emission in a redshift-2 gravitationally-lensed metal-poor dwarf galaxy](https://arxiv.org/abs/2101.00841)

- ALMA \[CII\] and PdBI CO(2-1) observations of a z=1.8, strongly lensed EELG SL2S 0217, a bright Lyman-α emitter with a metallicity 0.05 Z⊙. We obtain a tentative (3-4σ) detection of the \[CII\] line and set an upper limit on the \[CII\]/SFR ratio 
- The CO(2-1) emission is not detected. Photoionization modelling indicates that up to 80% of the \[CII\] emission originates from neutral or molecular gas, although we can not rule out that the gas is fully ionized.
- The very faint \[CII\] emission is in line with both nearby metal-poor dwarfs and high-redshift Lyman-α emitters, and predictions from hydrodynamical simulations.

##### [Rivers of Gas I.: Unveiling The Properties of High Redshift Filaments](https://arxiv.org/abs/2101.00844)

- RAMSES模拟一个高红移银河系质量星系周围的气体纤维：Radial density profiles of both gas and DM filaments are found to have the same functional form, namely a plummer-like profile modified to take into account the wall within which these filaments are embedded.
- Measurements of the typical filament core radius r0 from the simulation are consistent with that of isothermal cylinders in hydrostatic equilibrium

### Jan 5 

#### Relevant / Important / Useful

##### [Stacked phase-space density of galaxies around massive clusters: A theoretical framework and application to real data](https://arxiv.org/abs/2101.01342)

- #cosmology/cluster #ssst/cos [[Cluster Phase Space]]
- 理论模型预测 predict average histograms of line-of-sight velocities over pairs of galaxies and galaxy clusters. 
- A simple likelihood analysis with our model enables us to infer the three-dimensional velocity dispersion of observed galaxies in massive clusters.
- Our results confirm that the relation between the galaxy velocity dispersion and the host cluster mass in our sample is consistent with the prediction in dark-matter-only N-body simulations.
- 重要背景：The stacked velocity distribution of galaxies around clusters, referred to as the stacked phase-space density, has drawn much attention as a probe of the average dynamical mass estimate and galactic orbits in the cluster regime (Wojtak et al. 2009), the physics of star formation quenching (Haines et al. 2015; Adhikari et al. 2019), and large-scale galaxy infall (Aung et al. 2020; Tomooka et al. 2020).

##### [The Growth of Intracluster Light in XCS-HSC Galaxy Clusters from 0.1<z<0.5](https://arxiv.org/abs/2101.01644)

- #cluster/icl #galaxy/stellar_halo #survey/hsc
- 18个XMM Cluster Survey里的星系团：We apply a rest-frame μB\=25 mag/arcsec2 isophotal threshold to our clusters, below which we define light as the ICL
- We find that the ICL makes up about ∼ 24% of the total cluster stellar mass on average (∼ 41% including the flux contained in the BCG within 50 kpc)
- We find no evidence for any links between the amount of ICL flux with cluster mass, but find a growth rate of 2−4 for the ICL between 0.1<z<0.5.
- **Comment**: ICL的定义很随意；而且sky subtraction的改正基本不可能做对

##### [A Composite Likelihood Approach for Inference under Photometric Redshift Uncertainty](https://arxiv.org/abs/2101.01184)

- #photo-z #lsst
- We combine the redshift information from the galaxy photometry with constraints from two-point functions, utilizing cross-correlations with spatially overlapping spectroscopic samples. Our likelihood framework is designed to integrate directly into a typical large-scale structure and weak lensing analysis based on two-point functions.
- We evaluate and forecast photometric redshift performance using data from the CosmoDC2 simulations, within which we mimic a DESI-like spectroscopic calibration sample for cross-correlations.

#### Interesting / Keep in mind

##### [Radio halos in a mass-selected sample of 75 galaxy clusters. II. Statistical analysis](https://arxiv.org/abs/2101.01641)

- #intra_cluster_medium #galaxy_cluster
- We used the dynamical information derived from the X-ray data to assess the role of mergers in the origin of radio halos
	- We found that the fraction of radio halos drops from ~70% in high mass clusters to ~35% in the lower mass systems of the sample and we showed that this result is in good agreement with the expectations from turbulent re-acceleration models.
- 看射电晕的频率和质量的关系，并合湍动加速模型比较
	- We found that more than the 90% of radio halos are in merging clusters and that their radio power correlates with the mass of the host clusters. 但弥散很大
- 星系团的动力学状态影响很大：越disturbed的星系团，射电光度越高；Clusters without radio halos are generally relaxed and the upper limits to their diffuse emission lie below the correlation

##### [Stromlo Stellar Tracks: non-solar scaled abundances for massive stars](https://arxiv.org/abs/2101.01197)

- #stellar/evolution
- [Stromlo Stellar Tracks](https://sites.google.com/view/stromlotracks)
- MESA; fit the Galactic Concordance abundances for hot (T\>8000 K) massive (≥10M⊙) Main-Sequence (MS) stars.
- The Stromlo tracks cover massive stars (10≤M/M⊙≤300) with varying rotations (v/vcrit\=0.0,0.2,0.4) and a finely sampled grid of metallicities (−2.0≤\[Z/H\]≤+0.5; Δ\[Z/H\]\=0.1) evolved from the pre-main sequence to the end of 12Carbon burning.
- 使用Galactic Concordance abundances对高温大质量恒星很重要
- 凸显了自转的重要性

##### [A cuspy dark matter halo](https://arxiv.org/abs/2101.01282)

- #galaxy/udg #galaxy/dwarf
- Spatially-resolved mapping of gas dynamics toward a nearby ultra-diffuse galaxy (UDG), AGC 242019
- The derived rotation curve of dark matter is well fitted by the cuspy profile as described by the Navarro-Frenk-White model
- The modified Newtonian dynamics is also inconsistent with a shallow radial acceleration relationship of AGC 242019
- As a UDG, AGC 242019 is in a dwarf-size halo with weak stellar feedback, late formation time, a normal baryonic spin and low star formation efficiency (SFR/gas).

#### Others

##### [Toward Cosmicflows-4: The HI data catalog](https://arxiv.org/abs/2101.01515)

- All Digital HI (ADHI) catalog consists of the previous release augmented with our new HI observations and an analysis of archival data. 主要目标是通过TF关系测量旋涡星系的距离
- The ADHI database contains 18,874 galaxies, for which 15,433 have good quality data for TF use.

##### [Starlet l1-norm for weak lensing cosmology](https://arxiv.org/abs/2101.01542)

- #weak_lensing 
- 能够从WL观测中提取高阶信息的新summary statistics: We name this statistic the 'starlet ℓ1\-norm' as it is computed via the sum of the absolute values of the starlet (wavelet) decomposition coefficients of a weak lensing map
- 和peak count以及minimum count比较：The ℓ1-norm carries the information encoded in all pixels of the map, not just the ones in local maxima and minima.
	- 而且不需要担心peak和minimum的定义

##### [Radio halos in a mass-selected sample of 75 galaxy clusters. I. Sample selection and data analysis](https://arxiv.org/abs/2101.01640)

- #intra_cluster_medium #galaxy_cluster
- 75个Planck SZ样本中挑选的大质量星系团：GMRT + VLA + Chandra, This observational campaign led to the detection of several cluster-scale diffuse radio sources and candidates that deserve future follow-up observations
- We have built the largest mass-selected (> 80 per cent complete in mass) sample of galaxy clusters with deep radio observations available to date.


##### [Measurements of the E-Mode Polarization and Temperature-E-Mode Correlation of the CMB from SPT-3G 2018 Data](https://arxiv.org/abs/2101.016840)

- #cmb
- We find that the SPT-3G dataset is well-fit by a ΛCDM cosmological model with parameter constraints consistent with those from Planck and SPTpol data. From SPT-3G data alone, we find H0\=68.8±1.5kms−1Mpc−1 and σ8\=0.789±0.016, with a gravitational lensing amplitude consistent with the ΛCDM prediction (AL\=0.98±0.12).

##### [The impact of inhomogeneous subgrid clumping on cosmic reionization II: modelling stochasticity](https://arxiv.org/abs/2101.01712)

- #cosmology/reionization
- In Mao et al. 2019 (Paper I) we presented an improved, local density-dependent model for the sub-grid gas clumping. Here we extend this using an _empirical stochastic model_ based on the results from high-resolution numerical simulations which fully resolve all relevant fluctuations. 
- Our results show that the simplistic mean clumping model delays reionization compared to local density-dependent models, despite producing fewer recombinations overall.

##### [Laboratory Measurements of Instrumental Signatures of the LSST Camera Focal Plane](https://arxiv.org/abs/2101.01281)

- #lsst
- Testing of the camera sensors is performed using a set of custom-built optical projectors, designed to illuminate the full focal plane or specific regions of the focal plane with a series of light illumination patterns: the crosstalk projector, the flat illuminator projector, and the spot grid projector.
- In addition to measurements of crosstalk, linearity and full well, the ability to project realistically-sized sources, using the spot grid projector, makes possible unique measurements of instrumental signatures such as deferred charge distortions, astrometric shifts due to sensor effects, and the brighter-fatter effect, prior to camera first light.

##### [Searching for energy-resolved quasi-periodic oscillations in AGN](https://arxiv.org/abs/2101.01194)

- X-ray quasi-periodic oscillations (QPOs) in AGN allow us to probe and understand the nature of accretion in highly curved space-time
- We report QPO candidates in 6 AGN (7 including one tentative detection in MRK~766) from our sample of 38, which tend to be found at characteristic energies and, in four cases, at the same frequency across at least two observations, indicating they are highly unlikely to be spurious in nature.

##### [Regulating Star Formation in Nearby Dusty Galaxies: Low Photoelectric Efficiencies in the Most Compact Systems](https://arxiv.org/abs/2101.01182)

- We find that star-forming, IR luminous galaxies in the Great Observatories All-Sky LIRG Survey (GOALS) with high IR surface densities have low photoelectric efficiencies. These systems also have, on average, higher ratios of radiation field strength to gas densities, and larger average dust grain size distributions.
- The most compact galaxies have more young star-forming regions per unit area, which exhibit less efficient gas heating
- Diaz-Santos et al. (2017):  $\log \left(\mathrm{L}_{\text {line }} / \mathrm{L}_{\mathrm{IR}}\right)=a_{0}+a_{1} \log \Sigma_{\mathrm{IR}}+a_{2}\left(\log \Sigma_{\mathrm{IR}}\right)^{2}$
- $\log \Sigma_{\mathrm{IR}}=\log \left(0.5 \mathrm{~L}_{\mathrm{IR}} / \pi \mathrm{R}_{\mathrm{eff}, 70 \mu m}^{2}\right)$
- 本文的重点是定义了一个 Photoelectric Efficiency 的量
	- The fraction of energy that photoelectrons from PAHs transfer from UV photons into the gas relative to the total heating of dust
	- Assuming that the PAHs and ions are co-spatial such that the energy input into the gas by photoelectric heating powers the \[C II\], \[O I\], and \[Si II\] lines, an empirical tracer of the photoelectric efficiency
	- $$\epsilon_{\mathrm{PE}} \approx \frac{\mathrm{L}_{[\mathrm{CII}]}+\mathrm{L}_{[\mathrm{OI}]}+\mathrm{L}_{[\mathrm{Si} \mathrm{II}]}}{\mathrm{L}_{\mathrm{PAH}}}
	$$

##### [Lyman-α emission from a WISE-selected optically faint powerful radio galaxy M151304.72-252439.7 at z \= 3.132](https://arxiv.org/abs/2101.01192)

- 一个核心射电辐射弱，但有大尺度射电双瓣的高红移射电星系
- Based on long-slit spectroscopy and narrow band imaging centered on the Lyα emission, we identify two spatial components: a "compact component" with high velocity dispersion (∼1500kms−1) seen in all three lines, and an "extended component", having low velocity dispersion (i.e., 700-1000kms−1)
- We also detect spatially extended associated Lyα absorption, which is blue-shifted within 250-400kms−1 of the Lyα peak. The probability of Lyα absorption detection in such large radio sources is found to be low (∼10%)

##### [The rapid transition from star-formation to AGN dominated rest-frame UV light at z ~ 4](https://arxiv.org/abs/2101.01195)

- We find a rapid transition to AGN-dominated sources bright-ward of MUV≃−23.2.
	- The effect is observed in the rest-frame UV morphology and size-luminosity relation, where extended clumpy systems become point-source dominated, and also in the available spectra for the sample.

##### [Dating individual quasars with the HeII proximity effect](https://arxiv.org/abs/2101.01196)

- #smbh
- Due to the ~30 Myr equilibration time-scale of HeII in the z~3 IGM, the size of the HeII proximity zone depends on the time the quasar had been active before our observation
- 13个QSO的HST观测：spanning ~2 to ~15 proper Mpc.
- Comparing these sizes to predictions from cosmological hydrodynamical simulations post-processed with one-dimensional radiative transfer, we infer a broad range of quasar on-times from t\_on<1 Myr to t\_on>30 Myr that does not depend on quasar luminosity, black hole mass, or Eddington ratio.

##### [Mass accretion rates and multi-scale halo environment in cold and warm dark matter cosmologies](https://arxiv.org/abs/2101.01198)

- #halo/assemby_bias
- As expected from excursion set models, WDM haloes have higher specific accretion rates, dominated by the accretion of diffuse mass, as compared to CDM haloes.
- For low-mass WDM haloes, we find that the environment-dependence of both diffuse mass accretion as well as accretion by mergers is almost fully explained by α, the tidal anisotropy
- We detect, for the first time, a significant and evolving assembly bias due to diffuse mass accretion for low-mass CDM and WDM haloes (after excluding splashback objects), with a z\=0 strength higher than with almost all known secondary variables and largely explained by α. [[Assembly Bias]]

##### [Subaru High-z Exploration of Low-Luminosity Quasars (SHELLQs) XII. Extended \[C II\] Structure (Merger or Outflow) in a z = 6.72 Red Quasar](https://arxiv.org/abs/2101.01199)

- ALMA观测已知最远的red quasar
- The FIR continuum of J1205−0000 is bright; The \[C II\] line emission is extended on scales of r∼5 kpc, greater than the FIR continuum.
- The outflow kinetic energy and momentum are both much smaller than what predicted in energy-conserving wind models, suggesting that the AGN feedback in this quasar is not capable of completely suppressing its star formation.

##### [The Evolution of the Lyman-Alpha Luminosity Function During Reionization](https://arxiv.org/abs/2101.01205)

- 原理：Neutral hydrogen in the intergalactic medium (IGM) attenuates Lyα photons emitted by galaxies. As reionization progressed the IGM opacity decreased, increasing Lyα visibility. The galaxy Lyα luminosity function (LF) is thus a useful tool to constrain the timeline of reionization.
- 给 $5 < z < 10$的Lya LF建模：As the neutral fraction increases, the average number density of Lyα emitting galaxies decreases, and are less luminous, though for $\bar{x}_{\rm HI} < 0.4$ there is only a small decrease of the Lyα LF.
- 可以反过来用观测的Lya LF推测中性氢比例: as the neutral fraction increases, the faint-end slope of the Lyα LF steepens, and the characteristic Lyα luminosity shifts to lower values, concluding that the evolving shape of the Lyα LF -- not just its integral - is an important tool to study reionization.

##### [Observing the host galaxies of high-redshift quasars with JWST: predictions from the BlueTides simulation](https://arxiv.org/abs/2101.01219)
- We produce mock images of a sample of z~7 quasars extracted from the BlueTides simulation, and apply Markov Chain Monte Carlo-based PSF modelling to determine the detectability of their host galaxies with the James Webb Space Telescope (JWST).
- Exposure times of ~5 ks are required to detect the majority of host galaxies in the NIRCam wide-band filters, however even 10 ks exposures with MIRI result in <30% successful host detections.
- 能否探测到和host星系性质关系不大
- [`SynthObs` - package for producing synthetic observations from SPH simulations](https://github.com/stephenmwilkins/SynthObs)

##### [The Panchromatic Hubble Andromeda Treasury: Triangulum Extended Region (PHATTER) I. Ultraviolet to Infrared Photometry of 22 Million Stars in M33](https://arxiv.org/abs/2101.01293)

- 多波段数据：Advanced Camera for Surveys (ACS) in the optical (F475W, F814W), and the Wide Field Camera 3 (WFC3) in the near ultraviolet (F275W, F336W) and near-infrared (F110W, F160W) bands
- The photometry reaches a completeness-limited depth of F475W∼28.5 in the lowest surface density regions observed in M33 and F475W∼26.5 in the most crowded regions found near the center of M33.
- We find the young populations trace several relatively tight arms, while the old populations show a clear, looser two-armed structure.
- [`gaia\_alignment`](https://github.com/spacetelescope/gaia_alignment)
	- This repository contains tools used for aligning HST images to Gaia.

##### [The MOSDEF Survey: Environmental dependence of the gas-phase metallicity of galaxies at 1.4≤z≤2.6](https://arxiv.org/abs/2101.01706)

- Based on rest-frame optical emission lines, \[NII\]λ6584 and Hα, we measure gas-phase oxygen abundance of 167 galaxies at 1.37≤z≤1.7 and 303 galaxies at 2.09≤z≤2.61, located in diverse environments.
- We find that at z∼1.5, the average metallicity of galaxies in overdensities is higher than in the field 但这种金属丰度的增高在z=2.3不存在
- Our results support the hypothesis that, at the early stages of cluster formation, owing to efficient gas cooling, galaxies residing in overdensities host a higher fraction of pristine gas with prominent primordial gas accretion, which lowers their gas-phase metallicity compared to their coeval field galaxies.


### Jan 6 

#### Relevant / Important / Useful

##### [The Clusters Hiding in Plain Sight (CHiPS) survey: Complete sample of extreme BCG clusters](https://arxiv.org/abs/2101.01730)

- #cluster/x-ray
- Designed to find new galaxy clusters with extreme central galaxies that were misidentified as bright isolated sources in the ROSAT All-Sky Survey catalog.
- CHIPS1356-3421 and CHIPS1911+4455. Both clusters are luminous enough to be detected in the ROSAT All Sky-Survey data if not because of their bright central cores.
- We find the occurrence rate for clusters that would appear to be X-ray bright point sources in the ROSAT All-Sky Survey (and any surveys with similar angular resolution) to be 2+/-1%

##### [The Three Hundred Project: The gas disruption of infalling objects in cluster environments](https://arxiv.org/abs/2101.01734)

- #cluster/galaxy [[Cluster Phase Space]]
- We confirm the Arthur et al. (2019) result and identify a characteristic radius around 1.7R200 in 3D and at R200 in projection at which infalling haloes lose nearly all of the gas prior their infall.
- Splitting the trends by subhalo status we show that subhaloes residing in group-mass and low-mass host haloes in the infall region follow similar radial gas-loss trends as their hosts, whereas subhaloes of cluster-mass host haloes are stripped of their gas much further out

#### Interesting / Keep in Mind

##### [Completeness of the Gaia-verse IV: The Astrometry Spread Function of Gaia DR2](https://arxiv.org/abs/2101.01723)

- #gaia
- Astrometry Spread Function (ASF), the expected uncertainty in the measured positions, proper motions and parallax for a non-accelerating point source.
- The ASF will enable characterisation of binary systems, exoplanet orbits, astrometric microlensing events and extended sources which add an excess astrometric noise to the expected astrometry uncertainty. By using the ASF to estimate the unit weight error (UWE) of Gaia DR2 sources, we demonstrate that the ASF indeed provides a direct probe of the excess source noise.
- **Note** 有助于识别extended source
- [`scanninglaw`](https://github.com/gaiaverse/scanninglaw)

##### [The Clusters Hiding in Plain Sight (CHiPS) survey: CHIPS1911+4455, a Rapidly-Cooling Core in a Merging Cluster](https://arxiv.org/abs/2101.01731)

- #cluster/x-ray #cluster/cool-core #cluster/icm
- CHIPS1911+4455:  中心有Cool core; 大尺度上不对称；pointing to a more dynamically active and turbulent cluster. 中心SFR在140-190 Msun/yr
- One possible scenario for CHIPS1911+4455 is that the cool core was displaced during a major merger and rapidly cooled, with cool, star-forming gas raining back toward the core.

#### Others

##### [Structure formation in large-volume cosmological simulations of fuzzy dark matter: Impact of the non-linear dynamics](https://arxiv.org/abs/2101.01828)

- An ultra-light bosonic particle of mass in the range ≈10^{−22} eV/c2 is of special interest, as it both has particle physics motivations, and may give rise to notable differences in the structures on highly non-linear scales due to the manifestation of quantum-physical wave effects on macroscopic scales.
- Unlike in ΛCDM, it is computationally challenging to accurately treat the growth on large scales in FDM, even in the regime where this follows linear theory.
- FDM shows a pronounced suppression of power on small scales relative to cold dark matter (CDM), which can be understood as a damping effect due to 'quantum pressure'.
- The halo mass functions are identical for massive haloes, but FDM shows a significant abundance reduction below a characteristic mass scale.

##### [The Connection between Mergers and AGN Activity in Simulated and Observed Massive Galaxies](https://arxiv.org/abs/2101.01729)

- 通过Zoom-in模拟+辐射转移代码: We find that, in both the simulations and CANDELS, even the most luminous (Lbol\>10^{45} erg s−1) AGN in our sample are no more likely than inactive galaxies (Lbol<10^{43} erg s−1) to be found in merging systems
- Even gas rich major mergers (stellar mass ratio \>1:4) do not necessarily enhance AGN activity or significantly grow the central SMBH

##### [ALMA Lensing Cluster Survey: a strongly lensed multiply imaged dusty system at z≥6](https://arxiv.org/abs/2101.01740)

-  A ≃4σ dust detection is seen at 1.2mm as part of the ALMA; redshift from \[CII\] 158 micron.
-  恒星质量在 3x10^9 Msun; 尘埃质量 5x10^6 Msun; Size=0.54 kpc; a luminosity-weighted age of 200±100 Myr.

##### [VLA Imaging of HI-bearing Ultra-Diffuse Galaxies from the ALFALFA Survey](https://arxiv.org/abs/2101.01753)

- #galaxy/udg #galaxy/lsb
- The HUDs show ordered gas distributions and evidence of rotation, important prerequisites for the detailed kinematic models 
- HI经常比stellar body延展，而且有misalignment
- We explore the HI mass-diameter scaling relation, and find that although the HUDs have diffuse stellar populations, they fall along the relation, with typical global HI surface densities

##### [SITELLE Hα Imaging Spectroscopy of z~0.25 Clusters: Emission Line Galaxy Detection and Ionized Gas Offset in Abell 2390 & Abell 2465](https://arxiv.org/abs/2101.01887)

- #cluster/galaxy
- We present results based on the spatial offsets between the emission-line regions and stellar continua in ELGs from two z∼0.25 galaxy clusters, Abell 2390 and Abell 2465
- Combining the two clusters, there is a 3σ excess for high-velocity galaxies within the virial radius having the offsets to be pointed away from the cluster center. 
- Assuming the offset being a proxy for the velocity vector of a galaxy, as expected from ram pressure stripping, this excess indicates that ram pressure stripping occurs most effectively during the first passage of an infalling galaxy

##### [ALMA Lensing Cluster Survey: Bright \[CII\] 158 μm Lines from a Multiply Imaged Sub-L⋆ Galaxy at z\=6.0719](https://arxiv.org/abs/2101.01937)

- The \[CII\] line properties suggest that the LBG is a rotation-dominated system whose velocity gradient explains a slight difference of redshifts between the whole LBG and its sub region.
- The star formation rate (SFR)-L\[CII\] relations from the sub to the whole regions of the LBG are consistent with those of local galaxies

##### [First observed interaction of the circumstellar envelope of an S-star with the environment of Sgr A\*](https://arxiv.org/abs/2101.02077)

- We revisit the most prominent dusty and gaseous bow shock source, X7, close to the supermassive black hole, Sgr~A\*
- By analyzing the line maps of SINFONI, we identify a velocity of ∼200 km/s from the tip to the tail. 
- Observations after 2010 show that the dust and the gas shell seems to be decoupled in projection from its stellar source S50. The data also implies that the tail of X7 gets thermally heated up due to the presence of S50.

##### [The black hole masses of extremely luminous radio-WISE selected galaxies](https://arxiv.org/abs/2101.02101)

- We use the broad \[OIII\]λ5007 emission lines as a proxy for the bolometric AGN luminosity, and derive lower limits to supermassive black hole masses of $10^{7.9}$\-$10^{9.4}$ M⊙ with expectations of corresponding host masses of $10^{10.4}$\-$10^{12.0}$ M⊙

##### [PHANGS-HST: Star Cluster Spectral Energy Distribution Fitting with CIGALE](https://arxiv.org/abs/2101.02134)

- We report on the properties of clusters in NGC 3351 and find, on average, the clusters residing in the inner star-forming ring of NGC 3351 are young (<10 Myr) and massive (10^5M⊙) while clusters in the stellar bulge are significantly older.
- We explore a Bayesian analysis with additional physically-motivated priors for the distribution of ages and masses and analyze the resulting cluster distributions.

##### [Quantitative comparison of opacities calculated using the R-matrix and Distorted-Wave methods: Fe XVII](https://arxiv.org/pdf/2101.01788.pdf)

- [[Opacity Calculation]]


### Jan 7 

#### Relevant / Important / Useful

##### [An Optical Observational Cluster Mass Function at z∼1 with the ORELSE Survey](https://arxiv.org/abs/2101.02215)

- #cluster/cosmology #cluster/finder [[Galaxy Cluster Finders]]

- With ORELSE, a new cluster finding technique based on Voronoi tessellation Monte-Carlo (VMC) mapping, and rigorous purity and completeness testing, we have obtained ∼240 galaxy overdensity candidates in the redshift range 0.55<z<1.37
- We find cosmological constraints on the matter density of Ωm\=0.250+0.104−0.099 and on the amplitude of fluctuations of σ8\=1.150+0.260−0.163.
- VMC mapping will enable optical/NIR cluster cosmology at redshifts much higher than what has been possible before.

##### [CODEX Weak Lensing Mass Catalogue and implications on the mass-richness relation](https://arxiv.org/abs/2101.02257)

- #cluster/cosmology #cluster/x-ray #cosmology/weak_lensing
- CODEX sample contains the largest flux limited sample of X-ray clusters at 0.35<z<0.65: We present here the full results of the CFHT CODEX program on cluster mass measurement
- We combine 25 individual cluster mass likelihoods in a Bayesian hierarchical scheme with the inclusion of optical and X-ray selection functions to derive constraints on the mass-richness relation.
- In comparison to other weak lensing richness-mass relations, we find the normalization of the richness statistically agreeing with the normalization of other scaling relations from a broad redshift range (0.0<z<0.65) and with different cluster selection
- [`ccv` - semi-analytic model of cosmic (co)variance of galaxy cluster weak lensing profiles](https://github.com/danielgruen/ccv)

##### [Impact of the calibration of the Halo Mass Function on galaxy cluster number count cosmology](https://arxiv.org/abs/2101.02501)

- #cluster/cosmology 
- We quantify the impact of uncertainties in HMF parameters on cosmological constraints from cluster catalogs similar to those from Planck, those expected from the Euclid, Roman and Rubin surveys, and from a hypothetical larger future survey
- While current uncertainties on HMF parameters do not substantially impact Planck-like surveys, we find that they can significantly degrade the cosmological constraints for a Euclid-like survey.

##### [Spectroscopic and Photometric Redshift Estimation by Neural Networks For the China Space Station Optical Survey (CSS-OS)](https://arxiv.org/abs/2101.02532)

- #csst #photo-z 
- The 1-dimensional Convolutional Neural Networks (1-d CNN) and Multi-Layer Perceptron (MLP, one of the simplest forms of Artificial Neural Network) are employed to derive the spec-z and photo-z, respectively.
- We find that our networks can provide excellent redshift estimates with accuracies ~0.001 and 0.01 on spec-z and photo-z

##### [Spatially Resolved Stellar Spectroscopy of the Ultra-diffuse Galaxy Dragonfly 44. III. Evidence for an Unexpected Star-Formation History](https://arxiv.org/abs/2101.02220)

- #galaxy/udg #stellar_population 

- KCWI观测：测量星族轮廓
	- We find that DF44 falls below the mass--metallicity relation established by canonical dwarf galaxies
	- We measure a flat radial age gradient and a flat-to-positive metallicity gradient which are inconsistent with the gradients measured in similarly pressure-supported dwarf galaxies.
	- We also measure a flat-to-negative \[Mg/Fe\] gradient such that the central 1.5 kpc of DF44 has stellar population parameters comparable to metal-poor globular clusters
- DF44 does not have internal properties similar to other dwarf galaxies and is inconsistent with it having been puffed up through a prolonged, bursty star-formation history, as suggested by some simulations.
- [`SPI_Utils`](https://github.com/AlexaVillaume/SPI_Utils)

#### Interesting / Keep in Mind

##### [Multi-wavelength view of SPT-CL J2106-5844. The radio galaxies and the thermal and relativistic plasmas in a massive galaxy cluster merger at z>1.1](https://arxiv.org/abs/2101.02216)

- #cluster/igm #cluster/sze
- 看z>1的大质量星系团是否违反LambdaCDM？是否是并合星系团？
- ALMA SZ观测；ASKAP+ATCA；Chandra
	- In the ALMA+ACA SZ data, we reliably identify at high significance two main gas components associated with the mass clumps inferred from weak lensing.
	- The EMU radio observations reveal a diffuse radio structure ~400 kpc in projected extent along the north-west/south-east direction, indicative of strong activity from the active galactic nucleus within the brightest cluster galaxy.

##### [The Hubble Constant from Infrared Surface Brightness Fluctuation Distances](https://arxiv.org/abs/2101.02221)

- Surface brightness fluctuation (SBF) distances for 63 bright, mainly early-type galaxies out to 100 Mpc observed with the Wide Field Camera 3
- The median statistical uncertainty on individual measurements is 4%. We construct the IR SBF Hubble diagram with these distances and constrain H0 using three different treatments of the galaxy velocities.
- From a weighted average of the Cepheid and TRGB calibrations, we derive H0\=73.3±0.7±2.4 km/s/Mpc, where the error bars reflect the statistical and systematic uncertainties.

##### [Euclid preparation: XI. Mean redshift determination from galaxy redshift probabilities for cosmic shear tomography](https://arxiv.org/abs/2101.02228)

- #weak_lensing #photo-z 
- We implement a sufficiently realistic simulation to understand the advantages, complementarity, but also shortcoming of two standard approaches: the direct calibration of ⟨z⟩ with a dedicated spectroscopic sample and the combination of the photometric redshift probability distribution function (zPDF) of individual galaxies.
- The zPDF approach could also be successful if we debias the zPDF using a spectroscopic training sample. This approach requires deep imaging data, but is weakly sensitive to spectroscopic redshift failures in the training sample.

#### Others

##### [Detectability of optical transients with timescales of sub-seconds](https://arxiv.org/abs/2101.02454)

- Organized Autotelescopes for Serendipitous Event Survey (OASES): We search for optical transient sources with durations of ∼0.1 to ∼1.3 s
- From the non-detection result, we derive an upper limit on the event rate of sub-second transients around the ecliptic and the Galactic plane for the first time

##### [High-energy emission from tidal disruption events in active galactic nuclei](https://arxiv.org/abs/2101.02290)

- AGN中发生的TDE有何不同：In these events, the returning tidal debris stream drills through the pre-existing AGN accretion disk near the stream pericenter, destroying the inner disk in the process, and then intersects with the disk a second time at radii ranging from a few to hundreds of times the pericenter distance.
- 有可能从观测上看到"second impact"的迹象: The X-ray hardness and the smoothness of the light curve provide possible means for distinguishing the second impact from ordinary AGN flares, which exhibit softer spectra and more irregular light curves.

##### [Black Hole Mergers from Star Clusters with Top-Heavy Initial Mass Functions](https://arxiv.org/abs/2101.02217)

- Here we compute a new set of GC models, varying the IMF within observational uncertainties. We find that GCs with top-heavy IMFs lose most of their mass within a few Gyr through stellar winds and tidal stripping. Heating of the cluster through BH mass segregation greatly enhances this process.
- GC with top-heavy IMF可以演化到质量被黑洞主导：GCs with top-heavy IMFs also produce many more binary BH (BBH) mergers.
- We also report that one of our GC models with a top-heavy IMF produces dozens of intermediate-mass black holes (IMBHs) with masses M\>100M⊙

##### [On strong correlation between shifted velocity and line width of broad blue-shifted \[OIII\] components in quasars](https://arxiv.org/abs/2101.02465)

- The strong linear correlation can be treated as strong evidence for the broad blue-shifted \[OIII\] components as better indicators of outflows related to central engine in AGN

##### [Uncertainties in Galaxy Rotation Curves](https://arxiv.org/abs/2101.02525)

- We present a new standalone tool, `makemap`, that estimates the fitted velocity at each pixel from Gauss-Hermite fits to a 3D spectral data cube.
- We conclude that kinematic models of well-resolved HI datasets vary widely in their precision and reliability, and therefore potentially in their value for comparisons with predictions from cosmological galaxy formation simulations.

##### [Constraining the Metallicities of Damped Lyα Systems Using Extinction Curves](https://arxiv.org/abs/2101.02548)

##### [Green valley galaxies in the cosmic web: internal versus environmental quenching](https://arxiv.org/abs/2101.02564)

- We find that the fraction of the green galaxies does not depend on the environment and 10%−20% of the galaxies at each environment are in the green valley depending on the stellar mass range chosen.
- We do not find any statistically significant difference between the properties of green galaxies in different environments. We conclude that the environmental factors play a minor role and the internal processes play the dominant role in quenching star formation in the green valley galaxies.

##### [EDGE: Two routes to dark matter core formation in ultra-faint dwarfs](https://arxiv.org/abs/2101.02688)

- Engineering Dwarfs at Galaxy formation's Edge project
- Gravitational potential fluctuations within the central region of the simulated dwarfs kinematically heat the dark matter particles, lowering the dwarfs' central dark matter density.
- 但不一定由气体的内流和外流造成；也可能是来自minor merger的impulsive heating；所以即便是没有SF的dwarf也可以形成core


### Jan 10 

#### Relevant / Important / Useful

##### [Multi-wavelength mock galaxy catalogs of the low-redshift Universe](https://arxiv.org/abs/2101.02717)

- #galaxy_halo
- HOD + Optical-HI scaling relations
- The host halo of each central galaxy is also baryonified with realistic spatial distributions of stars as well as hot and cold gas, along with the corresponding rotation curve.
	- Can optionally include effects such as galactic conformity and colour-dependent galaxy assembly bias.
	
##### [The dependence of subhalo abundance matching on galaxy photometry and selection criteria](https://arxiv.org/abs/2101.02765)

- #galaxy_halo #sham [[Subhalo Abundance Matching]]
- In this paper we introduce a new parametrisation for AM and derive the best-fit AM parameters as a function of various properties of the selection of the galaxy sample and of the photometric definition
- In the optically-selected samples we find strong evidence that the scatter in the galaxy-halo connection increases towards the faint end, and that AM performs better with luminosity than stellar mass

##### [A sparse regression approach to modeling the relation between galaxy stellar masses and their host halos](https://arxiv.org/abs/2101.02986)

- #galaxy_halo #shmr
- 基于EAGLE模拟：The principal component of our governing equation is a third-order polynomial of the host halo mass, which models the stellar-mass halo-mass relation.
- An advantage of sparse regression approaches is that unnecessary terms are removed. Although we include information on halo specific angular momentum, these parameters are discarded by our methodology.
- [Introduction of Sparse Regression](https://cims.nyu.edu/~cfgranda/pages/OBDA_spring16/material/sparse_regression.pdf)

#### Interesting / Keep in Mind

##### [The NANOGrav 11yr Data Set: Limits on Supermassive Black Hole Binaries in Galaxies within 500Mpc](https://arxiv.org/abs/2101.02716)

- We compiled a comprehensive catalog of ~44,000 galaxies in the local universe (up to redshift ~0.05) and populated them with hypothetical binaries, assuming that the total mass of the binary is equal to the SMBH mass derived from global scaling relations.
	- we found that 216 galaxies are within NANOGrav's sensitivity volume.
- We placed constraints on the chirp mass and mass ratio of the 216 hypothetical binaries. For 19 galaxies, only very unequal-mass binaries are allowed, with the mass of the secondary less than 10 percent that of the primary

#### Others

##### [SDSS-IV MANGA: A Star Formation -- Baryonic Mass Relation at Kpc Scales](https://arxiv.org/abs/2101.02711)

- We propose an empirical relation between ΣSFR and the baryonic mass surface density
	- We derive an empirical relation between the ΣSFR and a second degree polynomial of Σb yielding a one-to-one relation between these two observables.

##### [Seeds Don't Sink: Even Massive Black Hole "Seeds" Cannot Migrate to Galaxy Centers Efficiently](https://arxiv.org/abs/2101.02727)

- #smbh
- We find that seed BHs less massive than 10^8M⊙ (i.e., all but the already-supermassive seeds) cannot efficiently sink in typical high-z galaxies. 
- We also discuss two possible solutions: forming a huge number of seeds such that one can end up trapped in the galactic center by chance, or seed BHs being embedded in giant structures (e.g. star clusters) with huge effective masses above the mass threshold.

##### [Probing the existence of a rich galaxy overdensity at z=5.2](https://arxiv.org/abs/2101.02747)

- 17 rest-frame UV selected galaxies (LAEs and LBGs) with 5.15<z\_phot<5.27, candidates to be physically associated with the overdensity, have been observed with the instrument OSIRIS at the GranTeCan telescope
- Beside the SMG HDF850.1, none of the 23 spectroscopically confirmed members are bright in the far-infrared/submm wavelength regime
- The clustering analysis of the whole sample of 23 confirmed members reveals four distinct components in physical space in different evolutionary states, within Delta\_z<0.04 from the central region hosting SMG HDF850.1

##### [The PHANGS-HST Survey: Physics at High Angular resolution in Nearby GalaxieS with the Hubble Space Telescope](https://arxiv.org/abs/2101.02855)

- PHANGS-HST, which is obtaining five band NUV-U-B-V-I imaging of the disks of 38 spiral galaxies at distances of 4-23 Mpc, and parallel V and I band imaging of their halos
- 同时还有ALMA，MUSE的数据：yield an unprecedented joint catalog of the observed and physical properties of ∼100,000 star clusters, associations, HII regions, and molecular clouds.

##### [Environments of a sample of AzTEC submillimetre galaxies in the COSMOS field](https://arxiv.org/abs/2101.02977)

- 116 SMGs in 96 ALMA observation fields; 基于COSMOS catalog研究环境
- We find that 27% (31 out of 116) of the SMGs in our sample are located in a galactic dense environment; a fraction that is similar to previous studies.
- The spectroscopic redshift is known for 15 of these 31 sources, thus this photometric approach is tested using spectroscopy. We are able to confirm that 7 out of 15 SMGs lie in high-density peaks.

### Jan 11 

#### Relevant / Important / Useful

##### [The Three Hundred Project: Substructure in hydrodynamical and dark matter simulations of galaxy groups around clusters](https://arxiv.org/abs/2101.03178)

- #cluster/phase_space 
- We directly compare the substructure of galaxy clusters and of surrounding galaxy groups in hydrodynamical and dark matter-only simulations.
- 和流体力学模拟比，DM-only模拟估计的星系团和星系群中心的星系数量偏少
- We also look at the phase space of infalling galaxy groups, to show that dark matter-only simulations underpredict the number density of galaxies in the centres of these groups by about a factor of four.

##### [The PAU Survey: narrowband photometric redshifts using Gaussian processes](https://arxiv.org/abs/2101.03723)

- #merian 
- We calibrate the fluxes of the 40 PAUS narrowbands with 6 broadband fluxes (uBVriz) in the COSMOS field using three different methods, including a new method which utilises the correlation between the apparent size and overall flux of the galaxy.
- We use a rich set of empirically derived galaxy spectral templates as guides to train the Gaussian process
- [[Photometric Redshift]] 
- [`Delight` - Photometric redshift via Gaussian processes with physical kernels](https://github.com/ixkael/Delight)

##### [DAWIS, a Detection Algorithm with Wavelets for Intracluster light Studies](https://arxiv.org/abs/2101.03835)

- [[Intra-Cluster Light]]
- 基于小波技术的ICL探测：DAWIS follows a multiresolution vision based on wavelet representation to detect sources, embedded in an iterative procedure called synthesis-by-analysis approach to restore the complete unmasked light distribution of these sources with very good quality.
- We find in simulations that in average DAWIS is able to disentangle galaxy light from ICL more efficiently, and to detect a greater quantity of ICL flux due to the way it handles sky background noise. 
- We also show that the ICL fraction, a metric used on a regular basis to characterise ICL, is subject to several measurement biases both on galaxies and ICL fluxes.

#### Interesting / Keep in Mind

##### [Indra: a Public Computationally-Accessible Suite of Cosmological N\-body Simulations](https://arxiv.org/abs/2101.03631)

- #cosmology/simulation 
- 384个模拟，1024$^3$ 1 Gpc/$h$, 64 snapshots
- All of the Indra data are immediately available for analysis via the SciServer science platform
- We present the Indra simulations, describe the data products and how to access them, and measure ensemble averages, variances, and covariances of the matter power spectrum, the matter correlation function, and the halo mass function
- [`indra-tools` - Code repository for the Indra simulations](https://github.com/bfalck/indra-tools)

##### [A Luminous Quasar at Redshift 7.642](https://arxiv.org/abs/2101.03179)

- We report the discovery of a luminous quasar at z\=7.642, J0313−1806, the most distant quasar yet known. 光度 3.6x10^13 Lsun; 黑洞质量 1.6x10^9 Msun
- 看到了很强的外流的迹象：the quasar spectrum exhibits strong broad absorption line (BAL) features in CIV and SiIV, with a maximum velocity close to 20% of the speed of light. The relativistic BAL features, combined with a strongly blueshifted CIV emission line, indicate that there is a strong active galactic nucleus (AGN) driven outflow in this system.
- ALMA observations detect the dust continuum and \[CII\] emission from the quasar host galaxy


#### Others

##### [Joint inference on the redshift distribution of fast radio burst and on the intergalactic baryon content](https://arxiv.org/abs/2101.03569)

- #frb #inference 
- We perform a joint inference of the intergalactic baryon content and the fast radio burst redshift distribution with the use of Bayesian statistics
- Assuming that the missing baryons reside in the ionized intergalactic medium, our results suggest that the redshift distribution of observed fast radio bursts peaks at z≲0.6. 
- [`PreFRBLE` - Probability Estimates for Fast Radio Burst to obtain model Likelihood Estimates](https://github.com/FRBs/PreFRBLE)
- [`frbpoppy` - Fast Radio Burst Population Synthesis in Python](https://github.com/davidgardenier/frbpoppy)

##### [Origin of Galactic Spurs: New Insight from Radio/X-ray All-sky Maps](https://arxiv.org/abs/2101.03302)

- Our analysis finds that the X-ray emissions, not only from the NPS but from the SPS are closer to the Galactic center by ~5 deg compared with the corresponding radio emission.
- The temperature of the X-ray emission is kT ~ 0.2 keV for the LAS, which is systematically lower than those of the NPS and SPS (kT ~ 0.3 keV) but consistent with the typical temperature of Galactic halo gas
- 原因：shock compression/heating of halo gas during a significant Galactic explosion in the past, whereas the enhanced X-ray emission from the LAS may be due to the weak condensation of halo gas in the arm potential or star formation activity without shock heating.

##### [Solo dwarfs II: The stellar structure of isolated Local Group dwarf galaxies](https://arxiv.org/abs/2101.03189)

- Solitary Local Dwarf Galaxy survey: volume limited (< 3Mpc), isolated, wide-field g and i-band surveys: 44 dwarfs are homogeneously analysed for quantitative comparisons to the satellite dwarf populations of the Milky Way and M31.
- All 12 galaxies are found to be reasonably well described by two-dimensional Sersic functions, although UGC 4879 in particular shows tentative evidence of two distinct components. 
- No prominent extended stellar substructures, that could be signs of either faint satellites or recent mergers, are identified in the outer regions of any of the systems examined. 

##### [Wolf-Rayet galaxies in SDSS-IV MaNGA. II. Metallicity dependence of the high-mass slope of the stellar initial mass function](https://arxiv.org/abs/2101.03217)

- We construct a large sample of 910 WR galaxies/regions that cover a wide range of stellar metallicity
- We measure the equivalent width of the WR blue bump at ~4650 AA from each spectrum, and make comparisons with predictions of both singular population models in Starburst99 and binary population models in BPASS.
- These analyses have consistently led to a positive correlation of IMF high-mass slope α with stellar metallicity Z, i.e. with steeper IMF (more bottom-heavy) at higher metallicities

##### [Three-dimensional simulations of X-ray cavities inflated by radio galaxies](https://arxiv.org/abs/2101.03517)

- 基于高分辨数值模拟：We assume adiabatic non-relativistic hydrodynamics with injected straight and precessing jets of supersonic gas emitted from nozzles
- The cavity shape is sensitive to the jet-ambient density contrast, varying from concave-shaped at η\=0.1 to convex for η\=0.0001 where η is the jet/ambient density ratio.

##### [ALMA 1.3 mm Survey of Lensed Submillimeter Galaxies (SMGs) Selected by Herschel: Discovery of Spatially Extended SMGs and Implications](https://arxiv.org/abs/2101.03677)

- We detect 29 sources in 20 fields of massive galaxy clusters with ALMA.
- SMG中的SF非常concentrated：we find the median dust-to-stellar continuum size ratio to be small (Re,dust/Re,star\=0.38±0.14) for the observed SMGs, indicating that star formation is centrally concentrated.
	- 但对两个比较延展的1.3mm低面亮度SMG是例外，SF在这两个星系中分布在整个星系中
- 整体来看，FIR面光度越高，R_dust/R_star 就越小
	- This indicates that SMGs with less vigorous star formation (i.e., lower ΣIR) lack central starburst and are likely to retain a broader spatial distribution of star formation 

##### [Galaxy And Mass Assembly: Group and field galaxy morphologies in the star-formation rate - stellar mass plane](https://arxiv.org/abs/2101.03804)

- GAMA + KiDS: Using GMB and nBulge, we see that the star-forming galaxies do not become more bulge or disk dominated as the group mass changes. Asymmetry does not appear to be greatly influenced by environment.
- Using C and r50, we find that galaxies typically become larger as the group mass increases. This change is greater for larger galaxies. 

##### [A titanic interstellar medium ejection from a massive starburst galaxy at redshift 1.4](https://arxiv.org/abs/2101.04021)

- We present a massive starburst galaxy at z=1.4 which is ejecting 46±13\\% of its molecular gas mass at a startling rate of ≳10,000 M⊙yr−1
- The implied statistics suggest that similar events are potentially a major star-formation quenching channel.
- 但并不是feedback导致的外流，更像是并合引起的tidal ejection

##### [J-PLUS: The star formation main sequence and rate density at d < 75 Mpc](https://arxiv.org/abs/2101.04062)

- (J-PLUS) first data release, that probes 897.4 deg2 with twelve optical bands.
- We extract the Halpha emission flux of 805 local galaxies
	- Our sample comprises 689 blue galaxies and 67 red galaxies, classified in the (u-g) vs (g-z) color-color diagram, plus 49 AGN.
- The SFMS is explored at log M > 8 and it is clearly defined by the blue galaxies, with the red galaxies located below them.
	- The SFMS is described as log SFR = 0.83 log M - 8.44.
- The derived star formation rate density at d < 75 Mpc is log rho\_SFR = -2.10 +- 0.11, with red galaxies accounting for 15% of the SFRD.

### Jan 12 

#### Relevant / Important / Useful

##### [How not to obtain the redshift distribution from probabilistic redshift estimates: Under what conditions is it not inappropriate to estimate the redshift distribution N(z) by stacking photo-z PDFs?](https://arxiv.org/abs/2101.04675)

- #photo-z [[Photometric Redshift]] 
- 传统WL分析中为了得到redshift distribution function的叠加方法不严谨
- "Under what conditions do traditional stacking methods successfully recover the true redshift distribution function N(z)?" By placing stacking in a rigorous mathematical environment, we identify two such conditions: those of perfectly informative data and perfectly informative prior information.
- We therefore conclude that stacking must be abandoned in favor of mathematically supported methods in order to advance observational cosmology.

#### Interesting / Keep in Mind

##### [Shocks in the Stacked Sunyaev-Zel'dovich Profiles of Clusters I: Analysis with the Three Hundred Simulations](https://arxiv.org/abs/2101.04179)

- #cluster/icm #cluster/sze #splashback  [[Splashback Radius]]
- We investigate the possibility of detecting signals from cluster shocks in the averaged thermal SZ profiles of galaxy clusters.
- 基于模拟：we show that if cluster SZ profiles are stacked as a function of R/R200m, shock-induced features appear in the averaged SZ profile
- Include gas shocks will gain a new handle on the properties and dynamics of the outskirts of massive halos, both in gas and in mass.

##### [A prediction on the age of thick discs as a function of the stellar mass of the host galaxy](https://arxiv.org/abs/2101.04478)

- #galaxy/thick_disc
- 研究厚盘的形成是否来自in-situ growth from a turbulent clumpy disc
- By combining thick disc and total stellar masses of edge-on galaxies with galaxy stellar mass functions calculated in the redshift range z≤3.0, I derive a positive correlation between the age of the youngest stars in thick discs and the stellar mass of the host galaxy; 质量越大，厚盘里最年轻的星族年龄越老
- I propose to conclusively test whether thick discs formed fast and in-situ by obtaining the ages of thick discs in field galaxies with masses $\mathcal{M}_{\star}(z=0) \sim 10^{9.5} \mathcal{M}_{\odot}$ and checking whether they contain ∼5Gyr\-old stars.

#### Others

##### [Assessing the accuracy of cosmological parameters estimated from velocity -- density comparisons via simulations](https://arxiv.org/abs/2101.04120)

- A promising method for measuring the cosmological parameter combination fsigma\_8 is to compare observed peculiar velocities with peculiar velocities predicted from a galaxy density field using perturbation theory.
- We find that for a Gaussian smoothing of 4 Mpc/h, the method has only small systematic biases at the level of 5%.
- 线性扰动理论下，密度场和本动速度之间的关系在低红移是：

$$
v(\boldsymbol{r})=\frac{H_{0} f\left(\Omega_{m}\right)}{4 \pi} \int \delta\left(\boldsymbol{r}^{\prime}\right) \frac{\left(\boldsymbol{r}^{\prime}-\boldsymbol{r}\right)}{\left|\boldsymbol{r}^{\prime}-\boldsymbol{r}\right|^{3}} d^{3} \boldsymbol{r}^{\prime}
$$


##### [Systematic difference between ionized and molecular gas velocity dispersion in z∼1−2 disks and local analogues](https://arxiv.org/abs/2101.04122)

- DYNAMO样本：ALMA+GMOS；the resolved velocity dispersion is systematically lower by a factor 2.45±0.38 for the molecular gas compared to the ionized gas, after correcting for thermal broadening 
- 气体比例越高，气体速度弥散度越高
- 高红移处的分子气体速度弥散度更高，但FIRE和EAGLE模拟高估了气体速度弥散度；TNG50表现更好
- 恒定SF效率的模型不能解释；需要SF和feedback效率有系统变化的feedback模型

##### [Buckling bars in nearly face-on galaxies observed with MaNGA](https://arxiv.org/abs/2101.04157)

- In simulations, a thin bar undergoes a rapid (<1 Gyr) event called "buckling," during which the inner part of the bar is asymmetrically bent out of the galaxy plane and eventually thickens, developing a peanut/X-shaped profile when viewed side-on. 
- 通过模拟数据找到buckling的运动学证据，以便在IFU巡天中搜索候选: we confirm a distinct quadrupolar pattern of out-of-plane stellar velocities in nearly face-on galaxies
- MaNGA中：five candidates of currently buckling bars among 434 barred galaxies 这个比例和模拟中0.5-1 Gyr的时标一致

##### [Processing of gas in cosmological filaments around Virgo cluster](https://arxiv.org/abs/2101.04389)

- 看Virgo附近环境对星系的pre-processing: SFR和cosmic filaments密度的关系
- We have observed the two first CO transitions in 163 galaxies with the IRAM-30m telescope
- We find a clear progression from field, to filament, and cluster galaxies for decreasing SFR, increasing fraction of galaxies in the quenching phase, increasing proportion of early-type galaxies and decreasing gas content.
- As the environmental density increases, the gas depletion time decreases, since the gas content decreases faster than the SFR. 气体的剥离比SF的quenching快得多

##### [The star formation history of Eridanus II: on the role of SNe feedback in the quenching of ultra-faint dwarf galaxies](https://arxiv.org/abs/2101.04464)

- 早期的CMB显示可能有年轻星族：This SFH shows that the bulk of the stellar mass in Eri II formed in an extremely short star formation burst at the earliest possible time. The derived star formation rate profile has a width at half maximum of 500 Myr
- For reasonable estimates of the EriII virial mass and values of the coupling efficiency of the SNe energy, we conclude that EriII could be quenched by SNe feedback alone, 可能不需要再电离

##### [HI Global Scaling Relations in the WISE-WHISP Survey](https://arxiv.org/abs/2101.04514)

- 228 nearby galaxies
- We utilize the novel method of deriving scaling relations for quantities enclosed within the stellar disk rather than integrating over the HI disk and find the global scaling relations to be tighter when defined for enclosed quantities.

##### [Candidate z ~ 2.5 Lyman Continuum Sources in the GOODS Fields](https://arxiv.org/abs/2101.04669)

- We select sources at 2.35<z<3.05, where the HST/WFC3 F275W filter probes only the redshifted LyC. 
- 有五个候选：The result is dominated by just five candidate F275W-bright LyC sources.
- We examine the contributions to the metagalactic ionizing background, finding that, at the sensitivity of the HDUV F275W data and allowing for the effects of LyC transmission in the intergalactic medium (IGM), star-forming galaxies can match the UV flux required to maintain an ionized IGM at z∼2.5.

##### [A parsec-scale faint jet in the nearby changing-look Seyfert galaxy Mrk 590](https://arxiv.org/abs/2101.04629)

- Over the last fifty years, Mrk 590 also underwent a powerful continuum outburst and a slow fading from X-rays to radio wavelengths with a peak bolometric luminosity reaching about ten per cent of the Eddington luminosity
- VLBI观测：To date, such a parsec-scale jet is rarely seen in the known changing-look AGN. The finding of the faint jet provides further strong support for variable accretion as the origin of the type changes in Mrk 590.

### Jan 13 

#### Relevant / Important / Useful

##### [The shape and connectivity of groups and clusters: Impact of dynamical state and accretion history](https://arxiv.org/abs/2101.04686)

- 基于TNG模拟：We find that the mass of groups and clusters mainly influences the geometry of the matter distribution: massive halos are significantly more elliptical, and more connected to the cosmic web than low-mass ones.
- Halo growth rate也有一定的重要性
- Both anisotropy measures appear to trace different dynamical states, such that unrelaxed groups and clusters are more elliptical and more connected than relaxed ones.

##### [SPIDERS: An Overview of The Largest Catalogue of Spectroscopically Confirmed X-ray Galaxy Clusters](https://arxiv.org/abs/2101.04695)

- #cluster/x-ray #cluster/finder #cluster/cosmology 
- 2740 visually inspected galaxy clusters
- Finally, we present our cosmological constraints derived using the velocity dispersion function.

##### [Exploring the contamination of the DES-Y1 Cluster Sample with SPT-SZ selected clusters](https://arxiv.org/abs/2101.04984)

- #cluster/cosmology  #cluster/finder [[Cluster Projection Effect]] [[Cluster Mass-Richness]]
- We find a mass trend $\lambda \propto M^{B}$ consistent with a linear relation (B∼1), no significant redshift evolution and an intrinsic scatter in richness of σλ\=0.22±0.06.
- At low richness SPT-SZ confirms fewer redMaPPer clusters than expected. We interpret this richness dependent deficit in confirmed systems as due to the increased presence at low richness of low mass objects not correctly accounted for by our richness-mass scatter model, which we call contaminants.
- 在$\lambda = 40$, contamination比例在12%左右；在$\lambda = 20$，比例占22%
- The mean mass from stacked weak lensing (WL) measurements suggests that these low mass contaminants are galaxy groups with masses $\sim 3-5 \times 10^{13} M_{\odot}$

##### [`mirkwood`: Fast and Accurate SED Modeling Using Machine Learning](https://arxiv.org/abs/2101.04687)

- #stellar_population 
- `mirkwood`: a user-friendly tool comprising of an ensemble of supervised machine learning-based models capable of non-linearly mapping galaxy fluxes to their properties.
- By stacking multiple models, we marginalize against any individual model's poor performance in a given region of the parameter space.
- To increase the added value to the observational community, we use Shapley value explanations (SHAP) to fairly evaluate the relative importance of different bands to understand why particular predictions were reached.
- [`mirkwood`](https://github.com/astrogilda/mirkwood)

#### Interesting / Keep in Mind 

##### [DESC DC2 Data Release Note](https://arxiv.org/abs/2101.04855)

- #lsst [[LSST DESC Data Challenge 2]]
- The DC2 simulated sky survey, in six optical bands with observations following a reference LSST observing cadence, was processed with the LSST Science Pipelines (19.0.0).

##### [The Interstellar Medium of Quiescent Galaxies and its Evolution With Time](https://arxiv.org/abs/2101.04700)

- #massive_galaxy 
- We find that the dust to stellar mass ratio (Md/M\*) rises steeply as a function of redshift up to z~1.0 and then remains flat at least out to z = 2.0.
- z~1 QG中的气体比例比同时期的SF星系低3-10倍，但比近邻的QGs要高得多
- The inferred gas depletion time scales are comparable to that of local SFGs and systematically longer than that of main sequence galaxies at their corresponding redshifts
- Our analysis also reveals that the average dust temperature (Td) of massive QGs remains roughly constant (< Td > = 21.0 \\pm 2.0K) at least out to z ~ 2.0 and is substantially colder (~ 10K) compared to that of z > 0 SFGs


#### Others

##### [Magnification bias in galaxy surveys with complex sample selection functions](https://arxiv.org/abs/2101.05261)

- We propose and test a procedure to quantify the magnification bias induced in clustering and galaxy-galaxy lensing (GGL) signals in galaxy samples subject to a selection function beyond a simple flux limit.
- The method employs realistic mock data to calibrate an effective luminosity function slope, αobs, from observed galaxy counts, which can then be used with the standard formalism.

##### [EDGE-CALIFA survey: Self-regulation of Star formation at kpc scales](https://arxiv.org/abs/2101.04683)

- 4260 star-forming regions of kpc size located in 96 galaxies included in the EDGE-CALIFA: 恒星形成率面密度和中盘压力的关系很紧密
- Locally, the residuals of this correlation show a significant anti-correlation with both the stellar age and metallicity whereas the total stellar mass may also play a secondary role
- The median value of this ratio for all the sampled regions is larger than the expected momentum just from supernovae explosions.
- Our results also suggest that Ph can be considered as the main parameter that modulates star formation at kpc scales, rather than individual components of the baryonic mass. 

##### [Efficiency of Thermal Conduction in a Magnetised Circumgalactic Medium](https://arxiv.org/abs/2101.04684)

- Thermal conduction in the presence of a magnetic field is highly anisotropic, being strongly suppressed in the direction perpendicular to the magnetic field lines
- 但在模拟中常常被假设是各向同的
- Thermal conduction is thus always highly suppressed, but its effect on the cloud evolution is generally not negligible.

##### [Powerful winds in high-redshift obscured and red quasars](https://arxiv.org/abs/2101.04688)

- For the ERQs, the galactic-scale outflows are likely driven by radiation pressure in a high column density environment or due to an adiabatic shock. 
	- The outflows in the ERQs carry a significant amount of energy ranging from 0.05-5% of the quasar's bolometric luminosity, powerful enough to have a significant impact on the quasar host galaxies.
	- The observed outflow sizes are generally smaller than other ionized outflows observed at high redshift
- For the type-2 quasar, the outflow is driven by radiation pressure in a low column density environment or due to a radiative shock

##### [Revisited cold gas content with atomic carbon \[C I\] in z=2.5 protocluster galaxies](https://arxiv.org/abs/2101.04691)

- Five galaxies out of sixteen targeted galaxies are detected in the \[CI\] line, and these are all previously detected in CO(3-2) and CO(4-3) and three in 1.1 mm dust continuum.
- Using the calibration adopted for field main-sequence galaxies, the \[CI\]-based gas measurements are lower than or comparable to the CO-based gas measurements by -0.35 dex at the lowest with the mean deviation of -0.14 dex.

##### [Giant Molecular Cloud Catalogues for PHANGS-ALMA: Methods and Initial Results](https://arxiv.org/abs/2101.04697)

- We present improved methods for segmenting CO emission from galaxies into individual molecular clouds, providing an update to the CPROPS algorithms
	- The new code enables both homogenization of the noise and spatial resolution among data, which allows for rigorous comparative analysis
- We measure the properties of 4986 individual clouds identified in these targets.
- Overall, the clouds in our target galaxies are well-described by approximate energy equipartition, although clouds in stellar bars and galaxy centres show elevated line widths and virial parameters.
- [`pycprops` - Python implementation of the CPROPS algorithm](https://github.com/PhangsTeam/pycprops)

##### [The Evolution of the IR Luminosity Function and Dust-obscured Star Formation in the Last 13 Billion Years](https://arxiv.org/abs/2101.04734)

- 2mm Mapping Obscuration to Reionization (MORA) survey: Large ALMA blank field survey; 13 sources detected above 5sigma
- Our results suggest a steep redshift evolution on the space density of DSFGs and confirm the flattening of the IR luminosity function at faint luminosities
- We conclude that the dust-obscured component, which peaks at z=2-2.5, has dominated the cosmic history of star formation for the past ~12 billion years, back to z~4

##### [Constraining Galaxy Haloes from the Dispersion and Scattering of Fast Radio Bursts and Pulsars](https://arxiv.org/abs/2101.04784)

- #fast_radio_burst 
- We compare our analysis of the Milky Way halo with other galaxy haloes by placing limits on the scattering contributions from haloes intersecting the lines-of-sight to FRB 181112 and FRB 191108. Our results are consistent with haloes making negligible or very small contributions to the scattering times of FRBs.

##### [Defining the (Black Hole)-Spheroid Connection with the Discovery of Morphology-Dependent Substructure in the MBH\--nsph and MBH\--Re,sph Diagrams: New Tests for Advanced Theories and Realistic Simulations](https://arxiv.org/abs/2101.04895)

- #smbh #early_type_galaxy 
- 123 local galaxies: we use these to derive the morphology-dependent MBH\--nsph and MBH\--Re,sph relations
- We detect two different MBH\--nsph relations due to ETGs and LTGs

##### [Galaxy mergers up to z < 2.5 II: AGN incidence of merging galaxies at separations of 3-15 kpc](https://arxiv.org/abs/2101.05000)

- Major merging systems at 0.3<z<2.5

##### [NOEMA Redshift Measurements of the Brightest Submillimeter Galaxies in the GOODS-N](https://arxiv.org/abs/2101.05268)

- We report spectroscopic redshift measurements for three bright submillimeter galaxies (SMGs) in the GOODS-N field, each with SCUBA-2 850 micron fluxes > 10 mJy, using the Northern Extended Millimeter Array (NOEMA).

### Jan 13 

#### Relevant / Important / Useful

##### [Observational Measures of Halo Properties Beyond Mass](https://arxiv.org/abs/2101.05280)

- #galaxy_halo #ssst_sci
- We show that different halo properties beyond mass imprint distinct scale-dependent signatures in both the galaxy two-point correlation function and the distribution of distances to galaxies' kth nearest neighbours, with features strong enough to be accessible even with low-resolution (e.g., grism) spectroscopy at higher redshifts.
- 基于SDSS数据：Classic galaxy size models (i.e., galaxy size being proportional to halo spin) as well as other recent proposals show significant tensions with observational data. 如果让size和halo growth有相关可以改善

##### [The Dark Energy Survey Data Release 2](https://arxiv.org/abs/2101.05765)

- #des [Data Release DR2 is here](https://des.ncsa.illinois.edu/releases/dr2)
- DES wide-area survey covering ~5000 deg2 of the southern Galactic cap in five broad photometric bands, grizY.
- Seeing: g= 1.11, r= 0.95, i= 0.88, z= 0.83, and Y= 0.90 arcsec
- The median coadded catalog depth for a 1.95 arcsec diameter aperture at S/N= 10 is g= 24.7, r= 24.4, i= 23.8, z= 23.1 and Y= 21.7 mag.
- These data are accessible through several interfaces, including interactive image visualization tools, web-based query clients, image cutout servers and Jupyter notebooks.

#### Interesting / Keep in Mind

##### [A kiloparsec view of a typical star-forming galaxy when the Universe was ~1 Gyr old. Part I. Outflow, halo, and interstellar medium properties](https://arxiv.org/abs/2101.05279)

- 作者[Rodrigo Herrera-Camus](http://www.astro.udec.cl/s/people/profs/rh.html); 文章的结构和图做的非常好
- ALMA观测[CII] 158$\mu$m线：一个z=5.5的“普通”SF星系；看[CII]/FIR比值，和SFR的关系等
- In the central ∼4 kpc of HZ4, the \[CII\]/FIR ratio is ∼3×10−3 on global scales as well as on spatially-resolved scales of ∼2 kpc, 和local的星暴星系差不多
- 看到了中心400km/s速度的minor axis方向的外流； 中性气体的外流率比SFR高很多
- We detect a diffuse component of \[CII\] emission, or "\[CII\]-halo", that extends beyond the star-forming disk and has a size of ∼12 kpc in diameter.
- Appendix C: 如何用[CII]光度观测估计外流质量

##### [Hyper Suprime-Cam Legacy Archive](https://arxiv.org/abs/2101.05463)

- #survey/hsc 
- We have processed the data from these PI programs and make the processed, high quality data available to the community through HSCLA. The current version of HSCLA includes data taken in the first year of science operation, 2014.

##### [The Fornax Deep Survey (FDS) with the VST XI. The search for signs of preprocessing between the Fornax main cluster and Fornax A group](https://arxiv.org/abs/2101.05699)

- #cluster/galaxy #early_type_galaxy 
- 582 galaxies from the Fornax main cluster and Fornax A group.
	- We find significant differences in the distributions of quantities derived from Sérsic profiles (g′−r′, r′−i′, Re, and μ¯e,r′), and non-parametric indices (A and S)
- We find the structural complexity of galaxies increases as a function of the absolute r′\-band magnitude (and stellar mass)
- [Decomposition results](https://www.oulu.fi/astronomy/FDS_DECOMP/main/index.html) (username=password=sundial)

##### [Composite Bulges -- II. Classical Bulges and Nuclear Discs in Barred Galaxies: The Contrasting Cases of NGC 4608 and NGC 4643](https://arxiv.org/abs/2101.05321)

- #early_type_galaxy 
- Detailed morphological, photometric, and stellar-kinematic analyses of the central regions of two massive, early-type barred galaxies with nearly identical large-scale morphologies
- Both have large, strong bars with prominent inner photometric excesses that we associate with boxy/peanut-shaped (B/P) bulges; the latter constitute ~ 30% of the galaxy light.
- Standard 2-component (bulge/disc) decompositions yield B/T ~ 0.5-0.7 (and bulge n > 2) for both galaxies. This overestimates the true "spheroid" components by factors of four (NGC 4608) and over 100 (NGC 4643), illustrating the perils of naive bulge-disc decompositions applied to massive barred galaxies.

#### Others

##### [Massive black holes in high-redshift Lyman Break Galaxies](https://arxiv.org/abs/2101.05292)

- We find that a typical LBG with MUV\=−22 residing in a Mh≈10^{12}M⊙ halo at z\=6 host a MBH with mass M∙≈2×10^{8}M⊙.
- 在模型里讨论了不同的seeding scenario的影响: mostly grow by accretion or by merger.

##### [HUBS: A dedicated hot circumgalactic medium explorer](https://arxiv.org/abs/2101.05587)

- HUBS is optimized to detect the X-ray emission from the hot baryons in the circum-galactic medium, and thus fill a void in observational astronomy. The goal is not only to detect the missing baryons, but to characterize their physical and chemical properties, as well as to measure their spatial distribution.

##### [Eclipsing the X-ray emitting region in the active galaxy NGC 6814](https://arxiv.org/abs/2101.05433)

- The detection of a rapid occultation event in the nearby Seyfert galaxy NGC 6814, simultaneously captured in a transient light curve and spectral variability
- The changes can be simply described by varying the fraction of the central engine that is covered by transiting obscuring gas.

##### [An underlying universal pattern in galaxy halo magnetic fields](https://arxiv.org/abs/2101.05291)

- EVLA观测：the radio halos of 35 nearby edge-on spiral galaxies and detected large scale magnetic fields in 16 of them.
- We discovered a large-scale magnetic field in the central region of the stacked galaxy profile, attributable to an axial electric current that universally outflows from the center both above and below the plane of the disk.
- This is an indication that galaxy halo magnetic fields are probably not generated by pure ideal magnetohydrodynamic (MHD) processes in the central regions of galaxies.
- Complex intensity of linear polarization: $\Pi \equiv Q+i U=P e^{i 2 \chi}=m I e^{i 2 \chi}$
	- $I$, $Q$, $U$: observed Stokes parameters
	- $P$ is the modulus of $\Pi$.
	- $\chi$: observed Electric Vector Position Angle (EVPA)
	- $m \equiv \sqrt{Q}^{2}+U^{2} / I$: observed degree of linear polarization.
- Faraday rotation changes the observed orientation of the EVPA when polarized light is propagated through a magnetoionic medium
	- Initial value of EVPA: $\chi_0$ at position $r_0$.
	- $\chi=\chi_{0}+\mathrm{RM} \cdot \lambda^{2}$
	- $\lambda$: wavelength
- RM: Faraday Rotation Measure: $\mathrm{RM} \equiv \frac{e^{3}}{2 \pi m_{e}^{2} c^{4}} \int_{r_{0}}^{0} n_{e} B_{\|} \mathrm{d} r$
	- $B_{\|}$:  line-of-sight magnetic field of the magnetoionic medium 

##### [ALMA detection of millimetre 183 GHz H2O maser emission in the Superantennae galaxy at z ~ 0.06](https://arxiv.org/abs/2101.05296)

- In addition to dense molecular line emission (HCN, HCO+, and HNC J = 2-1), we detect a highly luminous (~6e4Lsun) 183 GHz H2O 3(1,3)-2(2,0) emission line --> 来自maser amplification in AGN-illuminated dense and warm molecular gas
- We here demonstrate that with highly sensitive ALMA, millimetre 183 GHz H2O maser detection is feasible out to >270 Mpc, opening a new window to scrutinize molecular gas properties

##### [VLA resolves unexpected radio structures in the Perseus cluster of galaxies](https://arxiv.org/abs/2101.05305)

- #cluster/icm #cluster/perseus
- JVLA观测1.5GHz: We isolate for the first time the complete tail of radio emission of the bent-jet radio galaxy NGC 1272
- We suggest interpretations for these structures that involve bulk motions of intracluster gas, the galaxy's orbit in the cluster including projection effects

##### [The Evolution of the Luminosity Function for Luminous Compact Blue Galaxies to z=1](https://arxiv.org/abs/2101.05342)

- COSMOS场中：We find that over this redshift range (0.1 < z < 1.0), the characteristic luminosity (M∗) increases by ∼0.2 mag, and the number density increases by a factor of four.
- The strong evolution in number density indicates that LCBGs are an important population of galaxies to study in order to better understand the decrease in the star formation rate density of the universe since z∼1.

##### [First constraints on the AGN X-ray luminosity function at z∼6 from an eROSITA-detected quasar](https://arxiv.org/abs/2101.05585)

- #survey/erosita
- We report the X-ray detection of an eROSITA source securely matched to the well-known quasar SDSS J083643.85+005453.3 (z=5.81).
- The reported flux densities confirm a spectral flattening at lower frequencies in the emission of the radio core, indicating that the quasar could be a (sub-) gigahertz peaked spectrum source.
- 没有看到jet对X-ray的贡献
- The population of X-ray luminous AGNs at high redshift may be larger than previously thought. From our XLF constraints

##### [A million binaries from Gaia eDR3: sample selection and validation of Gaia parallax uncertainties](https://arxiv.org/abs/2101.05282)

- #gaia 
- Gaia eDR3: [an extensive catalog](https://zenodo.org/record/4435257#.YAHRFZNKhTY) of spatially resolved binary stars within ≈ 1 kpc of the Sun, with projected separations ranging from a few au to 1 pc.
- The catalog contains 1.3 (1.1) million binaries with >90% (>99%) probability of being bound, including 16,000 white dwarf -- main sequence (WD+MS) binaries and 1,400 WD+WD binaries
- 然后利用双星有相同的距离这一特点，校准Gaia视差的误差估计
	- We provide an empirical fitting function to inflate published σϖ values for isolated sources.


### Jan 16

#### Relevant / Important / Useful

##### [Bright galaxy sample in the Kilo-Degree Survey Data Release 4: selection, photometric redshifts, and physical properties](https://arxiv.org/abs/2101.06010)

- #survey/kids #galaxy/massive #shmr
- KiDS中有精确测光红移的1M个r< 20 mag星系
- As a demonstration of the usefulness of these data we split the dataset into red and blue galaxies, use them as lenses and measure the weak gravitational lensing signal around them for five stellar mass bins.
 - 验证了 M*>5x10^{11} Msun的red星系比blue星系的halo质量大

##### [Quantifying scatter in galaxy formation at the lowest masses](https://arxiv.org/abs/2101.05822)

- #galaxy/dwarf #shmr #merian 
- 用模拟星系来预测矮星系的SHMR：the simulated SMHM relationship agrees with literature determinations, including exhibiting a small scatter of 0.3 dex. However, the scatter in the SMHM relation increases for lower-mass halos.
- We fit linearly growing log-normal scatter in stellar mass, which grows to more than 1 dex at Mpeak \= 10^{8} Msun.
- At the faintest end of the SMHM relation probed by our simulations, a galaxy cannot be assigned a unique halo mass based solely on its luminosity.
- Code and visualization: [`smhm-toy-model`](https://github.com/emapple/smhm-toy-model)

##### [Dissecting the size-mass and Σ1\-mass relations at 1.0 < z < 2.5: galaxy mass profiles and color gradients as a function of spectral shape](https://arxiv.org/abs/2101.05820)

- #galaxy/structure 
- We classify ∼7,000 galaxies into sixteen groups with similar spectral shapes; each group represents a different evolutionary stage. 看这些星系在mass-size和mass-sigma1上的表现
- Star-forming groups form steep parallel relations in the size-mass plane, with slopes similar to the quiescent size-mass relation.
	- These steep slopes can be explained as a transformation of the star-forming Σ1\-mass relation and its scatter.
- 可以认出三种transitional galaxies:
	- Post-starburst和green valley的color-gradient不一样
	- PSB：flat color-gradient; compact; higher-z; fast quenching
	- GV: negative color-gradient; larger; lower-z; slow quenching

#### Interesting / Keep in Mind

##### [A Study of Gas Entropy Profiles of 47 Galaxy Clusters and Groups Out to the Virial Radius](https://arxiv.org/abs/2101.05947)

- #galaxy/icm
- We calculate the ICM entropy profiles in a sample of 47 galaxy clusters and groups, which have been observed out to at least ∼r500 with Chandra, XMM-Newton and/or Suzaku, by constructing a physical model to incorporate the effects of both gravity and non-gravitational processes to fit the observed gas temperature and surface brightness profiles via Bayesian statistics.
- The flattened profiles reported previously can be explained by introducing the gas clumping effect, the existence of which is confirmed in 19 luminous targets in our sample.
- [[Thermodynamical ICM Model]] (RTI)

##### [New constraints on the magnetic field in filaments of the cosmic web](https://arxiv.org/abs/2101.06051)

- #cluster/icm #cosmic_web
- 低频射电观测可能已经可以探测到近邻大质量星系团对之间的cosmic filament的射点辐射；但目前只有upper limit
- 利用LOFAR上限限制磁场：By combining the results from the two putative inter-cluster filaments, we derive new independent constraints on the median strength of inter-galactic magnetic fields
- Based on cosmological simulations and assuming a primordial origin of the B-fields, these estimates can be used to limit the amplitude of primordial seed magnetic fields: B0≤10nG.

#### Others

##### [HOLISMOKES -- V. Microlensing of type II supernovae and time-delay inference through spectroscopic phase retrieval](https://arxiv.org/abs/2101.06229)

- 看强引力透镜放大的超新星的微引力透镜效应的宇宙学影响
- We study the impact of microlensing on the color curves and find that there is no strong influence on them during the investigated time interval of the plateau phase
- However, the lack of non-linear structure in the color curves makes time-delay measurements difficult given the possible presence of differential dust extinction.
- As the spectral features shift to longer wavelengths with progressing time after explosion, the measured wavelength of a specific absorption line provides information on the epoch of the SN.

##### [Disc tearing: implications for black hole accretion and AGN variability](https://arxiv.org/abs/2101.05825)

- Discs that are misaligned to the black hole spin can become warped over time by Lense-Thirring precession. 会变得不稳定，break into discrete rings producing a more dynamic and variable accretion flow.
- When the disc warp is unstable near the inner edge of the disc, we find quasi periodic behaviour of the inner disc which may explain the recent quasi periodic eruptions observed
- When the instability manifests at larger radii in the disc, we find that the central accretion rate can vary on timescales that may be commensurate with, e.g., changing-look AGN.

### Jan 18

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

##### [A Long Stream of Metal-Poor Cool Gas around a Massive Starburst Galaxy at z = 2.67](https://arxiv.org/abs/2101.06273)

- #galaxy/cgm #galaxy/smg
- z=2.6的SMG的CGM：We detect strong HI and metal-line absorption near the redshift of the SMG towards both QSOs, each consisting of three main subsystems spanning over 1500 km/s.
- CGM中的冷气体柱密度很高，和相近红移的QSO类似；但金属丰度比之前QSO观测的要低很多
	- 内流的作用：The large physical extent, the velocity coherence, the high surface density, and the low metallicity are all consistent with the cool, inflowing, and near-pristine gas streams predicted to penetrate hot massive halos at z > 1.5.

##### [Evolution of the galaxy stellar mass function: evidence for an increasing M∗ from z\=2 to the present day](https://arxiv.org/abs/2101.07182)

- #galaxy/smf
- COSMOS+XMM; SExtractor + ProFound; 探测方法影响不大
- We find that including IRAC data reduces the number of massive (log10(M/M⊙)\>11.25) galaxies found due to improved photometric redshift accuracy, but has little effect on the more numerous lower-mass galaxies.
- 改正Eddingtong bias的方法对大质量端的SMF影响很大
- we find evidence for an evolving characteristic stellar mass with δlog10(M∗/M⊙)/δz \= −0.16±0.05(−0.11±0.05)

##### [CO excitation, molecular gas density and interstellar radiation field in local and high-redshift galaxies](https://arxiv.org/abs/2101.06646)

- CO激发和星际辐射场强度相关：We confirm the existence of a tight correlation between CO excitation as traced by the CO(5-4)/(2-1) line ratio (R52), and the mean ISRF intensity U as derived from infrared SED fitting using dust SED templates
- We present a framework linking global CO line ratios to the mean molecular hydrogen gas density nH2 and kinetic temperature Tkin
- the ISRF in galaxies is mainly regulated by Tkin and (non-linearly) by nH2
- Code for this work: [`co-excitation-gas-modeling`](https://pypi.org/project/co-excitation-gas-modeling/)


#### Others

##### [Quantifying Feedback from Narrow Line Region Outflows in Nearby Active Galaxies -- III. Results for the Seyfert 2 Galaxies Markarian 3, Markarian 78, and NGC 1068](https://arxiv.org/abs/2101.06270)

- HST + APO spec观测；给出外流质量速率，最大速度
- The outflows extend to radial distances of r≈0.1−3 kpc from the nucleus, with the gas masses, outflow energetics, and radial extents positively correlated with AGN luminosity.
- The outflow rates are consistent with in-situ ionization and acceleration where gas is radiatively driven at multiple radii.

##### [The OTELO survey as a morphological probe. Last ten Gyr of galaxy evolution. The mass--size relation up to z=2](https://arxiv.org/abs/2101.06460)

- OTELO survey galaxies detected with the Hubble Space Telescope (HST)-ACS F814W images
	- A total of 8,812 sources were successfully fitted with single-Sérsic profiles.
- We found no statistical evidence for the evolution of the low-mass end of mass-size relation for ET and LT since z=2.

##### [Searching for Nuclear Obscuration in the Infrared Spectra of Nearby FR I Radio Galaxies](https://arxiv.org/abs/2101.06579)

- We present a wide-band infrared spectroscopic analysis of 10 nearby FR I radio galaxies to determine whether there is significant emission from a dusty obscuring structure.
- We find that one galaxy is best fit by a clumpy torus and three others show some thermal mid-infrared component. This suggests that in those three there is likely some obscuring dust structure that is inconsistent with our torus models and there must be some source of photons heating the dust.

##### [X-ray analysis of SDSS J165202.60+172852.4, an obscured quasar with outflows at peak galaxy formation epoch](https://arxiv.org/abs/2101.06613)

- XMM + NuSTAR观测：We fit the spectra from the XMM-Newton/EPIC and NuSTAR detectors with a physically motivated torus model and constrain the source to exhibit a near Compton-thick column density, a near edge-on geometry, and a scattering factor of 3%
- A powerful quasar that is not intrinsically X-ray weak, consistent with observed trends in other ERQs.
- As previously suggested with shallower X-ray observations, optical and infrared selection of ERQ has proved effective in finding obscured quasars with powerful outflow signatures.

##### [An Active Galactic Nucleus Recognition Model based on Deep Neural Network](https://arxiv.org/abs/2101.06683)

- The main goals of this work are (i) to test if the AGN recognition problem in the North Ecliptic Pole Wide (NEPW) field could be solved by NN

##### [Breaking the degeneracy between gas inflow and outflows with stellar metallicity: Insights on M101](https://arxiv.org/abs/2101.06833)

- 通过恒星与气体质量比例估计气态和恒星金属丰度差别的模型
	- 气体丰度对内流和外流都敏感；有简并
	- 恒星丰度主要对外流敏感；
- The combination of gas-phase and stellar metallicity is indeed more effective for constraining the gas inflow and outflow rates.

##### [OzDES Reverberation Mapping Program: Lag recovery reliability for 6-year CIV analysis](https://arxiv.org/abs/2101.06921)

- By simulating six real sources that contain the CIV emission line, we developed a set of quality criteria that ranks the reliability of a recovered time lag depending on the agreement between different recovery methods, the magnitude of the uncertainties, and the rate at which false positives were found in the simulations

##### [Interferometric Cubelet Stacking to Recover HI Emission from Distant Galaxies](https://arxiv.org/abs/2101.06928)

- Unlike the traditional spectral stacking technique, which stacks one-dimensional spectra extracted from data cubes, we examine a method based on image domain stacks which makes deconvolution possible.
- we mock a sample of 3622 equatorial galaxies extracted from the GAMA survey, recently imaged as part of a DINGO-VLA project.
	- The extracted H\\,\\textsc{i} mass from the deconvolved image agrees with the average input mass to within 3\\%.

##### [The Subarcsecond Mid-Infrared View of Local Active Galactic Nuclei. IV. The L- and M-band Imaging Atlas](https://arxiv.org/abs/2101.07006)

- VLT ISAAC in the L\- and/or M\-bands; 119 z<0.3 AGN, 3-5 micron
- We separate the flux into unresolved nuclear flux and resolved flux through two-Gaussian fitting.
- We find that models including polar winds best reproduce the 3-5μm colors, indicating that winds are an important component of dusty torus models.

##### [Old and New Major Mergers in the SOSIMPLE galaxy, NGC 7135](https://arxiv.org/abs/2101.07072)

- #galaxy/merger #galaxy/etg #galaxy/spop
- MUSE观测：Snapshot Optical Spectroscopic Imaging of Mergers and Pairs for Legacy Exploration (SOSIMPLE)
- With counter-rotation of gas, disrupted kinematics and asymmetric chemical distribution, NGC 7135 is consistent with an ongoing merger.
- We further find a gradient in ex-situ material with galactocentric radius, with the accreted fraction rising from 0% in the galaxy centre, to ~7% within 0.6 effective radii.

##### [The Lop-sided Spiral Galaxy NGC 247: Clues to a Possible Interaction with NGC 253](https://arxiv.org/abs/2101.07224)

- Two bubbles with spatial extents of many kpc are identified in the disk, and many of the young stars in the southern disk of NGC 247 are located in the walls of one of these structures
- Dynamical age estimates of these bubbles coincide with the last large-scale star formation event in the nucleus, suggesting that there was large-scale star formation throughout the disk of NGC 247 a few hundred Myr in the past.

##### [Low star formation efficiency due to turbulent adiabatic compression in the Taffy bridge](https://arxiv.org/abs/2101.07092)

- About 10% of the molecular gas mass is located in the bridge region.
- The bridge GMAs are clearly not virialized because of their high velocity dispersion
	- Most of the bridge gas detected in CO does not form stars. We suggest that turbulent adiabatic compression is responsible for the exceptionally high velocity dispersion of the molecular ISM and the suppression of star formation in the Taffy bridge.
	
### Jan 19

#### Relevant / Important / Useful

#### Interesting / Keep in Mind

##### [The VANDELS ESO public spectroscopic survey: final Data Release of 2087 spectra and spectroscopic measurements](https://arxiv.org/abs/2101.07645)

- UDS和CDF-S天区
- Together with the redshift catalogue and the reduced spectra, we also provide optical mid-IR photometry and physical parameters derived through SED fitting.

##### [SDSS-IV MaNGA: the physical origin of off-galaxy Hα blobs in the local Universe](https://arxiv.org/abs/2101.07293)

- We have identified 13 Hα blobs in the public data of MaNGA survey
- Hα blobs in our sample can be broadly divided into two groups. 
	- One is associated with interacting/merging galaxy systems, of which the ionization is dominated by shocks or diffuse ionized gas. It is likely that these Hα blobs used to be part of their nearby galaxies, but were stripped away at some point due to tidal interactions. 
	- The other group is found in gas-rich systems, appearing as low-metallicity star-forming regions that are visually detached from the main galaxy.

#### Others

##### [Curved detector-based optical design for the VLT/BlueMUSE instrument](https://arxiv.org/abs/2101.07605)

- #ssst_dev
- We present the optomechanical architecture and design of BlueMUSE at pre-phase A level, with a particular attention to some original aspects such as the use of curved detectors.

##### [Estimating black hole masses in obscured AGN using X-rays](https://arxiv.org/abs/2101.07736)

- We utilized a sample of type 2 AGN with good-quality hard X-ray data obtained by the nuSTAR satellite and with MBH dynamically constrained from megamaser measurements - 看能否用X-ray的scaling relation估计黑洞质量
- when the X-ray broadband spectra are fitted with physically motivated self-consistent models that properly account for absorption, scattering, and emission line contributions from the putative torus and constrain the primary X-ray emission, then the X-ray scaling method yields MBH values that are consistent with those determined from megamaser measurements within their respective uncertainties 基本是通过X-ray光谱拟合得到的

##### [Formation of counter-rotating and highly eccentric massive black hole binaries in galaxy mergers](https://arxiv.org/abs/2101.07266)

- 数值模拟，并合星系中的黑洞并合：all binaries are initially prograde with respect to the galaxy sense of rotation. But, binaries that form with a high eccentricity, e≳0.7, quickly reverse their sense of rotation and become almost perfectly retrograde at the moment of binary formation
- This model indicates that the orbital plane flip is due to the torque from the triaxial background mass distribution that naturally arises from the galactic merger process

##### [Spectroscopic study of the \[OIII\]λ5007 profile in Seyfert 1 galaxies](https://arxiv.org/abs/2101.07288)

- Compare the black hole mass distribution in both BLS1 galaxies with symmetric and blue-asymmetric \[OIII\] profiles.
	- Similar black hole mass distributions were observed in both BLS1 galaxies with symmetric and blueshifted asymmetric \[OIII\] profiles.
	
##### [Star Formation Activity of Galaxies Undergoing Ram Pressure Stripping in the Virgo Cluster](https://arxiv.org/abs/2101.07472)

- We find no clear evidence for enhancement in the integrated star formation activity of galaxies undergoing early to active stripping.
- We are instead able to capture the overall quenching of star formation activity with increasing degree of ram pressure stripping
- 利用HI gas fraction和星系相空间位置可以找到处于不同stripping阶段的星系

##### [Multiwavelength dissection of a massive heavily dust-obscured galaxy and its blue companion at z ∼2](https://arxiv.org/abs/2101.07724)

- 两个高红移星系的个例研究：Astarte is a dusty star-forming galaxy at the massive-end of the main sequence (MS) and Adonis is a less-massive, bright in ultraviolet (UV), companion galaxy with an optical spectroscopic redshift.
- The molecular gas mass of Astarte is far below the gas fraction of typical star-forming galaxies at z=2. This low gas content and high SFR, result in a depletion time of 0.22±0.07 Gyrs, slightly shorter than what is expected for a MS galaxy at this redshift.
- Astarte might be experiencing a recent decrease of star formation activity and is quenching through the MS following a SB epoch.

### Jan 20

#### Relevant / Important / Useful

##### [The Gas Content and Stripping of Local Group Dwarf Galaxies](https://arxiv.org/abs/2101.07809)

- #galaxy/cgm 
- The gas content of the complete compilation of Local Group dwarf galaxies (119 within 2 Mpc) is presented using HI survey data
	- MW周围224 kpc以内，53/55 dwarf的HI气体上限<10^4 Msun
	- M31周围 virial半径以内；27/30缺乏气体
	- Beyond the virial radii of the Milky Way and M31, the majority of the dwarf galaxies have detected HI gas and have HI masses higher than the limits.
- Using the Gaia proper motion measurements available for 38 dwarf galaxies, the minimum gas density required to completely strip them of gas is calculated.
	- Halo densities between 10^{−5} and 5×10^{−4} cm−3 are typically required for instantaneous stripping at perigalacticon
- The results suggest a diffuse gaseous galactic halo medium is important in quenching dwarf galaxies, and that a Local Group medium also potentially plays a role.

##### [How baryons can significantly bias cluster count cosmology](https://arxiv.org/abs/2101.07800)

- #cluster/cosmology 
- We find that because of the need to accommodate the change in the density profile due to the ejection of baryons, weak lensing mass calibrations are only unbiased if the concentration is left free when fitting the reduced shear with NFW profiles.
- Even unbiased total mass estimates give rise to biased cosmological parameters if the measured mass functions are compared with predictions from dark matter-only simulations.
	- 对 $m_{500 \mathrm{c}}<10^{14.5} h^{-1} \mathrm{M}_{\odot}$ halo是主要的bias来源

##### [Low Surface Brightness Galaxies in z > 1 Galaxy Clusters: HST approaches the Progenitors of Local Ultra Diffuse Galaxies](https://arxiv.org/abs/2101.07799)

- #galaxy/lsb 
- This work uses the deepest Hubble Space Telescope (HST) imaging stacks of z > 1 clusters, namely: SPT-CL J2106-5844 and MOO J1014+0038
- 和XDF比，可以看到明显更多的LSB星系
- We find that the LSBs we detect in SPT-CL J2106-5844 and MOO J1014-5844 already have old stellar populations that place them on the red sequence

#### Interesting / Keep in Mind

##### [A restless supermassive black hole in the galaxy J0437+2456](https://arxiv.org/abs/2101.07932)

- #smbh
- Arecibo观测：an observing campaign to confirm the peculiar motion of the supermassive black hole (SMBH) in J0437+2456 first reported in Pesce et al. (2018).
- HI的，星系整体的恒星和电离气体速度都和H2O maser的显著不同
- 但星系的恒星速度和气体速度也不一致，证明星系动力学disturbed

##### [Multiple giant eruptions and X-ray emission in the recoiling AGN/LBV candidate SDSS1133](https://arxiv.org/abs/2101.07797)

- The UV-optical light curves reveal that SDSS1133 experienced three outbursts in 2001, 2014, and 2019.
- The optical spectra exhibit enduring broad hydrogen Balmer P-Cygni profiles with the absorption minimum at ∼−2,000 km/s, indicating the presence of fast moving ejecta.
- 有微弱的Chandra探测，更像是极亮的LBV

#### Others

##### [Dark Matter Constraints from a Unified Analysis of Strong Gravitational Lenses and Milky Way Satellite Galaxies](https://arxiv.org/abs/2101.07810)

- 基于Galacticus模型：We simultaneously infer the projected subhalo number density and the half-mode mass describing the suppression of the subhalo mass function in thermal relic warm dark matter (WDM

##### [The fast radio burst population evolves with the star-formation rate](https://arxiv.org/abs/2101.07998)

- #fast_radio_burst 
- Our fitted parameters demonstrate that the FRB population evolves with redshift in a manner consistent with the star-formation rate, ruling out a non-evolving population
- These results are consistent with the model of FRBs arising as the high-energy limit of magnetar bursts.

##### [The z--DM distribution of fast radio bursts](https://arxiv.org/abs/2101.08005)

- #fast_radio_burst 
- We develop a sophisticated model of FRB observations, accounting for the intrinsic cosmological gas distribution and host galaxy contributions, and give a full account of observational biases due to burst width, dispersion measure, and the exact telescope beamshape.
- We estimate that the unlocalised ASKAP FRBs arise from z<0.5, with between a third and a half within z<0.1.
- We find that above a certain DM, observational biases cause the Macquart (DM--z) relation to become inverted, implying that the highest-DM events detected in the unlocalised Parkes and ASKAP samples are unlikely to be the most distant.
- 直到能定位每个FRB之前不会有太大改变；用简单的DM--z关系得到的结果可能不正确

##### [Connection among environment, cloud-cloud collision speed, and star formation activity in the strongly barred galaxy NGC1300](https://arxiv.org/abs/2101.07798)

- 强调了云团碰撞的重要性: Recent simulations suggest that a CCC speed is different among galactic-scale environments, which is responsible for observed differences in star formation activity.
	- A high-speed CCC is proposed as a cause of star formation suppression in the bar regions in barred spiral galaxies.
- The difference in molecular gas mass (average density) of the giant molecular clouds (GMCs) between the bar (lower mass and lower density) and bar-end (higher mass and higher density) may be cause for the different star formation activity

##### [Sub-damped Lyman alpha systems in the XQ-100 survey II -- Chemical evolution at 2.4<z<4.3](https://arxiv.org/abs/2101.07821)

- Without accounting for ionization and dust depletion effects, we find that the HI-weighted gas-phase metallicity evolution of subDLAs are consistent with damped Lyman alpha systems (DLAs).
- When ionization corrections are included, subDLAs are systematically more metal-poor than DLAs
- The correlation of gas-phase \[Si/Fe\] with metallicity in subDLAs appears to be consistent with that of DLAs, suggesting that the two classes of absorbers have a similar relative dust depletion pattern.
- Both subDLAs and Lyman limit systems could trace carbon-rich ejecta, potentially in circumgalactic environments.

##### [A Census of the Extended Neutral Hydrogen Around 18 MHONGOOSE Galaxies](https://arxiv.org/abs/2101.07822)

- HI environment of 18 MHONGOOSE星系；GBT观测
	- We calculate the total amount of HI gas in and around the galaxies revealing that nearly all of these galaxies contained excess HI outside of their disks
	- 低柱密度弥散气体的比例分布弥散很大
	- However, by binning the percentage of diffuse HI into quarters, we find that the bin with the largest number of galaxies is the lowest quartile (0-25\\% diffuse HI)
- We also find a strong correlation between the fraction of diffuse gas in a galaxy and its baryonic mass

##### [Source Counts Spanning Eight Decades of Flux Density at 1.4 GHz](https://arxiv.org/abs/2101.07827)

- MeerKAT DEEP2观测：spanning the eight decades of flux density between 0.25μJy and 25 Jy at 1.4 GHz
- The brightness-weighted counts converge as $S^{2} n(S) \propto S^{1 / 2}$ below S\=10μJy, so \>99% of the ΔTb∼0.06K sky brightness produced by active galactic nuclei

##### [The Tully-Fisher relation in dense groups at z∼0.7 in the MAGIC survey](https://arxiv.org/abs/2101.08069)

- We study a sample of galaxies in 8 groups spanning a redshift range of 0.5<z<0.8 and located in 10 pointings of the MAGIC MUSE
- Our results suggest a significant offset of the TFR zero-point between galaxies in low- and high-density environments, whatever kinematics estimator is used.
- We show that this evolution of the TFR is consistent either with a decrease of star formation or with a contraction of the mass distribution due to the environment. These two effects probably act together with their relative contribution depending on the mass regime.

##### [Towards modelling Ghostly DLAs](https://arxiv.org/abs/2101.08218)

- We use simple models of the spatial structure of the quasar broad line region (BLR) to investigate the properties of so-called ghostly damped Lyman-{\\alpha} (DLA) systems detected in SDSS data： 有强金属吸收线，没有HI Lya吸收的系统

### Jan 21

#### Relevant / Important / Useful

##### [The buildup of the intracluster light of Abell 85 as seen by Subaru's Hyper Suprime-Cam](https://arxiv.org/abs/2101.08290)

- #cluster/icl #massive_galaxy 
- We measured the radial surface brightness profiles of the brightest cluster galaxy out to the intracluster light (radius ∼215 kpc), for the g and i bands. 
- We found that both the surface brightness and the color profiles become shallower beyond ∼75 kpc suggesting that a distinct component
- The color of the profile at ∼100 kpc suggests that the buildup of the intracluster light of Abell 85 occurs by the stripping of massive (∼10^{10}M⊙) satellites.
- The measured fraction of this light ranges from 8% to 30% in g, depending on the definition of intracluster light chosen.

##### [Constraints on f(R) and nDGP Modified Gravity Model Parameters with Cluster Abundances and Galaxy Clustering](https://arxiv.org/abs/2101.08728)

- #cluster/cosmology #ssst_cos #ssst_gal
- A Fisher analysis is conducted using σ8 constraints derived from thermal Sunyaev-Zel'dovich (tSZ) selected galaxy clusters, as well as linear and mildly non-linear redshift-space 2-point galaxy correlation functions.
- The two tracers of the cosmological gravitational field are found to be complementary, and their combination significantly improves constraints on the f(R) in particular in comparison to each individual tracer alone.

#### Interesting / Keep in Mind

##### [The Atacama Cosmology Telescope: Probing the Baryon Content of SDSS DR15 Galaxies with the Thermal and Kinematic Sunyaev-Zel'dovich Effects](https://arxiv.org/abs/2101.08373)

- #cluster/sze [[SZ Effect]]
- 12-sigma tSZ detection in 2.1 arcmin aperture;
- The corresponding optical depths, τ¯, which depend on the baryon content of the halos, are estimated using results from cosmological hydrodynamic simulations assuming an AGN feedback radiative cooling model.
- We find that the τ¯ estimates from the tSZ measurements in this work and the kSZ measurements in the companion paper agree within 1σ for two out of the three disjoint luminosity bins studied, while they differ by 2-3σ in the highest luminosity bin.
- The optical depth estimates account for one third to all of the theoretically predicted baryon content in the halos across luminosity bins.
- [`Mop-c-GT` - Model-to-observable projection code for galaxy thermodynamics](https://github.com/samodeo/Mop-c-GT)

##### [The Atacama Cosmology Telescope: Detection of the Pairwise Kinematic Sunyaev-Zel'dovich Effect with SDSS DR15 Galaxies](https://arxiv.org/abs/2101.08374)

- #cluster/sze
- 5.4-sigma kSZ detection using three maps
- We consider the impact of various aperture photometry assumptions and covariance estimation methods on the signal extraction.
- [`iskay` - pairwise kSZ calculator](https://github.com/patogallardo/iskay)

##### [The role of stochastic and smooth processes in regulating galaxy quenching](https://arxiv.org/abs/2101.08549)

- #galaxy/quenching
- 解析模型：We have specifically studied the effects of mass quenching, gas stripping, and mergers on galaxy quenching.
- The quenching timescale is on average 1.2 Gyr and a closer look reveals support for the slow-then-rapid quenching scenario.
- The major merging rate of galaxies is about once per 10~Gyr, while the rate of ram pressure stripping is significantly higher.

#### Others

##### [The in-situ formation of molecular and warm ionised gas triggered by hot outflows](https://arxiv.org/abs/2101.08269)

- We investigate an in-situ H2 formation scenario in the outflow using high-resolution simulations, including non-equilibrium chemistry and self-gravity, of turbulent, warm, and atomic clouds
- 10Myr时标上，最多有3%的气体可以被转换为分子气体。
	- The effect is stronger for winds with perpendicular B\-fields and intermediate density clouds
	- Here H2 formation can be boosted by up to one order of magnitude compared to isolated cooling clouds independent of self-gravity.
- Warm ionised gas is also generated, almost independent of the cloud density. The amount solely depend on the magnetic field configuration in the wind.

##### [Hubble Space Telescope Imaging of Isolated Local Volume Dwarfs GALFA-Dw3 and Dw4](https://arxiv.org/abs/2101.08270)

- Both galaxies are extremely isolated, with no other confirmed objects within ~1.5 Mpc of either dwarf.
	- GALFA Dw4 is also found to be unusually compact for a galaxy of its luminosity.
- 心态不规则；都有HII区，年轻星族
- The star formation histories of these two dwarfs show distinct differences: Dw3 shows signs of a recently ceased episode of active star formation across the entire dwarf, while Dw4 shows some evidence for current star formation in spatially limited HII regions.

##### [What to expect when using globular clusters as tracers of the total mass distribution in Milky Way-mass galaxies](https://arxiv.org/abs/2101.08282)

- #globular_cluster 
- We aim to test how well Jeans-Anisotropic-MGE (JAM) models using GCs (positions and line-of-sight velocities) as tracers can constrain the mass and radial distribution of DM halos. 
- 基于E-MOSAICS模拟：We find that the DM halo properties are reasonably well recovered by the JAM models. There is, however, a strong correlation between how well we recover the mass and the radial distribution of the DM and the number of GCs
	- At least 150 GCs are needed in order to guarantee that the JAM model will perform well.

##### [A Spatially-Resolved Survey of Distant Quasar Host Galaxies: II. Photoionization and Kinematics of the ISM](https://arxiv.org/abs/2101.08291)

- OSIRIS/Keck观测：We detect extended ionized emission on scales ranging from 1-30 kpc photoionized by stars, shocks, and active galactic nuclei (AGN).
- Spatially resolved emission-line ratios indicate that our systems reside off the star formation and AGN-mixing sequence on the Baldwin, Phillips & Terlevich (BPT) diagram at low redshift.
- Using gas velocity dispersion as a proxy to stellar velocity dispersion and dynamical mass measurement through inclined disk modeling we find that the quasar host galaxies are under-massive relative to their central supermassive black hole (SMBH) mass

##### [The Hα Dots Survey. IV. A Fourth List of Faint Emission-Line Objects](https://arxiv.org/abs/2101.08328)

- #merian 
- A total of 454 newly discovered objects are included in the current survey list.
- These objects have been detected in searches of moderately deep narrow-band images acquired for the ALFALFA Hα project (Van Sistine et al. 2016).

##### [Internal structure of molecular gas in a main sequence galaxy with a UV clump at z = 1.45](https://arxiv.org/abs/2101.08396)

- Sub-arcsec ALMA observations of CO(2-1) and CO(5-4)
- The CO emission lines are clearly detected and the CO(5-4)/CO(2-1) flux ratio (R\_52) is ~1, similar to that of the Milky Way.
- We find that R\_52 peak coincides with the position of the UV clump and its value is approximately two times higher than the galactic average. 说明UV clump中气体温度或者密度较高
- Compared to the stellar distribution, the molecular gas is more concentrated in the central region of the galaxy.

##### [Spatial segregation impact on star formation in nearby dwarf spheroidal galaxies](https://arxiv.org/abs/2101.08613)

- All objects demonstrate complex star formation history, with a significant portion of stars formed 10-13 Gyr ago; stars of middle ages (1-8 Gyr) are presented

### Jan 24

#### Relevant / Important / Useful

##### [Improving estimates of the growth rate using galaxy-velocity correlations: a simulation study](https://arxiv.org/abs/2101.09026)

- #ssst_sci
- We consider standard estimators of the velocity auto-correlation function, ψ1 and ψ2, the two-point galaxy correlation function, ξgg, and introduce a new estimator of the galaxy-velocity cross-correlation function, ψ3.
- When we consider all four statistics together we find that the statistical uncertainty in our measurement of the growth rate is reduced by 59%

#### Interesting / Keep in Mind

##### [Benchmarking Dust Emission Models in M101](https://arxiv.org/abs/2101.9236)

- [[Dust Model]]
- A comparative study of four physical dust models and two single-temperature modified blackbody models by fitting them to the resolved WISE, Spitzer, and Herschel photometry of M101
- 尘埃质量估计可以查到3倍；Despite differences in their definition of the carriers of the mid-IR aromatic features, all physical models show the same spatial variations for the abundance of that grain population. 
- We show that renormalizing the models to match the same Milky Way high latitude cirrus spectrum and abundance constraints can reduce the dust mass differences between models and bring the total dust mass below the maximum estimate at all radii.

##### [Testing the role of environmental effects on the Initial Mass Function of low mass stars](https://arxiv.org/abs/2101.08804)

- #initial_mass_function #stellar_population 
- We analyse the IMF of eight young clusters (<5 Myr):  After structural analysis and field decontamination we obtain an unbiased, uniformly sensitive sample of Pre-Main Sequence members of the clusters down to brown-dwarf regime. 
- The log-normal fit to the IMF of nine clusters gives the mean characteristic mass (mc) and σ of 0.32±0.02 M⊙ and 0.47±0.02,
- 没有看到显著的环境影响

#### Others

##### [The halo mass function and inner structure of ETHOS haloes at high redshift](https://arxiv.org/abs/2101.08790)

- The Extended Press-Schechter (EPS) formalism with a smooth-k filter is able to predict the cut-off in the halo mass function created by the suppression of small scale power in ETHOS models
- We find that the halo density profiles of all ETHOS models are well described by the NFW profile
- About ETHOS: A novel framework (ETHOS) has been proposed to incorporate new DM physics into structure formation theory, connecting a broad range of DM particle physics to effective parameters that characterize structure formation in the linear regime

##### [Using Pantheon and DES supernova, baryon acoustic oscillation, and Hubble parameter data to constrain the Hubble constant, dark energy dynamics, and spatial curvature](https://arxiv.org/abs/2101.08817)

- A joint analysis of these data sets provides model-independent estimates of the Hubble constant, H0\=68.8±1.8 km s−1 Mpc−1, and the non-relativistic matter density parameter, Ωm0\=0.294±0.020.
- We also add quasar angular size and HII starburst galaxy measurements to the combined data set and find more restrictive constraints.

##### [Reionization and galaxy inference from the high-redshift Lyα forest](https://arxiv.org/abs/2101.09033)

- #cosmology/reionization 
- High-quality quasar spectra have now firmly established the existence of large-scale opacity fluctuations at z > 5, whose physical origins are still debated
- We introduce a Bayesian framework capable of constraining the EoR and galaxy properties by forward-modelling the high-z Ly{\\alpha} forest.
	- Using priors from galaxy and CMB observations, we demonstrate that the final overlap stages of the EoR (when >95% of the volume was ionized) should occur at z < 5.6, in order to reproduce the large-scale opacity fluctuations seen in forest spectra.
- 关于大尺度Gunn-Peterson沟的成因：patchy reionization和不均匀的UV背景共同造成的
 
##### [A new determination of the primordial helium abundance using the analyses of HII region spectra from SDSS](https://arxiv.org/abs/2101.09127)

- From a regression to zero metallicity, we have obtained Yp\=0.2462±0.0022 which is one of the most stringent constraints obtained with such methods up to date 和Planck结果一致
- Further increase of statistics potentially allows us to achieve Planck accuracy, which in turn will become a powerful tool for studying the self-consistency of the Standard Cosmological Model and/or physics beyond.

##### [The X-ray emission of the Seyfert 2 galaxy MCG-01-24-12](https://arxiv.org/abs/2101.08793)

- Based on phenomenological and physically motivated models, we find the X-ray spectrum of MCG-01-24-12 to be best modelled by a power-law continuum emission with Γ\=1.76±0.09 with a high energy cut-off at Ec\=70+21−14 keV that is absorbed by a fairly constant column density

##### [APOGEE DR16: a multi-zone chemical evolution model for the Galactic disc based on MCMC methods](https://arxiv.org/abs/2101.08803)

- An inside-out formation of the Galaxy disc naturally emerges from the best fit of our two-infall chemical-evolution model to APOGEE-DR16: inner Galactic regions are assembled on shorter time-scales compared to the external ones.
- In the outer disc (with radii R\>6 kpc), the chemical dilution due to a late accretion event of gas with primordial chemical composition is the main driver of the \[Mg/Fe\] vs. \[Fe/H\] abundance pattern in the low-α sequence.
- Our results propose a clear interpretation of the \[Mg/Fe\] vs. \[Fe/H\] relations along the Galactic discs. The signatures of a delayed gas-rich merger which gives rise to a hiatus in the star formation history of the Galaxy are impressed in the \[Mg/Fe\] vs. \[Fe/H\] relation, determining how the low-α stars are distributed in the abundance space at different Galactocentric distances.

##### [GASTON: Galactic Star Formation with NIKA2. Evidence for the mass growth of star-forming clumps](https://arxiv.org/abs/2101.08811)

- We conduct an extraction of structures from the 1.15 mm maps using a dendrogram analysis and, by comparison to the compact source catalogues from Herschel survey data, we identify a population of 321 previously-undetected clumps. Approximately 80 per cent of these new clumps are 70 μm-quiet, and may be considered as starless candidates.

##### [Multiphase AGN winds from X-ray irradiated disk atmospheres](https://arxiv.org/abs/2101.9273)

- The mechanism of thermal driving for launching accretion disk winds is interconnected with classical thermal instability (TI)
- We identify a critical radius, Ru, beyond which TI should accompany thermal driving, resulting in clumpy disk wind solutions. Our numerical simulations reveal that clumpiness is a consequence of buoyancy disrupting the stratified structure of smooth solutions.

### Jan 25

#### Relevant / Important / Useful

##### [UltraNest -- a robust, general purpose Bayesian inference engine](https://arxiv.org/abs/2101.09604)

- #bayesian #statistics #inference
- UltraNest is a general-purpose Bayesian inference package for parameter estimation and model comparison. It allows fitting arbitrary models specified as likelihood functions written in Python, C, C++, Fortran, Julia or R.
- [`UltraNest` - Fit and compare complex models reliably and rapidly](https://github.com/JohannesBuchner/UltraNest/)

##### [Redshift-space distortions with split densities](https://arxiv.org/abs/2101.09854)

- [[Redshift Space Distortion]]
- #ssst_sci #cosmology/rsd 
- We take a different perspective to split the galaxy density field according to the local density, and cross-correlate those densities with the entire galaxy field. 比直接用2PCF要好
	- 1. The distribution of peculiar velocities in each split density is nearly Gaussian.
	- 2. The PDF of the density field at small scales is non-Gaussian, but the CCFs of split densities capture the non-Gaussianity, leading to improved cosmological constraints over the 2PCF.
	- 3. Baryon acoustic oscillations (BAO) are contained in all CCFs of split densities. Including BAO scales helps to break the degeneracy between the line-of-sight and transverse AP parameters, allowing independent constraints on them.

#### Interesting / Keep in Mind

##### [Introducing `piXedfit` -- a Spectral Energy Distribution Fitting Code Designed for Resolved Sources](https://arxiv.org/abs/2101.09717)

- #stellar_population #galaxy/spop 
- 主要面对IFU数据：The SED fitting module uses the Bayesian inference technique with two kinds of posteriors sampling methods: Markov Chain Monte Carlo (MCMC) and random densely-sampling of parameter space (RDSPS).
- The RDSPS method gives equally good fitting results as the MCMC and it is much faster than the MCMC.
- [`piXedfit` - is a Python package designed for analyzing spatially resolved SEDs of galaxies](https://github.com/aabdurrouf/piXedfit)

##### [A Lyman-α protocluster at redshift 6.9](https://arxiv.org/abs/2101.10204)

- #cluster/proto-cluster
- We report the discovery of the protocluster LAGER-z7OD1 at a redshift of 6.93, when the Universe was only 770 million years old and could be experiencing rapid evolution of the neutral hydrogen fraction in the intergalactic medium.
	- An overdensity of 6 times the average galaxy density, and with 21 narrowband selected Lyman-α galaxies
- LAGER-z7OD1 shows an elongated shape and consists of two subprotoclusters, which would have merged into one massive cluster
- The total volume of the ionized bubbles generated by its member galaxies is found to be comparable to the volume of the protocluster itself, indicating that we are witnessing the merging of the individual bubbles and that the intergalactic medium within the protocluster is almost fully ionized. 

##### [Discovery of Magnetic Fields Along Stacked Cosmic Filaments as Revealed by Radio and X-Ray Emission](https://arxiv.org/abs/2101.09331)

- #cluster/icm #cluster/magnetic
- 用LRG对作为clusters pair的tracer: we detect an average surface brightness between the clusters from synchrotron (radio) and thermal (X-ray) emission with ≳5σ significance, on physical scales larger than observed to date (≥3Mpc).
- We obtain a synchrotron spectral index of α≃−1.0 and estimates of the average magnetic field strength of 30≤B≤60nG,
- While the X-ray detection is inline with predictions, the average radio signal comes out higher than predicted by cosmological simulations and dark matter annihilation and decay models.
- 说明大尺度结构上的高物质聚集度区域之间有高度磁化的物质，并且用足够强的宇宙线存在，可以产生被探测到的同步加速辐射.

##### [Measuring H0 using X-ray and SZ effect observations of dynamically relaxed galaxy clusters](https://arxiv.org/abs/2101.09389)

- #cluster/cosmology #cosmoloy/h0 [[H0 Tension]]
- 用14个大质量星系团的X-ray和SZ观测限制H0:  H0\=67.3+21.3−13.3 km/s/Mpc
- The intrinsic scatter in the X-ray/SZ pressure ratio is found to be 13±4 per cent (10±3 per cent when two clusters with significant galactic dust emission are removed from the sample), consistent with being primarily due to triaxiality and projection


#### Others

##### [The HI-halo mass relation at redshift z∼1 from the Minkowski functionals of 21 cm intensity maps](https://arxiv.org/abs/2101.09288)

- We investigate the possibility of constraining this HI-halo mass relation (HIHMR) from intensity maps of the redshifted 21 cm line.
	- Use the geometry and topology of the brightness-temperature isocontours in a single frequency channel as quantified by the Minkowski functionals
- For a channel bandwidth of 2 MHz, we show that an integration time of a few×10^4 s per pointing is sufficient to image the smoothed HI distribution at redshift z≃1
- [`minkfncts2d` - An implementation of the 2D Minkowski Functionals in Python](https://github.com/moutazhaq/minkfncts2d)

##### [Evidence for Line-of-Sight Frequency Decorrelation of Polarized Dust Emission in Planck Data](https://arxiv.org/abs/2101.09291)

- **LOS frequency decorrelation**: If a single line of sight (LOS) intercepts multiple dust clouds of different spectral energy distributions and magnetic field orientations, the frequency scaling of each of the Stokes Q and U parameters of thermal dust emission may be different
- Our finding underlines the importance of ongoing studies to map the 3D structure of the magnetized dusty ISM that could help component separation methods to account for frequency decorrelation effects in CMB polarization studies.

##### [Using the redshift evolution of the Lyman-α effective opacity as a probe of dark matter models](https://arxiv.org/abs/2101.09917)

- We explore the redshift evolution of the observable effective optical depth τeff(z) from the Lyman-α data as a discriminator between dark matter models that differ from the ΛCDM model on small scales.
- The simulated effective optical depth for the alternative dark matter models diverges from the ΛCDM model for z≳3, which provides a meaningful probe of the matter power at small scales.

##### [The intra-cluster magnetic field in the double relic galaxy cluster Abell 2345](https://arxiv.org/abs/2101.09302)

- #cluster/icm #cluster/magnetic
- We derived the Rotation Measure (RM) of five polarized sources within ∼ 1 Mpc from the cluster center applying the RM synthesis.
- Using the thermal electron density profile derived from X-ray analysis and simulating a 3D magnetic field with fluctuations following a power spectrum derived from magneto-hydrodynamical cosmological simulations, we build mock RM images of the cluster 并和观测比较
- Within the framework of our model, the data require a magnetic field scaling with thermal electron density

##### [METAL: The Metal Evolution, Transport, and Abundance in the Large Magellanic Cloud Hubble program. II. Variations of interstellar depletions and dust-to-gas ratio within the LMC](https://arxiv.org/abs/2101.09399)

- #inter_stellar_medium 
- HST/ UV spectra toward 32 sightlines in the half-solar metallicity LMC, from which we derive interstellar depletions (gas-phase fractions) of Mg, Si, Fe, Ni, S, Zn, Cr, and Cu.
	- The depletions of different elements are tightly correlated, indicating a common origin.
	- 主要的驱动参数是H的柱密度；Within the parameter space probed by METAL, no correlation with molecular fraction or radiation field intensity are found.
- Dust-to-metal; Dust-to-gas比例随气体柱密度改变，从diffuse区域到molecular gas区域升高3-4倍
	- 这个相关 have important implications for the sub-grid physics of chemical evolution, gas and dust mass estimates throughout cosmic times
- Interstellar depletions are the logarithm of the fraction of metals in the gas-phase. Thus, the depletion for element X is $\delta(X)=\log _{10}(X / H)_{\text {gas }}-\log _{10}(X / H)_{\text {total }}$
	- $\log _{10}(X / H)_{\text {total }}$ is the total abundance of X (gas + dust)., assumed to be equal to the abundance of X in the photospheres of young stars that have formed out of the ISM recently

##### [Remnant Radio Galaxies Discovered in a Multi-frequency Survey](https://arxiv.org/abs/2101.09761)

- GAMA场中的MWA观测：看有多少比例的射电星系是在remnant phase: AGN jets停止后的演化阶段
	- We adopt an absent radio core criterion to identify 10 radio galaxies showing no evidence for an active nucleus	
	- On the other hand, only three show evidence of aged lobe plasma by the presence of an ultra-steep spectrum (α<−1.2) and a diffuse, low surface-brightness radio morphology.
- Remnant阶段比例的下限在4-10%

##### [The Araucaria Project: Deep near-infrared photometric maps of Local and Sculptor Group galaxies. I. Carina, Fornax, Sculptor](https://arxiv.org/abs/2101.09888)

- 很深的J-band和H-band图像：Depth of our photometry reaches about 22 mag at 5σ level, and is comparable to NIR surveys

##### [The Isaac Newton Telescope monitoring survey of Local Group dwarf galaxies -- IV. The star formation history of Andromeda VII derived from long period variable stars](https://arxiv.org/abs/2101.09900)

- M31的stellar halo的金属丰度不低；但dSph都贫金属，证明演化上的联系不紧密。
- 用LPV重构SFH: 
	- As the most-evolved asymptotic giant branch (AGB) and red supergiant (RSG) stars, the birth mass of LPVs can be determined by connecting their near-infrared photometry to theoretical evolutionary tracks.
- Based on their birth mass function, the star-formation rate (SFR) of And VII was obtained as a function of cosmic time. The main epoch of star formation occurred ≃6.2 Gyr ago with a SFR of 0.006±0.002 M⊙ yr−1. Over the past 6 Gyr, we find slow star formation, which continued until 500 Myr ago with a SFR ∼0.0005±0.0002 M⊙ yr−1.

##### [Star formation quenching stages of active and non-active galaxies](https://arxiv.org/abs/2101.10019)

- 基于不同位置上的Halpha发射线对CALIFA星系进行分类，分成六个不同的quenching阶段
	- 1. Objects dominated by recent star formation
	- 2. Systems that present a quiescent-nuclear-ring structure in their centre; 
	- 3. Galaxies that are centrally-quiescent; 
	- 4. Galaxies with no clear pattern in their ionisation gas distribution - mixed; 
	- 5. Systems that posses only a few star-forming regions - nearly-retired, 
	- 6. Galaxies that are completely quiescent - fully-retired.
- 不同group在Mstar-SFR分布上的位置不同
- The proposed emission-line classes reinforce the "inside-out" quenching scenario

##### [Validation of the accuracy and precision of Gaia EDR3 parallaxes with globular clusters](https://arxiv.org/abs/2101.10206)

- #gaia 
- The angular covariance at zero separation is 106.2 muas^2, yielding a minimum uncertainty for EDR3 parallaxes of 10.3 muas for individual stars. 
- The Lindegren et al. parallax bias correction works quite well, except for the brighter magnitudes, suggesting improvements may be possible there.

### Jan 26

#### Relevant / Important / Useful

##### [Dwarf galaxies in the MATLAS survey: Hubble Space Telescope observations of the globular cluster system in the ultra-diffuse galaxy MATLAS-2019](https://arxiv.org/abs/2101.10659)

- #galaxy/udg #galaxy/lsb #globular_cluster 
- Using images in the F606W and F814W filters, we trace the GC population two magnitudes below the peak of the GC luminosity function. Employing Bayesian considerations, we find a total of 37±5 GCs associated with the dwarf, which yields a large GC specific frequency of SN\=84±12
- 估计的Halo mass显示：either this UDG has an overly massive dark matter halo for its stellar mass, compared to other dwarfs -- though not as massive as the Milky Way -- or that the linear relation between the number of GCs and the dark matter halo mass breaks down for UDGs

##### [SHAM through the lens of a hydrodynamical simulation](https://arxiv.org/abs/2101.10733)

- #sham #galaxy_halo 
- We construct galaxy mock catalogues using a standard sub-halo abundance matching scheme coupled with a secondary assignment between galaxy colour or specific star formation rate and the following halo properties: starvation redshift zstarve, concentration at infall, dark matter density contrast δenvR, tidal anisotropy αR, and tidal overdensity δR.
- Among all the secondary halo properties tested, we find that zstarve and δR are the ones that best trace the large-scale structure, producing reliable clustering predictions for different samples of red/blue and quenched/star-forming galaxies.

##### [Signatures of quenching in dwarf galaxies in local galaxy clusters](https://arxiv.org/abs/2101.10728)

- #cluster/galaxy #galaxy/quenching 
- Venhola et al. analysed correlations between colour and surface brightness for galaxies in the Fornax cluster binned by luminosity or stellar mass.
	- 对 <10^8 Msun的dwarf星系：Redness和星系特征面亮度有关系；在Virgo中也有类似关系
- 这个关系可能只对late-type galaxy适用：when analysing early- and late-type galaxies separately, the consistency of the slope of the surface brightness-colour relations with the model expectations for fading and reddening stellar population applies only to the late types
- The sizes of the early- and late-type galaxies at these low masses are comparable 

#### Interesting / Keep in Mind

##### [The VLT-MUSE and ALMA view of the MACS 1931.8-2635 brightest cluster galaxy](https://arxiv.org/abs/2101.10718)

- #galaxy/bcg #cluster/galaxy
- 大质量cool-core星系团中心星系：The ionized gas flux brightness peak corresponds to the location of the supermassive black hole and the system shows a diffuse warm ionized gas tail extending 30 kpc in N-E direction.
	- The ionized and molecular gas are co-spatial and co-moving, with the gaseous component in the tail falling inward, providing fuel for star formation and accretion-powered nuclear activity.
- We measure a star formation rate of 97 Msun/yr, with its peak at the BCG core. However, star formation accounts for only 50-60% of the energetics needed to ionize the warm gas.
- The gas and stellar kinematics are decoupled, with the gaseous velocity fields being more closely related to the bulk motions of the intracluster medium.

#### Others

##### [A MeerKAT view of pre-processing in the Fornax A group](https://arxiv.org/abs/2101.10347)

- We detect HI in 10 galaxies and a total of 1.12 x 109 Msol of HI in the intra-group medium (IGM)
	- There are 9 galaxies that show evidence of pre-processing and we classify the pre-processing status of each galaxy
	- Galaxies currently being pre-processed display HI tails, truncated HI disks with typical gas ratios.
	- Galaxies in the advanced stages of pre-processing are HI deficient. If there is any HI, they have lost their outer HI disk and efficiently converted their HI to H2, resulting in H2\-to-HI ratios an order of magnitude higher than the median for their stellar mass
- 探测到了中心星系过去并合过程甩出的HI气体结构
- We also detect giant (100 kpc) ionised hydrogen (Hα) filaments in the IGM, likely from cool gas being removed (and ionised) from an infalling satellite.
	- We speculate that the Hα and multiphase gas is supported by magnetic pressure (possibly assisted by the AGN), such that the hot gas can condense and form HI that survives in the hot halo for cosmological timescales.

##### [Heavy elements unveil the non primordial origin of the giant HI ring in Leo](https://arxiv.org/abs/2101.10348)

- Taking advantage of MUSE (Multi Unit Spectroscopic Explorer) operating at the VLT, we performed optical integral field spectroscopy of 3 HI clumps in the Leo ring
- We detected, for the first time, ionized hydrogen in the ring and identify 4 nebular regions powered by massive stars
	- 可以测量金属丰度，接近太阳丰度
	- This inference, and the chemical homogeneity among the regions, convincingly demonstrates that the gas in the ring is not primordial, but has been pre-enriched in a galaxy disk

##### [A local baseline of the black hole mass scaling relations for active galaxies. IV. Correlations between MBH and host galaxy σ, stellar mass, and luminosity](https://arxiv.org/abs/2101.10355)

- #smbh 
- HST观测66 local active galactic nuclei (AGNs)；14个有Gemini观测
	- We combine this information with spatially-resolved kinematics obtained at the Keck Telescopes to study the correlations between MBH (determined from single-epoch virial estimators) and host galaxy properties.
- 星系和SMBH的关系依然非常紧致，和宁静早型星系一致：The correlations are uniformly tight for our AGN sample, with intrinsic scatter 0.2-0.4 dex, smaller or equal to that of quiescent galaxies.

##### [Redshift Evolution of the H2/HI Mass Ratio In Galaxies](https://arxiv.org/abs/2101.10372)

- 对5个近邻的Spiral galaxy中有空间分辨的MHI和MH2估计
- 用不同气体质量之间的经验关系，以及横行质量与气体质量间关系的红移演化来看光学半径内的中性气体与分子气体比例：
	- We find that MH2/MHI within the optical radius slightly decreases with redshift, contrary to common expectations of galaxies becoming progressively more dominated by molecular hydrogen at high redshifts.

##### [Exploring the AGN-Merger Connection in Arp 245 I: Nuclear Star Formation and Gas Outflow in NGC 2992](https://arxiv.org/abs/2101.10875)

- Gemini观测：we found that the stellar population is primarily composed by old metal-rich stars (t ≥ 1.4 Gyr, Z≥2.0\\zsun), with a contribution of at most 30 per cent of the light from a young and metal-poor population

##### [\[CII\] and CO Emission Along the Bar and Counter-Arms of NGC 7479](https://arxiv.org/abs/2101.10966)

- SOFIA + ALMA观测：As in most normal galaxies, the \[CII\] emission is generally consistent with emission from cooling gas excited by photoelectric heating in photo-dissociation regions.
- Anomalously high \[CII\]/CO ratios are seen at the two ends of the counter-arms. Both ends show shell-like structures, possibly bubbles, in H-alpha emission.
- The \[CII\] emission probably originates in warm shocked molecular gas heated by the interaction of the radio jet forming the counter-arms with the interstellar medium in the galaxy.