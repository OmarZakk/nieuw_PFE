#  What is this project?
This project aims to show how the COVID-19 pandemic affected the household saving rates across EU member states, and to see what role inflation played in that.
# How to run it?
This project mainly uses R, so to run the project import it into RStudio, and the project should be able to run. If there is a version mismatch, renv::restore() could be used to recreate the environment used for this project.
# Where we collected our data and how to collect it
The main datasets used for this project are run through the R plugin eurostat. If one wants to download the datasets used, links and data settings are available below:

https://ec.europa.eu/eurostat/databrowser/view/NASA_10_KI__custom_21822977/default/table
**Settings**
- Row: All European Union member states seperately selected (deselect EU27_2020, IS, NO, CH, RS ![UK], ![EA_19])
- Column: Select 2016 to 2022
- National accounts indicator ([na_item]): Open panel and make sure only [SRG_S14_S15] is selected
- Sector: [S14_S15]

https://ec.europa.eu/eurostat/databrowser/view/prc_hicp_ainr/default/table?lang=en
**Settings**
- Row: All European Union member states seperately selected (deselect EU27_2020, EA, EA21, EA20, EA19, EEA, IS, NO, CH, UK, MK, GE, AL, RS, TR, XK, US)
- Column: Select 2016 to 2022
- Unit of Measure: [RCH_A_AVG]
