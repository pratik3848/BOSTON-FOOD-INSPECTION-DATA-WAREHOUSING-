# Boston Food Inspection Data Pipeline

## Tools and Technologies used
  ### 1. Alteryx
  ### 2. Data Warehousing
  ### 3. MSSQL
  ### 4. PostgreSQL
  ### 5. Google Bigquery
  ### 6. PowerBI

This project is focused on designing a data pipeline based on Boston food inspection data. The pipeline was created using Alteryx to perform data profiling, data preparation, and designing workflows. The dimensional model was designed using facts and dimensions in MSSQL database, and the data was loaded using Alteryx. PowerBI was used to create visualizations to gain insights from the data.

## Data Source

The Boston food inspection data used in this project was obtained from the City of Boston's open data portal: [https://data.boston.gov/dataset/food-establishment-inspections](https://data.boston.gov/dataset/food-establishment-inspections). The data was downloaded as a CSV file and stored in the `data/` directory.

The data source provides information on food establishments and their inspections in the City of Boston. It includes details such as establishment name, location, inspection date, violations, and more.

For more information on the data, please visit the data source link above.

## Project Highlights

-   Accomplished data profiling, cleaning, integration using Alteryx and Google data studio on dataset with 58 million+ records
-   Constructed 15+ PowerBI dashboards to understand pattern and trends in data to get meaningful insights
-   Designing ETL workflows using Alteryx to load data into 30+ facts and dimensions

## Project Structure

-   `data/` directory: Contains the raw data files.
-   `alteryx/` directory: Contains the Alteryx workflows used to profile, prepare, and load the data.
-   `sql/` directory: Contains the SQL scripts used to create the dimensional model and load the data.
-   `powerbi/` directory: Contains the PowerBI report used to visualize the data.

## How to Use

1.  Clone the repository: `git clone https://github.com/your-username/boston-food-inspection-data-pipeline.git`
2.  Open the Alteryx workflows in the `alteryx/` directory and run them to profile, prepare, and load the data.
3.  Run the SQL scripts in the `sql/` directory to create the dimensional model and load the data.
4.  Open the PowerBI report in the `powerbi/` directory to visualize the data.

## Conclusion

This project demonstrates how to design a data pipeline using Alteryx, SQL, and PowerBI to gain insights from a large dataset.
