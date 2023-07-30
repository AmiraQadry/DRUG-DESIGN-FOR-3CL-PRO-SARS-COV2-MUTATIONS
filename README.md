# DRUG-DESIGN-FOR-3CL-PRO-SARS-COV2-MUTATIONS

A recently identified coronavirus strain (SARS-CoV-2), a class of virus known to cause respiratory infections in people, is the source of the contagious disease known as COVID-19. Prior to December 2019, when a pneumonia outbreak with an unknown cause appeared in Wuhan, China, this new strain was unknown.

Since the outbreak, scientists have cooperated and been closely working to stop the disease's spread and to suggest potential treatment plans. Algorithms that have recently been developed in machine intelligence are capable of discovering significant patterns from vast amounts of data and are beginning to perform some tasks at an expert level. Anyone who possesses these models can therefore contribute to the global research effort.

This project uses many ideas and implementations developed by others, and bring them together towards a common task.

The aim of this project is to find drug candidates (ligand) with a high binding affinity with the COVID-19 main protease using deep learning.

1. Outline of the problem and introduction

2. Dataset preparation

3. Generate SMILES strings

Use VAE and WGAN models, generating molecules that are structurally similar to potential protease inhibitors of COVID-19.

## Requirements
This model is built using Python, and utilizes the following packages:

- Numpy
- RDKit
- Pandas
- Tensorflow
- Matplotlib

## Dataset Preparation
The data set we used had not existed before and we prepared it using some bio servers like I-Tasser, HDock, Ligann, and programms like Discovery Studio Biovia and Auto Dock.

## Final Results
![Generated Molecules From WGAN model](https://github.com/AmiraQadry/DRUG-DESIGN-FOR-3CL-PRO-SARS-COV2-MUTATIONS/assets/106974489/c0b54af8-6b8e-4d8c-9859-0045c5a9736c)

![Generated Molecules From VAE model](https://github.com/AmiraQadry/DRUG-DESIGN-FOR-3CL-PRO-SARS-COV2-MUTATIONS/assets/106974489/f4c67f2f-a2fb-4dfe-9381-271bba0c21e0)

## References
![DeepChem Documentation](https://deepchem.readthedocs.io/en/latest/api_reference/models.html#basicmolganmod)
![MolGAN: An implicit generative model for small molecular graphs](https://arxiv.org/abs/1805.11973)
![Drug development](https://en.wikipedia.org/wiki/Drug_development)
![WGAN-GP with R-GCN for the generation of small molecular graphs](https://keras.io/examples/generative/wgan-graphs/)
