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

----

### June 4

- [Effects of the Hubble Parameter on the Cosmic Growth of the First Quasars](https://arxiv.org/abs/2006.01839)
    - We note that the predicted mass of a quasar at z=6 changes by >300% if the underlying Hubble parameter used in the model varies from H0=65 to H0=74 km s−1Mpc−1, a range encompassing current estimates.
    - Employing an MCMC approach based on priors from z≳6.5 quasars and on H0, we study the interconnection between H0 and the parameters describing BH growth: seed mass Mi and Eddington ratio fEdd. 现有的数据更支持H0~73; 以及10^4.5 Msun的种子质量和0.7左右的Eddington ratio.

- [ETHOS -- An effective parametrization and classification for structure formation: the non-linear regime at z≳5](https://arxiv.org/abs/2006.01842)
    - 用两个参数描述高红移不同暗物质模型下星系演化的模型：Our description is within the recently proposed ETHOS framework and includes standard thermal Warm DM (WDM) and models with dark acoustic oscillations (DAOs).
    - We show that the two physically motivated parameters hpeak and kpeak, the amplitude and scale of the first DAO peak, respectively, are sufficient to parametrize the linear matter power spectrum and classify the DM models as belonging to effective non-linear structure formation regions
    - 什么是DAO：
        - ETHOS covers two types of new DM physics: (i) a primordial cutoff in the linear matter power spectrum suppressing the growth of small density perturbations due to either collisionless damping (free-streaming) like in WDM, or due to collisional damping caused by interactions between DM and relativistic particles in the early Universe and resulting in Dark Acoustic Oscillations

- [Deep XMM-Newton Observations of the Most Distant SPT-SZ Galaxy Cluster](https://arxiv.org/abs/2006.02009)
    - **Interesting**
    - z=1.71的星系团，最高红移的有SZ探测的星系团：cluster emission is detected above the background to a radius of ∼2.2r500, or approximately the virial radius.
    - 能给出金属丰度测量：at radii r>0.3r500, we find it to be 0.33±0.17, in good agreement with precise measurements at similar radii in the most nearby clusters, supporting an early enrichment scenario
    - 对金属丰度演化模型有极强的限制能力

- [Towards a Bias-Free Selection Function in Shear Measurement](https://arxiv.org/abs/2006.02095)
    - We proposed a new selection function defined in the power spectrum of the galaxy image. This new selection function has low selection bias, and it is particularly convenient for shear measurement pipelines based on Fourier transformation.

- [GenetIC -- a new initial conditions generator to support genetically modified zoom simulations](https://arxiv.org/abs/2006.01841)
    - The code allows precise, user-specified alterations to be made to arbitrary regions of the simulation (while maintaining consistency with the statistical ensemble). These "genetic modifications" allow, for example, the history, mass, or environment of a target halo to be altered in order to study the effect on their evolution.

- [ASKAP reveals giant radio halos in two merging SPT galaxy clusters -- Making the case for a direction-dependent pipeline](https://arxiv.org/abs/2006.01833)
    - We performed direction-dependent (DD) calibration and imaging using state-of-the-art software killMS and DDFacet. 降低射电图像里的artefacts
    - We present our DD calibrated ASKAP radio images of both clusters showing unambiguous giant radio halos with largest linear scales of ∼1~Mpc.
    - Although there is a shock detected in the thermal X-ray emission of this cluster, we find that the particle number density in the shocked region is too low to allow for the generation of a radio shock.

- [Revisiting dual AGN candidates with spatially resolved LBT spectroscopy -- The impact of spillover light contamination](https://arxiv.org/abs/2006.01846)
    - MODS观测：We find that at most two of the seven targets actually retain a Seyfert-Seyfert dual AGN, whereas the others may be more likely powered by post-AGB stars in retired galaxies or through shock
    - The major cause of this discrepancy is a bias caused by the spillover of flux from the primary source in the secondary SDSS fibre which can be more than an order of magnitude at <3" separations.
    - We also find that the nuclei with younger stellar ages host the primary AGN.

- [The X-ray View of Merger-Induced AGN Activity at Low Redshift](https://arxiv.org/abs/2006.01850)
    - XMM观测post-merger和更大样本匹配后的不相互作用样本，发现post-merger中看到AGN的几率高一些，但统计不显著
    -  Dominant, luminous AGN are more frequent in post-mergers, the lack of a comparable excess of 2-10 keV X-ray AGN suggests that AGN in post-mergers are more likely to be heavily obscured.

- [JINGLE -- IV. Dust, HI gas and metal scaling laws in the local Universe](https://arxiv.org/abs/2006.01856)
    - Dust and Element evolUtion modelS (DEUS) - incluidng stellar dust production, grain growth, and dust destruction - within a Bayesian framework to enable a rigorous search of the multi-dimensional parameter space
    - We find that these scaling laws for galaxies with −1.0≲logMHI/M⋆≲0 can be reproduced using closed-box models with high fractions (37-89%) of supernova dust surviving a reverse shock, relatively low grain growth efficiencies (ϵ=30-40), and long dus lifetimes (1-2\,Gyr).
    - 恒星演化贡献的尘埃远多于在ISM环境下成长的

- [Mass loss from massive globular clusters in tidal fields](https://arxiv.org/abs/2006.01960)
    - N-body模拟研究 identify two populations we call kicks and sweeps, that escape through two-body encounters internal to the cluster and the external tidal field
    - We find that for a typical halo globular cluster on a moderately eccentric orbit, sweeps are far more common than kicks but the total mass loss rate is so low that these clusters can survive for hundreds of Hubble times.

- [Stellar Population Synthesis with Distinct Kinematics: Multi-Age Asymmetric Drift in SDSS-IV MaNGA Galaxies](https://arxiv.org/abs/2006.02071)
    - We present the first asymmetric drift (AD) measurements for unresolved stellar populations of different characteristic ages above and below 1.5 Gyr. These measurements sample the age-velocity relation (AVR) in galaxy disks.
    - We develop two efficient algorithms to extract AD on a spaxel-by-spaxel basis from optical integral-field spectroscopic (IFS)
    - We apply them to an initial sample of seven galaxies with comparable stellar mass and color to the Milky Way. We find a wide range of distinct AD radial profiles for young and old stellar populations.

- [Large-scale turbulent driving regulates star formation in high-redshift gas-rich galaxies](https://arxiv.org/abs/2006.02084)
    - We show that stellar feedback is sufficient to reduce the averaged star formation rate (SFR) to the level of the Schmidt- Kennicutt law in Milky-Way like galaxies but not in high-redshift gas rich galaxies
    - We investigate whether an external driving of the turbulence such as the one created by the large galactic scales could diminish the SFR at the observed level. we infer a typical turbulent forcing that we argue should be applied parallel to the plane of the galactic disc

----

### June 5

- [Revisiting Soltan's argument based on a semi-analytical model for galaxy and black hole evolution](https://arxiv.org/abs/2006.02436)
    - SAM: By tracing the growth history of individual SMBHs, we find that the fraction of the SMBH mass acquired during the super-Eddington accretion phases to the total SMBH mass becomes larger for less massive black holes and at higher redshift.
    - The mass-weighted radiation efficiency of SMBHs with > 1e+8 Msun obtained with our model, is about 0.08 at z = 0, which is consistent with Soltan's argument

- [Luminosity Functions and Host-to-Host Scatter of Dwarf Satellite Systems in the Local Volume](https://arxiv.org/abs/2006.02443)
    - We measure the surface brightness fluctuation (SBF) distances to recently cataloged candidate dwarf satellites around 10 massive hosts within D<12 Mpc to confirm association.
    - Adopting a SHMR that matches hydrodynamic simulations, the predicted overall satellite abundance agrees well with the observations. The MW is remarkably typical in its luminosity function amongst LV hosts.
    - We find that the host-to-host scatter predicted by the model is in close agreement with the scatter between the observed systems, once the different masses of the observed systems are taken into account
    - We find significant evidence that the observed systems have more bright and fewer faint satellites than the SHMR model predicts

- [Radial Distributions of Dwarf Satellite Systems in the Local Volume](https://arxiv.org/abs/2006.02444)
    - 12 well-surveyed satellite systems of MW-like hosts in the Local Volume that are complete to MV<−9 and within 150 projected kpc.
    - The observed satellites are significantly more centrally concentrated than the simulated systems.
    - Several of the observed hosts, including the MW, are ∼2σ outliers relative to the simulated hosts in being too concentrated, while none of the observed hosts are less centrally concentrated than the simulations.

- [The Mass-Metallicity Relation at z=8: Direct-Method Metallicity Constraints and Near-Future Prospects](https://arxiv.org/abs/2006.02447)
    - 高红移星系用[OIII] 88 micron线结合SFR估计气态丰度，typical abundances 12+log(O/H) = 7.9 (∼0.2 times the solar value) and an evolution of 0.9±0.5 dex in oxygen abundance at fixed stellar mass from z≃8 to 0.
    - We highlight [O III] 52μm as a valuable feature for robust metallicity measurements. Precision of 0.1-0.2 dex in T_e-based O/H abundance can be reasonably achieved for galaxies at z≈5-8 by combining [O III] 52μm

- [On the AGN nature of two UV bright sources at z_spec~5.5 in the CANDELS fields: an update of the AGN space density at M1450~-22.5](https://arxiv.org/abs/2006.02451)
    - GOODS-S, -N, EGS里的AGN：We derive an AGN space density of Phi=1.29x10^-6 cMpc^-3 at z~5.5 and M1450~-22.5 by simply dividing their observed number by the cosmological volume in the range 5.0<z<6.1.
    - This value supports a high space density of AGNs at z>5, in contrast with previous claims mostly based on standard color selection, possibly affected by significant incompleteness.

- [Formation of massive black holes in ultra-compact dwarf galaxies: migration of primordial intermediate-mass black holes in N-body simulation](https://arxiv.org/abs/2006.02517)
    - 看UCD里10^6 Msun的SMBH有没有可能是IMBH并合而来：We find that only massive IMBHs of 105 M⊙ sink into the central regions of their host dwarf (≈10^10 M⊙) to be gravitationally trapped by its stellar nucleus within less than 1 Gyr in most dwarf models.
    - We show that the IMBHs can form binaries in the centre and, rarely, before they reach the centre, which may lead to the IMBHs merging and thus emitting gravitational waves that could be detected by LISA.

- [The Sloan Digital Sky Survey Reverberation Mapping Project: The M_BH-Host Relations at 0.2<z<0.6 from Reverberation Mapping and Hubble Space Telescope Imaging](https://arxiv.org/abs/2006.02522)
    - SDSS RM测黑洞质量，HST观测估计bulge质量：The BH masses and stellar masses of our sample broadly follow the same correlations found for local RM AGN and quiescent bulge-dominant galaxies, with no strong evidence of evolution in the M_BH-M_*,bulge relation to z~0.6.
    - However, the host fraction derived from spectral decomposition is systematically smaller than that from imaging decomposition by ~30%, indicating different systematics in both approaches.

- [Rotation Curves in z~1-2 Star-Forming Disks: Evidence for Cored Dark Matter Distributions](https://arxiv.org/abs/2006.03046)
    - High quality, H{\alpha} or CO rotation curves (RCs) to several Re for 41 large, massive, star-forming disk galaxies (SFGs), across the peak of cosmic galaxy evolution (z~0.67-2.45)
    - Two-thirds or more of the z>1.2 SFGs are baryon dominated within a few Re of typically 5.5 kpc, and have DM fractions less than maximal disks (<fDM (Re)>=0.12).
    - DM fractions correlate inversely with the baryonic angular momentum parameter, baryonic surface density and bulge mass.
    - The typical central 'DM deficit' in these cores relative to NFW distributions is ~30% of the bulge mass. The observations are consistent with rapid radial transport of baryons in the first generation massive gas rich halos forming globally gravitationally unstable disks, and leading to efficient build-up of massive bulges and central black holes.

----

### June 7

- [Interpreting LOFAR 21-cm signal upper limits at z~9.1 in the context of high-z galaxy and reionisation observations](https://arxiv.org/abs/2006.03203)
    - We use 21CMMC, a Monte Carlo Markov Chain sampler of 21cmFAST which directly forward models the 3D cosmic 21-cm signal in a fully Bayesian framework. We use the astrophysical parameterisation from 21cmFAST, which includes mass-dependent star formation rates and ionising escape fractions as well as soft-band X-ray luminosities to place limits on the properties of the high-z galaxies. 排除一些参数空间
    - With tighter upper limits, across multiple redshift bins expected in the near future from LOFAR, more viable models will be ruled out. Our approach demonstrates the potential of forward modelling tools such as 21CMMC in combining 21-cm observations with other high-z probes to constrain the astrophysics of galaxies.

- [A measurement of the Hubble constant from Type II supernovae](https://arxiv.org/abs/2006.03412)
    - we use SNe II as standardisable candles to obtain an independent measurement of the Hubble constant. Using 7 SNe II with host-galaxy distances measured from Cepheid variables or the tip of the red giant branch, we derive H0=75.8+5.2−4.9 km s−1 Mpc−1
    - Adding an estimate of the systematic errors (2.8 km s−1 Mpc−1) changes the ∼1.7σ discrepancy with Planck +ΛCDM to ∼1.4σ. Including the systematic errors and performing a bootstrap simulation, we confirm that the local H0 value exceeds the value from the early Universe with a confidence level of 95%.

- [Modeling Photoionized Turbulent Material in the Circumgalactic Medium II: Effect of Turbulence within a Stratified Medium](https://arxiv.org/abs/2006.03066)
    - The circumgalactic medium (CGM) of nearby star-forming galaxies shows clear indications of OVI absorption accompanied by little to no detectable NV absorption.
    - We carry out chemodynamical simulations of stratified media in a Navarro-Frenk-White (NFW) gravitational potential with a total mass of 10^12 solar masses and turbulence that decreases radially.
    - Turbulence with an average one-dimensional velocity dispersion approximately 40 km/s, corresponding to an energy injection rate of approximately 10^49 erg/yr, produces a CGM that matches many of the observed ionic column densities and ratios.
    - The NVI to OVI ratio is suppressed from its equilibrium value due to a combination of radiative cooling and cooling from turbulent mixing

- [Circumnuclear Molecular Gas in Low-redshift Quasars and Matched Star-forming Galaxies](https://arxiv.org/abs/2006.03072)
    - 问题：whether an enhanced molecular gas mass surface density (Σmol) is found in the CND-scale of quasars relative to a comparison sample of inactive galaxies
    - ALMA CO(2-1)观测： We detected CO(2–1) emission from all quasars, which show diverse morphologies.
    -  Contrary to expectations, Σmol of the quasar sample, computed from the CO(2–1) luminosity, tends to be smaller than the comparison sample at r < 500 pc
    - XDR effects can have an impact on molecular mass measurements particularly in the vicinity of luminous quasar nuclei;

- [Spectral shapes of the Lyman-alpha emission from galaxies: I. blueshifted emission and intrinsic invariance with redshift](https://arxiv.org/abs/2006.03232)
    - At low-z, where absorption from the intergalactic medium (IGM) is negligible, we show that the relative contribution of blueshifted emission (blue/red) increases rapidly with increasing equivalent width (WLyα).
    - Our main result is that the blue-peak contribution evolves rapidly downwards with increasing redshift: the blue/red flux ratio is ≈30% at z≈0, but drops to 15% at z≈3, and to below 3% by z≈6.
    - This decrease in the blue-wing contribution can be entirely attributed to the thickening of intervening Ly{\alpha} absorbing systems, with no need for additional HI opacity from local structure

- [Shape, Color and Distance in Weak Gravitational Flexion](https://arxiv.org/abs/2006.03506)
    - Using color measurements in the u-r band and fit Sersic index values, objects with characteristics consistent with early-type galaxies are found to have a lower intrinsic scatter in flexion signal than late-type galaxies.

----

### June 8

- [Dissecting the Strong-lensing Galaxy Cluster MS 0440.5+0204. I. The Mass Density Profile](https://arxiv.org/abs/2006.03927)
    - 三种方法做星系团质量的SL重构：The first model uses the image positions of four multiple imaged systems (providing 26 constraints). The second one combines strong lensing constraints with dynamical information (velocity dispersion) of the cluster. The third one uses the mass calculated from weak lensing as an additional constraint.
    - However, in the third model, the inclusion of the velocity dispersion and the weak-lensing mass allows us to obtain better constraints in the scale radius and the line-of-sight velocity dispersion of the mass profile. M200=2x10^14 Msun

- [Chandra View of the LINER-type Nucleus in the Radio-Loud Galaxy CGCG 292-057: Ionized Iron Line and Jet-ISM Interactions](https://arxiv.org/abs/2006.03717)
    - A LINER-type nucleus and a complex radio structure that indicates intermittent jet activity.
    - We argue that this excess emission results from compression and heating of the hot diffuse fraction of the interstellar medium displaced by the expanding inner, ∼20 kpc-scale lobes observed in this restarted radio galaxy.
    - We demonstrate that the observed X-ray spectrum, particularly the equivalent width of Fe XXV Kα (of order 0.3 keV) can in principle, be explained in a scenario involving a Compton-thin gas located at the scale of the broad-lined region in this source and photoionized by nuclear illumination.

- [How Well Can We Measure the Stellar Mass of a Galaxy: The Impact of the Assumed Star Formation History Model in SED Fitting](https://arxiv.org/abs/2006.03599)
    - **Relevant**
    - 用 mock observations of high-resolution cosmological hydrodynamic galaxy formation simulations的SFH来检验SED拟合
    - 非参数表达的SFH表现更好
    - We find a decrease in the average bias of 0.4 dex with a delayed-τ model to a bias of just under 0.05 dex for the nonparametric model.

- [The power of co-ordinate transformations in dynamical interpretations of Galactic structure](https://arxiv.org/abs/2006.03600)
    - As we collect data over a wider area of the disc it becomes increasingly appealing to start analysing stellar actions and angles, which specifically label orbit space, instead of their current phase space location
    - Grouping in actions and angles refines this further to isolate stars which are travelling together through space and hence have shared histories

- [HST Grism-derived Forecasts for Future Galaxy Redshift Surveys](https://arxiv.org/abs/2006.03602)
    - **CSST, SSST**
    - The mutually complementary Euclid and Roman galaxy redshift surveys will use Halpha- and [OIII]-selected emission line galaxies as tracers of the large scale structure at 0.9≲z≲1.9 (Halpha) and 1.5≲z≲2.7 ([OIII])
    - 而这些ELG的选择函数很复杂：受到星系的尺寸和光度，发射线等值宽度等的影响
    - 利用HST数据模拟Euclid观测：we explore the prevalence of redshift misidentification in future Euclid samples, finding potential contamination rates of ∼14-20% and ∼6% down to 2×10^−16 and 6×10^−17 erg s−1 cm−2,

- [EMPRESS. II. Highly Fe-Enriched Metal-poor Galaxies with ∼1.0 (Fe/O)⊙ and 0.02 (O/H)⊙ : Possible Traces of Super Massive (>300M⊙) Stars in Early Galaxies](https://arxiv.org/abs/2006.03831)
    - **Interesting; SSST**
    - Weak emission lines such as [FeIII]4658 and HeII4686 are detected in very deep optical spectra of the EMPGs
    - The iron-to-oxygen abundance ratios (Fe/O) of the EMPGs are generally high; the EMPGs with the 2%-solar oxygen abundance show high Fe/O ratios of ~90-140% (Fe/O)_sun 不太可以被SNIa解释
    - These EMPGs have very high HeII4686/Hβ ratios of ~1/40, which are not reproduced by existing models of high-mass X-ray binaries whose progenitor stellar masses are less than 120 M_sun.
    - We propose that both the high Fe/O ratios and the high HeII4686/Hβ ratios are explained by the past existence of super massive (>300 M_sun) stars, which may evolve into intermediate-mass black holes (≳100 M_sun).

- [The ALMA Spectroscopic Survey in the Hubble Ultra Deep Field: The nature of the faintest dusty star-forming galaxies](https://arxiv.org/abs/2006.04284)
    - Median stellar masses and star formation rates (SFR) of 4.8×10^10 M⊙ and 30 M⊙ yr−1
    - We derive a median spectroscopic redshift of 1.8; 比SMG低很多
    - 大部分都在SFMS上或者低于SFMS；The ASPECS galaxies closely follow the SFR-molecular gas mass relation and other previously established scaling relations
    - ASPECS galaxies located significantly below the MS, a poorly exploited parameter space, have low gas-to-stellar mass ratios of ∼0.1−0.2 and long depletion timescales >1 Gyr.

- [Shadows in the Dark: Low-Surface-Brightness Galaxies Discovered in the Dark Energy Survey](https://arxiv.org/abs/2006.04294)
    - **Relevant**
    - A catalog of 20,977 extended low-surface-brightness galaxies (LSBGs) identified in ~ 5000 deg2 from the first three years of imaging data from the Dark Energy Survey (DES)
    - We define extended LSBGs as galaxies with g-band effective radii Reff>2.5" and mean surface brightness μ¯eff(g)>24.3 mag arcsec−2.
    - 颜色分布是高度双态的；Redder LSBGs are more clustered than their blue counterparts
    - Red LSBGs constitute ∼35% of our LSBG sample, and ∼30% of these are located within 1 deg of low-redshift galaxy groups and clusters
    - 在最显著的10个星系群或者星系团里找到了108个可能的UDG

- [NuSTAR view of Swift/BAT AGN: The R-Γ correlation](https://arxiv.org/abs/2006.04441)
    - The reflection strength was found to be strongly correlated with the power-law slope in unabsorbed sources, pointing towards disc reflection for these sources.
    - Different possible explanations were tested and the most likely one is that the corona is moving either towards or away from the disc with a moderately relativistic velocity.

- [Galaxy Optical Variability of Virgo Cluster: New Tracer for Environmental Influences on Galaxies](https://arxiv.org/abs/2006.04456)
    - 用PTF在Virgo方向的数据：A sample of 814 Virgo galaxies with 230263 observations shows a monotonically decreasing trend of optical variability with increasing clustercentric distance.
    - The variability level inside the cluster is 3.2σ higher than the level outside
    - Our result is consistent with the theory that the cold gas flowing inwards the cluster centre fuels AGN activity. This work is a new implementation of the method using optical variability to investigate the relation between galaxies evolution and their environment.

- [Properties of brightest group galaxies in cosmic web filaments](https://arxiv.org/abs/2006.04463)
    - We chose brightest group galaxies (BGGs) in groups with two to six members as our probes of the impact of filamentary environment because their local environment can be determined more accurately.
    - We note slight deviations between the galaxy populations inside and outside the filament radius in terms of stellar mass, colour, the 4000AA break, specific star formation rates, and morphologies. 基本上没有显著变化
    - Within a 4 Mpc radius of the filament axes, the effect of filaments on BGGs is marginal. The local environment is the main factor in determining BGG properties.

- [Polycyclic aromatic hydrocarbon excitation in nearby spiral galaxies](https://arxiv.org/abs/2006.04561)
    - 25个正向Spiral星系中PAH的观测
    - Within 11 of the galaxies, we found that the PAH excitation was straightforwardly linked to ultraviolet or mid-infrared star formation tracers
    - Within another 5 galaxies, the PAH emission is enhanced around star forming regions only at specific galactocentric radii. In 6 more galaxies, PAH excitation is more strongly correlated with the evolved stellar populations as traced by 3.6 micron emission.
    - Galaxies in which PAHs were excited by evolved stars had relatively high far-ultraviolet to mid-infrared ratios, indicating that variations in the link between PAH excitation and different stellar populations is linked to changes in dust attenuation within galaxies

- [A spectroscopic study of MATLAS-2019 with MUSE: an ultra-diffuse galaxy with an excess of old globular clusters](https://arxiv.org/abs/2006.04606)
    - **Relevant**
    - MATLAS J15052031+0148447 (MATLAS-2019) - located towards the nearby group NGC 5846
    - For the stellar body of MATLAS-2019 we derive a metallicity of -1.33+0.19-0.01 dex and an age of 11.2+1.8-0.8 Gyr.
    - From the 11 confirmed globular clusters and using a Markov Chain Monte Carlo approach we derived a dynamical mass-to-light ratio of 4.2+8.6-3.4M/L.

----

### June 11

- [Using GAMA to probe the impact of small-scale galaxy physics on nonlinear redshift-space distortions](https://arxiv.org/abs/2006.05383)
    - **SSST**
    - We explore this generalised halo model with an MCMC algorithm, comparing the predictions to data from the Galaxy And Mass Assembly (GAMA) survey, and thus derive one of the first constraints on the detailed kinematic degrees of freedom for satellite galaxies within haloes
    - With this approach, the distortions of the redshift-space galaxy autocorrelations can be accounted for down to spatial separations close to 10 kpc, opening the prospect of improved RSD measurements of the perturbation growth rate by the inclusion of data from nonlinear scales.

- [Biases in galaxy cluster velocity dispersion and mass estimates in the small number of galaxies regime](https://arxiv.org/abs/2006.05949)
    - 用模拟的星系团看不同estimator得到的速度弥散度估计有多少bias：biweight, gapper and standard deviation, in the small number of galaxies regime
    - The standard deviation is found to be the lowest variance estimator. 只选质量最大的星系会有少量的bias
    - 给出了一个unbiased的estimator：The proposed set of unbiased estimators effectively provides a correction of the velocity dispersion and mass estimates from all those effects in the small number of cluster members regime

- [The beautiful mess in Abell 2255](https://arxiv.org/abs/2006.05949)
    - **Interesting**
    - This is a nearby (z=0.0806) merging galaxy cluster hosting one of the first radio halos ever detected in the intra-cluster medium (ICM).
    - Among the numerous interesting features observed, we discover remarkable bright and filamentary structures embedded in the radio halo
    - We find that the X-ray and radio emission are overall well correlated. The fact that the steepest spectrum emission is located in the cluster center and traces regions with high entropy possibly suggests the presence of seed particles injected by radio galaxies that are spread in the ICM by turbulence generating the extended radio halo.

- [The atomic gas of star-forming galaxies at z∼0.05 as revealed by the Five-hundred-meter Aperture Spherical Radio Telescope](https://arxiv.org/abs/2006.04812)
    - FAST观测z=0.05处的星系里的HI:We use an ON-OFF observing approach that allowed us to reach an rms of 0.7mJy/beam at a 1.7km/s velocity resolution within only 20 minutes ON-target integration time.
    - We find that the CO(J=1−0) and HI emission line profiles are similar. The dynamical mass estimated from the HI data is an order of magnitude higher than the baryon mass and the dynamical mass derived from the CO observations

- [A Deep Learning Approach to Quasar Continuum Prediction](https://arxiv.org/abs/2006.04814)
    - intelligent quasar continuum neural network (iQNet)
    - We use principal component analysis and Gaussian mixture model to classify the HSLA quasar spectra into four classes and use them to synthesize mock quasar spectra create a training data set for iQNet.
    - 判据是 absolute fractional flux error (AFFE)

- [A Multiwavelength Study of the Massive Cool Core Cluste MACS J1447.4+0827](https://arxiv.org/abs/2006.04815)
    - Using this multiwavelength approach, including 70 ks of \textit{Chandra} X-ray observations, we detect the presence of collimated jetted-outflows that coincides with a southern and a northern X-ray cavity.
    -

- [The ALPINE-ALMA [C II] Survey: [C II]158micron Emission Line Luminosity Functions at z∼4−6](https://arxiv.org/abs/2006.04835)
    - 基于118个target：Our derived LFs are consistent with the z∼0 [C II] LF at ≤109L⊙, but show a hint of an excess of [C II] emitters at the luminous end (>109L⊙) compared to z∼0
    - Finally, we find that available model predictions tend to underestimate the number densities of [C II] emitters at z∼5.

- [The ALPINE-ALMA [C II] survey: the luminosity function of serendipitous [C II] line emitters at z∼5](https://arxiv.org/abs/2006.04837)
    - [CII] LF: From a sample of serendipitous lines detected in the ALPINE;  We used the 8 confirmed [CII] and the 4 [CII] candidates to build one of the first [CII] LFs at z∼5
    - We found that 11 out of these 12 sources have a redshift very similar to that of the ALPINE target in the same pointing, suggesting the presence of overdensities around the targets.
    - The clustered sample results in a SFRD ∼10 times higher than previous measurements from UV-selected galaxies. On the other hand, from the field sample (likely representing the average galaxy population) we derived a SFRD ∼1.6 higher compared to current estimates from UV surveys but compatible within the errors.

- [Wide and Deep Exploration of Radio Galaxies with Subaru HSC (WERGS). III. Discovery of a z = 4.72 Radio Galaxy with Lyman Break Technique](https://arxiv.org/abs/2006.04844)
    - 高红移射电星系：The SED fitting analysis with the rest-frame UV and optical photometries suggests the massive nature of this HzRG with logM∗/M⊙=11.4
    - 较低的Lya等值宽度和UV颜色说明系统可能已经演化得比较成熟，而且有尘埃
    - The radio spectral index does not meet a criterion for an ultra-steep spectrum

- [Formation of super-massive black holes in galactic nuclei I: delivering seed intermediate-mass black holes in massive stellar clusters](https://arxiv.org/abs/2006.04922)
    - We carry out N-body simulations of the simultaneous merger of three stellar clusters to form an NSC.
    - We show that these mergers are catalyzed by dynamical interactions with surrounding stars, which systematically harden the binary and increase its orbital eccentricity
    - The seed SMBH will be ejected from the NSC by the recoil kick produced when two IMBHs merge, if their mass ratio q≳0.15
    - 也许可以解释为什么有些星系中心有NSC但没有SMBH

- [The ALPINE-ALMA [CII] Survey: nature, luminosity function and star formation history of continuum non-target galaxies up to z~6](https://arxiv.org/abs/2006.04974)
    - **Important**
    - ALMA Band-7 发现的56个天体：The ALPINE data are the first ones to sample the faint-end of the infrared LF, showing little evolution from z=2.5 to z=6, and a flat slope up to the highest redshifts.
    - The SFRD obtained by integrating the luminosity function remains almost constant between z=2 and 6, and significantly higher than the optical/UV derivations. 一直到 z=6，SFR中都有很重要的被尘埃遮挡部分的贡献
    - 16 per cent of the ALPINE serendipitous continuum sources are optically+near-IR dark; The 7 HST and near-IR dark galaxies with mid-IR counterpart contribute for about 15 per cent of the total SFRD at z=5 and dominate the high-mass end of the stellar mass function at z>3.

- [Deep Learning Prediction of Quasars Broad Lyα Emission Line](https://arxiv.org/abs/2006.05124)
    - The SiIV, CIV, and CIII] broad emission lines are used as the input to the neural network, and the model returns the predicted Lyα emission line as the output.
    - Our model can be used to estimate the HI column density of eclipsing and ghostly damped Lyα (DLA) absorbers as the presence of the DLA absorption in these systems strongly contaminates the flux and the shape of the quasar continuum around Lyα spectral region.

- [J1110+4817 -- a compact symmetric object candidate revisited](https://arxiv.org/abs/2006.05144)
    - Compact symmetric objects (CSOs) are radio-emitting active galactic nuclei (AGNs) typically with a double-lobed radio structure confined to within 1 kpc. 有喷流的AGN的最早期阶段；有些能演化成大尺度的double-lobe AGN，有些也会die out
    - 取决于AGN活动的时间，喷流能量，附近ISM环境等；结构上可以分成：compact double-lobed or a core-jet structure
    - Lower-frequency VLBI images reveal an extended radio feature nearly perpendicular to the main structural axis of the source, apparently emanating from the brighter northern feature, that is rare among the known CSOs

- [Morphology and surface photometry of a sample of isolated early-type galaxies from deep imaging](https://arxiv.org/abs/2006.05323)
    - **Relevant**
    - We observed 20 (out of 104) iETGs, selected from the AMIGA catalog, with the 4KCCD camera at the VATT in the SDSS g and r bands.
    - Our re-classification suggests that the sample is composed of bona fide ETGs spanning from ellipticals to late-S0s galaxies. Most of the surface brightness profiles are best fitted with a bulge plus disc model, suggesting the presence of an underlying disc structure.
    - Shell systems are revealed in about 60% of these galaxies. Because interaction, accretion, and merging events are widely interpreted as the origin of the fans, ripples, shells and tails in galaxies, we suggest that most of these iETGs have experienced such events.

- [High-z Universe probed via Lensing by QSOs (HULQ) I. Number Estimates of QSO-QSO and QSO-Galaxy Lenses](https://arxiv.org/abs/2006.05423)
    - **SSST, CSST**
    - 用QSO host作为lense研究高红移宇宙：We find that ∼440 QSO lenses will reside in the Hyper Suprime-Cam Wide survey (HSC/Wide), which is expected to be the most prolific concurrent survey, with this number being boosted by one to two orders of magnitude (to ∼10000) with upcoming surveys
    - We demonstrate how the intimacy of lensed images to the bright deflector QSO for most systems will affect the \textit{detectability} of QSO lenses. We estimate that only ∼82 and 900 will be detectable for HSC/Wide and LSST, respectively

- [Identifying galaxy groups at high redshift from incomplete spectroscopic data: I. The group finder and application to zCOSMOS](https://arxiv.org/abs/2006.05426)
    - **SSST; Important**
    - We develop a group finder that is based on incomplete redshift samples combined with photometric data, using a machine learning method to assign halo masses to identified groups. Test using realistic mock catalogs shows that ≳90% of true groups with halo masses Mh≳10^12M⊙/h are successfully identified
    - The standard deviation in the halo mass estimation is smaller than 0.25 dex at all masses.

- [Towards an Understanding of the Massive Red Spiral Galaxy Formation](https://arxiv.org/abs/2006.05462)
    - We find that red spirals harbor compact cores with high stellar mass surface densities measured by Σ1 and they are bulge-dominated.
    - The red spirals, especially their bulges follow the Σ1-M∗ ridgeline for quenched galaxies.
    - The optical morphologies reveal that ~70% of red spirals show strong bars, rings/shells and even merging features

- [Local Simulations of Spiral Galaxies with the TIGRESS Framework: I. Star Formation and Arm Spurs/Feathers](https://arxiv.org/abs/2006.05614)
    - **Interesting**
    - We find that more than 90% of star formation takes place in spiral arms, but the global star formation rate (SFR) in models with spiral arms is enhanced by less than a factor of 2 compared to the no-arm counterpart.
    - 旋臂并不直接触发恒星形成，而是把恒星形成区聚集起来；SFR面密度和气体面密度之间有准线性关系
    - Correlated SN feedback produces gaseous spurs/feathers downstream from arms in both magnetized and unmagnetized models 这些结构不是长期存在的
    - SN feedback drives the turbulent component of magnetic fields, with the total magnetic field strength sublinearly proportional to Sigma.

- [Survey of Extremely High-velocity Outflows in Sloan Digital Sky Survey Quasars](https://arxiv.org/abs/2006.05633)
    - We find 40 quasar spectra with broad EHVO CIV absorption, 10 times more than the number of previously known cases. We characterize the EHVO absorption and find that in 26 cases, CIV is accompanied by NV and/or OVI absorption.
    - 缺少HeII发射线，和其他BALQSO比，热光度更高，黑洞质量更大; 说明外流很可能是辐射驱动的
    - 而且红移分布偏高

- [Constructing a multivariate distribution function with a vine copula: toward multivariate luminosity and mass functions](https://arxiv.org/abs/2006.05668)
    - **Interesting**
    - We have proposed a systematic method to build a bivariate luminosity or mass function of galaxies by using a copula. It allows us to construct a distribution function when only its marginal distributions are known
        - A copula is a multivariate cumulative distribution function for which the marginal probability distribution of each variable is uniform on the interval [0, 1]. Copulas are used to describe the dependence between random variables.
        - [vine copula](https://en.wikipedia.org/wiki/Vine_copula): A vine is a graphical tool for labeling constraints in high-dimensional probability distributions.
        - Copula不容易延伸到高维，除非分布特殊，比如多维高斯分布
    - We show a systematic method to extend the copula method to unlimitedly higher dimensions by a vine copula.
        - A typical example is the situation that we have univariate luminosity functions at some wavelengths for a survey, but the joint distribution is unknown

- [Dynamical masses of brightest cluster galaxies I: stellar velocity anisotropy and mass-to-light ratios](https://arxiv.org/abs/2006.05706)
    - **Relevant**
    - 25个BCG的观测：We measure positive central values for h4 for all the BCGs.
    - We find a strong correlation between anisotropy and velocity dispersion profile slope, with rising velocity dispersion profiles corresponding to tangential anisotropy and decreasing velocity dispersion profiles corresponding to radial anisotropy.
    - The rising velocity dispersion profiles can also indicate a significant contribution from the intracluster light (ICL) to the total light (in projection) in the centre of the galaxy.
    - We note that, for some BCGs, a variable βz(r) (from radial to tangential anisotropy) can improve the model fit to the observed kinematic profiles.

- [Testing a theoretical prediction for bar formation in galaxies with bulges](https://arxiv.org/abs/2006.05706)
    - We use those simulations to show that bars can form only when the force constant FB < 0.13, where FB depends on the ratio of the bulge force to the total force of the galaxy at twice the disk scale length 2Rd
    - 大部分S4G里的Bar星系符合这个标准

- [MOCCA Survey Database: Extra Galactic Globular Clusters. I. Method and first results](https://arxiv.org/abs/2006.05887)
    - We apply this study to 12 Gyr-old GCs simulated as part of the MOCCA Survey Database.
    - 区分GC动力学特征需要中心性质测量：The best distinction is achieved by considering the central parameters, those being observational core radius, central surface brightness, ratio between central and half-mass velocity dispersion, or similarly considering the central color, the central V magnitude and the ratio between central and half-mass radius velocity dispersion
    - We mention that the color spread in EGGCs due to internal dynamical models, at fixed metallcity, could be just as important due to the spread in metallicity.

- [Non-parametric Triaxial Deprojection of Elliptical Galaxies](https://arxiv.org/abs/2006.05971)
    - **Relevant, Useful**
    - Present a grid-based non-parametric approach to obtain a triaxial three-dimensional luminosity density from its surface brightness distribution; assumes that the contours of the luminosity density are boxy/discy ellipsoids with radially varying axis ratios
    - 3轴去投影难度很大，但对椭圆星系，其他方向的投影也需要像椭圆星系；本征shape有比较强的prior
    - The method also allows to compare the relative likelihood of deprojections at different viewing angles. We show that the viewing orientations of individual galaxies with nearly ellipsoidal isophotal shapes can be constrained from photometric data alone.

- [IRAM 30m-EMIR Redshift Search of z = 3-4 Lensed Dusty Starbursts selected from the HerBS sample](https://arxiv.org/abs/2006.05992)
    - We obtained spectroscopic redshifts between 3.4 < z < 4.1 through the detection of multiple CO-spectral lines with J ≤ 3.
    - The measured CO luminosities and line widths suggest that all these sources are gravitationally lensed.
    - These observations demonstrate that the 2 mm window is indispensable to confirm robust spectroscopic redshifts for z < 4 sources.

----

### June 12

- [Multiwavelength classification of X-ray selected galaxy cluster candidates using convolutional neural networks](https://arxiv.org/abs/2006.05998)
    - 不是所有的X-ray展源都是cluster：We train the networks on combined XMM-Newton X-ray observations with their optical counterparts from the all-sky Digitized Sky Survey.
    - The results of using CNNs on combined X-ray and optical data for galaxy cluster candidate classification are encouraging and there is a lot of potential for future usage and improvements

- [The copula of the cosmological matter density field is non-Gaussian](https://arxiv.org/abs/2006.06182)
    - Reionization also represents a significant contaminant to CMB-derived cosmological parameter constraints, due to the degeneracy between the Thomson-scattering optical depth, τ, and the amplitude of scalar perturbations, As.
    - We explore the kinematic Sunyaev-Zel'dovich (kSZ) effect as a probe of reionization, and show that it can be used to mitigate the optical depth degeneracy with high-sensitivity, high-resolution data from the upcoming CMB-S4 experiment
    - We show that by combining the kSZ two-point function and the reconstructed kSZ four-point function, degeneracies between τ and Δz can be strongly broken, yielding tight constraints on both parameters

- [Mitigating the optical depth degeneracy using the kinematic Sunyaev-Zel'dovich effect with CMB-S4](https://arxiv.org/abs/2006.06594)
    - Non-Gaussianity of the cosmological matter density field can be largely reduced by a local Gaussianization transformation (and its approximations such as the logrithmic transformation). Such behavior can be recasted as the Gaussian copula hypothesis
    - 但模拟里可以探测到很显著的 non-Gaussianities in the Gaussianized field; 造成的原因是:the very limited degrees of freedom in the copula function, which make it misleading as a diagnosis of residual non-Gaussianity in the Gaussianized field
    - 会影响对N-point CF的预测；explore a remedy of the Gaussian copula hypothesis, which alleviates but not completely solves the above problems.

- [Powering galactic super-winds with small-scale AGN winds](https://arxiv.org/abs/2006.05997)
    - 新的AGN wind模型：The wind is injected by prescribing mass, momentum and energy fluxes across a spherical boundary centred on a supermassive black hole according to available constraints for accretion disc winds.
    - After sweeping-up a mass equal to their own, small-scale winds thermalise, powering energy-driven outflows with dynamics, structure and cooling properties in excellent agreement with those of analytic wind solutions.
    - Above a critical AGN luminosity, initially spherical, small-scale winds power bipolar, energy-driven super-winds that break out of the galactic nucleus, flowing at speeds >1000kms−1 out to ∼10kpc.

- [VINTERGATAN I: The origins of chemically, kinematically and structurally distinct discs in a simulated Milky Way-mass galaxy](https://arxiv.org/abs/2006.06008)
    - We find that in connection to the last major merger at z∼1.5, cosmological accretion leads to the rapid formation of an outer, metal-poor, low-[α/Fe] gas disc around the inner, metal-rich galaxy containing the old high-[α/Fe] stars. 能解释[alpha/Fe]的双态分布
    - We demonstrate the way in which inside-out growth shapes the radial surface density and metallicity profile and how radial migration preferentially relocates stars from the inner to the outer disc. Secular disc heating is found to give rise to increasing velocity dispersions and scaleheights with stellar age.

- [VINTERGATAN II: the history of the Milky Way told by its mergers](https://arxiv.org/abs/2006.06011)
    - We find that the initial growth phase of galaxy evolution, dominated by repeated major mergers, provides the necessary physical conditions for the assembly of a thick, kinematically hot disk populated by high-[α/Fe] stars, formed both in situ and in accreted satellite galaxies
    - The diversity of evolutionary tracks followed by the simulated galaxy and its progenitors leads to very little overlap of the in situ and accreted populations for any given chemical composition.
    - At a given age, the spread in [α/Fe] abundance ratio results from the diversity of physical conditions in VINTERGATAN and its satellites, with an enhancement in [α/Fe] found in stars formed during starburst episodes. Later, the cessation of the merger activity promotes the in situ formation of stars in the low-[α/Fe] regime, in a radially extended, thin and overall kinematically colder disk

- [VINTERGATAN III: how to reset the metallicity of the Milky Way](https://arxiv.org/abs/2006.06012)
    - We present a new scenario for the onset of star formation at the metal-poor end of the low-[α/Fe] sequence in a Milky Way-like galaxy
    - Galaxy is fueled by two distinct gas flows. One is enriched by outflows from massive galaxies, but not the other.
        - 前一种feed银河系内部区域，后一种feed outer gas disk
        - The first passage of the last major merger galaxy triggers tidal compression in the outer disk, which increases the gas density and eventually leads to star formation, at a metallicity 0.75 dex lower than the inner galaxy. This forms the first stars of the low-[α/Fe] sequence.
    - This process implies that the low-[α/Fe] sequence is populated in situ, simultaneously from two formation channels, in the inner and the outer galaxy, with distinct metallicities.

- [The Sloan Digital Sky Survey Reverberation Mapping Project: To Breathe or Not to Breathe](https://arxiv.org/abs/2006.06178)
    - Broad-line region (BLR) "breathing": Increased central luminosity will enhance line emissivity in more distant clouds, leading to increased average distance of the broad-line-emitting clouds and decreased averaged line width 但不同发射线存在差异
    - Some high-ionization lines, such as C IV, can even show "anti-breathing" where the line broadens when luminosity increases.
    - We quantify the breathing effect (Δlog W=αΔlog L) of broad Hα, Hβ, Mg II, C IV, and C III] for statistical quasar samples over z≈0.1−2.5. We found that Hβ displays the most consistent normal breathing expected from the virial relation (α∼−0.25), Mg II and Hα on average show no breathing (α∼0), and C IV (and similarly C III] and Si IV mostly shows anti-breathing (α>0).
    - The anti-breathing of C IV can be well understood by the presence of a non-varying core component in addition to a reverberating broad-base component

- [The Compact Star-Forming Galaxies at 2<z<3 in 3D-HST/CANDELS: AGN and Non-AGN Physical Properties](https://arxiv.org/abs/2006.06223)
    - At 2 < z < 3, the similar environment between cSFGs with and without AGNs suggests that their AGN activities are potentially triggered by internal secular processes, such as gravitational instabilities or/and dynamical friction.

- [Tidal disruption events in the first billion years of a galaxy](https://arxiv.org/abs/2006.06565)
    - **Interesting**
    - We introduce a new physically motivated model to self-consistently treat TDEs in cosmological simulations, and apply it to the assembly of a galaxy with final mass 3×1010M⊙ at z=6. 每十万年一次
    - A fraction of the disrupted stars participate in the growth of MBHs, dominating it until the MBH reaches mass ∼5×10^5M⊙, but their contribution then becomes negligible compared to gas. TDE可能可以为黑洞质量增长提供新途径
    - Galaxy mergers bring multiple MBHs in the galaxy, resulting in an enhancement of the global TDE rate in the galaxy by ∼1 order of magnitude during 100Myr around mergers.

- [Space Telescope and Optical Reverberation Mapping Project. XI. Disk-wind characteristics and contributions to the very broad emission lines of NGC 5548](https://arxiv.org/abs/2006.06615)
    - 来自盘风上层的obscurer的吸收可能会导致AGN里吸收线和发射线的变化与连续谱脱相干。
    - Changes in the wind properties alter its shielding and affect the SED striking the BLR, producing the observed decorrelations.
    - We find that a translucent wind can contribute a part of the He II and Fe K? emission. It has a modest optical depth to electron scattering, which explains the fainter far-side emission in the observed velocity delay maps.

----

### June 14

- [The Massive and Distant Clusters of WISE Survey X: Results from a Sunyaev-Zeldovich Effect Pilot Study of Massive Galaxy Clusters at z>1 using the GBT + MUSTANG2](https://arxiv.org/abs/2006.06703)
	- **Relavant**
	- Using typical on-source integration times of 3-4 hours per cluster, MUSTANG2 on the Green Bank Telescope was able to measure strong detections of SZE decrements and statistically significant masses on 14 out of 16 targets.
	- Finally, there are indications that the relationship between optical richness used by MaDCoWS and SZE-inferred mass may be significantly flatter than indicated in previous studies.

- [The imprint of dark subhaloes on the circumgalactic medium](https://arxiv.org/abs/2006.06741)
    - **important**
    - We calculate the expected signal and how it depends on important physical parameters (subhalo mass, CGM temperature, and relative velocity).
    - We find that dark subhaloes enhance the local CGM pressure, density, and temperature, in order of decreasing magnitude of the effect.

- [Shear measurement bias II: a fast machine learning calibration method](https://arxiv.org/abs/2006.07011)
    - The method estimates the individual shear responses of the objects from the combination of several measured properties on the images using supervised learning
    - On simulated GREAT3 data, we obtain a residual bias after the calibration compatible with 0 and beyond Euclid requirements for SNR>20
    - 神经网络结构简单；可以使用较少的数据，因为对shape noise不敏感

- [An Optimized Lyα Forest Inversion Tool Based on a Quantitative Comparison of Existing Reconstruction Methods](https://arxiv.org/abs/2006.07162)
    - The methods which are used so far for matter reconstructions are the Richardson-Lucy algorithm, an iterative Gauss-Newton method and a statistical approach assuming a one-to-one correspondence between matter and flux.
    - We conclude that the iterative Gauss-Newton method offers the most accurate reconstruction, in particular at small S/N, but has also the largest numerical complexity and requires the strongest assumptions.

- [The PAU survey: Lyα intensity mapping forecast](https://arxiv.org/abs/2006.07177)
    - PAUS image and DESI or eBOSS spectra.
    - The total probability of detection is estimated to be 23% and 33% for PAUS-eBOSS and PAUS-DESI respectively

- [Fainter harder brighter softer: a correlation between alpha-ox and X-ray spectral state and Eddington ratio in tidal disruption events](https://arxiv.org/abs/2006.06684)
    - We estimate the relative contribution of the disk and corona to the observed X-ray emission through spectral modeling
    - 和X-ray binary以及AGN类似，有state transition.
    - 光学和Xray发现的TDE可能有系统差别
    - TDEs around the most massive supermassive black holes are observed in the hard state; this could indicate that TDE evolution is faster around more massive BHs.

- [Discovery and Follow-up of ASASSN-19dj: An X-ray and UV Luminous TDE in an Extreme Post-Starburst Galaxy](https://arxiv.org/abs/2006.06690)
    - ASASSN-19dj, a nearby tidal disruption event (TDE) discovered in the post-starburst galaxy KUG 0810+227 by the ASAS-SN at a distance of d ≃ 98 Mpc.
    - Initially remaining roughly constant in X-rays and slowly fading in the UV/optical, the X-ray flux increased by over an order of magnitude ∼225 days after peak, resulting from the expansion of the X-ray emitting surface.
    - ASASSN-19dj occurred in the most extreme post-starburst galaxy yet to host a TDE, wit

- [The imprint of arms and bars on rotation curves: in-plane and off-plane](https://arxiv.org/abs/2006.06688)
    - the induced non-circular motions are more prominent for spirals with larger pitch angle, the ones typical in late type galaxies. Moreover, inside corotation, stars rotate slower along the spiral arms than along the inter-arm, which translates into a local minima or maxima in the RC, respectively.
    - we conclude that, the following explanations of bumps and wiggles in RCs are equivalent: they are manifestations of diagonal ridges in the Vϕ−R plane or of the rearrangement of the orbital eccentricities in the stellar disc.

- [And In The Darkness Unbind Them: High-Resolution Simulations of Dark Matter Subhalo Disruption in a Milky Way-like Tidal Field](https://arxiv.org/abs/2006.06695)
    - Our simulations indicate that including stellar components in the tidal field results in the number of subhalos in Milky Way-like galaxies being only 65% of LCDM predictions.
    - For subhalos with small pericentres (rp≲25 kpc), the subhalo abundance is reduced further to 40%, with the surviving subhalos being less dense and having a tangentially-anisotropic orbital distribution
    - 分辨率很重要：These ratios are higher than those found in previous studies that include the effects baryonic matter, which are affected by spurious disruption caused by low resolution.

- [Diffuse Ionized Gas in Simulations of Multiphase, Star-Forming Galactic Disks](https://arxiv.org/abs/2006.06697)
    - For a theoretical investigation of the warm ionized medium (WIM), it is crucial to solve radiation transfer equations where the ISM and clusters are modeled self-consistently.
    - We find that the WIM volume filling factor is highly variable, and sensitive to the rate of ionizing photon production and ISM structure. The mean WIM volume filling factor rises to ~0.15 at |z|~1 kpc
    - Approximately half of ionizing photons are absorbed by gas and half by dust; the cumulative ionizing photon escape fraction is 1.1%.

- [Linear polarization in the nucleus of M87 at 7 mm and 1.3 cm](https://arxiv.org/abs/2006.07059)
    - VLBA观测:New images of the linear polarization substructure in the nuclear region are presented, characterized by a two-component pattern of polarized intensity and smooth rotation of the polarization plane around the 43 GHz core.
    - We find that this global polarization pattern remains stable on a time interval of 11 yr, while showing smaller month-scale variability.
    - the observed polarimetric pattern is associated with the magnetic structure in the confining magnetohydrodynamic wind, which also serves as the source of the observed Faraday rotation.

- [The Nature of 500 micron Risers I: SMA Observations](https://arxiv.org/abs/2006.07221)
    - We find that while lensing plays a role, at least 35% of the bright sources are likely to be multiple sources rather than the result of lensing. At fainter fluxes we find a blending rate comparable to, or greater than, the predicted 40%.
    - We determine far-IR luminosities and star formation rates for the non-multiple sources in our sample and conclude that, in the absence of strong lensing, our 500-risers are very luminous systems

- [Environments of dwarf galaxies with optical AGN characteristics](https://arxiv.org/abs/2006.07233)
    - This study finds no discernible differences in environment between AGN and non-AGN host dwarf galaxies and these results indicate that environment is not an important factor in triggering AGN activity in dwarf galaxies.
    - there are several mass-trends in emission line ratios and that the SDSS fiber covers galaxies non-uniformly with redshift. These biases should be accounted for in future work

- [Automated Measurement of Quasar Redshift with a Gaussian Process](https://arxiv.org/abs/2006.07343)
    - Our technique is an extension of an earlier Gaussian process method for detecting damped Lyman-alpha absorbers (DLAs) in quasar spectra with known redshifts.
    - Importantly our method produces a probabilistic density function for the quasar redshift, allowing quasar redshift uncertainty to be propagated to downstream users.

- [PyPopStar: A Python-Based Simple Stellar Population Synthesis Code for Star Clusters](https://arxiv.org/abs/2006.06691)
    - **Useful**
    - offers the user control of 13 input properties including (but not limited to) the Initial Mass Function, stellar multiplicity, extinction law, and the metallicity-dependent stellar evolution and atmosphere model grids used.
    - The user also has control over the Initial-Final Mass Relation in order to produce compact stellar remnants


----

### June 15

- [Quantifying the Line-of-Sight Halo Contribution to the Dark Matter Convergence Power Spectrum from Strong Gravitational Lenses](https://arxiv.org/abs/2006.07383)
    - We develop a formalism to calculate the effect of LOS halos as an effective convergence power spectrum.
    - By assuming that the perturbations due to the LOS halos are small, we show that they can be projected onto the main-lens plane as effective subhalos.
    - for the SLACS and BELLS lenses the interloper contribution dominates: fsub≳2% (4%) is needed for subhalos to dominate in SLACS (BELLS)is

- [Shapley Supercluster Survey: mapping the dark matter distribution](https://arxiv.org/abs/2006.08130)
    - 23 deg2 sky using gri VST images. overall matter distribution over a region containing 11 clusters at z∼0.048
    - The deeper r-band images have traced the five interacting clusters in the supercluster core as a single coherent structure, confirmed the presence of a filament extending North from the core

- [Diffuse Radio Sources in a Statistically Complete Sample of High Redshift Galaxy Clusters](https://arxiv.org/abs/2006.08494)
    - JVLA observations at L-band of the statistically complete sample of very X-ray luminous clusters from the Massive Cluster Survey (MACS) presented by Ebeling et al. (2010), and redshift range 0.3 - 0.5
    - Most clusters show evidence of emission in the radio regime.
    - Most of the brightest cluster galaxies (BCG) in relaxed clusters show radio emission with powers typical of FRII radio galaxies, and some are surrounded by a radio mini-halo.

- [The impact of line-of-sight structures on measuring H0 with strong Lensing time-delay](https://arxiv.org/abs/2006.08540)
    - we quantify the influence of additional structures along the line-of-sight by adopting realistic lightcones derived from the CosmoDC2 semi-analytical extra-galactic catalogue.
    - for realistic line-of-sight structures comprising many galaxies at different redshifts, this simple correction over-estimates the bias by a factor of approximately three.

- [A new approach to observational cosmology using the scattering transform](https://arxiv.org/abs/2006.08561)
    - **Interesting**
    - Parameter estimation with non-Gaussian stochastic fields is a common challenge in astrophysics and cosmology. In this paper we advocate performing this task using the scattering transform, a statistical tool rooted in the mathematical properties of convolutional neural nets
    - This estimator can characterize a complex field without explicitly computing higher-order statistics. It generates a compact set of coefficients which can be used as robust summary statistics for non-Gaussian information
    - 在convergence map宇宙学推断中比功率谱和peak counts表现好

- [Hunting for wandering massive black holes](https://arxiv.org/abs/2006.08203)
    - investigate low-density accretion flows onto massive black holes (BHs) with masses of ≳10^5 M⊙ orbiting around in the outskirts of their host galaxies
    - We find that when a wandering BH is fed with hot and diffuse plasma with density fluctuations, the mass accretion rate is limited at ∼10−20% of the canonical Bondi-Hoyle-Littleton rate
    - We further calculate radiation spectra from radiatively inefficient accretion flows onto the wandering BH and find that the spectra have a peak at the millimeter band. ALMA很适合


- [Quasar Sightline and Galaxy Evolution (QSAGE) survey -- II. Galaxy overdensities around UV luminous quasars at z=1-2](https://arxiv.org/abs/2006.07384)
    - UV brightest quasars at z=1-2 live in overdense environments.
    - One of the overdensities, PG0117+213 at z=1.50, has potentially 36 spectroscopically confirmed members, consisting of 19 with secure redshifts and 17 with single-line redshifts, within a cylinder of radius ~700 kpc. Its halo mass is estimated to be log (M/Msol)=14.7

- [Evolution of binary black holes in AGN accretion discs: Disc-binary interaction and gravitational wave emission](https://arxiv.org/abs/2006.07407)
    - We develop an idealised analytic model for the orbital evolution of BBHs in AGN accretion discs by combining the evolution equations of disc-binary interaction and GW inspiral.
    - By computing the evolution of the orbital eccentricity as a function of the GW frequency, we predict that most binaries in AGN discs should have significant residual eccentricities (e∼0.01−0.1), potentially detectable by LISA.

- [Galaxy and Mass Assembly (GAMA): Demonstrating the power of WISE in the study of Galaxy Groups to z<0.1](https://arxiv.org/abs/2006.07535)
    - **Relevant**
    - Ungrouped galaxies are largely unimodal in WISE color, the result of being dominated by star-forming, late-type galaxies. Grouped galaxies, however, show a clear bimodality in WISE color
    - We find that with increasing halo mass, the relative number of late-type systems on the SFMS decreases, with a corresponding increase in early-type.

- [Search for Optically Dark Infrared Galaxies without Counterparts of Subaru Hyper Suprime-Cam in the AKARI North Ecliptic Pole Wide Survey Field](https://arxiv.org/abs/2006.07577)
    - Using the AKARI infrared (IR) source catalog and HSC optical catalog, we select 583 objects that do not have HSC counterparts in the AKARI North Ecliptic Pole (NEP) wide survey field
    - The estimated redshifts of AKARI objects without HSC counterparts range up to z∼4, significantly higher than that of AKARI objects with HSC counterparts.

- [A massive mess: When a large dwarf and a Milky Way-like galaxy merge](https://arxiv.org/abs/2006.07620)
    - We confirm that Gaia-Enceladus probably fell in on a retrograde, 30∘ inclination orbit. We find that while 75% of the debris in our preferred simulation has large eccentricity (>0.8), roughly 9% has eccentricity smaller than 0.6.
    - Star particles lost early have large retrograde motions, and a subset of these have low eccentricity. Such stars would be expected to have lower metallicities as they stem from the outskirts of the satellite, and hence naively they could be confused with debris associated with a separate system.

- [The galaxy population within the virial radius of the Perseus cluster](https://arxiv.org/abs/2006.07631)
    - **Useful, Relevant**
    - We present a catalogue of 1294 galaxies. Morphological information was obtained for 90% of the galaxies from the `eyeball' inspection, partly supported by the surface brightness profile analysis

- [The influence of angular momentum and environment on the HI gas of late-type galaxies](https://arxiv.org/abs/2006.08103)
    - HI and angular momentum properties of a sample of 114 late-type galaxies 考虑重子质量-单位角动量关系
    - An unbroken power law of the form jb∝M_b^0.55±0.02 fits the data well
    - We find evidence that galaxies with close neighbours show a larger intrinsic scatter about the fatm−q relation compared to galaxies without close-neighbours. fatm是中性气体比例；q是气体稳定程度

- [Water megamaser emission in hard X-ray selected AGN](https://arxiv.org/abs/2006.08280)
    - We aim at characterizing the occurrence of water maser emission in an unbiased sample of AGN, investigating the relation with the X-ray properties and the possible favorable geometry needed to detect water maser.
    - We have searched for 22 GHz maser emission in a hard X-ray selected sample of AGN
    - The detection rate of water maser emission in the total sample is 15+/-3%, this fraction raises up to 19+/-5% for the complete sub-sample, especially if considering type 2 and Compton thick AGN.
    - These results demonstrate that the hard X-ray selection may significantly enhance the maser detection efficiency
    - 之前的探测率低可能是因为：an extreme luminous nuclear environment does not favour maser emission

- [Cold Molecular Gas and Free-Free Emission from Hot, Dust-Obscured Galaxies at z~3](https://arxiv.org/abs/2006.08400)
    - JVLA观测CO(1-0) lines in z>3 hot-DOGS.
    - We find that most of the 115 GHz rest-frame continuum is mostly due to synchrotron or free-free emission, with only a potentially small contribution from thermal emission.
    - We compare to the FIR-radio correlation, and find that at least half of the Hot DOGs in our sample are radio-quiet with respect to normal galaxies. These findings suggest that Hot DOGs have comparably less cold molecular gas than star-forming galaxies at lower, z∼ 2 redshifts, and are dominated by powerful, yet radio-quiet AGN.

- [Pairing of Massive Black Holes in Merger Galaxies Driven by Dynamical Friction](https://arxiv.org/abs/2006.08520)
    - The goal of this study is to determine how the properties of the merger remnant galaxy and the MBHs affect the likelihood and timescale for formation of a close MBH pair with separation of < 1 pc.
    - We find that the percentage for MBH pairing within a Hubble time is larger than 80% in remnant galaxies with a gas fraction < 20% and in galaxies hosting MBH pairs with total mass > 10^6 solar mass and mass ratios > 1/4.
    - In such galaxies, the MBHs with the shortest inspiral times, which are likely progenitors of coalescing MBHs, are either on circular prograde orbits or on very eccentric retrograde orbits

- [VLA imaging of the XMM-LSS / VIDEO deep field at 1-2 GHz](https://arxiv.org/abs/2006.08551)
    - We derive a catalogue containing 5,762 sources from the final mosaic. Sub-band imaging provides in-band spectral indices for 3,458 (60%) sources

- [An EAGLE's View of Ex-situ Galaxy Growth](https://arxiv.org/abs/2006.08590)
    - **Relevant, Important**
    - Our predictions are specifically tailored for direct testing with a new generation of observational techniques by calculating ex-situ fractions as functions of galaxy mass and morphological type, for a range of surface brightnesses.
    - finding that ex-situ fraction increases with stellar mass for central and satellite galaxies in a stellar mass range of 2×10^7 - 1.9×10^12 M⊙.
    - When categorising satellite galaxies by their parent group/cluster halo mass we find that the ex-situ fraction decreases with increasing parent halo mass at fixed galaxy mass.