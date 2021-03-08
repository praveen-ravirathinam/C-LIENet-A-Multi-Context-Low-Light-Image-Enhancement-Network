# C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network
**Official Code repository** for Paper 'C-LIENet: A Multi-Context Low-Light Image Enhancement Network', IEEE Access   
P. Ravirathinam<sup>\*</sup>, D. Goel<sup>\*</sup> and J. J. Ranjani
  
Implementation is done in Keras (Please make sure you have TensorFlow v1.15 installed). This repo consists of train and test code along with pretrained models for noise-free and noisy datasets. We also introduce a dataset Lowlight Image Dataset, created using images from MIT outdoor and indoor scenes dataset, on both noise-free settings(LID) and noisy settings(LID_NOISE). Noise was added in MATLAB and is of Poisson Gaussian nature to mimic real life settings as much as possible. Complete dataset available in link below.

**Paper Link**: https://ieeexplore.ieee.org/document/9354616  
**Full dataset available at**: https://drive.google.com/drive/folders/1PAn7gNg-i90q_a40bQwKLYJ9QMJMGmAl?usp=sharing  
**Citation details**: P. Ravirathinam, D. Goel and J. J. Ranjani, "C-LIENet: A Multi-Context Low-Light Image Enhancement Network," in IEEE Access, vol. 9, pp. 31053-31064, 2021, doi: 10.1109/ACCESS.2021.3059498.  
*(BibTeX citation at end of README)*

### Architecture Diagram  
![alt text](https://github.com/praveen-ravirathinam/C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network/blob/main/figures/C-LIENet_Architecture.png)  
An illustrative diagram for the architecture of C-LIENet

### Dataset sample images (LID and LID_NOISE)
![alt_text](https://github.com/praveen-ravirathinam/C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network/blob/main/figures/dataset.png)  
Images from LID and LID_NOISE along with their Ground Truth. First row: synthesized low-light images, Second row: Ground Truth

### Comparison against baselines on LID images
![alt_text](https://github.com/praveen-ravirathinam/C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network/blob/main/figures/comparison_LID_clean.png)  

### Comparison against baselines on LID_NOISE images
![alt_text](https://github.com/praveen-ravirathinam/C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network/blob/main/figures/comparison_LID_noise.png)  

### BibTeX Citation
@ARTICLE{9354616,  
  author={P. {Ravirathinam} and D. {Goel} and J. J. {Ranjani}},  
  journal={IEEE Access},   
  title={C-LIENet: A Multi-Context Low-Light Image Enhancement Network},   
  year={2021},  
  volume={9},   
  pages={31053-31064},  
  doi={10.1109/ACCESS.2021.3059498}}  
