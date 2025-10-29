# 💼 AI-Assisted Financial Performance Dashboard

An interactive **Financial Performance Dashboard** project that integrates **data visualization** and **AI-generated insights** — built to simulate the real-world work of a **Program Analyst (Finance)** at a company like Wells Fargo.

---

## 🧭 Project Overview

This project demonstrates how financial analysts can combine **no-code analytics** tools (Google Sheets + Looker Studio) with **AI technologies (Google AI Studio / Gemini)** to produce smart, automated reporting.

The dashboard visualizes key financial metrics such as:
- **Departmental Budgets vs Actual Spend**
- **Variance and Efficiency Trends**
- **Process Time vs Performance**
- **AI-Generated Executive Summaries**

The result is a professional, web-based financial dashboard that delivers both **visual clarity** and **analytical intelligence**.

---

## 🏗️ Project Architecture

| Component | Tool Used | Purpose |
|------------|------------|----------|
| Data Source | Google Sheets | Stores raw financial data (Budget, Actual, Variance%, etc.) |
| Visualization | Looker Studio (Google Data Studio) | Creates interactive visual dashboards |
| AI Insights | Google AI Studio (Gemini) | Generates executive summaries and recommendations |
| Web Hosting | Google Sites / HTML Dashboard | Publishes the interactive dashboard online |

---

## 🧰 Tech Stack

- **Google Sheets** → data preparation & cleaning  
- **Google Looker Studio** → dashboard creation  
- **Google AI Studio (Gemini)** → AI-generated insights  
- **HTML, CSS, JavaScript** → web-based dashboard (optional version)  
- **Chart.js** → front-end chart rendering  
- **Google Sites / GitHub Pages** → deployment

---

## 📊 Features

✅ Real-time visualization of **Budget vs Actuals**  
✅ **Variance analysis** across departments and months  
✅ **Interactive filters** for departments and time periods  
✅ **AI-powered narrative insights** generated via Google Gemini  
✅ Clean, responsive **web dashboard layout** (HTML/JS version)  
✅ Ready-to-present format for **program analyst portfolios**

---

## 🧮 Sample Dataset Structure

| Department | Month | Budget | Actual | Variance% | ProcessTimeDays |
|-------------|--------|--------|--------|------------|----------------|
| Marketing | Jan | 55,000 | 59,000 | 0.0727 | 8 |
| Sales | Jan | 70,000 | 72,500 | 0.0357 | 7 |
| HR | Jan | 40,000 | 39,000 | -0.025 | 5 |
| IT | Jan | 47,000 | 54,000 | 0.15 | 10 |
| Finance | Jan | 65,000 | 64,000 | -0.015 | 6 |

---

## 🤖 AI Studio Prompt Used

```text
You are a financial program analyst. Based on the following dataset, write a short executive summary (3–5 sentences) describing:
1. Which departments spent over their budget (positive variance%)
2. Which departments were under budget (negative variance%)
3. What overall trend do you notice in process efficiency (ProcessTimeDays)
4. One actionable recommendation to improve financial control.
Keep your response professional, concise, and easy to include in a report dashboard.
