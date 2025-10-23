# Combined use of eDNA metabarcoding and visual surveys to monitor climate change indicator species

*Simons D-L, Hipperson H, Webb TJ, Spencer M, Mieszkowska N*

This GitHub repository contains data and R code for reproducing analyses presented in Simons et al 2026, "Combined use of eDNA metabarcoding and visual surveys to monitor climate change indicator species". If you reuse any scripts or data in this project, please cite the paper (when released). 

> **Abstract:** Visual surveys are valuable for tracking long-term distributional range shifts of climate change indicator species, but logistical barriers reduce the ability of such surveys to obtain unbiased and reproducible ecological data. Environmental DNA (eDNA) can improve the efficiency of coastal monitoring, but its concordance with visual surveys in the intertidal has not been previously investigated. The performance of eDNA metabarcoding was compared with paired visual surveys in detecting 87 climate change indicator species, as well as other taxa across relevant groups, along the UK coastline. Overall, 60 of the 87 species were detected by visual surveys, of which 41 were identified at the species level by eDNA, with one target invasive species detected exclusively through eDNA. At the species level, eDNA detected lower richness estimates than visual surveys for the target taxa due to false negatives and misidentifications. Improved species-level detections using eDNA probably require more representative sequences in reference databases to better identify species with high intraspecific genetic variation, more specific primers, and a greater site-level sampling effort. However, eDNA performed better than visual surveys for 12 target taxa that were inconspicuous and typically inhabit the low shore or sublittoral. Additional invertebrate and macroalga taxa were revealed by eDNA that were not monitored by visual surveys, suggesting that eDNA is better suited for broader scale and exploratory monitoring than for searches of specific species. The relative read abundance for species with shifting range edges did not accurately match visual abundance estimates, however, general trends of higher visual abundance did lead to higher proportions of reads. This work suggests that a combined approach of molecular and visual methods will offer a more comprehensive assessment of coastal biodiversity. The benefits and costs of each survey method should be considered to address the monitoring goal most efficiently. Future work could focus on a multi-data approach in combination with occupancy modelling tools to better account for imperfect detection.

## Repository Structure
-   `Figures/`: Stores all figures produced from the analyses.
-   `Input_Data/`: Contains raw data files used for analyse, including metadata, phyloseq object and long data.
-   `Processed_Data/`: Stores processed data files used for analyses.
-   `intertidal-eDNA-comparison-analyses.Rproj`: RStudio project file to manage the project environment.
-   `intertidal-eDNA-comparison-analysess.qmd`: Quarto file containing the analysis code and documentation.
-   `intertidal-eDNA-comparison-analyses.html`: HTML output generated from the Quarto file, providing a rendered version of the analysis. This file can be download and viewed as a standard guide.

## How to run
1. Clone the repository to your local machine.
2. Open the RStudio project file (intertidal-eDNA-comparison-analyses.Rproj) to set up the project environment.
3. Run the Quarto file (intertidal-eDNA-comparison-analyses.qmd) to reproduce the analyses and generate the figures.

Alternatively, readers can download intertidal-eDNA-comparison-analyses.html and open in any browser to view the full output of analysis without needing to rerun. 

## Contact
For questions or suggestions, please contact Dina-Leigh Simons at dinathebiologist@gmail.com.
