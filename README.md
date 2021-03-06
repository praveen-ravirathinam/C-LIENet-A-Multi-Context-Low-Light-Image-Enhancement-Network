# C-LIENet-A-Multi-Context-Low-Light-Image-Enhancement-Network
Official Code repository for Paper 'C-LIENet: A Multi-Context Low-Light Image Enhancement Network', IEEE Access   
P. Ravirathinam<sup>\*</sup>, D. Goel<sup>\*</sup> and J. J. Ranjani
  
Implementation is done in Keras (Please make sure you have TensorFlow v1.15 installed). This repo consists of train and test code along with pretrained models for noise-free and noisy datasets. We also introduce a dataset Lowlight Image Dataset, created using images from MIT outdoor and indoor scenes dataset, on both noise-free settings(LID) and noisy settings(LID_NOISE). Noise was added in MATLAB and is of Poisson Gaussian nature to mimic real life settings as much as possible. 

Paper Link: https://ieeexplore.ieee.org/document/9354616  
Full dataset available at: https://drive.google.com/drive/folders/1PAn7gNg-i90q_a40bQwKLYJ9QMJMGmAl?usp=sharing  
Citation details: P. Ravirathinam, D. Goel and J. J. Ranjani, "C-LIENet: A Multi-Context Low-Light Image Enhancement Network," in IEEE Access, vol. 9, pp. 31053-31064, 2021, doi: 10.1109/ACCESS.2021.3059498.

Abstract: Enhancement of low-light images is a challenging task due to the impact of low brightness, low contrast, and high noise. The inability to collect natural labeled data intensifies this problem further. Many researchers have attempted to solve this problem using learning-based approaches; however, most models ignore the impact of noise in low-lit images. In this paper, an encoder-decoder architecture, made up of separable convolution layers that solve the issues encountered in low-light image enhancement, is proposed. The architecture is trained end-to-end on a custom low-light image dataset (LID), comprising both clean and noisy images. We introduce a unique multi-context feature extraction module (MC-FEM) where the input first passes through a feature pyramid of dilated separable convolutions for hierarchical-context feature extraction followed by separable convolutions for feature compression. The model is optimized using a novel three-part loss function that focuses on high-level contextual features, structural similarity, and patch-wise local information. We conducted several ablation studies to determine the optimal model for low-light image enhancement under noisy and noiseless conditions. We have used performance metrics like peak-signal-to-noise ratio, structural similarity index matrix, visual information fidelity, and average brightness to demonstrate the superiority of the proposed work against the state-of-the-art algorithms. Qualitative results presented in this paper prove the strength and suitability of our model for real-time applications.
