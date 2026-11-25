# Insurance Performance Dashboard (Power BI)

A 360° view of customers, policies and agents, built in Power BI from ~109K insurance transactions (2022–2024).

## Home page 
<img width="950" height="533" alt="homepage insurance" src="https://github.com/user-attachments/assets/53f493e0-d7fc-4796-bdef-e97a2ef2f220" />


## 🔗 Live Dashboard

**[Open the interactive dashboard (Power BI, published to web)](https://app.powerbi.com/view?r=eyJrIjoiNDg5Y2M1YzYtYjgyNS00NGFkLTk5NDctNzAxMDFjMjkzZGRlIiwidCI6IjQ4NTkyZTczLTE2OTUtNGVmMy1hYzg3LWM0ZDNjMGVhNDYzMyJ9)**

> Tip: open the link on a laptop or desktop for the best experience. Hover effects need a mouse.

## Presentation

Slides summarising the findings and insights: [`Insurance_Dashboard_Presentation.pptx`](Insurance-Performance-Dashboard-Findings-andInsights.pptx)

## Objective
Give leadership one place to track premium growth, claims, loss ratio, customer quality and branch/agent performance, with filters that work across every page.

## Dataset
insurance (1).csv : policy, customer, agent, branch, region, premium, claims, commission, renewal, cross-sell, satisfaction and risk fields.

## Dashboard Pages

### Overview
Premium, claims, loss ratio, active policies, regional premium and the monthly premium trend.
<img width="997" height="537" alt="overview insurance" src="https://github.com/user-attachments/assets/cb047d34-2f6d-4659-9a1a-99bc9e1ca884" />


### Portfolio
Customer segments, renewal rate, satisfaction vs risk, income brackets and policy tiers.
<img width="998" height="536" alt="portfolio insurance" src="https://github.com/user-attachments/assets/cf858661-e3a7-4a80-9e46-44f56cf06680" />




### Channels
Claim approval, commission by agent experience level, claims status and top branches.
<img width="996" height="532" alt="insurance channel" src="https://github.com/user-attachments/assets/b1bdf36c-1b10-4d51-a14f-c2cfa4616fb7" />



## How to Navigate

1. **Start on the Home page** and click **Overview**, **Portfolio** or **Channels** or ask question of your choice concerning the insights.
2. On every page, use the **navigation buttons** on the left panel to switch pages. The current page is highlighted.
3. Use the **filter panel** (Year, Month, Region, Policy Type, Customer Segment) to slice every visual on the page. Click **Clear All Filters** to reset.
4. On the Overview page, use the **Metric Parameter** dropdown (top right of the page) to change the metric shown in the analysis chart. The chart title updates to match.
5. Click the **🌙 icon** at the top right of a page to switch between dark and light themes.

## How to Use the Hover KPI Cards

The KPI cards (for example **Total Premium** and **Total Claims Amount**) are custom HTML cards with a flip effect.

| Step | What happens |
|---|---|
| **Front of the card** | Shows the headline value, with a badge comparing it to the same period last year (or the previous month when a single month is selected). |
| **Hover your mouse over the card** | The card flips to show the detail: the change in value and the two periods being compared. |
| **Move the mouse away** | The card flips back to the headline value. |

Tips:
- Change the **Year** or **Month** slicer and hover again. The comparison updates with your selection.
- For **claims**, a rise is shown in red because higher claims are bad news. For **premium**, a rise is shown in green.

## Features
- Custom HTML KPI cards with a hover flip
- Metric parameter and dynamic chart titles
- Slicers for Year, Month, Region, Policy Type and Customer Segment
- YoY / MoM trend arrows with red/green logic (loss ratio inverted, since higher is worse)
- Page navigation buttons, Clear All Filters and a dark/light theme toggle

## Key Insights
- **$29.46M** premium vs **$18.30M** claims gives a **62.1% loss ratio** across **5,200** active policies.
- **Home** and **Life** drive premium. **Northeast** leads regions at $8.52M (28.9%).
- Loss ratio by line: Home 59.9%, Life 60.3%, Health 64.3%, **Auto 73.3%**, **Travel 107.3%** (small, $0.11M of premium).
- Annual premium fell from $10.12M (2022) to $9.56M (2024), about -5.6%.
- Retail is ~75% of 4,000 customers. Satisfaction (7.2) and risk (5.02) are steady across segments.
- Claim approval rate is 64.3% and the average claim is $2,228. Mid-level agents earn the most commission ($1.11M of $2.50M).
- **New York Branch 28** has the highest claims ($1.24M), about 32% above the next branch.

## Recommendations
Reprice or tighten Auto, review Travel terms, audit high-claim branches, and investigate the premium decline.

## Tools
Power BI Desktop, Power Query, DAX, HTML Content visual, Power BI Service.

## Repository Contents
```
├── Insurance_Dashboard.pbix
├── Insurance (1).csv
├── Insurance_Dashboard_Presentation.pptx
├── insurance.png
└── README.md
```

## 👤 Author
Aishat · Data Force Fellowship, IOTB Tech
