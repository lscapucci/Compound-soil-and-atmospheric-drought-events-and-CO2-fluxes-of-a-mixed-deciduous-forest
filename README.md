Hi, 
This repository contains all the scripts used to perform the analysis and design the figures of the manuscript "Compound soil and atmospheric drought events and CO2 fluxes of a mixed deciduous forest: Occurrence, impact, and temporal contribution of main drivers" (https://egusphere.copernicus.org/preprints/2024/egusphere-2024-459/). 
The study concerns the co-occurrence of soil and atmospheric drought (CSAD) events in a mixed deciduous forest in Swtizerland, and in particular how these events affect the CO2 fluxes at different level of the ecosystem (above the canopy, at the forest floor and at the soil level). The events taken in considarations happened in 2015, 2018 and 2022. We wanted to understand what were the main drivers of the CO2 fluxes during the CSAD years and events. To do that we used two different machine learning approaches: conditional variable importance (CVI) with random forest and and SHAP analysis based on XGB model respectively (you can find more details in the publication and in the script). These two methods were really powerful in detecting the effect of soil and atmospheric drought on the CO2 fluxes at different levels of the forest.
The scripts are available as .Rmd file in this repository with the name "Rmarkdown_CSAD.Rmd".
Data: CH_LAS... (daily mean fluxes of forest floor measurements) and CH_LAE... (daily mean fluxes of above canopy fluxes) from the forest site: https://gl.ethz.ch/infrastructure/sites/laegeren.html
If you plan to use the same approach for your analysis check the publication and don't forget to cite us.
Enjoy your coding!
