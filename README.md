# Correlation-CO2-Emissions-per-Capita-and-Human-Development

## Abstract
This study aimed to examine the correlation between CO2 emissions per capita and the Inequality-Adjusted Human Development Index (IHDI) across 154 countries, with a focus on determining whether the correlation was stronger in developing countries. The study utilized Pearson's correlation test to investigate the relationship between these variables, and the data was divided into four subsets based on the countries' development status: Very High IHDI (>= 0.80), High IHDI (0.70 to 0.79), Medium IHDI (0.55 to 0.69), and Low IHDI (< 0.50). The study found a significant positive correlation globally, with a stronger correlation in developing countries. However, a potentially negative correlation was observed in countries with very high development. These findings offer valuable insights for stakeholders working towards a sustainable future.

Checkout `paper.pdf` for full paper.

## The Data

This repository contains 6 data files in `content` folder.
1. `co2_vs_ihdi_data_compiled_final.xlsx` has all the compiled data, data subsets, codebook, sources and raw data.
2. `all_countries.csv` contains data for all countries
3. `very_high_ihdi.csv` contains data for countries with Very High IHDI
4. `high_ihdi.csv` contains data for countries with High IHDI
5. `medium_ihdi.csv` contains data for countries with Medium IHDI
6. `low_ihdi.csv` contains data for countries Low IHDI

The data was seperated into subsets to faciliate analysis. CSV Files (2) to (6) are utilized in `correlation_results_CO2_IHDI.ipynb file.` 

### Codebook 

| Variable      | Description |
| ----------- | ----------- |
| country      | country       |
| year   | year data was collected        |
| ihdi|         Human Development Index value adjusted for inequalities in the three basic dimensions of human development (scale 0-1)    |
|  development_status| Very High Human Development (≥ 0.800),High Human Development (0.700–0.799), Medium Human Development (0.550–0.699), Low Human Development (≤ 0.549)      |
|          numeric_development_status   |   1 = Very HDI (≥ 0.800), 2 = High HDI (0.700–0.799), 3 = Medium HDI (0.550–0.699), 4 = Low HDI (≤ 0.549)          |
|        global_north     |     1 = country forms part of global north, 0 = country does not form part of global north        |
| annual_co2_per_capita | Annual total production-based emissions of carbon dioxide (CO₂), excluding land-use change, measured in tonnes per person. This is based on territorial emissions, which do not account for emissions embedded in traded goods.        |

### Data Sources
| Data| Source|
|------|-----|
| Inequality-Adjusted Human Development Index (IHDI) | “Source: UNDP (United Nations Development Programme). 2022. Human Development Report 2021/2022: Uncertain Times, Unsettled Lives: Shaping our Future in a Transforming World. New York.” |
| Carbon Emissions Data | [Our World in Data](https://github.com/owid/co2-data) |

