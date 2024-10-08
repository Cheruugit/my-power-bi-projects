# Nairobi Healthcare Accessibility - Data-Driven Analysis and Recommendations


## Problem Statement

Improving access to healthcare services is essential for better health outcomes and overall well-being, particularly in rapidly growing urban areas like Nairobi County. The existing healthcare infrastructure faces immense strain due to population growth, making essential medical care inaccessible to many residents. In this project, we analyze healthcare accessibility in Nairobi and propose data-driven strategies to improve equitable access across all constituencies.

This study aligns with Sustainable Development Goal 3 (SDG 3), which aims to ensure healthy lives and promote well-being for all by providing affordable and accessible healthcare services.

### Objective
To assess the current state of healthcare accessibility across Nairobi’s constituencies and propose targeted strategies to improve equitable access to healthcare facilities, beds, cots, and specialized services such as maternity and emergency care.

The study focuses on:

   - Highlighting disparities in healthcare resources across different constituencies.
   - Recommending strategies to bridge the gap between underserved and affluent areas.
   - Aligning the proposed recommendations with the principles of Universal Health Coverage (UHC) under SDG 3.

### Steps followed 

 - Step 1: Data Collection.

    - Population Data: Derived from the 2019 Kenya Census.
   - Healthcare Facility Data: Sourced from Kenya`s government platform like Kenya.gov.

- Step 2: Data Loading.
    - Loaded the Nairobi Population and Healthcare Facilities datasets into Power BI. This included facility information such as ownership (public/private), services provided, number of beds, and cots.

- Step 3 : Data Cleaning and Preparation
Loaded Data into Power BI Desktop, ensuring that all data sources were correctly imported.

Cleaned the Data:
   - Removed errors and duplicates.
   - Updated data types to ensure consistency.
   - Addressed missing values, standardized constituency names, and verified the facility types.

- Step 4: Data Modeling
   - Created relationships between the population dataset and the healthcare facilities data:
     - One-to-Many Relationship: Between constituencies' population data and healthcare facilities.
     - One-to-One Relationship: Between latitude/longitude of health points to map facilities accurately.

- Step 5:  Hypotheses Tested
  - Do high-population areas have fewer healthcare facilities?
   - Are public healthcare facilities more likely to have fewer beds and cots compared to private facilities?
   - Are certain services, such as maternity or emergency care, less available in specific regions?
    - Are facilities with 24-hour and weekend services better distributed in high-population areas?
    - Are more beds and cots available in healthcare facilities located in wealthier areas?

- Step 6: Data Visualization
   - Created Heatmaps showing the distribution of healthcare facilities across constituencies.
    - Bar charts comparing public vs. private ownership of facilities.
    - Pie charts visualizing facility ownership breakdown.
    - Tables and charts comparing the number of beds and cots between public and private healthcare facilities.

- Step 7: Gap Identification
    - Constituencies like Mathare, Kibra, and Kamukunji have a high population density but fewer healthcare facilities, exacerbating access issues.
    - Wealthier areas, such as Westlands and Dagoretti North, have better access to healthcare services, indicating socioeconomic disparities.

- Step 8: The report was then published to Power BI Service.

 # Report Snapshot (Power BI DESKTOP)

   ![Screenshot (167)](https://github.com/user-attachments/assets/6385a0ab-2f2c-461f-bf64-4fdd7c5b303d)


# Key Insights
Following inferences can be drawn from the dashboard;
-  Limited Healthcare Access in High-Density Areas: Mathare, Kibra, and Kamukunji, despite high population densities, have fewer healthcare facilities, leading to inadequate access to services.

- Better Coverage in Certain Areas: Constituencies like Kasarani, Embakasi, and Starehe have more healthcare facilities, ensuring better access.

- Imbalance in Facility Ownership: Public facilities (68%) dominate, but private facilities, though fewer (32%), offer fewer resources, indicating specialization or smaller operations.

- Gaps in Emergency and Maternity Services: Constituencies like Roysambu and Embakasi North have less than 5% of facilities offering emergency services. Maternity care is notably scarce in Starehe (6.57%).

- Resource Disparity in Wealthier Areas: Westlands and Dagoretti North have more beds and cots, reflecting a correlation between wealth and healthcare resources.

# Recommendations in Alignment with SDG3 "Good Health and Well-Being"
Increase Healthcare Facilities in High-Density Areas (Target 3.8): By 2030, expand the number of public healthcare facilities in underserved constituencies like Mathare, Kibra, and Kamukunji to improve access and ensure universal health coverage.

Improve Emergency and Maternity Services (Target 3.1 and 3.8): Increase emergency and maternity service availability by 2030, particularly in Roysambu and Starehe, to reduce maternal mortality and ensure emergency healthcare services are accessible.

Strengthen Public-Private Partnerships (Target 3.8): Foster collaborations between public and private healthcare sectors to increase resource allocation and improve service delivery, with a focus on underserved areas.

Equitable Resource Distribution (Target 3.8): Ensure equitable distribution of healthcare resources such as beds and cots across all constituencies by 2030, focusing on high-density, low-income areas to provide fair access to essential health services.

Expand Community Health Services (Target 3.8): By 2030, invest in mobile and community health services to extend healthcare access to remote or underserved regions, addressing disparities in service availability.

Enhance Health Insurance Coverage (Target 3.8): Strengthen health insurance programs to ensure financial protection for vulnerable populations, reducing out-of-pocket healthcare costs and promoting broader access to quality services.
