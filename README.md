<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>

# Influenza Season in the U.S.
### By Neena Tilton

<p align="center">
  <img width="500" height="330" src="Images/influenza.jpg"/>
</p>

### Background
A medical staffing agency needs to proactively plan for sending temporary medical workers to clinics and hospitals across the U.S. for the upcoming influenza season. To achieve this, an analysis determining influenza trends and the count of vulnerable populations for each state much be performed. 

### Tools & Context
- **Excel:** the bulk of the analysis was performed on this spreadsheet software, including data integration, cleaning, and transformation using pivot tables, along with hypothesis testing and statistical analysis using Analysis ToolPak (an Excel add-in for statistical functions). 
- **Tableau:** all of the visualizations and the final presentation for this project were created within this visualization software, including temporal forecasting, geospatial visualization, treemaps, and final dashboard. 

### Data Source
Although this is a fictional medical staffing agency, the data sets obtained for this project were from real and publicly-available government sources. 
- [Influenza deaths by geography, time, age, and gender – CDC](https://github.com/tiltonneena/InfluenzaSeason-Project/blob/main/Datasets/CDC_InfluenzaDeaths.xlsx) 
- [Population data by Geography – U.S. Census Bureau](https://github.com/tiltonneena/InfluenzaSeason-Project/blob/main/Datasets/USCensus_PopulationData.xlsx)
- [Vaccination data by State - CDC](https://github.com/tiltonneena/InfluenzaSeason-Project/blob/main/Datasets/CDC_StateFluVaxData.csv)

### Methodology
1.	Before any analysis, an initial project management plan was drafted for the purpose of stakeholder communication. The project management plan included meeting schedules, milestones, and a final deliverables proposal outlining the project plan.   

    <p align="center">
      <img width="469" height="356" src="Images/PrjMgmt.jpg"/>
    </p>
    <p align="center">
      <em>A section from the project management plan highlighting<br>the projected schedule for completing this project.</em>
    </p>

2.	Once the plan was drafted, analysis began with finding data sets that were publicly available and vetting them for data integrity. Beyond them being from credible government sources, other data integrity factors were taken into consideration, such as the relevancy of the data, potential biases, data limitations, timeliness, and any other issues related to the data collection process.

    <p align="center">
      <img width="300" height="80" src="Images/UScensuslogo.jpg"/>
    </p>
   
    <p align="center">
      <img width="282" height="156" src="Images/CDClogo.jpg"/>
    </p>

3.	After the process of vetting the reliability of data sets, the three selected data sets were cleaned, formatted to be consistent with one another, and fully integrated into one large data set.  

    <p align="center">
      <img width="514" height="134" src="Images/exl_integration.jpg"/>
    </p>

4.	Statistical analysis and hypothesis testing was performed on the sample data to find if there were any differences between vaccinated and unvaccinated groups. This was followed by an interim report for stakeholders. 

    <p align="center">
      <img width="404" height="183" src="Images/tTest.jpg"/>
    </p>
    <p align="center">
      <em>The two-sample t-test found that the death rates due to influenza in states with vaccination<br>rates below 35% was higher than the states with vaccination rates above 35%. </em>
    </p>
    
    <p align="center">
      <img width="469" height="592" src="Images/interimreport.jpg"/>
    </p>
    <p align="center">
      <em>The interim report included a descriptive analysis of the data set, the results of hypothesis testing,<br>and further plans for the remainder of the analysis.</em>
    </p>

5.	Data visualizations were created in Tableau to complete the rest of the analysis. 

    <p align="center">
      <img width="350" height="320" src="Images/histogram.jpg"/>
    </p>
    <p align="center">
      <em>A box plot made in Tableau shows the distribution of influenza deaths<br>within different age groups.</em>
    </p>
    
    <p align="center">
      <img width="490" height="300" src="Images/map.jpg"/>
    </p>
    <p align="center">
      <em>A combination choropleth and graduated symbol map made in Tableau shows<br>the size of vulnerable populations (blue circles) within each state overlaid<br>on the count of influenza deaths (yellow to red gradient).</em>
    </p>
    
6.	Final report was created in a dashboard format within Tableau. The final presentation for stakeholders was performed in a recorded video format. 

### Key Findings
- Hypothesis testing showed that higher vaccination rates do decrease the average number of influenza
deaths. However, real impact only started to show when state rates reached 38% or higher. 
- Higher concentration of vulnerable populations had a much clearer impact on total death count than vaccination rates. Therefore, prioritizing states with higher vulnerable populations was recommended for future staffing needs.
- The states with the highest concentration of vulnerable populations are California, Florida, Texas, and New York. These states should be prioritized when sending medical staff for the season. 

### Deliverables
### [Interim Report](https://github.com/tiltonneena/InfluenzaSeason-Project/blob/main/InterimReport.pdf)

<p align="center">
  <img width="300" height="210" src="Images/stackpaper.jpg"/>
 </p>

### [Tableau Dashboard](https://public.tableau.com/app/profile/neena1744/viz/InfluenzaWorkbookII/InfluenzaMedicalPlanningStory)

<p align="center">
  <img width="300" height="250" src="Images/dashboard.jpg"/>
 </p>
    
### [Video Presentation](https://vimeo.com/652267376)

<p align="center">
  <img width="300" height="250" src="Images/vimeo.jpg"/>
</p>

### Next Steps
This analysis did not cover the seasonality of the influenza virus for each state. Next steps will take this into consideration to draft the most optimal scheduling for sending temporary medical workers to each state.  

<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>
