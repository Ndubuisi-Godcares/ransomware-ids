# Ransomeware Detection and Mitigation using Machine Learning
This repository proposes an advanced IDS for real-time ransomware detection based on ransomware classification, and prevention using machine learning and network traffic analysis. The project aims to develop a machine learning-based system for the real-time detection and mitigation of ransomware attacks. With the increasing prevalence of ransomware threats, traditional security measures are often insufficient. Our solution leverages advanced machine learning algorithms to enhance cybersecurity defenses and minimize the impact of such attacks.

# Installation packages 
**Google Colab**
  
    !pip install pandas
    !pip install scikit-learn
The pandas package is for table handling, since or dataset will be in a tabular format, i.e Stuctured data format which is made up of rows and columns.

The scikit-learn comprises of so many packages with various functionalities which includes preprocessing and data modeling.


**Anaconda Prompt (Jupyter Notebook)**

Or the packages alongside their versions can be saved as a text file with the filename requirements.txt, and they can be installed using the command:
**!pip install -r requirements.txt**. Without explicitly defining the versions, the latest versions of the packages will be installed.

# Project Objectives
- To implement a system that monitors system activities in real-time.

- To classify activities as benign or ransomware-related 

- To automatically initiate mitigation measures upon detecting ransomware.


# Technology Stack
- Programming Language: Python

- Machine Learning Libraries: Scikit-learn, TensorFlow, Keras

- Monitoring Tools: Sysmon (System Monitor)

- Datasets: CICIDS 2017 (for training and testing)

- Development Environment: Google Colab

- Version Control: Git/GitHub


# Proposed Methodology
The proposed solution involves developing a machine learning-based system that monitors system activities in real-time using tools like Sysmon. By analyzing the data using supervised learning algorithms (Random Forest, SVM, Neural Networks), the system will classify activities as benign or ransomware-related. Upon detecting ransomware, the system will automatically initiate mitigation measures to prevent further damage.
![image](https://github.com/user-attachments/assets/3ca08e68-ef06-41f5-9d1f-8a44c32e6f6c)


# MLOPS PIPELINE 

![ML workflow1 drawio](https://github.com/user-attachments/assets/66fc173a-1fed-497f-b32a-690b76158eba)
