# WaferFaultDetection
To build a classification methodology to predict the quality of wafer sensors based on the given training data. 

![alt text](https://www.rsipvision.com/wp-content/uploads/2018/08/Macro-Defects-Detection-1.jpg)

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [License](#license)
* [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project

### Problem Statement

The inputs of various sensors for different wafers have been provided. In electronics, a wafer (also called a slice or substrate) is a thin slice of semiconductor used for the fabrication of integrated circuits. The goal is to build a machine learning model which predicts whether a wafer needs to be replaced or not(i.e., whether it is working or not) based on the inputs from various sensors. There are two classes: +1 and -1. 
•	+1 means that the wafer is in a working condition and it doesn’t need to be replaced.
•	-1 means that the wafer is faulty and it needs to be replaced. 

### Architecture

![alt text](https://github.com/vandangorade/WaferFaultDetection/blob/master/wafer_proj_pipeline.jpg)

### Built With
* [python]
* [SQLite]
* [Machine learning]


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you can set up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* python
* pip
* virtualenv

```sh
pip install python==3.6

pip install virtualenv
```

### Installation

2. Clone the repo
```sh
git clone https://github.com/vandangorade/WaferFaultDetection.git
```

3. Install virtualenv and activate it from your project root.
```sh
pip install virtualenv

vitualenv venv

./venv/scripts/activate

```
4. Install requirement.txt packages
```sh
pip install requirement.txt
```

5. Run main.py file
```sh
python -u main.py
```

6. You can train and predict locally using **Postman**

### Deployment
We deploy project using **Pivotal Cloud**

API : waferquality-grateful-cassowary-ec.cfapps.io

### Documentation
Docs : https://github.com/vandangorade/WaferFaultDetection/tree/master/LLD

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

https://ieeexplore.ieee.org/document/7744687/authors#authors

https://academy.ineuron.ai/index.php

https://run.pivotal.io/

https://scikit-learn.org/stable/

https://www.python.org/

