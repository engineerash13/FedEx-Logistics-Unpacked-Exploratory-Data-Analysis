# FedEx Logistics Unpacked: Exploratory Data Analysis

An individual EDA project analyzing FedEx supply chain performance using Python and Plotly. The project examines delivery patterns, shipment mode efficiency, vendor performance, and INCO term impact across global logistics data.

**Author:** Ashwin Suryawanshi

---

## Tools & Technologies

- Python (Pandas, NumPy)
- Plotly (interactive visualizations)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Files in This Repository

| File | Description |
|------|-------------|
| `EDA ON FedEx Dataset.ipynb` | Full EDA notebook — data cleaning, univariate, bivariate, and multivariate analysis with 20+ charts |

---

## Dataset

**Source dataset:** `SCMS_Delivery_History_Dataset.csv`

The dataset contains FedEx shipment-level records including:

| Column | Description |
|--------|-------------|
| Shipment Mode | Air, Sea, Road, etc. |
| Country | Destination country |
| Managed By | Management team (e.g., PMO - US) |
| INCO Terms | International commercial terms |
| Scheduled Delivery Date | Planned delivery date |
| Delivered to Client Date | Actual delivery date |
| Shipment Weight | Weight in kg |
| Insurance | Insurance cost |
| Item Description | Product type |

---

## Project Objectives

- Determine whether shipment mode influences on-time delivery rate
- Identify if management teams (e.g., PMO - US) differ in delivery effectiveness
- Analyze the correlation between shipment weight and insurance costs
- Understand country-specific delivery performance
- Examine the impact of INCO terms on vendor reliability

---

## Analysis Structure (UBM Framework)

### Univariate Analysis
- Distribution of shipment modes
- Delivery status breakdown (on-time vs delayed)
- Country-wise shipment volume

### Bivariate Analysis
- Shipment mode vs on-time delivery rate
- Management team vs delivery performance
- INCO terms vs vendor reliability
- Shipment weight vs insurance cost (correlation)

### Multivariate Analysis
- Combined effect of country + mode + INCO terms on delivery
- Heatmaps of delivery performance across segments

---

## Key Insights

- **South Africa Field Office** achieved the highest on-time delivery rate at **98.25%**
- **PMO - US** lagged significantly at **55.67%** on-time delivery
- **Air shipments** outperformed Sea and Road in on-time rates
- **Positive correlation** observed between shipment weight and insurance costs
- Significant variation in performance based on country and INCO terms

---

## Business Recommendations

- Audit and restructure PMO - US operations — the 55.67% on-time rate is a major operational risk
- Shift high-priority shipments to Air mode where cost-effective
- Renegotiate INCO terms with consistently underperforming vendors
- Implement predictive delivery scoring using shipment weight and mode

---

## Topics

`eda` `python` `pandas` `plotly` `logistics` `supply-chain` `data-analysis` `fedex`
