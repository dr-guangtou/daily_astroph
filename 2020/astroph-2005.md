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