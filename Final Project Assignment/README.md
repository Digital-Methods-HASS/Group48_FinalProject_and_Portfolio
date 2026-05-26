# How does the shift between secular and religious state rule have an effect on civil rights and the country as a whole in Iran and Nepal
## Authors: Valdemar Peter Tjørnelund Nissen, Theis Daniel Jensen, Markus Teilmann-Jørgensen
# Iran and Nepal: Political Transition, Civil Rights and National Development

## Project Description

This project analyses how shifts between secular and religious state rule affected civil rights and broader national development in Iran and Nepal. The project compares Iran after the 1979 revolution with Nepal after the political transition around 2007. Iran is examined as a case of transition toward religious state rule, while Nepal is examined as a case of transition away from religious monarchy and toward a secular republican state.

The purpose of the project is to investigate how these political transitions influenced gendered civil rights and social conditions, as well as the countries’ development as a whole. The civil rights section focuses mainly on women and girls, using indicators such as women’s parliamentary representation, female primary school enrollment, fertility rate and adolescent fertility rate. The state and national development section focuses on indicators such as GDP, trade and military expenditure.

The project combines quantitative analysis in RStudio with historical interpretation and close reading of constitutional texts, including the Iranian Constitution of 1979 and Nepal’s Interim Constitution of 2007.

## Results

The analysis shows that the transitions in Iran and Nepal affected the two countries in different ways. In Nepal, women’s parliamentary representation increased significantly after 2007, which suggests that the transition was connected to greater formal political inclusion of women. Female primary school enrollment also increased around the transition period, although this development had already begun before 2007 through earlier education reforms.

In Iran, the results are more complex. Female primary school enrollment increased after the 1979 revolution, even though the new Islamic Republic promoted a more family-oriented and religious gender ideology. This suggests that girls’ education could expand while women’s roles were being redefined within an Islamic state framework. Fertility also declined over time, showing that religious state rule did not automatically lead to higher birth rates.

For state and national development, the analysis shows major differences between the two cases. Iran’s trade index declined sharply after the 1979 revolution, which can be connected to the country’s reorientation away from Western partners, the Iran-Iraq War and later economic disruption. Nepal’s trade index declined more temporarily and recovered, suggesting that Nepal’s transition did not create the same level of international economic rupture. GDP and military expenditure also show different post-transition patterns in the two countries.

Overall, the project finds that political transitions between secular and religious state rule affect both civil rights and national development, but not in one simple direction. The effects depend on the historical context, the type of transition and the state’s broader political and economic priorities.

## Data Sources

The quantitative part of the project is based on data from **The World Bank Open Data**. The dataset includes country-level indicators for Iran and Nepal over time. The selected indicators include:

- GDP (current US$)
- Trade (% of GDP)
- Military expenditure (current USD)
- Fertility rate, total (births per woman)
- School enrollment, primary, female (% gross)
- Proportion of seats held by women in national parliaments (%)

The qualitative part of the project uses constitutional texts and historical sources. The main constitutional sources are:

- The Constitution of the Islamic Republic of Iran, 1979
- The Interim Constitution of Nepal, 2007

Additional academic books, articles and reports are used to provide historical context and support the interpretation of the quantitative findings.

## Requirements

The project required collecting, cleaning and restructuring CSV files from The World Bank Open Data. The original datasets were transformed into tidy format, where each row represents one country, one indicator and one year.

Data analysis and visualisation were conducted in **R** and **RStudio**. The project uses the following main R packages:

- `tidyverse`
- `readr`
- `dplyr`
- `tidyr`
- `ggplot2`
- `scales`

The analysis includes:

- data cleaning
- creation of transition-year variables
- indexed graphs with pre-transition baselines
- before-and-after comparisons
- percentage-change calculations
- visualisation of selected indicators
