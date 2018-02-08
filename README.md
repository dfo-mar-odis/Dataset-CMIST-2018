Canadian Marine Invasive Screening Tool (CMIST)
===============================================

CMIST website can be viewed through the following link: [http://www.bio.gc.ca/science/monitoring-monitorage/cmist/index-en.php](http://www.bio.gc.ca/science/monitoring-monitorage/cmist/index-en.php)  
CMIST database can be queried here: [http://www.bio.gc.ca/science/monitoring-monitorage/cmist/data-donnees-en.php](http://www.bio.gc.ca/science/monitoring-monitorage/cmist/data-donnees-en.php)

Description
-----------
CMIST assessments provide information on the likelihood and impact of invasions of different species in different assessment areas with scores adjusted for assessor uncertainty. Together, these assessments act as a new resource of collated information on invasive species that can assist researchers and managers dealing with aquatic invasive species (AIS) and increase the efficiency of decision-making. The growing database of CMIST assessments is an important repository for information on invasive species for students, researchers, and citizens around the world.

Folder structure:
-----------------
*	**1-Documentation**: Store documentation regarding the project methodology here. *e.g. specific methodology, data processing steps, 
*	**2-Data**: folder to store all observation, measurement, model, and processed data.  
	*	**1-RawData**: Store the raw data files generated here (Preferably in an open format, *i.e. .txt or .csv*
	*	**2-ProcessedData**: Store cleaned, processed, and QC/QA'd data here.  
*	**3-Code**: folder for all scripts used in order to process the data. *i.e. QA/QC, data manipulation, reformatting, or deriving values* 
*	**4-Products** folder is to store all finished data products derived from the data found in the **Data** folder using the scripts in **Code** folder unless it was processed using a graphical method (not reproducible). 
	*	**1-Reports**: Store published documents/reports/papers here
	*	**2-OpenDataContent**: Content that will be published to one of the Open Data platforms goes here