# Projects-Portfolio
This is a portfolio I created to showcase my works in Social and Geographical data science. 

My CV can be found as pdf here: https://github.com/Nademaa/Projects-Portfolio/blob/main/CV_AdemaNurasheva2025.pdf 
 
1. Assessing public transport accessibility in Astana, Kazakhstan using PTAL methodology (https://rpubs.com/AdemaN/1285198) 

Summary: This project applied the Public Transport Accessibility Level (PTAL) methodology (originally developed by Transport for London) to assess spatial disparities in bus accessibility across Astana, Kazakhstan. The objective was to produce a citywide Accessibility Index (AI) and identify underserved areas, supporting more equitable transport planning. The final map reveals areas with lower access to public transport (blue, level 1) and areas with higher access to public transport (red, level 10). Relation of public transport accessibility to some socio-economic factors was explored as well. 

Tools: Excel, QGIS, R (ggplot2, r5r, tmap, tidyverse, sf, osmdata, etc.).

Methodology:  
-	Data cleaning using R (tidyr, dplyr, stringr) and Excel (lookups, pivot tables)
-	Routing & Accessibility Calculations: Used R (r5r package) to model walking access times and compute Scheduled and Average Waiting Times 
-	Adaptation of PTAL methodology: calculated AI for each location using walking time to nearest bus stops, service frequency, and a reliability factor.
-	Visualisations: The calculated AI values were classified into PTAL bands (Levels) using the quantile method to highlight areas with different levels of accessibility.

Key Findings:
- Central districts demonstrated high accessibility, benefiting from dense bus networks and frequent services.
- Peripheral areas, particularly on the Left Bank (in the south) of the Yesil River, showed limited connectivity.
- A visible divide in access mirrored Astana’s historical urban development.
- Population size modestly correlated with accessibility; however, income levels did not show a clear trend.
- The analysis also projected potential improvements from the future Light Rail Transit (LRT) system, especially in underserved zones.

This project gave me extensive experience in data collection, cleaning, and geospatial analysis. I manually compiled and cleaned dataset of over 8,000 observations using Excel and R, ensuring accuracy and consistency across multiple sources. I worked with several tools including R (r5r, sf, tidy verse) and QGIS, to run accessibility calculations, map outputs, and create an interactive visualisation. Adapting a London-based methodology to a new context required careful calibration and iterative testing, reinforcing my ability to apply transport models critically and accurately. Ultimately, this experience strengthened my technical proficiency, attention to detail, and ability to manage complex data workflows.

 
2. Spatial Analysis of Airbnb listings in Manchester, UK 

Summary: In this project, I have conducted spatial analysis of Airbnb listings in Greater Manchester, UK, examining their distribution, pricing patterns, and relationships with urban characteristics such as economic activity and public transport accessibility. Using advanced geocomputational and spatial statistical techniques, the study investigates how Airbnb activity reflects and interacts with the city's socio-economic and transport infrastructure.

Software and Technologies:
- GIS tools (ArcGIS/QGIS) for mapping and spatial analysis
- R and/or Python for statistical analysis and modelling

Methods & Visualisations:
-	Choropleth Mapping
-	Kernel Density Estimation (KDE)
-	Local Moran’s I (LISA)
-	Price Interpolation (IDW)
-	Geographically Weighted Regression (GWR): Explored spatial variation in the relationship between Airbnb concentration and (i) Population Density, (ii) Economic Activity, (iii) Transport Accessibility.
-	Cluster Analysis (DBSCAN)

  Key Findings:
-	High Airbnb listing density was observed in Manchester city centre, Salford, and Trafford. KDE and LISA confirmed significant clustering in these regions
-	Higher Airbnb prices were geographically concentrated in the central boroughs
-	Economic activity was positively associated with Airbnb density
-	Transport accessibility showed a strong spatial correlation in central and northeastern boroughs, suggesting Airbnb success is linked to public transport access
-	Population density showed no strong influence, indicating other urban dynamics are at play
-	Cluster analysis revealed spatial alignment between Airbnb listings and transport nodes in urban centres, highlighting the importance of transit connectivity in tourist accommodation choices
  
This project showcases my ability to combine spatial statistics, GIS visualisation, and geospatial modelling to analyse urban trends. The analysis of how Airbnb patterns intersect with transport infrastructure and economic geography offers insights directly relevant to urban planning, transport accessibility analysis, and equity in city development.


3. Assessment of Gender Correlation with Economic Inactivity in London, UK

Summary: In this project, I provided statistical and spatial assessment of economic inactivity among the working-age population (ages 16–64) across London's 32 boroughs in 2011. The aim was to examine the extent of gender disparity in economic inactivity (EI) and identify key contributing factors, by using classical inferential statistics with spatial analysis techniques

Software tool: R for all statistical tests and model construction + visualisation

Main Data Source: Annual Population Survey data (NOMIS)

Methods: 
-	Two-Sample T-Test: Tested for significant gender difference in EI rates
-	Multiple Linear Regression: Modelled impact of different reasons for inactivity on EI rates (separately for total, female, and male populations)
-	Moran’s I Statistic: Assessed spatial autocorrelation of EI across boroughs.

Key Findings:
- EI was significantly higher among women (mean 33.08%) than men (18.14%). The difference was statistically significant (p < 0.01)
- Being a student was the strongest explanatory factor across regression models.
- Models for female EI were statistically significant; male EI model showed no significant predictors, suggesting a more complex or varied set of influencing factors.
- Female EI exhibited significant spatial clustering, particularly in certain boroughs. Male EI showed no spatial dependence, indicating a more random distribution.

Some limitations of the analysis: Potential overfitting in total EI regression model; Lack of age-stratified breakdown; Male EI model's statistical insignificance.

Though focused on employment rather than transport, this project demonstrates core analytical skills essential for transport planning and equity analysis. I believe these tools are directly transferable to evaluating transport accessibility, service equity, and spatial demand modelling in urban mobility contexts.

