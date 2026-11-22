# BIOSTAT721-Project-2:  Air Pollutant Analysis in RDU Airport (Jan. 2018 ~ Apr. 2020)
## Purpose:
This project processes and analyzes daily air pollutant quality (CO, O<sub>3</sub>, PM<sub>2.5</sub>) measured at the Raleigh-Durham (RDU) Airport EPA monitor from January 2018 to April 2020. These analyses provide a broader investigation of air pollution and sickle cell disease in Durham County, NC. This project summarizes annual pollutant ranges (minimum and maximum daily concentrations). It visualizes monthly trends using two plots: **(1)** pooled monthly means and 95% confidence intervals for CO and O<sub>3</sub>; **(2)** PM<sub>2.5</sub> concentrations across years. 

## Data Source:
The raw air quality datasets used in this project were collected from RDU Airport EPA monitors and processed using R programming in RStudio: 
- `AQ_2018.csv`: Air quality measurements from Jan. 2018 ~ Dec. 2018
- `AQ_2019.csv`: Air quality measurements from Jan. 2019 ~ Dec. 2019
- `AQ_2020.csv`: Air quality measurements from Jan. 2020 ~ Apr. 2020

## File Structure: 
All project files are located in the root directory of the repository:
- `AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv`: data files analyzed for this project
- `BIOSTAT721-Project-2.Rproj`: RStudio Project file that sets the working directory and standardizes workspace settings for reproducibility.
- `Emma_Kuok_ Project2.Rmd`: R Markdown script containing documentation, data-cleaning functions, data-analysis management, and code with comments for all summary tables and plots.
- `Emma_Kuok_ Project2.docx`: Final knitted Word report containing the formatted tables, visualizations, and interpretations of this project, executed by `Emma_Kuok_ Project2.Rmd`

## R Version and R-Package Versions
***These are the versions utilized for this project (11/22/2026):***
- **R Version:** 4.6.1 (2026-06-24 ucrt)
- **R-Package Versions:**
  - `dplyr`: 1.2.1
  - `flextable`: 0.10.5
  - `gt`: 1.3.0
  - `lintr`: 3.4.0
  - `lubridate`: 1.9.5
  - `purrr`: 1.2.2
  - `readr`: 2.2.0
  - `tidyverse`: 2.0.0

## Reproducing the Report:
1) **Download or Clone** the following files from the repository into the same folder:
   - ***Project File:*** `BIOSTAT721-Project-2.Rproj`
   - ***Data Files:*** `AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv` 
   - ***R Markdown Script:*** `Emma_Kuok_ Project2.Rmd`
2) **Open Project and Install Required R packages:** 
   - Double-click `BIOSTAT721-Project-2.Rproj` to open the project in RStudio (this ensures your working directory is set automatically).
   - Run the following command in the console if you have not installed these packages yet:
   ```r
      install.packages(c("dplyr", "flextable", "gt", "lintr", "lubridate", "purrr", "readr", "tidyverse"))
   ```
3) **Knitting the Report**
   - Open `Emma_Kuok_ Project2.Rmd` in RStudio
   - Click the *Knit* drop-down menu and select **Knit to Word** to run the code and generate the final Word document (`Emma_Kuok_ Project2.docx`)  

## Author and Date: 
Emma Kuok (Nov. 22, 2026)
