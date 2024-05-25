# GreenTeam
Big Data Analysis and Green Computing: Profiling HPC Power and Tracking CO2 Emissions. Explore the world of Big Data Analysis in the context of high-performance computing (HPC), with a specific focus on two important aspects: power profiling and tracking CO2 emissions.​

### BACKGROUND           
----
Sustainable computing is increasingly vital in our digital era, especially within HPC systems. To achieve this goal, it is crucial to utilize big data analysis of HPC monitoring data.

Open Data (M100 ExaData): 
- https://www.nature.com/articles/s41597-023-02174-3: the paper discusses the monitoring data of a large-scale data center, specifically a high-performance computing system.

Open Data (Electricity Consumption and Carbon Footprint Analysis):
- Carbon Intensity - Low Carbon Percentage - Renewable Percentage: https://www.electricitymaps.com/data-portal/italy 
- Energy source composition: [Link](https://transparency.entsoe.eu/generation/r2/actualGenerationPerProductionType/show?name=&defaultValue=false&viewType=GRAPH&areaType=BZN&atch=false&datepicker-day-offset-select-dv-date-from_input=D&dateTime.dateTime=06.03.2024+00:00%7CCET%7CDAYTIMERANGE&dateTime.endDateTime=06.03.2024+00:00%7CCET%7CDAYTIMERANGE&area.values=CTY%7C10YIT-GRTN-----B!BZN%7C10Y1001A1001A73I&productionType.values=B01&productionType.values=B02&productionType.values=B03&productionType.values=B04&productionType.values=B05&productionType.values=B06&productionType.values=B07&productionType.values=B08&productionType.values=B09&productionType.values=B10&productionType.values=B11&productionType.values=B12&productionType.values=B13&productionType.values=B14&productionType.values=B20&productionType.values=B15&productionType.values=B16&productionType.values=B17&productionType.values=B18&productionType.values=B19&dateTime.timezone=CET_CEST&dateTime.timezone_input=CET+(UTC+1)+/+CEST+(UTC+2) "Link")
- Cost of electricity data: https://ember-climate.org/data-catalogue/european-wholesale-electricity-price-data/

### STRUCTURE OF REPOSITORY     
----
- [**Report/main.pdf**](https://github.com/LSquarzoni/GreenTeam/blob/main/Report/main.pdf "**Report/main.pdf**") - report of the work done
- [**PWR_Dataset_3_years**](https://github.com/LSquarzoni/GreenTeam/blob/main/PWR_Dataset_3_years.ipynb "**PWR_Dataset_3_years**") - reading the power dataset, sampling and interpolation of the data
- [**PWR_Dataset_plotting**](https://github.com/LSquarzoni/GreenTeam/blob/main/PWR_Dataset_plotting.ipynb "**PWR_Dataset_plotting**") - visualizations of the dataset
- [**CI_Dataset_plotting**](https://github.com/LSquarzoni/GreenTeam/blob/main/CI_Dataset_plotting.ipynb "**CI_Dataset_plotting**") - reading the carbon intensity dataset, visualization and analysis
- [**CI_Prediction**](https://github.com/LSquarzoni/GreenTeam/blob/main/CI_Prediction.ipynb "**CI_Prediction**") - time series prediction of the carbon intensity
- [**Cop_Energy_Dataset**](https://github.com/LSquarzoni/GreenTeam/blob/main/Cop_Energy_Dataset.ipynb "**Cop_Energy_Dataset**") - operational carbon footprint calculations
- [**Energy_Saving_computation**](https://github.com/LSquarzoni/GreenTeam/blob/main/Energy_Saving_computation.ipynb "**Energy_Saving_computation**") - power/energy considerations and calculatons 