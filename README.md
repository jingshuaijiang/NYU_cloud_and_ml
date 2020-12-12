# NYU_cloud_and_ml

This is the final project In class cloud and machine leanring for jingshuai jiang(jj2903) and Sushanth Samala(ss12852).


This project contains code for google landmark recognition. We have run efficientnet, resnet50, vgg16, InceptionV3 and our enhanced inception model InceptionV100 and InceptionV200. Codes for these models have been indicated by their names.


The deployment code is in Deployment folder, which contains the model pth file, the index to label text file, the main.py inference service file,the dockerfile, and a kubernetes YAML file.

In order to deploy a service please use:
kuberctl create -f deploy.yaml
