# cardiac-diffusion-MRI
Diffusion weighted imaging (DWI) and diffusion tensor imaging (DTI) in the heart (myocardium)

"Ex vivo Magnetic Resonance Diffusion Weighted Imaging in Congenital Heart Disease, an Insight into the Microstructures of Tetralogy of Fallot, Biventricular and Univentricular Systemic Right Ventricle" (C Tous, T. Gentles, A. Young, B. Pontre, 2020), Journal of Cardiovascular Magnetic Resonance Imaging

This repository contains the sequences diagram of the spin echo monopolar, spin echo bipolar, Stimulated Echo Acquisition Mode monopolar, Twice refocused and Twice refocused adjusted. In particular, the b-matrix from the integration of all the gradients in the twice refocused spin echo has not been specified in any previous papers. You will be able to generate each bmatrix, determine the zeroth moment, first moment and second moment, calculate the velocity shift and Maxwell gradient moment. Although the last and only detailed diffusion sequence diagram dates from 1993 (Mattiello et al), there was no interest from the main stream MRI journals to see the comparison of theses sequences published. However, we believe that new information on muscle architecture can be gained from valuable legacy specimens that exist in many teaching hospitals. Previous literature investigating fixed specimens in formalin have mainly dealt with the first year of fixation. There has been no DWI investigation of fixed tissues from longer storage, since previous studies were no able to get enough SNR in the short T2 specimens, especially at 3T on a clinical scanner (70 cm bore). 

This repository (will) contains:
- the diffusion weighted images of the specimens. 
- the tractography of the congenital heart disease (CHD) specimens investigated presented in the article from C. Tous et al (2020). 
- the fitting model of the microstructure in the studied CHD specimens (HA, TA, E2A) from Tous et al (2020).
- the post processing code to analyse cardiac diffusion tensor images. 

For detailes information on the CHD specimens, please refers to the publication C. Tous et al (2020) in JCMR
