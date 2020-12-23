# Omnidirectional-Images-as-Moving-Camera-Videos

This is the repository of paper [Omnidirectional Images as Moving Camera Videos](https://arxiv.org/abs/2005.10547)

The database can be download at here [Database](https://drive.google.com/drive/folders/1GJ9g3G-QmZbmFbXxiBYyf28xFID3SXxW?usp=sharing)

# Highlights:
1. A principled computational framework for objective quality assessment of 360° images.
2. We propose to represent an omnidirectional image by different moving camera videos.
3. Three viewing behavior: starting point, exploration time, scanpath are incorporated into this framework.

# Implementation version:
1. Matlab (recommend) [oiqa_metric.m](/oiqa_metric.m)
Requirements:
Matlab>=R2017a
(The speed is much faster when using MatLab R2020a.)

2.Pytorch main.py
Requirements:
Python>=3.6
Pytorch>=1.0

# Usage:
```bash
git clone https://github.com/xiangjieSui/img2video
run demo.m
```
# Citation
```
@article{sui2020omnidirectional,
  title={Omnidirectional Images as Moving Camera Videos},
  author={Xiangjie Sui and Kede Ma and Yiru Yao and Yuming Fang},
  journal = {CoRR}, 
  volume = {abs/2005.10547}, 
  year={2020}, 
  url = {https://arxiv.org/abs/2005.10547}
}
```
