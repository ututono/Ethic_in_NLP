## Important dependencies

- For this exercise you need to install the following dependecies: python >= 3.6, thorch=1.8.0+cu111 and torchtext=0.9.0
- If you are using pip as your package manager you can enter the following command to install all dependencies:
  pip3 install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
---
- It is extremely recommended to install the torch with CUDA since the computing time reduces essentially
- Example: on a machine with i5 7300HQ the training of english model takes 40 minutes, but with CUDA only 3 minutes
- Here you can inform which version of CUDA your machine is supporting: https://en.wikipedia.org/wiki/CUDA Section - GPUs supported
---
- Here you can find some helpful commands that will guide you how to install the dependencies: https://pytorch.org/get-started/previous-versions/#v180
- Consider to install the right version
---
- You may need to install torchtext separately
