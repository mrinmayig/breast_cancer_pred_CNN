# Predicting Invasive Ductal Carcinoma using Convolutional Neural Network (CNN)

# Dataset obtained from: http://www.andrewjanowczyk.com/use-case-6-invasive-ductal-carcinoma-idc-segmentation/ 
The original dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive).

Each patch’s file name is of the format:

u_xX_yY_classC.png — > example 10253_idx5_x1351_y1101_class0.png

Where u is the patient ID (10253_idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.


# Tags: Image Classification, Breast Cancer Detection, Convolutional Neural Network (CNN), Loading Data, Normalization, Data Augmentation, Random Undersampling, Train-test Split, Model Training, Model Evaluation, Prediction, ROC Curve, Precision, Recall, Accuracy

# Tools: OpenCV, Python, Fnmatch, Glob, NumPy, Matplotlib, Keras, Scikit-Learn, Imblearn, Jupyter Notebook




