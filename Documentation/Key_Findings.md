# Uber Business Analysis | Key Insights

## Project Context

This document summarizes the key findings from the Uber Power BI dashboard based on the reported dashboard values and descriptions.

The analysis covers:
- Overall business performance
- Vehicle category performance
- Revenue and payment patterns
- Rider cancellations
- Trip distance and location patterns

> **Interpretation note:** These findings describe patterns and associations in the available dashboard data. They do not establish causation. Business implications are investigation opportunities, not proven explanations.

---

## 1. Overall Business Performance

### 1.1 Revenue and booking volume

**Finding**
- Total revenue: **47.26M**
- Total bookings: **150,000**
- Completed bookings: **93,000**
- Lost bookings: **37,500**
- Average revenue per completed booking: **508.2**

**Why it matters**

Revenue shows the scale of business activity, while booking outcomes show how much demand turns into completed trips. The average revenue per completed booking provides a useful reference point for comparing revenue performance over time or across vehicle categories.

**Business implication**

Monitor completed-booking volume alongside revenue. A change in revenue should be investigated together with changes in completed trips and average revenue per completed booking, rather than being interpreted in isolation.

**Validation note**

Completed bookings and lost bookings total **130,500**, leaving **19,500 bookings** (13% of all bookings) not accounted for by those two headline figures. The reported lost-booking total includes these statuses:
- Cancelled by Customer
- Cancelled by Driver
- Driver Not Found
- Incomplete

The remaining booking statuses or classification should be clarified before presenting completed and lost bookings as a complete breakdown of all bookings.

### 1.2 Revenue trend by month

**Finding**

Monthly revenue is relatively consistent, ranging from approximately **3.65M in February** to **4.17M in March**. March is the highest month in the supplied figures, while February is the lowest.

**Why it matters**

A relatively narrow monthly range may indicate that revenue is not heavily concentrated in one month. Identifying the highest and lowest months helps the business investigate possible seasonal or operational patterns.

**Business implication**

Compare monthly revenue with completed bookings, average booking value, vehicle mix, and relevant seasonal factors to understand what contributed to the monthly differences.

### 1.3 Revenue trend by quarter

**Finding**

Quarterly revenue is reported to range from approximately **11.65M to 11.95M** across the four quarters.

**Why it matters**

Quarterly comparison gives management a broader view of revenue stability and helps reduce the effect of short-term monthly fluctuations.

**Business implication**

Use quarterly revenue as a performance-monitoring measure, then investigate any quarter that differs from the others by checking booking volume and revenue contribution by vehicle type.

### 1.4 Pickup and drop-off locations

**Finding**

The Overview page highlights frequently appearing pickup locations such as Khandsa, Barakhamba Road, Saket, Badarpur, and Pragati Maidan. Frequently appearing drop-off locations include Ashram, Basai Dhankot, Lok Kalyan Marg, Narsinghpur, Cyber Hub, and Kalkaji. The displayed values are close to 1,000.

**Why it matters**

Repeated activity around particular locations may indicate areas with comparatively high trip demand.

**Business implication**

Investigate these locations further by comparing pickup and drop-off volumes, time periods, completed trips, and driver availability. The current figures alone do not establish profitability or unmet demand in those areas.

---

## 2. Vehicle Performance

### 2.1 Auto is the leading vehicle category by revenue

**Finding**

Auto generates the highest reported revenue:
- Auto: **11.73M (24.81%)**
- Go Mini: **9.41M (19.91%)**
- Go Sedan: **8.54M (18.07%)**
- Bike: **7.14M (15.12%)**
- Premier Sedan: **5.73M (12.13%)**
- eBike: **3.30M (6.98%)**
- Uber XL: **1.41M (2.98%)**

**Why it matters**

Auto contributes almost one quarter of total revenue and leads the listed vehicle categories. This makes it an important category to monitor when assessing overall revenue performance.

**Business implication**

Examine Auto's completed bookings, average revenue per completed trip, distance, and operating costs before deciding whether to expand its availability or prioritize it in operational planning. Revenue contribution alone does not establish profit contribution.

### 2.2 Revenue contribution broadly follows booking volume

**Finding**

Auto has the highest reported booking count (**37,419**) and revenue (**11.73M**). Uber XL has the lowest booking count (**4,449**) and revenue (**1.41M**). The other vehicle categories fall between these values.

**Why it matters**

The alignment between booking volume and revenue suggests that trip volume is an important dimension to examine when comparing vehicle-category revenue.

**Business implication**

Compare revenue per completed booking across vehicle categories to determine whether revenue differences are mainly associated with booking volume or also with differences in average trip value.

### 2.3 Auto accounts for the largest reported distance

**Finding**

Total distance by vehicle category is reported approximately as:
- Auto: **0.63M**
- Go Mini: **0.50M**
- Go Sedan: **0.45M**
- Bike: **0.38M**
- Premier Sedan: **0.30M**
- eBike: **0.18M**
- Uber XL: **0.07M**

**Why it matters**

Distance helps describe how vehicle categories contribute to trip activity. It provides context for interpreting revenue and completed bookings.

**Business implication**

Compare distance with revenue and completed bookings by vehicle category. This can help identify differences in revenue per kilometre and average trip distance.

### 2.4 Driver and rider ratings are similar across vehicle categories

**Finding**

Average driver ratings are around **4.23**, and average rider ratings are around **4.40** across most vehicle categories.

**Why it matters**

The reported averages are close across categories, so the available summary does not show a large rating difference between vehicle types.

**Business implication**

Review rating distributions and the number of ratings per category before concluding that service quality is consistent. Average values can hide differences among individual trips or customer groups.

---

## 3. Revenue and Payment Patterns

### 3.1 Average revenue per completed booking

**Finding**

The Revenue page reports:
- Total revenue: **47.26M**
- Completed bookings: **93,000**
- Average booking: **508.2**
- Revenue per kilometre: **18.8**

The average booking value is consistent with total revenue divided by completed bookings: approximately **508.18**.

**Why it matters**

Average revenue per completed booking provides a reference for monitoring the value generated by completed trips. Revenue per kilometre provides another view that relates revenue to distance.

**Business implication**

Track both measures over time and across vehicle categories. Investigate changes alongside trip distance, vehicle mix, and completed-booking volume.

### 3.2 UPI is the most frequently reported payment method

**Finding**

The dashboard reports the following payment-method distribution:
- UPI: **45.74%**
- Cash: **25.37%**
- Uber Wallet: **12.62%**
- Credit Card: **9.41%**
- Debit Card: **6.86%**

**Why it matters**

UPI represents the largest reported share, followed by cash. Payment preferences matter when planning payment experiences and monitoring payment-channel performance.

**Business implication**

Prioritize monitoring the reliability and user experience of the most-used payment methods, while continuing to support the other methods.

**Validation note**

The payment visual is described with values of 660K, 366K, 182K, 136K, and 99K, which add up to approximately 1.443M. This is not consistent with the reported total of 150,000 bookings if these values are intended to represent booking counts. The percentages add to 100%, but the count labels and their meaning should be checked before including the counts in a final report. The percentages are retained here as reported dashboard values.

### 3.3 Revenue by customer

**Finding**

The highest customer revenue values shown are:
- C7828101: **7.7K**
- C7186567: **6.1K**
- C2536937: **6.0K**
- C9494011: **6.0K**
- C3446144: **5.6K**

**Why it matters**

A customer-level revenue view can help identify high-value customers and understand whether revenue is concentrated among a small group.

**Business implication**

Review customer booking frequency, completed trips, and revenue contribution together. The listed top customers alone are not enough to conclude that revenue is highly concentrated or that these customers are repeat customers.

---

## 4. Rider and Cancellation Analysis

### 4.1 Customer cancellations and cancellation rate

**Finding**

The Rider page reports:
- Total riders: **104.1K**
- Customer-cancelled bookings: **11K**
- Completed bookings: **93K**
- Cancellation rate: **7%**

**Why it matters**

Customer cancellations represent demand that did not result in a completed trip. Monitoring cancellation volume and rate can help identify friction in the booking experience.

**Business implication**

Track customer cancellations over time and investigate the reasons behind them. Compare cancellation patterns across locations, time periods, and vehicle categories where the data allows.

### 4.2 Main reported reasons for customer cancellations

**Finding**

The most frequently reported reasons are:
- Wrong Address: **2.4K**
- Change of Plans: **2.4K**
- Driver is Not Moving Towards Pickup Location: **2.3K**
- Driver Asked to Cancel: **2.3K**
- AC is Not Working: **1.2K**

**Why it matters**

The reasons include both booking-information issues and service or driver-related issues. This distinction is useful because different types of issues may require different operational responses.

**Business implication**

Investigate address-entry and pickup-location guidance, driver movement toward pickup, and reports of drivers asking customers to cancel. Review vehicle-condition complaints separately. These are potential areas for investigation, not proof of the underlying causes.

### 4.3 Monthly customer cancellations

**Finding**

The supplied monthly figures show the highest customer cancellations in June (**37**) and the lowest in February and March (**20** each).

**Why it matters**

Monthly variation can help identify periods that deserve closer investigation.

**Business implication**

Compare these monthly counts with total bookings in each month. Counts alone do not show whether the cancellation rate increased, because monthly booking volumes may differ.

### 4.4 Quarterly customer cancellations

**Finding**

The supplied quarterly values are:
- Q1: **66**
- Q2: **89**
- Q3: **93**
- Q4: **80**

Q3 is the highest of the four reported quarters.

**Why it matters**

Quarterly grouping can reveal broader changes that may be less visible in monthly figures.

**Business implication**

Compare quarterly cancellation counts with quarterly booking volume and verify that the visual uses the same cancellation definition and filter context as the customer-cancellation KPI.

**Validation note**

The four quarterly values add up to **328**, which is far below the reported **11K** customer cancellations. Confirm whether the quarterly visual is filtered, uses a different measure, or represents a narrower subset before treating it as a complete quarterly breakdown.

---

## 5. Location and Distance Analysis

### 5.1 Distance contribution by vehicle category

**Finding**

Auto has the highest reported total distance (**0.63M**), followed by Go Mini (**0.50M**) and Go Sedan (**0.45M**). Uber XL has the lowest reported total distance (**0.07M**).

**Why it matters**

This comparison shows which vehicle categories account for the largest share of recorded travel distance.

**Business implication**

Compare distance with revenue and completed bookings to understand how travel activity relates to revenue generation across categories.

### 5.2 Monthly distance pattern

**Finding**

The Location page reports monthly distance values ranging from approximately **5.8K to 7.1K**. December is the highest reported month (**7,053**), while October is the lowest (**5,797**).

**Why it matters**

Monthly distance can help describe changes in trip activity, but it needs to be interpreted alongside the number of completed trips.

**Business implication**

Compare monthly distance with completed bookings and average trip distance to determine whether changes reflect more trips, longer trips, or both.

**Validation note**

The monthly values provided (approximately 5.8K–7.1K per month) do not appear to reconcile with the reported total distance of **2,512,975**. Confirm the unit, aggregation, and filters used in the monthly visual before using it to explain the overall distance KPI.

---

## 6. Data Checks Before Finalizing the Insights

The following items should be reviewed before publishing this document as a final business report:

1. **Booking-status reconciliation:** 150,000 total bookings minus 93,000 completed and 37,500 lost leaves 19,500 bookings not represented by those two headline figures. The reported lost total includes Cancelled by Customer, Cancelled by Driver, Driver Not Found, and Incomplete.
2. **Quarterly customer cancellations:** The supplied quarterly values total 328, not 11K. Confirm whether the chart represents a filtered subset or a different measure.
3. **Monthly distance:** The supplied monthly values do not reconcile with the 2.5M total distance KPI. Confirm units and aggregation.
4. **Payment-method counts:** The supplied counts total approximately 1.443M, not 150K. Confirm whether these are counts, a different aggregation, or labels from another measure.
5. **Booking Count by Vehicle chart:** The displayed values (1,197, 933, 821, 708, 560, 330, and 118) do not reconcile with the vehicle table's booking counts, which total 150,000. Confirm the measure and aggregation used in that chart.
6. **Lost bookings versus customer cancellations:** Lost Bookings (37.5K) includes multiple statuses, while Customer Cancelled (11K) is a narrower category. These should not be used interchangeably.
7. **Revenue per kilometre:** Confirm that the measure uses total revenue divided by the same distance population and filter context represented by the total-distance KPI.

---

## 7. Overall Business Takeaways

Based on the currently supplied dashboard values:

- **Auto is the leading revenue category**, contributing 24.81% of total revenue.
- **Revenue is relatively stable across months and quarters** in the reported charts, with some variation that merits further investigation.
- **UPI is the largest reported payment method** by percentage share.
- **Customer cancellation reasons point to several investigation areas**, including incorrect addresses, changes of plans, and pickup or driver-related issues.
- **Pickup and drop-off locations show recurring activity hotspots** that could be examined further for demand and operational planning.
- **Vehicle-category ratings are broadly similar** in the reported averages, although rating distributions should be reviewed before drawing a strong service-quality conclusion.

These takeaways should be treated as descriptive findings from the current dashboard. Recommendations should be refined after the data-validation items above are resolved.

