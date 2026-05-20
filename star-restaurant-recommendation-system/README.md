# Star Restaurant Identification & Recommendation System 📊🍳

## 📌 Project Overview
This project focuses on helping a global restaurant consolidator revamp its B2C portal using data-driven intelligence. Instead of relying on static, traditional sorting systems (like alphabetical lists), this project establishes a dynamic analytics matrix to identify **"Star Restaurants"** and power an automated recommendation engine. 

By analyzing user engagement, operational features, and geographic distribution, this end-to-end analytics solution translates raw operational data into actionable business strategies.

---

## 🛠️ Tech Stack & Tools
* **Data Processing & EDA:** Python (`Pandas`, `NumPy`)
* **Data Visualization:** Tableau, Excel, `Matplotlib`, `Seaborn`
* **Environment:** Jupyter Notebook

---

## 📈 The "Star Restaurant" Framework
A major milestone of this project was moving away from looking *only* at aggregate reviews. The data revealed that a true "Star Restaurant" is an ecosystem of customer engagement. The final matrix evaluates venues based on four core pillars:
1. **Quality:** High aggregate customer ratings.
2. **Popularity:** High transaction/voting volumes.
3. **Convenience:** Active online delivery options.
4. **Operational Capability:** Availability of online table bookings.

---

## 🔍 Key Data Insights
* **Geographic Density:** India represents the highest restaurant density in the network, identifying it as the ideal testing ground for localized feature rollouts.
* **The Convenience Premium:** Restaurants offering online delivery options experienced a massive spike in user engagement and vote volume compared to those without it. Platform convenience directly drives user activity.
* **Price vs. Quality:** There is a clear, statistically significant upward trend showing that higher price ranges directly correlate with better average ratings—proving that quality scales with cost.

---

## 📁 Repository Structure
* `/notebooks`: Contains `Marketing_EDA.ipynb` which covers data cleaning, handling missing values, removing duplicates, table joining (with Country Codes), and exploratory visualizations.
* `/dashboards`: Contains the final `Restaurant_Overview_Dashboard_Project_Report.pdf` detailing the visual presentation layouts.
    * *Dashboard Components include:* Executive KPI summary indicators, a World Map distribution plot, Rating vs. Votes scatter plots, Cost vs. Rating bar charts, and a Top 10 Cuisines performance breakdown.

---

## 🚀 Future Enhancements
* **Machine Learning Integration:** Upgrading the current matrix to a collaborative filtering or content-based recommendation engine.
* **Sentiment Analysis:** Scraping and parsing qualitative customer text reviews to catch underlying consumer sentiment trends.
* **Live Pipeline:** Transitioning static datasets into a live stream data feed for real-time dashboard updates.

---
💡 *This project was completed as a Capstone Project during the Simplilearn Masters Program.*