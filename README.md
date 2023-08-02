# A-holistic-zoo-approach-Testing-different-ABM-implementations
Repository for the publication "A holistic zoo approach - Testing different ABM implementations" published in journal XY. This repository include all data sources and model code used to generate the findings of the study. 

Additionally, it includes all supplementary material mentioned in the publication. This encompasses all interactive 3D figures of the model outputs.

The R-project "AnglerModel_NetLogo" is used to 1) prepare the raw data for GIS, 2) let the models run based on the GIS data, 3) compare the model outputs to the real-world data.

The NetLogo models in the model folder can be run directly through Netlogo. However, if you want to run the Netlogo models to conduct parameter scans or latin hypercube samples you have to use R. Probably some connections to the data sources, workspaces in R or similar are not correct anymore as they depend on how you safe each component, therefore please check before running anything.
