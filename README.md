# MiniProject2-3
## Project discription
Our idea is to have a generator that can detect different items in the sketch scene and make the generated image from the sketch make more sense. 

Train the model: 
`python3 semantic_main.py --mode='train' --init_with='resnet' --log_info=1 --ignore_class_bg=1`

Use Validation dataset: 
`python3 semantic_main.py --mode='val' --dcrf=0`

Test the model: `python3 semantic_main.py --mode='test' --dcrf=1`
## Citation
```@inproceedings{Zou18SketchyScene,
  author    = {Changqing Zou and
                Qian Yu and
                Ruofei Du and
                Haoran Mo and
                Yi-Zhe Song and
                Tao Xiang and
                Chengying Gao and
                Baoquan Chen and
                Hao Zhang},
  title     = {SketchyScene: Richly-Annotated Scene Sketches},
  booktitle = {ECCV},
  year      = {2018},
  publisher = {Springer International Publishing},
  pages		= {438--454},
  doi		= {10.1007/978-3-030-01267-0_26},
  url		= {https://github.com/SketchyScene/SketchyScene}
}```
```@inproceedings{hinz2019generating,
title     = {Generating Multiple Objects at Spatially Distinct Locations},
author    = {Tobias Hinz and Stefan Heinrich and Stefan Wermter},
booktitle = {International Conference on Learning Representations},
year      = {2019},
url       = {https://openreview.net/forum?id=H1edIiA9KQ},
}```
