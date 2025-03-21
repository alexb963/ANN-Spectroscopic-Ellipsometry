# ANN-Spectroscopic-Ellipsometry

The code for this project is done in Python version 3.12.7, Tensorflow version 2.18.0, and Keras version 3.7.0 on a Jupyter notebook. The programs can be accessed via a GitHub account. There are five different Jupyter notebooks as well as two folders. The folder labeled “Optical_Properties” contains the optical properties for soda-lime glass (SLG), silicon wafer[1] (Si_JAW), native oxide[1] (NTVE_JAW), and void while the folder labeled “Traditional_LSR_Data” that contains the experimental ellipsometric spectra from samples MV1519, MV1523, and MV1530 and the parameters determined from the traditional least-square regression. The notebook labeled “Tauc_and_Cody_Lorentz” contain the math used to generate the complex dielectric functions for the Tauc Lorentz and Cody Loretnz oscillators[2] as well as the Bruggeman Effective medium approximation[3]. The notebook labeled “Simulated_Ellipsometric _Specta_Generator-CL” is used to generate Data Sets 1 - 3. The notebook labeled “ANN_Development” uses Data Sets 1 - 3 to train ANN1 - 4. The notebook labeled “ANN_ Evaluation” uses the trained versions of ANN1 - 4 to make predictions on simulated test data as well as the experimental ellipsometric spectra from samples MV1519, MV1523, and MV1530. The notebook also contains the code used to generate the figures presented in this work as well as some figures that were not presented. The notebook labeled “Functions” contains any other functions used in this work. There are many instances in the program which reference directories of specific files or folders. The directories need to be updated for the code to function. The areas that need directories are marked with ‘XXXX’ as a placeholder. 





REFERENCES

(1) Herzinger, C.; Johs, B.; McGahan, W.; Woollam, J. A.; Paulson, W. Ellipsometric determination of optical constants for silicon and thermally grown silicon dioxide via a multi-sample, multi-wavelength, multi-angle investigation. Journal of Applied Physics 1998, 83 (6), 3323-3336.

(2) Ferlauto, A.; Ferreira, G.; Wronski, C.; Collins, R.; Deng, X.; Ganguly, G. Analytical model for the optical functions of amorphous semiconductors from the near-infrared to ultraviolet: Applications in thin film photovoltaics. Journal of Applied Physics 2002, 92 (5), 2424-2436.


(3) Aspnes, D.; Theeten, J.; Hottier, F. Investigation of effective-medium models of microscopic surface roughness by spectroscopic ellipsometry. Physical Review B 1979, 20 (8), 3292.

