{\rtf1}

*Video Advertisement Classifier*
*Project Overview*
This project involves creating a classifier to evaluate video advertisements based on multiple criteria extracted from a ground truth CSV file. The classifier is designed to answer 21 binary (yes/no) questions for each of the 150 video advertisements. The results include metrics such as precision, recall, F1 score, and agreement percentage.



To run the project, execute the meenakshisundaram.m_code.ipynb notebook. Ensure that all video data, textual data, and ground-truth data are stored in the Data folder and update the paths accordingly within the notebook.
 

*Data Description*
sample: This folder should contain 150 video files that need to be evaluated.
ground-truth.xlsx: This Excel file contains the ground truth annotations for the videos. The columns include Timestamp, creative_data_id, and 21 questions related to video advertisements.


*Evaluation Metrics*
Precision: The ratio of true positive predictions to the total number of positive predictions.
Recall: The ratio of true positive predictions to the total number of actual positive instances.
F1 Score: The harmonic mean of precision and recall.
Agreement Percentage: The percentage of predictions that match the ground truth.
Results
The results of the classifier's performance will be outputted in the terminal and saved in the results/ directory as a CSV file.