
# SD²A-Net: Attention-Enhanced Static–Dynamic Wi-Fi CSI Decomposition for Cross-Domain Human Activity Recognition
## Introduction
SD²A-Net (Static–Dynamic Decomposition with Attention Network): a robust cross-domain framework that decouples motion-induced dynamics from background interference. The framework utilizes a Gaussian Mixture Model (GMM) on CSI amplitude to isolate motion variations and Singular Value Decomposition (SVD) on CSI phase to suppress low-rank environmental structures. These refined features are processed via a Dual-stream Attention-CNN to capture global temporal dependencies and local hierarchical patterns. 
Our paper now under review in IEEE IEEE Sensors Journal. The full source code will upload after the paper have been published. 

## Run
### Download Processed Data
Data original can be downloaded at: 
1. [MultiEnv](https://github.com/lcsig/Dataset-for-Wi-Fi-based-human-activity-recognition-in-LOS-and-NLOS-indoor-environments): This dataset was collected in three scenarios: line-of-sight (LOS) in both the office and hall, and non-line-of-sight (NLOS).
2. [Widar 3.0]([https://github.com/ermongroup/Wifi_Activity_Recognition](https://ieee-dataport.org/open-access/widar-30-wifi-based-activity-recognition-dataset)): This dataset is a large dataset designed for use in WiFi-based hand gesture recognition.
### Our dataset
Our dataset, referred to as the MINE Lab dataset, was collected in a controlled office-like laboratory environment with a size of 5.5 × 3 m. The experimental setup used two Intel 5300 NIC-equipped computers: one configured with three transmitters (Tx) and the other with one receiver (Rx). The transmitter and receiver were separated by a distance of 4.0 m. 
Five participants performed six activities within 30 seconds, including standing up and squatting, raising one arm overhead to the left or right (Act. 2 and Act. 3), forward clapping (Act. 4), and left and right front kicks (Act. 5 and Act. 6), resulting in 216 original samples. 

Our dataset after processing can be downloaded at: https://drive.google.com/drive/folders/1gR5b0refbE1ZpF2iPrm7yeh7ZlQxANzK?usp=drive_link

<img width="584" height="332" alt="image" src="https://github.com/user-attachments/assets/4deedfd3-ae43-4d50-9293-091bbde34598" />






