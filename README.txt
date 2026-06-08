# EcoTrace
# 🌍 EcoTrace: Carbon Footprint Awareness Platform


**[Challenge 3] Carbon Footprint Awareness Platform**

## 🧠 Approach and Logic
EcoTrace is built as a lightweight, single-page application (SPA) designed to help users calculate, visualize, and reduce their carbon footprint. The logic is divided into four sequential steps:
1.  Contextual Input: Users input lifestyle data across Transport, Energy, Food, and Lifestyle.
2.  Algorithmic Calculation: The system uses standard emission factors to convert user habits into annual CO₂e (Carbon Dioxide Equivalent) tonnage.
3.  Visual Dashboard: Native Chart.js integration dynamically renders the user's data against national and global benchmarks.
4.  Actionable Intelligence: Based on the highest emission categories, the platform filters and presents tailored, evidence-based mitigation strategies.

## ⚙️ How the Solution Works
* Architecture: Pure HTML, CSS, and Vanilla JavaScript. No heavy backend or complex build tools, ensuring the repository remains highly efficient and easily under the 10 MB limit.
* Data Persistence: Uses the browser's `localStorage` to save historical calculations, allowing users to track their environmental progress over time without needing a centralized database.
* Responsive Design: CSS Grid and Flexbox are utilized to ensure the platform is fully accessible and usable on both mobile devices and desktop monitors.

## 🤔 Assumptions Made
* Calculations are based on generalized, standard lifecycle emission factors for awareness and educational purposes, rather than hyper-localized exact scientific metrics.
* Global and national averages used in the comparison charts are set to standard benchmarks (e.g., Global average ~4.7t, India average ~7.5t).
* Users have a rough estimation of their weekly/monthly habits (e.g., commute distance, energy bill).
