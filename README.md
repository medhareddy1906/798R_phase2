# 798R_phase2

Instrucrtions :
Install Dependencies
Use the requirements.txt file to install all required libraries for the project.

Prepare Dataset
Place the EEG .edf files and subject-info.csv file in the data/ folder. Each subject should have two files: one with _1 for background recording and another with _2 for the task recording. Dataset link : https://physionet.org/content/eegmat/1.0.0/.

Run Preprocessing and Training
First, run the preproceesing script to apply transformations to the data, then proceed with the training script to train the CNN-BLSTM model.

Evaluate the Model
Run the evaluation script to generate performance metrics, such as accuracy, precision, recall, F1-score, and AUC, for the trained model.
