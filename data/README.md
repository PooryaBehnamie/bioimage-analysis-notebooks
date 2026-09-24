# Example data

| File | Description |
|---|---|
| `fish_rgb.tif` | RGB display composite of a metaphase FISH spread (NCI-H2170 cells). DAPI is rendered gray (equal in R, G and B), the ERBB2/HER2 probe red, the MYC probe green. |
| `fish_dapi.tif` | DAPI channel, cropped by an expert to the metaphase spread (pixels outside the region of interest are 0). |
| `fish_mia_mask.tif` | Binary mask of ecDNA spots predicted by MIA (Microscopy Image Analyzer, a U-Net-based tool). This is a model output, **not** ground truth. |

**Source.** These images are the tutorial example distributed with the Brunk Lab's
[ecEnhance](https://github.com/Brunk-Lab/ecEnhance) repository
(`1_tutorial/Output/1a_Original RGB Image.tif`, `1b_DAPI Image.tif`, `1c_MIA Predicted Mask.tif`),
released under the MIT License (copy in `LICENSE-ecEnhance.txt`).
Pixel values are unchanged; the files were only re-saved with lossless zlib compression to reduce their size.

Related publication: Goble, K. et al. (2025). Leveraging AI to automate detection and quantification of
extrachromosomal DNA to decode drug responses. *Frontiers in Pharmacology* 15:1516621.
https://doi.org/10.3389/fphar.2024.1516621
