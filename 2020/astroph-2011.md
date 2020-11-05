# Astro-ph Notes

---- Song Huang ----

## 2020-November

----

### Nov 1

- [𝚍𝚎𝚎𝚙𝟸𝟷: a Deep Learning Method for 21cm Foreground Removal](https://arxiv.org/abs/2010.15843)
    - We demonstrate that a deep convolutional neural network (CNN) with a UNet architecture and three-dimensional convolutions, trained on simulated observations, can effectively separate frequency and spatial patterns of the cosmic neutral hydrogen (HI) signal from foregrounds in the presence of noise.
    - Our approach demonstrates the feasibility of analyzing 21cm intensity maps, as opposed to derived summary statistics, for upcoming radio experiments, as long as the simulated foreground model is sufficiently realistic.

- [Gaussian Process Foreground Subtraction and Power Spectrum Estimation for 21 cm Cosmology](https://arxiv.org/abs/2010.15892)
    - Recent works have claimed that Gaussian process regression (GPR) can robustly perform this separation, particularly at low Fourier k wavenumbers where the signal reaches its peak signal-to-noise ratio
    - We revisit this topic by casting GPR foreground subtraction (GPR-FS) into the quadratic estimator formalism, thereby putting its statistical properties on stronger theoretical footing. We find that GPR-FS can distort the window functions at these low k modes, which, without proper decorrelation, make it difficult to probe the EoR power spectrum.

- [Data Compression and Covariance Matrix Inspection: Cosmic Shear](https://arxiv.org/abs/2010.15986)
    - We investigate various compression mechanisms capable of vastly reducing the size of the covariance matrix in the context of cosmic shear statistics.
    - Massively Optimized Parameter Estimation and Data compression (MOPED) - only MOPED was able to replicate the original constraints in the 16-parameter space.
    - We apply a tolerance test to the elements of the compressed covariance matrix obtained with MOPED and confirm that the IA parameter A_IA is the most susceptible to inaccuracies in the covariance matrix.

- [Improving models of the cosmic infrared background using CMB lensing mass maps](https://arxiv.org/abs/2010.16405)
    - In measurements of the millimeter sky at frequencies higher than ∼300 GHz, the CIB and thermal emission from Galactic dust dominate. A limited understanding of the CIB contribution at lower frequencies on the other hand can hinder efforts to measure the kinetic Sunyaev-Zeldovich spectrum on small scales as well as new physics that affects the damping tail of the cosmic microwave background (CMB).
    - We show how significant improvements (20-100%) can be obtained on parameters of star formation models by cross-correlating the CIB (as measured from existing {\it Planck} maps or upcoming CCAT-prime maps) with upcoming mass maps inferred from gravitational lensing of the CMB.

- [The Evolution of Gas-Phase Metallicity and Resolved Abundances in Star-forming Galaxies at z≈0.6−1.8](https://arxiv.org/abs/2010.15847)
    - We define the stellar mass-metallicity relation at z≈0.6−1.0 and z≈1.2−1.8 and analyse the correlation between the scatter in the relation and fundamental galaxy properties
    - We find that for a given stellar mass, more highly star-forming, larger and irregular galaxies have lower gas-phase metallicities, which may be attributable to their lower surface mass densities and the higher gas fractions of irregular systems
    - A median, beam smearing-corrected, metallicity gradient of ΔZ/ΔR=0.002±0.004 dex kpc−1, indicating on average there is no significant dependence on radius.
    - [KMOS Galaxy Evolution Survey (KGES)](http://astro.dur.ac.uk/kmos/kges/)

- [BAT AGN Spectroscopic Survey-XX: Molecular Gas in Nearby Hard X-ray Selected AGN Galaxies](https://arxiv.org/abs/2010.15849)
    - We find that AGN in massive galaxies tend to have more molecular gas, and higher gas fractions, than inactive galaxies matched in stellar mass.
    - When matched in star formation, we find AGN galaxies show no difference from inactive galaxies with no evidence of AGN feedback affecting the molecular gas.
    - The likelihood of a given galaxy hosting an AGN (L_bol>10^44 erg/s) increases by ~10-100 between a molecular gas mass of 10^8.7 Msun and 10^10.2 Msun.
    - Higher Eddington ratio AGN galaxies tend to have higher molecular gas masses and gas fractions.

- [Connecting cosmological accretion to strong Lyman-alpha absorbers](https://arxiv.org/abs/2010.15857)
    - Performing simplified radiative transfer, we compute how the accreting gas turns increasingly neutral as it self-shields from the ionising background, and obtain the column density, NHI, as a function of impact parameter.
    - 关注点是柱密度分布函数,CDDF: The analytical expression elucidates (1) why halos over a large range in mass contribute about equally to the CDDF as well as (2) why the CDDF evolves so little with redshift in the range z=2→5.
    - CDDF的积分可以给出中性气体质量密度：ΩHI(z)  is nearly constant even though the accretion rate onto halos evolves. We show that this occurs because the fraction of time that the inflowing gas is neutral depends on the dynamical time of the halo, which is inversely proportional to the accretion rate.
    - 绝大多数的LLS和DLA都是正在吸积的气体：Most Lyman-limit system and damped Lyman-alpha absorbers are associated with the cosmological accretion of gas onto halos.

- [Galactic merger implications for eccentric nuclear disks: a mechanism for disk alignment](https://arxiv.org/abs/2010.15957)
    - 以M31中的nuclear disk为背景，看星系并合后，可能的second SMBH对盘的影响：We perform N-body simulations to study the disk under a range of different possible SMBH initial conditions. A second SMBH in the disk always disrupts it, but more distant SMBHs can shut off differential precession and stabilize the disk. This results in a more aligned disk, nearly uniform eccentricity profile, and suppression of tidal disruption events compared to the isolated disk.

- [The stellar mass function and evolution of the density profile of galaxy clusters from the Hydrangea simulations at 0<z<1.5](https://arxiv.org/abs/2010.16195)
    - **Relevant**
    - 24 massive galaxy clusters (>10^14M⊙ at z=0); 模拟中在z>1处有过多的<10^10 Msun星系
    - The NFW concentrations of cluster galaxies increase with redshift, in contrast to the decreasing dark matter halo concentrations
    - Quantitatively, we however find a discrepancy in that the simulations predict higher stellar concentrations than observed at lower redshifts (z<0.3), by a factor of ≈2.

- [Turbulent Gas in Lensed Planck-selected Starbursts at redshifts 1-3.5](https://arxiv.org/abs/2010.16231)
    - 关于高红移富气体星暴星系中ISM的激发状态：We analyze 162 CO rotational transitions (ranging from Jupper = 1 - 12) and 37 atomic carbon fine-structure lines ([CI]) in order to characterize the physical conditions of the gas in sample of LPs.
    - 用两个模型同时拟合CO+CI+连续谱：第一个模型是个双成分气体模型; The first model represents a two component gas density, while the second assumes a turbulence driven log-normal gas density distribution.
    - 模型描述了这些星系中湍动气体的性质：well-characterized by a high turbulent velocity dispersion (<ΔVturb>∼100 \kms) and gas kinetic temperature to dust temperature ratios <Tkin/Td>∼2.5, sustained on scales larger than a few kpc.

- [The effects of star formation history in the SFR-M relation of HII galaxies](https://arxiv.org/abs/2010.16296)
    - 看对HII星系，星暴矮星系等星系进行SED拟合时，假定不同SFH模型的影响
    - We modeled and fitted the SEDs with the code CIGALE adopting different descriptions of SFH. By adding information from different independent studies we find that HII galaxies are best described by episodic SFHs including an old (10 Gyr), an intermediate age (100-1000 Myr) and a recent population with ages < 10 Myr.
    - 在一定时标内平均的SFR上，矮星系也在M*-SFR的主序上；只有在使用当前SFR时才常位于这个关系的上方

----

### Nov 2

- [Quantifying the impact of baryon-CDM perturbations on halo clustering and baryon fraction](https://arxiv.org/abs/2010.01037)
    - Baryons and cold dark matter (CDM) did not comove prior to recombination. This leads to differences in the local baryon and CDM densities, the so-called baryon-CDM isocurvature perturbations δbc. 通常在LSS分析中被忽略
    - We further measure the cross-power spectrum between the halo field and δbc over a wide range of mass. This cross-correlation is nonzero and negative which shows that halo formation is impacted by δbc
    - This effect can be degenerate with the one of massive neutrinos for surveys like DESI.

- [SNEWS 2.0: A Next-Generation SuperNova Early Warning System for Multi-messenger Astronomy](https://arxiv.org/abs/2010.00035)
    - 和中微子探测器联动的早期预警设备; 包括了大亚湾的中微子实验

- [Radio Monitoring of the Tidal Disruption Event Swift J164449.3+573451. IV. Continued Fading and Non-Relativistic Expansion](https://arxiv.org/abs/2010.00074)
    - 9.4年的VLA和Chandra监测；We find that the X-ray emission has faded below detectable levels；while the radio emission continues to be detected and steadily fade.
    - Both are consistent with forward shock emission from a non-relativistic outflow, although we find that the radio spectral energy distribution is better fit at these late times with an electron power law index of p≈3 (as opposed to p≈2.5 at earlier times).
    - The energy scale of the blastwave is ≈1052 erg.

- [The scaling relations and clustering properties of central and satellite galaxies](https://arxiv.org/abs/2010.00014)
    - **Relevant**
    - While central and satellite galaxies display similar stellar mass - size relations, their halo mass - size relations differ significantly.
    - More massive haloes tend to host larger central galaxies. However, the size of satellite galaxies depends only slightly on halo virial mass.
    - We show that these results are compatible with a remarkably simple model in which the size of central and satellite galaxies scales as the cubic root of their host halo mass, with the normalization for satellites being ∼30 % smaller than that for central galaxies which can be attributed to tidal stripping.

- [A disk-dominated and clumpy circumgalactic medium of the Milky Way seen in X-ray emission](https://arxiv.org/abs/2010.00126)
    - **Interesting**
    - 基于HaloSat Cubesat的巡天：we report a survey of the southern Galactic sky with a soft X-ray spectrometer optimized to study diffuse soft X-ray emission. The X-ray emission is best fit with a disc-like model based on the radial profile of the surface density of molecular hydrogen, a tracer of star formation, suggesting that the X-ray emission is predominantly from hot plasma produced via stellar feedback.
    - Strong variations in the X-ray emission on angular scales of ∼10∘ indicate that the CGM is clumpy.

- [A proto-pseudobulge in ESO 320-G030 fed by a massive molecular inflow driven by a nuclear bar](https://arxiv.org/abs/2010.00347)
    - ALMA+Herschel H2O观测：Radiative transfer models indicate that 3 nuclear components are required to account for the H2O and continuum data. An envelope, a nuclear disk, and an extremely compact, warm, buried core component.
    - The nucleus is fed by a molecular inflow observed in CO 2-1 with ALMA, which is associated with the nuclear bar.
    - At lower r, the inflow is best probed by the far-infrared OH ground-state doublets, with an estimated inflow rate of ~30 Msun yr^{-1}. The short timescale of ~20 Myr for nuclear gas replenishment indicates quick secular evolution, and indicates that we are witnessing an intermediate stage (<100 Myr) proto-pseudobulge fed by a massive inflow that is driven by a strong nuclear bar.

- [A Method to Extract Spatially Resolved Polycyclic Aromatic Hydrocarbon Emission from Spitzer Spectra: Application to M51](https://arxiv.org/abs/2010.00405)
    - **Interesting**
    - We present a new approach of analyzing the spatial elements of the spectral datacube that simultaneously maximizes spatial resolution and spatial coverage, while yielding reliable measurements of the total, integrated 5−20μm PAH emission
    - We find that in M51 the PAH emission correlates tightly with the extinction-corrected far-ultraviolet, near-ultraviolet, and Hα emission, from scales∼0.4 kpc close to the nucleus to 6 kpc out in the disk of the galaxy, indicating that PAH serves as an excellent tracer of SFR over a wide range of galactic environments.
    - The spiral arms and the central star-forming region of the galaxy emit stronger 7.7 and 8.6 μm PAH features than the inter-arm regions.

- [A kpc-scale resolved study of unobscured and obscured star-formation activity in normal galaxies at z = 1.5 and 2.2 from ALMA and HiZELS](https://arxiv.org/abs/2010.00686)
    - ALMA连续谱观测：Four galaxies in our sample are detected at high significance by ALMA at a resolution of 0.25'' at rest-frame 355 μm.
    - We find that ALMA detection rates are higher for more massive galaxies (M∗>10^10.5 M⊙) and higher [Nii]/Hα ratios
    - The dust extends out to a radius of 8 kpc, with a smooth structure, even for those galaxies presenting clumpy Hα morphologies.

- [UV and NIR size of the HI selected low surface brightness galaxies](https://arxiv.org/abs/2010.00688)
    - **Relevant**
    - We select a sample of 381 HI bright LSBGs with both Far Ultraviolet (FUV) and Near Infrared (NIR) observation to investigate the star formation rate (SFR): most of the HI selected LSBGs have extended star formation structure.
    - The stellar mass distribution of LSBGs may have a similar structure as the disk galaxies at the same stellar mass bins, while the star-forming activity of LSBGs happens at a larger radius than the high surface density galaxies, which may help to select the LSBG sample from the wide-field deep u band image survey.
    - HI radius比UV radius大3倍左右

- [A population of galaxy-scale jets discovered using LOFAR](https://arxiv.org/abs/2010.01015)
    - **Interesting**
    - LoTSS研究低光度射电噪AGN的feedback：report on our discovery of a population of 195 radio galaxies and total radio emission no larger than 80 kpc.
    - 大部分host都是椭圆星系，但也有~9%是旋涡星系：Two of the spiral-hosted GSJ are highly unusual with low radio luminosities and FRII-like morphology
    - 大都是年轻的jet: The host properties of our GSJ show that they are ordinary AGN observed at a stage in their life shortly after the radio emission has expanded beyond the central regions of the host.
    - 能量可以影响星系整体的ISM性质：we find that about half of our GSJ have internal radio lobe energy within an order of magnitude of the ISM energy so that, even ignoring any possible shocks, GSJ are energetically capable of affecting the evolution of the host.
    - [`pysynch`: Python interface to synchrotron libraries](https://github.com/mhardcastle/pysynch)

- [Discovery of a new extreme changing-state quasar with 4 mag variation, SDSS J125809.31+351943.0](https://arxiv.org/abs/2010.01127)
    - SDSS J125809.31+351943.0 (J1258), which brightened in optical for 4 mag from 1983 to 2015, which is one of the largest quasar brightening events so far.
    - The results show that the continuum flux and the BEL flux decreased to about 50 % of its peak. This indicates that J1258 is causing two changing-states for the BEL flux and continuum flux.
    - We argue that J1258's variability, especially its brightening event, can be explained by the propagation of the heating front and the accretion disk state transitions based on the timescale and Eddington ratio variations.

----

### Nov 3

- [Constraining the Halo Mass of Damped Lyα Absorption Systems (DLAs) at z=2−3.5 using the Quasar-CMB Lensing Cross-correlation](https://arxiv.org/abs/2010.01234)
    - We study the cross correlation of damped Lyα systems (DLAs) and their background quasars, using the most updated DLA catalog and the Planck 2018 CMB lensing convergence field.
    - DLA bias bDLA is smaller than 3.1, corresponding to log(M/M⊙h−1)≤12.3 at a confidence of 90%.

- [Comparing Foreground Removal Techniques for Recovery of the LOFAR-EoR 21cm Power Spectrum](https://arxiv.org/abs/2010.01284)
    -

- [Cosmological consequences of intrinsic alignments super-sample covariance](https://arxiv.org/abs/2010.01284)

- [Fast magnetic field amplification in distant galaxy clusters](https://arxiv.org/abs/2010.01628)

- [Two-point statistics without bins: A continuous-function generalization of the correlation function estimator for large-scale structure](https://arxiv.org/abs/2010.01836)

- [Massive black hole binary systems and the NANOGrav 12.5 year results](https://arxiv.org/abs/2010.01246)

- [Fast radio bursts: do repeaters and non-repeaters originate in statistically similar ensembles](https://arxiv.org/abs/2010.01339)

- [Discovery of a Fast Iron Low-ionization Outflow in the Early Evolution of the Nearby Tidal Disruption Event AT2019qiz](https://arxiv.org/abs/2010.01593)

- [A low-frequency radio halo survey of the South Pole Telescope SZ-selected clusters with the GMRT](https://arxiv.org/abs/2010.01593)

- [Evolution of the chemical enrichment and the Mass-Metallicity relation in CALIFA galaxies](https://arxiv.org/abs/2010.01229)

- [Investigating Clumpy Galaxies in SDSS Stripe82 using Galaxy Zoo](https://arxiv.org/abs/2010.01232)

- [The Elephant in the Bathtub: when the physics of star formation regulate the baryon cycle of galaxies](https://arxiv.org/abs/2010.01235)

- [Observational insights on the origin of giant low surface brightness galaxies](https://arxiv.org/abs/2010.01238)

- [Highly turbulent gas on GMC-scales in NGC 3256, the nearest luminous infrared galaxy](https://arxiv.org/abs/2010.01250)

- [ALMA Resolves Giant Molecular Clouds in a Tidal Dwarf Galaxy](https://arxiv.org/abs/2010.01287)

- [Predicting Primordial Star Formation with Deep Convolutional Neural Networks](https://arxiv.org/abs/2010.01358)

- [Environmental processing of galaxies in HI-rich groups](https://arxiv.org/abs/2010.01438)

----

### Nov 4

- [Reconciling galaxy cluster shapes, measured by theorists vs observers](https://arxiv.org/abs/2010.01945)
    - **Relevant**
    - 用BAHAMAS模拟看cluster的X-ray，强引力透镜，弱引力透镜mock观测，看cluster shape
    - 和模拟里常用的moments of inertia比较：Even when moments of inertia are projected into 2D and evaluated at matched radius, they overestimate ellipticity by 56% (compared to observable strong lensing) and 43% (compared to observable weak lensing).
    - In real clusters, the ellipticity and orientation angle at all radii are strongly correlated. In simulated clusters, the ellipticity of inner (< rvir/20) regions becomes decoupled: for example with greater misalignment of the central cluster galaxy. This may indicate overly efficient implementation of feedback from active galactic nuclei.

- [ForSE: a GAN based algorithm for extending CMB foreground models to sub-degree angular scales](https://arxiv.org/abs/2010.02221)
    - ForSE exploits the ability of generative adversarial neural networks (GANs) to learn and reproduce complex features present in a set of images, with the goal of simulating realistic and non-Gaussian foreground radiation at sub-degree angular scales.
    - Our results show how ForSE is able to generate small scale features (at 12 arc-minutes) having as input the large scale ones (80 arc-minutes). The injected structures have statistical properties, evaluated by means of the Minkowski functionals, in good agreement with those of the real sky and which show the correct amplitude scaling as a function of the angular dimension.

- [On the halo-mass and radial scale dependence of the lensing is low effect](https://arxiv.org/abs/2010.02377)
    - **Relevant**
    - 还是关于Lensing-is-low的结果：We present new measurements and modelling of galaxies in the BOSS LOWZ sample. We focus on the radial and stellar mass dependence of the lensing amplitude mis-match. We find an amplitude mis-match of around 35% when assuming ΛCDM with Planck Cosmological Microwave Background (CMB) constraints.
    - The observation that the offset is both mass and scale independent places important constraints on the degree to which astrophysical processes (baryonic effects, assembly bias) can fully explain the effect.
    - This scale independence also suggests that the "lensing is low" effect on small and large radial scales probably have the same physical origin. Resolutions based on new physics require a nearly uniform suppression, relative to ΛCDM predictions, of the amplitude of matter fluctuations on these scales.

- [LOFAR observations of galaxy clusters in HETDEX](https://arxiv.org/abs/2010.02387)
    - We characterize the presence of diffuse radio emission in known galaxy clusters in the HETDEX Spring Field, covering 424 deg
    - The fraction of Planck PSZ2 clusters with any diffuse radio emission apparently associated with the ICM is 73±17%.
    - We detect a total of 10 radio halos and 12 candidate halos in the HETDEX Spring Field. Five clusters host radio relics. The fraction of radio halos in Planck PSZ2 clusters is 31±11%, and 62±15% when including the candidate radio halos.

- [CMB lensing power spectrum estimation without instrument noise bias](https://arxiv.org/abs/2010.02475)
    - Measuring the lensing power spectrum involves the estimation of the connected trispectrum of the four-point function of the CMB map, which requires the subtraction of a large Gaussian disconnected noise bias
    - We propose a new estimator that makes use of at least four splits of the CMB maps with independent instrument noise. This estimator makes the CMB lensing power spectrum completely insensitive to any assumptions made in modeling or simulating the instrument noise.

- [Atomic data for the Gaia-ESO Survey](https://arxiv.org/abs/2010.02049)
    - **Useful, SSST**
    - We present an unprecedented effort to create a homogeneous line list, which was used by several abundance analysis groups to calculate synthetic spectra and equivalent widths.
    - Desirable improvements in atomic data were identified for a number of species, including Al I, S I, Cr II, Na I, Si I, Ca II, and Ni I.

- [Magnetic flux inversion in a peculiar changing look AGN](https://arxiv.org/abs/2010.01954)
    - We argue that the changing-look event in the active galactic nucleus 1ES 1927+654, followed by a dip of 3 orders of magnitude in the X-ray luminosity, is controlled by a change in the accretion rate and an inversion of magnetic flux in a magnetically arrested disk (MAD).
    - Before the changing-look event, strong magnetic flux on the black hole powers X-ray emission via the Blandford-Znajek process while the UV emission is produced by a radiatively inefficient magnetized disk. An advection event, bringing flux of the opposite polarity, propagates inward leading, first, to a rise in the UV/optical luminosity and, then, to a dip in the X-ray luminosity when it reaches the black hole.
    - Although flux inversion events might be rare due to the large ratio of flux-to-mass that is needed, we argue that AGN showing an unusually high ratio of X-ray to UV luminosity are prime candidates for such events

- [Dynamical structure of highly eccentric discs with applications to tidal disruption events](https://arxiv.org/abs/2010.02219)
    - 关于TDE事件中的吸积过程：highly eccentric disc must have a strong, non-hydrostatic variation of the disc scale height around each orbit.
    - We study the variation of physical quantities around each elliptical orbit, taking into account the dynamical vertical structure, as well as viscous dissipation and radiative cooling
    - We find that J074749+115352, with a SMBH mass of MSMBH≈1.8×10^9 M⊙ and an Eddington ratio of λEdd≈2.3, is extraordinarily X-ray bright.
    - We find evidence for the existence of the thermal instability in highly eccentric discs dominated by radiation pressure

- [Chandra Detection of Three X-ray Bright Quasars at z>5](https://arxiv.org/abs/2010.02358)
    - 观测三个高红移QSO，信噪比可以单独抽谱
    - J074749+115352 at z=5.26 is the X-ray brightest radio-quiet quasar at z>5. It may have a short timescale variation (on a timescale of ∼3800 s in the observer's frame, or ∼600 s in the rest frame) which is however largely embedded in the statistical noise.
    - We compare Γ of the three quasars to other samples at different redshifts, and do not find any significant redshift evolution based on the limited sample of z>5 quasars with reliable measurements of the X-ray spectral properties.

- [Hot and counter-rotating star-forming disk galaxies in IllustrisTNG and their real-world counterparts](https://arxiv.org/abs/2010.01949)
    - 研究低质量星系中的hot stellar disk结构：We find that being dynamically hot arises in most cases as an induced transient state, for example due to galaxy interactions and merger activities, rather than as an age-dependent evolutionary phase of star-forming disk galaxies.
    - Kinematically misaligned gas and stellar disks, and centrally concentrated on-going star formation 是常见特征
    - Observed galaxies from MaNGA with kinematic misalignment between gas and stars show remarkably similar general properties as the IllustrisTNG galaxies, and therefore are plausible real-world counterparts

- [Quasi-equilibrium models of high-redshift disc galaxy evolution](https://arxiv.org/abs/2010.01966)
    - We introduce a set of galaxy models that are based on a simple physical framework but incorporate more sophisticated models of feedback, star formation, and other processes
    - 能重现一些empirical模型的预研：the stellar mass--halo mass relation depends almost entirely on the physics of feedback (and is thus independent of the details of small-scale star formation) and the specific star formation rate is a simple multiple of the cosmological accretion rate.
    - The galaxy's gas mass is sensitive to the physics of star formation, although the inclusion of feedback-driven star formation laws significantly changes the naive expectations.

- [High-resolution imaging follow-up of doubly imaged quasars](https://arxiv.org/abs/2010.01971)
    - NIRC2确认观测：Out of these 57 candidates, 15 are confirmed as lenses. We form a sample of 20 lenses adding in a number of previously-known lenses
    - We compare the departure of the observed flux ratios from the smooth-model predictions between doubly and quadruply imaged quasar systems. We find that the departure is consistent between these two types of lenses if the modelling uncertainty is comparable.

- [The black hole mass of the z=2.805 multiply imaged quasar SDSS J2222+2745 from velocity-resolved time lags of the CIV emission line](https://arxiv.org/abs/2010.02007)
    - Reverberation mapping分析：黑洞质量10^8.63 Msun

- [The Accreted Nuclear Clusters of the Milky Way](https://arxiv.org/abs/2010.02042)
    - We combine a number of independent constraints, focusing on their internal abundances and overall kinematics, to find NSCs accreted by the Galaxy and trace them to their accretion event.
    - We find that the true NSCs accreted by the Galaxy are: M54 from the Sagittarius Dwarf, ω Centari from Gaia-Enceladus/Sausage, NGC 6273 from Kraken and (potentially) NGC 6934 from the Helmi Streams.
    - No NSC appears to be associated with Sequoia or other minor accretion events. Other claimed NSCs are shown not to be such. We also discuss the peculiar case of Terzan 5, which may represent a unique case of a cluster-cluster merger.
