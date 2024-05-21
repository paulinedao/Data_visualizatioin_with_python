# Data_visualization_with_python
Hands-on exercices from IBM DV010E1N data science course


## Datasets
- *Hands-on_1 to 7: Immigration to Canada from 1980 to 2013 - International migration flows to and from selected countries - The 2015 revision from the United Nation's website*


Link: https://www.un.org/development/desa/pd/data/international-migration-flows


The cleaned-up dataset can be downloaded here: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Canada.csv

- *Hands-on_7: San Francisco Police Department Incidents for the year 2016 - [Police Department Incidents]*


Link: https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry


GeoJSON file: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/world_countries.json

- *Hands-on_8, 9, 10: Airline Reporting Carrier On-Time Performance from Data Asset eXchange*


Link: https://developer.ibm.com/exchanges/data/all/airline/?cm_mmc=Email_Newsletter-_-Developer_Ed%2BTech-_-WW_WW-_-SkillsNetwork-Courses-IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork-20297740&cm_mmca1=000026UJ&cm_mmca2=10006555&cm_mmca3=M12345678&cvosrc=email.Newsletter.M12345678&cvo_campaign=000026UJ

- *Hands-on_11 & 12: Australia Wildfire data*


Link: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Historical_Wildfires.csv

- *Final-Assignment-Part-1 & 2: The dataset used for this visualization assignment contains *historical_automobile_sales* data representing automobile sales and related variables during recession and non-recession period.*
Link: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv

### Libraries
```bash
import numpy as np
import pandas as pd
import seaborn as sns # version 0.9.0
%matplotlib inline
import matplotlib as mpl
import matplotlib.pyplot as plt # Matplotlib version: 3.5.3
import matplotlib.patches as mpatches # needed for waffle Charts
from PIL import Image # converting images into arrays
import wordcloud # version 1.9.3
import folium #!pip3 install folium==0.5.0
from folium import plugins
import plotly.graph_objects as go
import plotly.express as px
import dash
from dash import dcc
from dash import html
from dash.dependencies import Input, Output, State
from dash import no_update
import datetime as dt
```
