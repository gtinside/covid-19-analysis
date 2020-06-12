#### COVID-19 Analysis

These notebooks will work only on the databricks platform. I wanted to used Apache Spark on Kaggle but couldn't downgrade the JAVA version on the notebook VM as required by Spark 2.x version

##### Analysis
<hr/>

The notebook retrieves data from the following APIs :
1. [COVID-19 Public API](https://corona-api.com/)
2. [Alpha-3 country codes](https://gist.githubusercontent.com/tadast/8827699/raw/3cd639fa34eec5067080a61c69e3ae25e3076abb/countries_codes_and_coordinates.csv)

Both datasets are registered as tables and then analyzed. The notebook reflects on three important metrics

1. Countries with worst recovery rates
2. Countries with best recovery rates
3. Most affected countries based on deaths per million

##### Deployment
To deploy the notebook, you will have to register for Databricks Community Notebook platform. After the registration you will be able to import the notebooks from this repository 