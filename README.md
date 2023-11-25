# pinnate_leaf_modeling
Modeling leaflet and lobe shape within pinnate leaves
![pinnate_leaves_figure](https://github.com/DanChitwood/pinnate_leaf_modeling/assets/3772583/2ccb1af5-e429-4078-a266-c6ff08e4299f)

# Motivation
We were motivated to model lobes and leaflets within *Cannabis* leaves, so that leaves with different numbers of lobes or leaflets within a plant can be compared to each other and to discern differences between genotypes rather than the heteroblastic series. We model corresponding pseudo-landmarks for each leaflet as angle-radius coordinates relative to the petiolar junction and model angle or radius as a function of leaflet to create continuous polynomial models that bypass the problems associated with variable numbers of leaflets between leaves. 

It has been proposed that pinnate, palmate, and peltate compound leaves share a common developmental origin based on the extent of adaxial-abaxial juxtaposition that gives rises to blade outgrowth along the petiole ([Kim *et al.*, *Nature* 2003](https://www.nature.com/articles/nature01820)). Others have proposed methods to automatically isolate individual leaflets ([Failmezger *et al.*, *Plant Methods* 2018](https://doi.org/10.1186/s13007-018-0290-y) or to model developmental trajectories, such as heteroblastic series ([Biot *et al.*, *Development* 2016](https://doi.org/10.1242/dev.134619). Here, we seek to build on these works, but instead 
