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
<hr/>
To deploy the notebook, you will have to register for Databricks Community Notebook platform. After the registration you will be able to import the notebooks from this repository

##### Output
<hr/>

![](/docs/assets/images/worst_recovery.png) 

![](/docs/assets/images/best_recovery.png)

![](/docs/assets/images/worst_affected.png)


##### Live View
<hr/>

I have published this notebook on the [databricks platform](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/4934413682525655/2276315590266907/36285253315984/latest.html) and it will be active for next 6 months