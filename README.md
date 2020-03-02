# Stock comms analyzer - Kodołamacz Data Science Bootcamp project

## Abstract
The objective of the project is to:
1. collect the so called "ESPI Reports" which are the official reports submitted by the companies listed on the Warsaw Stock Exchage (Giełda Papierów Wartościowych w Warszawie) and 
2. analyze the impact of the words used in these reports on the increase of share prices in the close time vicinity of the submitted reports.

## The project contains two jupyter notebooks:
1. **ESPI_collect** - that collects data ("ESPI Reports") from the Warsaw Stock Exchange (GPW) website: https://www.gpw.pl, stores them in html and csv format for further processing,
2. **ESPI_analyse** - that performs processing and analysis of the collected data.
3. **ESPI_analyse sample** - contains same processing as for ESPI analyse notebook, but for a limited balanced sample of 1000 items with 50% of y=1 and 50% of y=0. 

## The data used in the project includes:
1. **ESPI Reports** collected from GPW website: https://www.gpw.pl/komunikaty,
2. **GPW Stock quotes** collected from stooq website: https://static.stooq.pl/db/h/d_pl_txt.zip,
3. **Mapping table**: map_symbol-name.csv

