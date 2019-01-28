### chromNN
We develop a bimodal neural network architecture to model induced *in vivo* TF binding based on TF's sequence preferences as well the preexisting chromatin landscape.The sequence and chromatin sub-networks interact in an additive model to predict genome-wide TF binding. 


### Citation (Update with BioRxiv submission)
Characterizing the sequence and chromatin pre-determinants of induced TF binding with deep bimodal neural networks. 

### Requirements
1. Python2.7
   All python dependencies can be installed with: pip install -r requirements.txt
2. Keras (Recommended version >= 2.02)
3. Tensorflow (Recommended verion >= v1.8)
4. Seaborn(0.9.0) for plotting (https://seaborn.pydata.org/installing.html)

### Usage
1. Model interpretation
Running the folowing module will reproduce all analyses and figures from the paper. [1] Note here, that by default, we reproduce all analyses with a test chromosome instead of the whole genome as a demonstration. 

cd interpretNN
python interpretNN.py model input_datapath
  
