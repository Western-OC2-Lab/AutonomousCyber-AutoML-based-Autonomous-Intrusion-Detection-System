# AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System
This repository includes code for the paper ["Towards Autonomous Cybersecurity: An Intelligent AutoML Framework for Autonomous Intrusion Detection"](https://dl.acm.org/doi/10.1145/3689933.3690833) accepted to the Workshop on Autonomous Cybersecurity (AutonomousCyber 2024), ACM CCS 2024 ([Top-3 Cybersecurity Conference](http://jianying.space/conference-ranking.html)).  

Authors: Li Yang (liyanghart@gmail.com) and Abdallah Shami  

Organizations: 
- The Advanced Networking Technology and Security (ANTS) Lab, Faculty of Business and IT, Ontario Tech University
- The Optimized Computing and Communications (OC2) Lab, ECE Department, Western University

The paper is publicly available on ArXiv: ["Towards Autonomous Cybersecurity: An Intelligent AutoML Framework for Autonomous Intrusion Detection"](https://arxiv.org/pdf/2409.03141)

In this work, we propose a novel and comprehensive AutoML framework that enables fully autonomous intrusion detection in next-generation networks, holding the potential to achieve fully autonomous cybersecurity. To achieve autonomous intrusion detection, the proposed AutoML framework automates all critical procedures of the data analytics pipeline, including data pre-processing, feature engineering, model selection, hyperparameter tuning, and model ensemble. 

If you are interested in AutoML and autonomous intrusion detection, below are two other comprehensive GitHub repositories:  
1. [AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics](https://github.com/Western-OC2-Lab/AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics)  
2. [AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security)  

## Abstract of The Paper
The rapid evolution of mobile networks from 5G to 6G has necessitated the development of autonomous network management systems, such as Zero-Touch Networks (ZTNs). However, the increased complexity and automation of these networks have also escalated cybersecurity risks. Existing Intrusion Detection Systems (IDSs) leveraging traditional Machine Learning (ML) techniques have shown effectiveness in mitigating these risks, but they often require extensive manual effort and expert knowledge. To address these challenges, this paper proposes an Automated Machine Learning (AutoML)-based autonomous IDS framework towards achieving autonomous cybersecurity for next-generation networks. To achieve autonomous intrusion detection, the proposed AutoML framework automates all critical procedures of the data analytics pipeline, including data pre-processing, feature engineering, model selection, hyperparameter tuning, and model ensemble. Specifically, it utilizes a Tabular Variational Auto-Encoder (TVAE) method for automated data balancing, tree-based ML models for automated feature selection and base model learning, Bayesian Optimization (BO) for hyperparameter optimization, and a novel Optimized Confidence-based Stacking Ensemble (OCSE) method for automated model ensemble. The proposed AutoML-based IDS was evaluated on two public benchmark network security datasets, CICIDS2017 and 5G-NIDD, and demonstrated improved performance compared to state-of-the-art cybersecurity methods. This research marks a significant step towards fully autonomous cybersecurity in next-generation networks, potentially revolutionizing network security applications.

<p float="left">
  <img src="https://github.com/Western-OC2-Lab/AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System/blob/main/Framework.jpg" width="500" />
</p>

## AutoML Pipeline and Procedures
1. Automated Data Pre-Processing (focusing on data balancing)
2. Automated Feature Engineering
3. Automated Model Selection
4. Hyper-Parameter Optimization
5. Automated Model Ensemble

## Implementation
### Machine Learning Algorithms  
* Decision tree (DT)
* Random forest (RF)
* Extra trees (ET)
* XGBoost  
* LightGBM  
* CatBoost

### Data Balancing Methods
* Tabular Variational Auto-Encoder (TVAE)

### Feature Selection Methods
* Feature Importance Averaging

### Optimization/AutoML Algorithms  
* Bayesian Optimization with Tree-structured Parzen Estimator (BO-TPE)

### Ensemble Learning Algorithms  
* Stacking
* Confidence-based Stacking

### Datasets 
1. CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
   * Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html  
   
2. 5G-NIDD dataset, a state-of-the-art 5G network security dataset
   * Publicly available at: https://ieee-dataport.org/documents/5g-nidd-comprehensive-network-intrusion-detection-dataset-generated-over-5g-wireless

### Code  
* [AutonomousCyber24_Dataset_1.ipynb](https://github.com/Western-OC2-Lab/AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System/blob/main/AutonomousCyber24_Dataset_1.ipynb): code for the sampled CICIDS2017 dataset.  
* [AutonomousCyber24_Dataset_2.ipynb](https://github.com/Western-OC2-Lab/AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System/blob/main/AutonomousCyber24_Dataset_2.ipynb): code for the sampled 5G-NIDD dataset.
  

### Requirements  
* Python 3.7+ 
* [scikit-learn](https://scikit-learn.org/stable/)  
* [hyperopt](https://github.com/hyperopt/hyperopt)  
* [Xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [lightgbm](https://lightgbm.readthedocs.io/en/v3.3.2/Python-Intro.html)
* [catboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [sdv](https://docs.sdv.dev/sdv)

## Contact-Info
Please feel free to contact me for any questions or cooperation opportunities. I'd be happy to help.
* Email: [liyanghart@gmail.com](mailto:liyanghart@gmail.com)
* GitHub: [LiYangHart](https://github.com/LiYangHart) and [Western OC2 Lab](https://github.com/Western-OC2-Lab/)
* LinkedIn: [Li Yang](https://www.linkedin.com/in/li-yang-phd-65a190176/)  
* Google Scholar: [Li Yang](https://scholar.google.com.eg/citations?user=XEfM7bIAAAAJ&hl=en)

## Citation
If you find this repository useful in your research, please cite this article as:  

L. Yang and A. Shami, “Towards Autonomous Cybersecurity: An Intelligent AutoML Framework for Autonomous Intrusion Detection,” in Proceedings of the Workshop on Autonomous Cybersecurity (AutonomousCyber ’24), 2024 ACM SIGSAC Conference on Computer and Communications Security (CCS’24), 2024, pp. 1–11. doi: 10.1145/3689933.3690833.

```
@INPROCEEDINGS{3690833,
  author={Yang, Li and Shami, Abdallah},
  title = {Towards Autonomous Cybersecurity: An Intelligent AutoML Framework for Autonomous Intrusion Detection},
  booktitle = {Proceedings of the Workshop on Autonomous Cybersecurity (AutonomousCyber '24), ACM Conference on Computer and Communications Security (CCS) 2024},
  year = {2024},
  address = {Salt Lake City, UT, USA},
  pages = {1-11},
  doi = {10.1145/3689933.3690833}
}
```
