# 📢 Marketing Campaign Performance Analysis — IBM Cognos Analytics

![IBM Cognos](https://img.shields.io/badge/IBM%20Cognos-Analytics-blue?style=for-the-badge&logo=ibm&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-300K%20Records-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📌 Project Overview

End-to-end marketing campaign performance analysis on a Social Media Advertising dataset 
(300,000 records, 19 variables) using IBM Cognos Analytics.

The goal was to identify **which channels, campaign goals, and audience segments 
deliver the best ROI and engagement** for marketing decision-making.

**Tool:** IBM Cognos Analytics (Dashboard + Reports)

---
---

## 📊 Dashboard Preview

### Page 1 — Key Performance Indicators
![KPI Dashboard](dashboard/New_dashboard.pdf)

> KPIs covered: Impressions, Clicks, CTR, CPC, ROI, Acquisition Cost

### Page 2 — Charts & Graphs
- Channel-wise clicks by Campaign Goal
- Impressions by Campaign Goal (Pie chart)
- Acquisition Cost vs ROI scatter plot
- Impressions trend by Date and Channel

### Page 3 — Detail Table
Campaign-level breakdown with filters for Channel, Audience, and Goal

---

## 🔍 Key Findings

### 📈 Overall KPIs
| Metric | Value |
|--------|-------|
| Total Impressions | 16.8 Billion |
| Total Clicks | 5.4 Billion |
| Average CTR | 31.42% |
| Average CPC | $0.46 |
| Average ROI | 3.18 |
| Total Acquisition Cost | $2.33 Billion |

### 📱 Channel Performance (ROI)
| Channel | Avg ROI | Avg CPC | Total Impressions |
|---------|---------|---------|-------------------|
| Instagram | **4.01** 🏆 | $0.387 | 4.6B |
| Twitter | 4.00 | $0.388 | 4.6B |
| Facebook | 3.99 | $0.388 | 4.6B |
| Pinterest | 0.72 🔻 | $0.660 | 3.0B |

> **Instagram delivers the highest ROI** while Pinterest underperforms significantly

### 🎯 Campaign Goals
| Campaign Goal | Avg CTR | Conversion Rate |
|---------------|---------|----------------|
| Brand Awareness | 31.42% | 8.0% |
| Increase Sales | 31.42% | 7.99% |
| Market Expansion | 31.42% | 8.02% |
| Product Launch | 31.41% | 7.99% |

> All campaign goals perform similarly in CTR — differentiation lies in channel selection

### 💡 Key Insights
1. **Pinterest has the lowest ROI (0.72)** — 5x lower than Instagram/Twitter — budget reallocation recommended
2. **Pinterest also has the highest CPC ($0.66)** — most expensive but least effective channel
3. **Instagram is the clear winner** — highest ROI, lowest CPC, strong impressions
4. **All campaign goals perform uniformly** — goal type doesn't significantly impact CTR or conversion
5. **300K campaigns analyzed** — large enough dataset for statistically reliable insights

---

## 💡 Business Recommendations

1. **Reallocate Pinterest budget** to Instagram and Twitter — ROI is 5x better
2. **Instagram-first strategy** for campaigns targeting high ROI
3. **Market Expansion** goal shows marginally better conversion — prioritize for new audience targeting
4. **Monitor CPC trends** — Pinterest's high CPC with low ROI is a red flag

---

## 🗂️ Dataset Details

| Feature | Details |
|---------|---------|
| Source | Kaggle — Social Media Advertising Dataset |
| Records | 300,000 campaigns |
| Variables | 19 |
| Channels | Facebook, Instagram, Pinterest, Twitter |
| Goals | Brand Awareness, Increase Sales, Market Expansion, Product Launch |
| Date Range | 2022 |

---

## 🔗 Related Projects
- HR Attrition SQL + Power BI: [employee-attrition-sql](https://github.com/Amitj6124/employee-attrition-sql)
- HR Attrition Python EDA: [ibm-hr-attrition-eda-python](https://github.com/Amitj6124/ibm-hr-attrition-eda-python)
