# Decision Analytics based Network Design for a Clothing Business Supply Chain
A project based on a case study on optimization methods to evaluate whether to construct or extend existing distribution centres to sustain growth of a clothing brand. The project was done as a part of the course on Decision Analytics for the Masters in Data Sciences and Business Analytics at ESSEC Business School and CentraleSupélec, Paris.

# Introduction
Initially called Zorba (after the classic 1964 movie Zorba the Greek), the Spanish Clothing Company ZARA was founded in 1975 by Amancio Ortega and Rosalía Mera. The first shop was located in A Coruña, in Galicia, Spain, where the company is still based. After a successful decade, the company was expanded and several shops were opened outside of Spain, starting in Portugal, and shortly after in the United States and France. During the 1990s, the expansion reached Mexico, Greece, Belgium, Sweden and Israel, and in the following decades the company was expanded to every continent of the world. Currently ZARA has over 2000 stores distributed along more than 95 countries. Annual sales for 2019 were estimated by Forbes to be US$ 21.9 billion1.

# Context
The distribution of products to the stores is performed through logistic platforms called “Distribution Centres” (DC). Having as many stores as possible close to an DC is a target of the logistic network. ZARA has currently multiple DCs in the European region. The current issue is that many DCs are operating at full capacity and the main response to that problem is to expand the network capacity.

In this case study, we considered a reduced DC network limited to a part of Southern Europe composed of France, Italy, Switzerland, Spain and Portugal.
There are currently 6 DCs in this region: Madrid (Spain), Montélimar, Orléans, Châlon-sur-Saône and Lille (France), and Piacenza (Italy) with various capacities.
Given market increase forecasts over the next 5 years and investment capabilities, ZARA has decided to expand its DC network in this region. 

It is possible:
- To construct new DCs, in Barcelona, Bordeaux or Rome (the capacity would be 50.000 items per year for each selected location). The construction cost of each new DC is fixed and it depends on the city in which the DC is constructed.
- And/or, to extend the capacity of existing DCs. The extension can provide between 8.000 and 13.000 extra items, with a unitary extension cost depending on the DC.

To simplify the problem, we only consider 21 aggregated stores (named after the city in which they are located), each of which is associated to an aggregated monthly demand of items. The travel times between DCs and aggregated stores, the number of items demanded monthly by each store, the DC capacities (in monthly number of items they can deliver), the DCs construction/extension costs are provided in an Excel file on the course moodle. We will assume that the travel cost per hour is 1 euro each 1000 items. We will assume that the size and weight of each item does not influence delivery times. ZARA has decided to construct or extend no more than 3 sites in the short-term, while ensuring that the monthly demand of each store is satisfied, and the monthly delivery costs do not exceed a budget of 4.500 euros.

# Deliverables
The deliverables were:

- An Executive Summary illustrated with maps showing solutions, tables, and Key Performance Indicators (KPI) other than just the costs (propose and measure relevant indicators per DC, per store, or other global indicators…), plus a summary of our What-if analysis.

- A Technical Appendix (.pdf) with (i) the two Linear Programming models for the Single-Source and Multi-Source problems. You will precisely define your decision variables and say whether these variables are binary 0-1 or continuous. You will comment each kind of constraints as well as the objective function. The Technical Appendix should also contain (ii) a critical analysis on the main limitations of the proposed models (according to your experience).

- Jupyter Notebooks files (.ipynb): one for the two problems (single-source and multi-source) and one for each solved scenario in the what-if analysis (each scenario in a different section of the notebook).

- Optimal solutions found in the different solved problems plus possible visualisations.
