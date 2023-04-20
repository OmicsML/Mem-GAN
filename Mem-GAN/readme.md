## Testing phase
### Tumor cell membrane generation
python test.py --dataroot ./datasets/test_data/tum_cell --name cosmxv6 --model cycle_gan --preprocess none --num_test=2
### Immune cell membrane generation
python test.py --dataroot ./datasets/test_data/imm_cell --name cosmximmv2 --model cycle_gan --preprocess none --num_test=2 --epoch 100
### Weak cell membrane generation
python test.py --dataroot ./datasets/test_data/weak_cell --name cosmxv7weak --model cycle_gan --preprocess none --num_test=2  
