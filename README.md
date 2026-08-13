# Cairo Real Estate Market Analysis & Interactive Power BI Dashboard

## 📌 Project Overview
This project presents an end-to-end data analysis and business intelligence solution for the **Greater Cairo Real Estate Market**. Utilizing a dataset of 5,578 apartment listings across Cairo, Giza, and surrounding districts, this interactive Power BI dashboard extracts actionable market insights, evaluates pricing dynamics, and highlights key factors influencing apartment valuations.

The dashboard serves real estate investors, developers, and potential home buyers by transforming raw market listings into intuitive visual analytics.

---

## 🛠️ Tech Stack & Tools
- **Business Intelligence & Visualization:** Power BI Desktop
- **Data Querying & Transformation:** Power Query (M Language)
- **Data Modeling & Analytics:** DAX (Data Analysis Expressions)
- **Data Preparation:** Python (Pandas, NumPy)
- **Documentation:** Markdown

---

## 📊 Key Performance Indicators (KPIs)
The dashboard header displays six core executive KPIs to give an instant overview of the market baseline:
1. **Avg Total Price (6.08M EGP):** Overall average listing price for apartments across Greater Cairo.
2. **Min Price Per Meter (4.17K EGP):** Baseline price per square meter in entry-level/budget segments.
3. **Max Price Per Meter (655.17K EGP):** Peak price per square meter in ultra-luxury/prime compounds.
4. **Avg Price Per Meter (42.99K EGP):** Market benchmark price per square meter.
5. **Avg Area (147.64 m²):** Average apartment size across the listings.
6. **Installment Share % (28.32%):** Percentage of listings offering payment plans vs. upfront cash.

---

## 📈 Visualizations & Chart Explanations

### **Page 1: Price Dynamics & Structural Features**

#### 1. Average Price/m² vs. Area (Scatter Line Chart with Trendline)
* **Purpose:** Analyzes the relationship between total apartment area ($m^2$) and unit price per meter.
* **Insights:** Features a downward trendline indicating the "economy of scale" principle in real estate — as apartment square footage increases, the average price per square meter decreases. Spikes highlight luxury boutique properties with small footprints but premium price points.

#### 2. Payment Method Distribution (Doughnut Chart)
* **Purpose:** Displays the proportion of payment options (Cash, Installments, or Cash/Installments hybrid).
* **Insights:** Provides market liquidity perspective by breaking down listings into payment flexibility categories, showing that cash transactions and hybrid options command significant market share alongside structured installments.

#### 3. Average Area vs. Average Price/m² (Combo Line & Bar Chart)
* **Purpose:** Evaluates unit size variations against average meter pricing.
* **Insights:** Highlights sweet-spot property configurations where area efficiency aligns with optimal valuation per meter.

---

### **Page 2: Location, Views, & Seller Behavior**

#### 1. Average Price/m² by Property View (Horizontal Bar Chart)
* **Purpose:** Measures the premium added by different view types (Nile View, Sea View, Pool, Garden, Main Street, Side Street).
* **Insights:** Quantifies the "View Premium" — **Nile View** commands the highest average price per meter at ~87K EGP, followed by **Sea/Lagoon View** (~62K EGP) and **Pool View** (~58K EGP), whereas **Side Street** listings sit at the lower baseline (~25K EGP).

#### 2. Top Locations by Valuation / Price per Meter (Horizontal Bar Chart)
* **Purpose:** Identifies prime real estate hotspots across Greater Cairo and major coastal developments listed (e.g., Marassi, Palm Hills, Marina West, ICity).
* **Insights:** Ranks premier developments and districts by overall listing value, guiding investors toward high-yield prime locations.

#### 3. Pricing & Payment Strategy by Seller Type (Clustered Column Chart)
* **Purpose:** Compares pricing strategies across four seller segments: Brokers, Compound Developers, Developers, and Private Owners across different payment methods.
* **Insights:** Shows how brokers and developers leverage installment structures to command higher pricing compared to direct private owners who favor cash transactions.

---

## 🎨 Design & UX
- **Branding & Theme:** Custom soft violet/lavender container theme with high-contrast electric blue KPI cards for maximum readability.
- **Navigation:** Page navigation arrows built into the top header for seamless multi-page interactivity.
- **Footer:** Personal branding banner (**MAhmoud Al-Sharqwai**).

---

## 🤝 Contact & Links
- **Portfolio:** [Cairo Real Estate Dashboard Portfolio](https://mahmoudal-sharqwai.journoportfolio.com)
- **LinkedIn Profile:** [Mahmoud Al-Sharqwai LinkedIn](https://www.linkedin.com/in/mahmoud-al-sharqwai )
