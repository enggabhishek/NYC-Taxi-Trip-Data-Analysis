# NYC-Taxi-Trip-Data-Analysis
<p>In order to proceed further in this project first download the following python libraries:
<ol>
  <li>PySpark</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>NumPy</li>
  <li>Scikit-learn</li>
  <li>Seaborn</li>
</ol>
</p>
<p> Download all the necessary <a href = 'https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page'>files</a> required for this project:
<ol>
  <li><b>fhvhv_tripdata_2023-02.parquet</b>: This dataset contains information about taxi trips, including details about the driver, trip duration, fares, pickup and dropoff locations, and various flags indicating trip characteristics like shared rides or accessibility features. </li>
  <li><b>taxi+_zone_lookup.csv</b>: It is a reference dataset that provides information about the different taxi zones within a particular area in New York.</li>
  <li><b>final_df.csv</b>: This dataset include all the necessary information which has been derived from 'fhvhv_tripdata_2023-02.parquet' file which is being used to create predictive model.</li>
</ol>
</p>

#### 1. DataCleaning_&_EDA.ipynb: 
<p>
This file involves two main processes: Data Cleaning and Exploratory Data Analysis (EDA). Data Cleaning includes tasks like handling missing values, ensuring data integrity, detecting and addressing outliers, standardizing data formats, and transforming data into a more suitable format for analysis. On the other hand, EDA entails summarizing key statistics, visualizing data patterns and relationships through graphs, analyzing feature correlations, examining variable distributions, and segmenting data for deeper insights.
</p>

##### Dashboard 1
![image](https://github.com/enggabhishek/NYC-Taxi-Trip-Data-Analysis/assets/29338852/6305139c-27ea-49ce-98c5-435d027bcedc)

##### Dashboard 2
![image](https://github.com/enggabhishek/NYC-Taxi-Trip-Data-Analysis/assets/29338852/da3fe337-79d5-4b25-a59f-ca8acc184917)

### 2. PredictiveModel.ipynb: 
<p>
This file includes predictive models to predict Taxi fares using trip distance, PULocationID, DOLocationID, Weekday number and Pickup Hour as the feature elements.
</p>

### 3. Final_Workbook.twb
<p> 
  It contains interactive dashboards showcasing high-tip zones, fee-generating zones, and surcharge-trip duration using Tableau application.
</p>
