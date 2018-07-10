# Fault Localization using Deep Neural Networks

## Project Description

The project is based on Software Testing. In particular, the topic is Fault Localization. For a given faulty code, the general problem is finding the method or even specific lines that contains the fault. In order to build models for Fault Localization, some datasets were gathered the past few years. The most common dataset are Space, Siemens and Defects4j, which all are based on java. For the purpose of this project, Defects4j is used.


This project was done as capstone project for the Udacity Machine Learning Engineer Nanodegree. The project inclcudes a proposal, the implementation and the report. For further information such as results, further instructions and explanations please read the PDF-Documents located in the "pdf_documents" folder. Other visualizations are included in the python notebook.


## How to use

Located in this folder is an evironment.yml. This can simply be loaded as an anaconda environment and then used in jupyter as ipython notebook.

```
conda env create -f environment.yml
jupyter notebook User\_Version\_Fault\_Localization.ipynb
```

## Software

the data was originally obtained by using gzoltar <http://www.gzoltar.com/> on the defects4j dataset <https://github.com/rjust/defects4j>. The faults can be inspected in <https://github.com/Spirals-Team/defects4j-presentation-urls>. Other than that, no external software was used. (except obivous things such as: python, jupyter, anaconda)

## Libraries used

The following is simply copied from my code documentation:

| **Import Name** | **Usage** |
|:-|:-|:-|
| **Path.pathlib** | Saving, loading and checking paths |
| **random** | Generating random numbers |
| **numpy** | Math package |
| **pandas** | Used for csv file reading |
| **operator** | easy sorting by second dimension |
| **copy** | Used to copy lists |
| **sklearn** | used for agglomerative clustering and silhouette metric |
| **tensorflow** | DNN framework |
| **matplotlib** | Visualization |
