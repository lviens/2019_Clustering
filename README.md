# Two-step clustering method to improve offshore-onshore deconvolution functions from the ambient seismic field


* We developped a method based on unsupervised learning to improve the retrieval of deconvolution functions calculated from the ambient seismic field.

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

- Update - 21/07/2020: The paper has been accepted in JGR ([The accepted paper is available on EarthArXiv](https://eartharxiv.org/8ba5p/)).
- Update - 03/06/2020: 2nd release of the code.
- 06/03/2020: 1st release of the code

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

1) This repository contains data and python codes to reproduce some of the Figures of Viens and Iwata (2020, Accepted in JGR):
  * The **Codes** folder contains:
    - **Reproduce_Fig_1_2.py** to reproduce Figures 1 and 2 of the paper
    - **Reproduce_Fig_4_5.py** to reproduce Figures 4 and 5 of the paper (data download required, see below)
    - **Function_clustering_DFs.py**, the main function to perform the clustering (used by the two codes above).

  * The **Data** folder is empty, but the data to reproduce Figures 4 and 5 can be downloaded [here](https://drive.google.com/file/d/1wbM-cN4gQ-MRhLOQaiXcHiXZ5Z5OOEsI/view?usp=sharing) and need to be copied in the **Data** folder.

  * The **Figures** folder contains the four figures generated by the two codes.

2) **Additional info**:
  - The deconvolution functions in the paper are computed using the deconvolution_stab function available [here](https://github.com/lviens/2017_GJI/blob/master/Codes/Functions_GJI_2017.py).

  - The raw Hi-net and DONET 1 data can be downloaded [here](http://www.hinet.bosai.go.jp).
