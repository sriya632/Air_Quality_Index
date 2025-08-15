

# Air Quality Index (AQI) 

# Snowflake + Snowpark + Streamlit

# Status: SUSPENDED (cost-safe mode)

This repo ingests AQI JSON from data.gov.in into Snowflake, then visualizes it in a Streamlit app.

Ingest: 

Python + Snowpark uploads JSON to an internal stage and (optionally) triggers a COPY INTO.


Store: 

Snowflake table RAW_AQI keeps the raw payload + metadata.

Visualize: 
Streamlit connects to Snowflake to plot KPIs, trends, and latest readings.

Live app: 
[AQI]([https://example.com](https://app.snowflake.com/cjucmjy/bu21662/#/streamlit-apps/DEV_DB.PUBLISH_SCH.G29S0NF2E6CYJCFZ?ref=snowsight_shared))
