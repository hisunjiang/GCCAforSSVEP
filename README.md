# GCCAforSSVEP
A generalized version of CCA for high performance SSVEP detection

# Brief description
This work is motivated by recented studies of Wei et al. [1] and Wong et al. [2]. In [1], a training data-drivem CCA (tdCCA) method is proposed and valitated to be superior than TRCA. While in [2], Wong et al. demonstrated that ultizing the prior knowledge from sine-cosine signal can significantly improve the performance of TRCA and CCA. We adopted the structure of tdCCA and added an additional variable set (composed of prefined sine-cosine signal) to the optimization process. Thus, the generalized version of CCA is utilized and the optimaized spatial filters are properly used for signal denoising. Study results indicated that the proposed method significantly outperformed TRCA as well as other CCA-based methods.
# Partial results 
![image](https://user-images.githubusercontent.com/30659685/109600871-dffa6680-7b58-11eb-9863-7cdbad360cea.png)
