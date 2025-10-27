# Cardiac-MRI-segmentation
Code to accompany the paper Fine-Tuning the Segment Anything Model (SAM) and Its Enhanced Versions (SAM2, SAM2.1) for Robust Segmentation of Cardiac Structures in Cine MRI


Acknowledgements

**Datasets acknoledgement**
1. This project uses the [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/databases.html) dataset (Automated Cardiac Diagnosis Challenge) provided by the University Hospital of Dijon (France). The dataset was released as part of the ACDC Challenge and contains short-axis cine-MRI data from 150 patients across five classes: healthy, myocardial infarction, dilated cardiomyopathy, hypertrophic cardiomyopathy, and abnormal right ventricle. Please cite the following paper when using this dataset:
   Bernard, A. Lalande, C. Zotti, F. Cervenansky, et al. Deep Learning Techniques for Automatic MRI Cardiac Multi-structures Segmentation and Diagnosis: Is the Problem Solved? IEEE Transactions on Medical Imaging, vol. 37, no. 11, pp. 2514-2525, Nov. 2018. https://doi.org/10.1109/TMI.2018.2837502
   The data are anonymized and were handled under the regulations of the local ethical committee. Use of the ACDC dataset is subject to its official terms and citation requirements as listed on the ACDC website

3. This project also uses the [M&Ms](https://www.ub.edu/mnms/) dataset (Multi-Centre, Multi-Vendor & Multi-Disease Cardiac Segmentation Challenge), provided as part of the MICCAI 2020 challenge and hosted by University of Barcelona. The dataset comprises heterogeneous cine-MRI data from multiple centres, vendors and disease conditions (including healthy subjects and various cardiomyopathies) and is intended to enable research on model generalisation across clinical sites and imaging settings. 

Please cite the following paper when using this dataset: V. M. Campello, P. Gkontra, C. Izquierdo, C. Martin-Isla, A. Sojoudi, P. M. Full, K. Maier-Hein, et al. “Multi-Centre, Multi-Vendor and Multi-Disease Cardiac Segmentation: The M&Ms Challenge” IEEE Transactions on Medical Imaging, 2021. DOI: 10.1109/TMI.2021.3090082. 
Use of the M&Ms dataset is subject to its official terms and citation requirements — please refer to the challenge website for details

**Code acknoledgement**:

1. We thank the authors for making the fine-tuning workflow for [SAM](mazurowski-lab/finetune-SAM) available.
   The work is described in the paper: Hanxue Gu, Haoyu Dong, Jichen Yang, Maciej A. Mazurowski, “How to build the best medical image segmentation algorithm using foundation models: a comprehensive empirical study with Segment Anything Model”, arXiv:2404.09957 (2024)

3. We also acknoledge the original [SAM](facebookresearch/segment-anything) source code.
   Please cite the original work if you use SAM in your research or project: A. Kirillov, E. Mintun, N. Ravi, H. Mao, C. Rolland, L. Gustafson, T. Xiao, S. Whitehead, A. Berg, W.-Y. Lo, P. Dollár, R. Girshick, “Segment Anything”, arXiv:2304.02643, 2023.

3. We thank Meta AI for making the source code of [SAM2](facebookresearch/sam2) publicly available.
   The model is described in the paper: N. Ravi, V. Gabeur, Y.-T. Hu, R. Hu, C. Ryali, T. Ma, H. Khedr, R. Rädle, C. Rolland, L. Gustafson, E. Mintun, J. Pan, K. Vasudev Alwala, N. Carion, C.-Y. Wu, R. Girshick, P. Dollár, C. Feichtenhofer, “SAM 2: Segment Anything in Images and Videos”, ICLR 2025. Hugging Face

2. We also thank the authors for making the source code for [MedSAM2](bowang-lab/MedSAM2) publicly available.
   The model is described in the pre-print: Jun Ma, Zongxin Yang, Sumin Kim, Bihui Chen, Mohammed Baharoon, Adibvafa Fallahpour, Reza Asakereh, Hongwei Lyu, Bo Wang, “MedSAM2: Segment Anything in 3D Medical Images and Videos”, arXiv pre-print arXiv:2504.03600, 2025.
