# legged_gym-rookie-
The initial reason for creating this repository was because I was a rookie and had a lot of problems learning to configure the environment. Therefore, I hope that through this can you.
# Enviromental requirement
```bash
Ubuntu=20.04
python 3.6 3.7 3.8(recommend)
pytorch=1.13.1
Cuda=11.7
```

# Isaac Gym Environments for Legged Robots
## 1、Installation
1、Create a new python virtual env with python 3.8（Ensure you have installed Anaconda successfully)

`conda create -n <env name> python=3.8`

2、Install `pytorch 1.13.1` with `cuda 11.7`(GPU only):
```bash
conda activate <env name>
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia
```
3、Make sure you have installed successfully in your bash:
```bash
python
import torch
print(torch.__version__)
print(torch.cuda.is_available())
```
If the output is true, the installation was successful.

4、Install Isaac Gym 

Download and install Isaac Gym Preview4 from https://developer.nvidia.com/isaac-gym/download

`cd isaacgym/python&&pip install -e .`

test through a demo:`cd examples%%python joint_monkey.py`

If you have problems with this step, please refer to this documentation
