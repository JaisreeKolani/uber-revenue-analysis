# Uber Booking Analytics

## 1. Overview
This project analyzes Uber booking data to understand ride performance, revenue trends, and cancellation behavior. The primary objective is to identify patterns in completed and lost bookings and evaluate how these trends impact overall revenue and platform efficiency.

---

## 2. Data and Approach
- **Dataset Size:** ~15,000 booking records  
- **Granularity:** One record per booking  
- **Time Period:** One full calendar year  

**Key Features:**
- Booking status (Completed / Cancelled)
- Vehicle type
- Pickup and drop locations
- Distance traveled
- Revenue
- Customer ID
- Cancellation reason
- Driver and customer ratings

**Methodology:**
- Cleaned and validated raw booking data
- Segmented completed vs cancelled rides
- Aggregated metrics by month, customer, and vehicle type
- Created KPIs and measures using Power BI
- Visualized trends in bookings, revenue, distance, and cancellations

This approach was chosen to directly link booking outcomes with revenue and customer behavior.

---

![Uber Booking Analytics Dashboard](assests/preview1.png)

## 3. Results
- **Total Bookings:** 149K  
- **Completed Bookings:** 93K  
- **Lost Bookings:** 57K (~38%)  
- **Total Revenue:** 52M  
- **Average Distance:** 24.64  
- **Average Driver Rating:** 4.23  
- **Average Customer Rating:** 4.40  

**Key Insights:**
- February shows the lowest completed bookings and revenue
- Monthly revenue remains stable between 4M–4.5M
- A small group of customers contributes disproportionately to revenue
- Most cancellations are customer-initiated, mainly due to change of plans

---

## 4. Conclusion
The analysis reveals that nearly 40% of bookings are lost due to cancellations, representing a significant revenue opportunity. Since revenue closely tracks completed bookings, reducing cancellations could materially improve platform performance. Improving pre-ride communication, introducing cancellation deterrents, and focusing on high-value customers can help increase revenue and efficiency.
