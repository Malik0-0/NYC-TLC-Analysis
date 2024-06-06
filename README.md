<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## Background of the NYC TLC Trip Record Dataset

**The New York City Taxi and Limousine Commission (TLC)** Trip Record dataset contains detailed information about taxi and for-hire vehicle (FHV) trips in New York City. This dataset is an essential resource for analyzing urban transportation patterns, and it includes data from yellow taxis, green taxis, and FHVs, which cover a wide range of vehicles, including traditional livery cabs, luxury cars, and high-volume for-hire services (HVFHS) like those provided by app-based platforms such as Uber and Lyft.

### **Overview of the Dataset**

The dataset includes detailed information about each trip, such as pickup and drop-off times and locations, trip distances, fare amounts, and payment types. By leveraging this dataset, analysts can make data-driven decisions to improve the efficiency and effectiveness of NYC's transportation systems.

The following are the features available:

* Trip Records:

  Each row in the dataset represents a single trip. For yellow and green taxis, the data captures the pickup and drop-off dates and times, the locations (by taxi zone), the trip distance, and the itemized fare details. For FHVs, the dataset includes similar fields but also captures the dispatching base license number.
* Data Coverage:

  The dataset is updated monthly and includes comprehensive trip records dating back several years, allowing for robust trend analysis and time series studies.
* Licensing and Management:

  The data is managed by the NYC TLC, and its use is governed by the city's terms of use policies. The data is publicly accessible, promoting transparency and enabling extensive research and policy analysis.
* Usage:

  The dataset is utilized for various purposes, including transportation planning, policy-making, economic studies, and urban mobility research. It is a valuable asset for understanding how people move around the city and for identifying trends in transportation usage.

### **Integration with Additional Data Sources**

Apart from that, there are several additional features such as the Journal Search feature using Keywords, the Journal Sorting feature by Date, the Filter feature based on a Specific Year, the Filter feature using a Specific Year Range and the Travel Summary feature.

To provide deeper insights, the dataset can be enhanced with additional data sources:

1.**NYC Taxi Zones**: This dataset maps LocationIDs to specific geographic zones within NYC. By linking trip records to these zones, you can perform spatial analyses to understand how taxi usage varies across different parts of the city. This helps in visualizing and analyzing taxi activity by neighborhood.

2.**Income Data from the U.S. Census Bureau**: The American Community Survey (ACS) provides detailed income data for various geographic areas in NYC. By combining this income data with the TLC dataset using borough and location keys, you can explore correlations between income levels and taxi usage. This can reveal patterns such as how frequently taxis are used in higher-income vs. lower-income areas, or how income levels influence the average fare paid and trip distance.

The NYC TLC Trip Record dataset, enriched with geographic and socioeconomic data, provides a comprehensive view of taxi usage patterns in New York City. By leveraging this data, stakeholders can gain valuable insights into urban mobility, economic disparities, and potential areas for service improvement, ultimately contributing to a more efficient and equitable transportation system. For more detailed trip records and related data, you can explore the TLC's data page and the U.S. Census Bureau's

NYC Government  link = https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

U.S Cencus Bureau's link = https://data.census.gov/table/ACSST1Y2022.S1901?q=income%202022&g=060XX00US3600508510,3604710022,3606144919,3608160323,3608570915

## **Business Problems** **(Fare Structure and Economic Accessibility)**

**Ensuring that taxi fare structures are affordable for passengers**

The fare structure can impact the accessibility and affordability of taxi services, especially for lower-income passengers. This involves analyzing various fare components, understanding their distribution, and identifying areas for potential adjustments to make the service more accessible.

## **Business Goals (Understanding the Impact on Accessibility)**

* **Affordability**:

  High fare amounts directly impact the affordability of taxi services. When fares are too high, low-income passengers are less likely to use taxis, thus limiting their transportation options.

  * Investigation:

    Understanding the impact of transportation costs on accessibility requires a closer look at areas where low-income residents face disproportionately high taxi fares. By analyzing fare distribution patterns across neighborhoods in each borough, we can identify areas where high fares coincide with lower median incomes. Additionally, examining fare fluctuations over time can provide insights into when residents are most burdened by transportation costs.
  * Solution:

    To address affordability challenges, we can use existing data on borough fares and income levels to inform targeted interventions. This may include implementing fare subsidy programs, optimizing public transit routes, and advocating for fare regulations in economically vulnerable areas. Collaboration between government agencies, community organizations, and transportation providers will be key to developing effective solutions that promote equitable access to transportation.

### Built With

This project was completely built using the tools:

* Python
* Pandas Library
* Seaborn Library
* Matplotlib Library

### Tableau & Installation

1. Tableau Publication
   Dashboard: https://public.tableau.com/app/profile/malik.alrasyid/viz/DashboardCapstone_17176760148040/Dashboard
   Story: https://public.tableau.com/app/profile/malik.alrasyid/viz/StoryCapstone/FairTransportationFare
2. Clone the repo
   ```sh
   git clone https://github.com/Malik0-0/NYC-TLC-Analysis.git 
   ```

## Contact

Malik Alrasyid Basori - malikalrasyidbasori.1@gmail.com

Project Link: https://github.com/Malik0-0
