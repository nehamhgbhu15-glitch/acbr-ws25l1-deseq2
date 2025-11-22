# Create Conda Environment with minconds
I am creating a conda environment for DESeq2 data analysis
with R and Biocondctor in my windows system using Windows
Subsystem Linux (WSL)

## Code in WSL terminal
- Start the WSL in Windows
Type the following to create a conda environment for R4.5 named as R4.5WS
```{}
conda create --name R4.5WS
```
- Activate the r4,5WS coonda environment as follows
```{cmd}
conda activate R4.5WS
```
- Install R4.5 in the R4.5WS conda environment
```{CMD}
conda install conda-forge::r-base
```
`conda-forge` is the channel from anaconda.org. [conda-forge-channel-for-r4.5.2] (https://anaconda.org/conda-forge/r-base)