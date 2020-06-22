# Physician-Prescribing-Patterns

Currently a work in progress. Expected completion June 25th.

For my project, I am exploring why North Dakota has higher use of antipsychotic drugs. I was alerted to this by Probuclica's exploration of Medicare prescriber data (see here: https://projects.propublica.org/checkup/). I decided to explore further into the North Dakota's use of antipsychotics. Specifically, what providers types are prescribing them and are there hospitals that are linked?

To answer this, I used the following 2 datasets:
  CMS Medicare Provider Utilization and Payment Data 
  CMS Physician Data 
 
Assumptions:
Antipsychotics list from CMS "Drug Category Lists" (link below)
Limitations of Medicare data


Python  
read in prescriber data, selected and renamed columns to reflect the following :   <list used columns>
read in physician data, selected and renamed columns to reflect the following :   <list used columns>
merged dataframes on npi
created new dataframe with only rows for North Dakota
queried dataframe using list of most common antipsychotics




Links:
Medicare Provider Utilization and Payment Data: 2017 Part D Prescriber (https://data.cms.gov/Medicare-Part-D/Medicare-Provider-Utilization-and-Payment-Data-201/77gb-8z53)
Physician Data (https://data.medicare.gov/Physician-Compare/Physician-Compare-National-Downloadable-File/mj5m-pzi6)
Drug Category List:  https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/PartD_Prescriber_PUF_NPI_Drug_Category_Lists_17.zip