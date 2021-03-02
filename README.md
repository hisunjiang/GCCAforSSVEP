# GCCAforSSVEP
A generalized version of CCA for high performance SSVEP detection

# Brief description
This work is motivated by recented studies of Wei et al. [1] and Wong et al. [2]. In [1], a training data-drivem CCA (tdCCA) method is proposed and valitated to be superior than TRCA. While in [2], Wong et al. demonstrated that ultizing the prior knowledge from sine-cosine signal can significantly improve the performance of TRCA and CCA. We adopted the structure of tdCCA and added an additional variable set (composed of prefined sine-cosine signal) to the optimization process. Thus, the generalized version of CCA is utilized and the optimaized spatial filters are properly used for signal denoising. Study results indicated that the proposed method significantly outperformed TRCA as well as other CCA-based methods.
# Partial results 
![image](https://user-images.githubusercontent.com/30659685/109600871-dffa6680-7b58-11eb-9863-7cdbad360cea.png)
# References
[1]	Q. Wei, et al., “A Training Data-Driven Canonical Correlation Analysis Algorithm for Designing Spatial Filters to Enhance Performance of SSVEP-Based BCIs,” Int. J. Neural Syst., vol. 30, no. 5, pp. 2050020, May, 2020.
[2]	C. M. Wong, et al., “Spatial filtering in SSVEP-based BCIs: Unified framework and new improvements,” IEEE Trans. Biomed. Eng., vol. 67, no. 11, pp. 3057-3072, Feb 21, 2020.
# Citation
Q. sun et al., "Improving SSVEP Identification Accuracy via Generalized Canonical Correlation Analysis", in 10th International IEEE/EMBS Conference on Neural Engineering (NER), 2021, accepted. 
