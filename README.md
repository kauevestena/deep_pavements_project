# Deep Pavements Project

![Alt text](logo.jpg) [1]

## About 

Deep Pavements is a framework to leverage open-source tools to produce data about pathway pavements using CC-compatible street-level Imagery. 
As a project highlight, the pavement classes are compliant with the OpenStreetMap [surface=*](https://wiki.openstreetmap.org/wiki/Key:surface) tag values. 

The main products that are meant to be created are with the provided tools are:

- I Regionally optimized Deep Learning models to do segmentation of road pavements and objects that may interfere with them.
- Datasets to train semantic segmentation models.
- A surface-patch dataset to train image classification models.

## Modules

The modules that made up the project are each one in a separate repository:

- [Sample Picker](https://github.com/kauevestena/deep_pavements_sample_picker): to generate samples from randomly selected images from Mapillary.
- [Sample Labeler](https://github.com/kauevestena/deep_pavements_labeler): To manually check the samples.
- [Surface Patch Dataset](https://github.com/kauevestena/deep_pavements_dataset): A manually curated dataset of surface patches.
- [Model Trainer](https://github.com/kauevestena/deep_pavements_trainer): To train semantic segmentation models.

A module "Data Processer" is also planned. This module will be used to generate the surface patches for an specified location.

### References:
[1] : The logo was produced using Microsoft Copilot, we plan to replace it with in the future with a CC one.
