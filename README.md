
# Atliq Hospitality Analysis

## 📌 Project Overview
This project focuses on analyzing key hospitality metrics for **Atliq Hotels**, a chain of premium hotels. The analysis provides insights into **revenue, occupancy rates, average daily rates (ADR), and booking trends** using Power BI.

[LIVE DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiYWQyYzYyODYtMjE2ZC00OWJiLWJkYWItNzAyZjgwODNhZGYxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## 📊 Dataset Details
The project utilizes multiple datasets related to hotel bookings:
- [dim date.csv]() - Date-related details.
- [dim hotels.csv]() - Information about different hotel properties.
- [dim rooms.csv]() - Room types and classifications.
- [fact_aggregated_bookings.csv]() - Summarized booking data.
- [fact bookings.csv]() - Detailed transactional booking data.

## 🔍 Key Insights
- **Revenue Analysis**: The total revenue generated is **581.9M**, with the highest revenue coming from Mumbai.
- **Occupancy Trends**: The overall occupancy rate is **59%**, with peak bookings during weekends.
- **ADR & RevPAR**: ADR stands at **12.7K**, while RevPAR (Revenue per Available Room) is **7.43K**.
- **Booking Cancellations**: The majority of cancellations occur through **online platforms**.
- **Platform Performance**: MakeMyTrip and LogTrip contribute to the highest bookings.

## 📈 Dashboard Overview
The Power BI dashboard contains the following key visuals:
1. **Overall Analysis**:
   - Revenue breakdown by city
   - Occupancy % by city
   - Booking trends by platform
   - Weekly revenue and rating trends
   - Occupancy ratio (Weekday vs. Weekend)

2. **Monthly Analysis**:
   - Capacity vs. Bookings vs. Cancellations
   - Revenue by Room Class
   - Cancellations by Platform
   - Property-wise performance

## 🛠️ Tools & Technologies Used
- **Power BI** - Data visualization and report building
- **DAX** - Used for advanced calculations and measures
- **Excel & CSV Files** - Data sources for the project
