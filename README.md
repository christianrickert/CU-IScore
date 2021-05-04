![header](https://user-images.githubusercontent.com/19319377/116955473-e20f9d00-ac4f-11eb-91fc-56399caedeb4.png)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4599591.svg)](https://doi.org/10.5281/zenodo.4599591)
# CU-IScore
## ImageJ2 macro for the IHC scoring of multi-channel images

![histo](https://user-images.githubusercontent.com/19319377/116958138-d4114a80-ac56-11eb-896b-89e4d8bb0a12.png)
**Figure 1: Histogram example.** Distribution of pixel counts as a function of the pixel values from the grayscale image (top). The histogram is partitioned into four equally-sized intervals for the I-Score calculation. From left to right: Pixels with values below a certain threshold are disregarded as background (white peak, left). Pixels within the valid value range contribute to the I-Score (black distribution, center) weighted by three pixel intensity categories. In addition, Pixels with values above a certain threshold can be disregarded as outliers (white line, right).

### Software documentation
The documentation of our macros is located in the corresponding source code: You can view the source code on GitHub by following the links to the macros.

### Software requirements
* ImageJ2 macros require a recent version of the [Fiji](https://fiji.sc/) image processing package.
