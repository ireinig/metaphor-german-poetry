# Metaphor detection for German Poetry

This repository contains the datasets POEMS and TSV described in the paper [Metaphor detection for German Poetry (2019)](https://2019.konvens.org/proceedings).
TSV is based on the English dataset of [Tsvetkov et al. (2014)](https://www.aclweb.org/anthology/P14-1024.pdf).

## Data 

The folders contain the following data:

- **poems**: POEMS dataset (train and test)
- **tsv-translated**: TSV dataset (train and test)

In both folders, the files are organized as follows:

- Training data: files starting with `train_`
- Test data: files starting with `test_`

- Metaphorical instances: files ending with `_met`
- Non-metaphorical instances: files ending with `_nonmet`
- Ambiguous instances: files ending with `_ambig` 

Each file contains one lemmatized adjective-noun pair per line.

Please note that ambiguous instances were not used in experiments.
