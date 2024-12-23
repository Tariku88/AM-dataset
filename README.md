# AM-dataset
In this repository, we have provided the AM dataset that is derived from Digimat-AM. The excel file is provided here. We also have the Digimat-AM models of all the corresponding configurations. However, we can not upload here due to its large file size. The data can be shared to intersted parties upon rerquest. The full paper can be accessed through (https://www.researchgate.net/profile/Tariku-Tamir/research). This AM data is utilized for the work of our paper entitled “Data-driven and physics-assisted machine learning approach for warpage classification and process parameter optimization in a 3-D-printed BeltClip”. The data collection of the paper begins with obtaining the STereoLithography (STL) file of the BeltClip object from Thingiverse and slicing it in Ultimaker© Cura, considering process parameters such as infill amount, toolpath pattern, layer height, print speed, and extrusion temperature (can be accessed through the Gcode files folder). The resulting G-code file is then input into Digimat-AM for further parameter setting and analysis. In Digimat-AM, glass fiber-filled and unfilled material types are set, undergoing the virtual 3D printing process (can be accessed through the Digimat model files folder), followed by a warpage analysis of the printed BeltClip. The collected 3D printing data is used to build ML models—deep neural network (DNN), decision tree (DT), support vector machine (SVM), logistic regression (LR), and random forest.


Please cite the paper as:
@article{tamir2025data,
  title={Data-driven and physics-assisted machine learning approach for warpage classification and process parameter optimization in a 3-D-printed BeltClip},
  author={Tamir, Tariku Sinshaw and Hua, Xijin and Jiang, Jingchao and Leng, Jiewu and Xiong, Gang and Shen, Zhen and Liu, Qiang},
  journal={IEEE Transactions on Computational Social Systems},
  year={2025},
  publisher={IEEE}
}
