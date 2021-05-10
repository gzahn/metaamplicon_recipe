# Recipe for meta-amplicon analyses


## File information:

Meta-Amplicon_Recipe.Rproj	The R Project file (open with Rstudio)

README.md	This file

workflow.sh	BASH script to run all R scripts in correct order

data/	contains all raw and intermediate sequence data used in this workflow

metadata/	contains sample metadata 
	- Sample IDs
	- Island
	- Site
	- Lat/Lon
	- Host ID
	- Status (healthy or impacted)
	- Associated file names

output/	contains intermediate files and figures

scripts/	contains all R scripts for conducting analyses

taxnomy/	contains RDP training database for assigning taxonomy to reads
