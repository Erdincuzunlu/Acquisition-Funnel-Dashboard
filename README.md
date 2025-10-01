# Acquisition Funnel Dashboard

<p align="center">
  <img src="./dashboard_screenshot.png" alt="Dashboard Screenshot" width="800">
</p>

## Overview
This project is a sample **Acquisition Funnel Dashboard** built with **Looker Studio**.  
It tracks the customer journey from **Impressions → Clicks → Leads → Trials → Members** and calculates key performance indicators (KPIs).

The dashboard is created using **dummy data** (CSV), but the same logic can be applied to real-world data sources such as:
- Meta Ads (Facebook & Instagram)
- Google Search Console / Google Ads
- Airtable or GoHighLevel (CRM)
- MyStudio (class attendance & membership)

## Key Metrics
- **CTR (Click Through Rate)** = clicks ÷ impressions  
- **Lead Rate** = leads ÷ clicks  
- **Trial Rate** = trials ÷ leads  
- **CAC (Customer Acquisition Cost)** = ad_spend ÷ members  

These metrics help visualize marketing efficiency, cost per acquisition, and conversion at each funnel stage.

## Visualizations
The dashboard includes:
- **KPI Cards:** CTR, Lead Rate, Trial Rate, CAC  
- **Time Series:** Impressions vs Clicks over time  
- **Bar Charts:** Weekly breakdown of Impressions, Clicks, Leads, Trials, Members  
- **Funnel Charts:** Conversion Funnel (%) and Stage Funnel (counts)

## Files
- `dashboard_screenshot.png` – Dashboard preview  
- `Acquisition Funnel Dashboard.pdf` – Full export from Looker Studio  
- `dummy_funnel_data_100rows.csv` – Dummy dataset used  
- `README.md` – Project documentation  

## How to Reproduce
1. Open [Looker Studio](https://lookerstudio.google.com/)  
2. Create a new report and connect `dummy_funnel_data_100rows.csv`  
3. Add calculated fields for CTR, Lead Rate, Trial Rate, CAC  
4. Build charts and KPIs as described above  
5. Export or share the dashboard  

## Notes
- This is a **demo project** for portfolio purposes.  
- Real-world integration would use API connections to Meta Ads, Google, and CRM tools.  
- The same funnel logic can be applied to **SaaS, e-commerce, or education businesses**.

## License
MIT
