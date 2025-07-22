# 📊 NYC 311 Complaint Analytics Dashboard (Live Data)

This Power BI dashboard provides real-time analytics of 311 complaints registered in New York City. The data is fetched live from the NYC Open Data API, making the dashboard dynamic and constantly up-to-date.

---

## 🎯 Objective

To track and analyze public complaints submitted through NYC’s 311 service in real-time to assist decision-makers in improving service response and community satisfaction.

---

## 🧩 Data Source

- **API**: [NYC Open Data 311 Complaints](https://data.cityofnewyork.us/resource/erm2-nwe9.json)
- Format: JSON
- Data Limit: 10,000 records (auto-refreshable)

---

## ⚙️ Technologies Used

- **Power BI** (for dashboard development and publishing)
- **NYC Open Data API** (for live data fetching)
- **Power Query Editor** (for real-time transformation)
- **Data Gateway + Power BI Service** (for refresh scheduling)

---

## 📌 Key Features

- Live data connection via Web API
- Complaint analysis by Borough, Type, Hour, Day
- SLA performance tracking (Resolution within 48h)
- Filterable by complaint type and location
- Trend insights over time
- Refreshable with a single click or auto-schedule

---

## 📈 KPIs

- Total Complaints
- Average Resolution Time (hours)
- Top Complaint Types
- Status Distribution (Open, Closed, etc.)

---

## 👥 Stakeholders

- NYC Government Agencies
- Data Analysts & Public Officials
- Residents & Local Communities
- Emergency Response & City Management Teams

---

## 🔁 Live Data Refresh

### 🔹 Before Refreshing:
<img width="1877" height="762" alt="Screenshot 2025-07-22 193712" src="https://github.com/user-attachments/assets/2bf63e79-4012-40d6-a99c-7dee04eb0f5c" />

### 🔹While Refreshing;
<img width="1834" height="735" alt="Screenshot 2025-07-22 193728" src="https://github.com/user-attachments/assets/34910173-a6fc-4fa0-a8ab-fcdafef16002" />


### 🔹 After Refreshing:
<img width="1876" height="746" alt="Screenshot 2025-07-22 194314" src="https://github.com/user-attachments/assets/c7a8275a-8cb1-4978-bae1-69f9fdfdb178" />


📌 Note: Dashboard reflects real-time status once **Refresh** is clicked in Power BI Desktop or is set up on a schedule in the **Power BI Service**.

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI
2. Click on **Refresh** to pull the latest 311 complaints
3. Interact with filters to slice data by borough, complaint type, or hour
4. Optionally, publish to Power BI Service and configure refresh frequency

---

## 📝 License

Open-source project under MIT License.  
Data source is publicly available through NYC Open Data.

---

