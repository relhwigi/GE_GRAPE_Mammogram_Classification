# Datasets
## Data Breakdown
A general description of the dataset would be that each row corresponds to a specific segment of each breast at a specific mammogram view. Each column in a row then contains information on the patient, the study, the mammogram view performed, the segment it relates to, descriptions of many haralick features at multiple rotations of the segment in question and the same segment on the opposite breast, and a label. All together there is 111 columns, of them, 104 describe haralick features.

## Haralick Features
Haralick features describe textural features for an image such as variance, en- tropy and correlation. They’re calculated from a grey level co-occurrence matrix (GLCM) which is a common method to represent image texture, as it is simple to implement and results in a set of interpretable texture descriptors.


## File Breakdown
haralick02.csv - contains the full dataset of 405,280 rows.
haralick02_250K.csv - contains a subset of the full dataset, 24,999 rows.
