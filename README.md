# Uber-Ride-Booking-Dashboard
Interactive Power BI dashboard analyzing Uber ride bookings, revenue, cancellations, vehicle performance, customer preferences, and monthly ride trends.





🎯 Project Objectives
The objective of this project is to analyze Uber ride-booking data using Power BI to identify trends in bookings, revenue, cancellations, vehicle demand, customer preferences, and operational performance, enabling data-driven business insights.
---

📁 Dataset used
<a  href="https://github.com/ManojKumarB17/Uber-Ride-Booking-Dashboard/blob/main/Uber_Ride_Booking_Dataset.xlsx">dataset</a>

📌 Dashboard KPIs
The dashboard contains the following key performance indicators:

1. Total Bookings
**500**
Represents the total number of ride bookings in the dataset.

2. Completed Rides
**287**
Represents the number of rides successfully completed.

3. Customer Cancelled Rides
**69**
Represents the number of rides cancelled by customers.

4. Total Distance
**5.73K km**
Represents the total distance covered across the rides.

5. Total Booking Value
**222.07K**
Represents the total value generated from the ride bookings.
---

📊 Dashboard Visualizations


1. Preferred Payment Methods

Chart Type
**Donut Chart**
Fields
- **Legend:** `Payment_Method`
- **Values:** Count of `Ride_ID`

Purpose
Shows the distribution of payment methods used by customers.
This helps identify the most commonly preferred payment options.
---

2. Bookings by Vehicle Type
Chart Type
**Clustered Column Chart**
Fields
- **X-axis:** `Vehicle_Type`
- **Y-axis:** Count of `Ride_ID`

Purpose
Compares the number of bookings across different vehicle types.
This helps identify which vehicle categories receive the highest demand.
---

3. Ride Booking Status Distribution
Chart Type
**Line Chart**
Fields
- **X-axis:** `Month`
- **Y-axis:** Count of `Ride_ID`

Purpose
Shows the monthly booking trend and helps identify periods of higher and lower ride demand.
---

4. Driver Ride Cancellation Reasons
Chart Type
**Horizontal Bar Chart**
Fields
- **Y-axis:** `Cancellation_Reason`
- **X-axis:** Count of `Ride_ID`

Purpose
Identifies the most common reasons for driver cancellations.

This can help the business understand operational problems such as:
- Car breakdown
- Vehicle problems
- Personal reasons
- Unable to reach pickup
- Traffic issues

---

5. Monthly Ride Bookings & Revenue Trend
Chart Type
**Line and Clustered Column Chart**
Fields
- **X-axis:** `Month`
- **Column Y-axis:** Total Bookings
- **Line Y-axis:** Total Booking Value

Purpose
Compares the number of bookings with the revenue generated each month.

This helps identify:
- High-demand months
- Revenue trends
- Changes in booking volume
- Relationship between bookings and revenue

---

🎛️ Interactive Filters

The dashboard contains interactive slicers for:

City
Allows users to analyze ride performance by city.

Vehicle Type
Allows comparison between different vehicle categories.

Booking Status
Allows users to analyze completed, cancelled, incomplete, and other booking statuses.

Month
Allows users to analyze ride performance for a specific month.

Payment Method
Allows analysis of customer payment preferences.

Booking Date
Allows users to select a specific date range.
---
💡 Project Insights
The analysis provides insights into ride demand, booking completion, customer cancellations, vehicle preferences, payment behavior, operational issues, and revenue trends. These insights can help identify areas for improving ride completion, reducing cancellations, and optimizing overall booking performance.

🏁 Conclusion
The Uber Ride Booking Dashboard provides a clear view of bookings, revenue, cancellations, vehicle demand, and customer preferences using Power BI, helping businesses make data-driven decisions.
