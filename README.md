# Awesome Curriculum Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Some bravo or inspiring research works on the topic of curriculum learning.

A curated list of awesome Curriculum Learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search)

#### Why Curriculum Learning?
Self-Supervised Learning has become an exciting direction in AI community. 
  - Bengio: "..." (ICML 2009)
  
Biological inspired learning scheme.
  - Learn the concepts by increasing complexity, in order to allow learner to exploit previously learned concepts and thus ease the abstraction of new ones.

## Contributing

Please help contribute this list by contacting [me](https://github.com/Openning07/awesome-curriculum-learning) or add [pull request](https://github.com/Openning07/awesome-curriculum-learning/pulls)

Markdown format:
```markdown
- Paper Name.
  [[pdf]](link) 
  [[code]](link)
  - Key Contribution(s)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents

### 2009
- Curriculum Learning.
  [[pdf]](https://qmro.qmul.ac.uk/xmlui/bitstream/handle/123456789/15972/Bengio%2C%202009%20Curriculum%20Learning.pdf?sequence=1&isAllowed=y)
  - "Rank the weights of the training examples, and use the rank to guide the order of presentation of examples to the learner."
  - Bengio, Yoshua and Louradour, J{\'e}r{\^o}me and Collobert, Ronan and Weston, Jason. *ICML 2009*

### 2015
- Self-Paced Curriculum Learning.
  [[pdf]](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14374/14349)
  - Jiang, Lu and Meng, Deyu and Zhao, Qian and Shan, Shiguang and Hauptmann, Alexander G. *AAAI 2015*

### 2017
- Self-Paced Learning: An Implicit Regularization Perspective.
  [[pdf]](https://www.researchgate.net/profile/Jian_Liang25/publication/303750070_Self-Paced_Learning_an_Implicit_Regularization_Perspective/links/5858e75b08ae3852d25555e3/Self-Paced-Learning-an-Implicit-Regularization-Perspective.pdf)
  - Fan, Yanbo and He, Ran and Liang, Jian and Hu, Bao-Gang. *AAAI 2017*
  
- Curriculum Dropout.
  [[pdf]](http://www.vision.jhu.edu/assets/MorerioICCV17.pdf) [[code]](https://github.com/pmorerio/curriculum-dropout)
  - Morerio, Pietro and Cavazza, Jacopo and Volpi, Riccardo and Vidal, Ren\'e and Murino, Vittorio. *ICCV 2017*

- Curriculum Domain Adaptation for Semantic Segmentation of Urban Scenes.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Zhang_Curriculum_Domain_Adaptation_ICCV_2017_paper.pdf) [[code]](https://github.com/YangZhang4065/AdaptationSeg)
  - Zhang, Yang and David, Philip and Gong, Boqing. *ICCV 2017*

### 2018
- Curriculum Learning by Transfer Learning: Theory and Experiments with Deep Networks.
  [[pdf]](https://arxiv.org/pdf/1802.03796.pdf)
  - "Sort the training examples based on the *performance* of a pre-trained network on a larger dataset,
    and then finetune the model to the dataset at hand."
  - Weinshall, Daphna and Cohen, Gad and Amir, Dan. *ICML 2018*

- Self-Paced Deep Learning for Weakly Supervised Object Detection.
  [[pdf]](https://arxiv.org/pdf/1605.07651.pdf)
  - Sangineto, Enver and Nabi, Moin and Culibrk, Dubravko and Sebe, Nicu. *TPAMI 2018*
  
- MentorNet: Learning Data-Driven Curriculum for Very Deep Neural Networks.
  [[pdf]](http://proceedings.mlr.press/v80/jiang18c/jiang18c.pdf) [[code]](https://github.com/google/mentornet)
  - Jiang, Lu and Zhou, Zhengyuan and Leung, Thomas and Li, Li-Jia and Li, Fei-Fei. *ICML 2018*
<p align="center">
  <img src="https://github.com/google/mentornet/blob/master/images/overview.png" alt="MentorNet" width="60%">
</p>

- CurriculumNet: Weakly Supervised Learning from Large-Scale Web Images.
  [[pdf]](https://arxiv.org/pdf/1808.01097.pdf) [[code]](https://github.com/MalongTech/research-curriculumnet)
  - Guo, Sheng and Huang, Weilin and Zhang, Haozhi and Zhuang, Chenfan and Dong, Dengke and Scott, Matthew and Huang, Dinglong. *ECCV 2018*

- Unsupervised Feature Selection by Self-Paced Learning Regularization.
  [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0167865518302782)
  - Zheng, Wei and Zhu, Xiaofeng and Wen, Guoqiu and Zhu, Yonghua and Yu, Hao and Gan, Jiangzhang. *Pattern Recognition Letters 2018*

- Learning to Teach with Dynamic Loss Functions.
  [[pdf]](https://papers.nips.cc/paper/7882-learning-to-teach-with-dynamic-loss-functions.pdf)
  - "A good teacher not only provides his/her students with qualified teaching materials (e.g., textbooks), but also sets up appropriate learning objectives (e.g., course projects and exams) considering different situations of a student."
  - Wu, Lijun Wu and Tian, Fei Tian and Xia, Yingce and Fan, Yang Fan and Qin, Tao and Lai, Jianhuang and Liu, Tie-Yan. *NeurIPS 2018*

### 2019
- Transferable Curriculum for Weakly-Supervised Domain Adaptation
  [[pdf]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/transferable-curriculum-aaai19.pdf) [[code]](https://github.com/thuml/TCL)
  - Shu, Yang and Cao, Zhangjie and Long, Mingsheng and Wang, Jianmin. *AAAI 2019*

- Dynamic Curriculum Learning for Imbalanced Data Classification.
  [[pdf]](https://arxiv.org/pdf/1901.06783.pdf)[[simple demo]](https://github.com/apeterswu/L2T_loss)
  - Wang, Yiru and Gan, Weihao and Wu, Wei and Yan, Junjie. *ICCV 2019*

- Guided Curriculum Model Adaptation and Uncertainty-Aware Evaluation for Semantic Nighttime Image Segmentation.
  [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Sakaridis_Guided_Curriculum_Model_Adaptation_and_Uncertainty-Aware_Evaluation_for_Semantic_Nighttime_ICCV_2019_paper.pdf)
  - Sakaridis, Christos and Dai, Dengxin and Gool Van Luc. *ICCV 2019*

- On The Power of Curriculum Learning in Training Deep Networks.
  [[pdf]](https://arxiv.org/pdf/1904.03626.pdf)
  - Hacohen, Guy and Weinshall, Daphna. *ICML 2019*

- Balanced Self-Paced Learning for Generative Adversarial Clustering Network.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ghasedi_Balanced_Self-Paced_Learning_for_Generative_Adversarial_Clustering_Network_CVPR_2019_paper.pdf)
  - Ghasedi, Kamran and Wang, Xiaoqian and Deng, Cheng and Huang, Heng. *CVPR 2019*
  
### 2020
- BBN: Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition.
  [[pdf]](https://arxiv.org/abs/1912.02413) [[code]](https://github.com/Megvii-Nanjing/BBN)
  - Zhou, Boyan and Cui, Quan and Wei, Xiu-Shen and Chen, Zhao-Min. *CVPR 2020*
<p align="center">
  <img src="http://bbs.cvmart.net/uploads/images/202004/03/21/LsQbBcInWZ.gif?imageView2/2/w/1240/h/0" alt="BBN" width="70%">
</p>

- Open Compound Domain Adaptation.
  [[pdf]](https://arxiv.org/abs/1909.03403) [[code]](https://github.com/zhmiao/OpenCompoundDomainAdaptation-OCDA)
  - Liu, Ziwei and Miao, Zhongqi and Pan, Xingang and Zhan, Xiaohang and Lin, Dahua and Yu, Stella X and Gong, Boqing. *CVPR 2020*
  <p align="center">
  <img src="https://bair.berkeley.edu/static/blog/ocda/figure_4.png" alt="OCDA" width="70%">
</p>

- Curriculum Manager for Source Selection in Multi-Source Domain Adaptation.
  [[pdf]](https://arxiv.org/pdf/2007.01261v1.pdf)[[code]](https://github.com/LoyoYang/CMSS)
  - Yang, Luyu and Balaji, Yogesh and Lim, Ser-Nam and Shrivastava, Abhinav. *ECCV 2020*
  
- Content-Consistent Matching for Domain Adaptive Semantic Segmentation.
  [[pdf]](https://arxiv.org/pdf/2007.01261v1.pdf) [[code]](https://github.com/Solacex/CCM)
  - "to acquire those synthetic images that share similar distribution with the real ones in the target domain, so that the domain gap can be naturally alleviated by employing the content-consistent synthetic images for training."
<p align="center">
  <img src="https://pic2.zhimg.com/80/v2-f6f3eb85a79f206b4f5524eaf43a71fd_1440w.jpg" alt="CMM" width="70%">
</p>
  - "not all the source images could contribute to the improvement of adaptation performance, especially at certain training stages."
  - Li, Guangrui and Kang, Guokiang and Liu, Wu and Wei, Yunchao and Yang, Yi . *ECCV 2020*

