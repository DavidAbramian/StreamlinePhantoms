# StreamlinePhantoms

Simulated MRI phantoms for evaluation of diffusion-informed spatial smoothing of fMRI data in white matter. These phantoms were created for the following [paper](https://doi.org/10.1016/j.neuroimage.2021.118095) (also available in [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.10.25.353920v3)):

> Abramian, D., Larsson, M., Eklund, A., Aganj, I., Westin, C.F. and Behjat, H., 2021. Diffusion-informed spatial smoothing of fMRI data in white matter using spectral graph filters. Neuroimage, p.118095.

This repostory contains two types of phantoms:
- __Circular phantoms__ contain a single circular streamline activation and are provided in 93 different spatial orientations.
- __Subject phantoms__ are based on 95 subjects from the HCP dataset, and contain 100 streamline activations produced by rasterizing real diffusion streamlines generated with [DSI Studio](http://dsi-studio.labsolver.org/).

With each phantom is also provided the corresponding white matter mask. We have also generated a set of diffusion ODFs for each phantom, covering every voxel in the mask. These are necessary to perform diffusion-informed smoothing, but are too large to upload on GitHub. They will be made available under request ([email](mailto:david.abramian@liu.se)).

For more details on the generation and usage of these phantoms, please refer to the aforementioned paper.
