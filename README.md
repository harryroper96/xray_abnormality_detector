# Detecting Pulmonary Abnormalities in Chest X-Rays
Convolutional Neural Networks (CNNs) for Image Recognition.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Interpretation and Discussion of Results](#results)
5. [Acknowledgements](#acknowledgements)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python version 3.

## Project Motivation<a name="motivation"></a>

The motivation behind undertaking this project was to explore the possibility of building Convolutional Neural Network (CNN) models for image recognition within the field of computer-aided medical diagnosis.

Despite the relative accessibility of X-ray machines, medical expertise in the area of radiology required to make diagnoses is scarce: particularly in developing nations.

Implementing AI solutions in this field and thereby reducing the reliance on human intervention could facilitate a crucial stage in development.

## File Descriptions <a name="files"></a>

This repository contains the notebook in which the code for the project was written, including the data preprocessing, exploratory analysis, and modelling, and a separate folder in which the visualisations are stored.

Since the training data set was too large to practically upload, the notebook uses the Kaggle API to access the files. Running the code will download and unzip the files locally (requiring ~9GB of internal storage space).

Please note that using the Kaggle API requires the setup of an authentication token, which can be done by following the instructions linked [here](https://www.kaggle.com/docs/api).

Alternatively, those who wish to run the code without using the API can simply comment out the second code cell, download the data set directly from the Kaggle page linked in the acknowledgements section, and rename the zip file `pulmonary-chest-xray-abnormalities.zip`.

## Interpretation and Discussion of Results <a name="results"></a>

A detailed discussion of the motivation, methodology, and results of the project can be found in the Medium post linked [here](https://towardsdatascience.com/detecting-pulmonary-abnormalities-in-chest-x-rays-47f3bf2a8499).

## Acknowledgements <a name="acknowledgements"></a>

K Scott Mader Pulmonary Chest X-Ray Abnormalities https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities

Jaeger S, Candemir S, Antani S, Wáng YX, Lu PX, Thoma G. Two public chest X-ray datasets for computer-aided screening of pulmonary diseases. Quant Imaging Med Surg. 2014;4(6):475–477. doi:10.3978/j.issn.2223–4292.2014.11.20

Jaeger S, Karargyris A, Candemir S, Folio L, Siegelman J, Callaghan F, Xue Z, Palaniappan K, Singh RK, Antani S, Thoma G, Wang YX, Lu PX, McDonald CJ. Automatic tuberculosis screening using chest radiographs. IEEE Trans Med Imaging. 2014 Feb;33(2):233–45. doi: 10.1109/TMI.2013.2284099. PMID: 24108713

Candemir S, Jaeger S, Palaniappan K, Musco JP, Singh RK, Xue Z, Karargyris A, Antani S, Thoma G, McDonald CJ. Lung segmentation in chest radiographs using anatomical atlases with nonrigid registration. IEEE Trans Med Imaging. 2014 Feb;33(2):577–90. doi: 10.1109/TMI.2013.2290491. PMID: 24239990
