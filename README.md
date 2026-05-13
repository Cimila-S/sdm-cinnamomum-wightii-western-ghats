MaxEnt species distribution modelling for an endangered endemic plant of the Western Ghats — conducted at NRSC/ISRO, Hyderabad
# Habitat Suitability Modelling — _Cinnamomum wightii_, Western Ghats

Predicting the potential distribution of _Cinnamomum wightii_ (Wild Cinnamon), 
an Endangered endemic species of the Western Ghats, using Maximum Entropy 
modelling (MaxEnt 3.4.1).

## Affiliation
Conducted at: Forest Biodiversity & Ecology Division, National Remote Sensing 
Centre (NRSC), ISRO, Hyderabad
In collaboration with: Kerala Forest Research Institute (KFRI), Peechi
Presented at: National Seminar on Environment Education & Sustainable 
Development, Hyderabad (2nd Best Paper Award)

## Methods
- Algorithm: MaxEnt 3.4.1 (machine learning, maximum entropy)
- Occurrence data: NRSC biodiversity characterisation project databases
- Environmental predictors: 19 WorldClim bioclimatic variables (1 km resolution)
- Train/test split: 75% calibration / 25% validation, 10 bootstrap replicates
- Model validation: AUC = 0.976 (SD = 0.012) — excellent predictive accuracy

## Key findings
- Most influential variable: Mean Temperature of Coldest Quarter (46.2% contribution)
- Second: Precipitation of Driest Month (23.5%)
- Highly suitable habitats identified across Shola forest zones of Anamalai, 
  Palani, and Nilgiris
- Outputs directly applicable to ecological restoration targeting and 
  long-term conservation planning under climate change scenarios

## Habitat Suitability Map
<img width="227" height="380" alt="Habitat suitability map for Cinnamomum wightii" src="https://github.com/user-attachments/assets/a72829b5-c24d-497d-8e6e-07515933aae1" />
Warmer colours indicate higher predicted suitability. AUC = 0.976.

## Tools used
MaxEnt 3.4.1 · ArcGIS (ArcMap 10.4.1) · WorldClim · NRSC biodiversity databases

## Files
presentation/ — Cimila-SDM-Cinnamomum.pptx
