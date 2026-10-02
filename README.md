# ELT Pipeline for Weather Data

An PoC ELT pipeline which extract weather data from the Open-Meteo API, loads it into an Azure Datalake, where it is transformed using Databricks and PySpark. The pipeline is orchestrated to run once as day via Databricks Workflows. Using GitHub Actions, the processed data from the Azure Datalake is loaded into the repository, automatically updating a static HTML/JS frontend hosted on GitHub Pages.

You can access the site [HERE](https://kitatex.github.io/medallion-pipeline/).

The site is a data engineering PoC, and hence the analytical part is not interesting at all :(
