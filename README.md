# Endowing rotation invariance for 3D finger shape and vein verification
By Hongbin Xu, Weili Yang, Qiuxia Wu and WenXiong Kang

This repository is the Matlab code of the 3D finger vein reconstruction algorithm and the 3D finger vein dataset.

## Abstract
Finger vein biometrics have been extensively studied for the capability to detect aliveness, and the high security as intrinsic traits.
However, vein pattern distortion caused by finger rotation degrades the performance of CNN in 2D finger vein recognition, especially in a contactless mode.
To address the finger posture variation problem, we propose a 3D finger vein verification system extracting axial rotation invariant feature.
An efficient 3D finger vein reconstruction optimization model is proposed and several accelerating strategies are adopted to achieve real-time 3D reconstruction on an embedded platform.
The main contribution in this paper is that we are the first to propose a novel 3D point-cloud-based end-to-end neural network to extract deep axial rotation invariant feature, namely 3DFVSNet.
In the network, the rotation problem is transformed to a permutation problem with the help of specially designed rotation groups.
Finally, to validate the performance of the proposed network more rigorously and enrich the database resources for the finger vein recognition community, we built the largest publicly available 3D finger vein dataset with different degrees of finger rotation, namely the Large-scale Finger Multi-Biometric Database-3D Pose Varied Finger Vein (SCUT LFMB-3DPVFV) Dataset Experimental results on 3D finger vein datasets show that our 3DFVSNet holds strong robustness against axial rotation compared to other approaches.

## SCUT LFMB-3DPVFV Dataset
We introduce a 3D finger vein dataset--the Large-scale Finger Multi-Biometric Database-3DPose Varied Finger Vein (SCUT LFMB-3DPVFV) Dataset.
SCUT LFMB-3DPVFV contains 702 fingers collected from the index finger and middle finger of both right and left hands. Each finger was acquired 14 times and the 3D model was reconstructed from images from 3 different views. To simulate the arbitrary rotation in realistic scenarios, the volunteers are asked to rotate their fingers in various poses. The first 10 acquisitions are collected with rotation no more than ±30 degrees, while the remaining 4 times are collected by rotating the fingers with larger rotation no more than ±80 degrees. Finally, There are 7020 3D finger vein models for easy rotation and 9828 3D finger vein models for hard rotation.

## Request
The SCUT LFMB-3DPVFV Dataset is publicly available(free of charge) to the research community. Unfortunately, due to privacy reasons, we cannot provide the database for commercial use.

We have made part of the dataset available for download in the repo in order to get a detailed view of this data. Those interested in obtaining the whole SCUT LFMB-3DPVFV Dataset should download [release agreement](https://github.com/BIP-Lab/SCUT--SFVD/blob/master/SCUT%20FV%20Presentation%20Attack%20Database%20Release%20Agreement.pdf), and send by e-mail one signed and scanned copy to scutbip@outlook.com.


While reporting results using the SCUT LFMB-3DPVFV Dataset, please cite the following article:  
@inproceedings{Hongbin2021fv,
  title={ Endowing rotation invariance for 3D finger shape and vein verification },
  author={ Hongbin Xu, Weili Yang, Qiuxia Wu and WenXiong Kang },
  booktitle={ Frontiers of Computer Science },
  year={2021}
}


## Contact
HongBin Xu     
Biometrics and Intelligence Perception Lab.    
School of Software Engineering    
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641   
xxxxxxxx@mail.scut.edu.cn   

Weili Yang   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641   
auyang.wei.li@mail.scut.edu.cn    

QiuXia Wu    
Biometrics and Intelligence Perception Lab.   
School of Software Engineering   
South China University of Technology    
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641    
qxwu@scut.edu.cn   

Prof. Kang Wenxiong   
Biometrics and Intelligence Perception Lab.   
College of Automation Science and Engineering   
South China University of Technology   
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641      
auwxkang@scut.edu.cn   

