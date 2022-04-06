# Supervised machine learning techniques analysis for intrusion detection in edge computing-enabled WSN
Wireless Sensor Networks (WSN) are low-cost, low-consumption devices with the ability to obtain information, process it locally, and communicate through wireless links to a central node. Integrating WSNs with the Internet of Things (IoT) and Edge/Fog Computing creates a sustainable sensing, monitoring, and industrial manufacturing ecosystem. Unfortunately, these ecosystems are attractive surfaces for security intrusions, vulnerable to multiple and simultaneous attacks due to their singular characteristics: lack of infrastructure, limited computing resources, and restricted security systems.
This research evaluates the performance of an Intrusion Detection System (IDS) configured with supervised Machine Learning (ML) algorithms such as Extra Trees, Random Forest, Decision Tree, among others, in an edge computing-enabled WSN. Edge computing-enabled WSN allows to reduce latency and bandwidth usage, and optimize computation capabilities. The results show that some supervised ML algorithms, i.e., Extra Trees, Random Forest, and Decision Tree, generate predictions with up to 100% of accuracy when trained and predicted with specific intrusions  (e.g., ICMP echo request Flood, SYN Flooding faster, and ARP spoofing), both of binary form (intrusion and no-intrusion) as multi-class form (five different intrusions and no-intrusion). In contrast, up to 82.16% of accuracy is achieved, making predictions about other five intrusions not used in the training process (i.e., UDP port scan, DDoS MAC Flood, Brute Force SSH, TCP Null, and IP Fragmentation).

## Citing

If you use our project for your research or if you find this paper and repository helpful, please consider citing the work.

## Folders

- **Data** This folder contain the datasets.
- **Notebook** In this folder, you will find all algorithms and implementations for the different scenarios. 

## Requirements
This repository requires the following libraries:

- NumPy
- Pandas
- string
- Seaborn
- openpyxl
- scikit-learn
- keras-gpu
- scikit-image
- NLTK
- spaCy
- imbalanced-learn
- Matplotlib
- Yellowbrick
- Time
- OpenCV
- Pydot
- Graphviz
- dtreeviz
- Statsmodels
- XGBoost

This repository was developed in the Python 3 (3.8) programming language.

## Package installation

If you don't use google colab, We highly recommend to use and install Python packages within an Anaconda environment. To create, execute the command below:
```
conda update -n base -c defaults conda
```
```
conda create --name NID python=3.8
```
```
pip install notebook
```
So, activate it:
```
conda activate NID
```
Packages installation
```
pip install ipykernel
```
and display of environment in jupyter
```
python -m ipykernel install --user --name NID --display-name "NID"
```
Now, install the libraries
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c districtdatalabs yellowbrick
```
```
conda install -c conda-forge imbalanced-learn
```
```
pip install imblearn
```
```
conda install -c anaconda scikit-learn
```
```
pip install scikit-image
```
```
pip install anaconda keras-gpu
```
```
pip install opencv-python
```
```
pip install pandas
```
```
pip install pydot
```
```
conda install -c conda-forge spacy
```
```
conda install openpyxl
```
```
pip install graphviz
```
```
pip install dtreeviz
```
```
pip install statsmodels
```
```
pip install xgboost
```

## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Supervised-Machine-Learning-for-Intrusion-Detection.git
```
If you will use colab, upload the cloned folder to drive, then open the folder and run the notebook.

If you are going to use your computer, install:
```
conda install jupyter 
```
Enter the cloned folder, then enter the folder and run the notebook.

