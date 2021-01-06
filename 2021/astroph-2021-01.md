# ArXiv astrop-ph Journal 

- #arxiv

## 2021 Jan 

### Jan 1 

#### Relevant / Important / Useful

##### [An Extended Halo-based Group/Cluster finder: application to the DESI legacy imaging surveys DR8](https://arxiv.org/abs/2012.14998)
- #cluster_galaxies #cluster_cosmology [[Galaxy Cluster Catalogs]]
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

- #cosmology/cluster #ssst/cos
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

##### [Subaru High-z Exploration of Low-Luminosity Quasars (SHELLQs) XII. Extended \[C II\] Structure (Merger or Outflow) in a z = 6.72 Red Quasar](https://arxiv.org/abs/2101.01199)

##### [The Evolution of the Lyman-Alpha Luminosity Function During Reionization](https://arxiv.org/abs/2101.01205)

##### [Observing the host galaxies of high-redshift quasars with JWST: predictions from the BlueTides simulation](https://arxiv.org/abs/2101.01219)

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