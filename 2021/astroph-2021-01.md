# ArXiv astrop-ph Journal 

- #arxiv

## 2021 Jan 

### Jan 1 

#### Relevant / Important / Useful

##### [An Extended Halo-based Group/Cluster finder: application to the DESI legacy imaging surveys DR8](https://arxiv.org/abs/2012.14998)
- #cluster_galaxies #cluster_cosmology 
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
- #photometry [[Reference: Photometric Methods]]
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
