# SIFT_ORB_TL_Pred

# SIFT and ORB-Based Turkish Lira (TL) Prediction Project

This project aims to recognize Turkish Lira banknotes using SIFT and ORB feature extraction algorithms for image-based prediction.

## Project Purpose

The main objective of our project is to predict the value of Turkish Lira banknotes based on features extracted from their images. SIFT and ORB algorithms are utilized to identify unique features in the banknotes.

## Used Algorithms

### SIFT (Scale-Invariant Feature Transform)

- **Advantages:**
  - High feature extraction capacity.
  - Resistant to scale and rotations.

- **Disadvantages:**
  - High computational cost.

### ORB (Oriented FAST and Rotated BRIEF)

- **Advantages:**
  - Fast operation.
  - Effective in real-time applications.

- **Disadvantages:**
  - May extract fewer features.

## Functions

1. **Feature Extraction:**
   - Features are extracted for each banknote using SIFT and ORB algorithms.

2. **Matching:**
   - Matching is performed using FLANN-based matching to compare test images with reference data.

3. **Prediction and Visualization:**
   - The best match is determined to predict the currency of the test images.
   - Results are printed on the screen and visualized.

## Results and Evaluation

- SIFT and ORB algorithms successfully predicted the value of banknotes by extracting features.
- SIFT algorithm accurately predicted all banknotes in the test folder.
- ORB algorithm accurately predicted all but one banknote in the test folder.
- SIFT algorithm extracts more features and makes better predictions but operates slower.
- ORB algorithm extracts fewer features, makes less accurate predictions, but operates faster.
