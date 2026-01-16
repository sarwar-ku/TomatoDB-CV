# Tomato-Dataset_UAV

#To download data follow any of the followings

#1: Paste this snippet into a notebook from our model library to download and unzip your dataset:

!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="uLZ3TATjrSEyoUMbVzVk")
project = rf.workspace("pa-iwi1f").project("tomato-dataset-0qmvl")
version = project.version(2)
dataset = version.download("coco")

#2: Use this code to download and unzip your dataset via the command line on any *nix machine:

curl -L "https://universe.roboflow.com/ds/fOsTXolSlI?key=B2n36gvGuE" > roboflow.zip; unzip roboflow.zip; rm roboflow.zip

#2. The direct link to download the zip file
https://universe.roboflow.com/ds/fOsTXolSlI?key=B2n36gvGuE


