# README
This repository is the official implementation of our work "A Grassmannian Manifold Self-Attention Network for Signal Classification", which has been accepted by IJCAI 2024. 

The implementation of our GDLNet is based on the code of Matt [a]. We would like to express our sincere thanks to the authors.

## Requirements
#### Step 1:
To install requirements:
```setup
conda env create -f /path/to/mAtt_env.yml
conda activate mAtt_env
```
#### Step 2:
Download datasets and unzip them to the folder 'data'.

## Dataset
1. MAMEM-SSVEP-II:
   https://www.mamem.eu/results/datasets/
2. BCI-ERN:
    https://www.kaggle.com/competitions/inria-bci-challenge/data

Link to download [data](https://drive.google.com/file/d/1_KBfSNzvxCZ-HwiOASQhlFe8wwsq4vHt/view?usp=sharing)

## Training and testing

To train and test the mAtt in the paper, run this command:

```train and test
python mAtt_<which_dataset>.py
```
All default hyperparameters are already set in files. 'which_dataset' can be chosen as 'mamem' (MAMEM-SSVEP-II), or 'bcicha' (BCI-ERN).



## Reference
```bash
[a] Pan, Y. T., Chou, J. L., & Wei, C. S. (2022). MAtt: A manifold attention network for EEG decoding. Advances in Neural Information Processing Systems, 35, 31116-31129.
```


```

