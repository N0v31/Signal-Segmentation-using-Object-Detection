# PQRST Segmentation using RetinaNet1D
## Data preprocessing
### Training
Because training data have some missing labels, those missing labels' data are removed during training.
Currently there is no data preprocessing on training data. But there are some options available:
1. training data denoising using wavelet thresholding.
2. training data augmentation by adding gaussian noise or scale some part of waves.
### Testing
Testing data will denoise using wavelet thresholding before predicting.
## Result
This approach can get 0.968 F1-score which is better than previous approach using UNet.
