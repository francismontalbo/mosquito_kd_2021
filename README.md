# REPOSITORY MADE FOR A RESEARCH PUBLICATION

- ### Author: Dr. Francis Jesmar P. Montalbo
- ### Affiliation: Batangas State University
- ### Email: francismontalbo@ieee.org; francisjesmar.montalbo@g.batstate-u.edu.ph
### <p><a href="https://francismontalbo.github.io">Personal Webpage</a></p>
***PLEASE CONTANCT ME IF YOU ARE HAVING TROUBLE. I CAN OFFER ASSITANCE***

# Graphical Abstract

<img src="/graphics/ga.jpg" alt="francis_montalbo_graphical_abstract_mosquito_KD_2021" width="400">

# Datasets used: 
<h1><a href="https://drive.google.com/file/d/1aIlFzGdjhu9XFQkNtdk_n8qiM88zp3XY/view"></a>Mosquito Dataset</h1>
<h3>Paper to cite:</h3>
<p><a href="https://www.nature.com/articles/s41598-020-57875-1">Classification and Morphological Analysis of Vector Mosquitoes using Deep Convolutional Neural Networks</a></p>

=========================================================================

***:heavy_exclamation_mark:For a faster method, you may download the already prepared dataset used in the given link below.*** 

<a href="#">CLICK THIS FOR THE PREPARED DATASET USED IN THIS STUDY. Download the `data.rar` and extract it to the `../dataset`</a>

=========================================================================

# How to use:
# Disclaimer
***:heavy_exclamation_mark:If training the model, the dependencies included a `tensorflow-gpu`. You may change the `tensorflow-gpu` to `tensorflow` if no GPU is to be used. However, the results from the paper were produced using a GPU (RTX 3060 12gb) and may have slight differences***

Dependencies included in the `requirements.txt`: 
- jupyter==1.0.0
- keras==2.4.3
- matplotlib==3.4.1
- numpy==1.19.5
- opencv-python==3.4.11.41
- pandas==1.2.4
- Pillow==8.2.0
- scikit-learn==0.24.1
- scikit-image==0.18.1
- scikit-plot==0.3.7
- scipy==1.2.0
- tf-nightly-gpu==2.6.0 (Note: This is optional and can train even with just a CPU or tensorflow non-gpu variant. Nightly is used to compensate the new RTX 3060 card)

=========================================================================
## General Instruction:
You may clone using git or download the repository and extract the files manually:
- Once cloned, CD into the folder and enter `pip install -r requirements.txt`. 
- Download the readily trained weights and dataset here ---> <a href="#">Dataset and Trained Weights</a>
- Extract the `data.rar` in `../dataset` and the `models.rar` in `../models`
======================================================================
