
  

# The Autoencoder

  

## Overview

The Autoencoder is a tool designed for various machine learning and data processing tasks such as dimensionality reduction and feature extraction. It uses a neural network model to achieve efficient encoding and decoding of data.

  

This script specifically handles neural network models for computational chemistry or pharmacology, enabling:

1. Loading and displaying configurations of pre-saved models.

2. Training models with detailed verbosity.

3. Visualizing training outcomes through accuracy and loss metrics.

4. Saving the modified models post-training.

5. Generating and analyzing molecular structures (noted in commented sections of the script).

6. Creating additional visualizations for molecular and chemical properties.

  

## Installation

  

### Prerequisites

- Anaconda or Miniconda (Recommended for managing dependencies)
- You can use also mamba (a faster and lighter version of anaconda)

### Downloading the miniforge
```bash
wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Linux-x86_64.sh"
```
### Installing it 
```bash
sh Miniforge3-Linux-x86_64.sh
# Accept the licence
# Define the pathway
# Initialise the shell by the way of installation
```

### Environment Setup

To set up the Python environment with all the necessary dependencies, follow these steps:

  

1. Clone the repository:

```bash

git clone https://gitlab.univ-nantes.fr/E235985F/internship.git

cd autoencoder

```

  

2. Create the environment from the `all.yml` file:

```bash

conda env create -f all.yml

```

  

3. Activate the environment:

```bash

conda activate all

```

  

## Usage

To run The Autoencoder, follow these steps after activating the environment:

  

```bash

python3  autoencoder.py

```

  

Replace `[Your Repository URL]`, `[Your Repository Directory]`, and `[Your Environment Name]` with the actual values relevant to your project.

## Recommendations
The autoencoder requires a fairly large RAM, so we advise you to run it on a fairly powerful PC

