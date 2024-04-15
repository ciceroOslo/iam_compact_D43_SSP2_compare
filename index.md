--- 
layout: default
--- 

The plots on this page compare population and GDP PPP data in the harmonized
data from D4.3 in IAM COMPACT, to the original SSP2 (2013 version), the draft
update of SSP2 published by IIASA in late July 2023 (review phase 1), and the
[final release](https://data.ece.iiasa.ac.at/ssp/) published in March 2024.


# Plots

Click the links below to access plots for each variable. On each plot, you can
select the region to plot in the pull-down menu on the top left.

Note that the 2024 release version is plotted on top of the 2023 review 1
version when they are identical. So if the 2023 review version appears to be
missing, it probably means that there was not change in the released 2024
version. You can confirm this by clicking on the 2024 line in the legend to
hide it.

Countries are sorted in alphabetical order by 3-letter ISO code (*not* country
name), while continents and other types of regions are listed at the bottom. See
"Regions" below for explanations of IAM COMPACT-specific regions.

Note that there is some variation in what countries are included in each dataset
and for what variables. For some countries you may therefore not get a complete
set of scenarios and models, or years.

The IAM COMPACT harmonized data is labeled as "M1, IAM COMPACT" in the charts.
The "M1" refers to the data used for the 1st modelling cycle (i.e., the data
specified by D4.3).

For GDP, the SSP2 data include numbers from two different models: one from the
OECD (which is usually taken as the default SSP GDP data) and one from IIASA.
The two differ markedly for several regions.

* **[Population](./ssp_pop_comparison.html):** Population of each country
* **[GDP PPP (scaled)](./ssp_gdp_scaled_comparison.html):** GDP at purchasing-power
  parity for each country. Original (2013) SSP2 numbers have been scaled to account
  for different base years (see below).
* **[GDP PPP per capita](./ssp_gdp_per_capita_comparison.html):** Equal to scaled
  GDP PPP divided by population.
  

# Notes

## GDP PPP scaling

The GDP charts are shown in 2017 international dollars, which is used by both
the IAM COMPACT and updated SSP datasets. The original SSPs used 2005
international dollars, which differs from 2017 international dollars both in
purchasing power of the US dollar (US inflation) and the purchasing-power
weighting of each country.

To adjust for the different currency units, the SSP2 GDP numbers from the OECD
model are scaled so that they match the IAM COMPACT dataset in 2005 (which is
equal to IMF data in that year). The IIASA GDP model does not provide data for
2005, so it is instead scaled to match the *scaled* OECD model numbers for 2010.


## Regions

In addition to continents, EU27, EU28, OECD and non-OECD groupings, the charts
include three IAM COMPACT-specific groupings that correspond to the different
data sources and data mergings used in the harmonized data:

* **"EU27+Norway":** Current EU countries plus Norway. These are grouped together
  because they are the ones for which the 2021 EU Ageing Report include
  projected GDP growth rates.

* **"OECD+ countries":** OECD countries plus Argentina, Brazil, China, India,
  Indonesia, Russia, Saudi Arabia and South Africa, excluding EU27+Norway. These
  are grouped together because they are included in the OECD Economic Outlook
  109 long-term baseline data, which are used for GDP projections through 2060
  for these countries.

* **"RoW excl. OECD+ and EU27+Norway":** All other countries. These countries use
  only UN data for population, and SSP2 for GDP growth rates after 2029, with no
  other specific projection sources.
