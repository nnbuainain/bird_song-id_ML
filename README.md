# Testing Machine Learning and Deep Learning to Identify birds by song

<p align="center"> 
  <img src="https://github.com/nnbuainain/bird_song-id_ML/blob/main/image_bird.png?raw=true" width="300" class="center"/>
  <img src="https://github.com/nnbuainain/bird_song-id_ML/blob/main/pca_plot.png?raw=true" width="350" class="center"/> 
</p>

## Goals
In this project me and Maura Costa (https://github.com/Mauregina) used different data processing and machine learning methods including supervised and non-supervised algorithms to try to distinguish genetically differentiated birds by their songs.

## Tools
sklearn, keras, autokeras, autosklearn, pandas, numpy, plotly, and few other algorithms.
Methods/models tested: Kmeans, PCA, Decision Tree, Random Forest, Support Vector Machine (SVM), Neural Network, and others tested with automated ML

** Output models can be found in the "models" directory, except for the automated deeplearning results which are in "structure_data_classifier"

## Main conclusion
* Our best models had over 90% of accuracy and were capable to distinguish some groups of birds that were not distinguished by traditional methods (human hearing and more classic statistics). The most recent genetic groups could not be distinguished, possibly because they have not yet evolved different songs. 


## Data

The original data comes from a previous publication of mine and it is accessible here:

Buainain, N., Maximiano, M. F. A., Ferreira, M., Aleixo, A., Faircloth, B. C., Brumfield, R. T., . . . Ribas, C. C. (2021). Multiple species and deep genomic divergences despite little phenotypic differentiation in an ancient Neotropical songbird, Tunchiornis ochraceiceps (Sclater, 1860) (Aves: Vireonidae). Molecular Phylogenetics and Evolution, 162, 107206. https://doi.org/10.1016/j.ympev.2021.107206

https://www.sciencedirect.com/science/article/abs/pii/S1055790321001391?via%3Dihub
