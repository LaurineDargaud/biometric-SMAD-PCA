# biometric-SMAD-PCA
Python code for PCA-based method in Single Image Face Morphing Attack Detection

Here is the code used for the PCA-based S-MAD approach.

1. DATA_PREPROCESSING.ipynb: Notebook I, for data preprocessing and LPB features generation
	- needs lpb.py file
2. PROPOSED_METHOD.ipynb: Notebook II, to conduct an experiment with proposed PCA-based method
	- needs exercise5.py (Gaussian Process Bayesian Classifier code)
3. DET_SCRIPT_SHORT.ipynb: Notebook III, for DET curves and D-EER computing
	- need DET.py (course material)
4. PCA_VISUALIZATION.ipynb: Notebook IV, to visualize some elements from a given PCA

In data, you can find:
- in S-MAD-Experiments
	- the repositories of all conducted experiments, with save txt files
	- all associated reports
	- a merged report, that combine all experiment reports
- the empty repositories that should contain FERET and FRGCv2 processed pictures
