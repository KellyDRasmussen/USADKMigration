# USADeepDive

A data dashboard exploring Syrian migration, employment, and naturalisation in Denmark (2008–2024), using public datasets from Statistics Denmark and JobIndats.dk

## 📦 Data Sources

### 👶 Population & Age Structure
- `FOLK1B`: Total population over time, disaggregated by age group

### 💼 Employment
-  Industries where Americans are employed
- Types of work permits associated with jobs

### 🌍 Net Migration Over Time
- `VAN1AAR_total_immigrations.csv`: Immigration totals (2007–2024)
- `VAN2AAR_total_emigrations.csv`: Emigration totals (2007–2024)
- `DKSTAT_nydanskere.csv`: Acquired Danish citizenships (1979–2024)

### 🗺️ Geographic Location (by Kommune)
- `VAN1AAR_kommunes.csv`: Immigration to Danish municipalities (2007–2024)
- `VAN2AAR_kommunes.csv`: Emigration from municipalities (2007–2024)


---
## 🧠 Notes

- All data is publicly available through [Statistikbanken.dk](https://www.statistikbanken.dk/) 
- Some dataset names refer to local filenames or saved queries
- See “Notes & Sources” in the dashboard for assumptions, caveats, and methodology

---

## 📊 Dashboard File

The main Power BI dashboard is included here:

**`usadk.pbix`** — Built in Power BI Desktop (April 2025)  
To explore or edit the dashboard, open this file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

This file includes:
- All visuals and pages (population, migration, employment, etc.)
- Custom measures, relationships, and slicers
- Embedded metadata and queries from the original source files
[📥 Download usadk.pbix](./usadk.pbix)




## 👋 Credits

Dashboard by Kelly Rasmussen | April 2025  
Not affiliated with any institution. Built for clarity and informed debate.
