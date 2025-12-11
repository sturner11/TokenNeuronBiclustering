# Emergent Token–Neuron Circuits in GPT-2


## Intro
This repo houses the code for creating neuron-token biclusters in GPT-2.
It consists of the jupyter notebook, the requirements.txt, and a poster overview of the results.

Current configuration is built for running in colab with a GPU (cpu will take too long on the larger models)

For configuration inspect the notebook configuration cell where model, dataset, and bicluster sizes are set.

Also, please note running will result in a large amount of output including the tokenized dataset, saved models, 
and bicluster mappings

## Running
In it's current state, the notebook is ready to run with the addition of a HF_token to your google drive. Instructions
for obtaining a token can be found [here](https://huggingface.co/docs/huggingface_hub/v0.23.0/en/quick-start)

Once this happens, simply run the notebook after choosing an appropriate GPU. I would recommend saving the files to drive
with the current cells.

The notebook will run to completetion automatically with the except of 3 areas 1) on connecting to google drive, it
will ask you to authenticate with your google account 2) it will ask to get access to you HF_token 3 

Note:it will take a while to run the full notebook.

## Results
[![Poster Preview](poster_preview.png)](AdditionalFiles/EmergentTokenNeuronCircuits.pdf)
The full poster is available [here](AdditionalFiles/EmergentTokenNeuronCircuits.pdf)