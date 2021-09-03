# Poster abstract list


## ID 71

**Title**: An extensive grid of synthetic spectral energy distributions for Seyfert 2 galaxies

**Author**: A. R. Chougule

**Abstract**: Extragalactic astrophysics researchers widely use spectral population synthesis codes to estimate the physical properties of galaxies. We created an extensive grid of realistic synthetic spectral energy distributions (SED) for Seyfert 2 narrow-line emission models specially tailored for benchmark tests, which will help quantify the accuracy in recovering the physical properties of Seyfert 2s from these codes.

Firstly, we produced single power-law templates as a fiducial mock sample to represent the primary source emission. This approach is standard in the literature. These models have various ranges in the parameters with single power-law indexes going from -2 to +1, Hydrogen number densities from 10 to 10^6 cm^−3, and six solar metallicities. To reproduce the observed properties of local Seyfert 2 galaxies, only a limited set of these parameters are valid. However, we kept the full range of the AGN template dataset parameters to account for reproducing the observed characteristics of intermediate to high redshift Seyfert 2s. We generated a total number of single power-law models of the order of 30000 models, with approximately 15% of these models being compatible with observed Seyfert 2 properties in the local universe.

Our main objective is to create a reference grid of Seyfert 2 narrow-line emission models using more realistic incident radiation field models. Therefore, for that purpose, we used the SKIRTOR models (Stalevski et al., 2012; Stalevski et al., 2016) as the primary source of emission from the AGN and produced AGN SEDs with emission lines calculated self-consistently. These models correspond to AGNs having a two-phase medium dust distribution in the torus – with a large number of high-density clumps embedded in a smooth, dusty component of low density. In addition, we account for the anisotropy of the accretion disk due to its projected area and limb darkening effect. We also include the impact of polar dust extinction and re-emission in our models. This strategy allowed us to develop a standalone AGN module primarily built from scratch in Python3 to compute the incident radiation field of AGNs. Furthermore, this module, combined with a photoionisation code, allows us to evaluate the corresponding nebular emission, i.e. continuum and lines in galaxies.

Finally, we used these mock datasets to generate realistic observations of AGNs across distinct redshift slices from 0.5 to 2.5. We passed the synthetic spectra through an in-house pipeline to simulate several millions of VLT/MOONS observations, which will be beneficial to benchmark different spectral synthesis codes. In addition, our results will provide a comprehensive framework to identify active galaxies in observations, i.e. detectability of AGNs at intermediate to higher redshifts. Our work has not only furnished a huge, distinct, diverse set of Seyfert 2 model reference grids but also helps in planning the VLT/MOONS future observations.



## ID 3

**Title**: Asteroid astrometry by stellar occultations: statistics on accuracy from orbital fitting

**Author**: J. F. Ferreira

**Abstract**: Stellar occultations by small bodies of the Solar System are a powerful way of investigating physical properties of objects that are in general too far and small to offer details at telescopes on Earth.
Revived by the publication of the Gaia data releases, this technique permits not only the determination of asteroid size and shape, but also the retrieval of additional very accurate astrometry, with a possible relevant impact on the study of dynamical properties. In previous works, we presented the impact of the Gaia Data Release 1 on the precision of occultation astrometry, and the possible performances of a single telescope used to systematically collect asteroid astrometry.
In recent times, a new error model for occultation astrometry was also implemented to better describe the uncertainties specific to this technique, and the data reduction was refined.
We explore in more details the improvement in performance brought by Gaia DR2 and EDR3, exploited jointly to the new occultation error model and the new astrometry. Our goal is to verify that the extreme quality of DR2, in particular, brings a sensible progress in the exploitation of occultation astrometry.
We proceed by accurate orbit computation of occultation data, alone or joined to the other available ground-based observations.
We find that Gaia DR2 brings a noticeable improvement to the accuracy of occultation data. This is particularly visible when occultations alone are used, resulting in very good orbits for a large fraction of objects.
The joint use of archival data and occultations remains more challenging as the higher uncertainties and systematic errors of existing data have the tendency to deteriorate the results obtained by occultations alone.




## ID 8

**Title**: A reanalysis of ISO-SWS Jupiter observations: first results

**Author**: J. L. F. Ribeiro

**Abstract**: 	Determining the abundances of chemicals species and their isotopic ratios is fundamental to understand how and when the planets formed, in what conditions and what processes happen in their atmosphere. Jupiter still has some unanswered questions in this regard. The apparent low-temperature origin of the elements that formed the planet, the detailed meteorological processes that happen in its atmosphere remain largely unknown and the chemistry responsible for the colours of clouds of Jupiter is one of its oldest mysteries (Taylor et al.). With this work, we hope to contribute to the progress of unravelling some of these questions.
	We used the observations of Jupiter from the ESA mission Infrared Space Observatory (ISO) (Kessler et al. 1996) in the 793.65-3125 cm-1 (3.2-12.6 µm) region using the Short-Wave Spectrometer (SWS) (de Graauw et al., 1996). Our work is focused on the 793.65-1492.54 cm-1 (6.7-12.6 µm) region of the spectrum. Even though this data set is old, it was an important step in the study of Jupiter’s atmosphere and with the advancements in atmospheric models and line data, we argue that it warrants a revisit and reanalysis.
	Firstly, we used the NEMESIS radiative transfer suite (Irwin et al. 2008) to reproduce the results from Encrenaz et al. 1999 as a way to verify the validity of our method. This study is done using the CIRS NEMESIS template as a base adapted to the ISO-SWS data.  We used correlated k-tables compiled for NH3, PH3, 12CH3D, 12CH4, 13CH4, C2H2, C2H6, CH3Br, CH3OH, HCOOH and SF6, with our results showing good agreement. 
	Having verified our method, we present here our first results of the study of abundances of 12CH3D, 12CH4, 13CH4, C2H2 and C2H6 of Jupiter’s atmosphere as well as our initial study of the pressure-temperature profile of Jupiter. We use the NEMESIS suite to determine the abundances as a function of altitude and retrieve the pressure-temperature profile. We compare our results with the profiles and abundances from Neimann et al. and Fletcher et al. 2016 with the aim to constrain the number of possible best fit profiles.
	We also present our initial study the H/D and 12C/13C isotopic ratio of the Jovian atmosphere from the abundances of 12CH3D, 13CH4 and 12CH4 following the methodology from Fouchet et al. 2000.
	Despite the ISO-SWS data used being global, with this preliminary work we hope to further advance the knowledge about the chemical processes that happen in Jupiter, as well as the chemical and temperature vertical distribution. As future work, we expect to extend our frequency domain to the range of ISO/SWS observations and study the 15N/14N ratio.


References
	•	de Graauw et al., Observing with the ISO short-wavelength spectrometer, A&A 315, L49-L54, 1996
	•	Encrenaz et al., The atmospheric composition and structure of Jupiter and Saturn form ISO observations: a preliminary review, Planetary and Space Science 47, 1225-1242, 1999
	•	Fletcher et al., Mid-infrared mapping of Jupiter’s temperatures, aerosol opacity and chemical distributions with IRTF/TEXES, Icarus 278, 128–161, 2016
	•	Fouchet et al., ISO-SWS Observations of Jupiter: Measurement of the Ammonia Tropospheric Profile and of the 15N/14N Isotopic Ratio, Icarus 143, 223–243, 2000
	•	Irwin et al., The NEMESIS planetary atmosphere radiative transfer and retrieval tool, Journal of Quantitative Spectroscopy & Radiative Transfer 109, 1136–1150, 2008
	•	Kessler et al., The Infrared Space Observatory (ISO) mission, A&A 315, L27, 1996
	•	Neimann et al., The composition of the Jovian atmosphere as determined by the Galileo probe mass spectrometer, Journal of Geophysical Research Atmospheres 103(E10):22831-45, 1998
	•	Taylor et al., Jupiter, The Planet, Satellites and Magnetosphere, Ch.4, Cambridge Planetary Science, Eds. Bagenal, Dowling, McKinnon, 2006


Acknowledgements
	We acknowledge support from the Portuguese Fundação Para a Ciência e a Tecnologia (ref. PTDC/FIS-AST/29942/2017) through national funds and by FEDER through COMPETE 2020 (ref. POCI-01-0145 FEDER-007672).




## ID 19

**Title**: Host galaxy FORS2 polarization

**Author**: J. Rino-Silvestre

**Abstract**: Dust grains are key ingredients in understanding the interstellar medium (ISM) and the largest effects of dust on astronomical observations, the extinction of light in the line of sight and the wavelength dependent reddening it causes, both affecting distance measurements for cosmology when using extragalactic sources such as supernovae. Size, shape and distribution of the dust grains may also polarize light as it traverses the ISM. A comprehensive galaxy polarization study is thus justified.
In this talk I will describe the reduction steps undertaken and how simply switching the Stoke parameter calculation method yields more reliable and less biased polarimetry. Finally, preliminary multi-band polarization maps of an ensemble of galaxies observed with VLT's FORS2 are shown.



## ID 68

**Title**: The cosmological constant in voids

**Author**: M. A. Botas

**Abstract**: Astronomical observations reveal the existence of large regions of both concentration of matter, and nearly empty space populated by small amounts of cosmic structures. The latter are often designated as voids in the Universe, exactly because they are vast areas that contain very few or no galaxies, in comparison to commonly observed dense structures. They are regions characterized by having less than one tenth of the Universe's average density, which indicates the significant absence of matter. Voids are comprised mostly of invisible matter detected through gravitational effects, possibly being influenced by dark energy. In sum, they are important astrophysical structures whose dynamics aren't as well known as, for example, that of over-dense structures. And in addition they may provide information about the dark components of the universe without the local contamination by matter.

In this poster, we report  on a study of the conditions for the existence of voids, and we claim that the presence of a cosmological constant plays a significant role in the process of avoiding the collapse of matter into the empty region. We adopt  a Newtonian approach, first,  and subsequently we  build a “swiss cheese” model based on the theory of General Relativity to assess the role of a cosmological constant in providing appropriate conditions for the stability of voids. By the same token we argue that observations of the parameters characterizing voids may conversely give information about the cosmological constant.




## ID 90

**Title**: New numerical approaches to test the cosmological principle with the Euclid Mission

**Author**: S. Nóbrega

**Abstract**: The cosmological principle, which states that the Universe is homogeneous and isotropic, is the basis of modern cosmology. The upcoming ESA/Euclid satellite mission will test this paradigm over a wide range of scales allowing us to assess whether the non-homogeneous Lemaitre-Tolman-Bondi (LTB) models should be considered to accurately describe observations locally and at intermediate cosmological scales. 
The Euclid survey is expected to reveal/confirm more than 40 thousand new clusters in the optical and infrared bands, which represents a new era for cluster cosmology as well as for understanding the physical processes that govern the evolution of these structures. This project proposes to address the problem of modeling the galaxy cluster population in the context of LTB models, and the development of new numerical tools that may be used to provide ways of confronting model predictions with observations from galaxy surveys (e.g. Euclid) and the CMB (such as Planck).
Our first objective is to modify the galaxy cluster component of Planck Sky Model (PSM) to a LTB framework. We will extend this software to predict catalogues with optical cluster observables, such as cluster richness, and integrated mass maps that may be used to study model signatures and galaxy surveys - CMB/SZ (eg Euclid - Planck) correlations. The study proposed in this project is timely and innovative. This is the first time the galaxy cluster population will be modelled in the LTB context with a set of new tools predicting CMB/SZ and galaxy survey observables in a consistent way at the beginning of a new era for cluster cosmology with the Euclid satellite.



## ID 61

**Title**: Cosmology in scalar-tensor f(R,T) gravity

**Author**: T. Gonçalves

**Abstract**: We apply cosmological reconstruction methods to f(R,T) modified gravity, in its recently developed scalar-tensor representation. We do this analysis assuming a perfect fluid in a Friedmann-Lemaı̂tre-Robsertson-Walker (FLRW) universe. Solutions with general scale factor, curvature parameter and equation of state are found for the energy density, pressure, and one of the dynamical fields of the scalar-tensor representation. We then apply three particular forms of the scale factor: an exponential expansion (in analogy with the de Sitter solution); and two types of power-law expansion (radiation domination and matter domination). This allows us to find, in each particular case, a complete solution. We do so for each of the three values of the curvature parameter, and with three different values of the equation of state corresponding, in general relativity, to the equation of state of a cosmological constant, of matter and of radiation.



## ID 49

**Title**: Terrestrial planets: they are all made of star stuff

**Author**: V. Adibekyan

**Abstract**: Young stars and planets both grow by accreting material from the proto-stellar disks. Planetary structure and formation models assume a common origin of the building blocks, yet, thus far, there is no direct observational evidence correlating the composition of rocky planets to their host stars. Here we present evidence of a tight chemical link between rocky planets and their host stars. The iron-mass fraction of the most precisely characterized rocky planets is compared to that of their building blocks, as inferred from the atmospheric composition of their host stars. We find a clear and statistically significant correlation between the two. Our results explain the deviations from the Earth-like densities of planets which have been previously considered as anomalous. We also find that on average the iron-mass fraction of planets is higher than that of the primordial iron content in the planet building blocks, owing to the disk-chemistry and planet formation processes. Finally, our results provide some hints that the giant impact alone is not responsible for the high-densities of super-Mercuries. We conclude that rocky planet composition depends on the chemical composition of the proto-planetary disk and contains signatures about planet formation processes.



## ID 70

**Title**: Large Scale Structure Tessellation Statistics as a probe of Cosmology

**Author**: A. G. M. Guerreiro

**Abstract**: The spatial and angular distribution of galaxies and galaxy clusters are sensitive probes of Cosmology and large scale structure formation mechanisms. These probes involve, for example, the application of estimators of spatial/angular N-point correlations (and their fourier space/spherical harmonics counterparts) of sources to constrain theory parameters. 
Here we investigate the tessellation patterns of galaxies and galaxy clusters in simulations of future galaxy surveys (e.g. the Euclid mission survey) and observations (e.g. SDSS surveys), and characterize the dependence of their tessellation statistics with redshift and Cosmology.


