# DynamicDPI
Reconstructing video of quickly evolving sources, with uncertainty quantification, using Deep Probabilistic Imaging (DPI) in a message passing protocol on a probabilstic graphical model of the hidden images. Case studies include VLBI and Dynamic MRI.

## Run Examples
TODO
  
## Requirements
General requirements for PyTorch release:
* [pytorch](https://pytorch.org/)
* [torchkbnufft](https://pypi.org/project/torchkbnufft/)

For radio interferometric imaging:
* [eht-imaging](https://pypi.org/project/ehtim/)
* [astropy](https://pypi.org/project/astropy/)
* [pyNFFT](https://pypi.org/project/pyNFFT/)

Please check ```DPI.yml``` for the detailed Anaconda environment information. TensorFlow release is coming soon!

## Citations

DPI
```
@inproceedings{sun2021deep,
    author = {He Sun and Katherine L. Bouman},
    title = {Deep Probabilistic Imaging: Uncertainty Quantification and Multi-modal Solution Characterization for Computational Imaging},
    booktitle = {AAAI Conference on Artificial Intelligence (AAAI)},
    year = {2021},
}
```

StarWarps
```
K. L. Bouman et al., "Reconstructing Video of Time-Varying Sources From Radio Interferometric Measurements," in IEEE Transactions on Computational Imaging, vol. 4, no. 4, pp. 512-527, Dec. 2018, doi: 10.1109/TCI.2018.2838452.
```
