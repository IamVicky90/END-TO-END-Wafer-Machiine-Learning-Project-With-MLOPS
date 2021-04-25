# END-TO-END-Wafer-Machiine-Learning-Project-With-MLOPS
## This is a Wafer Fault detection ML project, it tells you whether the wafer has some problems or not.
## Table of Contents.
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Directory Tree](#directory-tree)
  * [Libraries](#libraries)
  
  ## Demo
  Deployment Link. https://wafer-fault-detection-mlops.herokuapp.com/ .
  
 
 __Frontent based on html, css.__
  
  ![error check your internet](https://github.com/IamVicky90/Health-App/blob/main/git%20images/Capture.PNG)
  
  
  __Click the images for the predictions.__
  
  ![error check your internet](https://github.com/IamVicky90/Health-App/blob/main/git%20images/1.PNG)
  
 

  
  ## Overview
I made this application to know that whether a particular Wafer has some deffect or not. If it has some defect then we can remove this so that our work runs smoothly.
## Motivation
The motivation behind this is not very interesting, I just want to work in some MLOPS/DEVOPS techniques like a realtime industry do. So i choose this project.

## Technical Aspect
This project is divided into two part:
1. Training a Machine Learning Model.
2. Building deployed, and hosting a Flask web app on Heroku( https://wafer-fault-detection-mlops.herokuapp.com/ ).

## Installation
The Code is written in Python 3.6.9. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [downloading it](https://github.com/IamVicky90/Plant-Disease-Prediction/archive/main.zip):
```bash
pip install -r requirements.txt
```
## Run
To run the app in a local machine, shoot this command in the project directory:
__Run the follwing command after installing requirements.txt__
```bash
python app.py
```
## Directory Tree 
```
├── .vscode
│   ├── settings.json
├── Model
│   ├── Chest XRay Pnemonia xception model.h5
│   ├── Heart_disease_ab_0.90_model.sav
│   ├── brest_cancer_rf_model.sav
│   ├── diabetes_xg_0.76_model.sav
│   ├── kidney_disease_ab1_model.sav
│   └── skin cancer vgg16 model.h5
├── chest_xray
│   ├── Test
    │   ├── NORMAL.
    │   ├── PNEUMONIA
│   ├── Train
    │   ├── NORMAL.
    │   ├── PNEUMONIA
│   ├── Val
    │   ├── NORMAL.
    │   ├── PNEUMONIA
├── git images
│   ├── 2.PNG
│   ├── capture.PNG

├── .ipynb notebooks
│   ├── Breast Cancer.ipynb
│   ├── Chest XRay Pnemonia.ipynb
│   ├── Heart Disease.ipynb
│   ├── Kidney Disease.ipynb
│   ├── Real_skin_cancer.ipynb
│   └── diabetes.ipynb

├── skin cancer dl
│   ├── Test
    │   ├── benign
    │   ├── malignant
│   ├── Train
    │   ├── benign
    │   ├── malignant

├── static
│   ├── css
│   ├── Images
│   ├── js

├── templates
│   ├── base.html
│   ├── breast.html
│   ├── diabtes.html
│   ├── heart.html
│   ├── index.html
│   ├── kidney.html
│   ├── pnemonia.html
│   ├── skin.html
│   ├── skin_base.html


├── Breast_cancer_data.csv
├── app.py
├── cancer desc.txt
├── diabetes.csv
├── heart.csv
├── kidney disease desc.txt
├── kidney_disease.csv 
├── README.md
├── requirements.txt
```
## Libraries
also mentioned in [requirements.txt](https://github.com/IamVicky90/END-TO-END-Wafer-Machiine-Learning-Project-With-MLOPS/blob/main/requirements.txt)
```
APScheduler==3.7.0
argon2-cffi==20.1.0
async-generator==1.10
attrs==20.3.0
backcall==0.2.0
bleach==3.3.0
certifi==2020.12.5
cffi==1.14.5
click==7.1.2
colorhash==1.0.3
configparser==5.0.2
cycler==0.10.0
decorator==5.0.5
defusedxml==0.7.1
entrypoints==0.3
Flask==1.1.2
Flask-Cors==3.0.10
Flask-MonitoringDashboard==3.1.0
greenlet==1.0.0
imbalanced-learn==0.8.0
imblearn==0.0
importlib-metadata==3.10.0
ipykernel==5.5.3
ipython==7.16.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
itsdangerous==1.1.0
jedi==0.17.2
Jinja2==2.11.1
joblib==1.0.1
jsonschema==3.2.0
jupyter==1.0.0
jupyter-client==6.1.13
jupyter-console==6.4.0
jupyter-core==4.7.1
jupyterlab-pygments==0.1.2
jupyterlab-widgets==1.0.0
kiwisolver==1.3.1
kneed==0.7.0
MarkupSafe==1.1.1
matplotlib==3.3.4
mistune==0.8.4
nbclient==0.5.3
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.3.0
numpy==1.19.5
packaging==20.9
pandas==1.1.5
pandocfilters==1.4.3
parso==0.7.1
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
prometheus-client==0.10.0
prompt-toolkit==3.0.18
psutil==5.8.0
# ptyprocess==0.7.0
gunicorn
pycparser==2.20
Pygments==2.8.1
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
pytz==2021.1
pyzmq==22.0.3
qtconsole==5.0.3
QtPy==1.9.0
scikit-learn==0.24.1
scipy==1.5.4
seaborn==0.11.1
Send2Trash==1.5.0
six==1.15.0
sklearn==0.0
SQLAlchemy==1.4.6
terminado==0.9.4
testpath==0.4.4
threadpoolctl==2.1.0
tornado==6.1
traitlets==4.3.3
typing-extensions==3.7.4.3
tzlocal==2.1
wcwidth==0.2.5
webencodings==0.5.1
Werkzeug==1.0.1
widgetsnbextension==3.5.1
xgboost==1.4.1
zipp==3.4.1
```

