# Pose-Based Human Localization and Height Estimation from FIFA Player Images

## How to run the code
1. 01_Data Resources.ipynb
   : Dataset construction and preprocessing
2. 02_PoseClassification_HeightRegression.ipynb
   : Pose classification and pose-based height regression
3. 03_HeightRegression_baseline.ipynb
   : Baseline height regression without pose filtering

## Data 
### Data Source
- ⚽FIFA WORLD CUP 2022🏆 ALL PLAYER'S IMAGE DATASET⚽
  : Contains images collected from web sources
  : https://www.kaggle.com/datasets/soumendraprasad/fifa-2022-all-players-image-dataset
- FIFA 24 Player Stats Dataset
  : Contains player names and height labels
  : https://www.kaggle.com/datasets/rehandl23/fifa-24-player-stats-dataset

### Raw and intermediate CSV files
- fifa_height_labels.csv
- fifa_pose_keypoints_raw.csv
- fifa_pose_keypoints_labeled.csv
- fifa_pose_keypoints_3class.csv

## Models
Saved model checkpoints
