# Healthcare Data Analysis Dashboard

Interactive Tableau dashboard analyzing **patient demographics, seasonal disease patterns, and healthcare system efficiency** across a private healthcare provider. The project helps management anticipate demand, allocate resources effectively, and improve patient experience.

---

## 📊 Project Overview
This project analyzes healthcare appointment and patient data across **34 states, 13,247 patients, and 13,599 appointments (2023–2025)**. The dashboard highlights:
- **System overview & demographics** – Who are the patients, and how do they use the system?
- **Disease patterns & seasonal trends** – What conditions spike during certain seasons?
- **Operational efficiency** – How long do patients spend with providers, and how long do lab results take?

🔗 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/shared/JQD3BZ83T?:display_count=n&:origin=viz_share_link)

---

## 🗂 Dataset
- **Scope**: 34 states, 13,247 patients, 13,599 appointments
- **Dimensions**: demographics (age, gender, race), payer type, reasons for visits, diagnoses, provider specialty, lab wait times
- **Tools**: Tableau (visualization), SQL (data prep), Excel

---

## 📌 Dashboard Features & Insights

### 1. System Overview & Patient Demographics
- Operated in 34 states, concentrated in **Texas, California, Florida, and New York**.
- **Private insurance + Medicare** dominate payment methods.
- Appointments peaked at **1,075/month in Jan 2025**, above the baseline of 618.
- Patients are majority **White (75%)**, with distinct visit reasons by race.
- Balanced gender split (7,057 women, 6,190 men); most common age group: **45–64 years**.

![System Overview](./images/system_overview.jpg)

![Demographics](./images/demographics.png)

---

### 2. Disease Patterns & Seasonal Trends
- **Bronchitis & depressive disorder** spike in winter/fall → implications for staffing & medication planning.
- Seasonal disease impact varies across states, affecting department capacity and drug needs.
- Repeat visits highlight chronic conditions → opportunity to improve follow-ups.

![Seasonal Disease](./images/seasonal_disease.png)
![Repeat Patients](./images/repeat_patients.png)

---

### 3. Operational Efficiency: Provider & Lab Times
- **Time with providers** varies by specialty: Ophthalmology (33h), Allergy (31h) vs. Pediatrics (16h).
- Geographic differences: Minnesota providers average **31h**, while Kansas averages **15h**.
- **Lab result turnaround** varies by state and demographics; New Jersey has the longest delays.
- High-volume departments (Internal Medicine, Pulmonology) face longer processing times.

![Provider Efficiency](./images/provider_time.png)
![Lab Results](./images/lab_results.png)

---

## 🔑 Key Takeaways
- Monthly appointments surged in 2024–25, suggesting rising demand and need for scalable staffing.
- Seasonal spikes in respiratory and psychiatric conditions require **drug stock planning** and **department staffing adjustments**.
- Efficiency gaps across states and demographics highlight opportunities for **resource reallocation**.

---

## 🚀 How to Use
1. Explore the dashboard on Tableau Public → filter by state, disease, payer type.
2. Use demographic filters to drill into patient subgroups.
3. Compare seasonal patterns and efficiency metrics to identify bottlenecks.

---

## 📎 Resources
- [Interactive Dashboard (Tableau Public)](https://public.tableau.com/shared/JQD3)
- [Project Repository (GitHub)](link-to-your-repo)

---

✍️ * Duke University - Data Visualization Team - Team 58: Moshu Huang, David Chang, Jamie Fobel, Lydia Luo, Jessica Liang*
