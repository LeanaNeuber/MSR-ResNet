# MSR-ResNet
This repo is part of  a research project at the EFREI Paris.

This project aims at using an open source dataset that is used in many papers, namely the [MSR action 3D dataset](https://sites.google.com/view/wanqingli/data-sets/msr-action3d), and a Deep Learning ResNet architecture described in a [paper by Pham et al. in 2018](https://arxiv.org/pdf/1803.07781) to perform action recognition. 


The dataset contains of 20 actions (a01 - a20), 10 subjects performing the actions (s01 - s10) and each subject performs the action 2-3 times (e01-e03). 
The actions are:
*   a01 High arm wave
*   a02 Horizontal arm wave
*   a03 Hammer
*   a04 Hand catch
*   a05 Forward punch
*   a06 High throw
*   a07 Draw cross
*   a08 Draw tick
*   a09 Draw circle
*   a10 Hand clap  
*   a11 Two-hand wave 
*   a12 Side-boxing 
*   a13 Bend 
*   a14 Forward kick
*   a15 Side-kick
*   a16 Jogging
*   a17 Tennis swing 
*   a18 Tennis serve
*   a19 Golf swing 
*   a20 Pick-up and throw



At the beginning of the project, the goal was to understand and analyze the open source dataset. The original dataset in the form of depth maps was downloaded, read from the binary files and visualized exemplary. Afterwards, the skeleton data was loaded and also visualized. For better visualization, edges were added to the joins to achieve skeletons. Both visualizations can be found in the `MSR_Action_3D_Visualisation.ipynb` notebook.

The preprocessing and ResNet implementation with Keras can be found in the `ResNet-MSRAction3D.ipynb` notebook.

