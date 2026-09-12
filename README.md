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
- Haiwen Diao, Jiahao Wang, Chenjing Ding, Hanming Deng, Jiangnan Chen, Ruixi Zhang, Ruohui Wang, Wenwen Tong, Xiangyu Fan, Yubo Wang, Yue Zhu, Yuwei Niu, Zhengqi Bai, Zhiqian Lin, Zhitao Yang, Zhongang Cai, Bo Yang, Chen Feng, Chengguang Lv, Guangjia Liu, Guanlin Wang, Hanyu Zhang, Haojia Yu, Hongcan Xiao, Hongli Wang, Huan Wu, Huaping Zhong, Jian Fang, Jianan Fan, Jiaqi Li, Jiefan Lu, Jing Zuo, Jingcheng Ni, Junxiang Xu, Linjun Dai, Mutian Xu, Peishen Yan, Penghao Wu, Ruijie Mao, Ruisi Wang, Shihao Bai, Shuang Yang, Shuya Yang, Shuyan Zheng, Silei Wu, Siying Li, Tao Chu, Tianbo Zhong, Tongxi Zhou, Weichao Luo, Weichen Fan, Wenhao Jia, Wenjie Gao, Xiangli Kong, Yan Li, Yang Yong, Zimo Wen, Zixuan Qian, Wenxiu Sun, Ruihao Gong, Quan Wang, Lewei Lu, Lei Yang, Ziwei Liu, Dahua Lin. SenseNova-U1.5: Towards Native Unified Visual Intelligence. arXiv preprint arXiv:2609.11929v1 : https://arxiv.org/abs/2609.11929v1
- Niange Yu, Ye Tian, Biaolong Chen, Miao Lu, Aixi Zhang, Hao Jiang, Yunhai Tong, Pipei Huang. Harnessing Intrinsic Subject-Aware Attention for Controllable Multi-Subject Video Generation. arXiv preprint arXiv:2609.11507v1 : https://arxiv.org/abs/2609.11507v1
- Meng Luo, Yicheng Liu, Jiahao Wang, Yuanxing Zhang, Xin Tao, Pengfei Wan, Kun Gai, Hao Fei. From Evaluation to Enhancement: Benchmarking and Improving Think-with-Video Reasoning for Video Generative Models. arXiv preprint arXiv:2609.11242v1 : https://arxiv.org/abs/2609.11242v1
- Yang Wu, Stefano Petrangeli, Ishita Dasgupta, Yu Shen. CamPilot: A Multi-Agent Cinematic Assistant for Camera-Controlled Movie Generation. arXiv preprint arXiv:2609.10943v1 : https://arxiv.org/abs/2609.10943v1
- Nisarga Nilavadi, Ralf Römer, Moritz Reuss, Michael Krawez, Tobias Jülg, Angela P. Schoellig, Rudolf Lioutikov, Wolfram Burgard. DUET-DINO: Simultaneous Cross-View World Modeling for Latent Planning in Robot Manipulation. arXiv preprint arXiv:2609.10506v1 : https://arxiv.org/abs/2609.10506v1
- Sheng Li, Peng Liu, Qianqian Zhang, Tiancheng Zhao. VLX-VR: An Agentic-Aware Video Reasoning Model. arXiv preprint arXiv:2609.09985v1 : https://arxiv.org/abs/2609.09985v1
- Zengjue Chen, Peidong Liu, Jiawei Li, Qi Wang. HaWMPO: Hallucination-Aware World Model-based Policy Optimization for Generalist Robot Policy. arXiv preprint arXiv:2609.09941v1 : https://arxiv.org/abs/2609.09941v1
- Yansen Han, Shengyi Liao, Peng Sun, Deyuan Liu, Yuanxing Zhang, Pengfei Wan, Tao Lin. FlowCPO: A Unified Divergence View of Preference Alignment for Flow Models. arXiv preprint arXiv:2609.09905v1 : https://arxiv.org/abs/2609.09905v1
- Zhenxin Qin, Peng Shi, Cong Han, Yinlong Qian, Zequn Jie, Lin Ma. Video-MOPD: Multi-Teacher On-Policy Distillation for Video Understanding. arXiv preprint arXiv:2609.09300v1 : https://arxiv.org/abs/2609.09300v1
- Yang Wan, Xihang Yue, Zhirui Liu, Ziyuan Chu, Shuxun Wang, Yuhan Chen, Xiaonan Jiang, Xukun Zhu, Yubo Dong, Linchao Zhu. No Free Checker: A Survey of Verifiers for Robot Policies. arXiv preprint arXiv:2609.09250v1 : https://arxiv.org/abs/2609.09250v1
- Saurbh Singh Jamwal, Nived Chebrolu. Learning to Fly: Stable Vision-Guided UAV Servoing with Compact Target-Centric Cues and Reinforcement Learning. arXiv preprint arXiv:2609.09234v1 : https://arxiv.org/abs/2609.09234v1
- Yuncong Yang, Zhengtao Han, Furkan Ozyurt, Zeyuan Yang, Han Yang, Junyi Cao, Haoyu Zhen, Yilun Du, Chuang Gan. SyncWorld: Visual Calibration Enables World Models as Zero-Shot Simulators. arXiv preprint arXiv:2609.09155v1 : https://arxiv.org/abs/2609.09155v1
- Linnan Zhao, Xu Liu, Lingling Li, Licheng Jiao, Fang Liu, Wenping Ma. SeGDeP: Semantic- and Geometric-Aware Decoupled Prompts for Reasoning Segmentation. arXiv preprint arXiv:2609.08867v1 : https://arxiv.org/abs/2609.08867v1
- Aoting Zhang, Mingze Gao, Dongbao Yang, Longyi Chen, Daoxin Zhang, Yi Wu, Yao Hu, Yu Zhou. From Glance to Scrutiny: Progressive Distortion Reasoning for Fine-Grained Image Quality Assessment. arXiv preprint arXiv:2609.08316v1 : https://arxiv.org/abs/2609.08316v1
- Bozhou Li, Jiahang Zhang, Yue Ding, Yushuo Guan, Bohan Zeng, Yiyan Ji, Xinlong Chen, Yang Shi, Yifan Dai, Yuran Wang, Chengzhuo Tong, Pengfei Wan, Yuanxing Zhang, Wentao Zhang. Human-Centric Image Captioning with Subject-Centered Spatial Understanding. arXiv preprint arXiv:2609.08300v1 : https://arxiv.org/abs/2609.08300v1
- Vishwas Sathish, Viresh Ranjan, Xinliang Zhu, Arnab Dhua, Douglas Gray. Eliciting Self-Verification in Multimodal Reasoning Agents with Reinforcement Learning. arXiv preprint arXiv:2609.08025v1 : https://arxiv.org/abs/2609.08025v1
- Wanli Liuchen, Fangyuan Wang, Bin Li, Anqing Duan, Yunhui Liu, Peng Zhou, David Navarro-Alarcon. Phase-and-First-Arrival VLM Feedback for Sparse-Reward Reinforcement Learning in Surgical Manipulation. arXiv preprint arXiv:2609.07211v1 : https://arxiv.org/abs/2609.07211v1
- Zhiwei Ning, Zhen Zhou, Puhua Jiang, Xintong Han, Gengming Zhang, Jie Yang, Zhonglong Zheng, Yuanjie Zheng, Wei Liu, Chunchao Guo. Flow3D-OPD: Multi-Teacher On-Policy Distillation for 3D Geometry Generation with Flow-Matching Diffusion Transformer. arXiv preprint arXiv:2609.07137v1 : https://arxiv.org/abs/2609.07137v1
- Jiangning Zhu, Bowen Li, Shenyu Qiao, Yima Gu, Zhao Zhang, Yuhui Yuan, Shixia Liu. Detect Anything in Graphic Design: Element-Level Rewards for Autoregressive Detection. arXiv preprint arXiv:2609.07072v1 : https://arxiv.org/abs/2609.07072v1
- Jia-Jen Lee, Shih-Yen Hou, Kee Koon Ng, Wei-Chun Wang, Shih-Sheng Chang. CARDEA: Auditable Reasoning Grounded in Spatial Evidence for End-to-End Coronary Angiography Interpretation. arXiv preprint arXiv:2609.06931v1 : https://arxiv.org/abs/2609.06931v1
- Yinming Huang, Shuyuan Tu, Xi Yan, Jiahao Zhan, Zihan Yang, Zhen Xing, Hui Zhang, Tiehua Zhang, Yu-Gang Jiang, Zuxuan Wu. Agentic Visual Generation: From Generative Models to Agentic Control. arXiv preprint arXiv:2609.06758v1 : https://arxiv.org/abs/2609.06758v1
- Xiao Zhang, Wang Zeng, Sheng Jin, Wentao Liu, Chen Qian, Shichao Kan. Thinking with Cameras: Active Visual Reasoning via Dynamic Viewpoint Control for Surveillance Video Understanding. arXiv preprint arXiv:2609.06475v1 : https://arxiv.org/abs/2609.06475v1
- Yangyang Xie, Ke Hao, Jiaqi Liu, Yun Gu, Xinglin Zhang. Separating Capability from Confidence: Grounded Dual-State Calibration for GRPO-Trained Medical Vision-Language Models. arXiv preprint arXiv:2609.06419v1 : https://arxiv.org/abs/2609.06419v1
- Junyi Hu, Shuaihang Yuan, Yi Fang. CST-WM: A Causally Structured World Model for Embodied Visual Tracking. arXiv preprint arXiv:2609.06302v1 : https://arxiv.org/abs/2609.06302v1
- Ting Huang, Yue Huang, Zeyu Zhang, Shuicheng Yan, Hao Tang. MobileVLA-R1 2.0: RL-Enhanced Reasoning for Mobile Robot Control. arXiv preprint arXiv:2609.06251v1 : https://arxiv.org/abs/2609.06251v1
- Hao He, Chengcheng Hu, Zirun Su, Heng Zhang, Haisong Liu, Jinke Li, Haochen Tian, Zhenwei Shen, Hongyang Li, Zhichao Li, Yunchen Yang, Bochao Huang, Siyu Zhang, Kuangye Chen, Xiongjie Zhang, Wentao Dai, Hengchen Dai, Siyuan Liu, Zehao Huang, Naiyan Wang. DriveZero: End-to-End Driving Beyond Human Demonstrations. arXiv preprint arXiv:2609.06055v1 : https://arxiv.org/abs/2609.06055v1
- Xin Xie, Fan Zhang, Dong Gong. Test-Time Weak-to-Strong Alignment: Transferring Implicit Rewards from Weak to Strong Flow Models. arXiv preprint arXiv:2609.05968v1 : https://arxiv.org/abs/2609.05968v1
- Jiaoyang Chen, Bin Hu, Jingyu Hu, Kun Zhou, Qin Zhang, Zhengzhe Liu. FACT: A Forensic Agent with Compiled Tool-Use Trajectories for AI-Generated Image Detection. arXiv preprint arXiv:2609.05876v1 : https://arxiv.org/abs/2609.05876v1
- Yibin Wang, Zehan Wang, Junshu Tang, Zhimin Li, Yujie Zhou, Jiazi Bu, Pengyang Ling, Feng Han, Zhixiong Zhang, Long Xing, Shengyuan Ding, Ziang Li, Cheng Jin, Yuhang Zang, Jiaqi Wang, Tianyu Pang. WorldReward: Reward Modeling for Camera-Conditioned World Models. arXiv preprint arXiv:2609.03952v1 : https://arxiv.org/abs/2609.03952v1
- Marco Cipriano, Leonardo Zini, Alexandra Schild, Valentin Teutschbein, Afsana Mimi, Marcella Cornia, Lorenzo Baraldi, Gerard de Melo. SVG-Score: Human-Aligned Evaluation of Text-to-SVG Generation. arXiv preprint arXiv:2609.03806v1 : https://arxiv.org/abs/2609.03806v1
- Yijun Yang, Shenghe Zheng, Wenbo Li, Jianhui Liu, Haoze Sun, Yanbing Zhang, Jiaxiu Jiang, Lin Song, Haoyang Huang, Nan Duan, Lei Zhu. Unfold The World: Factorize 4D Properties in Reinforcing Spatial Reasoning. arXiv preprint arXiv:2609.03729v1 : https://arxiv.org/abs/2609.03729v1
- Juntao Xu, Shihong Li, Hoi Fan Au, Ning Zhu. ToPO: Token-Conditioned Preference Routing for Attention-Based Latent Diffusion Models. arXiv preprint arXiv:2609.03688v1 : https://arxiv.org/abs/2609.03688v1
- Alejandro Barón García, Feng Wang, Emilia Garcia Casademont, Han Xiao. Jina-OCR-v1: Efficient Document Parsing with Speculative Decoding and Dense Verifiable Rewards. arXiv preprint arXiv:2609.03181v1 : https://arxiv.org/abs/2609.03181v1
- Adrienne Deganutti, Purvanshi Mehta, Simon Hadfield, Andrew Gilbert. GDB-Reward: From Evaluation Metrics to Training Rewards for Graphic Design. arXiv preprint arXiv:2609.02813v1 : https://arxiv.org/abs/2609.02813v1
- Song Jin, Zhongtao Jiang, Chenglei Shen, Huanxuan Liao, Haozhe Chi, Zhiwei Wang, Kun Xu, Yong Liu. Allocate Before You Embed: Adaptive Visual Input Allocation for Video Embeddings. arXiv preprint arXiv:2609.01778v1 : https://arxiv.org/abs/2609.01778v1
- Giovanni Bonetta, Matteo Merler, Davide Zago, Rossella Cancelliere, Bernardo Magnini. Selective Agent Guidance via Entropy: Learning Autonomous Policies from Imperfect VLM Teachers. arXiv preprint arXiv:2609.01567v2 : https://arxiv.org/abs/2609.01567v2
- Christian Greisinger, Zhixue Zhao, Steffen Eger. EdiTikZ: Scientific Figure Editing from Revision Trajectories. arXiv preprint arXiv:2609.01409v1 : https://arxiv.org/abs/2609.01409v1
- Jiayu Ding, Zhuodong Liu, Lei Zhang, Manyu Xiong, Hongbo Jin, Haoran Tang, Hongbo Zhang, Changen Zhu, Wenbo Xing. Dyn-3D: Unveiling and Resolving Ego-Motion Ambiguity in Vision-Language Models. arXiv preprint arXiv:2609.01059v1 : https://arxiv.org/abs/2609.01059v1
- Ahmad Alfan Alfian Irfan, Nur Ahmad Khatim, Mansur Arief. A Closed-Loop Evaluation of Capability Loss and Recovery in Compressed Driving Policies. arXiv preprint arXiv:2609.00718v1 : https://arxiv.org/abs/2609.00718v1
- Jongyeop Hyun, Taeyoung Kim, Hyounghun Kim. Controllable Image Captioning with Prompt-Conditioned Scene Rewards. arXiv preprint arXiv:2609.00709v1 : https://arxiv.org/abs/2609.00709v1
- Suryaansh Jain, Rahasya Barkur, Vishal G, Ryan Rossi, Franck Dernoncourt, Jack Wang, Koustava Goswami, Nedim Lipka, Puneet Mathur, Samyadeep Basu, Seunghyun Yoon. A Glance Is All You Need: Single-Pass Fine-Grained Image Captioning with SimLoss. arXiv preprint arXiv:2609.00591v1 : https://arxiv.org/abs/2609.00591v1
- Ce Zhang, Jing Bi, Jinxi He, Jianshu Zhang, Jingyang Lin, Yunzhong Xiao, Minghao Fu, Yaqi Xie, Zhentao Xie, Weicong Chen, Katia Sycara, Ming Zhou. StreamScout: Learning When to Look Deeper for Streaming Video Understanding. arXiv preprint arXiv:2609.00291v1 : https://arxiv.org/abs/2609.00291v1
- Jiashu Zhu, Yanhao Zheng, Ruitian Tian, Rujing Dang, Shen Zhang, Bingze Song, Jiachen Lei, Ruimin Lin, Jiahong Wu, Xiangxiang Chu. DreamX-Creator: Democratizing Native Audio-Video Generation at 2K Resolution. arXiv preprint arXiv:2608.31106v1 : https://arxiv.org/abs/2608.31106v1
- Xingjian Wang, Shijian Wang, Yibo Wang, Zihao Yu, Runhao Fu, Xuelian Cheng, Zongyuan Ge. Learning Compositional Spatio-Temporal Video Grounding with Synthetic Curriculum. arXiv preprint arXiv:2608.30584v1 : https://arxiv.org/abs/2608.30584v1
- Jiani Guo, Junjie Wang, Jie Wu, Pengxiang Zhao, Dongdong Zhang, Shaohan Huang, Yujiu Yang, Furu Wei. Learning Where Outcomes Change:Credit-Addressable Reasoning for Multimodal Geometry. arXiv preprint arXiv:2608.30457v1 : https://arxiv.org/abs/2608.30457v1
- Aryan Vijay Bhosale, Vaibhavi Lokegaonkar, Vishnu Raj, Gouthaman KV, Sreyan Ghosh, Ramani Duraiswami, Lie Lu, Dinesh Manocha. VIBE: Video Instruction-aligned Background music gEneration. arXiv preprint arXiv:2608.30125v1 : https://arxiv.org/abs/2608.30125v1
- Tian Zhang, Zhuo Huang, Hongrui Ye, Yu Wu, Zengmao Wang, Kaixuan Zhou. Aligning Multi-Trajectory Supervision with Policy Optimization for VLA Driving. arXiv preprint arXiv:2608.30122v1 : https://arxiv.org/abs/2608.30122v1
- Kaidong Zhang, Yukang Ding, Xiaoyu Liu, Ying Chen. Beyond Global Realism: Virtual Try-On Evaluation and Optimization with Dimension-wise Garment Fidelity Assessment. arXiv preprint arXiv:2608.29804v1 : https://arxiv.org/abs/2608.29804v1
- Weifei Chen, Honghao Zhang, Zhiyuan You, Xinyi Le. InspectorGPT: A Comparative Reasoning Enhanced VLM for Comprehensive Industrial Anomaly Detection. arXiv preprint arXiv:2608.29783v1 : https://arxiv.org/abs/2608.29783v1
- Hao Feng, Zhi Zuo, MingJian Liang, Jingyu Hu, Xiaowei Hu, Liupengfei Wu, Dian Zhang, Guoxin Fang, Zhengzhe Liu. FuncRoom-Agent: Sequential Feed-Forward 3D Functional Indoor Scene Generation. arXiv preprint arXiv:2608.29519v1 : https://arxiv.org/abs/2608.29519v1
- Yu Cheng, Arushi Goel, Hakan Bilen. Think, Look, and Revise: Inconsistency-Aware Visual Self-Correction in MLLMs. arXiv preprint arXiv:2608.29374v1 : https://arxiv.org/abs/2608.29374v1
- Yuhan Li, Xianfeng Tan, Fangao Zeng, Wenxiang Shang, Pipei Huang, Hao Zhou, Zhiyu Jin, Wenjun Zhang, Bingbing Ni. RAGDiffusion++: From Macro-Retrieval to Micro-Fidelity Alignment for Garment Generation. arXiv preprint arXiv:2608.29280v1 : https://arxiv.org/abs/2608.29280v1
- Ziyue Wang, Shiqi Huang, Weiwen Xu, Bihan Wen, Xudong Jiang. Video-OPSD: Exploiting Privileged Visual Evidence for On-Policy Self-Distillation in Video Large Language Models. arXiv preprint arXiv:2608.27065v1 : https://arxiv.org/abs/2608.27065v1
- Zijian Kan, Wei Wang, Long Luo, Bing Zhao, Xuan Ren, Weixu Qiao, Wenbo Li, Hu Wei, Lin Qu. RubricRM: Generative Reward Modeling via Dynamic Rubrics for Image Generation and Editing. arXiv preprint arXiv:2608.26956v1 : https://arxiv.org/abs/2608.26956v1
- Ji Soo Lee, Jinyoung Park, Seohyun Lee, Jongha Kim, Joonmyung Choi, Jinsung Yoon, Hyunwoo J. Kim. Reason in the Words You Speak: Idiolectal Paraphrasing Off-Policy Traces for Reasoning Distillation in VideoLLMs. arXiv preprint arXiv:2608.26684v1 : https://arxiv.org/abs/2608.26684v1
- Yogesh Kulkarni, Pooyan Fazli. Video-FLAIR: Not Whether to Reason, But How. arXiv preprint arXiv:2608.26495v1 : https://arxiv.org/abs/2608.26495v1
- Junxiang Xu, Ruisi Wang, Fanyi Pu, Maijunxian Wang, Ran Ji, Tongxi Zhou, Chenyang Gu, Jing Zuo, Hongcan Xiao, Yimeng Geng, Wanqi Yin, Wei Chen, Oscar Qian, Zhengan Yan, Ziqi Huang, Haiwen Diao, Liang Pan, Bo Li, Xiangyu Fan, Dezhi Luo, Fengyuan Yu, Zehong Zhao, Qingying Gao, Tinghui Zhu, Yilan Zhang, Jingqi Tong, Pinyuan Feng, Zhengze Jiang, Letian Wang, Ziyu Guo, Renrui Zhang, Jieneng Chen, Sonia Joseph, Constantin Venhoff, Saman Motamed, Mengyue Yang, Chandra Sripada, Alan Yuille, Philip Torr, Lvmin Zhang, Vikash Kumar, Daniel Khashabi, Nikolaus Kriegeskorte, Raphaël Millière, Vincent C. Müller, Anyi Rao, Quan Wang, Ziwei Liu, Dahua Lin, Lei Yang, Hokin Deng, Zhongang Cai. VBVR-Pro: A Scalable and Verifiable Suite for Native Visual Reasoning. arXiv preprint arXiv:2608.26105v1 : https://arxiv.org/abs/2608.26105v1
- Shulin Tian, Minglun Li, Yuhao Dong, Hao Ding, Jiarui Yao, Haiwen Diao, Jingkang Yang, Hongyuan Zhu, Ziwei Liu. V-Rubrics: Visual Faithfulness via Rubric-Based Reinforcement Learning. arXiv preprint arXiv:2608.25580v1 : https://arxiv.org/abs/2608.25580v1
- Xintong Zhang, Xiaomeng Fan, Shilin Yan, Ekko He, Zicheng Liu, Zijian Zou, Guannan Zhang, Yuwei Wu, Zhi Gao, Hongwei Xue. AdaVDR: Adaptive Tool Use and Reflection for Video Deep Research. arXiv preprint arXiv:2608.25559v1 : https://arxiv.org/abs/2608.25559v1
- Longteng Jiang, DanDan Zheng, Qianqian Qiao, Heng Huang, Huaye Wang, Yihang Bo, Bao Peng, Jingdong Chen, Jun Zhou, Xin Jin. VGA-BenchV2: An Expanded Unified Benchmark and Multi-Model Framework for Evaluating Video Aesthetics and Generation Quality. arXiv preprint arXiv:2608.25452v1 : https://arxiv.org/abs/2608.25452v1
- Srivalli Katkuri, Maxwell Kawada, Juan Wachs. Beyond Pairwise Feedback: Listwise Vision-Language Supervision for Preference-Based Reward Learning. arXiv preprint arXiv:2608.25350v1 : https://arxiv.org/abs/2608.25350v1
- Jingyang Su, Pu Cao, Xiuze Jin, Longyue Zhang, Qing Song, Lu Yang. PointRL: Learning Point-Level Vision-Language Grounding from Verifiable Annotation Evidence. arXiv preprint arXiv:2608.25299v1 : https://arxiv.org/abs/2608.25299v1
- Wei Zhou, Xiongwei Zhu, Lingdong Kong, Bo Chen, Lei Zhang, Yongyuan Liang, Xiaoxia Hou, Ye Tian, Xian Sun, Yingshuo Wang, Linfeng Li, Shengqiong Wu, Leigang Qu, Feng Li, Wei Liu, Julian McAuley, Tat-Seng Chua. On-Policy Self-Distillation in Diffusion Models. arXiv preprint arXiv:2608.24646v1 : https://arxiv.org/abs/2608.24646v1
- Wenqi Liu, Shijie Ma, Yunxiao Wang, Meng Liu, Qile Su, Han Liu, Bohan Hou, Zeyu Wang, Xuanyu Zheng, Changyi Liu, Tianke Zhang, Haonan Fan, Kaiyu Jiang, Yingxin Li, Jiankang Chen, Xu Wang, Hongyi Fu, Jianxiong Wang, Bin Wen, Tingting Gao, Han Li, Jianhua Yin, Yinwei Wei, Xuemeng Song. Thinking Beyond Videos: Unifying Video Reasoning and Deep Research for Open-World Video Agents. arXiv preprint arXiv:2608.23329v2 : https://arxiv.org/abs/2608.23329v2
- Tong Wang, Huan Deng, Mucheng Yang, Yang He, Xiaohui Kuang, Gang Zhao. From Generation to Simulation: How Far Are World Models from Being True Simulators?. arXiv preprint arXiv:2608.23070v1 : https://arxiv.org/abs/2608.23070v1
- Simon Hakenes, Tobias Glasmachers. Macro-Action Topological Navigation under Noisy Localization using Reinforcement Learning. arXiv preprint arXiv:2608.23055v1 : https://arxiv.org/abs/2608.23055v1
- Qichao Ma, Jikang Cheng, Ling Liang, Zhaofei Yu, Tiejun Huang, Renye Yan. Can We Perform Online RL for Image Editing without Editing Rewards?. arXiv preprint arXiv:2608.22780v1 : https://arxiv.org/abs/2608.22780v1
- Yucheng Chen, Yang Yu, Jiazhou Zhou, Yufei Shi, Yongying Lan, Yichi Zhang, Liyi Li, Si Yong Yeo. UR$^{2}$-MLLM: Uncertainty-aware Revisit Reasoning in Multimodal Large Language Models for Radiology Report Generation. arXiv preprint arXiv:2608.22217v1 : https://arxiv.org/abs/2608.22217v1
- Wen Luo, Xiaohan Yi, Xiaotao Huang, Liqun Huang. VIG: Visual Information Gain as a Reward Signal for Multimodal Chain-of-Thought Compression. arXiv preprint arXiv:2608.21883v2 : https://arxiv.org/abs/2608.21883v2
- Md Asaduzzaman Jabin, Zihao Wu, Tianming Liu. BioMed-Agent-RL: A Meta Learning, All You Need for Biomedical Applications. arXiv preprint arXiv:2608.21864v1 : https://arxiv.org/abs/2608.21864v1
- Qiqian Fu. Hints, Critics, and Teachers: Prior Injection for Sparse-Reward RL in Vision-Language Math Reasoning. arXiv preprint arXiv:2608.21811v1 : https://arxiv.org/abs/2608.21811v1
- Long Shu, Shuochen Liu, Wei Chen, Junda Lin, Zhi Zheng, Huijun Hou, Tong Xu. SAFE-G: Structure-aware Faithful Evidence-guided Generation for Knowledge-based Visual Question Answering. arXiv preprint arXiv:2608.21796v1 : https://arxiv.org/abs/2608.21796v1
- Taihang Hu, Zhao Wang, Zuan Gao, Tao Liu, Hao Yan, Zhengze Xu, Yuhang Yu, Yongchao Du, Xingjian Wang, Jun Zheng, Qinye Zhou, Zhengrui Chen, Chao Lin, Yefeng Shen, Zhengtao Wu, Ge Wu, Xiaoli Xu, Denghui Yang, Huayu Zhang, Mingzhou Zhang, Mengting Chen. Swift-Image: Exploring the Performance Frontier of Compact Unified Image Generation Models. arXiv preprint arXiv:2608.20334v1 : https://arxiv.org/abs/2608.20334v1
- Shiao Xie, Siyu Chen, Jianwei Lv, Bo Yuan, Yujin Wang, Xiandong Li. G-CARL: Grounded Checklist-Aligned Reward Learning for Patient-Oriented Medical Report Interpretation. arXiv preprint arXiv:2608.20331v1 : https://arxiv.org/abs/2608.20331v1
- Yunseo Lee, Hyun Jun Kim, Heeseung Shin, Changwon Lim. Towards Clinically Faithful Medical Image Captioning via Enhanced Vision-Language Alignment. arXiv preprint arXiv:2608.19825v1 : https://arxiv.org/abs/2608.19825v1
- Johannes Künzel, Peter Eisert, Anna Hilsmann. RIPE++: Reinforced Keypoint Learning from Positive Pairs Only. arXiv preprint arXiv:2608.19693v1 : https://arxiv.org/abs/2608.19693v1
- Haoqiang Kang, Yinpeng Chen, Luyang Liu, Jesper Sparre Andersen, Abhijit Ogale, Baochen Sun, Lichan Hong, Ed H. Chi. Scaffolding Minds: Optimizing Latent Visual Target Representations for Multimodal Reasoning. arXiv preprint arXiv:2608.19669v1 : https://arxiv.org/abs/2608.19669v1
- Sofian Chaybouti, Yasser Dahou, Ngoc Dung Huynh, Reda Alami, Hilde Kuehne. Falcon Perception-HD: High Density Perception via Reinforcement Learning. arXiv preprint arXiv:2608.18881v1 : https://arxiv.org/abs/2608.18881v1
- Kangning Ye, Yunhao Li, Sijing Wu, Yucheng Zhu, Guangtao Zhai. PCQA-R1: Advancing Generalized 3D Point Cloud Quality Assessment with Reinforcement Learning. arXiv preprint arXiv:2608.18627v1 : https://arxiv.org/abs/2608.18627v1
- Yinming Huang, Shuyuan Tu, Xi Yan, Zihan Yang, Jianhua Han, Xu Hang, Yu-Gang Jiang, Zuxuan Wu. VA-Judger: Reward Modeling from Human Preference Feedback for Joint Video-Audio Generation. arXiv preprint arXiv:2608.18607v2 : https://arxiv.org/abs/2608.18607v2
- Amir Arsalan Nematollahi, Shayan Ahmadi, Mehdi Tale Masouleh, Ahmad Kalhor. Iterative Grasp Pose Refinement: A Deep Reinforcement Learning Approach for 2D Vision. arXiv preprint arXiv:2608.17628v1 : https://arxiv.org/abs/2608.17628v1
- Zeyun Deng, Yuzhe Lu, Yawei Wang, Linbo Liu, Qing Ping, Han Ding, Guande Wu, Panpan Xu, Jun Huan. Prism-GRPO: Faster VLA Policy Optimization via Splitting Same-outcome Groups. arXiv preprint arXiv:2608.17423v1 : https://arxiv.org/abs/2608.17423v1
- Yuanbang Liu, Chenxi Ruan, Yihan Hou, Qiong Luo, Wei Zeng. REChart: Reasoning-Efficient Chart Editing with Large Reasoning Models. arXiv preprint arXiv:2608.17414v1 : https://arxiv.org/abs/2608.17414v1
- Yunhao Yang, Yuexin Bian, Yunjie Tian, Di Fu, Tianjin Huang, Yuanyuan Shi, Ziang Xiao, Nuno Vasconcelos, Yijiang Li. Co-RL: Unsupervised Reasoning Emerges from Diverse Cohort in Multi-agent RL. arXiv preprint arXiv:2608.17253v2 : https://arxiv.org/abs/2608.17253v2
- Mohamad Mohamad, Francesco Ponzio, Maxime Gassier, Nicolas Pote, Xavier Descombes. Interactive Whole Slide Images for RL-based Tumour Segmentation. arXiv preprint arXiv:2608.16607v1 : https://arxiv.org/abs/2608.16607v1
- Tristan Gottwald, Maximilian Schier, Melanie Schaller, Bodo Rosenhahn. FLEET: Token-Based Feature Extraction for Event Camera-based Reinforcement Learning. arXiv preprint arXiv:2608.16523v1 : https://arxiv.org/abs/2608.16523v1
- Keming Wu, Baoyi Wang, Kaichen Zhang, Xiang An, Zuhao Yang, Sudong Wang, Haowei Zhu, Tingxuan Huang, Hongcheng Gao, Bin Wang. StreamOPD: A Post-Training Recipe with Spatio-Temporal Cue Gating for Streaming Video Understanding. arXiv preprint arXiv:2608.16320v1 : https://arxiv.org/abs/2608.16320v1
- Xiaoan Liu, Lichen Ma, Zipeng Guo, Yu He, Xiaoyan Su, Shaojie Guo, Jingling Fu, Xiaolong Fu, Hao Yang, Tongxuan Liu, Yu Guo, Fei Wang, Xinyi Liu, Yongjun Zhang, Junshi Huang. PosterText: Towards Unified Visual Text Generation and Editing for E-commerce Poster. arXiv preprint arXiv:2608.16289v3 : https://arxiv.org/abs/2608.16289v3
- Xiaoan Liu, Lichen Ma, Zipeng Guo, Yu He, Xiaoyan Su, Shaojie Guo, Hao Yang, Jingling Fu, Xiaolong Fu, Zhen Chen, Yu Guo, Fei Wang, Xinyi Liu, Yongjun Zhang, Ke Zhang, Junshi Huang. TransAnyText: Translating Arbitrary Text in E-commerce Images via Structured Visual Generation. arXiv preprint arXiv:2608.16284v1 : https://arxiv.org/abs/2608.16284v1
- Bowen Deng, Jiahui Zhan, Yikun Ji, Haozhen Yan, Jianfu Zhang. Defake-o3: From Speculative Rationales to Verifiable Evidence for Explainable AIGI Detection. arXiv preprint arXiv:2608.16259v1 : https://arxiv.org/abs/2608.16259v1
- Alam Noor, Luis Almeida, Kai Li, Jiyan Wu, Miguel Gutiérrez Gaitán, Eduardo Tovar. Graph Neural Assisted Actor-Critic for Latency-Efficient Edge Vision System. arXiv preprint arXiv:2608.16142v1 : https://arxiv.org/abs/2608.16142v1
- Zesheng Yang, Lingling Zhang, Xinyu Zhang, Cheng Zhang, Pengyu Li, Heng Wang, Lin Wu. GLaQ: Grounding Latent Queries in Visual Evidence for Multimodal Reasoning. arXiv preprint arXiv:2608.15517v2 : https://arxiv.org/abs/2608.15517v2
- Penghao Yin, Haomin Wang, Qihong Tang, Xiaoye Qu, Hongjie Zhang, Xiao-Ping Zhang. MetaReason: Precise Interleaved Multimodal Reasoning via Editing Meta Information for Solving Geometry Problems. arXiv preprint arXiv:2608.15006v1 : https://arxiv.org/abs/2608.15006v1
- Yi-Chung Chen, Philip Jacobson, Tom Lampo, Yiren Lu, Jin Yao, David I. Inouye, Jing Gao, Danhua Guo, Burhan Yaman. TraVEL: Trajectory-Guided Video Embedding Learning for Driving-Video Retrieval. arXiv preprint arXiv:2608.13495v1 : https://arxiv.org/abs/2608.13495v1
- Hao Dou. FIRE-VLA: Failure-Informed Self-Evolution for Vision-Language-Action Models in Autonomous Driving. arXiv preprint arXiv:2608.13395v1 : https://arxiv.org/abs/2608.13395v1
- Yao Zhou, Hang Gao, Fengge Wu, Changwen Zheng, Wenwen Qiang. Temporal GRPO: Beyond Trajectory-Level Credit in Vision-Language-Action Reinforcement Learning. arXiv preprint arXiv:2608.13026v1 : https://arxiv.org/abs/2608.13026v1
- Ankita Joshi. A Deep RL based Framework for Targeted White Matter Tractography. arXiv preprint arXiv:2608.12960v1 : https://arxiv.org/abs/2608.12960v1
- Yicheng Bao, Xiahui Guo, Xuhong Wang, Xin Tan. SPARED: Reasoning-Based AI-Generated Image Detection via Adversarially Edited Data. arXiv preprint arXiv:2608.12876v1 : https://arxiv.org/abs/2608.12876v1
- Quan-Dung Pham, Anh Dao, The-Anh Nguyen, Minh Nguyen-Dinh, Phuong Nam Dang, Tri Pham, Hung Tran, Bach Dao, Tuyen P. Le, Truong Nguyen, Quan Nguyen. HumanoidVLN: A Physics-Grounded Simulator and Benchmark for Vision-Language Navigation Across Diverse Humanoid Embodiments. arXiv preprint arXiv:2608.12860v1 : https://arxiv.org/abs/2608.12860v1
- Xinming Wang, Weinong Wang, Hongming Yang, Yansong Lin, Zheng Ruan, Shangpin Peng, Qiming Peng, Nan Qiao, Fengyuan Lu, Guoqing Ma, Marito Li, Songyang Zhang, Saiyong Yang, Han Hu, Yonglong Tian, Xu-Yao Zhang. Beyond Correctness: Benchmarking and Aligning Response Behaviors in Hybrid-Thinking MLLMs. arXiv preprint arXiv:2608.12781v1 : https://arxiv.org/abs/2608.12781v1
- Zile Zhou, Huining Yuan, Weichen Zhang, Xinlei Chen, Xiao-ping Zhang. SCOUT: Unlocking Enhanced Spatial Reasoning via Structured Chain-of-Thought and Multi-Objective Process Reward. arXiv preprint arXiv:2608.12220v1 : https://arxiv.org/abs/2608.12220v1
- Wenshuo Peng, Kaipeng Zhang. HarmoniDPO: Video-guided Audio Generation via Preference-Optimized Diffusion. arXiv preprint arXiv:2608.11913v1 : https://arxiv.org/abs/2608.11913v1
- Xinhao Zhong, Yuxia Qiao, Junhao Li, Hao Fang, Yi Sun, Bin Chen. LEMUR: Latent Entropy-aware Multimodal Unlearning via Visual-anchored Reasoning Redirection. arXiv preprint arXiv:2608.11691v1 : https://arxiv.org/abs/2608.11691v1
- Bowei Liu, Zheng Lu, Yuhan Bian, Xinchen Zhang, Xingming Shui, Yuesheng Huang, Xuhuan Li, Zihao Liu, Yifan Yang, Jun Zhou, Xiu Li. VidForensics-M1: Meta-Detection Reinforcement Learning with Verifiable Temporal Grounding for AI-Generated Video Forensics. arXiv preprint arXiv:2608.11201v1 : https://arxiv.org/abs/2608.11201v1
- Shiyu Xuan, Zechao Li. Test-Time Self-Evolving GUI Visual Grounding via Reflection-Guided On-Policy Self-Distillation. arXiv preprint arXiv:2608.11191v1 : https://arxiv.org/abs/2608.11191v1
- Xinrui Lin, Sha Zhang, Shumin Wang, Zenghuan Zhu, Jiajun Deng, Yanyong Zhang. ThinkAfford: Affordance-Centric Reasoning for Fine-Grained 3D Grounding in Cluttered Scenes. arXiv preprint arXiv:2608.10981v1 : https://arxiv.org/abs/2608.10981v1
- Yuetian Du, Yucheng Wang, Zhenyuan Chen, Luyuan Chen, Rongyu Zhang, Jinjian Zhang, Wei Zhou, Zhijie Xu, Ming Kong, Zhan Zhou, Jie Liu, Qiang Zhu. CARE: Confidence-Aware Reasoning for Reliable Medical VQA. arXiv preprint arXiv:2608.10964v1 : https://arxiv.org/abs/2608.10964v1
- Zhaoyang Wei, Bowen Jiang, Xumeng Han, Jiashu Li, Xuehui Yu, Yuling Liu, Guorong Li, Zhenjun Han, Jianbin Jiao. Evidence-Grounded Trustworthy Multimodal Reasoning and Evaluation Benchmark in Complex Urban Scenes. arXiv preprint arXiv:2608.10954v1 : https://arxiv.org/abs/2608.10954v1
- Shengzhi Wang, Jun Yang, Kai Wu, Xiaozhong Ji, Yiwen Ye, Ziyang Chen, Mingliang Xiong, Wen Fang, Mingqing Liu, Mengyuan Xu, Miaoxuan Shan, Caiyan Liu, Bin He, Qingwen Liu. MIRA: Medical Image Reflection for Agentic Diagnosis. arXiv preprint arXiv:2608.10827v1 : https://arxiv.org/abs/2608.10827v1
- Fufangchen Zhao, Jinhu Fu, Jiachen Lei, Jiahong Wu, Xiangxiang Chu, Danfeng Yan. FADE: From Passive Verification to Active Discovery in Counterfactual Video Understanding. arXiv preprint arXiv:2608.10764v1 : https://arxiv.org/abs/2608.10764v1
- Caoyuan Ma, Wenpu Liu, Weichu Xie, Tian Gu, Shilei Zhao, Lingxi Min, Shuai Dong, Yuqi Xu, Ji Zhao, Ziyue Wang, Wenzheng Chang, Taiqiang Wu, Yongfu Zhu, Wenqi Shao, Yinqiang Zheng. SafeCap: Improving LVLM Safety with Image Captioning Reinforcement Learning. arXiv preprint arXiv:2608.10513v1 : https://arxiv.org/abs/2608.10513v1
- Dongchi Huang, Hongyin Zhang, Bohan Hou, Siteng Huang, Zhian Su, Hang Guo, Tong Lu, Zhaofeng Xu, Jiahao Tang, Jianfei Yang, Donglin Wang, Peixi Peng, Mingxiu Chen, Deli Zhao, Xin Li. RynnValue: Scaling Robotic Value Foundation Models with Temporal Distance. arXiv preprint arXiv:2608.09853v1 : https://arxiv.org/abs/2608.09853v1
- Renshan Zhang, Haoyang Meng, Yixiao He, Rui Shao, April Hua Liu, Liqiang Nie. LookAgain: Closed-Loop GUI Grounding with Visually Grounded Reflection. arXiv preprint arXiv:2608.09723v1 : https://arxiv.org/abs/2608.09723v1
- Guolei Huang, Tengfei She, Yuxuan Lu, Yao Huang, Yuqi Ye, Yongjun Shen. FactorDrive: Adaptive Multi-Step Reasoning Driven by Planning-Critical Factors for End-to-End Autonomous Driving. arXiv preprint arXiv:2608.09591v1 : https://arxiv.org/abs/2608.09591v1
- Zeyuan Ma, Jiaxin Chen, Di Huang. From Semantic Grounding to Decision Optimization: A Unified Framework for Long-Horizon UAV Vision-Language Navigation. arXiv preprint arXiv:2608.09564v1 : https://arxiv.org/abs/2608.09564v1
- Boxiong Wang, Hui Kang, Geng Sun, Jiahui Li, Chao Yu, Daxin Tian. RecoverFly: A Failure-Aware Reinforcement Learning Post-Training Framework for Aerial Vision-Language Navigation. arXiv preprint arXiv:2608.09467v1 : https://arxiv.org/abs/2608.09467v1
- Zhi Zeng, Cheng Zhang, Zesheng Yang, Rendong Pi, Jiaying Wu, Di Zhang, Zihan Ma, Guodong Li, Zhou Yang, Yu Xiang, Yifei Zheng, Minnan Luo. Listen, See and Track: Spatio-Temporal Audio-Visual Sound Event Reasoning for Omni-Modal Language Models. arXiv preprint arXiv:2608.09435v1 : https://arxiv.org/abs/2608.09435v1
- Mingfeng Lin, Chengfei Cai, Lin Xu, Yuxiang Wei, Liang Han. DreOPD: Degraded-Reference Extrapolative On-Policy Distillation for Flow-matching Models. arXiv preprint arXiv:2608.09233v2 : https://arxiv.org/abs/2608.09233v2
- Yuhan Li, Fangao Zeng, Sicong Kang, Mengfei Xu, Hao Zhou, Wei Li, Pipei Huang, Bingbing Ni. RL-Native Distillation: Exploiting Scored Trajectories for Few-Step Image Generation. arXiv preprint arXiv:2608.09226v1 : https://arxiv.org/abs/2608.09226v1
- Jiaye Fu, Weiqi Li, Qiankun Gao, Yanchen Zhao, Xiandong Meng, Jian Zhang, Siwei Ma, Jiaqi Zhang. CodecArena: Codec Quality Assessment via Visual Reinforcement Learning. arXiv preprint arXiv:2608.09139v1 : https://arxiv.org/abs/2608.09139v1
- Jingyun Chen, Fengchun Liu, Linghan Cai, Songhan Jiang, Shenjin Huang, Hongpeng Wang, Lequan Yu, Yongbing Zhang. Agentic Visual Reasoning in Whole-Slide Pathology Images via Active Perception. arXiv preprint arXiv:2608.08648v1 : https://arxiv.org/abs/2608.08648v1
- Prishita Ray. Curriculum Generation under Structured Parametric Environments for Robust Navigation Policies. arXiv preprint arXiv:2608.08545v1 : https://arxiv.org/abs/2608.08545v1
- Hwanhee Kim, Jaehyun Jang, Seungmin Cha, Hyeonseo Yun, Donghoon Lee, Chang D. Yoo. Action- and Language-Conditioned Video Assessment for Embodied Control. arXiv preprint arXiv:2608.08273v1 : https://arxiv.org/abs/2608.08273v1
- Rui Wang, Yeteng Wu, Xianling Zhang, Mengshi Qi. VTO: Visual Tool Orchestration for Video Anomaly Detection. arXiv preprint arXiv:2608.08219v1 : https://arxiv.org/abs/2608.08219v1
- Jie Huang, Xiaohe Li, Jiahao Li, Fangli Mou, Chen Qian, Yuqiang Fang, Junhao Fan, Kaixin Zhang, Zide Fan. PhysX-CoT: Structured Physical Reasoning from a Single Image to Simulation-Ready 3D Assets. arXiv preprint arXiv:2608.08053v1 : https://arxiv.org/abs/2608.08053v1
- Haojie Huang, Xinlei Yu, Chengming Xu, Zhangquan Chen, Cheng Yang, Qingdong He, Yu Yang, Jiangning Zhang, Xiaobin Hu. Evidence-RL: Towards Evidence-intensive Visual Reasoning. arXiv preprint arXiv:2608.08021v1 : https://arxiv.org/abs/2608.08021v1
- Liangliang Zhao, Junying Wang, Danni Yang, Yifan Chang, Bin Fu, Yu Qiao, Bowen Zhou, Yihao Liu. Distilling Physical Priors into Streaming World Models. arXiv preprint arXiv:2608.07981v1 : https://arxiv.org/abs/2608.07981v1
- Donghu Kim, Youngdo Lee, Hojoon Lee, Johan Obando-Ceron, Byungkun Lee, Aaron Courville, Pablo Samuel Castro, Jaegul Choo, Clare Lyle. V-Simba: Unleashing the Architectural Potential of RL in Visual Continuous Control. arXiv preprint arXiv:2608.07870v1 : https://arxiv.org/abs/2608.07870v1
- Saugat Adhikari, Ashok Prasad Neupane, Pramish Paudel, Ajad Chhatkuli, Danda Pani Paudel. iARCS: Iterative Agentic RL for Controllable 3D Scene Generation. arXiv preprint arXiv:2608.06161v1 : https://arxiv.org/abs/2608.06161v1
- Rui Li, Yuanzhi Liang, Ke Hao, Ziqiao Weng, Haibin Huang, Chi Zhang, XueLong Li. Sample-Adaptive Latent Rewards for Uncertainty-Guided Diffusion Post-Training. arXiv preprint arXiv:2608.06125v1 : https://arxiv.org/abs/2608.06125v1
- He Kong, Zengjue Chen, Qi Wang, Qianli Xing, Runliang Niu, Peidong Liu, Jiawei Li, Shiqi Wang, Yi Chang. Beyond Flat Policies: Hierarchical Post-Training for Embodied Agents in Robotic Manipulation. arXiv preprint arXiv:2608.05999v1 : https://arxiv.org/abs/2608.05999v1
- Katrin Schmid, Iuri Frosio. Training a Conditioned Video Game Agent on a VLM Annotated Dataset. arXiv preprint arXiv:2608.05954v1 : https://arxiv.org/abs/2608.05954v1
- Yingqing Guo, Hui Yuan, Zijian He, Mengdi Wang, Zheng Ding. LC-GRPO: Bridging Train-Inference Gap for Flow-Based GRPO with Langevin Correction. arXiv preprint arXiv:2608.05600v1 : https://arxiv.org/abs/2608.05600v1
- Bohai Gu, Yueyang Yuan, Taiyi Wu, Dazhao Du, Jian Liu, Xiaoyi Pang, Jie Zhang, Xiaocheng Lu, Haobin Zhong, Xiaotong Zhao, Alan Zhao, Song Guo. WorldCycle: Self-Verifiable Reinforcement Learning for Long-Horizon Video World Models. arXiv preprint arXiv:2608.04964v1 : https://arxiv.org/abs/2608.04964v1
- Xuzheng Yang, Jun Ling, Tao Huang, Caiyan Qin, Peng Wang. Teaching MLLMs to Say No: Generalized Referring Expression Comprehension via Refusal Calibrated GRPO. arXiv preprint arXiv:2608.04698v1 : https://arxiv.org/abs/2608.04698v1
- De Jiang, Zhengyang Zhang, Kehong Yuan, Shaohua Ma. CARGO-VL: Counterfactual Arbitration with Risk-Constrained Group Optimization for Vision-Language Models. arXiv preprint arXiv:2608.04509v1 : https://arxiv.org/abs/2608.04509v1
- Shuo Liu, Huixiang Cai, Weiru Zhang, Xiaoyi Zeng. GeoReward: Mitigating Contextual Variable Overestimation in Vision-Language Models for Cross-Market Preference Prediction. arXiv preprint arXiv:2608.04504v1 : https://arxiv.org/abs/2608.04504v1
- Jiahao Zhao, Xiaomin Yu, Zhongxiang Sun, Fengwei Teng, Chengwei Qin, Xiaobin Hu, Jun Xu, Shuicheng Yan. ToolArtist: Tool-Using Unified Multimodal Models for Agentic Image Generation. arXiv preprint arXiv:2608.04436v1 : https://arxiv.org/abs/2608.04436v1
- Yuanshen Guan, Zipeng Feng, Chengru Song, Zhiwei Xiong, Peiqin Sun. Latent Reward Registers for Diffusion Preference Alignment. arXiv preprint arXiv:2608.03929v2 : https://arxiv.org/abs/2608.03929v2
- Mercy Prasanna Ranjit, Anirban Porya, Sathvik Joel, Niharika Vadlamudi, Nikhilesh Chowdary Eathamukkala, Prasanth V, Abhyuday Kumara Swamy, Pranay Narhari Umredkar, Pradeep Narayan, Vivek Rajagopal, Tanuja Ganu. CARE-X: Towards Clinically Useful Radiology VLMs with Auxiliary Supervision, Reward-Aligned Learning, and Tool-Augmented Measurement. arXiv preprint arXiv:2608.03890v1 : https://arxiv.org/abs/2608.03890v1
- Pyrros Koussios, Chenhao Li, Xin Chen, Andreas Krause. Enhancing VLM Reward Models Through Structure-Aware Fine-Tuning. arXiv preprint arXiv:2608.03875v1 : https://arxiv.org/abs/2608.03875v1
- Shuoqin Zhang, Tongtong Cheng, Xiru Gao, Jinzhuo Peng, Bin Zheng, Jiahao Tu, Ke Wang, Jia Pan, Zhe Hu, Kai Liu. EvoHIL: Self-Evolving Reward and Flow-Matched Policy Optimization for Robust Human-in-the-Loop Reinforcement Learning. arXiv preprint arXiv:2608.03872v1 : https://arxiv.org/abs/2608.03872v1
- Andrea Protopapa, Davide Buoso, Francesca Pistilli, Georgia Chalvatzaki, Giuseppe Averta. GORDON: Graph-based Object-centric Rewards for Decomposition of Long-Horizon Manipulation. arXiv preprint arXiv:2608.03753v1 : https://arxiv.org/abs/2608.03753v1
- Weichen Xu, Zhenhua Liu, Lin Luo, Yaobo Liang, Chengtang Yao, Qingyu Mei, Jian Cao, Xixin Cao, Xing Zhang, Jiaolong Yang, Baining Guo. Continue or Replan? Bernoulli-Continuation Policy Learning for Adaptive Horizon Execution. arXiv preprint arXiv:2608.03483v1 : https://arxiv.org/abs/2608.03483v1
- Inkyu Sa, Konstantin Stulov, Rajat Bhageria. ValueFormer: A Causal Transformer Value Function with Stage-Aware Labels for Semi-Autonomous Vision-Language-Action Policies. arXiv preprint arXiv:2608.02958v1 : https://arxiv.org/abs/2608.02958v1
- Yizheng Wu, Jiashen Hua, Bing Deng, Jieping Ye. VC-Tooler: Learning Compositional and Adaptive Visual Tool Use. arXiv preprint arXiv:2608.02217v1 : https://arxiv.org/abs/2608.02217v1
- Wei Jia, Zhicong Lu, Yu Chen, Xiang Wang, Shuai Li, Wenqian Lv, Jiayue Cao, Huaxing liu. CAVE: Competence-Aware Visual Boundary Evidence Alignment for Video Temporal Grounding. arXiv preprint arXiv:2608.02078v1 : https://arxiv.org/abs/2608.02078v1
- Jingqi Tian, Haoji Zhang, Lin Chen, Hongbo Jin, Haonan Xu, Tianrui Zhu, Xingming Shui, Shilin Ma, Wenjing Yang, Yansong Tang. AdaThinkV: Adaptive Thinking for Token-Efficient Video Reasoning. arXiv preprint arXiv:2608.01980v1 : https://arxiv.org/abs/2608.01980v1
- Jianmin Chen, Jiaqi Tang, Wei Wei, Xiaogang Xu, Jiafei Wu, Zhe Liu, Qianzhou Wang, Yingying Yan, Botong Geng, Yuyang Xia, Lei Zhang, Qifeng Chen. Remember-R1: Mitigating Long-Context Visual Forgetting through Reinforcement Learning. arXiv preprint arXiv:2608.01314v1 : https://arxiv.org/abs/2608.01314v1
- Xinheng Han, Jianfei Wang, Yu Chen, Xiang Wang, Shuai Li, Weixing Li, Feng Pan. Credit the Right Box: Marginal Contribution Assignment for Structured Visual Perception. arXiv preprint arXiv:2608.01055v1 : https://arxiv.org/abs/2608.01055v1
- Damir Nurtdinov, Alexei Kornaev, Alexander Maloletov. RL Bootstrapping of OpenVLA-OFT for a Novel Robot Embodiment. arXiv preprint arXiv:2608.01013v1 : https://arxiv.org/abs/2608.01013v1
- Jiaxuan Kang, Siyu Chen, Mingda Li, Mingjie Liu, Tianyue Wang, Zhaoyang Wei, Yongheng Zhang, Yanchao Hao, Zheng Wei. LUT: Latent Utility Training for Visual Reasoning. arXiv preprint arXiv:2608.00743v1 : https://arxiv.org/abs/2608.00743v1
- Jingtong Chen, Jiahui Wang, Xue Zhao, ShaoGuo Liu, Minghao Li. Element-Aware Group Learning for E-Commerce Image Generation. arXiv preprint arXiv:2608.00584v1 : https://arxiv.org/abs/2608.00584v1
- Yunhao Wang, Binghong Wu, Zhenyu Huang, Jiacheng Shi, Shuo Huang, Tinghao Yu, Feng Zhang. DocPO: Advancing Document Policy Optimization via Tailored Step-Aware Rewards. arXiv preprint arXiv:2608.00536v2 : https://arxiv.org/abs/2608.00536v2
- Yufei Zhang, Chenlu Zhan, Donghui Sun, Xiaoxin Chen, Hongwei Wang. SpatialAfford: Teaching Compact VLMs Where to Look and Where to Ground for Affordance. arXiv preprint arXiv:2608.00502v1 : https://arxiv.org/abs/2608.00502v1
- Song Tang, Shuming Hu, Xincheng Shuai, Henghui Ding, Yu-Gang Jiang. Seek to Segment: Active Perception for Panoramic Referring Segmentation. arXiv preprint arXiv:2607.02497v1 : https://arxiv.org/abs/2607.02497v1
- Liyan Tang, Fangcong Yin, Greg Durrett. Visually Grounded Self-Reflection for Vision-Language Models via Reinforcement Learning. arXiv preprint arXiv:2607.02490v1 : https://arxiv.org/abs/2607.02490v1
- Ruihang Li, Mengde Xu, Shuyang Gu, Leigang Qu, Fuli Feng, Han Hu, Wenjie Wang. Optimizing Visual Generative Models via Distribution-wise Rewards. arXiv preprint arXiv:2607.02291v1 : https://arxiv.org/abs/2607.02291v1
- Yuriy Maksyuta, George Bredis, Ruslan Rakhimov, Daniil Gavrilov. Rank-Then-Act: Reward-Free Control from Frame-Order Progress. arXiv preprint arXiv:2607.01897v1 : https://arxiv.org/abs/2607.01897v1
- Hexian Ni, Tao Lu, Yinghao Cai. CoRe: Combined Rewards with Vision-Language Model Feedback for Preference-Aligned Reinforcement Learning. arXiv preprint arXiv:2607.01721v1 : https://arxiv.org/abs/2607.01721v1
- Jinwen Wang, Youfang Lin, Xiaobo Hu, Siyu Yang, Sheng Han, Shuo Wang, Kai Lv. From Pixels to Temporal Correlations: Learning Informative Representations for Reinforcement Learning Pre-training. arXiv preprint arXiv:2607.00811v1 : https://arxiv.org/abs/2607.00811v1
- Jinwen Wang, Youfang Lin, Xiaobo Hu, Shuo Wang, Kai Lv. Local Motion Matters: A Deconstruct-Recompose Paradigm for Reinforcement Learning Pre-training from Videos. arXiv preprint arXiv:2607.00808v1 : https://arxiv.org/abs/2607.00808v1
- Jinwen Wang, Youfang Lin, Xiaobo Hu, Qian Xu, Shuo Wang, Zhuo Chen, Kai Lv. Task-Relevant Representation Decoupling for Visual Reinforcement Learning Generalization. arXiv preprint arXiv:2607.00796v1 : https://arxiv.org/abs/2607.00796v1
- Kuan-Chen Chen, Winston Chen, Wei-Fang Sun, Min-Chun Hu. VLM-AR3L: Vision-Language Models for Absolute and Relative Rewards in Reinforcement Learning. arXiv preprint arXiv:2607.00483v2 : https://arxiv.org/abs/2607.00483v2
- Lang Cao, Renhong Chen, Luyi Li, Peng Wang, Mofan Peng, Yitong Li. Z-1: Efficient Reinforcement Learning for Vision-Language-Action Models. arXiv preprint arXiv:2606.31846v1 : https://arxiv.org/abs/2606.31846v1
- Junha Jung, Minbyul Jeong, Suhyeon Lim, Sungwook Jung, Jaehoon Yun, Taeyun Roh, Mujeen Sung, Jaewoo Kang. Breaking Failure Cascades: Step-Aware Reinforcement Learning for Medical Multimodal Reasoning. arXiv preprint arXiv:2606.31825v1 : https://arxiv.org/abs/2606.31825v1
- Yaozhi Zheng, Yilei Jiang, Manyuan Zhang, Yuxuan Wan, Kaituo Feng, Tianshuo Peng, Bo Zhang, Xiangyu Yue. UniCoder: Unified Visual-to-Code Generation via Symbolic Rewards and Reference-Guided Code Optimization. arXiv preprint arXiv:2606.31732v1 : https://arxiv.org/abs/2606.31732v1
- Kaitao Chen, Weiqian Zhao, Jiamin Wu, Qihao Zheng, Shangquan Sun, Chunfeng Song, Xiaosong Wang, Mu Zhou, Mianxin Liu. Token-Sparse Medical Multimodal Reasoning via Dual-Stream Reinforcement Learning. arXiv preprint arXiv:2606.31599v1 : https://arxiv.org/abs/2606.31599v1
- Mohammad Mahdi Abootorabi, Sina Namazi, Armin Saadat, Lyuyang Wang, Obed Dzikunu, Paul F. R. Wilson, Zhuoxin Guo, Brian Wodlinger, Parvin Mousavi, Purang Abolmaesumi. Learning Where to Look: A Reinforcement Learning Framework for Robust Micro-Ultrasound Prostate Cancer Detection. arXiv preprint arXiv:2606.30951v1 : https://arxiv.org/abs/2606.30951v1
- Hyunwoo Park, Sang-Hyun Lee. Domain Adaptation with Adaptive Imagination for Visual Reinforcement Learning under Limited Target Data. arXiv preprint arXiv:2606.30192v1 : https://arxiv.org/abs/2606.30192v1
- Eric Peh, Debaditya Roy, Basura Fernando. H-GRPO: Permutation-Invariant Reinforcement Learning for Grounded Visual Reasoning. arXiv preprint arXiv:2606.29915v1 : https://arxiv.org/abs/2606.29915v1
- Siyao Chen, Jiakang Yuan, Jiaxin Wang, Tao Chen. Trust Your Instincts: Confidence-Driven Test-Time RL for Vision-Language-Action Models. arXiv preprint arXiv:2606.29892v1 : https://arxiv.org/abs/2606.29892v1
- Tianshu Zhang, Yan Wang, Ji Qi, Lijie Wen. Efficient Spatio-Temporal Grounding with Multimodal Large Models via Second-Level Tracking and RL Verification. arXiv preprint arXiv:2606.29023v1 : https://arxiv.org/abs/2606.29023v1
- Fatma Youssef Mohammed, Grzegorz Malczyk, and Kostas Alexis. Fast Human Attention Prediction for Fixation-guided Active Perception in Autonomous Navigation. arXiv preprint arXiv:2606.20491v1 : https://arxiv.org/abs/2606.20491v1
- Chengwen Liu, Hao Peng, Jisheng Dang, Hong Peng, Bin Hu, and Tat-Seng Chua. CARE: Competence-Aware Reward Shaping for Adaptive Reasoning Length in Video-MLLMs. arXiv preprint arXiv:2606.19927v1 : https://arxiv.org/abs/2606.19927v1
- Seyed Alireza Azimi, Homayoon Farrahi, Abhishek Naik, Colin Bellinger, and A. Rupam Mahmood. Benchmarking Action Spaces in Reinforcement Learning for Vision-based Robotic Manipulation. arXiv preprint arXiv:2606.18594v1 : https://arxiv.org/abs/2606.18594v1
- Mukund Khanna, Raj Singh Yadav, and Kunal Singh. ProductConsistency: Improving Product Identity Preservation in Instruction-Based Image Editing via SFT and RL. arXiv preprint arXiv:2606.19103v1 : https://arxiv.org/abs/2606.19103v1
- Yilian Liu, Sicong Leng, Guoshun Nan, Junyi Zhu, Jiayu Huang, Minghao Sun, Xuancheng Zhu, Yisong Chen, Zexian Wei, and Xiaofeng Tao. See First, Answer Later: Visual Evidence Pre-Alignment via Sufficiency-Driven RL. arXiv preprint arXiv:2606.17678v1 : https://arxiv.org/abs/2606.17678v1
- Saraswathy Amjith. Self-Questioning Vision-Language Models: Reinforcement Learning for Compositional Visual Reasoning. arXiv preprint arXiv:2606.15651v1 : https://arxiv.org/abs/2606.15651v1
- Mohamed Bayan Kmainasi, Mucahid Kutlu, Ali Ezzat Shahroor, Abul Hasnat, and Firoj Alam. Adapting Reinforcement Learning with Chain-of-Thought Supervision for Explainable Detection of Hateful and Propagandistic Memes. arXiv preprint arXiv:2606.15307v1 : https://arxiv.org/abs/2606.15307v1

# Contribute
A paper is missing ? don't hesitate to open an issue or pull-request to keep the repository updated 😊
