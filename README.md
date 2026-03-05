This repository contains the implementation of DERMANet (ConvNeXt + CBAM) for nail disease classification. The code allows reproduction of the experiments reported in the manuscript including:

- model training
- 5-fold cross validation
- Grad-CAM visualization
- inference

# Nail-Disease-Classification
# DERMANet Reproducibility
## Install
pip install -r requirements.txt
## Train model
python train_dermanet.ipynb
## Test model
python inference.ipynb
## Generate GradCAM
python gradcam.ipynb
**Dataset structure**
dataset/
   train/
       healthy/
       psoriasis/
       onychomycosis/

   test/
       healthy/
       psoriasis/
       onychomycosis/
    
