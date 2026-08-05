# NPF
Minimal implementation to reproduce the main results presented in  https://doi.org/10.48550/arXiv.2512.07842
## Requirements
- See `requirements.txt`
## Data 
- Imaging data used in this work have been deposited in the Donders Repository https://doi.org/10.34973/2w2s-tg07
- NPF.ipynp contains a section 'LFP' that describe the structure of the data and how to transform it. This section can be ignored if you are running the notebook for synthetic observations.
**Note:** Numba functions are compiled on first use. Run a small test example (small number of particles and few observations) before the main experiments to avoid compilation overhead during the full execution.
