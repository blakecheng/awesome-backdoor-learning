# Awesome Backdoor Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


A curated list of awesome **Backdoor Learning** resources. Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers).

#### Why Backdoor Learning?
Backdoor learning is an emerging research area, which discusses the security issues of the training process towards machine learning algorithms. It is critical for safely adopting third-party algorithms in reality.  Although backdoor learning shares certain similarity with adversarial learning (which concentrates on the security issues of the inference process), they do have essential differences and can be easily distinguished.

Note: 'Backdoor' is also commonly called the 'Neural Trojan' or 'Trojan'.


## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help to contribute this list by contacting [me](http://liyiming.tech) or add [pull request](https://github.com/THUYimingLi/awesome-backdoor-learning/pulls)

Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```

## Table of Contents
- [Survey](#survey)
- [Image Classification](#image-classification) 
  - [Poisoning-based Attack](#poisoning-based-attack)
  - [Non-poisoning-based Attack](#non-poisoning-based-attack)
  - [Backdoor Defense](#backdoor-defense)
- [Attack and Defense Towards Other Tasks](#attack-and-defense-towards-other-tasks)  
- [Properties Discussion and Evaluation](#properties-discussion-and-evaluation)
- [Application in other Tasks](#application-in-other-tasks)


## Survey
- A Survey on Neural Trojans. 
  [[pdf]](https://eprint.iacr.org/2020/201.pdf)
  - Yuntao Liu, Ankit Mondal, Abhishek Chakraborty, Michael Zuzak, Nina Jacobsen, Daniel Xing, and Ankur Srivastava. 2020.

## Image Classification
### Poisoning-based Attack
#### 2020
- Hidden Trigger Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1910.00033.pdf)
  [[code]](https://github.com/UMBCvision/Hidden-Trigger-Backdoor-Attacks)
  - Aniruddha Saha, Akshayvarun Subramanya, and Hamed Pirsiavash. *AAAI 2020*.

- Bypassing Backdoor Detection Algorithms in Deep Learning.
  [[pdf]](https://arxiv.org/pdf/1905.13409.pdf)
  - Te Juin Lester Tan, and Reza Shokri. *EuroS&P 2020*.

- Backdoor Embedding in Convolutional Neural Network Models via Invisible Perturbation.
  [[pdf]](https://arxiv.org/pdf/1808.10307.pdf)
  - Cong Liao, Haoti Zhong, Anna Squicciarini, Sencun Zhu, and David Miller. *ACM CODASPY 2020*.

- Live Trojan Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2004.11370.pdf)
  [[code]](https://github.com/robbycostales/live-trojans)
  - Robby Costales, Chengzhi Mao, Raphael Norwitz, Bryan Kim, and Junfeng Yang. *CVPR Workshop 2020*.

- Backdooring and Poisoning Neural Networks with Image-Scaling Attacks.
  [[pdf]](https://arxiv.org/pdf/2003.08633.pdf)
  - Erwin Quiring, and Konrad Rieck. *IEEE S&P Workshop 2020*.

- Blind Backdoors in Deep Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2005.03823.pdf)
  - Eugene Bagdasaryan, and Vitaly Shmatikov. arXiv 2020.

- FaceHack: Triggering backdoored facial recognition systems using facial characteristics.
  [[pdf]](https://arxiv.org/pdf/2006.11623.pdf)
  - Esha Sarkar, Hadjer Benkraouda, and Michail Maniatakos. arXiv 2020.

- Dynamic Backdoor Attacks Against Machine Learning Models. 
  [[pdf]](https://arxiv.org/pdf/2003.03675.pdf)
  - Ahmed Salem, Rui Wen, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv 2020.  

#### 2019
- A New Backdoor Attack in CNNS by Training Set Corruption Without Label Poisoning.
  [[pdf]](https://arxiv.org/pdf/1902.11237.pdf)
  - M.Barni, K.Kallas, and B.Tondi. *ICIP 2019*.
  
- Label-Consistent Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1912.02771.pdf)
  - Alexander Turner, Dimitris Tsipras, and Aleksander Madry. arXiv 2019.

- Invisible Backdoor Attacks Against Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1909.02742.pdf)
  - Shaofeng Li, Benjamin Zi Hao Zhao, Jiahao Yu, Minhui Xue, Dali Kaafar, and Haojin Zhu. arXiv 2019.
  
#### 2017
- BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain.
  [[pdf]](https://arxiv.org/pdf/1708.06733.pdf)
  [[journal]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8685687)
  - Tianyu Gu, Brendan Dolan-Gavitt, and Siddharth Garg. arXiv 2017 (*IEEE Access 2019*).

- Targeted Backdoor Attacks on Deep Learning Systems Using Data Poisoning.
  [[pdf]](https://arxiv.org/pdf/1712.05526.pdf)
  [[code]](https://github.com/GeorgePisl/backdoor-attacks-based-on-deep-learning)
  - Xinyun Chen, Chang Liu, Bo Li, Kimberly Lu, and Dawn Song. arXiv 2017.
  
- Trojaning Attack on Neural Networks.
  [[pdf]](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?referer=&httpsredir=1&article=2782&context=cstech)
  - Yingqi Liu, Shiqing Ma, Yousra Aafer, Wen-Chuan Lee, and Juan Zhai. *NDSS 2017*.


### Non-poisoning-based Attack  
- An Embarrassingly Simple Approach for Trojan Attack in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2006.08131.pdf)
  [[code]](https://github.com/trx14/TrojanNet)
  - Ruixiang Tang, Mengnan Du, Ninghao Liu, Fan Yang, and Xia Hu. *KDD 2020*.

- TBT: Targeted Neural Network Attack with Bit Trojan.
  [[pdf]](https://arxiv.org/abs/1909.05193)
  [[code]](https://github.com/adnansirajrakin/TBT-CVPR2020)
  - Adnan Siraj Rakin, Zhezhi He, and Deliang Fan. *CVPR 2020*.

- TrojanNet: Embedding Hidden Trojan Horse Models in Neural Network.
  [[pdf]](https://arxiv.org/pdf/2002.10078.pdf)
  - Chuan Guo, Ruihan Wu, and Kilian Q. Weinberger. arXiv 2020.

- Backdooring Convolutional Neural Networks via Targeted Weight Perturbations.
  [[pdf]](https://arxiv.org/pdf/1812.03128.pdf)
  - Jacob Dumford, and Walter Scheirer. arXiv 2018.
  
### Backdoor Defense
#### Inference Proprocessing based Empirical Defense
- Neural Trojans.
  [[pdf]](https://arxiv.org/pdf/1710.00942.pdf)
  - Yuntao Liu, Yang Xie, and Ankur Srivastava. *ICCD 2017*.

- Rethinking the Trigger of Backdoor Attack.
  [[pdf]](https://arxiv.org/pdf/2004.04692.pdf)
  - Yiming Li, Tongqing Zhai, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shutao Xia. arXiv 2020.

- Februus: Input Purification Defense Against Trojan Attacks on Deep Neural Network Systems.
  [[pdf]](https://arxiv.org/pdf/1908.03369.pdf)
  - Bao Gia Doan, Ehsan Abbasnejad, and Damith C. Ranasinghe. arXiv 2019.
  
- Model Agnostic Defense against Backdoor Attacks in Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1908.02203.pdf)
  - Sakshi Udeshi, Shanshan Peng, Gerald Woo, Lionell Loh, Louth Rawshan, and Sudipta Chattopadhyay. arXiv 2019.


#### Sample Filtering based Empirical Defense
- Spectral Signatures in Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/1811.00636.pdf)
  - Brandon Tran, Jerry Li, and Aleksander Madry. *NeurIPS 2018*.

- Detecting Backdoor Attacks on Deep Neural Networks by Activation Clustering.
  [[pdf]](https://arxiv.org/pdf/1811.03728.pdf)
  - Bryant Chen, Wilka Carvalho, Nathalie Baracaldo, Heiko Ludwig, Benjamin Edwards, Taesung Lee, Ian Molloy, and Biplav Srivastava. *AAAI Workshop 2019*

- STRIP: A Defence Against Trojan Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1902.06531.pdf)
  [[extension]](https://arxiv.org/pdf/1911.10312.pdf)
  [[code]](https://github.com/garrisongys/STRIP)
  - Yansong Gao, Chang Xu, Derui Wang, Shiping Chen, Damith C. Ranasinghe, and Surya Nepal. *ACSAC 2019*.

- Deep Probabilistic Models to Detect Data Poisoning Attacks.
  [[pdf]](https://arxiv.org/pdf/1912.01206.pdf)
  - Mahesh Subedar, Nilesh Ahuja, Ranganath Krishnan, Ibrahima J. Ndiour, and Omesh Tickoo. *NeurIPS Workshop 2019)*  

- Robust Anomaly Detection and Backdoor Attack Detection via Differential Privacy.
  [[pdf]](https://arxiv.org/pdf/1911.07116.pdf)
  [[code]](https://www.dropbox.com/sh/rt8qzii7wr07g6n/AAAbwokv2sfBeE9XAL2pXv_Aa?dl=0)
  - Min Du, Ruoxi Jia, and Dawn Song. *ICLR 2020*.  

- Exposing Backdoors in Robust Machine Learning Models.
  [[pdf]](https://arxiv.org/pdf/2003.00865.pdf)
  - Ezekiel Soremekun, Sakshi Udeshi, and Sudipta Chattopadhyay. arXiv 2020.

- A Unified Framework for Analyzing and Detecting Malicious Examples of DNN Models.
  [[pdf]](https://arxiv.org/pdf/2006.14871.pdf)
  - Kaidi Jin, Tianwei Zhang, Chao Shen, Yufei Chen, Ming Fan, Chenhao Lin, and Ting Liu. arXiv 2020.

- Demon in the Variant: Statistical Analysis of DNNs for Robust Backdoor Contamination Detection.
  [[pdf]](https://arxiv.org/pdf/1908.00686.pdf)
  - Di Tang, XiaoFeng Wang, Haixu Tang, and Kehuan Zhang. arXiv 2019.

- Poison as a Cure: Detecting & Neutralizing Variable-Sized Backdoor Attacks in Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1911.08040.pdf)
  - Alvin Chan, and Yew-Soon Ong. arXiv 2019.  
  
#### Model Reconstruction based Empirical Defense
- Neural Trojans.
  [[pdf]](https://arxiv.org/pdf/1710.00942.pdf)
  - Yuntao Liu, Yang Xie, and Ankur Srivastava. *ICCD 2017*.
  
- Fine-Pruning: Defending Against Backdooring Attacks on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/1805.12185.pdf)
  [[code]](https://github.com/kangliucn/Fine-pruning-defense)
  - Kang Liu, Brendan Dolan-Gavitt, and Siddharth Garg. *RAID 2018*.   
  
- Bridging Mode Connectivity in Loss Landscapes and Adversarial Robustness.
  [[pdf]](https://arxiv.org/pdf/2005.00060.pdf)
  [[code]](https://github.com/IBM/model-sanitization)
  - Pu Zhao, Pin-Yu Chen, Payel Das, Karthikeyan Natesan Ramamurthy, and Xue Lin. *ICLR 2020*.

- Defending against Backdoor Attack on Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2002.12162.pdf)
  - Hao Cheng, Kaidi Xu, Sijia Liu, Pin-Yu Chen, Pu Zhao, and Xue Lin. *KDD Workshop 2019*.

- Neural Network Laundering: Removing Black-Box Backdoor Watermarks from Deep Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2004.11368.pdf)
  - William Aiken, Hyoungshick Kim, and Simon Woo. arXiv 2020.


#### Model Diagnosis based Empirical Defense
- Universal Litmus Patterns: Revealing Backdoor Attacks in CNNs.
  [[pdf]](https://arxiv.org/pdf/1906.10842.pdf)
  [[code]](https://umbcvision.github.io/Universal-Litmus-Patterns/)
  - Soheil Kolouri, Aniruddha Saha, Hamed Pirsiavash, and Heiko Hoffmann. *CVPR 2020*.

- NeuronInspect: Detecting Backdoors in Neural Networks via Output Explanations.
  [[pdf]](https://arxiv.org/pdf/1911.07399.pdf)
  - Xijie Huang, Moustafa Alzantot, and Mani Srivastava. arXiv 2019.

- Detecting AI Trojans Using Meta Neural Analysis.
  [[pdf]](https://arxiv.org/pdf/1910.03137.pdf)
  - Xiaojun Xu, Qi Wang, Huichen Li, Nikita Borisov, Carl A. Gunter, and Bo Li. arXiv 2019.

#### Poison Suppression based Empirical Defense
- Robust Anomaly Detection and Backdoor Attack Detection via Differential Privacy.
  [[pdf]](https://arxiv.org/pdf/1911.07116.pdf)
  [[code]](https://www.dropbox.com/sh/rt8qzii7wr07g6n/AAAbwokv2sfBeE9XAL2pXv_Aa?dl=0)
  - Min Du, Ruoxi Jia, and Dawn Song. *ICLR 2020*.  
  
- On the Effectiveness of Mitigating Data Poisoning Attacks with Gradient Shaping.
  [[pdf]](https://arxiv.org/pdf/2002.11497.pdf)
  [[code]](https://github.com/Sanghyun-Hong/Gradient-Shaping)
  - Sanghyun Hong, Varun Chandrasekaran, Yiğitcan Kaya, Tudor Dumitraş, and Nicolas Papernot. arXiv 2020.  

#### Trigger Reconstruction based Empirical Defense
- Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks.
  [[pdf]](https://gangw.web.illinois.edu/class/cs598/papers/sp19-poisoning-backdoor.pdf)
  [[code]](https://github.com/bolunwang/backdoor)
  - Bolun Wang, Yuanshun Yao, Shawn Shan, Huiying Li, Bimal Viswanath, Haitao Zheng, Ben Y. Zhao. *IEEE S&P 2019*。

- Defending Neural Backdoors via Generative Distribution Modeling.
  [[pdf]](https://arxiv.org/pdf/1910.04749.pdf)
  [[code]](https://github.com/superrrpotato/Defending-Neural-Backdoors-via-Generative-Distribution-Modeling)
  - Ximing Qiao, Yukun Yang, and Hai Li. *NeurIPS 2019*.

- TABOR: A Highly Accurate Approach to Inspecting and Restoring Trojan Backdoors in AI Systems.
  [[pdf]](https://arxiv.org/pdf/1908.01763.pdf)
  [[code]](https://github.com/UsmannK/TABOR)
  - Wenbo Guo, Lun Wang, Xinyu Xing, Min Du, and Dawn Song. arXiv 2019.

- NNoculation: Broad Spectrum and Targeted Treatment of Backdoored DNNs.
  [[pdf]](https://arxiv.org/pdf/2002.08313.pdf)
  [[code]](https://github.com/akshajkumarv/NNoculation)
  - Akshaj Kumar Veldanda, Kang Liu, Benjamin Tan, Prashanth Krishnamurthy, Farshad Khorrami, Ramesh Karri, Brendan Dolan-Gavitt, and Siddharth Garg. arXiv 2020.

#### Certificated Defense
- On Certifying Robustness against Backdoor Attacks via Randomized Smoothing.
  [[pdf]](https://arxiv.org/pdf/2002.11750.pdf)
  - Binghui Wang, Xiaoyu Cao, Jinyuan jia, and Neil Zhenqiang Gong. *CVPR Workshop 2020*.

- RAB: Provable Robustness Against Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2003.08904.pdf)
  [[code]](https://github.com/AI-secure/Robustness-Against-Backdoor-Attacks)
  - Maurice Weber, Xiaojun Xu, Bojan Karlas, Ce Zhang, and Bo Li. arXiv 2020.


## Attack and Defense Towards Other Tasks
### 2020
- Backdoor Attacks against Transfer Learning with Pre-trained Deep Learning Models.
  [[pdf]](https://arxiv.org/pdf/2001.03274.pdf)
  - Shuo Wang, Surya Nepal, Carsten Rudolph, Marthie Grobler, Shangyu Chen, and Tianle Chen. *IEEE Transactions on Services Computing 2020*.

- Weight Poisoning Attacks on Pre-trained Models.
  [[pdf]](https://arxiv.org/pdf/2004.06660.pdf)
  [[code]](https://github.com/neulab/RIPPLe)
  - Keita Kurita, Paul Michel, and Graham Neubig. *ACL 2020*.

- Clean-Label Backdoor Attacks on Video Recognition Models.
  [[pdf]](http://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.pdf)
  - Shihao Zhao, Xingjun Ma, Xiang Zheng, James Bailey, Jingjing Chen, and Yu-Gang Jiang. *CVPR 2020*.

- NeuroAttack: Undermining Spiking Neural Networks Security through Externally Triggered Bit-Flips.
  [[pdf]](https://arxiv.org/pdf/2005.08041.pdf)
  - Valerio Venceslai, Alberto Marchisio, Ihsen Alouani, Maurizio Martina, and Muhammad Shafique. *IJCNN 2020*.
  
- Graph Backdoor.
  [[pdf]](https://arxiv.org/pdf/2006.11890.pdf)
  - Zhaohan Xi, Ren Pang, Shouling Ji, and Ting Wang. arXiv 2020.
  
- Backdoor Attacks to Graph Neural Networks. 
  [[pdf]](https://arxiv.org/pdf/2006.11165.pdf)
  - Zaixi Zhang, Jinyuan Jia, Binghui Wang, and Neil Zhenqiang Gong. arXiv 2020.
  
- Backdoor Attacks on Federated Meta-Learning. 
  [[pdf]](https://arxiv.org/pdf/2006.07026.pdf)
  - Chien-Lun Chen, Leana Golubchik, and Marco Paolieri. arXiv 2020. 

- BadNL: Backdoor Attacks Against NLP Models.
  [[pdf]](https://arxiv.org/pdf/2006.01043.pdf)
  - Xiaoyi Chen, Ahmed Salem, Michael Backes, Shiqing Ma, and Yang Zhang. arXiv 2020.

- Targeted Forgetting and False Memory Formation in Continual Learners through Adversarial Backdoor Attacks.
  [[pdf]](https://arxiv.org/pdf/2002.07111.pdf)
  - Muhammad Umer, Glenn Dawson, Robi Polikar. arXiv 2020.

- Exploring Backdoor Poisoning Attacks Against Malware Classifiers.
  [[pdf]](https://arxiv.org/pdf/2003.01031.pdf)
  - Giorgio Severi, Jim Meyer, Scott Coull, and Alina Oprea. arXiv 2020.

- Learning to Detect Malicious Clients for Robust Federated Learning. 
  [[pdf]](https://arxiv.org/pdf/2002.00211.pdf)
  - Suyi Li, Yong Cheng, Wei Wang, Yang Liu, and Tianjian Chen. arXiv 2020.

- Bias Busters: Robustifying DL-based Lithographic Hotspot Detectors Against Backdooring Attacks.
  [[pdf]](https://arxiv.org/pdf/2004.12492.pdf)
  - Kang Liu, Benjamin Tan, Gaurav Rajavendra Reddy, Siddharth Garg, Yiorgos Makris, and Ramesh Karri. arXiv 2020.


### 2019
- A Backdoor Attack Against LSTM-based Text Classification Systems.
  [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8836465)
  - Jiazhu Dai, Chuanshuai Chen, and Yufeng Li. *IEEE Access 2019*.

- Design of Intentional Backdoors in Sequential Models.
  [[pdf]](https://arxiv.org/pdf/1902.09972.pdf)
  - Zhaoyuan Yang, Naresh Iyer, Johan Reimann, and Nurali Virani. arXiv 2019.

- Trojan Attacks on Wireless Signal Classification with Adversarial Machine Learning.
  [[pdf]](https://arxiv.org/pdf/1910.10766.pdf)
  - Kemal Davaslioglu, and Yalin E. Sagduyu. *DySPAN 2019*.

- Can You Really Backdoor Federated Learning?
  [[pdf]](https://arxiv.org/pdf/1911.07963.pdf)
  - Ziteng Sun, Peter Kairouz, Ananda Theertha Suresh, and H. Brendan McMahan. *NeurIPS 2019 Workshop*

- Attack-Resistant Federated Learning with Residual-based Reweighting.
  [[pdf]](https://arxiv.org/pdf/1912.11464.pdf)
  [[code]](https://github.com/fushuhao6/Attack-Resistant-Federated-Learning)
  - Shuhao Fu, Chulin Xie, Bo Li, and Qifeng Chen. arXiv 2019.
  
### 2018
- How to Backdoor Federated Learning.
  [[pdf]](https://arxiv.org/pdf/1807.00459.pdf)
  - Eugene Bagdasaryan, Andreas Veit, Yiqing Hua, Deborah Estrin, and Vitaly Shmatikov. *AISTATS 2020* (arXiv 2018).

## Properties Discussion and Evaluation
- A Tale of Evil Twins: Adversarial Inputs versus Poisoned Models.
  [[pdf]](https://arxiv.org/pdf/1911.01559.pdf)
  [[code]](https://github.com/alps-lab/imc)
  - Ren Pang, Hua Shen, Xinyang Zhang, Shouling Ji, Yevgeniy Vorobeychik, Xiapu Luo, Alex Liu, and Ting Wang. *CCS 2020*.

- Systematic Evaluation of Backdoor Data Poisoning Attacks on Image Classiﬁers.
  [[pdf]](https://arxiv.org/pdf/2004.11514.pdf)
  - Loc Truong, Chace Jones, Brian Hutchinson, Andrew August, Brenda Praggastis, Robert Jasper, Nicole Nichols, and Aaron Tuor. *CVPR Workshop 2020*

- Rethinking the Trigger of Backdoor Attack.
  [[pdf]](https://arxiv.org/pdf/2004.04692.pdf)
  - Yiming Li, Tongqing Zhai, Baoyuan Wu, Yong Jiang, Zhifeng Li, and Shutao Xia. arXiv 2020.
  
- Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and Data Poisoning Attacks.
  [[pdf]](https://arxiv.org/pdf/2006.12557.pdf)
  [[code]](https://github.com/aks2203/poisoning-benchmark)
  - Avi Schwarzschild, Micah Goldblum, Arjun Gupta, John P Dickerson, and Tom Goldstein. arXiv 2020.

- Backdoor Attacks on Facial Recognition in the Physical World.
  [[pdf]](https://arxiv.org/pdf/2006.14580.pdf)
  - Emily Wenger, Josephine Passanati, Yuanshun Yao, Haitao Zheng, and Ben Y. Zhao. arXiv 2020.

## Application in other Tasks
- Turning Your Weakness into a Strength: Watermarking Deep Neural Networks by Backdooring.
  [[pdf]](https://arxiv.org/pdf/1802.04633.pdf)
  [[code]](https://github.com/adiyoss/WatermarkNN)
  - Yossi Adi, Carsten Baum, Moustapha Cisse, Benny Pinkas, and Joseph Keshet. *USENIX Security 2018*. 

- Towards Probabilistic Verification of Machine Unlearning.
  [[pdf]](https://arxiv.org/pdf/2003.04247.pdf)
  [[code]](https://github.com/inspire-group/unlearning-verification)
  - David Marco Sommer, Liwei Song, Sameer Wagh, and Prateek Mittal. arXiv 2020. 

