# Advanced Data Visualization: Treemap (RAWGraphs)

This repository contains the data and instructions to generate a **Treemap visualization** using [RAWGraphs](https://rawgraphs.io/).  
The visualization represents **market share distribution** across product categories and subcategories, designed for **portfolio analysis and resource allocation** in strategic consulting.

---

## 📧 Email
21f2000670@ds.study.iitm.ac.in

---

## 📂 Repository Structure
- **data.csv** → Hierarchical dataset with columns:
  - `category`
  - `subcategory`
  - `value`
- **chart.png** → Final Treemap exported from RAWGraphs (PNG, 300–512px).
- **README.md** → Project overview and usage instructions.

---

## 🔎 Data Context
The dataset contains **15–20 rows** representing different product categories (Electronics, Clothing, Home & Garden, etc.) and their respective subcategories.  
Values represent **market share / business value**, making the dataset realistic for **portfolio analysis**.

---

## 🛠️ How to Reproduce the Treemap
1. Visit [RAWGraphs.io](https://rawgraphs.io/).
2. Import `data.csv` (copy & paste or upload).
3. Select **Treemap** chart.
4. Map fields:
   - **Hierarchy** → `category` → `subcategory`
   - **Size** → `value`
   - **Color** → `category`
   - **Labels** → `subcategory` (and optionally `value`)
5. Customize:
   - Professional categorical color palette.
   - Thin borders for category separation.
   - Compact number formatting (e.g., 1.2M, 845k).
6. Export the chart:
   - Format: **PNG**
   - Dimensions: **512×512 px** (or any size 300–512px)
   - Save as `chart.png` in this repository.

---

## 🎯 Business Use Case
- Helps executives **visualize portfolio distribution** quickly.
- Treemap shows **relative market values** across categories & subcategories.
- Publication-ready for **annual reports, board presentations, and strategy documents**.

---

© Bergnaum Okuneva and Satterfield — Strategic Consulting, Advanced Data Visualization.

