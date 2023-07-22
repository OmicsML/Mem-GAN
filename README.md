# Mem-GAN
> This repo holds code for [Mem-GAN: a pseudo membrane generator for single-cell imaging in fluorescent microscopy](https:).

<!--![](https://github.com/dbader/readme-template/raw/master/xxx.png)-->

## Usage

### Demo (https://omicsml.ai/memgan/)


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

### Testing phase
> According to your generation goal, Put your test images into 
```
./datasets/test_data/*/testA/
```

> Tumor cell membrane generation
```
python test.py --dataroot ./datasets/test_data/tum_cell --name cosmxv6 --model cycle_gan --preprocess none --num_test=2
```
> Immune cell membrane generation
```
python test.py --dataroot ./datasets/test_data/imm_cell --name cosmximmv2 --model cycle_gan --preprocess none --num_test=2 --epoch 100
```
> Weak cell membrane generation
```
python test.py --dataroot ./datasets/test_data/weak_cell --name cosmxv7weak --model cycle_gan --preprocess none --num_test=2
```
> Generated images will be under ./results/

### Citation
If you find this paper or code useful for your research, please cite our paper:
```

```
### Acknowledgement
> This repo is borrowed from the [Reproduction](CycleGAN)

### TO DO
> 
