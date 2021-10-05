# Readme

#### ABOUT:  Data from the Costs of Climate Change series is available through GitHub. This data has been developed through analyses led by the Canadian Institute for Climate Choices. 

https://climatechoices.ca/reports/under-water/
https://climatechoices.ca/reports/the-health-costs-of-climate-change/

Please cite this data as: Clark, Dylan G., Ryan Ness, Dena Coffman, Julien Bourque, and Dale Beugin. 2021. 'Costs of Climate Change Web-Portal'. Canadian Institute for Climate Choices.
This document provides description of the following files:
 - CostCCPTData
 - CriticalInfFloodRisk
 - FederalPropertyFloodAnalysis
 - FloodingCSDdata
 - HealthREsultsByProvince
 - HistoricCNDInfrastructureInvestment

For additional details about the methodologies used to model climate impacts and costs, see the technical reports for the Costs of Climate Change Series available at climatechoices.ca

Any questions not covered in this document or the technical reports may be directed to Dylan Clark, dclark[at]climatechoices.ca

#### CostCCPTData.csv document OVERVIEW

This document provides model results from the Costs of Climate Change Series. Data on infrastructure and health outcomes are included in the document. Impacts from permafrost thaw and shifts in winter road seasons are not included as these data will be released in 2022.

## Adaptation variable: 'No adaptation' scenarios are available for each impact area. 'No adaptation' scenarios may include some reactive responses, but do not include foresight about future risks. 'Proactive adaptation' and 'Highly proactive adaptation' are available for many of the impact areas - see the technical reports for more details about the assumptions for these scenarios.
## Outcome variable: These include the sector, infrastructure area, or health threat analyzed.
## GCM variable: The analysis used 7 GCMs for most impact models. Data for each GCM is generally available for each Outcome and Unit, however some impacts (like coastal flooding) used a 5%, mean, and 95% sea level rise distribution of a larger ensemble. For coastal flooding only ensemble data is available. For other impact areas, results were aggregated into ensemble high, mean, and low, in these cases GCM level data is not included.
## RCP variable: RCP4.5 (of CMIP5) and RCP8.5 were used for the analysis. RCP4.5 is referred to as 'Low-emissions' and RCP8.5 is referred to as 'High-emissions'
## yr variable: Most impact models were run annually. Data was then aggregated into 30 year averages. Some impact model outcomes were aggregated into 10-year averages. The Yr category is a continuous variable that allows users to graph and analyse data no matter the aggregation bins.
## Era variable: This is a categorical variable that only uses 30 year time horizons
## Level variable: Indicates if the data is at a provincial/territorial scale 'PT' or a national level
## Province and ID: PT name or Canada as well as a unique identifier.
## Avg: If the GCM is an ensemble, this is the mean of all GCMs. If the GCM is a unique model (not ensemble) this is the raw value. All dollars are 2019 Canadian dollars.
## Low: If the GCM is an ensemble, this is the low of all GCMs. If the GCM is a unique model (not ensemble) this is the raw value. All dollars are 2019 Canadian dollars.
## High: If the GCM is an ensemble, this is the high of all GCMs. If the GCM is a unique model (not ensemble) this is the raw value. All dollars are 2019 Canadian dollars.


#### CriticalInfCloodRisk.csv document OVERVIEW

The Canadian Institute for Climate Choices purchased data licenses from LightBox (DMTI spatial data) and from JBA Risk (flood data) for the Costs of Climate Change series. The DMTI spatial data includes geospatial layers of health facilities, airports, police station, fire stations, and ambulance stations.

We assessed the flood risk of these critical infrastructure by overlaying JBA return period data and flood defense data (presence of flood protections). This file summarizes results for each province and territory. Note that this data should not be used for emergency planning or facility-level critical infrastructure decision making, it is intended to serve as a high-level analysis of risks.

##Region variable: province or territory 
##Critical_inf_type variable: highest order category of critical infrastructure types analyzed (Airport, Police, Fire, HCR [health care resource], Ambulance)
##Sub_type variable: second order category of critical infrastructure types.
##Total properties variable: The total count of each group for each region
##Return period variables: The total number of facilities defended by flood protections, in a 20, 100, 200, and 500 year floodplain respectively. Return period data is historical and not scaled to future climates. Return periods include fluvial, pluvial, and coastal flooding.


#### FederalPropertyFloodAnalysis.csv document OVERVIEW

We obtained data about federal buildings from the Treasury Board Secretariat open data portal: https://open.canada.ca/data/en/dataset/08013e71-101a-457c-af76-c7b13a08ff64

The Canadian Institute for Climate Choices purchased data licenses JBA Risk (flood data) for the Costs of Climate Change series. We assessed the flood risk of these federal properties by overlaying JBA return period data and flood defense data (presence of flood protections). This file summarizes results for each Government of Canada department/agency.

##Total properties variable: The total count of each group for each department or agency
##Return period variables: The total number of facilities defended by flood protections, in a 20, 100, 200, and 500 year floodplain respectively. Return period data is historical and not scaled to future climates. Return periods include fluvial, pluvial, and coastal flooding.


#### FloodingCSDdata.csv document OVERVIEW

This data is from the Costs of Climate Change series inland flooding and coastal flooding analyses. For methodology details see the technical report available at climatechoices.ca

Information about each variable in this document can be found in the "readMe_floodCSDdata.csv" document.


#### HistoricCDNInfrastructureInvestment.csv document OVERVIEW
Data for this table is pulled from a few Statistics Canada open data tables. We have used these sources to create a timeseries of infrastructure investment from 1955 to 2019 that is standardized to 2019 Canadian dollars.

Original data sources:
- Flows and stocks of fixed non-residential capital, by North American Industry Classification System (NAICS) and asset, Canada, provinces and territories (1953-2013) - Table: 36-10-0236-01 (formerly CANSIM 031-0002)
- Flows and stocks of fixed non-residential and residential capital, by sector and asset, provincial and territorial (2009-2021) - Table: 34-10-0163-01 (formerly CANSIM 031-0009)
- Gross domestic product at factor cost, by industry, 1926 to 1976 (concluded) - https://www150.statcan.gc.ca/n1/pub/11-516-x/sectionf/4057751-eng.htm#1
- Gross domestic product (GDP), expenditure-based, annual, 1961 - 2011 - Table: 36-10-0255-01 (formerly CANSIM 380-0017)
- Gross domestic product, expenditure-based, provincial and territorial, annual (1981 - 2019) - Table: 36-10-0222-01 (formerly CANSIM 384-0038)
