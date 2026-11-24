# Agricultural-Production-Yield-Annalysis
# 🌾 Nigeria Agricultural Production & Yield Analysis (2015–2024)

## 📌 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** of historical crop production patterns in Nigeria using **FAOSTAT (QCL Domain)** data from **2015 to 2024**. The analysis evaluates five major crops—**Cassava (fresh), Yams, Maize (corn), Rice, and Cocoa beans**—to uncover growth trends, land efficiency, and investment opportunities.

![Dashboard Preview](images/dashboard.png)

---

## Research Objective & Business Question
* **Research Objective:** To analyze historical crop production patterns in Nigeria, compare production and yield performance across selected crops, and identify trends that inform future agricultural investment research.
* **Business Question:** *Which selected crops demonstrate the strongest production and yield performance in Nigeria, and what historical patterns should inform further agricultural investment investigation?*
* **Target Stakeholders:** Agricultural investors, agribusiness executives, policymakers, and agricultural development agencies.

---

## Key Findings & Research Question Answers

| Metric (2015–2024) | 2015 Baseline | 2024 Final | 10-Year Change | Key Takeaway |
| :--- | :---: | :---: | :---: | :--- |
| **Total Production (`t`)** | 118,924,616 | 148,590,878 | **+24.95%** | Strong upward volume growth |
| **Harvested Area (`ha`)** | 23,548,953 | 30,111,495 | **+27.87%** | Growth driven by land expansion |
| **Average Yield (`kg/ha`)** | 3,905.48 | 3,657.04 | **-6.36%** | Peaked in 2018 (`4,725.3`), then declined |

### Crop-by-Crop Breakdown (2015–2024)

| Crop (`Item`) | 10-Yr Total Production (`t`) | Production Growth | 10-Yr Avg Yield (`kg/ha`) | Area Harvested Growth |
| :--- | :---: | :---: | :---: | :---: |
| **Cassava, fresh** | 602,143,776 | **+9%** | 7,040.79 | +35.7% |
| **Yams** | 555,914,967 | **+48%** | 8,515.13 | +48.7% |
| **Maize (corn)** | 114,551,593 | **+17%** | 1,900.13 | -0.9% |
| **Rice** | 83,107,410 | **+21%** | 1,997.57 | +25.2% |
| **Cocoa beans** | 3,007,703 | **+16%** | 280.99 | +23.0% |

* **Top & Bottom Performing Produce:** **Cassava (fresh)** recorded the highest cumulative 10-year production (`602.1M t`), though **Yams** grew fastest (`+48%`) and overtook Cassava in 2024 (`65.3M t` vs. `62.6M t`). **Cocoa beans** recorded the lowest physical production (`3.01M t`).
* **Yield Efficiency Rankings:** **Yams** recorded the highest average yield (`8,515.1 kg/ha`), followed by **Cassava** (`7,040.8 kg/ha`). **Cocoa beans** recorded the lowest yield (`281.0 kg/ha`), followed by **Maize** (`1,900.1 kg/ha`) and **Rice** (`1,997.6 kg/ha`).
* **Harvested Area Shifts:** Harvested land expanded across all crops except **Maize (corn)**, which experienced a slight reduction (`-0.9%`) from 2015 to 2024.
* **Area vs. Production Relationship (`r = 0.71`):** Increases in harvested area are strongly correlated with higher production, proving that output gains came primarily from farming *more land* rather than improved yield per hectare.

---

## Tools & Workbook Structure
* **Data Source:** FAOSTAT Crops and Livestock Products (`2015–2024`)
* **Tools Used:** Microsoft Excel (`PivotTables`, `SUMIFS`, `CORREL`, Descriptive Statistics, Dynamic Dashboard)
* **Workbook Tabs:**
  1. `Raw_Data`: Untouched FAOSTAT source records.
  2. `Data_Quality`: Duplicate checks, missing value validation, and long-format structuring.
  3. `Analysis`: Year-over-year aggregations, growth rates, yield calculations, and correlation testing.
  4. `Dashboard`: Executive visual summary of production, yield, and area trends.

---

## Investment Recommendations
1. **Shift Capital Toward Yield Efficiency:** Focus funding on high-yield seedlings, fertilizers, and irrigation to reverse declining yields (such as Cassava's yield drop despite +35.7% land expansion).
2. **Scale Tuber Value Chains:** Prioritize processing and post-harvest infrastructure for **Yams** and **Cassava**, Nigeria's highest-volume and fastest-growing staples.
3. **Address Grain & Cocoa Bottlenecks:** Investigate drivers behind declining **Maize** acreage (`-0.9%`) and low per-hectare yields in **Cocoa**, **Maize**, and **Rice**.
