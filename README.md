# StaySpain
Practical business simulation project using a real tourist accommodations dataset, complemented with secondary sources such as the "Encuesta de Ocupación Hotelera (INE).
The goal is to replicate real-world analytics and reporting processes to support data-driven decision-making and KPI monitoring.

---

## Project Overview

The analysis focuses on understanding customer experience in tourist accommodations across Spanish cities where Stay Spain operates. It explores satisfaction levels, occupancy rates, and the relationship between price and customer ratings to generate actionable insights for business expansion and operational improvement, amongs others.

The project was developed collaboratively with specialists in **marketing**, **operations**.

**Role:** Customer Experience Analyst

---

## Business Questions (Customer Experience Area)

* What is the average rating given by users to tourist accommodations?
* What percentage of accommodations have a general rating higher than 80 in each city?
* Which aspects show the largest differences between the best- and worst-rated accommodations?
* Is there a relationship between accommodation price and customer satisfaction?
* Should the company expand into the hotel market beyond tourist accommodations?

---

## Key Performance Indicators (KPIs)

* General satisfaction index
* City with the highest occupancy rate
* Occupancy ratio
* Highest-rated service item

---

## Technologies & Tools

* **[Python](https://www.python.org/)** (data cleaning, transformation, analysis)
* **[Pandas](https://pandas.pydata.org/)** – Data manipulation and aggregation
* **[NumPy](https://numpy.org/)** – Numerical operations
* **[Matplotlib](https://matplotlib.org/stable/contents.html)** and **[Seaborn](https://seaborn.pydata.org/)** – Data visualization
* **[MissingNo](https://github.com/ResidentMario/missingno)** – Missing data analysis
* **[SQL](https://dev.mysql.com/doc/)** – Data extraction and relational modeling
* **[Flourish](https://flourish.studio/)** – Interactive dashboards and storytelling visualizations

**Techniques:**

* Statistical validation and hypothesis testing
* Correlation analysis between pricing and satisfaction
* Distribution analysis and pattern detection
* **[Spearman’s rank correlation test](https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient)** for non-linear relationships
* Advanced visualizations (heatmaps, scatterplots, geospatial maps)

---

## Visual Features

* **Bar charts** – % of accommodations with ratings > 80 by city
* **Heatmaps** – Satisfaction differences by item and city
* **Scatter plots** – Correlation between price and customer ratings
* **Geographical map** – Distribution of accommodations by city
* **Composite dashboard** – Overview of KPIs and insights for decision-makers
* **And much more!**

---

## Data

* Format: CSV
* Size: ~10,000 records, 35 columns
* Sources:
  * Primary dataset of tourist accommodations
  * Secondary source: [INE – Encuesta de Ocupación Hotelera](https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736177015&menu=ultiDatos&idp=1254735576863)

---

## 🧠 Techniques & Insights

The analysis combined **exploratory data analysis (EDA)** with advanced statistical validation:

* **Correlation analysis** identified the relationship between accommodation prices and customer satisfaction across different cities.
* **Distribution plots** were used to evaluate how satisfaction and price values vary by region.
* **Spearman’s rank correlation test** validated non-linear relationships between numerical variables.
* **Boxplots** and **violin plots** provided visual support for detecting outliers and data asymmetries.
* Findings were confirmed through statistical confidence intervals to ensure robustness.

---

## Project Structure

/week 1/results/ → Analysis outputs and visualizations for week 1
/week 2/data/ → Datasets for week 2 analysis
/week 2/results/ → Analysis outputs and visualizations for week 2
/week 3/data/ → Datasets for week 3 analysis
/week 3/results/ → Analysis outputs and visualizations for week 3
/week 4/data/ → Datasets for week 4 analysis
/week 4/results/ → Analysis outputs and visualizations for week 4
README.md → Project documentation

recursos/ contains the main dataset and secondary sources.
week 1/data/ → week 4/data/ contain CSV datasets for each week of analysis.
week 1/results/ → week 4/results/ contain visualizations, plots, and analytical outputs.

---

## Results & Business Impact

The analysis identified key patterns in customer satisfaction and occupancy:

** **Barcelona and Girona need to explore strategies** to improve accommodation quality and experience, aiming to meet the 90% high-rating target.
* **Price and satisfaction correlation** there isn't a correlation, showing potential for price elasticity and  brand repositioning with a focus on experience.
* **Accommodation items** such as cleanliness and location have the strongest influence on overall satisfaction.
* **Recommendation:** explore expansion into the hotel market, where customer satisfaction and occupancy indicators suggest higher profitability.

Results were presented to stakeholders through data-driven presentation and visualizations, supporting evidence-based decision-making.

---

## 👤 Author

**Álvaro Pérez-Hernán**
Customer Experience Analyst – Data storytelling and visualization

[GitHub Repository](https://github.com/aperezhernan/StaySpain)
