# Artifact-Resilient-EEG-system-for-Hand-Motor-Imagery-Classification
INSE 6450: AI in Systems Engineering (Project Work)
Pralhad Chapagain (ID: 40352467)

This is the Milestone 1 for the INSE 6450 Project work.
In this milestone, Dataset selection, loading, preprocessing and feature extraction part were done.
This project processes the PhysioNet EEG Motor Movement/Imagery Dataset (EEGBCI) from raw EDF files all the way to cleaned, artifact-free EEG epoches.
The program structure:
1. Loading Dataset
2. Preprocessing
3. Quality Check
4. Visualization

   Dataset are directly loaded from the mne and selected first 5 subject among 109 for computational constraint and generalization. Each subject has 14 different run, among them 4,8 and 12 are for motor imagery left and right hand movement so these 3 runs are choosen.
   In preprocessing, First checks for the Missingness, High amplitude artifacts, EMG artifacts, Outlier, Duplicates and class imbalance and after that try to resolve these issues.
   Before and After preprocessing results are plotted for the qua;ity check and visulization.

This project uses:
1. Python 3.12.7
2. NumPy
3. SciPy
4. Matplotlib
5. MNE-Python 

   

