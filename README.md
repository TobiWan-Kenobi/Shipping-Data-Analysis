# Analysis of CO2 Emmissions of container Ships in 2019

The provided data contains i) hourly data of 100 container ships in 2019 including position (latitude & longitude), speed and CO2 emissions; and ii) locations (latitude & longitude) of ports worldwide.

### WORK IN PROGRESS

So far, this has been an exploratoy data analysis (EDA). Planned next steps in the analysis:
- Building a log of journeys from the hourly log. This will allow to analyse
  - which routes are being penetrated the most
  - on which routes most CO2 emissions occur
- I found that different ships have different relationships of speed and CO2 emissions. In any case, though, the relationship is exponential, meaning there is a CO2-optimal speed. Based on this insight, I want to estimate the relationship between speed and CO2 emissions per ship, compute the CO2-optimal speed of a ship and compare it against the actual speed ships are going
