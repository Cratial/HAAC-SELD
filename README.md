# HAAC: Hierarchical Audio Augmentation Chain for ACCDOA Described Sound Event Localization and Detection


This is a PyTorch implementation of our submitted manuscript [HAAC: Hierarchical Audio Augmentation Chain for ACCDOA Described Sound Event Localization and Detection](https://www.sciencedirect.com/science/article/pii/S0950705123000813).


**Abstract**
The goal of sound event localization and detection (SELD) is to detect the occurrence and temporal activity of a known set of sound events, as well as localize them in spatial space. Acquiring a large dataset is essential for one deep neural network-based SELD method learned as a supervised task. Nonetheless, gathering and annotating such datasets is a costly and time-intensive process. Hence, various data augmentation methods have gained attention as a solution to increase sample diversity from the limited collections. In this paper, we propose one hierarchical audio augmentation chain (HAAC) for the activity-coupled Cartesian direction of arrival output representation (ACCDOA) described SELD task. The HACC consists of three waveform and spectrogram augmentation techniques, which are exquisitely assembled from the feature map augmentation to audio channel swapping, and finally sample mixup. Experiments on the Sony-TAu Realistic Spatial Soundscapes 2022 (STARSS22) dataset show that our HACC audio augmentation chain greatly improved the SELD performance, which increased the sound event detection score by 24\% and decreased the localization error by 12.1\degree. To further improve the SELD performance, we generate simulated audio samples by convolving selected sound events with spatial room impulse responses (SRIRs) collected in reality. Enhanced with more simulated training samples, the sound event detection and localization performance are improved obviously.



## Acess to this source code
 **Note: The source code is free for non-commercial research and education purposes.** Any commercial use should get formal permission first.
 
 The code and relevant supplementary materials are released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) for NonCommercial use only. 

 Please cite our paper if you use any part of our source code or data in your research.


## Requirement
- python>=3.9.7
- audioread>=2.1.9
- PyTorch>=1.12.1
- torchvision>=0.13.1
- pandas>=1.4.4
- librosa>=0.8.1 
- h5py>=3.7.0
- numpy>=1.20.3
- scikit-learn>=1.0.1
- scipy>=1.7.3



## Usage 
Source code is coming soon...



## Code References
In this Codebase, we utilize code from the following source(s):

* [crnn-based seld](https://github.com/sharathadavanne/seld-dcase2022) 
* [einv2-based seld](https://github.com/Jinbo-Hu/DCASE2022-TASK3) 

