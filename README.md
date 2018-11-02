
* [**What is MIDAS-VT?**](https://github.com/K1-ZR/midas-vt-pre/blob/master/README.md#what-is-midas-vt)  
* [**What is MIDAS-VT-Pre?**](https://github.com/K1-ZR/midas-vt-pre/blob/master/README.md#what-is-midas-vt-pre)  
* [**Installation**](https://github.com/K1-ZR/midas-vt-pre/blob/master/README.md#installation)  
* [**Link to the complete user's guide**](https://github.com/K1-ZR/midas-vt-pre/blob/master/MIDAS-VT-User'sGuide.pdf)  

# What is MIDAS-VT?
MIDAS Virtual Tester, MIDAS-VT, is a software package that virtually analyses homogenous and heterogenous common material experiments. MIDAS-VT is capable of predicting viscoelastic behavior and crack propagation in smaples.
The current version is able to simulate the following test configurations. 
The blue areas represent potential crack regions.
<p align="center">
  <img src="https://github.com/K1-ZR/midas-vt-pre/blob/master/Gallery/AT.png" width="400" title="all tests">
</p>  

# What is MIDAS-VT-Pre?
MIDAS Virtual Tester Preprocessor, MIDAS-VT-Pre, is a part of MIDAS-VT package. MIDAS-VT-Pre generates Finite Element model of the test samples.
Overall flow of MIDAS-VT-Pre is shown below. MIDAS-VT-Pre has two options:  
* Case I: generates the FE model directly from the sample image or sample geometry  
* Case II: adds cohessive elemnets into regular FE mesh which is generated in advance  
  
<p align="center">
  <img src="https://github.com/K1-ZR/midas-vt-pre/blob/master/Gallery/MIDAS-VT-Pre-flowchart.png" width="500" title="midas-vt-pre flowchart">
</p>

# Installation
1. Download the latest version,midas-vt-pre.rar, from [release](https://github.com/K1-ZR/midas-vt-pre/releases) page. Then unzip the file.  
2. make sure you have all files in the release package:   
Gallery folder, MIDAS_VT_Pre.exe, splash.PNG  
3. Prerequisites:  
Verify the suitable MATLAB Runtime is installed on your computer.  
4. Run the target executable:  
MIDAS_VT_Pre.exe   

**Note:** all the output messages will be stored in STATUS.txt for future reference.  
**Note:** The execution may take several minutes.  
