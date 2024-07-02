# Image Reconstruction

# Comaprison b/w Patch and Subset removed and reconstructed using Factorization

## $(30 \times 30)$ patch missing

## $\text{RMSE} = 0.07127 | \text{PSNR} = 22.941448$

![1](./Q5aMedia/1.png)

![2](./Q5aMedia/2.png)

![3](./Q5aMedia/3.png)

### Removed Patch Image

![patchrestruct](./Q5aMedia/EmptyPatch.png)

### Reconstructed using Matrix Factorization

![res](./Q5aMedia/Patch30x30.png)

## $900$ points $(30 \times 30)$ missing

## $RMSE = 0.021735 | PSNR = 33.25666$

![ed](./Q5aMedia/4.png)

## Empty Subset

![ex](./Q5aMedia/EmptySubset.png)

### Reconstructed using Factorization

![ex1](./Q5aMedia/Subset30x30.png)

## $RMSE_{subset} < RMSE_{patch}$ and $PNSR_{subset} > PSNR_{patch}$

### Thus removing the same number of points from a well distributed region does better reconstruction than removing the points from a localised region.

# Comaprison b/w Patch and Subset removed and reconstructed using RFF

## $(30 \times 30)$ Patch Missing

## $RMSE = 0.093466 | PSNR = 20.58686$

![ex](./Q5aMedia/5.png)

### Reconstructed Image using RFF

![ex](./Q5aMedia/ReconstructPatch.png)

## $900$ points $(30 \times 30)$ missing

## $RMSE = 0.023188 | PSNR = 32.69445$

![ex](./Q5aMedia/6.png)

### Reconstructed Image using RFF

![ex](./Q5aMedia/ReconstructSubset.png)

## $RMSE_{subset} < RMSE_{patch}$

## $PNSR_{subset} > PSNR_{patch}$

## ALSO

## $RMSE^{RFF}_{subset} < RMSE^{wh}_{subset}$

### Hence RFF does better reconstruction as compared to Matrix Factorization in the case of Subset Removal and in general, the reconstruction for subset removal is better than patch removal since points in the input space are sparsely missing, hence interpolation would be able to approximate well for the removed points as compared to an entire subset of the input space missing and the function basically giving a high biased prediction for the patch of missing points
