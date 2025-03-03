# legged_gym-rookie-
The initial reason for creating this repository was because I was a rookie and had a lot of problems learning to configure the environment. Therefore, I hope that through this can you.

# Isaac Gym Environments for Legged Robots
## 1、Installation
1、Create a new python virtual env with python 3.8（Ensure you have installed Anaconda successfully)

`conda create -n <env name> python=3.8`

2、Install `pytorch 1.13.1` with `cuda 11.7`(GPU only):

`conda activate <env name>\conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia`

3、Make sure you have installed successfully in your bash:

`python
import torch
print(torch.cuda.is_available())`

