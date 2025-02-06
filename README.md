# <h1 align='center'> **Henry DataPT11 - Individual Project 02** </h1>
# <h1 align="center">**Telecommunications**</h1>

### Table of Contents
1. [Description](#description)
2. [Requirements](#requirements)
3. [Project Structure](#project-structure)
4. [Data and Sources](#data-and-sources)
5. [Methodology](#methodology)
6. [Insights](#insights)
7. [Conclusions](#conclusions)
8. [Recommendations](#recommendations)
9. [Proposed KPIs](#proposed-kpis)
10. [Autor](#autor)

### Description
This project aims to conduct a comprehensive analysis of the behavior of the telecommunications sector at the national and provincial level in Argentina, in order to guide the company to identify trends and growth opportunities in the supply of Internet access to the population. Through the analysis of the available data, insights will be generated from which conclusions and recommendations will be drawn to capitalize on the opportunities found.

### Requirements
- Python 3.7 or latest
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Project Structure
- [`EDA.ipynb`](EDA.ipynb): Exploratory Data Analysis.
- [`HenryPI02.pbix`](Dashboards/HenryPI02.pbix) : Client's Dashboard.
- [`README.md`](README.md): Project Summary.

### Data and Sources
- Source: Data is from the website of the National Communications Agency (ENACOM in Spanish) of Argentina. ENACOM is the telecommunications regulatory body in Argentina, responsible for the regulation and control of communications services in the country.
- Data: [Datasets](https://indicadores.enacom.gob.ar/datos-abiertos)

### Methodology
The datasets were reviewed, searching for null, erroneous, missing, and duplicate values. Error correction and value imputation. Line plots were used to observe the behavior of the variables over time and heat maps were used to observe the correlation between the different attributes.

### Insights
- The number of landlines accesses and ADSL internet connections decreases over time.
- The number of cable modem internet accesses (same infrastructure as cable TV) tends to increase over time.
- Fiber-optic shows exponential growth in all provinces from the range of years between 2019-2022.

### Conclusions
- Landlines and, therefore, ADSL are technologies that are being discarded by Argentine consumers.
- The demand for internet via cable modem is growing, regardless of the performance of its infrastructure partner: cable TV.
- Fiber-optic providers were the most benefited from the consequences of the pandemic.

### Recommendations
- Do not invest in ADSL or landline infrastructure, as these technologies are becoming obsolete and the public is aware of this.
- Invest in other Internet access technologies, especially cable modem and fiber-optic.

### Proposed KPIs
1. Increase by 1% the proportion of cablemodem Internet access coverage in relation to the total number of cable TV accesses, per province, over the next quarter.
2. Increase by 5% the total number of Internet accesses through fiber-optic, per province, over the next quarter.
3. Increase by 2% the number of Internet accesses for every 100 homes, per province, over the next quarter.

### Autor
Samuel Antonio Rangel - Contact: [LinkedIn](https://www.linkedin.com/in/samuel-antonio-rangel-sar021/)