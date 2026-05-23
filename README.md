# Zomato Business Intelligence & Market Analysis

## **Executive Summary**
This project leverages exploratory data analysis (EDA) to deliver actionable data science insights and business intelligence for opening a new premium restaurant in Bangalore. The analysis focuses on identifying prime locations, developing pricing strategies, and competitor mapping to maximize market success.

**Data Pipeline:**
- Handled missing data in critical columns such as ratings and cost by imputation or removal.
- Standardized rating formats and converted costs into numeric values.
- Extracted and cleaned location data for accurate geographical mapping.

**Key Insights:**
- Market Saturation (BTM layout has the most footfall but highest competition).
- Pricing Strategy (There is a clear mathematical floor for ratings as premium pricing increases).
- Competitor mapping for premium spots.

**Visualizations:**
![Insight 1](screenshots/market_share.png)
![Insight 2](screenshots/cost_vs_rating.png)
![Insight 3](screenshots/btm_competitors.png)

**How to Run:**
```bash
# Clone the repository
git clone https://github.com/Rehanku/zomato-business-eda.git
cd zomato-business-eda

# Create a virtual environment
python3 -m venv .venv

# Activate the virtual environment
source .venv/bin/activate

# Install the required packages
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook notebooks/01_EDA.ipynb
```

## **🛠️ Skills Demonstrated**
- **Data Wrangling:** Regex and string manipulation for cleaning complex columns like `rate`.
- **Geospatial Grouping:** Analyzing location data to understand market saturation and footfall.
- **Business Storytelling:** Translating raw metrics into actionable strategies for pricing and competitor mapping.

---
## 📬 Let's Connect
**Rehan Khan**
* **LinkedIn:** [linkedin.com/in/rehan-khan-741088377](https://www.linkedin.com/in/rehan-khan-741088377/)
* **GitHub:** [github.com/Rehanku](https://github.com/Rehanku)
