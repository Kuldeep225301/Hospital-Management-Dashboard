# 🏥 Hospital Management Dashboard (Power BI)

An interactive Power BI dashboard that consolidates hospital operations and financial performance into a single view — helping hospital management monitor patient demographics, doctor availability, billing, and payment trends for data-driven decision-making.

---

## 📌 Objective

The objective of this project is to design an interactive Hospital Management Dashboard using Power BI that provides a comprehensive overview of hospital operations and financial performance. The dashboard helps hospital management and stakeholders monitor patient demographics, doctor availability, billing status, and payment trends in order to support data-driven decision-making, improve operational efficiency, and enhance financial control.

> **Problem Statement:** *"To build a Power BI dashboard that analyzes hospital patient data, doctor specialization, and billing performance to support operational and financial decision-making."*

---

## 🎯 Scope of Analysis

- What is the total patient volume, and what does the patient age profile look like?
- How many doctors are available, and how is patient load distributed across specializations?
- What is the total billed amount, and how much has been collected vs. is still pending?
- Which payment modes (Cash, Card, Online, Insurance, etc.) are most commonly used by patients?
- Where are the biggest opportunities to improve collections and resource allocation?

---

## 🛠️ Methodology & Approach

- **Data Preparation:** Performed ETL and data wrangling to clean and integrate structured hospital datasets (patient records, doctor assignments, billing data).
- **Data Modeling:** Built relationships between patient, doctor, and billing tables, and created DAX measures to calculate key metrics and optimize dashboard performance.
- **Dashboard Design:** Designed a **2-page interactive Power BI dashboard** — a main dashboard view for at-a-glance KPIs, and a detailed metrics/overview page for deeper drill-down analysis.
- **Visualization:** Used KPI cards, bar/column charts, and breakdown visuals to represent patient demographics, doctor specialization load, and payment mode distribution.

**Technical Stack:** Power BI · ETL · Data Wrangling · Data Modeling · DAX Measures

---

## 📊 Dashboard Features

| Metric / View | Purpose |
|---|---|
| Total Patients & Average Age | Insight into patient demographics and case mix |
| Total Doctors | Assess resource availability and specialization coverage |
| Total Bill Amount | Track overall hospital revenue |
| Paid Amount vs. Pending Amount | Monitor collected revenue vs. outstanding dues |
| Doctor Specialization vs. Patient Load | Identify high-demand specialties and optimize doctor allocation |
| Payment Mode Analysis | Cash, Card, Online, Insurance — understand patient payment behavior |

---

## 💡 Key Insights

- Analyzing average patient age alongside total patient volume gives a clear view of the case mix, informing staffing and resource planning.
- Comparing doctor specialization against patient load surfaces which specialties are in high demand vs. which have spare capacity, enabling more balanced doctor allocation.
- Splitting total billed amount into paid vs. pending gives administrators immediate visibility into cash flow and outstanding dues, rather than a single opaque revenue number.
- Payment mode analysis reveals which channels patients prefer, highlighting where billing/collection processes could be streamlined (e.g., promoting faster-settling digital payment modes).
- Consolidating clinical and financial metrics into one interactive dashboard replaces scattered manual reporting with a single source of truth for hospital administration.

---

## ✅ Business Impact

By combining these views, the dashboard enables hospital administrators to:
- Monitor financial health and reduce pending payments
- Optimize doctor utilization across specializations
- Gain insight into patient trends and demographics
- Improve transparency and operational planning

---

## 🚀 How to Use

1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Refresh the data source (or load your own hospital dataset in the same schema).
4. Navigate between the **Main Dashboard** and **Detailed Metrics/Overview** pages to explore the data.

---

## 📁 Repository Structure

```
├── Hospital_Management_Dashboard.pbix   # Power BI dashboard file
├── data/                                # Hospital patient, doctor & billing dataset
└── README.md                            # Project documentation
```

---

## 🏷️ Tags

`Power BI` `Healthcare Analytics` `Data Visualization` `DAX` `Dashboard` `ETL` `Business Intelligence`

---

## 📬 Connect

If you found this project useful, feel free to ⭐ the repo or connect with me for feedback and collaboration!
