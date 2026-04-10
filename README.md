# Calgary-Urban-Equity-and-Socioeconomic-Indicators
# 🏙️ Calgary Urban Equity & Socioeconomic Indicator Analysis

An analytical study of Calgary's Equity Index (CEI), examining the relationships between working poverty, transit access, and part-time employment across Calgary's four city quadrants — using correlation analysis, regression modeling, and data visualization to surface neighbourhood-level socioeconomic disparities.

---

## 📌 Overview

This project explores the **Calgary Equity Index (CEI)**, a municipal dataset based on the WHO's Urban HEART framework, which measures socioeconomic inequality across Calgary's neighbourhoods. The analysis focuses on two core questions:

1. To what extent does working poverty align with adult low-income transit pass usage?
2. To what extent is working poverty linked to part-time or part-year employment?

Analysis was conducted at both the quadrant level (NW, NE, SE, SW) and city-wide to reveal where disparities are strongest and where policy intervention may have the most impact.

---

## 🔍 Key Findings

- **Strong link between working poverty and transit access** — a city-wide R value of 0.70 confirms that neighbourhoods with higher working poverty consistently show greater reliance on subsidized transit passes. The Northwest quadrant showed the strongest correlation.
- **Weak link between working poverty and part-time employment** — the relationship varies from negligible (SW) to moderate (NE), suggesting that deeper structural factors beyond employment type are at play.
- These findings point to transit policy as a meaningful lever in addressing socioeconomic inequality across the city.

---

## 🛠️ Tools & Methods

| Tool | Purpose |
|------|---------|
| Python | Core analysis language |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Scatter plots, bar charts, regression lines |
| Seaborn | Statistical visualizations |
| Correlation Analysis (R values) | Measuring strength and direction of relationships |
| Linear Regression | Modeling relationships between indicators |

---

## 📊 Socioeconomic Indicators Analyzed

- **Working Poor (Excluding Students %)** — Share of working-age adults (18–64) earning above $3,000 annually yet living below the Low-Income Measure after tax
- **Low-Income Transit Pass (Adult %)** — Percentage of adults utilizing subsidized transit passes
- **Part-Time or Part-Year Employment (%)** — Proportion of individuals employed mainly part-time or less than 48 weeks per year

---

## 🗺️ Methodology

- Data broken down at the neighbourhood level across four quadrants: **NW, SW, NE, SE**
- Correlation analysis (R values) used to measure the strength and direction of relationships between indicators
- Regression scatter plots produced for each quadrant and city-wide
- Results framed within the broader context of **Social Determinants of Health**

---

## 📁 Project Structure

```
calgary-urban-equity/
│
├── data/                   # Calgary Equity Index dataset (Open Calgary)
├── notebooks/              # Jupyter notebooks with analysis
├── visuals/                # Exported charts and plots
└── presentation.pdf        # Full project presentation
```

---

## 📄 Data Source

Calgary Equity Index - 2024 | Open Calgary
[https://data.calgary.ca/Demographics/Calgary-Equity-Index-2024/i6pu-a35d/about_data](https://data.calgary.ca/Demographics/Calgary-Equity-Index-2024/i6pu-a35d/about_data)

---

## 📋 Presentation

View the full project presentation [here](./presentation.pdf)

---

*Developed by Farhaz Kolathoor — Data Analytics, SAIT*
