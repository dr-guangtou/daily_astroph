# Astro-ph Notes

---- Song Huang ----

## 2020-June

----

### June 2

- [Joint cosmology and mass calibration from tSZ cluster counts and cosmic shear](https://arxiv.org/abs/2006.00008)
    - **Relevant**
    - We combine cluster counts with the spherical harmonic cosmic shear power spectrum and the cross-correlation between cluster overdensity and cosmic shear.
    - Forecasting constraints on cosmological and mass calibration parameters for a combination of LSST cosmic shear and Simons Observatory tSZ cluster counts, we find competitive constraints for cluster cosmology, with a factor two improvement in the dark energy figure of merit compared to LSST cosmic shear alone.
    - We find most of the mass calibration information will be in the large and intermediate scales of the cross-correlation between cluster overdensity and cosmic shear.

- [OzDES multi-object fibre spectroscopy for the Dark Energy Survey: Results and second data release](https://arxiv.org/abs/2006.00449)
    - **Relevant, SSST**
    - 2dF AAT巡天：monitored 771 AGN, classified hundreds of supernovae, and obtained redshifts for thousands of galaxies that hosted a transient within the 10 deep fields of the Dark Energy Survey
    - 30,000 sources, some as faint as rAB=24 mag, and 375,000 individual spectra
    - OzDES is a template for future surveys that combine simultaneous monitoring of targets with wide-field imaging cameras and wide-field multi-object spectrographs

- [Building a digital twin of a luminous red galaxy spectroscopic survey: galaxy properties and clustering covariance](https://arxiv.org/abs/2006.00612)
    - **Relevant, SSST**
    - 结合Galform模型和Parallel-PM生成的halo catalog去：make clustering predictions on scales that cannot be modelled in the original N-body simulation
    - We find that the LRG-halo connection is non-trivial, leading to the prediction of a non-standard halo occupation distribution; in particular, the occupation of central galaxies does not reach unity for the most massive haloes, and drops with increasing mass.
    - We use the \glam{} mocks to compute the covariance matrices for the two-point correlation function and power spectrum of the LRGs and their background dark matter density field, revealing important differences. 给出了一个对应DESI的mock表格

- [Fully probabilistic quasar continua predictions near Lyman-α with conditional neural spline flows](https://arxiv.org/abs/2006.00615)
    - **Interesting, Useful**
    - we introduce a fully probabilistic approach to intrinsic continua prediction. We frame the problem as a conditional density estimation task and explicitly model the distribution over plausible blue-side continua (1190 Å≤λrest<1290 Å) conditional on the red-side spectrum (1290 Å≤λrest<2900 Å) using normalizing flows.
    - Normalizing flows: Normalizing flows model complex probability densities by mapping samples between a base density and the distribution of interest, i.e. the data distribution. The transformation, T, is composed of a series of invertible mappings Ti , or bijections, each of which must be differentiable
    - QSmooth: https://github.com/DominikaDu/QSmooth
    - Spectre: 本文的代码：https://github.com/davidreiman/spectre

- [ASASSN-15lh: a TDE about a maximally rotating 109M⊙ black hole](https://arxiv.org/abs/2006.00803)
    - 一个极为明亮的暂现天体的多波段光变曲线拟合：Good fits to all nine light curves are simultaneously obtained when Macc≃0.07M⊙ is accreted onto a black hole of mass M≃109M⊙, and near maximal rotation a/rg=0.99.
    - If confirmed, our results represent the detection of one of the most massive rapidly spinning black holes to date, and are strong evidence for a TDE origin for ASASSN-15lh

- [The post-maximum behaviour of the changing-look Seyfert galaxy NGC 1566](https://arxiv.org/abs/2006.00001)
    - We observed three significant re-brightenings in the post-maximum period
    - An X-ray flux minimum occurred in Mar. 2019. The UV minimum occurred about 3 months later.
    - Effectively, two CL states were observed for this object: changing to type 1.2 and then returning to the low state as a type 1.8 Sy.

- [Kinematics of the Circumgalactic Medium of a z=0.77 Galaxy from MgII Tomography](https://arxiv.org/abs/2006.00006)
    - **Interesting**
    - Using background lensed arcs from the CSWA 38 lens system, we continuously probed, at a resolution element of about 15 kpc2, the spatial and kinematic distribution of MgII absorption in a star-forming galaxy at z=0.77
    - Present an anisotropic, optically thick medium whose absorption strength decreases with increasing impact parameter, in agreement with the statistics towards quasars and other gravitational arcs
    - MgII气体LOS速度小，速度弥散度较高；可能不是外流

- [UV Spectral-Slopes at z=6−9 in the Hubble Frontier Fields: Lack of Evidence for Unusual or Pop III Stellar Populations](https://arxiv.org/abs/2006.00013)
    - We find no correlation between β and rest-frame UV magnitude M1500 at all redshifts but we find a strong correlation between β and stellar mass, with lower mass galaxies exhibiting bluer UV slope
    - We find no evidence for extreme stellar populations or evidence for Pop III stars in low-luminosity galaxies at z>6.
    - We find a strong correlation between β and SFR such that galaxies with low SFRs exhibit bluer slopes

- [Gravitational Potential and Surface Density Drive Stellar Populations -- II. Star-Forming Galaxies](https://arxiv.org/abs/2006.00720)
    - In Barone et al. (2018) we found that for early-type galaxies the age-Σ and [Z/H]-Φ relations show the least intrinsic scatter as well as the least residual trend with galaxy size.  Φ基本就是引力势，M/R 本文发现在SF星系中有类似结论
    - For the [Z/H]--Φ relation we conclude that gravitational potential is the primary regulator of metallicity, via its relation to the gas escape velocity.
    - The age--Σ relation is consistent with compact galaxies forming earlier

- [Abundance matching tested on small scales with galaxy dynamics](https://arxiv.org/abs/2006.00818)
    - 190个Virgo cluster星系，测量恒星质量和total mass到r23.5处，和AM方法给出的比较
    - We find that theoretical models reproduce the slope and normalization of the observed stellar-to-halo mass relation (SHMR) over more than three orders of magnitude in stellar mass 但是和观测比，SHMR的scatter大了很多
    - For systems with stellar masses exceeding 5×10^10 M⊙, AM overpredicts the observed stellar masses for a given dynamical mass.

- [The impact of stellar and AGN feedback on halo-scale baryonic and dark matter accretion in the EAGLE simulations](https://arxiv.org/abs/2006.00924)
    - We find that variations in halo baryon fractions at fixed mass (particularly their circum-galactic medium gas content) are very well correlated with variations in the baryon fraction of accreting matter, which we show to be heavily suppressed by stellar feedback in low-mass haloes
    - Breaking down accretion rates into first infall, recycled, transfer and merger components, we show that baryons are much more likely to be smoothly accreted than to have originated from mergers when compared to DM, finding (averaged across halo mass) a merger contribution of ≈6% for baryons, and ≈15% for DM at z≈0

- [The Horizon Run 5 Cosmological Hydrodynamic Simulation: Probing Galaxy Formation from Kilo- to Giga-parsec Scales](https://arxiv.org/abs/2006.01039)
    - **Useful, SSST, CSST**
    - Gpc尺度, 1 kpc分辨率；Inside the simulation box we zoom-in on a high-resolution cuboid region with a volume of 1049x114x114 Mpc^3 进行了sub-grid physics模拟，RAMSES
    - The simulation also indicates that hydrodynamical effects on small scales impact galaxy clustering up to very large scales near and beyond the baryonic acoustic oscillation (BAO) scale. Hence, caution should be taken when using that scale as a cosmic standard ruler: one should carefully understand the corresponding biases.

- [Multi-phase environment of Centaurus A galaxy](https://arxiv.org/abs/2006.01099)
    - ALMA+Chandra: hot X-ray emitting plasma coexists with the warm and cold medium in Cen A
    - 由于来自核心AGN的高能辐射和附近气体与尘埃的相互作用产生的热不稳定性可以自然的产生multi-phase的气体
    - We show that cold gas clouds can coexist in the mutual contact with hot plasma, but even colder dusty molecular clouds have to be distanced by several hundred pc from the hot region

- [An Accreting, Anomalously Low Mass Black Hole at the Center of Low Mass Galaxy IC 750](https://arxiv.org/abs/2006.01114)
    - low mass galaxy IC 750, which has circumnuclear 22 GHz water maser emission; 侧向气体盘直径0.2 pc，中心还有X-ray源
    - The position-velocity structure of the maser emission indicates the central black hole (BH) has a mass less than 1.4×10^5 M⊙
    - Fitting the optical spectrum, we measure a nuclear stellar velocity dispersion σ∗=110.7 km/s
    - The mass upper limit of the intermediate mass black hole in IC 750 falls roughly two orders of magnitude below the MBH−σ∗ relation and roughly one order of magnitude below the MBH−MBulge and MBH−M∗ relations

----

### June 3

- [Galaxy Bias and σ8 from Counts in Cells from the SDSS Main Sample](https://arxiv.org/abs/2006.01146)
    - The counts-in-cells (CIC) galaxy probability distribution depends on both the dark matter clustering amplitude σ8 and the galaxy bias b
    - Unlike the power spectrum, the CIC distribution breaks the degeneracy between σ8 and b on scales large enough that both bias and redshift distortions are still linear 可以同时估计这两个参数

- [HIR4: Cosmological signatures imprinted on the cross correlation between 21cm map and galaxy clustering](https://arxiv.org/abs/2006.01146)
    - 用Horizon Run4模拟Tianlai 21cm map以及DESI ELG
    - Foreground residual: We find that the contamination cannot be ignored in the angular auto-power spectra of HI even when it is small, but has no influence on the accuracy of the angular cross-power spectra between HI and galaxies.
    - We forecast a constraint on the angular diameter distance DA for the Tianlai Pathfinder redshift 0.775 < z <1.03, giving a distance measurement with a precision of 3.3% at that redshift.

- [AT 2017gbl: a dust obscured TDE candidate in a luminous infrared galaxy](https://arxiv.org/abs/2006.01518)
    - Extremely infrared (IR) luminous transient AT 2017gbl, coincident with the Northern nucleus of the luminous infrared galaxy (LIRG) IRAS 23436+5257.
    - Radiative transfer modelling of the host galaxy spectral energy distribution shows the presence of a hitherto undetected dust obscured active galactic nucleus (AGN)
    - An extremely energetic supernova would satisfy this budget, but is ruled out by the radio counterpart evolution.
    - This makes AT 2017gbl the third TDE candidate to be hosted by a LIRG, in contrast to the so far considered TDE population discovered at optical wavelengths and hosted preferably by post-starburst galaxies.

- [ALMA [N ıı] 205 μm Imaging Spectroscopy of the Lensed Submillimeter galaxy ID 141 at redshift 4.24](https://arxiv.org/abs/2006.01147)
    - Benefiting from lensing magnification by a galaxy pair at z=0.595, ID 141 is one of the brightest z>4 SMGs
    - Our continuum-based lensing model implies an averaged amplification factor of ∼5.8 and reveals that the de-lensed continuum image has the S\'ersic index ≃0.95 and the S\'ersic radius of ∼0.18″(∼1.24 kpc). 动力学给出DM质量在10^12 Msun
    - ID 141 being a disk galaxy dynamically supported by rotation.

- [The weak imprint of environment on the stellar populations of galaxies](https://arxiv.org/abs/2006.01154)
    - SDSS DR7: we find that satellites are both more metal-rich (<0.1 dex) and older (<2 Gyr) than centrals of the same stellar mass.
    - 但是当区分开SF，GV，Red星系后，发现年龄和金属丰度的环境依赖都弱了很多
    - We find that star-forming galaxies show no environmental effects, neither for centrals nor for satellites.
    - Finally, we find a unique feature in the stellar mass--stellar metallicity relation for passive centrals, where galaxies in more massive haloes have larger stellar mass at constant stellar metallicity; this effect is interpreted in terms of dry merging of passive central galaxies and/or progenitor bias.

- [New Constraints On the Origin of Surface Brightness Profile Breaks of Disk Galaxies From MaNGA](https://arxiv.org/abs/2006.01356)
    - Most TII (TIII) galaxies have down-bending (up-bending) star formation rate (SFR) radial profiles, implying that abrupt radial changes of SFR intensities contribute to the formation of both TII and TIII breaks
    - Nevertheless, a comparison between our galaxies and simulations suggests that stellar migration plays a significant role in weakening down-bending Σ⋆ profile breaks.
    - While there is a correlation between the break strengths of SBPs and age/metallicity-sensitive spectral features for TII galaxies, no such correlation is found for TIII galaxies, indicating that stellar migration may not play a major role in shaping TIII breaks

- [New Analytic Solutions for Galaxy Evolution II: Wind Recycling, Galactic Fountains and Late-Type Galaxies](https://arxiv.org/abs/2006.01643)
    - We generalize the analytic solutions presented in Pantoni et al. (2019) by including a simple yet effective description of wind recycling and galactic fountains, with the aim of self-consistently investigating the spatially-averaged time evolution of the gas, stellar, metal, and dust content in disc-dominated late-type galaxies (LTGs).
    - We highlight the crucial relevance of wind recycling and galactic fountains in efficiently refurnishing the gas mass, extending the star-formation timescale, and boosting the metal enrichment in gas and stars.

- [Radio morphology of southern narrow-line Seyfert 1 galaxies with the JVLA observations](https://arxiv.org/abs/2006.01700)
    - JVLA观测：radio emission of NLS1s is mainly concentrated in a central region at kpc-scale and only a few sources show diffuse emission.
    - In RQ NLS1s, the radio luminosity tends to be higher in steep-spectrum sources and be lower in flat-spectrum sources, which is opposite to RL NLS1s
    - May be because the radio emission of steep NLS1s is dominated by misaligned jets, AGN-driven outflows, or star formation superposing on a compact core. Instead the radio emission of flat NLS1s may be produced by a central core which has not yet developed radio jets and outflows
    - 不需要很大质量SMBH就能产生能量较高的kpc尺度的jet

- [A Catalog of Holes and Shells in the Interstellar Medium of the LITTLE THINGS Dwarf Galaxies](https://arxiv.org/abs/2006.01735)
    - A catalog of holes and shells in the neutral atomic hydrogen (\HI) of 41 gas-rich dwarf galaxies in LITTLE THINGS: confirmed 306 holes between 38 pc (our resolution limit) and 2.3 kpc, with expansion velocities up to 30 km/s
    - The global star formation rates measured by Ha and FUV emission are consistent with those estimated from the energy required to create the cataloged holes in our sample