Hi! 

this project is part of the 
"Machine Learning - Unsupervised Learning and Feature Engineering" 
module at the International University (IU).

In order to reproduce results, you would need to
a) download the dataset from kaggle "https://www.kaggle.com/datasets/Cornell-University/arxiv/data" and name it "original_data.json" and  put it in the same folder as the other files
b) in the PCA_SciBERT.ipynb file need to change the import "intel_extension_for_pytorch as ipex" code to suit your local system if you intend to use GPU accelaration
c) have pytorch, pyreadr, scikit and usual modules like pandas, numpy, matplot installed in your environment

Credits go to  the Allen Institute for Artificial Intelligence (AI2) for developing SciBERT, an open-source language model that proved instrumental in the study.
Please See https://github.com/allenai/scibert/?tab=readme-ov-file for further reference