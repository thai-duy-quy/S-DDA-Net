
# SD²A-Net: Attention-Enhanced Static–Dynamic Wi-Fi CSI Decomposition for Cross-Domain Human Activity Recognition
## Introduction
SD²A-Net (Static–Dynamic Decomposition with Attention Network): a robust cross-domain framework that decouples motion-induced dynamics from background interference. The framework utilizes a Gaussian Mixture Model (GMM) on CSI amplitude to isolate motion variations and Singular Value Decomposition (SVD) on CSI phase to suppress low-rank environmental structures. These refined features are processed via a Dual-stream Attention-CNN to capture global temporal dependencies and local hierarchical patterns. 
Our paper now under review in IEEE IEEE Sensors Journal. The full source code will upload after the paper have been published. 

## Run
### Download Processed Data
Data original can be downloaded at: 
1. [MultiEnv](https://github.com/lcsig/Dataset-for-Wi-Fi-based-human-activity-recognition-in-LOS-and-NLOS-indoor-environments): This dataset was collected in three scenarios: line-of-sight (LOS) in both the office and hall, and non-line-of-sight (NLOS).
2. [StanWiFi](https://github.com/ermongroup/Wifi_Activity_Recognition): This dataset contains continuous CSI data for six activities without precise segmentation timestamps for each sample.

Try to run dataset.py to process the data from original dataset.

Data processed can be downloaded at: [PA-CSI dataset](https://drive.google.com/drive/folders/1fiJBDWDC3WKkD5pLYRwpLCWMXPVzCQ-i?usp=sharing)



