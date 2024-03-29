# KidNeYronal

## General
This is an implementation of KidNeYronal - neural networks for pH predictions, using Python, Keras, and TensorFlow with [Google Colab](https://colab.research.google.com/) . The networks generate 3 pHe compartment predictions from hyperpolarized zymonic acid spectra obtained in MRI of mixed (synthetic + acquired) data set of acquisitions from the kidneys of healthy mice.

![alt text](https://github.com/ryanayf/KidNeYronal/blob/a28ea6ef19c6f921847de9262efb5e4a0fdeca56/KidNeYronal_Fig1.png)

## The repository includes:
### 1. Code: 

- Training code for KidNeYronal in Jupyter notebooks 
  -	CNN with mixed data (_Mix) and with synthetic data (_S)
  -	MLP with mixed data (_Mix) and with synthetic data (_S)
 
- Line-fitting analysis code

### 2. Data:

-	Training, validation and test data sets (synthetic + acquired)
- Healthy mice kidney imaging data and ROI
  
## Notes
**If you use this repository in your research, please cite our paper:**

Fok, WY.R., Grashei, M., Skinner, J.G. et al. Prediction of multiple pH compartments by deep learning in magnetic resonance spectroscopy with hyperpolarized 13C-labelled zymonic acid. EJNMMI Res 12, 24 (2022). https://doi.org/10.1186/s13550-022-00894-y
