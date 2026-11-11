## Introduction
This repo is a play ground for trying different things, such as courses, opensource projects even hardwares. Some tools and web site which are used in this docs are good to use in China, you may need to change according your own location.

## OS
For software development, I prefer using ubuntu 24.04 and 26.04, all commands should work on them.

## Python
I prefer using conda for managing python modules, but some modules can only be installed with pip. So both of these two module managing tools are used.

### Speed up conda 
Add following content to ~/.condarc
```
solver: libmamba
channels:
  - nodefaults
  - conda-forge
  - bioconda
custom_channels:
  conda-forge: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  bioconda: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
  pytorch: https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud
show_channel_urls: true
```

### Speed up pip
```bash
python3 -m pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
```