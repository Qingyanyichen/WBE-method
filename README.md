# WBE-method
This is the official Pytorch implementation of our paper "How to Evaluate and Remove the Weakened Bands in Hyperspectral Image Classification", IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2025.3526917 (https://ieeexplore.ieee.org/document/10833848).

----------
Requirements  
----------
To install requirements:

    conda env create -f environment.yml

To download the dataset and setup the folders:

    bash setup_script.sh  

----------
Train Examples
----------
To train the model(s) in the paper, run this command in the A2S2KResNet folder:

    python A2S2KResNet.py -d <IN|UP|KSC> -e 200 -i 3 -p 3 -vs 0.9 -o adam

For more details about the algorithm, please refer to our article (https://ieeexplore.ieee.org/document/10833848).  

If you have any questions or any suggestions, please contact Huan Zhang: zhanghuan19@tsinghua.org.cn

----------
Citation
----------
H. Zhang, X. Han, J. Deng and W. Sun, "How to Evaluate and Remove the Weakened Bands in Hyperspectral Image Classification," in IEEE Transactions on Geoscience and Remote Sensing, vol. 63, pp. 1-15, 2025, Art no. 5502515, doi: 10.1109/TGRS.2025.3526917.

