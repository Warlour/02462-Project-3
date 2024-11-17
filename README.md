# 02462-Project-3

## Setup
0a. Installer [conda](https://docs.anaconda.com/miniconda/#latest-miniconda-installer-links).

0b. `conda init` (First-time setup efter ny conda installation, genåbn din terminal. *Behøves ikke hvis der står `(base)` i starten af din terminal*)

1. `conda create -n "02462"` (Kald den hvad du vil)

2. `conda activate 02462`

3. `conda install python=3.11`

4. `pip install -r requirements/requirements.txt -r requirements/mac.txt`

5. Hvis du har CUDA-understøttet GPU, skal du installere torch via følgende formula: [pytorch.org](https://pytorch.org/get-started/locally/)