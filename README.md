
# 🏨 Hotel Booking Dashboard

This project presents an interactive **Hotel Booking Dashboard** built using **Excel**, **Python**, **Power BI**, and **DAX**, offering deep insights into guest behavior, revenue generation, and country-specific trends.

---

## 🎯 Objective

To analyze hotel booking data and extract actionable insights regarding:

- Booking behavior by hotel type and country  
- Customer segments and room/meal preferences  
- Revenue trends and cancellation impact  
- Comparison between City and Resort hotels  
- Monthly KPIs and distribution channel performance

---

## 🛠 Tools & Technologies

| Tool        | Purpose                                 |
|-------------|------------------------------------------|
| Excel       | Initial formatting, handling missing data |
| Python (`pandas`, `matplotlib`, `seaborn`) | EDA and visualizations |
| Power BI    | Dashboard creation and interactivity |
| DAX         | Custom KPIs and business logic |

---

## 🧹 Data Cleaning

The dataset required extensive cleaning, including:

- Filling missing values for guest numbers, booking features, and pricing
- Removing duplicate rows
- Fixing inconsistent data types and formatting
- Standardizing hotel type, room categories, and channel names

---

## 📊 Dashboard Pages

### 1️⃣ Overview Dashboard

**Purpose**: High-level summary of guest demographics and booking behavior.

**Key Components**:
- KPIs: Total Reservations, Confirmed, Cancelled, Adults, Children, Babies
- Booking Type: Transient, Group, Contract
- Visuals:  
  - Booking Changes vs Customer Type  
  - Weekend Stay vs Adults  
  - Room Type Popularity  
  - Monthly Guest and Reservation Trends  

> This dashboard helps identify general trends in guest types and seasonal changes.

---

### 2️⃣ Revenue Dashboard *(Dynamic Visualization)*

This dashboard dynamically adjusts based on selected **Hotel Type**:

#### ▶️ If "City Hotel" is selected:
- City Hotel image
- Revenue = $5.93M | Confirmed = $4M | Cancelled = -$2M  
- Monthly Revenue vs Cancelled Loss (bar)
- Revenue by Customer Type & Meal
- Distribution Channels and Market Segments (bar)
- Monthly Revenue Trend (area chart)

#### ▶️ If "Resort Hotel" is selected:
- Resort Hotel image
- Revenue = $3.36M | Confirmed = $2M | Cancelled = -$947K  
- Similar visuals, but filtered by resort data only

#### 🔄 If no hotel type is selected:
- Comparative image + merged KPIs
- Helps understand overall performance contrast between the two hotels

**All visuals respond to slicers:**
- Hotel Type | Year | Meal | Room Type | Channel | Customer Type | Segment

---

### 3️⃣ Guests Country Dashboard

**Goal**: Analyze guest origin, pricing, and cancellations geographically.

**Visuals**:
- KPIs: Countries = 177 | Reservations = 87K | Cancelled = 24K | Revenue = $9.29M
- Total Reservations by Country (Bar)
- Cancelled Reservations by Country (Bar)
- Revenue by Country (Map)
- Top 15 & Bottom 15 Countries by Revenue
- Avg. Room Price by Country (Scatter)

**Filters**: Hotel Type, Country, Channel, Segment, Customer Type, Room, Date Range

---

## 📂 Folder Structure

```
hotel-booking-dashboard/
├── data/                  # Raw and cleaned datasets
├── eda/                   # Python notebooks for EDA
├── dashboard/             # Power BI (.pbix) file
├── visuals/               # Dashboard screenshots
└── README.md              # Project documentation
```

---

## 👨‍💻 Author

**Mahmoud Mohamed Fawzy Elzayat**  
📧 mahmoudelzeiat7@gmail.com  
📞 01044293980  
🔗 [LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)  
🐙 [GitHub](https://github.com/M-Elzayat)

---

## 📊 Dataset

Dataset from:  
[Kaggle – Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

---

## 📄 License

Creative Commons BY-NC-ND 4.0  
© Mahmoud Elzayat, 2025 — All rights reserved.
