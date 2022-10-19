# CNet
This is the code of our paper: **CNet: A Calibrate Network for Citation Graph Classification**. 

>Due to the limit of file uploads on GitHub, we use Cora data for the demo here. The rest of the experimental data can be downloaded from [google drive](https://drive.google.com/drive/folders/1Q9vUaNYvSP-PS2dcSkb7BD9lX0r0FHAa?usp=sharing).

## Requirements
* Python 3.7.13
* Pytorch 1.10.0


## Usage Example
* CNet's Graph Data Augmentation (GDA) one trial on Cora:
```jupyter notebook GDA/CNet(HF-ML).ipynb```
* t-SNE one trial on Cora:
```jupyter notebook t-SNE/t-SNE-Cora.ipynb```
* Setting CNet's GNN experimental parameters:
```vi Config.ini ```
* Running CNet's GNN one trial on Cora:
```python CNet-GNN.py ```


## Running Environment 

The experimental results reported in paper are conducted on a single NVIDIA GeForce RTX 2070 with CUDA 11.4, which might be slightly inconsistent with the results induced by other platforms.


## t-SNE Results (Cora, Citeseer, Pubmed)


![](https://i.imgur.com/Zd9ryuk.png)
![](https://i.imgur.com/QtLFTq8.png)
![](https://i.imgur.com/bGtLD4D.png)



