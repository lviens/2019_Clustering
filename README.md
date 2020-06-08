# Two-step clustering method to improve offshore-onshore deconvolution functions from the ambient seismic field

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

The 2nd release of the code is sligthly different from what is presented in the current EarthArXiv pre-print. The EarthArXiv pre-print will be updated soon 

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

* We developped a method to improve the retrieval of clear deconvolution functions calculated from the ambient seismic field using unsupervised learning. Details about the method can be found in Viens and Iwata (Submitted to JGR). EarthArXiv pre-print available [here](https://eartharxiv.org/8ba5p/) 


* The deconvolution functions in the paper were computed using the deconvolution_stab function available [here](https://github.com/lviens/2017_GJI/blob/master/Codes/Functions_GJI_2017.py).

* The Hi-net and DONET 1 data are available [here](http://www.hinet.bosai.go.jp).

* The **Code** folder contains:
  - **Reproduce_Fig_1_2.py** to reproduce Figures 1 and 2 of the paper
  - **Reproduce_Fig_4_5.py** to reproduce Figures 4 and 5 of the paper (data download required, see below)
  - **Function_clustering_DFs.py**, the main function to perform the clustering (used by the two codes above).

* The **Data** folder is empty, but the data to reproduce Figures 4 and 5 can be downloaded [here](https://drive.google.com/file/d/1wbM-cN4gQ-MRhLOQaiXcHiXZ5Z5OOEsI/view?usp=sharing) and need to be copied in the **Data** folder.

* The **Figures** folder contains the four figures generated by the two codes


