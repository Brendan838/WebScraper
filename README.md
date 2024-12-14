# Mars News and Weather Data Analysis

## Overview
This project involves web scraping and data analysis to collect, organize, and analyze information about Mars. The project is divided into two parts:

1. **Scraping titles and preview text from Mars news articles.**
2. **Scraping and analyzing Mars weather data from an HTML table.**

The project uses Beautiful Soup, Splinter, and Pandas to achieve these goals.

---

## Deliverables
The project consists of two deliverables:

### Deliverable 1: Scrape Titles and Preview Text from Mars News
- **Objective:** Scrape the titles and preview text of news articles from the [Mars News website](https://redplanetscience.com/).
- **Steps:**
  - Use automated browsing with Splinter to visit the site.
  - Create a Beautiful Soup object to parse the HTML.
  - Extract titles and preview text of the news articles.
  - Store the scraped data in a Python list of dictionaries with the format:
    ```python
    {'title': 'Sample Title', 'preview': 'Sample preview text.'}
    ```
  - Optionally, save the data to a JSON file for easy sharing.

- **Output:** A Python list containing dictionaries of titles and previews.

---

### Deliverable 2: Scrape and Analyze Mars Weather Data
- **Objective:** Scrape Mars weather data from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and analyze it.
- **Steps:**
  - Use Beautiful Soup to scrape the data from the HTML table.
  - Assemble the data into a Pandas DataFrame with the following columns:
    - `id`: Identification number
    - `terrestrial_date`: Earth date
    - `sol`: Martian day since Curiosity's landing
    - `ls`: Solar longitude
    - `month`: Martian month
    - `min_temp`: Minimum temperature in Celsius
    - `pressure`: Atmospheric pressure at Curiosity's location
  - Convert data types to the appropriate formats (e.g., datetime, int, float).
  - Perform data analysis using Pandas to answer the following:
    - Number of months on Mars.
    - Total Martian days of data available.
    - Coldest and warmest months on Mars, based on average minimum temperatures (visualized with a bar chart).
    - Months with the lowest and highest atmospheric pressure (visualized with a bar chart).
    - Approximate number of terrestrial days in a Martian year, estimated using a plot of daily minimum temperatures.
  - Export the DataFrame to a CSV file.

- **Output:** A cleaned and analyzed Pandas DataFrame, visualizations, and a CSV file.
---

## Tools and Libraries
The following tools and libraries are used in this project:
- **Python**
- **Jupyter Notebook**
- **Beautiful Soup**: For HTML parsing
- **Splinter**: For automated browsing
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For data visualization

---

## Usage
1. Clone the repository to your local machine.
2. Open the Jupyter Notebooks (`part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`) in your environment.
3. Follow the instructions within the notebooks to run the code step-by-step.
4. Review the generated outputs, including the Mars news data and Mars weather analysis.

---

## Contact
For questions or feedback, feel free to reach out to me at Brendan838@gmail.com

---

