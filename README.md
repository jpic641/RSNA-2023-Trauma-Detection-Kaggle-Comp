# RSNA-2023-Trauma-Detection-Kaggle-Comp
 Kaggle's Abdominal Trauma Detection competition project

# Problem Statement
Please see:
https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection/overview

# Approach
1. First approach was using the kerasCV starter notebook, using a dataset converted from dicom to .png and Resnet50
2. Second approach was replacing the Resenet50 model with efficientnet as the backbone and improved the score.
3. Third approach was made using the efficientnet_version0_backbone1 (efficientnetV0B1) model and using k-fold cross validation to obtain far better results.
4. Further progress was made using a published (on the competition page) variation of the dataset (2.5D: sequential scans in the same series stacked to create an RGB like image but each channel represented by each scan) and using efficientnetV1B1.

Note: Final submission was built from a published notebook from kaggle grandmaster AWSAF and modified to improve the result.


# Reference
A noteworthy discussion that helped submission: 
https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection/discussion/435053#2425570 

Chest CT Scan Machine Learning in 5 minutes
https://glassboxmedicine.com/2020/08/04/chest-ct-scan-machine-learning-in-5-minutes/
