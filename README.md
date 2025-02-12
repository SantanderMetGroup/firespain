# FIRESPAIN025

Burned Area is recognized as an Essential Climate Variable by the Global Climate Observing System (GCOS), highlighting its importance in understanding and monitoring climate change impacts. FIRESPAIN-025 is a gridded daily database of burned area (BA) created on the basis of the General Forest Fire Statistics [Estadística General de Incendios Forestales, EGIF](https://www.miteco.gob.es/es/biodiversidad/temas/incendios-forestales/estadisticas-datos.html), a publicly available database that collects information on all forest fires occurring in Spain as obtained from the standardized Forest Fire Reports submitted by the Autonomous Communities every year to the Ministry for the Ecological Transition and Demographic Challenge. 

EGIF includes more than 150 data fields for each fire event. It was initiated in 1968 and it is one of the most complete international data series on forest fires, offering valuable insights into fire dynamics and impacts. However, the comprehensive nature of EGIF also needs a relational database format, which requires tailored queries to retrieve specific information, such as total BA records per reported fire event. 

To address these needs and facilitate broader use of the data, we have developed the new FIRESPAIN product that organizes the database into a standard, gridded format (netCDF) of BA. This format simplifies data access and analysis, enabling researchers and practitioners to more easily integrate the information into their workflows for further studies and applications.

This repo contains code and auxiliary materials for FIRESPAIN development. Interested data users are referred to the [latest version available in Zenodo](https://doi.org/10.5281/zenodo.14644902)


***
This research work was funded by the Ministry for the Ecological Transition and the Demographic Challenge (MITECO) and the European Commission NextGenerationEU (Regulation EU 2020/2094), through CSIC’s Interdisciplinary Thematic Platform Clima (PTI-Clima). J.B. acknowledges support from Project PROTECT (PID2023-149997OA-I00), funded by MICIU/AEI/10.13039/501100011033 UE / EDRF
