Mercury Benchmarking Script 

This directory contains a set of python scripts used to benchmark used to benchmark new and updated versions of the GEOS-Chem 
mercury model. The primary script used is a Jupyter Notebook named Mercury Benchmark; this will call all other necessary routines.

Also included are various data to which the model versions are compared found in the folder data. 

The Benchmarks aim is to compare and analyse data from a new model run to a reference model run. For this you will need the
bpch files generated by the model run and their associated tracer and diag info. You will need to specify the location of these 
along with their tracer and diag info (preferably put into the directory folder i.e. pythonHgBenchmark). 

Summary of scripts and their function:

GeneralGraph : Plot the mean over time for any chosen variable at the surface level for both the reference and new models. 
Latitudinal_Graphs : Plot observations against the model for different latitudes.
MeanSurfaceTGM :  Plot the mean surface TGM for mercury for both the reference and new models. 
PlotSeasonSites : Plot the reference and new models against the observations made at each site for a year. 
SiteLevels : Dictionary of all of the sites with different levels other than 0 at the surface.
TGMAndObs : Plot the mean surface TGM for mercury against different sites for the reference and new models.

