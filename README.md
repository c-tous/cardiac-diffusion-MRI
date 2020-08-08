# cardiac-diffusion-MRI
A repository on diffusion weighted imaging (DWI) and diffusion tensor imaging (DTI) in the heart (myocardium). 

Please, cite:

"Ex vivo Magnetic Resonance Diffusion Weighted Imaging in Congenital Heart Disease, an Insight into the Microstructures of Tetralogy of Fallot, Biventricular and Univentricular Systemic Right Ventricle" (C Tous, T. Gentles, A. Young, B. Pontre, 2020), Journal of Cardiovascular Magnetic Resonance Imaging

This repository (will) contains:
- the sequences diagram, bmatrix, M0-M1-M2, velocity shift and Maxwell gradient moment of the Spin Echo monopolar, Spin Echo bipolar, Stimulated Echo Acquisition Mode monopolar, Twice refocused and Twice refocused adjusted
- the diffusion weighted images of the congenital heart disease (CHD) specimens presented in the article from C. Tous et al (2020). 
- the tractography of the CHD specimens presented in the article from C. Tous et al (2020). 
- the fitting model of the microstructure in the CHD specimens (HA, TA, E2A) from C. Tous et al (2020).
- the post processing code to analyse the cardiac diffusion tensor images. 

For detailed information on the CHD specimens, please refer to the publication C. Tous et al (2020) in JCMR

More about this repository: 

This repository contains the sequences diagram of the Spin Echo monopolar, Spin Echo bipolar, Stimulated Echo Acquisition Mode monopolar, Twice refocused and Twice refocused adjusted. In particular, the b-matrix from the integration of all the gradients in the twice refocused spin echo has not been specified in any previous papers. You will be able to generate each bmatrix, determine the zeroth moment, first moment and second moment, calculate the velocity shift and Maxwell gradient moment. Although the last and only detailed diffusion sequence diagram dates from 1993 (Mattiello et al), there was no interest from the main stream MRI journals to see theses detailed sequences published. However, we believe that new information on muscle architecture can be gained from valuable legacy specimens that exist in many teaching hospitals. Previous literature investigating fixed specimens in formalin have mainly dealt with the first year of fixation. There has been no DWI investigation of fixed tissues from longer storage, since previous studies were no able to get enough SNR in the short T2 specimens, especially at 3T on a clinical scanner (70 cm bore)

PS: 
Please be aware that the sequences, presented here, do not account for the gradient limit of your MRI scanner. You will break the body coil if you use the full gradient amplitude and a short TR. You will need to account for the cooling of your gradients. 
