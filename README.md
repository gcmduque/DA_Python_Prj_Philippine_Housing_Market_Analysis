# Philippines Housing Market Analysis with Property Finder Feature
### Overview
 <p align="justify">The project aims to give a quick overview of the current situation of the Philippine housing market as well as provide means to explore available properties in the country. The overview focused on the property prices and its relationship with their city location, cost of living, liveability score and city population to give an idea to interested buyers on where to find their ideal properties and their corresponding prices. To complete this project, I applied the standard procedures done by a DA role starting from Data Acquisition, Data Cleaning and Data Analysis using Python and MySQL for the Database handling and further Data Exploratory. I then summerize the findings, and presented the analysis and property finder feature on a dashboard via Tableau. </p>

 ### Steps
 A. Data Acquisition
 - Initial Planning
 - Data Acquisition: Kaggle - Housing Market Data
 - Data Acquisition: Data Scraping - City Data
 - Issues and Resolutions

B. Data Acquisition
- Data Cleaning: Housing Market Data (City)
- Data Cleaning: Housing Market Data (Latitude and Longitude)
- Data Cleaning: City Data
- Issues and Resolutions

 C. Data Loading using Python	
- Data Loading: Housing Market Data (City)
- Data Cleaning: City Data

 D. Data Exploratory (SQL & Python)	
 - Data Exploratory using SQL
 - Data Exploratory using Python

 E. Dashboard (Tableau)	
 - Housing Market Analysis
 - Property Finder

Click here for the [Project Documentation](https://docs.google.com/spreadsheets/d/1tmjBILrCU6O69kfs9HEHsDVPurFAVKC5_M1tB-TeHZQ/edit?usp=sharing) to see the complete details.

### Dashboard

Dashboard 1: Housing Market Analysis

![Housing Market Analysis Dashboard](https://github.com/user-attachments/assets/f3128b27-a076-48a1-9479-c47b3fd5f5bf)

Dashboard 1 Details:

- Scatter Plot: Living Cost vs, Liveability with Population
&nbsp;&nbsp;<p align="justify">I represented the relationship between the Cost of Living and Liveability by their corresponding City (circle). I also used the Rank and Population to characterized each City circle for easy distinction and additional information. In addition, I divided the chart into 4 quadrants, divided by their averages to help in understanding the relationships between the parameters.</p>

- Bar Graphs: Liveability vs. Avg. Price and Living Cost vs. Avg.Price
&nbsp;&nbsp;<p align="justify">I then relate the average property price per city against Liveability and Cost of Living. Since we proved (in Data Exploratory using Python) that price has a positive correlation with these parameters, the outcome came as expected. As both Liveability and Living Cost increase, the average price also increased which supports the idea of higher liveabity equates to higher cost of living hence high property prices.</p>

Data Exploratory using Python: Correlation Heat Map

![Correlation_Diagram](https://github.com/user-attachments/assets/f4bd23c9-384f-4108-b942-1856b47cd3a2)


- Summary List
&nbsp;&nbsp;<p align="justify">I also included the SQL query results from before in the form of a List as a summary and as a reference as well. This list will be helpful in understanding each city and their respective parameters and rankings against other cities.</p>
  

Dashboard 2: Propert Finder

![Property Finder Dashboard](https://github.com/user-attachments/assets/09e959df-cabd-4af1-8652-5d262b3f9dea)

Dashboard 2 Details:

- Map showing each property (circles)
&nbsp;&nbsp;<p align="justify">To get an overview of all the available properties in the Philippines, I used the latitude and longitude data to set the location and represented them in red circles. In addition, filters were also added (i.e. city, Price, Cost Of Living, etc.) to allow the user to filter the properties according to their needs.</p>

- Summary List
&nbsp;&nbsp;<p align="justify">The summary list below contains all the available properties per city and its' corresponding details which the user has filtered. And when selected, it will highlight the information and filter the map to show the location. Additionaly, the details will be displayed in the upper right square display.</p>

### Conclusion
<p align="justify">Cities that possessed the most favorable living conditions also requires higher living cost (1st quadrant (+,+)), however despite the cost many still choose to live here as shown by the large population count (Large circle size). Overall, majority of the cities are found in the 1st (+,+) and 4th (+,-) quadrants (Liveability > Average) which indicates that people really prioritized living condition. As many people seek these living condition, there will be high demand for properties found in these cities. And as we can see in the bar graphs, that this demand is reflected in the high property prices in these cities.</p>

<p align="justify">Lastly, since this project came with two dashboards, a person who is seeking to find their ideal home may use this analysis as a reference and can directly have an idea which properties are available by accessing the property finder feature of this dashboard.</p>

### Data Source
The Housing Market Data used here is acquired from [Kaggle](https://www.kaggle.com/datasets/klekzee/phillipines-housing-market/data) while the city information was retrived from [livingcost.org]( https://livingcost.org/cost/philippines).

### Tools
For this project, I used Python (Visual Studio Code and Google Colab) for data acquisition, cleaning, analysis and loading. I also used MySQL for database handling and exploratory data, and Tableau for dashboard making.

### Files

- Project Documentation: Contains all the steps and details done in completing the project.

- Python Codes: Contains the python code for data acquisition, processing and loading.

- SQL Query: Contains the SQL query used for data exploratory.

- Output Data: Contains the processed output data.

[[Files Link]](https://drive.google.com/drive/folders/1UlFk8EFgXzBQ3dRzseVmpGK8hiCdjKGC?usp=sharing)





