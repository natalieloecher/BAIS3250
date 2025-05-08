# Data Wrangling Project Template

This repository provides a structured starting point for data wrangling projects, including folders for data, notebooks, documentation, and outputs.

---

##  Folder Structure

| Folder       | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| `data/`      | Contains raw and cleaned datasets (CSV files, scraped data, etc.)           |
| `notebooks/` | Jupyter Notebooks for cleaning, analysis, and visualizations                |
| `outputs/`   | Final figures, charts, and reports                                          |        |

---

##  Table of Contents

- [Folder Structure](#-folder-structure)
- [Data Dictionary](#-data-dictionary)
- [Data Sources](#-data-sources)
- [Notebooks](#-notebooks)

---

##  Data Dictionary

| Column Name           | Description                                          |
|-----------------------|------------------------------------------------------|
| Rating                | Star rating in text form (e.g., '4.3 stars')         |
| Clean_Date            | Cleaned review date in YYYY-MM-DD format             |
| Location              | Restaurant or cafe name where review was left        |
| NumericRating         | Numeric version of star rating (float)               |
| City                  | City and state of the location (e.g., Chicago Illinois) |
| Date_y                | Date matched from the weather dataset (YYYY-MM-DD)   |
| Temp Max (°F)         | Maximum temperature recorded on that day (°F)        |
| Temp Min (°F)         | Minimum temperature recorded on that day (°F)        |
| Avg Temp (°F)         | Average daily temperature (°F)                       |
| Feels Like (°F)       | 'Feels Like' temperature (°F)                        |
| Humidity (%)          | Humidity percentage on that day                      |
| Precipitation (in)    | Precipitation measured in inches                     |
| Snow (in)             | Snowfall recorded that day in inches                 |
| Snow Depth (in)       | Depth of snow on the ground (inches)                 |
| Wind Speed (mph)      | Average wind speed in miles per hour                 |
| Cloud Cover (%)       | Percentage of sky covered by clouds                  |
| Visibility (mi)       | Visibility distance in miles                         |
| UV Index              | Ultraviolet index score (0–11+)                      |
| Severe Weather Risk   | Risk level for severe weather (0–100 scale)          |
| Conditions            | General weather description (e.g., 'Rain', 'Cloudy') |


---

##  Data Sources

- Review data scraped from [OpenTable](https://www.opentable.com/)
- Weather data from [National Weather Service](https://www.weather.gov/)

---

##  Notebooks

- `naloecher_WebScraping&Integration.ipynb`: Merges weather and review data.
