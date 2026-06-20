# ( Reinforcement Learning + Computer Vision ) Papers
A curated list of papers applying Reinforcement Learning to Computer Vision tasks.
# Summary
- [Object Localization](#object-localization)
- [Image Instance Segmentation](#image-instance-segmentation)
- [Object Tracking](#object-tracking)
- [Image Registration](#image-registration)
- [Video Analysis](#video-analysis)
- [Survey](#survey)
- [Recent additions](#recent-additions)
- [Landmark Detection](#landmark-detection)


## Image Instance Segmentation
1985:
- Robert M Haralick and Linda G Shapiro. Image segmentation techniques. Computer vision, graphics, and image processing, 29(1):100–132 : https://www.sciencedirect.com/science/article/abs/pii/S0734189X85901537


1992 :
- Ronald J Williams. Simple statistical gradient-following algorithms for connectionist reinforcement learning. Machine learning, 8(3-4):229–256 : https://link.springer.com/article/10.1007/BF00992696


2006 :
- Farhang Sahba, Hamid R Tizhoosh, and Magdy MA Salama. A reinforcement learning framework for medical image segmentation. In The 2006 IEEE International Joint Conference on Neural Network Proceedings, pages 511–517. IEEE : https://ieeexplore.ieee.org/document/1716136
- Leo Grady. Random walks for image segmentation. IEEE transactions on pattern analysis and machine intelligence, 28(11):1768–1783 : https://ieeexplore.ieee.org/document/1704833

2007 :
- Farhang Sahba, Hamid R Tizhoosh, and Magdy MMA Salama. Application of opposition-based reinforcement learning in image segmentation. In 2007 IEEE Symposium on Computational Intelligence in Image and Signal Processing, pages 246–251. IEEE : https://www.researchgate.net/publication/4250708_Application_of_Opposition-Based_Reinforcement_Learning_in_Image_Segmentation

2015 :
- Matthew J. Hausknecht and Peter Stone. Deep recurrent q-learning for partially observable mdps. CoRR, abs/1507.06527 : https://arxiv.org/abs/1507.06527

2016 :
- Md Reza, Jana Kosecka, et al. Reinforcement learning for semantic segmentation in indoor scenes. arXiv preprint arXiv:1606.01178, : https://arxiv.org/abs/1606.01178
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages 1928–1937: http://proceedings.mlr.press/v48/mniha16.pdf

2017 :
- D. Carrera, F. Manganini, G. Boracchi, and E. Lanzarone. Defect detection in sem images of nanofibrous materials. IEEE Transactions on Industrial Informatics, 13(2):551–561 : https://boracchi.faculty.polimi.it/docs/2017_Anomaly_Detection_SEM.pdf

2018 :
- Gwangmo Song, Heesoo Myeong, and Kyoung Mu Lee. Seednet: Automatic seed generation with deep reinforcement learning for robust interactive segmentation. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 1760–1768 : https://openaccess.thecvf.com/content_cvpr_2018/papers/Song_SeedNet_Automatic_Seed_CVPR_2018_paper.pdf

2020 :
- Xuan Liao, Wenhao Li, Qisen Xu, Xiangfeng Wang, Bo Jin, Xiaoyun Zhang, Yanfeng Wang, and Ya Zhang. Iteratively-refined interactive 3d medical image segmentation with multi-agent reinforcement learning. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 9394–9402: https://arxiv.org/abs/1911.10334
- Zhiqiang Tian, Xiangyu Si, Yaoyue Zheng, Zhang Chen, and Xiaojian Li. Multi-step medical image segmentation based on reinforcement learning. JOURNAL OF AMBIENT INTELLIGENCE AND HUMANIZED COMPUTING : https://www.researchgate.net/publication/340239080_Multi-step_medical_image_segmentation_based_on_reinforcement_learning
- Wen-Hsuan Chu and Kris M. Kitani. Neural batch sampling with reinforcement learning for semi-supervised anomaly detection. In European Conference on Computer Vision, pages 751–766 : https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123710749.pdf



## Object Tracking
2005 :
- Kye Kyung Kim, Soo Hyun Cho, Hae Jin Kim, and Jae Yeon Lee. Detecting and tracking moving object using an active camera. In The 7th International Conference on Advanced Communication Technology, 2005, ICACT 2005., volume 2, pages 817–820. IEEE, 2005 : https://www.researchgate.net/publication/4153839_Detecting_and_tracking_moving_object_using_an_active_camera

2015 :
- Timothy P Lillicrap, Jonathan J Hunt, Alexander Pritzel, Nicolas Heess, Tom Erez, Yuval Tassa, David Silver, and Daan Wierstra. Continuous control with deep reinforcement learning. arXiv preprint arXiv:1509.02971 : https://arxiv.org/abs/1509.02971
- Yu Xiang, Alexandre Alahi, and Silvio Savarese. Learning to track: Online multi-object tracking by decision making. In Proceedings of the IEEE international conference on computer vision, pages 4705–4713 : https://cvgl.stanford.edu/papers/xiang_iccv15.pdf

2016 :
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages 1928–1937: https://proceedings.mlr.press/v48/mniha16.html

2017 :
- Wenhan Luo, Peng Sun, Fangwei Zhong, Wei Liu, Tong Zhang, and Yizhou Wang. End-to-end active object tracking via reinforcement learning. arXiv preprint arXiv:1705.10561 : https://arxiv.org/abs/1705.10561
- Da Zhang, Hamid Maei, Xin Wang, and Yuan-Fang Wang. Deep reinforcement learning for visual object tracking in videos. arXiv preprint arXiv:1701.08936 : https://arxiv.org/pdf/1701.08936.pdf

2018 :
- Minghao Guo, Jiwen Lu, and Jie Zhou. Dual-agent deep reinforcement learning for deformable face tracking. In Proceedings of the European Conference on Computer Vision (ECCV), pages 768–783 : https://openaccess.thecvf.com/content_ECCV_2018/papers/Minghao_Guo_Dual-Agent_Deep_Reinforcement_ECCV_2018_paper.pdf
- Liangliang Ren, Xin Yuan, Jiwen Lu, Ming Yang, and Jie Zhou. Deep reinforcement learning with iterative shift for visual tracking. In Proceedings of the European Conference on Computer Vision (ECCV), pages 684–700 : https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Deep_Reinforcement_Learning_ECCV_2018_paper.pdf
- Boyu Chen, Dong Wang, Peixia Li, Shuang Wang, and Huchuan Lu. Real-time’actor- critic’tracking. In Proceedings of the European Conference on Computer Vision (ECCV), pages 318–334 : https://openaccess.thecvf.com/content_ECCV_2018/html/Boyu_Chen_Real-time_Actor-Critic_Tracking_ECCV_2018_paper.html
- Liangliang Ren, Jiwen Lu, Zifeng Wang, Qi Tian, and Jie Zhou. Collaborative deep reinforcement learning for multi-object tracking. In Proceedings of the European Conference on Computer Vision (ECCV), pages 586–602 : https://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Collaborative_Deep_Reinforcement_ECCV_2018_paper.pdf
- Ming-xin Jiang, Chao Deng, Zhi-geng Pan, Lan-fang Wang, and Xing Sun. Multiobject tracking in videos based on lstm and deep reinforcement learning. Complexity : https://www.hindawi.com/journals/complexity/2018/4695890/

 
2019 :
- Matteo Dunnhofer, Niki Martinel, Gian Luca Foresti, and Christian Micheloni. Visual tracking by means of deep reinforcement learning and an expert demonstrator. In Proceedings of the IEEE International Conference on Computer Vision Workshops : https://arxiv.org/abs/1909.08487
- Mingxin Jiang, Tao Hai, Zhigeng Pan, Haiyan Wang, Yinjie Jia, and Chao Deng. Multi-agent deep reinforcement learning for multi-object tracker. IEEE Access, 7:32400–32407 : https://ieeexplore.ieee.org/document/8653482

## Object Detection
2012 :
- A. Geiger, P. Lenz, and R. Urtasun. Are we ready for autonomous driving? the kitti vision benchmark suite. In 2012 IEEE Conference on Computer Vision and Pattern Recognition, pages 3354–3361: https://www.cvlibs.net/publications/Geiger2012CVPR.pdf

2015 :
- Juan C Caicedo and Svetlana Lazebnik. Active object localization with deep reinforcement learning. In Proceedings of the IEEE international conference on computer vision, pages 2488–2496 : https://arxiv.org/abs/1511.06015

2016 :
- Miriam Bellver, Xavier Gir´o-i Nieto, Ferran Marqu´es, and Jordi Torres. Hierarchical object detection with deep reinforcement learning. arXiv preprint arXiv:1611.03718 : https://arxiv.org/abs/1611.03718
- Stefan Mathe, Aleksis Pirinen, and Cristian Sminchisescu. Reinforcement learning for visual object detection. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 2894–2902 : https://openaccess.thecvf.com/content_cvpr_2016/html/Mathe_Reinforcement_Learning_for_CVPR_2016_paper.html
- Zequn Jie, Xiaodan Liang, Jiashi Feng, Xiaojie Jin, Wen Lu, and Shuicheng Yan. Tree-structured reinforcement learning for sequential object localization. In Advances in Neural Information Processing Systems, pages 127–135 : https://arxiv.org/abs/1703.02710

2017 : 
- Gabriel Maicas, Gustavo Carneiro, Andrew P Bradley, Jacinto C Nascimento, and Ian Reid. Deep reinforcement learning for active breast lesion detection from dce-mri. In International conference on medical image computing and computer-assisted intervention, pages 665–673. Springer : https://cs.adelaide.edu.au/~gabriel/DRL_maicasEtAl.pdf

2018 :
- Yan Wang, Lei Zhang, Lituan Wang, and Zizhou Wang. Multitask learning for object localization with deep reinforcement learning. IEEE Transactions on Cognitive and Developmental Systems, 11(4):573–580 : https://ieeexplore.ieee.org/document/8570827
- Aleksis Pirinen and Cristian Sminchisescu. Deep reinforcement learning of region proposal networks for object detection. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 6945–6954 : https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1543.pdf
- Morgane Ayle, Jimmy Tekli, Julia El-Zini, Boulos El-Asmar, and Mariette Awad. Bar-a reinforcement learning agent for bounding-box automated refinement : https://ojs.aaai.org/index.php/AAAI/article/view/5639

2020 :
- Burak Uzkent, Christopher Yeh, and Stefano Ermon. Efficient object detection in large images using deep reinforcement learning. In The IEEE Winter Conference on Applications of Computer Vision, pages 1824–1833 : https://arxiv.org/abs/1912.03966
- Fernando Navarro, Anjany Sekuboyina, Diana Waldmannstetter, Jan C Peeken, Stephanie E Combs, and Bjoern H Menze. Deep reinforcement learning for organ localization in ct. arXiv preprint arXiv:2005.04974 : 
- Lijie Liu, Chufan Wu, Jiwen Lu, Lingxi Xie, Jie Zhou, and Qi Tian. Reinforced axial refinement network for monocular 3d object detection. In European Conference on Computer Vision ECCV, pages 540–556 : https://arxiv.org/abs/2008.13748

## Image Registration
2000 :
- Philippe Th´evenaz and Michael Unser. Optimization of mutual information for mul-
tiresolution image registration. IEEE transactions on image processing, 9(12):2083–
2099 : https://infoscience.epfl.ch/record/63070?ln=fr

2013 :
- Tayebeh Lotfi, Lisa Tang, Shawn Andrews, and Ghassan Hamarneh. Improving probabilistic image registration via reinforcement learning and uncertainty evaluation. In International Workshop on Machine Learning in Medical Imaging, pages 187–194. Springer : https://www.researchgate.net/publication/268789684_Improving_Probabilistic_Image_Registration_via_Reinforcement_Learning_and_Uncertainty_Evaluation

2016 :
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages 1928–1937 : https://proceedings.mlr.press/v48/mniha16.html

2017 :
- Rui Liao, Shun Miao, Pierre de Tournemire, Sasa Grbic, Ali Kamen, Tommaso Mansi, and Dorin Comaniciu. An artificial agent for robust image registration. In Thirty-First AAAI Conference on Artificial Intelligence : https://arxiv.org/abs/1611.10336
- Kai Ma, Jiangping Wang, Vivek Singh, Birgi Tamersoy, Yao-Jen Chang, Andreas Wimmer, and Terrence Chen. Multimodal image registration with deep context reinforcement learning. In International Conference on Medical Image Computing and Computer-Assisted Intervention, pages 240–248. Springer : https://www.researchgate.net/publication/319462712_Multimodal_Image_Registration_with_Deep_Context_Reinforcement_Learning
- Julian Krebs, Tommaso Mansi, Herv´e Delingette, Li Zhang, Florin C Ghesu, Shun Miao, Andreas K Maier, Nicholas Ayache, Rui Liao, and Ali Kamen. Robust non-rigid registration through agent-based action learning. In International Conference
on Medical Image Computing and Computer-Assisted Intervention, pages 344–352. Springer : https://www.semanticscholar.org/paper/Robust-Non-rigid-Registration-Through-Agent-Based-Krebs-Mansi/f8ef0f45de2d61a2b5b82cad79c1703a5c37f405
- Rui Liao, Shun Miao, Pierre de Tournemire, Sasa Grbic, Ali Kamen, Tommaso Mansi, and Dorin Comaniciu. An artificial agent for robust image registration. In Thirty-First AAAI Conference on Artificial Intelligence : https://arxiv.org/abs/1611.10336

2018 :
- Shanhui Sun, Jing Hu, Mingqing Yao, Jinrong Hu, Xiaodong Yang, Qi Song, and Xi Wu. Robust multimodal image registration using deep recurrent reinforcement learning. In Asian Conference on Computer Vision, pages 511–526. Springer : https://arxiv.org/abs/2002.03733

## Video Analysis
2015 :
- John Schulman, Sergey Levine, Pieter Abbeel, Michael Jordan, and Philipp Moritz. Trust region policy optimization. In International conference on machine learning, pages 1889–1897 : https://proceedings.mlr.press/v37/schulman15.html
- Max Jaderberg, Karen Simonyan, Andrew Zisserman, et al. Spatial transformer networks. In Advances in neural information processing systems, pages 2017–2025 : https://papers.nips.cc/paper_files/paper/2015/hash/33ceb07bf4eeb3da587e268d663aba1a-Abstract.html

2016 :
- Fanyi Xiao and Yong Jae Lee. Track and segment: An iterative unsupervised approach for video object proposals. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 933–942 : https://www.researchgate.net/publication/311611179_Track_and_Segment_An_Iterative_Unsupervised_Approach_for_Video_Object_Proposals
- Farhang Sahba. Deep reinforcement learning for object segmentation in video sequences. In 2016 International Conference on Computational Science and Computational Intelligence (CSCI), pages 857–860. IEEE : https://www.semanticscholar.org/paper/Deep-Reinforcement-Learning-for-Object-Segmentation-Sahba/5889b83977ee5464bb14e1d51e26961b1d91234f
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages
1928–1937 : https://proceedings.mlr.press/v48/mniha16.html
- Hado Van Hasselt, Arthur Guez, and David Silver. Deep reinforcement learning with double q-learning. In Thirtieth AAAI conference on artificial intelligence : https://dl.acm.org/doi/10.5555/3016100.3016191
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages 1928–1937, 2016 : https://proceedings.mlr.press/v48/mniha16.html

2018 :
- Daochang Liu and Tingting Jiang. Deep reinforcement learning for surgical gesture segmentation and classification. In International conference on medical image computing and computer-assisted intervention, pages 247–255. Springer : https://arxiv.org/abs/1806.08089
- Junwei Han, Le Yang, Dingwen Zhang, Xiaojun Chang, and Xiaodan Liang. Reinforcement cutting-agent learning for video object segmentation. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 9080–9089, 2018.
- Vikash Goel, Jameson Weng, and Pascal Poupart. Unsupervised video object segmentation for deep reinforcement learning. In Advances in Neural Information Processing Systems, pages 5683–5694 : https://arxiv.org/abs/1805.07780
- Yansong Tang, Yi Tian, Jiwen Lu, Peiyang Li, and Jie Zhou. Deep progressive reinforcement learning for skeleton-based action recognition. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 5323–5332 : https://openaccess.thecvf.com/content_cvpr_2018/papers/Tang_Deep_Progressive_Reinforcement_CVPR_2018_paper.pdf
- Kaiyang Zhou, Yu Qiao, and Tao Xiang. Deep reinforcement learning for unsupervised video summarization with diversity-representativeness reward. In Thirty-Second AAAI Conference on Artificial Intelligence : https://arxiv.org/abs/1801.00054
- Kaiyang Zhou, Tao Xiang, and Andrea Cavallaro. Video summarisation by classification with deep reinforcement learning. arXiv preprint arXiv:1807.03089 : https://arxiv.org/abs/1807.03089

2020 :
- Yujiang Wang, Mingzhi Dong, Jie Shen, Yang Wu, Shiyang Cheng, and Maja Pantic. Dynamic face video segmentation via reinforcement learning. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 6959–
6969 : https://www.researchgate.net/publication/343465859_Dynamic_Face_Video_Segmentation_via_Reinforcement_Learning
- Giuseppe Vecchio, Simone Palazzo, Daniela Giordano, Francesco Rundo, and Concetto Spampinato. Mask-rl: Multiagent video object segmentation framework through reinforcement learning. IEEE Transactions on Neural Networks and Learning Systems : https://ieeexplore.ieee.org/document/8967004

## Landmark Detection
2010 :
- Antonio Criminisi, Jamie Shotton, Duncan Robertson, and Ender Konukoglu. Regression forests for efficient anatomy detection and localization in ct studies. In International MICCAI Workshop on Medical Computer Vision, pages 106–117. Springer, 2010.

2015 :
- Justin Girard and M Reza Emami. Concurrent markov decision processes for robot team learning. Engineering applications of artificial intelligence, 39:223–234 : https://www.sciencedirect.com/science/article/abs/pii/S0952197614002991


2016 :
- Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Timothy Lillicrap, Tim Harley, David Silver, and Koray Kavukcuoglu. Asynchronous methods for deep reinforcement learning. In International conference on machine learning, pages 1928–1937 : https://proceedings.mlr.press/v48/mniha16.html

2017 :
- Florin-Cristian Ghesu, Bogdan Georgescu, Yefeng Zheng, Sasa Grbic, Andreas Maier, Joachim Hornegger, and Dorin Comaniciu. Multi-scale deep reinforcement learning for real-time 3d-landmark detection in ct scans. IEEE transactions on pattern analysis and machine intelligence, 41(1):176–189, 2017 : https://pubmed.ncbi.nlm.nih.gov/29990011/

2019 :
- Amir Alansary, Ozan Oktay, Yuanwei Li, Loic Le Folgoc, Benjamin Hou, Ghislain Vaillant, Konstantinos Kamnitsas, Athanasios Vlontzos, Ben Glocker, Bernhard Kainz, et al. Evaluating reinforcement learning agents for anatomical landmark detection. Medical image analysis, 53:156–164 : https://pubmed.ncbi.nlm.nih.gov/30784956/
- Walid Abdullah Al and Il Dong Yun. Partial policy-based reinforcement learning for anatomical landmark localization in 3d medical images. IEEE transactions on medical imaging : https://ieeexplore.ieee.org/abstract/document/8863403
- Athanasios Vlontzos, Amir Alansary, Konstantinos Kamnitsas, Daniel Rueckert, and Bernhard Kainz. Multiple landmark detection using multi-agent reinforcement learning. In International Conference on Medical Image Computing and Computer-Assisted Intervention, pages 262–270. Springer : https://arxiv.org/abs/1907.00318

## Survey
2021
- Deep Reinforcement Learning in Computer Vision: A Comprehensive Survey: https://arxiv.org/abs/2108.11510



## Recent additions
2026 :
- Fatma Youssef Mohammed, Grzegorz Malczyk, and Kostas Alexis. Fast Human Attention Prediction for Fixation-guided Active Perception in Autonomous Navigation. arXiv preprint arXiv:2606.20491v1 : https://arxiv.org/abs/2606.20491v1
- Chengwen Liu, Hao Peng, Jisheng Dang, Hong Peng, Bin Hu, and Tat-Seng Chua. CARE: Competence-Aware Reward Shaping for Adaptive Reasoning Length in Video-MLLMs. arXiv preprint arXiv:2606.19927v1 : https://arxiv.org/abs/2606.19927v1
- Seyed Alireza Azimi, Homayoon Farrahi, Abhishek Naik, Colin Bellinger, and A. Rupam Mahmood. Benchmarking Action Spaces in Reinforcement Learning for Vision-based Robotic Manipulation. arXiv preprint arXiv:2606.18594v1 : https://arxiv.org/abs/2606.18594v1
- Mukund Khanna, Raj Singh Yadav, and Kunal Singh. ProductConsistency: Improving Product Identity Preservation in Instruction-Based Image Editing via SFT and RL. arXiv preprint arXiv:2606.19103v1 : https://arxiv.org/abs/2606.19103v1
- Yilian Liu, Sicong Leng, Guoshun Nan, Junyi Zhu, Jiayu Huang, Minghao Sun, Xuancheng Zhu, Yisong Chen, Zexian Wei, and Xiaofeng Tao. See First, Answer Later: Visual Evidence Pre-Alignment via Sufficiency-Driven RL. arXiv preprint arXiv:2606.17678v1 : https://arxiv.org/abs/2606.17678v1
- Saraswathy Amjith. Self-Questioning Vision-Language Models: Reinforcement Learning for Compositional Visual Reasoning. arXiv preprint arXiv:2606.15651v1 : https://arxiv.org/abs/2606.15651v1
- Mohamed Bayan Kmainasi, Mucahid Kutlu, Ali Ezzat Shahroor, Abul Hasnat, and Firoj Alam. Adapting Reinforcement Learning with Chain-of-Thought Supervision for Explainable Detection of Hateful and Propagandistic Memes. arXiv preprint arXiv:2606.15307v1 : https://arxiv.org/abs/2606.15307v1

# Contribute
A paper is missing ? don't hesitate to open an issue or pull-request to keep the repository updated 😊
