# ChIP-Seq-Otago-2017

# ETHERPAD WITH LINKS FOR THIS WORKSHOP IS HERE: 
https://beta.etherpad.org/p/H9l6EdbQfR

Analyzing ChIP-seq data - the material here is taken from https://angus.readthedocs.io/en/2017/chip-seq.html, which is based on (the material here is based on the 
ChIP‐seq Hands‐on Exercise, by Remco Loos and Myrto Kostadima at EMBL‐EBI, available here: https://www.ebi.ac.uk/training/online/course/ebi-next-generation-sequencing-practical-course/chip-seq-analysis/chip-seq-practical

The goal of the workshop is to introduce researchers to ChIP-Seq data 101 - mapping settings and calling peaks with macs2. The workshop is based on mouse data.

For this workflow, we are going to need the following tools:

1. Bowtie
2. SAMtools
3. BEDTools
4. UCSC Tools
5. MACS2
6. And for visualization, we will use ENSEMBL



# Genomics Virtual Lab via NeCTAR
We will be using an instance of Genomics Virtual Lab which will run on the University of Auckland [NeCTAR](https://nectar.org.au/labs-and-tools/) Node - supported by the [Centre for eResearch](http://www.eresearch.auckland.ac.nz/). 

* NeCTAR (National eResearch Collaboration Tools and Resources) is a federated research cloud hosted in 7 Australian institutions, and is now a pilot service at University of Auckland.
* NeCTAR provides virtual computing resources, virtual labs (such as the one used in this workshop), scientific clouds, and collaborative workflows to assist researchers.
* If you are a postgraduate or staff researcher at UoA and would like to get on board (free of charge), please contact Centre for
eResearch Staff:  nectar@auckland.ac.nz
