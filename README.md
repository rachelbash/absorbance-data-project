# absorbance-data-project
This repository will hold all things relevant to my final project in my Environmental Data Analytics class, ENVIRON 872L. The project will focus on UV absorbance characteristics in northern lakes.

The following was pulled from the original READ_ME file for NTL_LTER Lake datasets, prepared by Kateri Salk. 

# NTL-LTER Lake - Carbon Dataset


## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019

The dataset contains data from studies on several lakes in the North Temperate Lakes District in Wisconsin, USA. Data were collected as part of the Long Term Ecological Research station established by the National Science Foundation.

## Database Information
Data were collected from the North Temperate Lakes Long Term Ecological Research website. More information can be found here: https://lter.limnology.wisc.edu/about/overview

Data were collected using the Data tool (https://lter.limnology.wisc.edu/data).
From the Data homepage, the following selections were made: 
* Cascade (NTL Categories)
* Cascade Project at North Temperate Lakes LTER Core Data Carbon 1984 - 2016

csv file was saved as `NTL-LTER_Lake_Carbon_Raw.csv`.

Data were accessed 2018-12-06.

## Data Content Information
From the NTL-LTER site: 
### Carbon
Data on dissolved organic and inorganic carbon, particulate organic matter, partial pressure of CO2 and absorbance at 440nm. Samples were collected with a Van Dorn sampler. Organic carbon and absorbance samples were collected from the epilimnion, metalimnion, and hypolimnion. Inorganic samples were collected at depths corresponding to 100%, 50%, 25%, 10%, 5%, and 1% of surface irradiance, as well as one sample from the hypolimnion. Samples for the partial pressure of CO2 were collected from two meters above the lake surface (air) and just below the lake surface (water). Sampling frequency: varies; number of sites: 14

Detailed field and laboratory protocols can be found in the Cascade Methods Manual, found here: https://cascade.limnology.wisc.edu/public/public_files/methods/CascadeMa...
POC, PON and DOC: 1. 100 - 300 ml (Typically ~200mL for PML, 150 metalimnion and 75 – 100 for the hypolimnion) of lake water from each depth was filtered through 153 um mesh to remove large zooplankton. Water was then filtered through a precombusted 25mm GF/F filter (0.7 um pore size) at less than 200 mm Hg pressure. Filters were placed in drying oven at 60 C to dry for at least 48 hours. 20mL of filtered water was stored in a scintillation vial and acidified with 200uL of 2N H2SO4 for DOC analysis. Blank samples for POC and DOC were prepared with deionized water to control for contamination. All samples were sent to the Cary Institute of Ecosystem Studies for analysis.

Absorbance: 60ml of water was filtered through a 25mm GF/F filter and refrigerated until it was able to be run. Samples were warmed up to room temperature and run on a spectrophotometer in a 10cm glass cuvette. The spectrophotometer was set to 440nm and blanked with deionized water. The cuvette was rinsed once with sample water and then filled and absorbance was measured.

DIC: Water was sampled with a van dorn and taken back to the lab. 10 mL subsamples were taken with syringes and 200 uL of 2N H2SO4 and 20 mL of helium gas were added to the syringe. Syringes were shaken for one minute and 10 mL of the helium headspace was injected into a Gas Chromatograph with Thermal Conductivity Detector to determine DIC concentration.

PCO2: Air PCO2 was measured by filling a syringe with air from two meters above the lake surface and running though the GC. Water PCO2 was measured by filling a two liter bottle with lake surface water and replacing 60 mL of water with atmospheric air for headspace. The bottle was shaken for 100 seconds and two subsamples of the headspace were taken and run though a GC in the lab.


## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)
