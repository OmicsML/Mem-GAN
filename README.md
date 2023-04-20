# Mem-GAN
> This repo holds code for [Mem-GAN: a pseudo membrane generator for single-cell imaging in fluorescent microscopy](https:).

<!--![](https://github.com/dbader/readme-template/raw/master/xxx.png)-->

## Usage

### Dataset
> You need to download the [CosMx](https://www.med.upenn.edu/sbia/brats2018/registration.html) or other multi-modality datasets into ```<root_dir>/ACN/data```
> The dataset directory should have this basic structure (BraTS as an example):
```
<root_dir>/ACN/data/<DATA_NAME>/*/case_name/*_flair.nii.gz      
<root_dir>/ACN/data/<DATA_NAME>/*/case_name/*_t1.nii.gz   
<root_dir>/ACN/data/<DATA_NAME>/*/case_name/*_t1ce.nii.gz   
<root_dir>/ACN/data/<DATA_NAME>/*/case_name/*_flair.nii.gz
<root_dir>/ACN/data/<DATA_NAME>/*/case_name/*_seg.nii.gz     # groundtruth 
```
### Pre-requsites
```
torch>=1.4.0
torchvision>=0.5.0
dominate>=2.4.0
visdom>=0.1.8.8
```
Please use the command ```pip install -r requirements.txt``` for the dependencies.

### Train Phase
> Run the code for training a generation model for your own dataset

> Note: 
```
python xxx.py
```
### Citation
If you find this paper or code useful for your research, please cite our paper:
```

```
### Acknowledgement
> This repo is borrowed from the [Reproduction]() of CycleGAN

### TO DO
> 
