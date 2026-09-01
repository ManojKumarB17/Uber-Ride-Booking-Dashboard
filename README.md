# Uber-Ride-Booking-Dashboard
Interactive Power BI dashboard analyzing Uber ride bookings, revenue, cancellations, vehicle performance, customer preferences, and monthly ride trends.

# 🚗 Uber Ride Booking Dashboard | Power BI

## 📊 Project Overview

The **Uber Ride Booking Dashboard** is an interactive Power BI data analytics project designed to analyze ride bookings, customer behavior, vehicle performance, cancellations, payment preferences, and revenue trends.
The dashboard transforms raw ride-booking data into meaningful business insights using interactive visualizations, KPIs, filters, and trend analysis.
This project demonstrates how **Power BI can be used to clean, analyze, visualize, and communicate business data effectively.**
---

## 🎯 Project Objectives
The main objectives of this project are:
- Analyze overall ride booking performance
- Track completed and cancelled rides
- Understand ride booking trends over time
- Analyze revenue and booking value
- Compare different vehicle types
- Identify major driver cancellation reasons
- Understand customer payment preferences
- Analyze ride distance
- Study booking status distribution
- Identify patterns in monthly ride demand
---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| **Power BI** | Data visualization and dashboard development |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and KPI calculations |
| **Excel** | Source dataset |
| **GitHub** | Project documentation and portfolio |

---

## 📁 Dataset Information
The dataset contains **500 ride booking records** and **18 columns**.

### Dataset Columns
| Column | Description |
|--------|-------------|
| `Ride_ID` | Unique ID of each ride |
| `Booking_Date_Time` | Date and time when the ride was booked |
| `Customer_Name` | Customer name |
| `Driver_Name` | Driver name |
| `City` | City where the ride was booked |
| `Vehicle_Type` | Type of vehicle used |
| `Booking_Status` | Current status of the booking |
| `Booking_Value` | Total booking value |
| `Ride_Distance_km` | Distance travelled in kilometers |
| `Payment_Method` | Payment method used |
| `Cancellation_Reason` | Reason for cancellation |
| `Incomplete_Reason` | Reason for incomplete ride |
| `Driver_Rating` | Rating given to the driver |
| `Customer_Rating` | Rating given by the customer |
| `Booking_Date` | Booking date |
| `Month` | Booking month |
| `Month_Number` | Numerical month used for sorting |
| `Hour` | Booking hour |

---

# 📌 Dashboard KPIs
The dashboard contains the following key performance indicators:

### 1. Total Bookings
**500**
Represents the total number of ride bookings in the dataset.

### 2. Completed Rides
**287**
Represents the number of rides successfully completed.

### 3. Customer Cancelled Rides
**69**
Represents the number of rides cancelled by customers.

### 4. Total Distance
**5.73K km**
Represents the total distance covered across the rides.

### 5. Total Booking Value
**222.07K**
Represents the total value generated from the ride bookings.
---

# 📊 Dashboard Visualizations

## 1. Preferred Payment Methods

### Chart Type
**Donut Chart**
### Fields
- **Legend:** `Payment_Method`
- **Values:** Count of `Ride_ID`

### Purpose
Shows the distribution of payment methods used by customers.
This helps identify the most commonly preferred payment options.
---

## 2. Bookings by Vehicle Type
### Chart Type
**Clustered Column Chart**
### Fields
- **X-axis:** `Vehicle_Type`
- **Y-axis:** Count of `Ride_ID`

### Purpose
Compares the number of bookings across different vehicle types.
This helps identify which vehicle categories receive the highest demand.
---

## 3. Ride Booking Status Distribution
### Chart Type
**Line Chart**
### Fields
- **X-axis:** `Month`
- **Y-axis:** Count of `Ride_ID`

### Purpose
Shows the monthly booking trend and helps identify periods of higher and lower ride demand.
---

## 4. Driver Ride Cancellation Reasons
### Chart Type
**Horizontal Bar Chart**
### Fields
- **Y-axis:** `Cancellation_Reason`
- **X-axis:** Count of `Ride_ID`

### Purpose
Identifies the most common reasons for driver cancellations.

This can help the business understand operational problems such as:
- Car breakdown
- Vehicle problems
- Personal reasons
- Unable to reach pickup
- Traffic issues

---

## 5. Monthly Ride Bookings & Revenue Trend
### Chart Type
**Line and Clustered Column Chart**
### Fields
- **X-axis:** `Month`
- **Column Y-axis:** Total Bookings
- **Line Y-axis:** Total Booking Value

### Purpose
Compares the number of bookings with the revenue generated each month.

This helps identify:
- High-demand months
- Revenue trends
- Changes in booking volume
- Relationship between bookings and revenue

---

# 🎛️ Interactive Filters

The dashboard contains interactive slicers for:

### City
Allows users to analyze ride performance by city.

### Vehicle Type
Allows comparison between different vehicle categories.

### Booking Status
Allows users to analyze completed, cancelled, incomplete, and other booking statuses.

### Month
Allows users to analyze ride performance for a specific month.

### Payment Method
Allows analysis of customer payment preferences.

### Booking Date
Allows users to select a specific date range.
---

