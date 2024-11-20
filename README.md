# DS4002 Project 3 - Facial Mask Image Recognition

## Team Mango:
* Rithwik Raman (xak7jw)
* Pranav Arora (aub5uy)
* Ayush Acharya (htb4hv)

## Description
### This repository contains our project's datasets, scripts, and generated visualizations. The project uses facial image data of individuals either with or without masks and uses image recognition models to detect whether an individual is wearing a mask. 


## Software and Platform
* Development was performed in a Python-based Jupyter Notebook.
* The following Python packages were imported:
  * Pandas
  * Matplotlib
  * Seaborn
  * NumPy
  * Scikit-learn
  * TensorFlow
  * Keras
  * ZipFile
  * Image
  * IO
  * TQDM
* Scripts were run on the Rivanna HPC Environment platform through UVA (as it took too long to run in the Google Colab Runtime Environment Platform).

## Map of Documentation
### DS4002-Project3
* DATA
  * Dataset_Retrieval
  * Data Appendix.pdf
* OUTPUT
  * Class Distribution Histogram.png
  * Confusion Matrix.png
  * Dataset Information.png
  * Image Width and Height Distributions.png
  * Metrics Results Table.png
  * Sample Dataset.png
* SCRIPTS
  * DS4002_Project3_Final.ipynb
* LICENSE
* README.md

## Reproducing these Results
* Either upload the DS4002_Project3_Final.ipynb file to a Rivanna Cluster with GPU power (around 2-3 cores, 16 GB RAM, and 2-3 GPUs) or Google Colab's Runtime Environment.
* Run the entire Jupyter Notebook (script file) and view the results (note that the image size histogram generation and neural net model training may take longer).
