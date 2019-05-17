# MReT2019
This README.md file was generated on 2019/05/16 by Xiaohan Yu.

## Basic information 
This is a MATLAB code for implementation of MReT presented in:
* Xiaohan Yu, Yongsheng Gao, Shengwu Xiong, Xiaohui Yuan. *Multiscale Contour Steered Region Integral and Its Application for Cultivar Classification*, IEEE Access 2019.

## Folder *Feature Matrix*
MAT files in folder *Featrue Matrix* represent the feature matrices of three parts of the soybean datasets, and can be used directly for performance evaluation (using Concatenate_soybeantest.m).
(1). p1s2.mat, p2s2.mat, p3s2.mat are the feature matrices of MReT using major vein and secondary vein.
(2). p1v3correct.mat, p2v3correct.mat, p3v3correct.mat are the feature matrices of MReT using major, secondary and tertiary vein.

## Folder *code*
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

