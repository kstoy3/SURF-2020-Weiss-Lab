# SURF-2020-Weiss-Lab

Characterization of Human Genome Regulatory Regions using Convolutional Neural Networks.

## Motivation
To speed up the trial and error process of research by providing a system that can test for epigenetic failures from the DNA sequence before DNA is even inserted into the host organisim. 

## Most up to date information
- The master branch contains papers about this project and the most up to date model
- The working branch will contain code snippets and occassional unfinished models being updated

## Downloads
1. 
File: E003_25_imputed12marks_hg38lift_mnemonics.bed.gz	30-Mar-2018 22:12	4.2M	 
From: https://egg2.wustl.edu/roadmap/data/byFileType/chromhmmSegmentations/ChmmModels/imputed12marks/jointModel/final/

2. 
You can access the hg38 genome sequence through the UCSC genome browser here:
(Only need to download chr1-22 and chrX as that is what is used in ChromHMM on imputed data)
https://hgdownload.soe.ucsc.edu/goldenPath/hg38/chromosomes/  

3. 
The files in the github so you can run the scripts to create the data and run it on the models. 
Typically run in Anaconda on Jupyter Lab.

## Abstract
The Human Genome Project has led to the sequencing of 94% percent of human DNA1. However, there are still parts of the genome that have not been fully annotated. A recent multivariate Hidden Markov Model, chromHMM, has annotated 25 different chromatin states (each representing a genomic element such as a promoter or heterochromatin). They used epigenetic marks – such as ChIP-seq data of histone modifications. We used these labeled regions of chromatin states as input for a Convolutional Neural Network (CNN) model that we created for further categorizing regions of the human genome. We specifically chose to work with epigenome E003, which is the H1 cell line, due to it being a frequently used human Embryonic Stem Cell (hESC) line. The model is currently predicting with a 79.35% percent accuracy. By working on this new CNN, we anticipate finding new regulatory regions that could aid in synthetic biology genetic circuit development, which could then be experimentally verified. 

## Usage

- First, run the files to annotate the sequences from the hg38 using the chromHMM annotations
- Next, run a file to prepare a data set
- Lastly, run a Model file that corresponds to the same number as one of the data sets 

## Contributing
- Please reach out if you would like to use this code or contribute

## Credits
Primary Contributer: Kristina Stoyanova (Undergraduate at Caltech)
Mentors: Professor Ron Weiss (Ron Weiss Lab at MIT), PhD candidate Sebsastian Palacios (Weiss Lab at MIT)
Sponsors: Caltech SFP Office

