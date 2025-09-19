# **Enhancing Healthcare Accessibility in Nairobi**

## 📊 Report Snapshot (Power BI Dashboard)

<img width="896" height="504" alt="Image" src="https://github.com/user-attachments/assets/0c4a5122-16a9-4e10-99d9-6fbc47046849" />


---

## 🛑 Problem Statement

Nairobi, home to over 4 million residents, faces major disparities in healthcare accessibility:  

- **Uneven Distribution:** High-density sub-counties like Embakasi are underserved compared to others.  
- **Reliance on Private Sector:** 68% of facilities are private, creating affordability barriers.  
- **Limited After-Hours Care:** Only 24 facilities (22 private, 2 public) operate 24/7, leaving critical service gaps.  

---

## 🔍 Methodology & Dashboard Development

### **1. Data Collection**
- Sourced healthcare facility dataset (facility type, ownership, status, services, contacts).  
- Integrated **population data** (for demand analysis) and **geospatial data (lat/long)** for mapping.  

---

### **2. Data Cleaning & Preparation**
- **Handled missing values** in key columns (`Beds`, `Cots`, `Operational Status`, `Owner`, `Contact Info`).  
- **Created calculated fields**:  
  - `Ownership_Category` → Public vs Private.  
  - `Has_Contact_Info` → Binary indicator.  
  - `Operational_Binary` → 1 if operational, 0 if not.  
- Standardized categorical values (e.g., normalizing owner types).  
- Merged **population + facility data** at sub-county level to compute facility-per-population ratios.  

---

### **3. Data Modeling**
- Built relationships in **Power BI** between healthcare facility dataset, population dataset, and geospatial data.  
- Ensured consistency of sub-county identifiers across all datasets.  

<img width="826" height="419" alt="Image" src="https://github.com/user-attachments/assets/67330ff7-60d2-4309-beb3-77b8405e5cd1" />

---

### **4. Dashboard Development**
**Key Performance Indicators (KPIs):**  
- Total number of facilities.  
- % of operational facilities.  
- Beds and cots per facility type.  
- Facility-to-population ratios.  

**Visualizations:**  
- **Maps:** Spatial distribution of facilities (lat/long).  
- **Bar/Column Charts:** Beds, cots, and specialized services across ownership.  
- **Stacked Bar Charts:** Service availability (ART, FP, IPD, HBC, etc.).  
- **Slicers/Filters:** By sub-county, facility type, ownership, operational status.  

**Advanced Features:**  
- Highlighted **underserved areas** by overlaying population density with facility counts.  
- Indicators for **weekend and 24-hour facilities** to assess emergency readiness.  
- Binary contact info flag to evaluate communication accessibility.  

---

### **5. Hypothesis Testing**
Each visualization was designed to test specific questions:  
- Ownership vs. availability of specialized services (Public vs Private).  
- Operational hours (weekend/24-hour) vs. accessibility.  
- Facility distribution vs. population density.  
- Contact info availability vs. operational status.  

---

### **6. Insights**
- High-population areas (e.g., Embakasi) are **severely underserved**.  
- Public vs Private disparities in **bed capacity** and **service specialization**.  
- Facilities with proper **contact info** correlated with better operational accessibility.  
- Gaps in **youth and TB services** despite demographic demand.  

---

### **7. Recommendations**
- Expand **public facilities** in high-population, underserved areas.  
- Increase **24/7 facilities** and incentivize private-public partnerships.  
- Strengthen **digital/communication infrastructure** (contact info systems).  
- Invest in **specialized services** (maternal health, TB, youth care).  

---

## 📈 Impact & Results *(if implemented)*

- **Improved Health Outcomes:** Earlier diagnosis and treatment, reduced morbidity and mortality.  
- **Equitable Access:** Balanced public-private distribution ensures affordability.  
- **Emergency Readiness:** More 24/7 facilities reduce ER strain.  
- **Resilient System:** A stronger network for crisis response and public health programs.  

---

## 👩‍💻 Personal Contribution

I designed and implemented the **Power BI dashboard**, prepared and modeled the data, and translated findings into **policy-oriented recommendations**.  

This project directly supports **UN SDG 3 (Good Health and Well-being):**  
- **Target 3.8:** Achieve universal health coverage.  
- **Target 3.c:** Strengthen health workforce and financing in underserved areas.  

