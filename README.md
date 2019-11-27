# MReT2019
This README.md file was generated on 2019/05/16 by Xiaohan Yu.

## Basic information
Two works are included.
1. A MATLAB code and datasets for our paper accepted by AAAI 2020:
* Xiaohan Yu, Yang Zhao, Yongsheng Gao, Shengwu Xiong, Xiaohui Yuan. *Patchy Image Structure Classification Using Multi-Orientation Region Transform*, accpeted in AAAI 2020. 

2. A MATLAB code for implementation of MReT presented in:
* Xiaohan Yu, Yongsheng Gao, Shengwu Xiong, Xiaohui Yuan. *Multiscale Contour Steered Region Integral and Its Application for Cultivar Classification*, IEEE Access 2019.

## Detailed Instrcution for *Patchy Image Structure Classification Using Multi-Orientation Region Transform*
1. A zip file "Leeds_btf_patchy_dataset.zip" contains the code, extracted feature matrix, and the dataset for the whole evalution on BtfPIS dataset introduced in our paper. 
step (1) run butflymain.m to calculate the feature matrix.
step (2) "btf_result.mat" is such a feature matrix obtained by saving the yyy1-yyy4 in step (1). 
step (3) run AAAI20201NNfulltest.m to calculate the 1NN results.

## Detailed Instruction for *Multiscale Contour Steered Region Integral and Its Application for Cultivar Classification*
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

