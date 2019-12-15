# Masterthesis by Sabrina Meindlhumer
09/2019, Johannes Kepler University, Linz/Austria

The goal of this master's thesis was to develop a framework that would complement formerly established methods in dynamic force spectroscopy (DFS) data evaluation. To have a dataset on which this evaluation framework could be put to the test, an interaction study on C-reactive protein (CRP) and a monoclonal antibody (anti-CRP) was performed using an atomic force microscope (AFM).

The collected unbinding force data were analyzed with respect to their dependence on the loading rate with a few methods and theoretical models, most prominently Friddle and Bell-Evans model. The goal of this analysis is to extract characteristic parameters of the interaction, like the kinetic off-rate k_off.

The most important approach was based on binning of the data into a certain number of bins per logarithmic decade with respect to the loading rate. Doing so allows to perform an analysis of the force distribution functions calculated for the datapoints in the respective bins. These force distributions make it possible to identify individual populations within the data, which may correspond to multibonds or other types of interactions occurring within the system. For this purpose, Gaussian functions were fitted onto the bin-wise force distributions and interpreted as representing one population each.

The whole analysis comprises least-squares fitting of the original data, of the mean forces calculated for the bins and of the mean forces obtained for the isolated populations.

This method was implemented in a MATLAB-based framework that allows to perform similar analyses on other systems in the future. The framework was also tested on data recorded on another biological system (mesenchymal stem cells and a specific monoclonal antibody).
