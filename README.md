# Personal Protective Equipment detection using YOLOv8 with Global Attention Mechanism (Status: Submission)

![avatar](Image/VietNam_4.jpg)

## Introduction

This paper presents an improved Yolov8 's framework for PPE detection. We propose I-GAM attention modules incorporated with Yolov8 architecture to highlight significant information.  Additonally, the modified Improved Global Attention Mechanism (I-GAM) was inserted in the head of Yolo network to enhance feature representation

## Proposed Yolov8 's Architecture

![avatar](Image/IGAM_YOLOV8.png)

## Proposed I-GAM Architecture with fine-tunning AND choose H-swish activation function

![avatar](Image/Original_GAM_hswish.png)

## Color Helmet and Vest (CHV)  Dataset

In our experiment, we used dataset **Color Helmet and Vest (CHV)**, which contains 1330 images, and 9209 instances in total.



The dataset is open for free use, raw data download at (https://github.com/ZijianWang-ZW/PPE_detection) or data which already processed (https://universe.roboflow.com/hienlongairesearch/chv_dataset_train_officially ). 




## Results

- **YOLO v8 have higher mAP when compare with others method 's research.**

<center><img src="Image/Result.png"/> 

<div align=center>Figure: Comparision Results.</div>


- **System evaluation on Jetson Orin Nano.**

<center><img src="Image/Runtime.png"/> 

<div align=center>Figure: System Evaluation.</div>

## Citation
	
`P. H. Long and T. Q. Vinh `

