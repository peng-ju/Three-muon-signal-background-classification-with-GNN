# Three-muon-signal-background-classification-with-GNN

The aim of this project is to distinguish the signal from background for the three-moun experient. For this purpose, we build a GNN (graph neural network) based classifier with a recall rate of 0.92.

The physics process is explained in the following figure:

Incident muon collides with W and produce S particle. S particle decays into two muons. Totally, three muons are produced in this process. 

The true signal will have three close hits on the detector plus background noise. 

<img src="/image/experiment.png" alt="drawing" width="500"/>

The experiment system is explained in 'https://en.wikipedia.org/wiki/Fermilab_E-906/SeaQuest'


# Root2PKL

Root2PKL imports the original dataset and extraccts select features for training the GNN classification model.

# DATA_ANALYSIS

DATA_ANALYSIS analyses and visualizes the the dataset. 
