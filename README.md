# Protocol-DWI-analysis

## 1. General Review
Assaf, Y., Johansen‐Berg, H., & Thiebaut de Schotten, M. (2019). The role of diffusion MRI in neuroscience. NMR in Biomedicine, 32(4), e3762.

Jbabdi, S., Sotiropoulos, S. N., Haber, S. N., Van Essen, D. C., & Behrens, T. E. (2015). Measuring macroscopic brain connections in vivo. Nature Neuroscience, 18(11), 1546-1555.

Le Bihan, D., & Johansen-Berg, H. (2012). Diffusion MRI at 25: exploring brain tissue structure and function. Neuroimage, 61(2), 324-341.

Le Bihan, D. (2003). Looking into the functional architecture of the brain with diffusion MRI. Nature Reviews Neuroscience, 4(6), 469-480.

Le Bihan, D., & Breton, E. (1985). Imagerie de diffusion in vivo par résonance magnétique nucléaire. Comptes rendus de l'Académie des sciences. Série 2, Mécanique, Physique, Chimie, Sciences de l'univers, Sciences de la Terre, 301(15), 1109-1112.

## 2. Voxel-wise Properties

### (1) Indices

**Fractional Anisotropy (FA)**: (mm²/s)

is a measure of the degree of anisotropy, or directional dependence, of a diffusion process in a biological tissue. 0 indicates completely isotropic diffusion while 1 indicates completely anisotropic diffusion, of which the white matter should have ***larger*** FA than the grey matter.

**Axial Diffusivity (AD)**: “λ₁”; (mm²/s)

is the eigenvalue of the primary diffusion direction derived from DTI in a tissue, which measures the rate at which water molecules diffuse along the primary diffusion direction in a tissue. 

**Radial Diffusivity (RD)**: “λ₂”; (mm²/s)

is the eigenvalue of the perpendicular directions to the primary diffusion direction derived from DTI in a tissue, which reflects the degree to which diffusion is unrestricted in the tissue perpendicular to the primary diffusion direction. 

**Mean Diffusivity (MD)**: “λ̄”; (mm²/s)

is the average of the three eigenvalues derived from DTI, which represents the degree of diffusional restriction in three orthogonal directions in a tissue.  

**Orientation Dispersion (OD)**: 

is a measure of neurite orientation dispersion. 0 means more coherent with no dispersion while 1 means more dispersion. The white matter should have ***smaller*** values than the grey matter.

**Intra-Cellular Volume Fraction (ICVF)**:

is a measure of neurite density. 0 means no neurite while 1 means dense neurite. The white matter should have ***larger*** values than the grey matter.

**ISOtropic Volume Fraction (ISOVF)**

### (2) Models

Tournier, J. D., Mori, S., & Leemans, A. (2011). Diffusion tensor imaging and beyond. Magnetic resonance in medicine, 65(6), 1532.


- ### Model-free (diffusion Orientation distribution function) 

#### DSI (Diffusion Spectrum Imaging)
Wedeen, V. J., Hagmann, P., Tseng, W. Y. I., Reese, T. G., & Weisskoff, R. M. (2005). Mapping complex tissue architecture with diffusion spectrum magnetic resonance imaging. Magnetic resonance in medicine, 54(6), 1377-1386.

#### QBI (Q-Ball Imaging)
Tuch, D. S. (2004). Q‐ball imaging. Magnetic Resonance in Medicine, 52(6), 1358-1372.

#### GQI
Yeh, F. C., Wedeen, V. J., & Tseng, W. Y. I. (2010). Generalized q-sampling imaging. IEEE transactions on medical imaging, 29(9), 1626-1635.

 - ### Model-based (fiber ODF compartment models)

#### DTI (Diffusion Tensor Imaging)
   
Soares, J. M., Marques, P., Alves, V., & Sousa, N. (2013). A hitchhiker's guide to diffusion tensor imaging. Frontiers in neuroscience, 7, 31.

[Pierpaoli, C., & Basser, P. J. (1996). Toward a quantitative assessment of diffusion anisotropy. Magnetic Resonance in Medicine, 36(6), 893-906.]

Basser, P. J., & Pierpaoli, C. (1996). Microstructural and physiological features of tissues elucidated by quantitative-diffusion-tensor MRI. Journal of magnetic resonance. Series B, 111(3), 209-219. (FA proposed)

[Basser, P. J., Mattiello, J., & LeBihan, D. (1994). Estimation of the effective self-diffusion tensor from the NMR spin echo. Journal of Magnetic Resonance, Series B, 103(3), 247-254.]

Basser, P. J., Mattiello, J., & LeBihan, D. (1994). MR diffusion tensor spectroscopy and imaging. Biophysical journal, 66(1), 259-267.

#### DKI (Diffusion Kurtosis Imaging)
Jensen, J. H., Helpern, J. A., Ramani, A., Lu, H., & Kaczynski, K. (2005). Diffusional kurtosis imaging: the quantification of non‐gaussian water diffusion by means of magnetic resonance imaging. Magnetic Resonance in Medicine, 53(6), 1432-1440.

#### NODDI (Neurite Orientation Dispersion and Density Imaging) 
Zhang, H., Schneider, T., Wheeler-Kingshott, C. A., & Alexander, D. C. (2012). NODDI: practical in vivo neurite orientation dispersion and density imaging of the human brain. Neuroimage, 61(4), 1000-1016.

#### Ball-stick
Behrens, T. E., Woolrich, M. W., Jenkinson, M., Johansen‐Berg, H., Nunes, R. G., Clare, S., ... & Smith, S. M. (2003). Characterization and propagation of uncertainty in diffusion‐weighted MR imaging. Magnetic Resonance in Medicine, 50(5), 1077-1088.

##### CHARMED
Assaf, Y., & Basser, P. J. (2005). Composite hindered and restricted model of diffusion (CHARMED) MR imaging of the human brain. Neuroimage, 27(1), 48-58.

Assaf, Y., Freidlin, R. Z., Rohde, G. K., & Basser, P. J. (2004). New modeling and experimental framework to characterize hindered and restricted water diffusion in brain white matter. Magnetic Resonance in Medicine, 52(5), 965-978.

##### AxCaliber
Assaf, Y., Blumenfeld‐Katzir, T., Yovel, Y., & Basser, P. J. (2008). AxCaliber: a method for measuring axon diameter distribution from diffusion MRI. Magnetic Resonance in Medicine, 59(6), 1347-1354.

 - ### Spherical Deconvolution
Dell'Acqua, F., & Tournier, J. D. (2019). Modelling white matter with spherical deconvolution: How and why?. NMR in Biomedicine, 32(4), e3945.

Tournier, J. D., Calamante, F., Gadian, D. G., & Connelly, A. (2004). Direct estimation of the fiber orientation density function from diffusion-weighted MRI data using spherical deconvolution. Neuroimage, 23(3), 1176-1185.

#### MSMT-CSD (Multi-Shell, Multi-Tissue CSD)
Jeurissen, B., Tournier, J. D., Dhollander, T., Connelly, A., & Sijbers, J. (2014). Multi-tissue constrained spherical deconvolution for improved analysis of multi-shell diffusion MRI data. NeuroImage, 103, 411-426.

#### CSD (Constrained Spherical Deconvolution)
Tournier, J. D., Calamante, F., & Connelly, A. (2007). Robust determination of the fibre orientation distribution in diffusion MRI: non-negativity constrained super-resolved spherical deconvolution. Neuroimage, 35(4), 1459-1472.

## 3. Fiber Tracking

Jeurissen, B., Descoteaux, M., Mori, S., & Leemans, A. (2019). Diffusion MRI fiber tractography of the brain. NMR in Biomedicine, 32(4), e3785.

Mori, S., & Van Zijl, P. C. (2002). Fiber tracking: principles and strategies–a technical review. NMR in Biomedicine, 15(7‐8), 468-480.

### (1) Major tracts

Bullock, D. N., Hayday, E. A., Grier, M. D., Tang, W., Pestilli, F., & Heilbronner, S. R. (2022). A taxonomy of the brain’s white matter: twenty-one major tracts for the 21st century. Cerebral Cortex, 32(20), 4524-4548.

Yeh, F. C. (2022). Population-based tract-to-region connectome of the human brain and its hierarchical topology. Nature communications, 13(1), 4933.

- ### Commissural pathways:
  #### corpus callosum
  #### anterior commissure
  #### posterior commissure
- ### Association pathways:
  #### arcuate fasciculus (AF)
  #### uncinate fasciculus (UF)
  #### cingulum
  #### inferior fronto-occipital fasciculus (IFOF)
  #### inferior longitudinal fasciculus (ILF); middle longitudinal fasciculus (MdLF); superior longitudinal fasciculus (SLF)
- ### Projection pathways:
  #### optic radiation
  #### corticospinal tract
  #### fornix
- ### Cerebellum pathways

### (2) Methods
Sarwar, T., Ramamohanarao, K., & Zalesky, A. (2019). Mapping connectomes with diffusion MRI: deterministic or probabilistic tractography? Magnetic resonance in medicine, 81(2), 1368-1384.

Maier-Hein, K. H., Neher, P. F., Houde, J. C., Côté, M. A., Garyfallidis, E., Zhong, J., ... & Descoteaux, M. (2017). The challenge of mapping the human connectome based on diffusion tractography. Nature communications, 8(1), 1349.

Bastiani, M., Shah, N. J., Goebel, R., & Roebroeck, A. (2012). Human cortical connectome reconstruction from diffusion weighted MRI: the effect of tractography algorithm. Neuroimage, 62(3), 1732-1749.

Tournier, J. D., Calamante, F., & Connelly, A. (2007). Robust determination of the fibre orientation distribution in diffusion MRI: non-negativity constrained super-resolved spherical deconvolution. Neuroimage, 35(4), 1459-1472.

- ### Deterministic  
Basser, P. J., Pajevic, S., Pierpaoli, C., Duda, J., & Aldroubi, A. (2000). In vivo fiber tractography using DT‐MRI data. Magnetic resonance in medicine, 44(4), 625-632.

Conturo, T. E., Lori, N. F., Cull, T. S., Akbudak, E., Snyder, A. Z., Shimony, J. S., ... & Raichle, M. E. (1999). Tracking neuronal fiber pathways in the living human brain. Proceedings of the National Academy of Sciences, 96(18), 10422-10427.

Mori, S., Crain, B. J., Chacko, V. P., & Van Zijl, P. C. (1999). Three‐dimensional tracking of axonal projections in the brain by magnetic resonance imaging. Annals of Neurology, 45(2), 265-269.

- ### Probabilistic
Sherbondy, A. J., Dougherty, R. F., Ben-Shachar, M., Napel, S., & Wandell, B. A. (2008). ConTrack: finding the most likely pathways between brain regions using diffusion tractography. Journal of Vision, 8(9), 15-15.

Behrens, T. E., Berg, H. J., Jbabdi, S., Rushworth, M. F., & Woolrich, M. W. (2007). Probabilistic diffusion tractography with multiple fiber orientations: What can we gain? Neuroimage, 34(1), 144-155.

Parker, G. J., Haroon, H. A., & Wheeler‐Kingshott, C. A. (2003). A framework for a streamline‐based probabilistic index of connectivity (PICo) using a structural interpretation of MRI diffusion measurements. Journal of Magnetic Resonance Imaging, 18(2), 242-254.

- ### Global
Jbabdi, S., Woolrich, M. W., Andersson, J. L., & Behrens, T. E. J. (2007). A Bayesian framework for global tractography. Neuroimage, 37(1), 116-129.

Iturria-Medina, Y., Canales-Rodríguez, E. J., Melie-García, L., Valdés-Hernández, P. A., Martínez-Montes, E., Alemán-Gómez, Y., & Sánchez-Bornot, J. M. (2007). Characterizing brain anatomical connections using diffusion weighted MRI and graph theory. Neuroimage, 36(3), 645-660.

## 4. Softwares

Smith, S. M., Jenkinson, M., Woolrich, M. W., Beckmann, C. F., Behrens, T. E., Johansen-Berg, H., ... & Matthews, P. M. (2004). Advances in functional and structural MR image analysis and implementation as ***FSL***. Neuroimage, 23, S208-S219.

Cieslak, M., Cook, P. A., He, X., Yeh, F. C., Dhollander, T., Adebimpe, A., ... & Satterthwaite, T. D. (2021). ***QSIPrep***: an integrative platform for preprocessing and reconstructing diffusion MRI data. Nature Methods, 18(7), 775-778.

Tournier, J. D., Smith, R., Raffelt, D., Tabbara, R., Dhollander, T., Pietsch, M., ... & Connelly, A. (2019). ***MRtrix3***: A fast, flexible and open software framework for medical image processing and visualisation. Neuroimage, 202, 116137.

Garyfallidis, E., Brett, M., Amirbekian, B., Rokem, A., Van Der Walt, S., Descoteaux, M., ... & Dipy Contributors. (2014). ***Dipy***, a library for the analysis of diffusion MRI data. Frontiers in neuroinformatics, 8, 8.

Yeh, F. C., Wedeen, V. J., & Tseng, W. Y. I. (2010). ***DSI studio*** Generalized q-sampling imaging. IEEE Transactions on Medical Imaging, 29(9), 1626
