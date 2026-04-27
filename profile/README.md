# Hi! This is the ElectrGrid Capstone Project - MEDS 2026 ⚡️
## Power lines and people: Mapping how distribution grid constraints shape resilient and equitable energy transition

## Project summary

Distributed energy resources (DER) are small-scale energy generation and storage technologies, such as rooftop solar or electric vehicles, that play a significant role in the rapid decarbonization of the energy system. The integration of DERs and the electrification of residential buildings and transportation require grid infrastructure capacity, which may be inequitably distributed across communities. There is currently no streamlined method for determining these inequities that considers both grid infrastructure and socioeconomic data. Through this project, the capstone team will create a reproducible workflow that automates the linkage between the two data sources in order to assess gaps between electrification needs and grid infrastructure hosting or load capacity. These analytical tools and data products will help utility grid planners, state energy regulators, and community advocacy groups ensure a more equitable decarbonization process.

## People
### Authors 
- [Zach Loo](https://bren.ucsb.edu/people/zach-loo)
- [Sofia Rodas](https://bren.ucsb.edu/people/sofia-rodas)
- [Sofia Sarak](https://bren.ucsb.edu/people/sofia-sarak)

### Advisor
- [Grace Wu](https://bren.ucsb.edu/people/grace-wu)  

### Client
- [Yohan Min](https://es.ucsb.edu/people/yohan-min)  

## Data
- [Microsoft/Global Building Atlas Building Footprints](https://sat-io.earthengine.app/view/gba) – Contains modeled building footprints geometries and heights for all buildings in the world.
- [California parcel geometries](https://egis-lacounty.hub.arcgis.com/documents/baaf8251bfb94d3984fb58cb5fd93258/about) – Residential parcel geometries for 51 out of 58 California countries.
- Zillow, or tax assessor data, provided directly by the client (not currently public). – Contains geographic points of residential buildings in California, and information on whether they are single- or multi- family, home value, etc. (Lots of missing data).
- [PG&E ICA data dashboard](https://grip.pge.com/)
- [SDGE ICA data dashboard](https://interconnectionmapsdge.extweb.sempra.com/)
- [SCE ICA data dashboard](https://drpep.sce.com/drpep/)
- [tidycensus package](https://cran.r-project.org/web/packages/tidycensus/index.html) – American Census Survey data for sociodemographic variables.

## More Resources
The analysis is part of a capstone project for the [Master of Environmental Data Science program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at the Bren School of Environmental Science & Management. More information on the project can be found on the [Bren website](https://bren.ucsb.edu/projects/power-lines-and-people-mapping-how-distribution-grid-constraints-shape-resilient-and).
