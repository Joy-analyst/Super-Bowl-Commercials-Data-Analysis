```markdown
# 🏈 Super Bowl Commercials Data Analysis

## 📘 Project Overview
This project analyzes Super Bowl commercials over the years to uncover insights about advertising trends, audience engagement, and the factors that drive successful ads. Using the dataset containing variables such as **brand**, **ad type**, **estimated cost**, **YouTube views**, and **likes**, this analysis identifies what makes a Super Bowl commercial stand out.

---

## 🎯 Objectives
- Identify the brands that invest the most in Super Bowl advertising.  
- Analyze which ad characteristics (funny, celebrity, patriotic, animals, etc.) lead to higher engagement.  
- Examine the relationship between ad cost and audience reach.  
- Calculate engagement rate to measure ad effectiveness.  
- Visualize key trends over time using pivot tables and charts.

---

## 📊 Dataset Description
| Column | Description |
|---------|-------------|
| **Year** | Year of the Super Bowl commercial |
| **Brand** | Company/Brand name |
| **Funny, Celebrity, Patriotic, Danger, Animals, Uses Sex** | Binary indicators showing ad characteristics |
| **Length** | Duration of the ad (seconds) |
| **Estimated Cost** | Approximate cost of the ad in millions |
| **YouTube Views** | Number of views on YouTube |
| **YouTube Likes** | Number of likes on YouTube |
| **TV Viewers** | Number of people who viewed the ad on TV |

---

## 📈 KPIs
- **Total Number of Ads**  
- **Average Estimated Cost per Ad**  
- **Average YouTube Views per Ad**  
- **Average YouTube Likes per Ad**  
- **Engagement Rate (Likes ÷ Views)**  
- **Top Performing Brand by Engagement**  
- **Most Common Ad Type (Funny, Celebrity, etc.)**

---

## 📑 Pivot Tables Used
1. **Brand Performance Summary** – compares ad count, average cost, and engagement.  
2. **Content Type Effectiveness** – analyzes ad features vs. YouTube views and likes.  
3. **Yearly Trend Analysis** – tracks changes in spending and audience engagement.  
4. **Cost vs. Engagement** – evaluates correlation between investment and performance.  
5. **Ad Length Impact** – checks how duration influences engagement.

---

## 🎨 Visualizations
- **Bar Chart:** Average YouTube Views per Brand  
- **Pie Chart:** Distribution of Ad Types  
- **Line Chart:** Estimated Cost Trends Over the Years  
- **Scatter Plot:** Estimated Cost vs. YouTube Views  
- **Bubble Chart:** Views vs. Likes vs. Cost (Engagement Visual)

---

## 🎨 Color Palette
| Purpose | Color | Hex Code |
|----------|--------|----------|
| Primary | Royal Blue | `#0052CC` |
| Accent 1 | Bright Orange | `#FF8C00` |
| Accent 2 | Lemon Yellow | `#FFD700` |
| Neutral | Light Gray | `#EAEAEA` |

---

## 🧮 Engagement Rate Formula
```

Engagement Rate = YouTube Likes / YouTube Views

```

**Example:**  
If an ad has 13,615 views and 84 likes →  
`84 / 13,615 = 0.00617 = 0.62%`

---

## 🧠 Key Insights
- Funny and celebrity-featured ads tend to get higher engagement.  
- There’s not always a direct link between higher spending and higher engagement.  
- Some brands maintain consistent performance across multiple years.  
- Engagement rates are generally below 1%, emphasizing the competitive nature of Super Bowl ads.

---

## 🛠️ Tools Used
- **Microsoft Excel** – Data cleaning, pivot tables, KPIs, and charts.  
- **Power BI** *(optional)* – Interactive dashboard creation.  
- **Python (Pandas, Matplotlib)** *(optional)* – Further analysis and visualization.

---

## 📂 Repository Structure
```

SuperBowl-Commercials-Analysis/
│
├── data/
│   └── superbowl_ads_dataset.xlsx
│
├── visuals/
│   ├── Brand_Performance.png
│   ├── Yearly_Trend.png
│   └── Engagement_Rate.png
│
├── analysis/
│   └── Superbowl_Commercials_Analysis.xlsx
│
├── README.md
└── LICENSE

```

---

## 🧾 License
This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Author
**Joy Uko**  
*Data Analyst & Data Scientist*  
📧 [Your Email Here]  
🔗 [LinkedIn Profile](#) | [GitHub Profile](#)
```
