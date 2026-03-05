This repository contains the implementation of **DERMANet (ConvNeXt + CBAM)** proposed in the paper:

**Deep Learning-Based Nail Disease Diagnosis Leveraging the DERMANet Architecture with ConvNeXt and CBAM**

The code supports:
- model training
- stratified 5-fold cross-validation
- model inference
- Grad-CAM visualization

The repository is provided to ensure **reproducibility of the results reported in the manuscript**.


# 1. Installation

Clone the repository

```bash
git clone https://github.com/bhuvanya/Nail-Disease-Classification.git
cd DERMANet
Install dependencies
pip install -r requirements.txt

## 2. Dataset
dataset/
   train/
       healthy/
       psoriasis/
       onychomycosis/

   test/
       healthy/
       psoriasis/
       onychomycosis/

# 3. Training the Model
DERMANet.ipynb

#4. Cross Validation
5 Fold Stratified CV.ipynb

#5. Model inference
inference.ipynb

#6. Grad-CAM Visualizion
grad-cam.ipynb
