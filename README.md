# data-pipeline-web-to-dashboard
🌐 End-to-End Data Science Project | Web Scraping, Data Cleaning, Analysis, Visualization &amp; Tableau Dashboard

---

## 🏢 Top Indian Companies – Web Scraping, Analysis & Visualization

This project showcases end-to-end data handling — from extracting company data using web scraping, cleaning and analyzing the dataset in Python, and visualizing insights through Tableau dashboards.

---

### 🔧 Tools & Libraries Used

* **Python**

  * `requests`
  * `BeautifulSoup`
  * `pandas`
  * `matplotlib` / `seaborn`
* **Tableau Public** for interactive dashboards

---

### 📌 Project Workflow

1. **📥 Web Scraping**

   * Extracted data from a public website listing top Indian companies using `requests` and `BeautifulSoup`.

2. **🧹 Data Cleaning**

   * Cleaned missing values
   * Standardized industry & location columns
   * Converted revenue/profit strings to numerical formats

3. **📊 Data Analysis**

   * Identified patterns in industries, headquarters, and company performance
   * Used filtering/grouping techniques for sector-level insights

4. **📈 Visualization & Dashboards (Tableau)**

   * Created bar charts, bubble charts, and scatter plots
   * Interactive dashboards to explore:

     * Top industries by revenue
     * City-wise company distribution
     * Revenue vs Profit mapping

---

### 📉 Key Insights

* **Banking** and **Oil & Gas** dominate in total revenue.
* **Mumbai** and **New Delhi** are the primary headquarters for major companies.
* Several companies with modest revenue still show high profit margins, indicating operational efficiency.
* The **Automotive**, **Insurance**, and **Infotech** industries contribute significantly across both revenue and company count.

---

### 📊 Tableau Dashboards

* [📍 Revenue by Industry](https://public.tableau.com/app/profile/poojith.inavolu/viz/revenuebyindustry/Sheet4)
* [🏙️ Top Companies in India – Overview](https://public.tableau.com/app/profile/poojith.inavolu/viz/topcompaniesinindia2/Dashboard1)
* [📈 Industry-Wise Revenue & Headquarters Distribution](https://public.tableau.com/app/profile/poojith.inavolu/viz/topcompaniesinindia/Dashboard2)

---

### 📁 Repository Structure

```
top-indian-companies/
│
├── 📂 data/
│   └── companies_cleaned.csv        # Cleaned dataset
│
├── 📂 notebooks/
│   └── web_scraping_analysis.ipynb  # Full Colab notebook
│
├── 📄 README.md                     # Project overview and insights
```

---

### 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/poojithinavolu/data-pipeline-web-to-dashboard.git
   cd top-indian-companies
   ```

2. Run the notebook:
   Open `web_scraping_analysis.ipynb` in Google Colab or Jupyter Notebook.

---
