# Exploration of the EDH dataset for the purpose of SNA creation and analysis

## About
This repository aims to use the existing EDH dataset to create past social networks from inscriptions as part of the Past Social Network project.

## Authors 
* Petra Hermankova [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-6349-0540), PSN, Aarhus University
* Matteo Mazzamurro [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0009-0004-4454-1551), PSN, Aarhus University
* Tom Brughmans [![](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-1589-7768), PSN, Aarhus University
* [Name], [ORCID], [Institution], 
* [Name], [ORCID], [Institution]
* [Name], [ORCID], [Institution]

## Funding
*The Past Social Networks Projects* is funded by The Carlsberg Foundation’s Young Researcher Fellowship (CF21-0382) in 2022-2026. 

## License
CC-BY-SA 4.0, see attached License.md

---

## Data
**EDH dataset**

**DATASET 2022**: `Heřmánková, Petra, & Kaše, Vojtěch. (2022). EDH_text_cleaned_2022_11_03 (v2.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.7303886 http://doi.org/10.5281/zenodo.7303886`

SCRIPTS 2022: `Heřmánková, Petra, & Kaše, Vojtěch. (2022). sdam-au/EDH_ETL: Scripts (v2.0). Zenodo. https://doi.org/10.5281/zenodo.7303867 https://doi.org/10.5281/zenodo.7303867`

_The 2022 dataset contains 81,883 cleaned and streamlined Latin inscriptions from the Epigraphic Database Heidelberg (EDH, https://edh-www.adw.uni-heidelberg.de/), aggregated on 2022/11/03, created for the purpose of a quantitative study of epigraphic trends by the Social Dynamics in the Ancient Mediterranean Project (SDAM, http://sdam.au.dk). The dataset contains 69 attributes with original and streamlined data. Compared to the 2021 dataset, there are 407 more inscriptions and 5 fewer attributes containing redundant legacy data, thus the entire dataset is approximately the same size but some of the attributes are streamlined (260 MB in 2022 compared to 234 MB in 2021). Some of the attribute were removed as they are no longer available due to the changes in the EDH itself, e.g. edh_geography_uri, external_image_uris, fotos, geography, military, social_economic_legal_history, uri; and some new attributes were added due to the streamlining of the ETL process, e.g. pleiades_id._

**DATASET 2021**: `Heřmánková, Petra, & Kaše, Vojtěch. (2021). EDH_text_cleaned_2021_01_21 (v1.0) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.4888168 http://doi.org/10.5281/zenodo.4888168`

SCRIPTS 2021: `Heřmánková, Petra, & Kaše, Vojtěch. (2021). sdam-au/EDH_ETL: Scripts (v2.0). Zenodo. https://doi.org/10.5281/zenodo.6478243 https://doi.org/10.5281/zenodo.6478243`

_The 2021 dataset contains 81,476 cleaned and streamlined Latin inscriptions from the Epigraphic Database Heidelberg (EDH, https://edh-www.adw.uni-heidelberg.de, License https://creativecommons.org/licenses/by-sa/4.0/), aggregated on 2021/01/21, created for the purpose of a quantitative study of epigraphic trends by the Social Dynamics in the Ancient Mediterranean Project (SDAM, http://sdam.au.dk)._

---

## Scripts

1. [Dataset extraction and basic exploration as HTML](https://past-networks.github.io/EDH_sna/scripts/1_EDH_data_exploration.html), [view raw code as Rmd](https://github.com/past-networks/EDH_sna/blob/master/scripts/1_EDH_data_exploration.Rmd) in GitHub
  _Purpose of this script is to create a smaller subsection of the full Epigraphic Database Heidelberg (*EDH*) dataset that can be further explored for the purpose of the SNA within the *Past Social Network Project*, Aarhus University. A basic exploration of useful attributes connected to people on inscriptions, such as gender, age, social status, is included._

## DOI
TBA

## How to cite us
TBA

---

<img src="./img/PSN_logo.png" alt="PSNP logo" style="width:300px;height:auto;" align="left">
<img src="./img/aulogo_uk_var2_blue.png" alt="Aarhus University logo" style="width:300px;auto;"align="right">
<img src="./img/Carlsbergfondet_logo_2-liner_UK_RGB_GREEN.png" alt="Carlsberg Foundation logo" style="width:300px;height:auto;"align="center" >

