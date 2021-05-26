# MReT2019
![image](https://user-images.githubusercontent.com/9549469/119602490-9905cf80-be2e-11eb-8535-28f152c0d3b2.png)

This README.md file was generated on 2019/05/16 and updated on 2020/09/06 by Xiaohan Yu.

## Latest News
We have released another five large-scale ultra-fine-grained image datasets for research purpoose. Please visit https://maxwell.ict.griffith.edu.au/cvipl/databases.html or contact me directly to download the datasets.

## Basic information
Two works are included.
1. A MATLAB code and datasets for our paper accepted by AAAI 2020: https://arxiv.org/abs/1912.00622
* Xiaohan Yu, Yang Zhao, Yongsheng Gao, Shengwu Xiong, Xiaohui Yuan. *Patchy Image Structure Classification Using Multi-Orientation Region Transform*, accpeted in AAAI 2020. 

2. A MATLAB code for implementation of MReT presented in:
* Xiaohan Yu, Yongsheng Gao, Shengwu Xiong, Xiaohui Yuan. *Multiscale Contour Steered Region Integral and Its Application for Cultivar Classification*, IEEE Access 2019.

## Detailed Instrcution for AAAI 2020 *Patchy Image Structure Classification Using Multi-Orientation Region Transform*
1. A zip file "AAAI2020.zip" contains the code, extracted feature matrix, and the dataset for the whole evalution on BtfPIS, IwPIS, and SoyCultivarVein datasets introduced in our paper. 

step (1) run butflymain.m to calculate the feature matrix.

step (2) "btf_result.mat","p1.mat"-"p3.mat", "iw_result.mat" are such feature matrices obtained by saving the yyy1-yyy4 in step (1). 

step (3) run AAAI20201NNfulltest.m to calculate the 1NN results.

p1.mat, p2.mat, p3.mat are the feature matrices of SoyCultivarVein dataset. iw_result.mat is the feature matrix of IwPIS dataset. btf_result.mat is the feature matrix of BtfPIS dataset.

Conv_Datasets contains the datasets for Deep Learning techniques.

## Detailed Instruction for IEEE Access 2019 *Multiscale Contour Steered Region Integral and Its Application for Cultivar Classification*
Folder *Feature Matrix*
MAT files in folder *Featrue Matrix* represent the feature matrices of three parts of the soybean datasets, and can be used directly for performance evaluation (using Concatenate_soybeantest.m).
(1). p1s2.mat, p2s2.mat, p3s2.mat are the feature matrices of MReT using major vein and secondary vein.
(2). p1v3correct.mat, p2v3correct.mat, p3v3correct.mat are the feature matrices of MReT using major, secondary and tertiary vein.

Folder *code*
1. main.m is the start code to run the MReT method, including
(1) data loading
(2) contour extraction
(3) feature extraction
2. Concatenate_soybeantest.m is the evaluation code including
(1) feature fusion of features from three parts of plants
(2) Nearest Neighbor (1NN) evaluation protocol
(3) Bulls-eye test evaluation protocol

## zip *SoyCultivarVein_Dataset.7z*
The down load URL is *https://maxwell.ict.griffith.edu.au/cvipl/databases/SoyCultivarVein_Dataset.7z*.
This zip file contains the whole SoyCultivarVein dataset including 100 cultivars with 6 leaf images in each cultivar.

## Author contact info
*Xiaohan Yu*, *yuxiaohan112@gmail.com*

