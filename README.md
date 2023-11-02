# CardiacUDA-dataset

We collect CardiacUDA from our two hospitals: site G and site R. In order to guarantee all echocardiogram videos are standardscompliant, all cases of CardiacUDA are collected, annotated and approved by 5-6 experienced physicians. For
ethical issues, we have required approval from medical institutions. Each patient underwent four views during scanning, which included parasternal left ventricle long axis (LVLA), pulmonary artery long axis (PALA),
left ventricular short-axis (LVSA), and apical fourchamber heart (A4C), resulting in four videos per patient. The resolution of each video was either 800x600 or 1024x768, depending on the scanner used (Philips
or HITACHI). A total of 516 and 476 videos were collected from Site G and Site R, respectively, from approximately 100 different patients. Each video consists of over 100 frames, covering at least one heartbeat cycle.

We have provided pixel-level annotations for each view, including masks for the left ventricle (LV) and right ventricle (RV) in the LVLA view, masks for the pulmonary artery (PA) in the PALA view, masks for the
LV and RV in the LVSA view, and masks for the LV, RV, left atrium (LA), and right atrium (RA) in the A4C view. The videos in both Site R and Site G were divided into a ratio of 8:1:1 for training, validation, and testing,
respectively. To lower annotation costs in the training set, only five frames per video are provided with pixellevel annotation masks. To better measure the model performance, we provide pixel-level annotations for every frame in each video in the validation and testing sets.

Please refer to the code (https://github.com/xmed-lab/GraphEcho) and our ICCV paper (https://arxiv.org/abs/2309.11145) for more detailes.

**HIGHLIGHT** 20231101: We have deployed the dataset on Kaggle! https://www.kaggle.com/xiaoweixumedicalai/datasets

Please send emails to xiao.wei.xu@foxmail.com for any questions.
