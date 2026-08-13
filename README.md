# Semi-Supervised Framework for Error Debugging in VLSI Using Deep Learning

# About the Project

Finding faults in VLSI circuits can be a time-consuming process, especially when the circuits become large and complex. This project focuses on using deep learning techniques to make VLSI fault detection and debugging easier and more efficient.

In this project, ATALANTA is used to generate test patterns for different benchmark VLSI circuits. The generated data is then processed using a Variational Autoencoder (VAE) to learn useful features. Deep learning models such as CNN and Bi-LSTM are used to identify faults in combinational and sequential circuits.

The main idea is to combine traditional VLSI testing methods with deep learning so that faults can be detected more effectively.

# Project Objectives

The main objectives of this project are:

* To generate test patterns for VLSI circuits using ATALANTA.
* To process and prepare the generated test-pattern data.
* To use VAE for extracting useful features from the data.
* To use CNN for analyzing combinational circuits.
* To use Bi-LSTM for analyzing sequential circuits.
* To identify and locate faults in VLSI circuits.
* To evaluate how well the proposed models perform.

# How the Project Works

The project uses ATALANTA to generate test patterns for VLSI circuits. The patterns are processed using VAE to extract useful features. CNN is used for combinational circuits and Bi-LSTM for sequential circuits to detect faults. Finally, the results are evaluated using different performance metrics to check the accuracy of fault detection.

### Step 1: Test Pattern Generation

First, ATALANTA is used to generate test patterns for the selected VLSI benchmark circuits. These patterns are used as the input data for further analysis.

### Step 2: Data Processing

The generated test patterns are collected and prepared so that they can be used for training and testing the deep learning models.

### Step 3: Feature Extraction using VAE

A Variational Autoencoder is used to learn important features from the test-pattern data. This helps reduce unnecessary information and provides useful representations for the next stage.

### Step 4: Fault Detection

For combinational circuits, a CNN model is used to learn patterns related to faults.

For sequential circuits, a Bi-LSTM model is used because it can learn relationships between data patterns over a sequence.

### Step 5: Evaluation

The trained models are evaluated using different performance measures to understand how accurately they can detect faults.

## Circuits Used

The project uses different benchmark VLSI circuits for testing and evaluation.

The repository includes:

* C432
* C880
* C1908
* S1238
* S1488

Circuit images are also included in the repository to provide a visual representation of the circuits.


# Files in This Repository

### Source and Documentation

* Code_vlsi_project.txt – Contains the project code and implementation details.
* Project_Report.pdf – Complete project report with the methodology, experiments and results.
* project_outputs.docx – Contains the project outputs and related results.

### Circuit Images

* C432_IMG.png
* C880_IMG.png
* C1908_IMG.png
* S1238_IMG.png
* S1488_IMG.png

### Test Pattern Files

* c432.pat
* c880.pat
* c1908.pat
* s1238.pat
* s1488.pat

These files contain the test patterns generated for the respective benchmark circuits.

# Tools and Technologies Used

* Python – Used for implementing the project and processing data.
* ATALANTA – Used for automatic test pattern generation.
* VAE – Used for feature extraction.
* CNN – Used for combinational circuit fault analysis.
* Bi-LSTM – Used for sequential circuit fault analysis.
* Deep Learning – Used for detecting and analyzing circuit faults.
* VLSI Benchmark Circuits – Used to test and evaluate the framework.

# Performance Evaluation

The performance of the models is studied using different machine learning metrics, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Fault Coverage
* Hamming Loss
* Confusion Matrix
* ROC Curve
* MCC
* KL Divergence

These measures help us understand how effectively the models are able to identify faults.

# Results

The project was tested using benchmark circuits such as C432, C880, C1908, S1238 and S1488.
The results show that deep learning can be combined with traditional ATPG techniques to support automated VLSI fault detection and debugging.The detailed results and observations can be found in the Project_Report.pdf and project_outputs.docx files included in this repository.

# Applications

This project can be useful in areas such as:

* VLSI testing
* Digital circuit debugging
* Fault detection
* Automatic Test Pattern Generation
* Semiconductor testing
* Hardware verification
* Deep learning-based circuit analysis
* Automated fault diagnosis

# Future Improvements

In the future, the project can be improved by:

* Testing the framework with more benchmark circuits.
* Improving the accuracy of fault localization.
* Trying other advanced deep learning models.
* Automating more parts of the testing process.
* Creating a simple interface for users to upload and analyze circuits.
* Reducing the time required for training and testing.
* Exploring newer models for sequential circuit analysis.

# Project Documentation

For a detailed explanation of the project, please refer to:

Project Report : Project_Report.pdf

Project Outputs : project_outputs.docx

Source Code : Code_vlsi_project.txt

#Project Area

VLSI | Deep Learning | ATPG | Fault Detection | CNN | Bi-LSTM | VAE

# Conclusion

This project explores how deep learning can be used along with traditional VLSI testing techniques to make fault detection easier and more efficient. By using ATALANTA for test pattern generation and models such as VAE, CNN and Bi-LSTM for data analysis, the project provides a practical approach toward automated VLSI debugging.
