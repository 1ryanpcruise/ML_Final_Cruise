# ML_Final_Cruise
This is my final project for CISC5800 - Machine Learning - Fall 2025 at Fordham University

## Content Descriptions

### bash_scripts
1. mk_dir_health.sh - This script creates a new directory structure with all the classes divided into either plant-healthy or plant-unhealthy.
2. mk_dir_skf.sh - This script creates a new directory structure where all the files are within one parent directory (no sub-directories), and the class names have been appended onto the file names.
3. mk_dir_small.sh - This script creates a new directory structure for the "small" dataset. This dataset has the same structure as the original, but only has 20 classes and about 56,000 samples.

### keras_models
1. cnn_small_final.keras is from the "small" dataset.
2. model{0-3}.keras are saved models from the SKF model.

### Individual Files
1. ML_Final_Cruise.ipynb is my main Jupyter Notebook with most of the code for my project.
2. ML_Final_Cruise_copy.pdf is a PDF file of the Jupyter Notebook with the same name.
3. ML_Final_Cruise_SKF.ipynb is my Jupyter Notebook that only has the Stratified K-Fold model on it (becuase it took so long to run).
4. ML_Final_Cruise_SKF_copy.pdf is a PDF file of the Jupyter Notebook with the same name.
5. ML_Final_Cruise.pdf is the write-up for my final project. 
