# OLA-DashX 📊

**A Data Analyst Project by Sheel Ganvir**

---

## 📌 Project Overview

**OLA-DashX** is a complete data analytics case study that simulates a ride-booking platform similar to OLA. This project leverages SQL for data extraction and Power BI for data visualization. The objective is to gain insights into booking patterns, cancellations, ratings, revenue, and customer behavior.

---

## 💾 Tech Stack

- **SQL** – Data analysis and extraction
- **Power BI** – Interactive dashboard visualizations
- **Excel/CSV** – Dataset storage and import

---

## 🧠 Key Insights & Objectives

This project answers various business questions using SQL and visualizes them using Power BI. Key areas covered include:

### 🔎 SQL-Based Questions

1. Retrieve all successful bookings
2. Average ride distance per vehicle type
3. Total number of cancelled rides by customers
4. Top 5 customers by number of rides
5. Rides cancelled by drivers due to personal/car issues
6. Max & Min driver ratings for Prime Sedan
7. Rides paid via UPI
8. Average customer rating per vehicle type
9. Total booking value of successful rides
10. Incomplete rides with reasons

### 📊 Power BI Dashboard Views

- **Overall**: Ride volume over time, Booking status breakdown  
- **Vehicle Type**: Top 5 vehicle types by distance, Ratings  
- **Revenue**: Payment method-wise revenue, Top customers  
- **Cancellation**: Reasons for cancellations (customer & driver)  
- **Ratings**: Distribution and comparison between customer and driver ratings  

---

## 🧮 Data Columns

| Column | Description |
|--------|-------------|
| Date | Booking date |
| Time | Booking time |
| Booking_ID | Unique ID for each booking |
| Booking_Status | Success, Cancelled by Customer/Driver |
| Customer_ID | Unique customer identifier |
| Vehicle_Type | Type of vehicle (e.g., Mini, Prime Sedan) |
| Pickup_Location | Starting point of the ride |
| Drop_Location | Destination of the ride |
| V_TAT / C_TAT | Turnaround time for vehicle/customer |
| cancelled_Rides_by_Customer / Driver | Reason for cancellation |
| Incomplete_Rides | Yes/No |
| Incomplete_Rides_Reason | Reason if ride is incomplete |
| Booking_Value | Fare amount |
| Payment_Method | UPI, Cash, Card |
| Ride_Distance | Distance in KM |
| Driver_Ratings / Customer_Rating | Feedback scores |

---

## 📷 Power BI Dashboard Preview

![image](https://github.com/user-attachments/assets/df227341-8d43-477f-9eda-ddee602d179d)

---

## 📁 Folder Structure

```bash
OLA-DashX/
│
├── SQL Queries/
│   └── All SQL views and queries used
│
├── PowerBI Dashboard/
│   └── .pbix file of the report
│
├── Dataset/
│   └── Bookings data in .csv/.xlsx
│
├── Documentation/
│   └── OLA-Project-Documentation.pdf
│
└── README.md
