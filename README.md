### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

Moreover, the easiest way how to carry on with analyzing this data without the need to set up local environment is to fork a corresponding [Kaggle kernel](https://www.kaggle.com/samusram/covid-19-person-level-drill-down-czechia-canada).

## Project Motivation<a name="motivation"></a>

There are mainly cumulative COVID-19 statistics for larger populations, e.g. country-level counts of infected people.
Being valuable, it tells us little about COVID-19 situation for an age/gender group our parents belong to, or the group of our partners, or our siblings’ age/gender.
In this project I've performed and shared a prelimenary analysis of currently available person-level information about age and gender groups in The Czech Republic.

### Goals
  * Firstly, we'll do exploratory data analysis. In the EDA the main goal would be to drill down into the persol-level details as much as possible. The detailed drill down would be illustrated on Czechia due to better data at hand.

  * Secondly, we'll target the following important question:
    **Does COVID-19 attack all age-gender groups evenly?**

  * Thirdly, we'll attempt to quantitatively compare by how much are selected age-gender groups more at risk of contracting COVID-19.

## File Descriptions <a name="files"></a>

There is 1 main notebook with its own Content enabling easier navigation between different parts of the analysis.

Data about COVID-19 patients in The Czech Republic are openly available at the Ministry of Health of the Czech Republic [webpage](https://onemocneni-aktualne.mzcr.cz/api/v1/covid-19). 
To put the COVID-19 situation into demographics context, we’ll use data from the Czech Statistical Office [website](https://www.czso.cz/csu/czso/home).
For brief comparison with population of Canada, data from [Roche UNCOVER COVID-19 Challenge](https://www.kaggle.com/roche-data-science-coalition/uncover) were used, as well as demographics data from [Statistics Canada website](https://www.statcan.gc.ca/eng/start).
[Novel Corona Virus 2019 Dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) by [SRK](https://www.kaggle.com/sudalairajkumar) was used for data quality validation.

## Results<a name="results"></a>

The main findings have been summarized in a [Medium post](https://medium.com/@raman.samusevich/covid-19-person-level-drill-down-86a14dbbd78b).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to the Ministry of Health of the Czech Republic, the Czech Statistical Office, Kaggle platform including its partners and community for the data.  
Please, feel free to use the code as you like and, if interested, to carry on with the analysis. 
