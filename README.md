# Awesome Weakly Supervised Object Detection [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Weakly Supervised Object Detection resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), and [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning)


## Contributing

Please feel free to send me [pull requests](https://github.com/SongYii/awesome-weakly-supervised-object-detection/pulls) or email (songyii@tju.edu.cn) to add links.

Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents
 - [Papers](#papers)
 - [Tutorials and Talks](#tutorials-and-talks)
 - [Benchmarks](#benchmarks)

## Papers
### Only Image-level Labels

#### 2020
- Object Instance Mining for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/2002.01087.pdf) 
  [[code]](https://github.com/bigvideoresearch/OIM)
  - Chenhao Lin, Siwen Wang, Dongqi Xu, Yu Lu, Wayne Zhang. *AAAI 2020*

- Instance-Aware, Context-Focused, and Memory-Efficient Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/2004.04725.pdf)
  [[code]](https://github.com/NVlabs/wetectron)
  - Zhongzheng Ren, Zhiding Yu, Xiaodong Yang, Ming-Yu Liu, Yong Jae Lee, Alexander G. Schwing, Jan Kautz. *CVPR 2020*

- SLV: Spatial Likelihood Voting for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/abs/2006.12884.pdf) 
  - Ze Chen, Zhihang Fu, Rongxin Jiang, Yaowu Chen, Xian-Sheng Hua. *CVPR 2020*

- High-Quality Proposals for Weakly Supervised Object Detection.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9069411) 
  - Gong Cheng, Junyu Yang, Decheng Gao, Lei Guo, Junwei Han. *TIP*

- Enabling Deep Residual Networks for Weakly Supervised Object Detection.
  [[pdf]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530120.pdf)
  [[Caffe2 Code]](https://github.com/shenyunhang/DRN-WSOD)
  [[PyTorch Code]](https://github.com/shenyunhang/DRN-WSOD-pytorch/tree/DRN-WSOD/projects/WSL)
  - Yunhang Shen, Rongrong Ji, Yan Wang, Zhiwei Chen, Feng Zheng, Feiyue Huang, Yunsheng Wu. *ECCV 2020*

-  Comprehensive Attention Self-Distillation for Weakly-Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/2010.12023.pdf)
  [[code]](https://github.com/DeLightCMU/CASD)
  - Zeyi Huang*, Yang Zou*, Vijayakumar Bhagavatula, and Dong Huang. *NeurIPS 2020*

#### 2019
-  C-MIL: Continuation Multiple Instance Learning for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1904.05647.pdf)
  [[code]](https://github.com/WanFang13/C-MIL)
  - Fang Wan, Chang Liu, Wei Ke, Xiangyang Ji, Jianbin Jiao, Qixiang Ye. *CVPR 2019*

-  Dissimilarity Coefficient Based Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1811.10016.pdf)
  - Aditya Arun, C.V. Jawahar, M. Pawan Kumar. *CVPR 2019*

-  Towards Precise End-to-end Weakly Supervised Object Detection Network.
  [[pdf]](https://arxiv.org/pdf/1911.12148.pdf)
  - Ke Yang, Dongsheng Li, Yong Dou. *ICCV 2019*

-  WSOD2: Learning Bottom-Up and Top-Down Objectness Distillation for Weakly-Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1909.04972.pdf)
  - Zhaoyang Zeng, Bei Liu, Jianlong Fu, Hongyang Chao, Lei Zhang. *ICCV 2019*

-  Weakly Supervised Object Detection With Segmentation Collaboration.
  [[pdf]](https://arxiv.org/pdf/1904.00551.pdf)
  - Xiaoyan Li, Meina Kan, Shiguang Shan, Xilin Chen. *ICCV 2019*

-  Weakly Supervised Object Detection With Segmentation Collaboration.
  [[pdf]](https://arxiv.org/pdf/1908.03792.pdf)
  - Satoshi Kosugi, Toshihiko Yamasaki, Kiyoharu Aizawa. *ICCV 2019*

-  C-MIDN: Coupled Multiple Instance Detection Network With Segmentation Guidance for Weakly Supervised Object Detection.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Gao_C-MIDN_Coupled_Multiple_Instance_Detection_Network_With_Segmentation_Guidance_for_ICCV_2019_paper.pdf)
  - Yan Gao, Boxiao Liu, Nan Guo, Xiaochun Ye, Fang Wan, Haihang You, Dongrui Fan. *ICCV 2019*

#### 2018
-  PCL: Proposal Cluster Learning for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1807.03342.pdf)
  [[code]](https://github.com/ppengtang/pcl.pytorch)
  - Peng Tang, Xinggang Wang, Song Bai, Wei Shen, Xiang Bai, Wenyu Liu, Alan Yuille. *TPAMI*

-  Min-Entropy Latent Model for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1902.06057.pdf)
  [[code]](https://github.com/WanFang13/MELM)
  - Fang Wan, Pengxu Wei, Jianbin Jiao, Zhenjun Han, Qixiang Ye. *CVPR 2018*

-  Zigzag Learning for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1804.09466.pdf)
  - Xiaopeng Zhang, Jiashi Feng, Hongkai Xiong, Qi Tian. *CVPR 2018*

-  W2F: A Weakly-Supervised to Fully-Supervised Framework for Object Detection.
  [[pdf]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_W2F_A_Weakly-Supervised_CVPR_2018_paper.pdf)
  - Yongqiang Zhang, Yancheng Bai, Mingli Ding, Yongqiang Li, Bernard Ghanem. *CVPR 2018*

-  Weakly Supervised Region Proposal Network and Object Detection.
  [[pdf]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Peng_Tang_Weakly_Supervised_Region_ECCV_2018_paper.pdf)
  - Peng Tang, Xinggang Wang, Angtian Wang, Yongluan Yan, Wenyu Liu, Junzhou Huang, Alan Yuille. *ECCV 2018*

-  TS2C: Tight Box Mining with Surrounding Segmentation Context for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1807.04897.pdf)
  - Yunchao Wei, Zhiqiang Shen, Bowen Cheng, Honghui Shi, Jinjun Xiong, Jiashi Feng, Thomas Huang. *ECCV 2018*

-  Collaborative Learning for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1802.03531.pdf)
  - Jiajie Wang, Jiangchao Yao, Ya Zhang, Rui Zhang. *IJCAI 2018*

#### 2017
-  Multiple Instance Detection Network With Online Instance Classifier Refinement.
  [[pdf]](https://arxiv.org/pdf/1704.00138.pdf)
  [[code]](https://github.com/ppengtang/oicr)
  - Peng Tang, Xinggang Wang, Xiang Bai, Wenyu Liu. *CVPR 2017*

#### 2016
-  Weakly Supervised Deep Detection Networks.
  [[pdf]](https://arxiv.org/abs/1511.02853)
  [[code]](https://github.com/hbilen/WSDDN)
  - Hakan Bilen, Andrea Vedaldi. *CVPR 2016*

### Others
-  Boosting Weakly Supervised Object Detection with Progressive Knowledge Transfer.
  [[pdf]](https://arxiv.org/pdf/2007.07986.pdf)
  [[code]](https://github.com/mikuhatsune/wsod_transfer)
  - Yuanyi Zhong, Jianfeng Wang, Jian Peng, Lei Zhang. *ECCV 2020*

-  C-WSL: Count-guided Weakly Supervised Localization.
  [[pdf]](https://arxiv.org/pdf/1711.05282.pdf)
  - Mingfei Gao, Ang Li, Ruichi Yu, Vlad I. Morariu, Larry S. Davis. *ECCV 2018*

## Tutorials and Talks
- ECCV 2020 tutorial on Weakly Supervised Learning in Computer Vision.
  [[link]](https://www.youtube.com/playlist?list=PLcD_yLvcdUll95mAnBDV0rZKhfClJMZMr)

## Benchmarks
- Weakly Supervised Object Detection. paperswithcode.
  [[link]](https://paperswithcode.com/task/weakly-supervised-object-detection)




