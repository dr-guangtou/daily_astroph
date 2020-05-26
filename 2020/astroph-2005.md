# Astro-ph Notes

---- Song Huang ----

## 2020-May

----

### May 3

- [A hydrodynamical halo model for weak-lensing cross correlations](https://arxiv.org/abs/2005.00009)
  - **Relevant** 关于baryonic effect
  - We develop a cosmology-dependent model for the matter distribution that simultaneously accounts for the clustering of dark matter, gas and stars.
  - We present two variants; one that matches the feedback-induced suppression seen in the matter-matter power spectrum at the per-cent level and a second that matches the matter-matter data slightly less well (~2 per cent), but that is able to simultaneously model the matter-electron pressure spectrum at the ~15 per-cent level.
  - 将tSZ观测和lensing correlation测量功率谱结合起来

- [Euclid: The importance of galaxy clustering and weak lensing cross-correlations within the photometric Euclid survey](https://arxiv.org/abs/2005.00055)
  - **csst, ssst**
  - We aim at understanding the amount of additional information that cross-correlation can provide for parameters encoding systematic effects, such as galaxy bias or intrinsic alignments (IA).
  - We show that XC improves the dark energy Figure of Merit (FoM) by a factor ∼5, whilst it also reduces the uncertainties on galaxy bias by ∼17% and the uncertainties on IA by a factor ∼4.
  - We also show that XC can help in distinguishing between different IA models, and that if IA terms are neglected then this can lead to significant biases on the cosmological parameters.

- [Star formation and morphological properties of galaxies in the Pan-STARRS 3π survey- I. A machine learning approach to galaxy and supernova classification](https://arxiv.org/abs/2005.00155)
  - We train and test two Random Forest (RF) classifiers using photometric features (colors and moments)
  - 给出每个星系是High SF星系和是旋涡星系的概率：We show that by selecting on PHSFF or Pspiral it is possible to significantly enhance or suppress the fraction of core-collapse SNe (or thermonuclear SNe) in the sample with respect to random guessing.

- [The Fornax Deep Survey with VST. VIII. Connecting the accretion history with the cluster density](https://arxiv.org/abs/2005.00025)
  - **Relevant**
  - 19个明亮的ETG：We performed multi-component fits to the azimuthally averaged surface brightness profiles available for all sample galaxies.
  - We find that in the most massive and reddest ETGs the fraction of light in, probably accreted, halos is much larger than in the other galaxies.
  - Inside the virial radius of the cluster, the total luminosity of the intra-cluster light, compared with the total luminosity of all cluster members, is about 34%.

- [Flat Rotation Curves of z∼1 Star-Forming Galaxies and Evidence of Disk-Scale Length Evolution](https://arxiv.org/abs/2005.00279)
  - **Interesting**
  - K-band Multi-Object Spectrograph (KMOS) for Redshift One Spectroscopic Survey (KROSS): 409个0.6< z <1.0的SF星系，平均恒星质量10^10Msun
  - 3DBarolo方法提取Halpha旋转曲线：考虑beam smearing effect和压力梯度效应 (ADC方法)
  - Nearly all objects (0.1< v/σ <15) are affected by the pressure gradient, and we noticed that ADC improves the rotation velocity of these systems by ∼10−87%.
  - We do not see any change in the shape of RCs with respect to the local star-forming disk-type galaxies. In contrast, we do find a significant evolution in the stellar-disk length (RD) of the galaxies.

- [Galaxy Merger Rates up to z ∼ 3 using a Bayesian Deep Learning Model − A Major-Merger classifier using IllustrisTNG Simulation data](https://arxiv.org/abs/2005.00476)
  - We classify major mergers and measure galaxy merger rates up to z ∼ 3 in all five CANDELS fields (UDS, EGS, GOODS-S, GOODS-N, COSMOS) using deep learning convolutional neural networks (CNNs) trained with simulated galaxies from the IllustrisTNG cosmological simulation.
  - We finish by demonstrating that our model is capable of measuring galaxy merger rates, that are consistent with results found for CANDELS galaxies using close pairs statistics, with R(z)=0.02±0.004×(1+z)^2.76±0.21.

----

### May 4

- [Predicting Cosmological Observables with PyCosmo](https://arxiv.org/abs/2005.00543)
  - **Useful**
  - `PyCosmo` is a Python-based framework providing solutions to the Einstein-Boltzmann equations and accurate predictions for cosmological observables

- [X-ray absorption in INTEGRAL AGN: Host galaxy inclination](https://arxiv.org/abs/2005.01028)
  - For our hard X-ray selected sample a deficit of edge-on galaxies hosting type 1 AGN is present.
  - In our hard X-ray selected sample there is a deficit of 24% (+/- 5%) of type 1 AGN.
  - Our findings clearly indicate that material located in the host galaxy on scales of hundreds of parsecs and not aligned with the putative absorbing torus of the AGN can contribute to the total amount of column density.

- [The SAMI Galaxy Survey: stellar population gradients of central galaxies](https://arxiv.org/abs/2005.00541)
  - **Relevant**
  - Stellar population radial gradients (age, metallicity and [α/Fe]) of ∼ 100 passive central galaxies up to ∼2Re.
  - We find negative metallicity radial gradients, which become shallower with increasing stellar mass. The age and [α/Fe] gradients are consistent with zero or slightly positive.
  - We do not observe a significant difference between the stellar population gradients of central and satellite galaxies, at fixed stellar mass.
  - This evidence suggests that the central region of central passive galaxies form in a similar fashion to satellite passive galaxies, in agreement with a two-phase formation scenario.

- [Dynamical Modeling of Galaxies and Supermassive Black Holes: Axisymmetry in Triaxial Schwarzschild Orbit Superposition Models](https://arxiv.org/abs/2005.00542)
  - **Relevant**
  - We show that in order to achieve (oblate) axisymmetry in a triaxial code, care needs to be taken to axisymmetrize the short-axis tube orbits and to exclude both the long-axis tube and box orbits from the orbit library
  - Using up to 12 Gauss-Hermite moments of the line-of-sight velocity distributions as constraints, we demonstrate the effects of orbit types on the best-fit MBH in orbit modeling of the massive elliptical galaxy NGC 1453 reported in Liepold et al. (2020).

- [The formation of dusty cold gas filaments from galaxy cluster simulations](https://arxiv.org/abs/2005.00549)
  - **Relevant**
  - We report a radiation hydrodynamic simulation of AGN feedback in a galaxy cluster, in which cold filaments form from the warm, AGN-driven outflows with temperatures between 10^4 and 10^7 K as they rise in the cluster core.
  - Our analysis reveals a new mechanism, which, through the combination of radiative cooling and ram pressure, naturally promotes outflows whose cooling time is shorter than their rising time, giving birth to spatially extended cold gas filaments.

- [Low Mass Group Environments have no Substantial Impact on the Circumgalactic Medium Metallicity](https://arxiv.org/abs/2005.00779)
  - Explore how environment affects the metallicity of the circumgalactic medium (CGM) using 13 low mass galaxy groups (2-5 galaxies) at ⟨zabs⟩=0.25
  - Both group and isolated CGM metallicities span a wide range (−2<[Si/H]<0), where the mean group (−0.54±0.22) and isolated (−0.77±0.14) CGM metallicities are similar.
  - Contrary to isolated galaxies, we do not find an anti-correlation between {\HI} column density and the nearest group galaxy impact parameter.
  - We conclude that either environmental effects have not played an important role in the metallicity of the CGM at this stage and expect that this may only occur when galaxies are strongly interacting or merging, or that some isolated galaxies have higher CGM metallicities due to past interactions.

- [The XXL Survey. XLI. Radio AGN luminosity functions based on the GMRT 610 MHz continuum observations](https://arxiv.org/abs/2005.01162)
  - GMRT 610MHz XXL-North巡天，30.4 deg^2, 6.5 arcsec beam size
  - The multi-component sources were matched visually with the aid of a computer code: Multi-Catalog Visual Cross-Matching (MCVCM).
  - We constructed the rest-frame 1.4 GHz radio luminosity functions of these sources using the maximum volume method. This survey allows us to probe luminosities of 23≲log(L1.4 GHz[W/Hz])≲28 up to redshifts of z≈2.1.

- [Dynamical evidence of the sub-parsec counter-rotating disc for a close binary of supermassive black holes in the nucleus of NGC 1068](https://arxiv.org/abs/2005.01220)
  - 关于ALMA在NGC1068中心0.2-7 pc处看到的逆向旋转的盘：we find that the Kelvin-Helmholtz (KH) instability (KHI) results in an unavoidable catastrophe of the disc developed at the interface between the reversely rotating parts, and demonstrate that a close binary of supermassive black holes provides tidal torques as the unique external sources to prevent the disc from the KH catastrophe.
  - 作者认为中心一定有双黑洞:the KHI leads to an efficient annihilation of the orbital angular momentum and speed up merge of the binary, providing a new paradigm of solving the long term issue of "final parsec problem".

- [The Next Generation Fornax Survey (NGFS): VII. A MUSE view of the nuclear star clusters in Fornax dwarf galaxies](https://arxiv.org/abs/2005.01532)
  - **Relevant**
  - This work presents the analysis of the NSCs in a sample of 12 dwarf galaxies in the Fornax Cluster observed with MUSE.
  - 有多星族的证据；金属丰度普遍比host星系低 which is consistent with a scenario for mass-assembly through mergers with infalling globular cluster
  - We conclude that the NSCs in these dwarf galaxies likely originated as globular clusters that migrated to the core of the galaxy which have built up their mass mainly through mergers with other infalling clusters, with gas-inflow leading to in-situ star formation playing a secondary role.

----

### May 5

- [Orphan GRB afterglow searches with the Pan-STARRS1 COSMOS survey](https://arxiv.org/abs/2005.01730)
  - There is extensive theoretical and observational evidence suggesting that GRBs are collimated jets; the direct observation of orphan GRB afterglows would further support this model.
  - 目前的极限星等是R~23, 然后用HSC找host，可以做到R~26 mag
  - 目前没有找到：The null result implies that the consideration of jet structures is essential for further orphan GRB afterglow surveys.

- [High-resolution, 3D radiative transfer modelling IV. AGN-powered dust heating in NGC 1068](https://arxiv.org/abs/2005.01720)
  - DustPedia: detailed, 3D radiative transfer simulations of face-on spiral galaxies
  - 看AGN对尘埃的影响：We find a strong wavelength dependency of AGN contamination to the broadband fluxes. It peaks in the MIR, drops in the FIR, but rises again at submm wavelengths.
  - The AGN contribution is measurable at the percentage level in the disc, but quickly increases in the inner few 100 pc, peaking above 90%.

- [Massive disc galaxies in cosmological hydrodynamical simulations are too dark matter-dominated](https://arxiv.org/abs/2005.01724)
  - **Relevant**
  - 比较EAGLE和IllustrisTNG与SPARC比较：the simulated discs inhabit halos that are a factor ~4 (in EAGLE) and ~2 (in IllustrisTNG) more massive than those derived from the rotation curve analysis of the observed dataset.
  - We also use synthetic rotation curves of the simulated discs to demonstrate that the recovery of the halo masses from rotation curves are not systematically biased
  - 可能还是因为Feedback导致的问题，盘星系恒星形成效率太低

- [Probing the AGN Unification Model at redshift z ∼ 3 with MUSE observations of giant Lyα nebulae](https://arxiv.org/abs/2005.01732)
  - We use the morphology of giant Lyα nebulae around AGNs at redshift z∼3 to probe AGN emission and therefore the validity of the AGN unification model at this redshift.
  - 19个Type-I AGN周围的，4个Type-II周围的Lya星云：Type-II周围的在30 pkpc之外更在不对称
  - We discuss how the lack of asymmetry in the inner parts (r≲30 pkpc) and the associated high values of the HeII to Lyα ratios in these regions could indicate additional sources of (hard) ionizing radiation originating within or in proximity of the AGN host galaxies.

- [ALMACAL VII: First Interferometric Number Counts at 650 μm](https://arxiv.org/abs/2005.01733)
  - We present interferometric 650μm submillimetre number counts. Using the Band 8 data from the ALMACAL survey, we have analysed 81 ALMA calibrator fields together covering a total area of 5.5~arcmin2.
  - Using a signal-to-noise threshold of 4.5σ, we find 21 dusty, star-forming galaxies with 650μm flux densities of ≥0.7mJy. At the detection limit we resolve ≃100 per cent of the CIB at 650μm
  - We have therefore identified all the sources contributing to the EBL at 650 microns and predict that the contribution from objects with flux 0.7< mJy will be small.

- [Star Formation in Massive Galaxies at Redshift z∼0.5](https://arxiv.org/abs/2005.01738)
  - **Relevant**
  - z=0.5的>10^11.3 Msun的星系，用u-z颜色看SF：20%有SF，其中大部分都有不对称结构，可能有并合引起; 越不对称，颜色越蓝
  - We find two blue and symmetric galaxies, candidates for massive blue disks, in our observed sample, which indicates that about ∼10% of massive SF galaxies are forming stars in the normal mode of disk star formation

- [New Methods for Identifying Lyman Continuum Leakers and Reionization-Epoch Analogues](https://arxiv.org/abs/2005.01734)
  - 用模拟看low-z Lya Leaker是不是真的和高红移星系很像：We find that the simulated galaxies with high LyC escape fractions (fesc) often exhibit high O32 and populate the same regions of the R23-O32 plane as z∼3 LyC leakers.
  - Viewing angle, metallicity, and ionisation parameter can all impact where a galaxy resides on the O32-fesc plane
  - We find that identifying low-redshift galaxies based on [SII] deficiencies does not seem to produce true analogues.
  - We show that our model using only [CII]158μm and [OIII]88μm can identify potential leakers from non-leakers from the local Dwarf Galaxy Survey.

- [The MOSDEF Survey: the Variation of the Dust Attenuation Curve with Metallicity](https://arxiv.org/abs/2005.01742)
  - We constrain the shape of the attenuation curve by comparing the average flux densities of galaxies sorted into bins of dust obscuration using Balmer decrements
  - 大质量，高金属丰度的符合Calzetti law; 2176A bump强度是银河系的一半左右
  - 低金属丰度星系的消光曲线中没有看到2175 bump：缺少小尘埃颗粒 (?) 和SMC类似
  - 对低金属丰度星系，星云气体消光一般是恒星成分消光的2倍左右；高金属丰度星系中无差别

- [Implications of the mild gas motion found with Hitomi in the core of the Perseus cluster](https://arxiv.org/abs/2005.01883)
  - **Relevant, Interesting**
  - Through (magneto)hydrodynamic and gravitational channels, the moving galaxies are expected to drag the ICM around them, and transfer to the ICM some fraction of their dynamical energies on cosmological time scales.
  - Further assuming that the energy lost by the galaxies is first converted into ICM turbulence and then dissipated, this picture can explain the subsonic and uniform ICM turbulence
  - The scenario may also explain several other unanswered problems regarding clusters of galaxies, including what prevents the ICM from the expected radiative cooling, how the various mass components in nearby clusters have attained different radial distributions, and how a thermal stability is realized between hot and cool ICM components that co-exist around cD galaxies.

- [Examining supernova events in Type 1 active galactic nuclei](https://arxiv.org/abs/2005.02052)
  - A statistical study of intermediate Palomar Transient Factory supernovae (SNe) in Type 1 AGN has shown a major deficit of supernovae around Type 1 AGN host galaxies, with respect to Type 2 AGN hosts. (What?)
  - The findings are supportive of a deficiency of SNe near Type 1 AGN, although we cannot with certainty assess the overall detection fractions of SNe in Type 1 AGN relative to other SN host galaxies
  - Type 1 AGN has equal detection fractions of thermonuclear vs core-collapse SNe. However, we note the possibility of a higher detection rate of core-collapse supernovae in Type-1 AGN with insecure AGN classifications.

- [Atomic Hydrogen Clues to the Formation of Counterrotating Stellar Discs](https://arxiv.org/abs/2005.02355)
  - Interferometric HI observations of six double-disc stellar counterrotator ("2σ") galaxies from the Atlas3D sample.
  - This is the first direct evidence that a double-disc stellar counterrotator could be formed through the accretion of retrograde gas. However, the dominant formation pathway for the formation of 2σ galaxies is still unclear.

- [An obscured AGN population hidden in the VIPERS galaxies: identification through spectral energy distribution decomposition](https://arxiv.org/abs/2005.02361)
  - We aim to identify the obscured AGN population in the VIPERS survey in the CFHTLS W1 field through SED modelling. We construct SEDs for 6,860 sources and identify 160 AGNs at a high confidence level using a Bayesian approach.
  - Our AGN sample is highly complete (~92%) compared to mid-IR colour selected AGNs, including a significant number of galaxy-dominated systems with lower luminosities. In addition to the lack of X-ray emission (80%), the SED fitting results suggest that the majority of the sources are obscured.
  - Interestingly, only 35% of the most luminous mid-IR selected AGNs have X-ray counterparts suggesting strong absorption.

- [A Faster Fourier Transform? Computing Small-Scale Power Spectra and Bispectra for Cosmological Simulations in O(N2) Time](https://arxiv.org/abs/2005.01739)
  - **Useful**
  - https://hipster.readthedocs.io/
  - We present O(N2) estimators for the small-scale power spectrum and bispectrum in cosmological simulations. 对小尺度不使用FFT计算功率谱，By working in configuration-space, both power spectra and bispectra can be computed via a weighted sum of particle pairs up to some radius, which can be reduced at larger k

----

### May 6

- [KiDS+VIKING+GAMA: Testing semi-analytic models of galaxy evolution with galaxy-galaxy-galaxy-lensing](https://arxiv.org/abs/2005.02419)
  - These SAMs can be tested by comparing their predictions for galaxy-galaxy-galaxy-lensing (G3L), which is weak gravitational lensing around galaxy pairs, with observations. 把星系分成不同的颜色和质量bin，其实就是看不同的模型能否产生符合观测的星系对
  - Using an improved G3L estimator, we measure the three-point correlation of the matter distribution for mixed lens pairs with galaxies from different samples, and unmixed lens pairs with galaxies from the same sample.

- [The Accuracy of the Hubble Constant Measurement Verified through Cepheid Amplitudes](https://arxiv.org/abs/2005.02445)
  - We show a direct consequence of crowding by unresolved sources at Cepheid sites is a reduction in the fractional amplitudes of their light curves.
  - We use a simple analytical expression to infer crowding directly from the light curve amplitudes of >200 Cepheids in 3 SNe~Ia hosts and NGC 4258 as observed by HST
  - Where local crowding is minimal, we find near-infrared amplitudes match Milky Way Cepheids at the same periods. At greater stellar densities we find that the empirically measured amplitudes match the values predicted
  - Extragalactic Cepheid amplitudes would need to be ~20% smaller than measured to indicate additional, unrecognized crowding as a primary source of the present discrepancy in H_0.

- [The kinematics of globular cluster populations in the E-MOSAICS simulations and their implications for the assembly history of the Milky Way](https://arxiv.org/abs/2005.02401)
  - Find 18 correlations describing the assembly of L∗ galaxies and their dark matter haloes based on their GC population kinematics. The correlations arise because the orbital distributions of accreted and in-situ GCs depend on the masses and accretion redshifts of accreted satellites, driven by the combined effects of dynamical fraction, tidal stripping, and dynamical heating.
  - The MW assembled its dark matter and stellar mass rapidly through a combination of in-situ star formation, more than a dozen low-mass mergers, and 1.4±1.2 early (z=3.1±1.3) major merger. The rapid assembly period ended early, limiting the fraction of accreted stars.

- [The [OIII]+Hβ Equivalent Width Distribution at z≃7: Implications for the Contribution of Galaxies to Reionization](https://arxiv.org/abs/2005.02402)
  - Using a new colour-selection which precisely selects galaxies at z≃6.63−6.83, a redshift range where blue Spitzer/IRAC [3.6]−[4.5] colours unambiguously indicate strong [OIII]+Hβ emission.
  - EW分布是log-normal的，中值在700AA, 明显比z=2的SF星系的高，符合高SFR和低金属丰度的预期
  - 有些星系的EW>1200 AA: 20% of the z≃7 population has such extreme nebular emission, implying that galaxies likely undergo intense star formation episodes regularly at z>6. 可能对再电离有重要贡献。

- [The e-MERLIN Galaxy Evolution Survey (e-MERGE): Overview and Survey Description](https://arxiv.org/abs/2005.02407)
  - A large program of high-resolution 1.5 GHz radio observations of the GOODS-N field comprising ∼140 hours of observations with eMERLIN and 40 hours with VLA
  - Produce a deep 1.5 GHz radio survey with the sensitivity (∼1.5μJy beam−1), angular resolution (0.2"--0.7") and field-of-view (∼15′×15′) to detect and spatially resolve star-forming galaxies and AGN at z≳1.
  - We measure a mean radio-to-optical size ratio of reMERGE/rHST∼1.02±0.03, suggesting that in most high-redshift galaxies, the ∼GHz continuum emission traces the stellar light seen in optical imaging.

- [The Cosmic Ultraviolet Baryon Survey (CUBS) I. Overview and the diverse environments of Lyman limit systems at z<1](https://arxiv.org/abs/2005.02408)
  - CUBS is designed to map diffuse baryonic structures at redshift z<~1 using absorption-line spectroscopy of 15 UV-bright QSOs with matching deep galaxy survey data.
    - 用NUV亮度选源，因为FUV-bright QSO bias against sightlines intercepting LLS at low redshift.
  - We report five new LLSs of log N(HI)/cm^-2 >~ 17.2; All LLSs exhibit a multi-component structure and associated heavy ions from multiple ionization states such as CII, CIII, MgII, SiII, SiIII, OVI absorption.
  - A diverse range of galaxy properties are seen around these LLSs, from a low-mass dwarf galaxy pair, a co-rotating gaseous halo/disk, a star-forming galaxy, a massive quiescent galaxy, to a galaxy group LLS可以来自各种星系环境，并指示拥有不同气体丰度的结构

- [The Age-Dependence of Mid-Infrared Emission Around Young Star Clusters](https://arxiv.org/abs/2005.02446)
  - We find a tight anti-correlation with a Pearson correlation coefficient of r=−0.84±0.05 between the mass-normalized dust-only 8 μm luminosity and the age of stellar clusters younger than 1 Gyr; the 8 μm luminosity decreases with increasing age of the stellar population.
  - Variations in stellar metallicity have little effect on the scatter, while PAH abundance and the fraction of dust-absorbed light bracket the full range of the data
  - We also find that the trend is better explained by continuous star formation, rather than instantaneous burst models.

- [Hydrodynamical Backflow in X-shaped Radio Galaxy PKS 2014-55](https://arxiv.org/abs/2005.02723)
  - **Interesting**
  - MeerKAT 1.28 GHz total-intensity, polarization, and spectral-index images covering the giant (projected length l≈1.57~Mpc) X-shaped radio source PKS~2014−55
  - They show the clear "double boomerang" morphology of hydrodynamical backflows from the straight main jets deflected by the large and oblique hot-gas halo of the host galaxy PGC~064440.
  - The radio source is embedded in faint (Tb≈0.5K) cocoons having the uniform brightness temperature and sharp outer edges characteristic of subsonic expansion into the ambient intra-group medium.
  - Compression and turbulence in the backflows probably produce the irregular and low polarization bright region behind the apex of each boomerang as well as several features in the flow with bright heads and dark tails.

- [SDSS-IV MaNGA: spatially resolved dust attenuation in spiral galaxies](https://arxiv.org/abs/2005.02772)
  - While both the dust attenuation in the gas and the dust attenuation affecting the stellar populations decrease with galactocentric radius, the ratio of the two quantities does not vary with radius. This ratio does, however, decrease systematically as the stellar mass of the galaxy increases.

- [LEGUS and Halpha-LEGUS Observations of Star Clusters in NGC 4449: Improved Ages and the Fraction of Light in Clusters as a Function of Age](https://arxiv.org/abs/2005.02840)
  - The inclusion of Halpha measurements, the role of stochasticity for low mass clusters, the assumptions about reddening, and the choices of SSP model and metallicity all have important impacts on the age-dating of clusters.
  - The observed cluster age distribution is found to decline over time as dN/dt ~ t^g, with g=-0.85+/-0.15, independent of cluster mass, and is consistent with strong, early cluster disruption.

----

### May 7

- [Nonlinear 3D Cosmic Web Simulation with Heavy-Tailed Generative Adversarial Networks](https://arxiv.org/abs/2005.03050)
  - We demonstrate that a deep-convolutional GAN can generate samples that capture both large- and small-scale features of the matter density field, as validated through a variety of n-point statistics.
  - The use of a data scaling that preserves high-density features and a heavy-tailed latent space prior allow us to obtain state of the art results for fast 3D cosmic web generation.
  - By modeling the latent space with a heavy-tailed prior rather than a standard Gaussian, we better capture sample variance in the high-density voxel PDF and reduce errors in power spectrum and bispectrum covariance on all scales.

- [The Dynamical State of the Frontier Fields Galaxy Cluster Abell 370](https://arxiv.org/abs/2005.03212)
  - Analyzing archival Chandra observations of A370 and comparing the X-ray morphology to the latest gravitational lensing mass reconstruction, we find offsets of ~30 kpc and ~100 kpc between the two X-ray surface brightness peaks and their nearest mass surface density peaks, suggesting that it is a merging system.
  - Our simulations suggest that A370 is a major merger after the second core passage in the infalling phase, just before the third core passage. In this phase, the gas has not settled down in the gravitational potential well of the cluster, which explains why A370 does not follow closely the galaxy cluster scaling relations.

- [Evolution of superclusters and supercluster cocoons in various cosmologies](https://arxiv.org/abs/2005.03480)
  - 比较不同宇宙学下大尺度结构的演化：the open model OCDM with no DE, the standard SCDM model with no DE, and the Hyper-DE HCDM model with an enhanced DE density value.
  - We use diameters of the largest superclusters and the number of superclusters as percolation functions to describe properties of the ensemble of superclusters in the cosmic web.
  - The essential parameter, which defines the evolution of superclusters, is the matter density.
  - The DE density influences the growth of the amplitude of density perturbations, and the growth of masses of superclusters, albeit significantly less strongly

- [VERITAS Discovery of VHE Emission from the Radio Galaxy 3C 264: A Multi-Wavelength Study](https://arxiv.org/abs/2005.03110)
  - NGC3862, or 3C 264中发现VHE Gamma辐射；The observed VHE flux is variable on monthly time scales
  - The VHE emission during this elevated state is well-characterized by a power-law spectrum with a photon index Γ=2.20±0.27.

- [Correlation between relativistic reflection fraction and photon index in NuSTAR sample of Seyfert 1 AGN](https://arxiv.org/abs/2005.03307)
  - AGN的power-law能量分布的X-ray辐射可以被吸积盘反射；吸积盘内部的反射成分可以收到黑洞相对论性效应的显著影响。
  - We investigate the relationship between the relativistic reflection fraction Rf, defined as the ratio of the coronal intensity that illuminates the accretion disc to the coronal intensity observed directly, and the hard X-ray photon index Γ of a NuSTAR sample of Seyfert 1 galaxies.
  - The parameter Rf depends on the amount of Comptonised X-ray emission intercepted by the inner accretion disc. We found a positive correlation between Γ and Rf in our sample.

- [SDSS-IV MaNGA: Excavating the fossil record of stellar populations in spiral galaxies](https://arxiv.org/abs/2005.03012)
  - STARLIGHT拟合：small negative mean age gradients in most spiral galaxies, especially at high stellar mass
  - We show that the youngest (<10^{8.5} years) populations exhibit significantly more extended distributions than the oldest (>10^{9.5} years), again with a strong dependence on stellar mass.
  - 还是支持inside-out盘增长，但是对盘的整体质量演化影响不大

- [Circumgalactic Mg II Emission from an Isotropic Starburst Galaxy Outflow Mapped by KCWI](https://arxiv.org/abs/2005.03017)
  - KCWI观测一个z=0.7的SF星系：shows emission from the Mg II 2796, 2803 Angstrom doublet in the circumgalactic medium (CGM) extending ~37 kpc at 3-sigma significance in individual spaxels
  - Spaxels covering the galaxy stellar regions show clear P-Cygni-like emission/absorption profiles with the blueshifted absorption extending to relative velocities of v = -800 km/s 但在大半径处变成单纯的发射线
  - 辐射转移建模：Our observations are most consistent with an isotropic outflow rather than biconical wind models with half-opening angles phi <= 80 deg.

- [Finding the First Quasars at Birth](https://arxiv.org/abs/2005.03018)
  - 关于直接坍缩形成的黑洞：we present near infrared luminosities for DCBHs born in cold accretion flows in which they are destined to grow to 109 M⊙ by z∼ 7.
  - Strongly-lensed DCBHs could be found in future wide-field surveys by Euclid and the Wide-Field Infrared Space Telescope at z≲ 15.

- [A large amount of diffuse molecular gases in the bar of the strongly barred galaxy NGC1300: Cause of the low star formation efficiency](https://arxiv.org/abs/2005.03019)
  - 看棒区域是否有很多无法产生恒星的弥散分子气体，降低了SFE：We examine the relation between the SFE and the diffuse molecular gas fraction (fdif)
  - Find that the SFE decreases with increasing fdif. 在棒区域，弥散分子气体比例在70-91%；在旋臂区域是30-60%
  - 但弥散分子气体不是唯一原因：The suppression of the SFE in the bar has also been seen even when we exclude the diffuse molecular gas components.

- [A detailed look at the stellar populations in green valley galaxies](https://arxiv.org/abs/2005.03024)
  - 用4000AA break定义Green valley: We explore high quality stacked SDSS spectra, and find a population trend that suggests a substantial difference between low- and high-mass galaxies, with the former featuring younger populations with star formation quenching, and the latter showing older (post-quenching) populations that include rejuvenation events.

- [The twisted dark matter halo of the Milky Way](https://arxiv.org/abs/2005.03025)
  - EAGLE模拟中类似银河系的星系DM halo性质比较；考虑了卫星星系的空间分布和运动学：specifically systems in which the majority of the satellites (8 out of 11) have nearly co-planar orbits that are also perpendicular to the central stellar disc.
  - Orbital plane of the co-planar satellites is well aligned with the minor axis of the host dark matter halo
  - 由此推断银河系Halo结构：The halo, however, is not homologous and its flattening and orientation vary with radius. The inner parts of the halo are rounder than the outer parts and well-aligned with the stellar disc (that is the minor axis of the halo is perpendicular to the disc).

- [On the origin of nitrogen at low metallicity](https://arxiv.org/abs/2005.03038)
  - **Interesting**
  - The observed N/O ratio, however, shows large scatter at low O/H, and is strongly dependent on galactic environment.
  - We show that several heretofore unexplained features of the N/O distribution at low O/H can be explained by the N seen in metal-poor galaxies being mostly primary nitrogen that is returned to the ISM via pre-supernova winds from rapidly rotating massive stars. 不能全靠超新星解释

- [GOODS-ALMA: Using IRAC and VLA to probe fainter millimeter galaxies](https://arxiv.org/abs/2005.03040)
  - Using positional information at 3.6 and 4.5 μm (from Spitzer-IRAC), we explore the presence of galaxies detected at 1.1 mm with ALMA below our original blind detection limit.
  - 找到16个新星系，其中2个没有HST对应; Although exhibiting larger physical sizes, these galaxies have still far-infrared sizes significantly more compact than inferred from their optical emission.
  - 讨论了HST图像的天体测量问题：We show that the astrometry of the HST image does not only suffer from a global astrometric shift, as already discussed in previous papers, but also from local shifts.

- [On the Stellar Kinematics and Mass of the Virgo Ultra-Diffuse Galaxy VCC 1287](https://arxiv.org/abs/2005.03041)
  - **Relevant**
  - KCWI观测：We measure a stellar velocity dispersion (19±6 km s−1) and infer both a dynamical mass (1.11+0.81−0.81×10^9 M⊙) and mass to light ratio (13+11−11) within the half light radius (4.4 kpc). 稍稍偏离正常星系的关系。
  - We use our dynamical mass, and an estimate of GC system richness, to place VCC 1287 on the GC number - dynamical mass relation, finding good agreement with a sample of normal galaxies.
  - Halo可能比较flat或者有core：we find that strong stellar feedback and/or tidal effects are plausibly the dominant mechanisms in the formation of VCC 1287.

- [GOODS-ALMA: The slow downfall of star-formation in z = 2-3 massive galaxies](https://arxiv.org/abs/2005.03043)
  - **Relevant**
  - The galaxies detected by ALMA are among the most massive at z = 2-4 (M⋆,med = 8.5× 10^10 M⊙) and are either starburst or located in the upper part of the galaxy star-forming main sequence.
  - 40%的2.5 < z < 3星系有很低的气体比例；而星系大小似乎与z=2的椭圆星系类似
  - We show that there is a strong link between star formation surface density (at 1.1 mm) and gas depletion time 星系越compact，气体耗尽时标越短： The identified compact sources associated with relatively short depletion timescales (∼100 Myr), are the ideal candidates to be the progenitors of compact elliptical galaxies at z ∼ 2.

- [A 700-pc extended coronal gas emission in the Circinus galaxy](https://arxiv.org/abs/2005.03113)
  - First characterization of an extended outflow of high ionized gas in the Circinus Galaxy by means of the coronal line [FeVII] λ6087 \AA. 分布在[OIII]电离锥内，能到距离AGN 700pc处
  - The gas distribution appears clumpy, with several knots of emission. Its kinematics is complex, with split profiles and line centroids shifted from the systemic velocity.
  - 可能是之前活动的遗迹：the remnants of shells inflated by the passage of a radio-jet.

- [KKH 22, the first dwarf spheroidal satellite of IC 342](https://arxiv.org/abs/2005.03132)
  - ACS观测：We derived its distance of 3.12+-0.19 Mpc using the tip of red giant branch (TRGB) method.
  - BTA测量GC的速度：consistent with the dSph galaxy being gravitationally bound to IC 342.
  - The dSph galaxy KKH 22 has the V-band absolute magnitude of -12.19 mag and the central surface brightness mu_v,0 = 24.1 mag/sq.arcsec.

- [The Sizes of z∼9−10 Galaxies Identified in the BoRG Survey](https://arxiv.org/abs/2005.03515)
  - We explore a vetted sample of BoRG z∼9 and z∼10 candidate galaxies and the object rejected by Morishita+ (2018) to explore the utility of a size criterion in z=9-10 candidate selection.
  - We argue that including a size constraint in lieu of a visual inspection may serve in wide-field searches for these objects in e.g. EUCLID or HST archival imaging with the understanding that some brightest (L>>L∗) candidates may be missed.

----

### May 10

- [KiDS+VIKING-450: Improved cosmological parameter constraints from redshift calibration with self-organising maps](https://arxiv.org/abs/2005.04207)
  - Our fiducial analysis finds marginal posterior constraints of S8=0.716+0.043−0.038; smaller than, but fully consistent with, previous work using this dataset (|ΔS8|=0.023).
  - Our largest shift in S8 is found when calibrating redshift distributions without the DEEP2 spectroscopic subset, where we find S8=0.707+0.046−0.042.

- [Supermassive black holes with high accretion rates in active galactic nuclei. XI. Accretion disk reverberation mapping of Mrk 142](https://arxiv.org/abs/2005.03685)
  - Swift加地面望远镜RM观测：Mrk 142 was highly variable throughout, displaying correlated variability across all wavelengths.
  - 波长越长，time lag越长：through the UV and optical the wavelength-dependent lags, τ(λ), generally follow the relation τ(λ)∝λ^4/3
  - 与一个稳恒态光学厚，几何薄的吸积盘的温度随半径分布的预期一致
  - The exceptions are the u and U band, where an excess lag is observed, as has been observed in other AGN and attributed to continuum emission arising in the broad-line region.
  - Moreover, the X-ray to UV lag is significantly offset from an extrapolation of the UV/optical trend, with the X-rays showing a poorer correlation with the UV than the UV does with the optical.

- [The Sloan Digital Sky Survey Reverberation Mapping Project: MgII Lag Results from Four Years of Monitoring](https://arxiv.org/abs/2005.03663)
  - SDSS RM观测QSO MgII 2800AA的time lag，找到了一个很好sample
  - The MgII lags follow a radius -- luminosity relation with a best-fit slope that is consistent with alpha=0.5 but with an intrinsic scatter of 0.36dex that is significantly larger than found for the Hb radius -- luminosity relation.

- [A flexible modelling of galaxy assembly bias](https://arxiv.org/abs/2005.03672)
  - we propose an extension to the standard SHAM technique so it can include arbitrary amounts of assembly bias. We do this by preferentially selecting subhaloes with the same internal property but different individual large-scale bias.

- [Recovering age-metallicity distributions from integrated spectra: validation with MUSE data of a nearby nuclear star cluster](https://arxiv.org/abs/2005.03682)
  - **Relevant**
  - MUSE观测的M54光谱做成分分解：find a dominant old (8-14 Gyr), metal-poor (-1.5 dex) and a young (1 Gyr), metal-rich (+0.25 dex) component - consistent with the complex stellar populations
  - 和分解星族的结果比：Differences are only 3% in age and 0.2 dex metallicitiy.
  - By co-adding individual stars to create M54's integrated spectrum, we show that the recovered age-metallicity distribution is insensitive to the magnitude limit of the stars or the contribution of blue horizontal branch stars - even when including additional blue wavelength coverage from the WAGGS survey. 但有overshine效应影响，亮星可能会产生老年富金属星族的成分

- [Gas and dust cooling along the major axis of M33 (HerM33es) -- Herschel/PACS [CII] and [OI] observations](https://arxiv.org/abs/2005.03683)
  - We mapped the emission of gas and dust in M33 using the far-infrared lines of [CII] and [OI](63um) and the TIR.
  - The binned [CII]/TIR ratio drops with rising TIR, with large, but decreasing scatter.

- [Search and Analysis of Giant radio galaxies with Associated Nuclei (SAGAN) -- I : New sample & multi-wavelength studies](https://arxiv.org/abs/2005.03708)
  - We have identified 162 new GRGs primarily from the NVSS with sizes ranging from ~0.71 Mpc to ~2.82 Mpc in the redshift range of ~0.03 - 0.95.
  - Our results firmly establish that the distributions of radio spectral index and the black hole mass of GRGs do not differ from the corresponding distributions of normal sized radio galaxies (RGs). 但GRG的Eddington ratio偏低
  - We find that GRGs in high excitation state statistically have larger sizes, radio power, jet kinetic power and Eddington ratio than those in low excitation state.
  - Our environmental study reveals that ~10% of all GRGs may reside at the centres of galaxy clusters, in a denser galactic environment while majority seem to reside in sparse environment.
  - **Interesting**
  - https://sites.google.com/site/anantasakyatta/sagan

- [Weak CS Emission in an Extremely Metal-poor Galaxy DDO 70](https://arxiv.org/abs/2005.03907)
  - we report ALMA observations of the CS J=5→4 emission line of DDO~70, a nearby gas-rich dwarf galaxy with ∼7% solar metallicity.
  - We did not detect CS emission from all regions with strong CO emission. After stacking all CS spectra from CO-bright clumps, we find no more than a marginal detection of CS J=5→4 transition, at a signal-to-noise ratio of ∼3.3

- [CIV emission line properties and uncertainties in black hole mass estimates of z ~ 3.5 quasars](https://arxiv.org/abs/2005.04002)
  - The median logarithm of the CIV- and Hβ-based MBH ratios is 0.110 dex with the scatter of 0.647 dex. The CIV-to-Hβ BH mass differences are significantly correlated with the CIV FWHMs, blueshifts and asymmetries.
  - Corrections of the CIV FWHM using the blueshift and asymmetry reduce the scatter of the mass differences by ∼ 0.04-0.2 dex

- [Unravelling stellar populations in the Andromeda Galaxy](https://arxiv.org/abs/2005.04052)
  - We devise a new technique to recover the distribution of these parameters using spatially resolved, line-of-sight averaged data. Our chemodynamical method is based on the made-to-measure (M2M) framework and results in an N-body model for the abundance distribution
  - We found that the metallicity is enhanced along the bar, with possible maxima at the ansae.
  - In the edge-on view the [Z/H] distribution has an X shape due to the boxy/peanut bulge; the average vertical metallicity gradient is equal to −0.132±0.006 dex/kpc.
  - The highest [α/Fe] is found in the centre, due to the classical bulge. Away from the centre, the α-overabundance in the bar region increases with height, which could be an indication of a thick disc.

----

### May 11

- [Intrinsic and extrinsic correlations of galaxy shapes and sizes in weak lensing data](https://arxiv.org/abs/2005.04604)
  - **Euclid, CSST**
  - Setting up a linear intrinsic alignment model for elliptical galaxies which parameterises the reaction of the galaxy to an external tidal shear field through the velocity dispersion, we predict intrinsic correlations and cross-correlations with weak lensing for both shapes and sizes, juxtaposing both types of spectra with lensing.
  - We quantify the observability of the intrinsic shape and size correlations and estimate with the Fisher-formalism how well the alignment parameter can be determined from the Euclid weak lensing survey.

- [Characterizing EoR foregrounds: A study of the Lockman Hole Region at 325 MHz](https://arxiv.org/abs/2005.05205)
  - This paper demonstrates, for the first time, the variation of the power-law index for diffuse emission at very high galactic locations.

- [Discovering New Strong Gravitational Lenses in the DESI Legacy Imaging Surveys](https://arxiv.org/abs/2005.04730)
  - We compile a training sample that consists of known lensing systems as well as non-lenses in the Legacy Surveys and the Dark Energy Survey. After applying our trained neural networks to the survey data, we visually inspect and rank images with probabilities above a threshold. Here we present 1014 new strong lens candidates.

- [Optical Variability of the Dwarf AGN NGC 4395 from the Transiting Exoplanet Survey Satellite](https://arxiv.org/abs/2005.04491)
  - TESS半个小时的Cadence特别适合研究这些可能的低质量或者低吸积率的AGN的光变：Significant variability is detected on timescales from weeks to hours before reaching the background noise level.
  - Damped random walk模型拟合：lies almost exactly on the extrapolation of the τDRW−MBH relation measured for AGN with BH masses that are more than three orders of magnitude larger.

- [The SAMI Galaxy Survey: Gas velocity dispersions in low-z star-forming galaxies and the drivers of turbulence](https://arxiv.org/abs/2005.04874)
  - 3D forward modeling进行电离气体运动学建模
  - We find the vertical velocity dispersion (σv,z) to be positively correlated with measures of star-formation rate, stellar mass, HI gas mass, and rotational velocity. 和SFR面密度的相关最好
  - This is consistent with recent theoretical models that suggest a σv,z floor driven by star-formation feedback processes with an upturn in σv,z at higher SFR driven by gravitational transport of gas through the disc.
  - Blobby3D (Varidel+2019)

- [Redshift Evolution of Green Valley Galaxies in Different Environments from the Hyper Suprime-Cam Survey](https://arxiv.org/abs/2005.04894)
  - The green valley fraction, when normalized to the total population, is higher in the field than that in groups or clusters and decreases with a decreasing redshift and increasing mass.
  - To assess the effect of the environment on star formation quenching, we define the effective green valley fraction as the ratio of the number of green valley galaxies to that of nonquiescent galaxies only. The effective green valley fraction for field galaxies is lower than that for group or cluster galaxies, which reveals a strong positive mass dependence and mild redshift evolution.

- [Black hole mergers from dwarf to massive galaxies with the NewHorizon and Horizon-AGN simulations](https://arxiv.org/abs/2005.04902)
  - While Horizon-AGN can be used to estimate the rate of inspirals for Pulsar Timing Arrays, NewHorizon can investigate MBH mergers in a statistical sample of dwarf galaxies for LISA, which is sensitive to low-mass MBHs
  - 关于BH并合：we post-process MBH dynamics to account for time delays mostly determined by dynamical friction and stellar hardening
  - MBHs typically merge long after the galaxies do, so that the galaxy morphology at the time of the MBH merger is no longer determined by the galaxy merger from which the MBH merger originated.

- [How Unusual is the Milky Way's Assembly History?](https://arxiv.org/abs/2005.04969)
  - **Interesting**
  - MW有不止一次massive accretion过程：Gaia enceladus和LMC
  - 用EAGLE模拟看有多罕见：We find that ∼ 16 per cent of MW-mass haloes have an LMC; ∼ 5 per cent have a GES event and no further merger with an equally massive object since z = 1; and only 0.65 per cent belong to the LMC & GES category

- [Probing gravity and growth of structure with gravitational waves and galaxies' peculiar velocity](https://arxiv.org/abs/2005.04325)
  - **SSST**
  - We propose to use distances from gravitational wave (GW) detections, in conjunction with the redshifts of their host galaxies from wide field spectroscopic surveys (e.g. DESI, 4MOST, TAIPAN), to measure peculiar motions within the local Universe.
  - We find that binary neutron star mergers with associated counterpart at z≲0.2 that will be detected by the Einstein Telescope (ET) will be able to constrain fσ8 to ∼3% precision after 10 years of operations when combined with galaxy overdensities from DESI and TAIPAN.
  - This constraint is improved to σγ∼0.02−0.03 when combined with galaxy overdensities. The potential of combining galaxies' peculiar velocities with gravitational wave detections for cosmology highlights the need for extensive optical to near--infrared follow--up of nearby gravitational wave events


----

### May 12

- [Dynamic Zoom Simulations: a fast, adaptive algorithm for simulating lightcones](https://arxiv.org/abs/2005.05328)
  - **Interesting**
  - Our method is tailored to the production of lightcone outputs from N-body numerical simulations, which allow for a more efficient storage and post-processing compared to standard comoving snapshots, and more directly mimic the format of survey data. In DZS, the resolution of the simulation is dynamically decreased outside the lightcone surface

- [Three- and two-point spatial correlations of IGM at z∼2: Cloud based analysis using simulations](https://arxiv.org/abs/2005.05346)
  - We explore the transverse three-point correlation (ζ) of these Lyα clouds using mock triplet spectra obtained from hydrodynamical simulations

- [A high-energy neutrino coincident with a tidal disruption event](https://arxiv.org/abs/2005.05340)
  - Here we present the association of a radio-emitting tidal disruption event (AT2019dsg) with another high-energy neutrino, identified as part of our systematic search for optical counterparts to high-energy neutrinos with the Zwicky Transient Facility (ZTF).
  - Our electromagnetic observations can be explained through a multi-zone model, with radio analysis revealing a central engine, embedded in a UV photosphere, that powers an extended synchrotron-emitting outflow. --> provides an ideal site for PeV neutrino production.

- [Accretion of Galaxy Groups into Galaxy Clusters](https://arxiv.org/abs/2005.05344)
  - **Relevant**
  - A median of ∼38% of surviving galaxies at z=0 are accreted as part of groups and did not infall directly from the field, albeit with significant cluster-to-cluster scatter.
  - substructure适合发生星系并合：Integrated over time, we identify (per cluster) an average of 17±6 mergers that occur in infalling galaxy associations, of which 7±3 occur well within the virial radius of their cluster hosts.

- [The Semi-forbidden CIII\]λ1909Å~ Emission in the Rest-Ultraviolet Spectra of Green Pea Galaxies](https://arxiv.org/abs/2005.05399)
  - We detect CIII] emission in 7/10 galaxies with CIII] equivalent widths that range from 2-10\AA~.
  - 与考虑了年轻双星演化的光致电离模型预测一致
  - The Green Pea galaxies do not show a significant correlation between the Lyα and CIII] equivalent widths, and the observed scatter is likely due to the variations in the optical depth of Lyα to the neutral gas.
  - The potential LyC leaker galaxies in our sample have high CIII] equivalent widths that can only be reproduced by starburst ages as young as < 3 Myrs and harder ionizing spectra than the non-leakers.

- [On the variation of carbon abundance in galaxies and its implications](https://arxiv.org/abs/2005.05717)
  - We analyse recent determinations of carbon-to-iron and carbon-to-oxygen abundance ratios in different environments (the Milky Way and elliptical galaxies) using our latest chemical evolution models that implement up-to-date stellar yields and rely on the tight constraints provided by asteroseismic stellar ages
  -  A scenario where most carbon is produced by rotating massive stars, with yields largely dependent on the metallicity of the parent proto-star clouds, allows us to fit simultaneously the high-quality data available for the local Galactic components (thick and thin discs) and for microlensed dwarf stars in the Galactic bulge, as well as the abundance ratios inferred for massive elliptical galaxies.

- [GalICS 2.1: a new semianalytic model for cold accretion, cooling, feedback and their roles in galaxy formation](https://arxiv.org/abs/2005.05958)
  - We take their analysis one step further and present a new semianalytic model that computes the shock radius from first principles. This advancement allows us to compute the critical mass individually for each halo.
  - Separating cold-mode and hot-mode accretion has little effect on the final galaxy masses if feedback does not preferentially couple to the hot gas

----

### May 13

- [An accurate emulator for the redshift-space power spectrum of dark matter halos and its application to galaxy power spectrum](https://arxiv.org/abs/2005.06122)
  - 基于Dark Quest模拟：we develop a simulation-based template, so-called emulator, for the redshift-space power spectrum of dark matter halos. 基于Neural Network的
  - Our emulator achieves about 1 and 5% fractional accuracies in predicting the monopole and quadrupole moments of the power spectrum.

- [A measurement of the CMB E-mode angular power spectrum at subdegree scales from 670 square degrees of POLARBEAR data](https://arxiv.org/abs/2005.06168)
  - We reach an effective polarization map noise level of 32μK-arcmin across an observation area of 670 square degrees
  - The data are consistent with the standard ΛCDM cosmological model with a probability-to-exceed of 0.38.

- [SatGen: a semi-analytical satellite galaxy generator -- I. The model and its application to Local-Group satellite statistics](https://arxiv.org/abs/2005.05974)
  - **Interesting, SSST**
  - The model combines dark-matter halo merger trees, empirical relations for the galaxy-halo connection, and analytic prescriptions for tidal effects, dynamical friction, and ram pressure stripping.
  - SatGen emulates cosmological zoom-in hydro-simulations in certain aspects. Satellites can reside in cored or cuspy DM subhaloes, depending on the halo response to baryonic physics that can be formulated from hydro-simulations and physical modeling.
  - We use the model to study satellites of Milky Way sized hosts, making it emulate simulations of bursty star formation and of smooth star formation, respectively, and to experiment with a disc potential in the host halo

- [The Pristine Dwarf-Galaxy survey -- III. Revealing the nature of the Milky Way globular cluster Sagittarius II](https://arxiv.org/abs/2005.05976)
  - We find a low velocity dispersion of SgrII v = 1.7 +/- 0.5 km s-1, in agreement with the dispersion of Milky Way globular clusters of similar luminosity.
  - We confirm the very metal-poor nature of the satellite ([Fe/H]_SgrII = -2.23 +/- 0.07) and find that the metallicity dispersion of Sgr II is not resolved
  - No star with a metallicity below -2.5 is confidently detected. Therefore, despite the unusually large size of the system (rh = 35.5 +1.4-1.2 pc), we conclude that Sgr II is an old and metal-poor globular cluster of the Milky Way.

- [Constraints on the assembly history of the Milky Way's smooth, diffuse stellar halo from the metallicity-dependent, radially-dominated velocity anisotropy profiles probed with K giants and BHB stars using LAMOST, SDSS/SEGUE, and Gaia](https://arxiv.org/abs/2005.05980)
  - 用SDSS/SEGUE blue horizontal branch stars and SDSS/SEGUE and LAMOST K giants研究银河系halo的anisotropy profile
  - We find radially dominated kinematic profiles with nearly constant anisotropy within 20 kpc, beyond which the anisotropy profile gently declines although remains radially dominated to the furthest extents of our sample.
  - Independent of star type or substructure removal, the anisotropy depends on metallicity, such that the orbits of the stars become less radial with decreasing metallicity.

- [The globular cluster system mass-halo mass relation in the E-MOSAICS simulations](https://arxiv.org/abs/2005.05991)
  - **Relevant**
  - The simulated M_gc-M_halo relation is linear for halo masses >5×1011 Msun, and is driven by the hierarchical assembly of galaxies, in agreement with previous studies.
  - Below this halo mass, the simulated relation features a downturn, which we show is consistent with observations, and is driven by the underlying stellar mass (M_star)-halo mass relation of galaxies.
  - Our fiducial model reproduces the observed M_gc-M_star relation across the full mass range, which we argue is more physically relevant than the M_gc-M_halo relation.

- [The variable and non-variable X-ray absorbers in Compton-thin type-II Active Galactic Nuclei](https://arxiv.org/abs/2005.06079)
  - X-ray光变观测20个Compton薄的Type-II AGN，研究前方遮挡中性气体的变化：We detected variability in the column density of the full-covering absorber in 7/20 sources, on timescales of months-years, indicating a component of compact-scale X-ray-obscuring gas lying along the line of sight of each of these objects.
  - However, 13/20 sources yielded no detection of significant variability in the full-covering obscurer. The dominant absorbing media in these systems could be distant, such as kpc-scale dusty structures associated with the host galaxy, or a homogeneous medium along the line of sight.

- [The Three Hundred Project: the stellar and gas profiles](https://arxiv.org/abs/2005.06135)
  - **Relevant**
  - We study the scatter and self-similarity of the profiles and distributions of the baryonic components of the clusters: the stellar and gas mass, metallicity, the stellar age, gas temperature, and the (specific) star formation rate.
  - We find that the shape and the scatter of the gas density profiles matches well the observed trends including the reduced scatter at large radii which is a signature of self-similarity suggested in previous studies.
  - The gas metallicity profiles from both simulation sets, despite following the observed trend, have a relatively lower normalisation
  - The stellar age, metallicity and (s)SFR show very large scatter, which are then presented in 2D maps. We also do not find any clear radial dependence of these properties. However, the brightest central galaxies have distinguishable features compared to the properties of the satellite galaxies.

- [A Data-Driven Technique Using Millisecond Transients to Measure the Milky Way Halo](https://arxiv.org/abs/2005.06256)
  - We model these distributions, correcting for the Galactic interstellar medium, with kernel density estimation---well-suited to the small data regime---to find lower/upper bounds to the corrected DMpulsar/DMFRB distributions 给出银河系Halo的DM测量的范围
  - 来自FRB host的DM成分暂时无法扣除；It strongly disfavors models where the Galaxy has retained the majority of its baryons with a density profile tracking the presumed dark matter density profile.

- [The changing circumgalactic medium over the last 10 Gyr I: physical and dynamical properties](https://arxiv.org/abs/2005.06310)
  - EAGLE模拟用的银河系质量halo：We find that the high-z CGM is almost equally divided between the "cool" (T<105 K) and "hot" (T≥105 K) phases, while the low-z hot CGM phase contains 5× more mass.
  - The high-z hot CGM contains 60% more metals than the cool CGM, while the low-z cool CGM contains 35% more metals than the hot CGM content.
  - 高红移处的hot CGM主要是高温外流；冷气体主要是在内流，但同时cold metal有净的外流
  - At low z, the cool metals dominate the interior and the hot metals are more prevalent at larger radii. The low-z cool CGM has tangential motions consistent with rotational support out to 0.2R200, often exhibiting r≈40 kpc disc-like structures.
  - CGM的温度，密度，金属丰度，运动学都有很强的演化

- [A Low Incidence of Mid-Infrared Variability in Dwarf Galaxies](https://arxiv.org/abs/2005.06452)
  - ALLWISE/NEOWISE: We find only 2 dwarf galaxies with mid-infrared variability, a factor of ~10 less frequent than the more massive galaxies (p = 6 x 10^-6),
  - Compared to the more massive galaxies, AGNs selected in dwarf galaxies using either their mid-infrared color or optical emission line classification are systematically missed by variability selection 也许cadence更高了就行

- [Systematically Asymmetric: A comparison of \hi\ profile asymmetries in real and simulated galaxies](https://arxiv.org/abs/2005.06453)
  - We find that our newly introduced channel-by-channel asymmetry is less sensitive to the effects of viewing angle and inclination than other morphometrics.
  - We find that the lopsidedness-velocity of equality space can be used to identify profiles with deep central dips without visual inspection.

----

### May 14

- [The impact of non-Gaussianity on the Epoch of Reionization parameter forecast using 21-cm power spectrum measurements](https://arxiv.org/abs/2005.06535)
  - 三个参数描述再电离：能支撑电离源的最小暗物质晕质量，暗物质晕内单位重子物质能提供的逃逸电离光子数量，以及电离光子在IGM中的平均自由程。看未来21cm测量能测量到多精确。
  - 考虑了非高斯性：Considering cosmic variance only and assuming that foregrounds are completely removed, we find that non-Gaussianity increases the volume of the 1σ error ellipsoid of the parameters by a factor of 133 relative to the Gaussian predictions
  - The impact of non-Gaussianity increases for longer observations, and it is particularly important for Rmfp.

- [Parameter Inference for Weak Lensing using Gaussian Processes and MOPED](https://arxiv.org/abs/2005.06551)
  - **CSST, SSST**
  - A Gaussian Process (GP) emulator for the calculation of a) tomographic weak lensing band-power spectra; b) coefficients of summary data massively compressed with the MOPED algorithm
  - The GP opens up the possibility of dropping the Limber approximation, without which the theoretical calculations may be unfeasibly slow. A potential advantage of GPs is that an error on the emulated function can be computed and this uncertainty incorporated into the likelihood.

- [CMB Shadows: The Effect of Interstellar Extinction on Cosmic Microwave Background Polarization and Temperature Anisotropy](https://arxiv.org/abs/2005.06614)
  - **Interesting**
  - We evaluate the degradation of the accuracy of the component separation between the cosmic microwave background (CMB) and foreground components caused by neglect of absorption of the monopole component of the CMB by the galactic interstellar matter. 因为尘埃引起的CMB影子产生的温度变化在 1 uK左右; 精度与测量非高斯性的要求类似
  - 对偏振测量的影响更大：the amplitude of the polarization caused by the CMB shadow due to dust is comparable to or larger than the RMS value of the CMB B-mode polarization, imprinted by primordial gravitational waves
  - We show that applying a single-power law model as the dust spectrum to observed multifrequency data introduces systematic errors

- [ECoPANN: A Framework for Estimating Cosmological Parameters using Artificial Neural Networks](https://arxiv.org/abs/2005.07089)
  - For a well trained ANN model, it is capable of estimating parameters for multiple experiments that have different precisions, which can greatly reduce the consumption of time and computing resources for parameter inference.

- [PypeIt: The Python Spectroscopic Data Reduction Pipeline](https://arxiv.org/abs/2005.06505)
  - **Useful**
  - PypeIt is a Python package for semi-automated reduction of astronomical, spectroscopic data.

- [The SAMI Galaxy Survey: Decomposed Stellar Kinematics of Galaxy Bulges and Disks](https://arxiv.org/abs/2005.06474)
  - 本质上还是测光分解：The spatially-resolved rotation velocity (V) and velocity dispersion (σ) of bulge and disk components have been simultaneously estimated using the penalized pixel fitting (pPXF) method with photometrically defined weights for the two components.
  - We present Tully-Fisher and Faber-Jackson relations showing that the galaxy stellar mass scales with both V and σ for both components of all galaxy types. We find a tight Faber-Jackson relation even for the disk component.
  - bulge and disk components are kinematically distinct:
    - (1) the two components show scaling relations with similar slopes, but different intercepts;
    - (2) the spin parameter λR indicates bulges are pressure-dominated systems and disks are supported by rotation;
    - (3) the bulge and disk components have, respectively, low and high values in intrinsic ellipticity.

- [A Deeper Look at DES Dwarf Galaxy Candidates: Grus I and Indus II](https://arxiv.org/abs/2005.06478)
  - MegaCam观测：we resolved the main sequence turn-off (MSTO) and ∼2 mags below it.
  - We show Grus I to be consistent with an old, metal-poor (∼13.3 Gyr, [Fe/H]∼−1.9) dwarf galaxy；an absolute V-band magnitude ∼−4.1
  - Although our photometry of Indus II is ∼2−3 magnitudes deeper than the DES Y1 Public release, we find no coherent stellar population at its reported location. 可能是False positive.

- [Living with Neighbors. III. Scrutinizing the Spin−Orbit Alignment of Interacting Dark Matter Halo Pairs](https://arxiv.org/abs/2005.06479)
  - **Interesting**
  - Spin−orbit alignment (SOA; i.e., the angular alignment between the spin vector of a halo and the orbital angular momentum vector of its neighbor) 适合研究星系角动量演化
  - 把模拟中维里半径相互接触的，质量比在1/3-3之间的halo pair分成并合和flyby组：we find a significant SOA in that 75.0±0.6 % of merging neighbors and 58.7±0.6 % of flybying neighbors are on the prograde orbit.
  - The overall SOA of our sample is mainly driven by fast-rotating halos, corroborating that a well-aligned interaction spins a halo faster.
  - We find for the first time a strong number excess of nearly perpendicular but still prograde interactions (∼75∘) in the spin−orbit angle distribution for both the merger and flyby cases. Such prograde-polar interactions predominate for slow-rotating halos, testifying that misaligned interactions reduce the halos' spin.
  - The prograde-polar interaction will soon flip the spin of a slow-rotator to align with its neighbor's orbital angular momentum.

- [Photometric redshifts for the Pan-STARRS1 survey](https://arxiv.org/abs/2005.06489)
  - The photometric redshift of a galaxy is then estimated by means of a local linear regression in a 5-dimensional magnitude and colour space.
  - Even though the relation between each of the Pan-STARRS1 colours and the spectroscopic redshifts is noisier than for SDSS colours, the results obtained by our method are very close to those yielded by SDSS data.

- [A Thirty-Four Billion Solar Mass Black Hole in SMSS J2157-3602, the Most Luminous Known Quasar](https://arxiv.org/abs/2005.06868)
  - 用MgII双线测量，(3.4 +/- 0.6) x 10^10 M_sun and refine the redshift of the quasar to be z=4.692
  - 已知光度最高的QSO，its Eddington ratio is only ~0.4

- [Velocity Dispersions of Massive Quiescent Galaxies from Weak Lensing and Spectroscopy](https://arxiv.org/abs/2005.07122)
  - **Relevant**
  - 用quiescent星系的中心速度弥散度和stacking lensing signal得到的暗物质晕速度弥散度比较
  - We measure the stacked lensing signal from the HSC deep imaging. The central stellar velocity dispersion is directly proportional to the velocity dispersion derived from the lensing σLens, σLens=(0.98±0.14)σSHELS+(19.89±31.89).

----

### May 18

- [The 21 cm-kSZ-kSZ Bispectrum during the Epoch of Reionization](https://arxiv.org/abs/2005.06535)
  - The 21 cm signal and the contribution to the kSZ from the EoR are expected to be anti-correlated, the former coming from regions of neutral gas in the intergalactic medium and the latter coming from ionized regions 但简单的cross-correlation不能得到有用的信号
  - We present here an investigation of the 21 cm-kSZ-kSZ bispectrum, which should not suffer the same cancellation as the simple two-point cross-correlation. We show that there is a significant and non-vanishing signal that is sensitive to the reionization history

- [Effects of self-consistent rest-ultraviolet colours in semi-empirical galaxy formation models](https://arxiv.org/abs/2005.07208)
  - 在SEM框架下讨论高红移星系UV LF和尘埃的关系：we find that UV colours evolve with redshift (at fixed UV magnitude), as suggested by observations, even in cases without underlying evolution in dust production, destruction, absorption, or geometry. 主要由星族年龄和sSFR变化引起
  - The UV extinction, AUV, evolves similarly with redshift, though we find a systematically shallower relation between AUV and MUV than that predicted by IRX-β relationships derived from z∼3 galaxy samples

- [The origin of the escape of Lyman alpha and ionizing photons in Lyman Continuum Emitters](https://arxiv.org/abs/2005.07215)
  - 低中性气体柱密度是LyC的关键：we highlight strong correlations between the presence of low HI covering fractions and (1) low LyA peak velocities; (2) more flux at the profile minimum; and (3) larger EW(LyA), fesc(LyA), and fesc(LyC).
  - Galaxies with narrower HI absorption velocity widths have higher LyA equivalent widths, larger LyA escape fractions, and lower LyA peak velocity separations.
  - Finally, we find that dust regulates the amount of LyA and LyC radiation that actually escapes the ISM. ISM的多孔性是产生LyC的重要因素，但不足以解释观测到的最强的LyC

- [Galaxy classification: deep learning on the OTELO and COSMOS databases](https://arxiv.org/abs/2005.07228)
  - We used three classification methods for the OTELO database: 1) u-r color separation , 2) linear discriminant analysis using u-r and a shape parameter classification, and 3) a deep neural network using the r magnitude, several colors, and a shape parameter.

- [Dust Reverberation Mapping of Type 2 AGN NGC 2110 Realized with X-ray and 3-5 μm IR monitoring](https://arxiv.org/abs/2005.07339)
  - Here we focus on an X-ray-bright type 2 AGN, NGC 2110, and utilize 2-20 keV X-ray variation monitored by MAXI to trace disc emission, instead of optical-UV variation.
  - X-ray和WISE光变曲线：we found candidates of the dust reverberation time lag at ∼60 days, ∼130 days, and ∼1250 days between the X-ray flux variation and those of the IR bands.
  - we found that the time lag of ∼130 days is most favoured. With this time lag, the relation between the time lag and luminosity of NGC 2110 is consistent with those in type 1 AGNs

- [Bar rejuvenation in S0 galaxies?](https://arxiv.org/abs/2005.07387)
  - We found that bars are bluer in S0 galaxies compared to the spiral galaxies
  - The possibility of minor mergers and tidal interactions which occurs frequently in the intermediate-density environment might have caused either a bar to form and/or induce star formation in the barred region of S0 galaxies.
  - The underlying discs show the usual behaviour being redder in S0s compared to spiral galaxies while the bulges are red and old for both S0 and spiral galaxies

- [Formation of the Large Nearby Galaxies](https://arxiv.org/abs/2005.07588)
  - **Interesting**
  - 近邻L*星系的bulge fraction很低，和模拟预测得不同，轨道性质也不同。认为可能有宇宙学背景
  - The situation might be improved by a prescription for non-Gaussian initial conditions on the scale of galaxies.

- [The Formation of Isolated Ultra-Diffuse Galaxies in Romulus25](https://arxiv.org/abs/2005.07634)
  - **Relevant**
  - At z=0, we find that isolated UDGs have average star formation rates, colors, and virial masses for their stellar masses and environment.
  - We predict that many isolated UDGs have been missed by current surveys. 可能占到field星系的20%
  - Despite their isolation at z=0, the UDGs in our sample are the products of major mergers at z>1. Mergers are no more common in UDG than non-UDG progenitors, but mergers that create UDGs tend to happen earlier, produce a temporary boost in spin, and cause star formation to migrate to the outskirts of galaxies

- [Galaxy properties as revealed by MaNGA. III. Kinematic profiles and stellar population gradients in S0s](https://arxiv.org/abs/2005.07693)
  - **Relevant**
  - MaNGA z<0.08 S0星系的Lick index-based Spop gradient研究
  - 质量> 3x10^10 Msun的S0的年龄和速度弥散度梯度较明显，但丰度梯度很平；而低于这个质量的则反之
  - 在相同的速度弥散度或者光度上S0比FR-Ell的速度弥散度梯度要陡
  - The kinematic profiles and stellar population gradients of E-FRs are both more similar to those of slow rotating ellipticals (E-SRs) than to S0s, suggesting that E-FRs are not simply S0s viewed face-on.
  - 在固定的速度弥散度上，S0和E-FR比E-SR年轻。

----

### May 19

- [Constraining the Reionization History using Bayesian Normalizing Flows](https://arxiv.org/abs/2005.07694)
  - 21cm信号有非Gaussian的特性，比较难拟合
  - We demonstrate the advantages of Normalizing Flows (NF) combined with BNNs, being able to model more complex output distributions and thus capture key information as non-Gaussianities
  - Normalizing flows: Transforming probability distributions has become a powerful tool in deep learning. The main idea of a Normalizing Flow is to use a diffeomorphism (a differentiable and bijective mapping) to transform the sample space of a distribution.

- [ALMA Characterises the Dust Temperature of z ~ 5.5 Star-Forming Galaxies](https://arxiv.org/abs/2005.07716)
  - ALMA Band-8观测z=5.5的星系：we measure for the first time the emissivity index at these redshifts to provide more robust estimates of molecular gas masses based on dust continuum.
  - The derived dust peak temperatures at z ∼ 5.5 (38±8 K) are elevated compared to average local galaxies, however, 5−10 K below what would be predicted from an extrapolation of the trend at z < 4 可能是来自尘埃丰度的下降
  - 分子气体质量在10^10-10^11之间，气体比例在30-80%之间

- [Science with the TianQin Observatory: Preliminary Results on Galactic Double White Dwarf Binaries](https://arxiv.org/abs/2005.07889)
  - 讨论用天琴探测 Galactic double white dwarf (DWD) binaries: 能探测到已知DWD中的12个，可以提前预测信号，作为校验源
  - 有望探测到10^4量级的DWD：能测量轨道周期和幅度

- [Science with the TianQin observatory: Preliminary result on extreme-mass-ratio inspirals](https://arxiv.org/abs/2005.08212)
  - EMRIs: allow for testing gravitational theories in the strong field regime, and for checking the validity of the black hole no-hair theorem.
  - We find that TianQin can observe EMRIs involving COs with mass of 10M⊙ up to redshift ∼2
  - We also find that a network of multiple detectors would allow for improvements in both detection rates

- [A comparison of X-ray photon indices among the narrow and broad-line Seyfert 1 galaxies](https://arxiv.org/abs/2005.08352)
  - We found clear evidence of the difference in the ΓsX and REdd distributions among NLSy1 and BLSy1 galaxies, with steeper ΓsX and higher REdd for the former
  - The difference in REdd distributions does exist even after applying the average correction for the difference in the inclination angle of NLSy1 and BLSy1 galaxies
  - Our analysis suggests that the higher REdd in NLSy1 is responsible for its steeper X-ray spectral slope compared to the BLSy1, consistent with the disc-corona model as proposed for the luminous AGNs.

- [Hard - X-rays selected Active Galactic Nuclei. I. A radio view at high-frequencies](https://arxiv.org/abs/2005.08569)
  - We present JVLA 22 and 45 GHz observations of 16 nearby (0.003≤z≤0.3) hard - X-rays selected AGN at the (sub)-kpc scale 15/16 detected
  - All detected sources host a compact core, with 8 being core-dominated at either frequencies, the others exhibiting also extended structures.
  - We conclude that, at these frequencies, extended, optically-thin components are present together with the flat-spectrum core.

- [Lyman-αabsorption beyond the disk of simulated spiral galaxies](https://arxiv.org/abs/2005.08580)
  - On average the galaxies retain about 50\% of the cosmic fraction in baryons, almost equally divided into disc (interstellar medium) gas, cool CGM gas and warm-hot CGM gas
  - At radii smaller than 50 kpc the CGM is dominated by recycled warm-hot gas injected from the central galaxy, while at larger radii it is dominated by cool gas accreted onto the halo. Recycled gas占CGM气体的1/3.
  - 和观测的Lya吸收EW分布类似：Disc galaxies with quiescent assembly histories show significantly more absorption along the disc major axis

- [The Host Galaxies of Rapidly Evolving Transients in the Dark Energy Survey](https://arxiv.org/abs/2005.08653)
  - **SSST**
  - 红移>1, peak光度分布很宽，光变曲线衰减比SN快。后续观测难度大，物理机制和起源未知
  - We find that RETs explode exclusively in star-forming galaxies and are thus likely associated with massive stars.
  - We find that RETs prefer galaxies with high specific SFRs, indicating a link to young stellar populations
  - There are no clear relationships between properties of the host galaxies and the peak magnitudes or decline rates of the transients themselves.

----

### May 20

- [Antisymmetric cross-correlation of line-intensity maps as a probe of reionization](https://arxiv.org/abs/2005.08977)
  - The proposed estimator is the hitherto neglected antisymmetric component of the cross-correlation, under the exchange of line-of-sight positions
  - As a way to break the degeneracy between astrophysics and cosmology in the intensity mapping power spectrum, we study the ratio between the antisymmetric and symmetric components
  - 2PCF应该依赖于两个点的指向和位置，但是一般假设CF与交换位置无关；但是如果是两个完全不同的tracers的CF则不然。需要考虑 antisymmetric component.
    - 在Line intensity mapping里面，功率谱的antisymmetric成分依赖于温度和所用发射线的bias的红移演化。

- [Redshift Evolution of the Underlying Type Ia Supernova Stretch Distribution](https://arxiv.org/abs/2005.09441)
  - We study the dependence with redshift of the SN Ia SALT2.4 lightcurve stretch, a purely intrinsic SN property, to probe its potential redshift drift.
  - We clearly demonstrate that the underlying SN Ia stretch distribution is evolving as a function of redshift, and that the young/old drifting model is a much better description of the data than any time-constant model

- [Model independent measurement of the growth rate from the consistency relations of the LSS](https://arxiv.org/abs/2005.09574)
  - **CSST**
  - We illustrate how BS and PS measurements can be used to extract bα and f without the need of any theoretical approximation scheme for the computation of the BS and the PS
  - Consistency Relations for LSS:建立了PS和squeezed BS的BAO幅度的关系，可以用于不依赖宇宙学模型地提取tracer的大尺度bias信息，以及结构growth rate信息

- [Broad-band X-ray observation of broad-line radio galaxy 3C 109](https://arxiv.org/abs/2005.09077)
  - X-ray谱分解成连续谱，中性和电离吸收，以及一个反射成分；主连续谱的光子指数有明显光变
  - We obtain a new black hole mass estimate of 9.3 ×10^8M⊙, which brings all Eddington ratio estimates into agreement and does not require 3C 109 to be super-Eddington.

- [Modelling and peeling extended sources with shapelets: a Fornax A case study](https://arxiv.org/abs/2005.09316)
  - 考虑EoR 21cm测量的前景扣除问题：Sources such as Fornax A present a modelling challenge due to spatial structures spanning from arc seconds up to a degr
  - We also introduce a new CUDA simulation code (WODEN) to generate point source, Gaussian, and shapelet components into visibilities

- [Simba: The average properties of the circumgalactic medium of 2≤z≤3 quasars are determined primarily by stellar feedback](https://arxiv.org/abs/2005.08971)
  - 看z>2处AGN feedback对CGM和IGM的影响： The observations are well reproduced, except within 100 kpc from the foreground quasar, where Simba overproduces absorption
  - 主要的影响还是来自stellar feedback而不是AGN feedback

- [Millisecond Pulsars Modify the Radio-SFR Correlation in Quiescent Galaxies](https://arxiv.org/abs/2005.08982)
  - LOFAR recently extended radio observations of the related correlation with star formation rate to lower frequencies (150~MHz), finding a peculiar radio excess in galaxies with high stellar masses and low star-formation rates.
  - We show that recycled/millisecond pulsars (MSPs) can dominate the non-thermal emission in these massive quiescent galaxies and explain the excess: MSP spin down损失的能量可以有效地转化为正负电子对

- [Completeness of the Gaia-verse II: what are the odds that a star is missing from Gaia DR2?](https://arxiv.org/abs/2005.08983)
  - **Useful**
  - We infer the completeness of Gaia DR2 by exploiting the fact that it only contains sources with at least five astrometric detections.
  - We fit both these models to the 1.7 billion stars of Gaia DR2, and thus are able to robustly predict the completeness of Gaia across the sky as a function of magnitude
  - We find that the magnitude limit at which Gaia is still 99% complete varies over the sky from G=18.9 to 21.3.

- [Diffuse LINER-type emission from extended disc regions of barred galaxies](https://arxiv.org/abs/2005.08985)
  - 48 SBa - SBcd的观测，中心有SF沙漠区域，但是依然有弥散电离发射。Favour post-Asymptotic Giant Branch (p-AGB) stars as the source of this line excitation, rather than extreme Blue Horizontal Branch stars.
  - The line equivalent widths are also larger than those observed in many fully passive (e.g. elliptical) galaxies, which may also be a consequence of a greater ambient gas density in the SFD regions.

- [SDSS-IV MaNGA: Spatially resolved star formation in barred galaxies](https://arxiv.org/abs/2005.08987)
  - MaNGA中的684 barred galaxies: we find that fractional (or scaled) bar length correlates with the host's offset from the star-formation main sequence.
  - We find that only low-mass galaxies host star formation along their bars, and that this is located predominantly at the leading edge of the bar itself
  - 星系棒内的SF位置由剪切力，湍动，和气体流向决定:the physical properties of a bar are mostly governed by the existing stellar mass of the host galaxy, but that they also play an important role in the galaxy's ongoing star formation.

- [Observing Correlations Between Dark Matter Accretion and Galaxy Growth: I. Recent Star Formation Activity in Isolated Milky Way-Mass Galaxies](https://arxiv.org/abs/2005.08995)
  - **Interesting**
  - We present a technique to observationally measure this correlation strength for isolated Milky Way-mass galaxies with z<0.123 基于DM吸积率和附近星系的密度轮廓的相关，和过去Splashback radius有联系
  - We find that positive correlations between dark matter accretion and recent star formation activity are ruled out with ≳85% confidence.
  - Our results suggest that star formation activity may not be correlated with fresh accretion for isolated Milky Way-mass galaxies at z=0 and that other processes, such as gas recycling, dominate further galaxy growth.

- [Gemini Multi-Object Spectrograph Integral Field Unit Spectroscopy of the Double-peaked Broad Emission Line of a Red Active Galactic Nucleus](https://arxiv.org/abs/2005.09014)
  - We confirm the existence of two BEL peaks that are kinematically separated by 3000,kms−1, with the SMBH of each BEL component weighing at 10^8.92±0.06M⊙ and 10^7.13±0.06M⊙
  - 两成分的间隔是0.085", 或250 pc. 但很不确定
  - Given the uncertainty regarding the spatial separation, various models, such as the disk emitter and multiple SMBH models, are viable solutions to explain the double BEL components

- [The local universe in the era of large surveys. I. Spectral classification of S0 galaxies](https://arxiv.org/abs/2005.09016)
  - This procedure has revealed that objects bearing the S0 designation consist, despite their similar morphology, of two separate sub-populations with statistically inconsistent physical properties.
  - Compared to the absorption-dominated S0, those with significant nebular emission are, on average, somewhat less massive, more luminous with less concentrated light profiles, have a younger, bluer and metal-poorer stellar component, and avoid high-galaxy-density regions.

- [Time-delay measurement of MgII broad line response for the highly-accreting quasar HE 0413-4031: Implications for the MgII-based radius-luminosity relation](https://arxiv.org/abs/2005.09071)
  - SALT 6年的观测：This time-delay is below the value expected from the standard radius-luminosity relation.
  - 时间延迟的变短可能来自高吸积率

- [A Universal fundamental plane and the Mdyn−M⋆ relation for galaxies with CALIFA and MaNGA](https://arxiv.org/abs/2005.09149)
  - **Relevant**
  - 定义S^2_K = K*V^2_Re + sigma^2_Re: We confirm that spheroidal and spiral galaxies follow the same M⋆−S0.5 scaling relation with lower scatter than the M⋆−VRe and M⋆−σ⋆e ones.
  - We use sophisticated Schwarzschild dynamical models for a sub-sample of 300 galaxies from the CALIFA survey to calibrate the so called Universal Fundamental Plane: log(Υe)=log(S20.5)−log(Ie)−log(Re)+C
  - We find that all classes of galaxies, from spheroids to disks, follow this Universal Fundamental Plane with a scatter significantly smaller (0.05 dex) than the one reported for the M⋆−S0.5 relation (0.1 dex)

- [Star formation in outer rings of S0 galaxies. III. UGC 5936 -- an S0 with currently accreted satellite matter](https://arxiv.org/abs/2005.09383)
  - The ionized gas of the ring is excited by young stars and has solar metallicity. Star formation in the ring is rather prolonged, and its intensity corresponds to the current HI content of UGC 5936 (to the Kennicutt-Schmidt relation).
  - The whole morphology of the HI distribution implies current accretion of the cold gas from the satellite onto the outer disc of UGC 5936; due to the satellite location and rotation in the plane of the stellar disc of the host galaxy, the accretion is smooth and laminar providing the favorable condition for star formation ignition.

- [A discrete chemo-dynamical model of M87's globular clusters: Kinematics extending to ~ 400 kpc](https://arxiv.org/abs/2005.09410)
  - **Relevant**
  - MUSE IFU观测中心2.4kpc内的恒星加上GC：Our catalogue comprises 894 globular clusters (GCs) extending to a projected radius of ∼430 kpc with line-of-sight velocities and colours
  - Varying M/L for the main galaxy -> 一个显著的效果是 1Re以内的DM比例从26%涨到了73%; 5Re以内从84%涨到了94%
  - 结果对DM halo是core还是cusp不敏感
  - Red (in-situ) v.s. Blue (ex-situ): Red GCs have moderate rotation with Vmax/σ∼ 0.4, and blue GCs have weak rotation with Vmax/σ∼ 0.1. Red GCs have tangential velocity dispersion anisotropy, while blue GCs are consistent with being nearly isotropic.

- [A New Metal-poor Globular Cluster and Resolved Stars in the Outer Disk of the Black Eye Galaxy M64: Implication for the Origin of the Type III Disk Break](https://arxiv.org/abs/2005.09633)
  - At r≈5.5′ (7 kpc) to the east, we discover a new metal-poor globular cluster (Reff=5.73±0.02 pc and MV=−9.54±0.09 mag), M64-GC1.
  - The CMD of the resolved stars in the entire ACS field shows two distinguishable red giant branches (RGBs): a curved metal-rich RGB and a vertical metal-poor RGB.
  - GC年老，贫金属，属于stellar halo；性质和metal poor星族类似
  - The radial number density profile of the metal-rich RGB stars is described by an exponential disk law, while the profile of the metal-poor RGB stars is described by a de Vaucouleurs's law

----

### May 21

- [Effective Opacity of the Intergalactic Medium from Galaxy Spectra Analysis](https://arxiv.org/abs/2005.09667)
  - Effective opacity (τeff) of the Intergalactic Medium (IGM) from the composite spectra of 281 Lyman-Break Galaxies (LBGs) in the redshift range 2≲z≲3
  - 对叠加光谱进行基于SSP的SED拟合之后外推到Lya森林区域:At z=2.22, we estimate τeff=0.159±0.001 from a power-law fit to the data.
  - 和QSO得到的结果类似

- [Impact of systematics on cosmological parameters from future Galaxy Clusters surveys](https://arxiv.org/abs/2005.10204)
  - **Relevant**
  - This higher accuracy exposes the impact of the mass function evaluation, which is a subdominant source of systematics for current data. For the ΛCDM model, we find a 1.6σ shift in the (Ωm,σ8) parameter plane and a discrepancy of ∼7σ for the redshift evolution of the scatter of the scaling relations.
  - These results show the impact, and the necessity for a precise modelling, of the interplay between the redshift evolution of the mass function and of the scaling relations in the cosmological analysis of galaxy clusters.

- [Studying Type II supernovae as cosmological standard candles using the Dark Energy Survey](https://arxiv.org/abs/2005.09757)
  - We present a sample from the Dark Energy Survey Supernova Program (DES-SN) consisting of 15 SNe II with photometric and spectroscopic information spanning a redshift range up to 0.35.
  - We construct the largest available Hubble diagram with SNe II in the Hubble flow (70 SNe II) and find an observed dispersion of 0.27 mag. 加入color项不能改进Hubble diagram的scatter
  - SNII作为距离指示还有很长的路：find new correlations, define a more standard subclass of SNe II, construct new SN II templates, and dedicate more observing time to high-redshift SNe II.

- [Detection of a variable ultra-fast outflow in the Narrow Line Seyfert 1 galaxy PG 1448+273](https://arxiv.org/abs/2005.09982)
  - The UFO spectral features are often weak due to high ionisation of the outflowing material, and the inference of the wind physical properties can be complicated by other spectral features in AGN such as relativistic reflection.
  - The UFO absorption is observed in both soft and hard X-ray bands with the XMM-Newton observatory. The velocity of the outflow is (26900 +- 600) km/s (~0.09c)
    - The UFO is not detected in a second, shorter observation with XMM-Newton, indicating variability in time, observed also in other similar AGN.
  - We detect weak warm absorption features in the spectrum of the object. Our systematic outflow search suggests the presence of further multi-phase wind structure, but we cannot claim a significant detection considering the present data quality

- [VLA-ALMA Spectroscopic Survey in the Hubble Ultra Deep Field (VLASPECS): Total Cold Gas Masses and CO Line Ratios for z=2-3 "Main Sequence" Galaxies](https://arxiv.org/abs/2005.09653)
  - Six detections of CO(J=1-0) emission and one upper limit in z=2-3 galaxies originally detected in higher-J CO emission in ALMA
  - 气体质量：M_gas = 2.4-11.6 x 10^10 (alpha_CO/3.6) Msun
  - CO(J=3-2) selected galaxies may have a higher CO line excitation on average than CO(J=1-0) selected galaxies, based on the limited, currently available samples
  - 之前基于CO(3-2)估计宇宙冷气体密度可能需要调低一倍左右

- [Resolving small-scale cold circumgalactic gas in TNG50](https://arxiv.org/abs/2005.09654)
  - **Relevant**
  - z=0.5的>10^11 Msun的大质量星系周围的CGm：a significant abundance of small-scale, cold gas structure in the CGM of 'red and dead' elliptical systems；主要是HI和MgII系统；数量很大，尺度可以在1kpc左右
  - 冷气体云团的形成源自于强烈密度扰动促进的热不稳定性；局域的过密度区域引起快速冷却：act as cosmologically long-lived, 'stimulated cooling' seeds in a regime where the global halo does not satisfy the classic cooling criteria
  - 而且，这些小团块是被磁场压力而不是热压力支撑的；with plasma beta << 1

- [High-redshift Damped Ly-alpha Absorbing Galaxy Model Reproducing the N(HI)-Z Distribution](https://arxiv.org/abs/2005.09660)
  - 模型描述高红移QSO光谱中的DLA和SF星系的关系：construct a model based on observed and physically motivated scaling relations in order to reproduce the bivariate distributions of metallicity, Z, and HI column density, N(HI).
  - The model strongly favours a metallicity gradient, which scales with the luminosity of the host galaxy
  - We find that DLAs trace galaxies over a wide range of galaxy luminosities, however, the bulk of the DLA cross-section arises in galaxies with L ~ 0.1 L* at z ~ 2.5

- [A Cold, Massive, Rotating Disk Galaxy 1.5 Billion Years after the Big Bang](https://arxiv.org/abs/2005.09661)
  - **Interesting**
  - We report imaging, with a resolution of about 1.3 kiloparsecs, of the 158-micrometre emission line from singly ionized carbon, the far-infrared dust continuum and the near-ultraviolet continuum emission from a galaxy at a redshift of 4.2603.
  - These observations show that the emission arises from gas inside a cold, dusty, rotating disk with a rotational velocity of 272 kilometres per second.

- [What has quenched the massive spiral galaxies?](https://arxiv.org/abs/2005.09663)
  - We report the identification of a rare population of very massive, quenched spiral galaxies with stellar mass ≳10^11 M⊙ and halo mass ≳10^13 M⊙ from the Sloan Digital Sky Survey at redshift z∼0.1
  - IRAM观测显示分子气体质量很少

- [SDSS-IV MaNGA: the role of bars in central star formation enhancements](https://arxiv.org/abs/2005.09853)
  - We identify 124 "turnover" galaxies that each have a central upturn in EW(Hα), EW(HδA) and/or a central drop in Dn(4000), indicative of ongoing/recent star formation.
  - 质量多在10^10 Msun以上: The majority of the turnover galaxies are barred, with a bar fraction of 87±3\%.
  - For barred galaxies the radius of the central turnover region (Rt) is found to tightly correlate with the bar length (Rbar):
  - Only half of the barred galaxies in our sample have a central turnover feature, implying that the presence of a bar is not sufficient to lead to a central SF enhancement.

- [The Three Hundred project: shapes and radial alignment of satellite, infalling, and backsplash galaxies](https://arxiv.org/abs/2005.09896)
  - **Relevant**
  - We find that radial alignment depends on distance to the centre of the galaxy cluster but appears independent of the dynamical state of the central host cluster.
  - We cannot find a relation between radial alignment of the halo or galaxy shape with its own mass

- [Predicted rates of merging neutron stars in galaxies](https://arxiv.org/abs/2005.10226)
  - 预测Kilonova rate：we take into account the production of r-process elements either by MNS or core-collapse supernovae.
  - The [Eu/Fe] vs. [Fe/H] relation in the Milky Way can be well reproduced with only MNS if the time delay is short and constant.
  - The spirals are the major contributors to the cosmic MNS at all redshifts in hierarchical scenarios.
  - Future observations of Kilonovae in ellipticals will allow to disentangle among constant or a distribution of time delays as well as among different cosmological scenarios.

----

### May 22

- [Beware of commonly used approximations I: errors in forecasts](https://arxiv.org/abs/2005.10384)
  - 宇宙学推断中，三个层面上的近似有可能产生问题：in the form of the likelihood, in the theoretical modelling of the observable and in the numerical computation of the observable.
  - 用星系角功率谱展示这一点：We show that there are cases where these commonly used approximations lead, perhaps counter-intuitively, to unacceptably large mis-estimates of parameters errors and correlations 可能会抵消使用multi-tracer的好处
  - we have developed MultiCLASS, a new extension of CLASS that includes the angular power spectrum for multiple (galaxy and other tracers such as gravitational waves) populations

- [Apparent Superluminality of Lensed Gravitational Waves](https://arxiv.org/abs/2005.10702)
  - If GWs have wavelengths comparable to the Schwarzschild radius of astrophysical lenses, they must be treated with wave optics, whereas EM waves are typically well within the approximation of geometric optics.
  - 如果同时发出，GW信号永远不会比EM对应先到达；during the inspiral of a binary, peaks of the GW waveform can arrive before their EM counterpart

- [Complete coordination of robotic fiber positioners for massive spectroscopic surveys](https://arxiv.org/abs/2005.10702)
  - **SSST**
  - We first define the local and the global completeness problems and determine their relationship. We then propose a new artificial potential field according to which the convergences of a positioner and its neighboring positioners are cooperatively taken into account

- [Optimal target assignment for massive spectroscopic surveys](https://arxiv.org/abs/2005.08853)
  - **SSST**
  - We establish an optimal target assignment scheme which simultaneously provides the fastest coordination accompanied with the minimum of colliding scenarios between robotic fiber positioners.
  - we propose a cost function by whose minimization both of the cited requirements are taken into account in the course of a target assignment process

- [Considerations for the Observability of Kinematically Offset Binary AGN](https://arxiv.org/abs/2005.10255)
  - 能否用binary AGN的BLR的发射线移动来找双AGN：There is a delicate trade-off between requiring binary separations to be large enough for BL regions to remain attached to one of the AGN, but also small enough such that their orbital velocity is detectable.
  - We find that kinematic signatures are only observable for the lower-mass secondary AGN, for binaries with total-masses above about 108M⊙, and separations between 0.1 and 1 pc.
  - 可能1万个AGN里才有一个，还需要更好地理解AGN BLR的本征光变特性：This requires multi-epoch spectroscopy of large populations of AGN over a variety of timescales. **SSST**

- [The Mergers in Abell 2256: Displaced Gas and its Connection to the Radio-emitting Plasma](https://arxiv.org/abs/2005.10263)
  - 射电结构丰富，被一个relic主导，X-ray观测看到三个子结构
  - The infalling gas is not co-spatial with bright galaxies and the radio loud brightest cluster galaxy of the infalling group appears dissociated from the low entropy plasma by 50 kpc in projection, to the south of the eastern edge of the cold front.
  - Part of the low frequency radio emission near the cold front might be revived by magnetic field amplification due to differential gas motions

- [Chandra Imaging of the Western Hotspot in the Radio Galaxy Pictor A: Image Deconvolution and Variability Analysis](https://arxiv.org/abs/2005.10350)
  - Pictor A是一个FR-II射电星系，hot spot是相对论性喷流与IGM相互作用的位置； forming a termination shock that converts jet bulk kinetic energy to internal energy of the plasma.
  - 热点在X-ray很亮是因为激波波前内的极端相对论性电子的同步加速辐射
  - The brightest segment of the X-ray hotspot is observed to be extended in the direction perpendicular to the jet, forming a thin, ∼3 kpc-long, feature that we identify with the front of the reverse shock.

- [Dynamical evolution of cosmic supermassive binary black holes and their gravitational wave radiation](https://arxiv.org/abs/2005.10818)
  - By combining these BBH evolution tracks, galaxy mass functions, galaxy merger rates, and supermassive black hole-host galaxy relations into our model, we obtain the statistical distributions of surviving BBHs, BBH coalescence rates, the strength of their GW radiation, and the stochastic GW background contributed by the cosmic BBH population.
  - 近邻星系中有1-3%的星系中心应该有binary SMBH with mass ratio >1
  - The application of the cosmic BBH population to the LISA band provides a lower limit to the detection rate of BBHs by LISA, ~0.9/yr.

- [A molecular absorption line survey toward the AGN of Hydra-A](https://arxiv.org/abs/2005.10252)
  - **Relevant**
  - ALMA观测，来自至少12个云团的多个分子发射线：have velocities of approximately −50 to +10 km s−1 relative to its recession velocity
  - A clumpy interstellar medium within brightest cluster galaxies 柱密度，速度弥散，激发温度和银河系内的类似
  - **nice figure**

- [Galactic inflow and wind recycling rates in the EAGLE simulations](https://arxiv.org/abs/2005.10262)
  - Galaxy-scale wind recycling is generally inefficient, with a characteristic return timescale that is comparable or longer than a Hubble time, and with an efficiency that clearly peaks at the characteristic halo mass of M200 = 10^12 M.
  - We are able to show that the fractional contribution of wind recycling to galaxy growth is smaller in EAGLE than in some other simulations.
  - We find that cumulative first-time gas accretion rates at the virial radius are reduced relative to the expectation from dark matter accretion for haloes with mass, M200 < 10^12 M

- [How primordial magnetic fields shrink galaxies](https://arxiv.org/abs/2005.10269)
  - 高分辨MHD模拟：vary the initial magnetic field strength and configuration along with the prescription for stellar feedback
  - 更强的原初磁场可以：1. 推迟SF的开始；2. 让星系逐渐失去rotational support；3. 减小星系的size；4. 驱动更多的气体流向星系中心。
  - The effects of primordial magnetic fields are amplified in the presence of stellar feedback

- [ALMA [CII] 158um imaging of an HI-Selected Major Merger at z~4](https://arxiv.org/abs/2005.10279)
  - Our ALMA images reveal a pair of star-forming galaxies separated by ~6kpc (projected) undergoing a major merger. Between these galaxies is a third emission component with highly elevated (2x) [CII] 158um emission relative to the dust continuum, which is likely to arise from stripped gas associated with the merger.
  - The DLA associated with the merger exhibits extreme kinematics, with a velocity width for the low-ionization metal lines of Dv90~470km/s that spans the velocity spread revealed in the [CII] 158um emission.
  - DLAs with high Dv90 values are a signpost of major mergers in normal galaxies at high redshifts

- [Wobbly discs -- corrugations seen in the dust lanes of edge-on galaxies](https://arxiv.org/abs/2005.10290)
  - corrugations: 褶皱; small scale bending waves
  - Because they are seen in absorption, this feature must be present in the dust disc in the outskirts of these galaxies.
  - The corrugation amplitude is found to be in the range of 70 - 200 pc and the wavelengths lie between 1 - 5 kpc.
  - The amplitude of the corrugations tends to be larger for lower mass galaxies

- [Internal kinematics of giant H II regions in M101 with the Keck Cosmic Web Imager](https://arxiv.org/abs/2005.10369)
  - 用Hbeta和[OIII]线轮廓分析找膨胀中的shell以及filaments的证据
  - The supersonic turbulence inferred from the global line profiles is consistent with the velocity dispersion of the individual narrow components; global轮廓是一群小的discrete clouds的贡献的加和
  - We argue that the resolution of this long-standing problem lies in the physics of the line-emitting gas rather than in the smearing effects induced by the different thermal widths.

----

### May 25

- [Chandra and XMM-Newton observations of A2256: cold fronts, merger shocks, and constraint on the IC emission](https://arxiv.org/abs/2005.10838)
  - The temperature and metallicity maps show clear evidence of a merger between the western subcluster and the primary cluster.
  - X-ray看到了各种面亮度edge：中心的cold front和边缘的shock front
  - We propose a merger scenario including a primary cluster, a subcluster, and a group

- [The Mean Absorption Line Spectra of a Selection of Luminous z~6 Lyman Break Galaxies](https://arxiv.org/abs/2005.11078)
  - We demonstrate the practicality of stacking our lower resolution data to measure the depth of various interstellar and stellar absorption lines to probe the covering fraction of low ionization gas and the gas-phase and stellar metallicities near the end of the era of cosmic reionization.
  - From maximum absorption line depths of SiII1260 and CII1334, we infer a mean covering fraction of >0.85 +/-0.16 for our sample.
  - Using various interstellar absorption lines we deduce gas-phase metallicities close to solar indicative of substantial early enrichment.

- [Galaxy And Mass Assembly (GAMA): Assimilation of KiDS into the GAMA database](https://arxiv.org/abs/2005.11215)
  - **Useful**
  - The source extraction and analysis is based on the new ProFound image analysis package, providing matched-segment photometry across all bands. The data are classified into stars, galaxies, artefacts, and ambiguous objects

----

### May 26

- [Chandra and XMM-Newton observations of A2256: cold fronts, merger shocks, and constraint on the IC emission](https://arxiv.org/abs/2005.10838)
  - **Relevant, Important**
  - CLASH+RELICS+HFF的BCG和halo的alignment，shape来自SL测量
  - DM halo结构比较elongated，平均椭率在0.5左右；且和BCG align得很好，alignment角度在~20度左右
  - We find that DM haloes in our sample are on average more elongated than their BCGs with the mean difference of their ellipticities of 0.11 ± 0.03. 但Horizon-AGN模拟里Halo和BCG shape则很一致

- [The Mass Accretion Rate of Clusters of Galaxies: CIRS and HeCS](https://arxiv.org/abs/2005.11562)
  - **Relevant, Important**
  - 基于模拟中训练出的方法估计观测的0.1< z <0.3的>10^14 Msun的星系团的MAR：Based on three-dimensional mass profiles of simulated clusters reaching beyond the virial radius, our recipe returns MARs that agree with MARs based on merger trees. 基于caustic的方法。
  - The median MARs based on the caustic mass profiles of the simulated clusters are unbiased and agree within 17% with the median MARs based on the real mass profile of the clusters.  
  - The MAR of the CIRS and HeCS clusters increases with the mass and the redshift of the accreting cluster, in excellent agreement with the growth of clusters in the ΛCDM model.

- [The cosmic web connection to the dark matter halo distribution through gravity](https://arxiv.org/abs/2005.11598)
  - We use the invariants of the tidal field tensor as generating functions (dubbed I-web), to reproduce the halo number counts of a reference catalog from full gravity calculations, populating the dark matter field on a mesh well into the non-linear regime 能得到比较真实的功率谱

- [Galaxy cluster mass estimation with deep learning and hydrodynamical simulations](https://arxiv.org/abs/2005.11819)
  - **Relevant**
  - BAHAMAS模拟：We train four separate single-channel networks using: stellar mass, soft X-ray flux, bolometric X-ray flux, and the Compton y parameter as observational tracers
  - The resulting predictions are especially precise for halo masses in the range 10^13.25M⊙ < M < 10^14.5M⊙ 基于SZ效应的最好
  - The CNN trained with stellar mass images detect galaxies (not surprisingly), while CNNs trained with gas-based tracers utilise the shape of the signal to estimate cluster mass.

- [On the road to per-cent accuracy IV: ReACT -- computing the non-linear power spectrum beyond ΛCDM](https://arxiv.org/abs/2005.12184)
  - We present the public software package ReACT, demonstrating its capability for the fast and accurate calculation of non-linear power spectra from non-standard physics.
  - Accurate non-linear modelling with ReACT more than doubles LSST's constraining power on the f(R) parameter, in contrast to an analysis that is limited to the quasi-linear regime.

- [Jet Properties of Compact Steep-Spectrum Sources and an Eddington-Ratio-Driven Unification Scheme of Jet Radiation in Active Galactic Nuclei](https://arxiv.org/abs/2005.11534)
  - 有Gamma ray探测的CSS射电源的喷流SED拟合：SED fits with a two-zone leptonic model for radiations from the compact core and large-scale extended region
  - 有些CSS的Gamma辐射有明显变化，来自：their compact cores via the inverse Compton process of the torus photons
  - The six CSSs on average have higher Eddington ratio and black hole mass than those non-GeV-detected CSSs, and they follow the correlation between the jet power in units of Eddington luminosity (P_jet/L_Edd) and Eddington ratio (R_Edd) with other sub-classes of AGNs

- [On the radial acceleration of disk galaxies](https://arxiv.org/abs/2005.11316)
  - Using published data of the galaxies NGC 3198, NGC 2403, NGC 1090, UGC 3205 and NGC 1705, it has been possible to find good fits without DM for the observed disk velocities and, as example, also for the extraplanar matter of NGC 3198.

- [PHANGS CO kinematics: disk orientations and rotation curves at 150 pc resolution](https://arxiv.org/abs/2005.11709)
  - 更好的拟合CO速度场的方法： identifies an optimal global orientation as a way to reduce the impact of non-axisymmetric (bar and spiral) features and the uneven spatial sampling characteristic of CO emission in the inner regions
  - We use the inner slope as well as the amplitude of our fitted rotation curves to demonstrate that CO is a reliable global dynamical mass tracer.
  - From the consistency between photometric orientations from the literature and kinematic orientations determined with our method, we infer that the shapes of stellar disks in the mass range of log(M⋆(M⊙))=9.0-10.9 probed by our sample are very close to circular and have uniform thickness.

- [A giant galaxy in the young Universe with a massive ring](https://arxiv.org/abs/2005.11880)
  - A detailed study of a ring galaxy at a look-back time of 10.8 Gyr (z=2.19).
  - Compared with our Milky Way, this galaxy has a similar stellar mass, but has a stellar half-light radius that is 1.5-2.2 times larger and is forming stars 50 times faster.
  - The large, diffuse stellar light outside the star-forming ring, combined with a radial velocity on the ring and an intruder galaxy nearby, provides evidence for this galaxy hosting a collisional ring. 
  - This work suggests that massive collisional rings were as rare 11 Gyr ago as they are today.

- [Galaxy And Mass Assembly (GAMA): A forensic SED reconstruction of the cosmic star-formation history and metallicity evolution by galaxy type](https://arxiv.org/abs/2005.11917)
  - **Relevant, Important**
  - ProSpect拟合7000个z<0.06的GAMA星系：parametric SFH+closed-box丰度演化模型
  - 能重构正确的CSFH模型： an indication that stars are being formed in the correct epoch of the Universe, on average, for the manner in which we are conducting SED fitting.
  - This analysis suggests that half of the mass in present-day elliptical galaxies was in place 11 Gyr ago, whereas in other morphological types the stellar mass formed later, up to 6 Gyr ago for present-day irregular galaxies

- [Cold molecular gas and PAH emission in Seyfert galaxies](https://arxiv.org/abs/2005.11959)
  - 看11.3 micron PAH是否trace冷分子气体
  - Galaxies with a nuclear detection of the 11.3μm PAH feature contain more cold molecular gas 柱密度也更高; 说明分子气体起到了保护PAH的作用
  - The Spitzer/IRS PAH ratios on circumnuclear scales (∼ 4" ∼ 0.25-1.3kpc) are in between model predictions for neutral and partly ionized PAHs.

- [Measuring the local dark matter density with LAMOST DR5 and Gaia DR2](https://arxiv.org/abs/2005.12018)
  - vertical Jeans equation分析：The mass models applied consist of a single exponential stellar disc, a razor thin gas disc and a constant dark matter density.
  - The local dark matter densities for subsamples in an azimuthal angle range of −10∘<ϕ<5∘ are consistent within their 1σ errors. However, the northern and southern subsamples show a large discrepancy due to plateaux in the northern and southern vertical velocity dispersion profiles
  - Taking the tilt term into account has little effect on the parameter estimations and does not explain the north and south asymmetry

- [The Fornax Deep Survey with VST. X. The catalog of sources in the FDS area, with an example study for globular clusters and background galaxies](https://arxiv.org/abs/2005.12085)
  - **Relevant**
  - 21.7 deg^2的巡天：catalogs of compact stellar systems in the Fornax cluster as well as extended background sources and point-like sources.
  - We observe the inter-galactic population of GCs, a population of mainly blue GCs centered on NGC1399, extends over ∼0.9Mpc, with an ellipticity ∼0.65.
  - Using the gri catalogs we analyze the GC distribution over the extended FDS area, and do not find any obvious GC sub-structure bridging the two brightest cluster galaxies, NGC1316 and NGC1399.