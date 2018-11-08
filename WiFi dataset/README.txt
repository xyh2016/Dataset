Wi-Fi Dataset
=====================================================
Wi-Fi dataset comes from the Data Mining Challenge at the 2007 ICDM International Conference. This challenge aims to predict the coordinate based on the strength of the nearby wireless signal. 
This dataset has been used in the paper entitled by "A Unified Framework for Metric Transfer Learning".

# Original Source
http://www.cse.ust.hk/~qyang/ICDMDMC07/

# Attribute Information
(1) wifi_icdm2007.mat: this dataset is used for traditional regression task.
  - Including 2642 instances: 505 for training, 2137 for test. 
  - The dimension of the instances is 101. Each attribute represents the strength of a nearby ap.
  -struct
    --> src_X:  training instance
    --> src_labels: coordinate for each instance in src_X
    --> tar_X:  test instance
    --> tar_labels: coordinate for each instance in tar_X

(2) wifi_icdm2007_tr_99.mat: this dataset is used for transfer learning task on regression problem.
  - Including 621 instances in source domain, 3128 instances in target domain.
  - The dimension of the instances is 99. Each attribute represents the strength of a nearby ap.
  -struct
    --> src_X:  training instance from source domain instance
    --> src_labels: coordinate for each instance in src_X
    --> tar_train_X:  training instance from target domain
    --> tar_train_labels: coordinate for each instance in tar_train_X
    --> tar_test_X:  test instance from target domain
    --> tar_test_labels: coordinate for each instance in tar_test_X

# Copyright Notice
This procedure is for scientific use only and can not be used for commercial purposes. If you are going to use the program in a paper or work, please quote the following paper.


# Citation Request
Please refer to the following paper:

Y. Xu et al., "A Unified Framework for Metric Transfer Learning," in IEEE Transactions on Knowledge and Data Engineering, vol. 29, no. 6, pp. 1158-1171, June 1 2017.
doi: 10.1109/TKDE.2017.2669193

@ARTICLE{7855802, 
author={Y. Xu and S. J. Pan and H. Xiong and Q. Wu and R. Luo and H. Min and H. Song}, 
journal={IEEE Transactions on Knowledge and Data Engineering}, 
title={A Unified Framework for Metric Transfer Learning}, 
year={2017}, 
volume={29}, 
number={6}, 
pages={1158-1171},
doi={10.1109/TKDE.2017.2669193}, 
ISSN={1041-4347}, 
month={June},}
