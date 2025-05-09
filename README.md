# Supply Chain Delivery Analysis

This capstone explores operational drivers of late deliveries using R, Python, and predictive modeling. The project analyzes 11,000+ records to identify key delivery risk patterns and segments.

---

## Project Summary

- Built an end-to-end analytics pipeline to model on-time delivery outcomes.
- Discovered that products under **$175 and 4 lbs** had a **96.8%** on-time rate.
- Used `XGBoost`, `Logistic Regression`, and `Decision Trees` to classify late deliveries with up to **68% accuracy**.
- Designed visuals in `ggplot2` and `seaborn`; final reporting in `R Markdown`.

---

## Key Insights

- **0% late deliveries** for products between **4.5–8 lbs**
- “Ship” mode and warehouse **Type F** were highly represented in perfect delivery segments
- Delivery priority, support calls, and gender were **not significant predictors**

---

## Project Structure

| File / Folder              | Description                                  |
|---------------------------|----------------------------------------------|
| `train.csv`               | Cleaned dataset used for modeling            |
| `Supply_Chain_Analysis.Rmd` | Full R Markdown analysis + final report      |
| `product_cost_vs_weight.png` | Key scatterplot showing perfect segments     |
| `colab_modeling.ipynb` *(optional)* | Python-based modeling in Colab        |
| `Supply_Chain_Analysis.html` | Knit version of the final report (viewable) |

---

## Links

- [Final HTML Report (R Markdown)](./Supply-Chain-Analysis.html)
- [Colab Notebook (Python modeling)](https://colab.research.google.com/drive/1FVgIY6qvmbH7W0Zrpdu1KYgv2V9KvMJ5?usp=sharing))

## Key Visuals

### Product Cost vs Weight
![Product Cost vs Weight](./product_cost_vs_weight.png)

### On-Time Delivery by Warehouse Type
![On-Time Delivery by Warehouse](./on_time_delivery_by_warehouse_type.png)

### On-Time Delivery by Delivery Type
![On-Time Delivery by Delivery Type](./on_time_delivery_by_delivery_type.png)


---

## Tools Used

- **R**: tidyverse, ggplot2, dplyr, readr
- **Python**: pandas, seaborn, scikit-learn, xgboost
- **Modeling**: Logistic Regression, Decision Tree, XGBoost (tuned)
- **Reporting**: R Markdown, GitHub Pages

---

## Contact

Built by [Casey Ortiz](https://www.linkedin.com/in/kco1).  
Best Contact: kcarlos.ortiz@gmail.com
Looking for roles in Data Analytics | ML Ops | Supply Chain Intelligence.

