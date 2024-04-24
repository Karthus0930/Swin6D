Code is coming soon
![image](https://github.com/Karthus0930/Swin6D/assets/102593205/76f33488-e5f6-4ff9-982e-cabfe40746bb)

## Requirements
* Open3D==0.16.0
* python==3.7.13
* OpenCV==4.6.0
* Pytorch==1.7.0
* CUDA==11.4

## Downloads
* YCB-Video dataset [[link](https://rse-lab.cs.washington.edu/projects/posecnn/)]
* Preprocesssed LineMOD dataset (refer from DenseFusion) [[link](https://hkustconnect-my.sharepoint.com/personal/yhebk_connect_ust_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fyhebk%5Fconnect%5Fust%5Fhk%2FDocuments%2Fpublically%20shared%20%E5%85%B1%E4%BA%AB%E6%96%87%E4%BB%B6%E5%A4%B9%2F6D%5Fpose%5Fdatasets%2FLinemod%5Fpreprocessed%2Ezip&parent=%2Fpersonal%2Fyhebk%5Fconnect%5Fust%5Fhk%2FDocuments%2Fpublically%20shared%20%E5%85%B1%E4%BA%AB%E6%96%87%E4%BB%B6%E5%A4%B9%2F6D%5Fpose%5Fdatasets&ga=1)]
* Pred mask of PVN3D on YCB-Video dataset [[link](https://drive.google.com/file/d/1ftLn9itGQtjx5QM7SfOousIL44olIcm9/view?usp=sharing)]
* Pred mask of HybirdPose on LineMOD Occlusion dataset [[link](https://drive.google.com/file/d/1Jwp-J6opAAvtbMV1ewzhpBLoSjmZoMVJ/view)]

## Train
Pre-trained models are provided ([Download](https://pan.baidu.com/s/1fiQR-c0Kzo_U6f1QdJM3TQ))

## Results
ADD(-S) performance on Occlusion LineMOD dataset

| Method | Average of ADD(-S) |
| :---: | :---: |
| CloudAAE | 58.9 |
| OVE6D (w Mask) | 56.1 |
| OVE6D (w GT) | 70.9 |
| **Swin6D (w/o GT)** | **60.4** |
| **Swin6D (w GT)** | **77.2** |
