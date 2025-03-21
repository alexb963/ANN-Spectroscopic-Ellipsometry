# ANN-Spectroscopic-Ellipsometry

The code for this project is done in Python version 3.12.7, Tensorflow version 2.18.0, and Keras version 3.7.0 on a Jupyter notebook. The programs can be accessed via a GitHub account. There are five different Jupyter notebooks as well as two folders. The folder labeled “Optical_Properties” contains the optical properties for soda-lime glass (SLG), silicon wafer1 (Si_JAW), native oxide1 (NTVE_JAW), and void while the folder labeled “Traditional_LSR_Data” that contains the experimental ellipsometric spectra from samples MV1519, MV1523, and MV1530 and the parameters determined from the traditional least-square regression. The notebook labeled “Tauc_and_Cody_Lorentz” contain the math used to generate the complex dielectric functions for the Tauc Lorentz and Cody Loretnz oscillators2 as well as the Bruggeman Effective medium approximation3. The notebook labeled “Simulated_Ellipsometric _Specta_Generator-CL” is used to generate Data Sets 1 - 3. The notebook labeled “ANN_Development” uses Data Sets 1 - 3 to train ANN1 - 4. The notebook labeled “ANN_ Evaluation” uses the trained versions of ANN1 - 4 to make predictions on simulated test data as well as the experimental ellipsometric spectra from samples MV1519, MV1523, and MV1530. The notebook also contains the code used to generate the figures presented in this work as well as some figures that were not presented. The notebook labeled “Functions” contains any other functions used in this work.
