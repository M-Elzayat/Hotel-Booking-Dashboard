# 🏨 Hotel Booking Dashboard

This project provides an interactive dashboard and exploratory data analysis (EDA) of hotel booking data. Using **Excel**, **Python**, **Power BI**, and **DAX**, the project uncovers patterns in booking behavior, guest demographics, cancellations, revenue distribution, and more.

## 🎯 Project Objective

To analyze hotel booking data and extract key insights related to:

- Booking trends by country  
- Hotel type comparison (City Hotel vs Resort Hotel)  
- Guest demographics (adults, children, babies)  
- Booking types and customer segments  
- Room preferences and average daily rates  
- Cancellations vs confirmed bookings  
- Revenue analysis by channel, segment, and time  
- Meal types distribution  
- **Booking changes by customer type**  
- **Relation between weekend stays and number of adults**  
- **Link between room changes and booking type shifts**

## 🛠️ Tools & Technologies

| Tool        | Purpose                                 |
|-------------|-----------------------------------------|
| Excel       | Initial data exploration and formatting |
| Python (`pandas`, `matplotlib`, `seaborn`) | Data cleaning and visualization |
| Power BI    | Interactive dashboard design            |
| DAX         | Custom measures, KPIs, and calculations |

## 🧪 Data Cleaning & Challenges

Several data quality issues were addressed:
- **Missing values**: Handled empty records in guest counts and booking info.
- **Duplicates**: Removed repeated rows to ensure clean insights.
- **Incorrect data types**: Standardized columns such as dates, numbers, and categories.

## 📊 Exploratory Data Analysis

Python was used to perform visual analysis and uncover key trends:
- Top and bottom countries by number of bookings
- Guest distribution (adults, children, babies)
- Room type preferences and pricing trends
- Cancellation behavior across booking types

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

Visualizations were created using `matplotlib` and `seaborn`.

## 📈 Power BI Dashboard

The dashboard is divided into four main pages:

1. **Home** – Project summary and KPIs  
2. **Booking Overview** – Booking trends, hotel comparison, guest breakdown  
3. **Reservation Details** – Revenue, market segments, cancellations  
4. **Table Details** – Raw data view and filters  

### 📌 DAX Measures Used

Custom KPIs were built to enhance analysis:

- `Adult count`, `Babies count`, `Children count`
- `Total Guests`, `Total Reservations`, `Total Revenue`
- `Average Room Rate`, `Avg Lead Time`, `Cancelled Reservations`
- Image-based fields: `Hotel_img`, `room picture`, `Family img`, `Gif`...

## 📂 Folder Structure

```
hotel-booking-dashboard/
├── data/                  # Raw and cleaned dataset
├── python-analysis/       # EDA scripts and charts
├── dashboard/             # Power BI (.pbix) file
└── README.md              # Project documentation
```

## 🔍 Dataset

The dataset used is publicly available on [Kaggle – Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

## 📬 Author

**Mahmoud Mohamed Fawzy Elzayat**  
[🔗 LinkedIn](https://www.linkedin.com/in/mahmoud-elzayat-data-analysis)

## License

This project is licensed under the Creative Commons BY-NC-ND 4.0 License.  
© Mahmoud Elzayat, 2025 — All rights reserved.
