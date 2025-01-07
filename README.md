# Water-Quality-Analysis-Dashboard

**Overview**
This repository provides the resources and guidance to recreate a Tableau dashboard for analyzing water quality metrics. The dashboard visualizes relationships between water depth, temperature, dissolved oxygen, pH levels, and air temperature. The project is supported by a CSV file containing the dataset used for these visualizations.

**Features**
**1. Water Temperature vs. Water Depth**
* Explore how water temperature (°C) varies with depth (m).
* Filters applied to exclude null values ensure clean data visualization.

**2. Dissolved Oxygen vs. Water Depth**

* Examine the relationship between dissolved oxygen (mg/L) and water depth.
* Temporal trends are highlighted using year-based color coding.

**3. Air Temperature vs. Water Depth**

* Investigate the correlation between air temperature (°C) and water depth.

**4. pH Levels vs. Water Temperature**
* Analyze pH (standard units) of water temperature, with depth indicated through color encoding.

**How to Use**
**1. Download Resources**

* Clone this repository.
* Download the provided CSV file, **Water_Quality_Dataset.csv**, containing the dataset.

**2. Open in Tableau**
* Import the CSV file into Tableau Desktop or Tableau Public.
* Use the fields in the dataset to recreate the visualizations described in the Features section.

**3. Recreate the Dashboard**

* **Chart 1:** Water Temperature vs. Water Depth
  * X-axis: Water Temperature (°C)
  * Y-axis: Water Depth (m)
  *Filter: Exclude null values.
* **Chart 2:** Dissolved Oxygen vs. Water Depth
  * X-axis: Dissolved Oxygen (mg/L)
  * Y-axis: Water Depth (m)
  * Color: Year
  * Filter: Exclude null values.
* **Chart 3:** Air Temperature vs. Water Depth
  * X-axis: Air Temperature (°C)
  * Y-axis: Water Depth (m)
  * Filter: Exclude null values.
* **Chart 4:** pH Levels vs. Water Temperature
  * X-axis: Water Temperature (°C)
  * Y-axis: pH (standard units)
  * Color: Water Depth (m)
  * Filter: Exclude null values.

**4. Customize**

* Add titles, tooltips, and interactivity to enhance usability.
* Combine individual charts into a unified dashboard layout.

**Dataset**

The dataset, Water_Quality_Dataset.csv, includes the following columns:

* Water Depth (m)
* Water Temperature (°C)
* Air Temperature (°C)
* Dissolved Oxygen (mg/L)
* pH (standard units)
* Year

**Applications**
This dashboard is useful for:

* Monitoring water quality trends.
* Identifying correlations between environmental and water parameters.
* Assisting in environmental research and policymaking.

**Contribution**
If you create enhanced versions of the dashboard or have suggestions for improvement, you can just contribute by forking the repository and submitting a pull request.


**Link To Tableau Dashboard**

<a href='https://public.tableau.com/views/DAB202_Lab5_W0864162_Dhruv/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link'> Water-Analysis-Dashboard </a>

