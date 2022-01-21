# Credit_Risk_Analysis
Module 17

# Overview

The purpose of this analysis was to apply machine learning to solve the challenge of credit card risk. Using the LendingClub provided credit card credit data set, oversampling, undersampling, a combination of over and undersampling (SMOTEENN) and reducing bias were used to predict credit risk.

# Results

* For the Naive Random Oversampling, the balanced accuracy score was 0.65. The high risk precision is 0.01 with a sensitivity of 0.60.

![naive_random_oversampling_bas](https://user-images.githubusercontent.com/90632470/150577504-c8f5eb12-e624-4773-9066-cf6b76400a4b.png)

![naive_random_oversampling](https://user-images.githubusercontent.com/90632470/150577516-95589c6b-116a-4290-b7bd-e32f2331bca0.png)


* For the SMOTE Oversampling, the balanced accuracy score was 0.64. The high risk precision is 0.01 with a sensitivity of 0.63.

![SMOTE_oversampling_bas](https://user-images.githubusercontent.com/90632470/150577535-4ab9e68f-db43-437e-be06-871cd88a4b78.png)

![SMOTE_oversampling](https://user-images.githubusercontent.com/90632470/150577543-36e81c8a-cbd0-4e15-bb0e-8bde4d1c5ff4.png)


* For the Undersampling, the balanced accuracy score was 0.64. The high risk precision is 0.01 with a sensitivity of 0.67.

![undersampling_bas](https://user-images.githubusercontent.com/90632470/150577568-d5d715e0-cfb6-47dd-a9eb-59a74c150f17.png)

![undersampling](https://user-images.githubusercontent.com/90632470/150577591-2cd2057b-adab-456b-a4b5-2cda71d892b8.png)


*  For the Combination (Over and Under) Sampling,  the balanced accuracy score was 0.62. The high risk precision is 0.01 with a sensitivity of 0.70.

![combo_bas](https://user-images.githubusercontent.com/90632470/150577605-bcfe60e0-2667-4083-af72-47b6069d8824.png)

![combo](https://user-images.githubusercontent.com/90632470/150577620-a7d2cb6f-14df-4b67-aa31-83aa238a5e17.png)


# Summary

It doesn't appear that the models used to perform the credit risk analysis are adequate at determining if credit risk is high.
