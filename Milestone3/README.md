# Hotel Reservation Analytics & Forecasting Dashboard

This Power BI project delivers a comprehensive analysis of hotel reservation data, focusing on booking trends, cancellations, no-shows, lead time behavior, and future demand estimation. The dashboard is designed to assist hotel management teams in identifying demand patterns, minimizing revenue loss, and improving strategic and operational decisions.

---

## Demand Forecasting Overview

Future booking demand is projected using Power BI’s built-in time series forecasting functionality.

- **Core forecast metric**: `Forecast Bookings Next Months`, which predicts upcoming bookings based on historical reservation data.
- **Forecast highlight**: A KPI card displays an estimated **810.02 bookings** expected in the near-term forecast horizon.
- Forecast visuals combine line and column charts to contrast actual booking values with predicted figures across **Spring, Summer, and Winter** seasons.
- Seasonal fluctuations and historical booking behavior are reflected in the forecast continuation.

---

## Cancellation & Lead Time Insights

### Cancellation Trends
- Monthly cancellations are represented using the metric **Sum of Cancellations by Month**.
- Peak cancellation periods occur in **January (~20)** and **July (~17)**, followed by **February (~15)** and **March (~12)**.
- Data is visualized both as raw counts and normalized percentage bands (85%–100%) for better comparison.

### No-Show Behavior
- **Average Monthly No-Shows** show a steady decline, improving from approximately **1.4** to **1.1** over time.
- **Total No-Shows by Month** peak in **January (~40)**, reach a low in **March (~28)**, and rise slightly again by **July (~35)**.
- **Daily analysis** indicates that no-shows are highest during the **first 10 days of each month**, reaching up to **8**, before stabilizing between **2–6** for the remainder of the month.

### Booking Lead Time Analysis
- Lead times are compared between **Direct** and **OTA** booking channels.
- Early periods show longer booking lead times, peaking around **March**, followed by a sharp reduction in later months.
- Direct reservations typically demonstrate marginally longer lead times compared to OTA bookings, offering better planning visibility.

---

## Analytical Insights

1. **Declining No-Show Rates**  
   The consistent reduction in average no-shows suggests improved booking confirmation processes or better guest reliability.

2. **Clear Seasonality Pattern**  
   Booking volumes are strongest during Spring and Summer, with noticeable drops in Winter. The forecasted value of ~810 bookings indicates continued softness ahead.

3. **Cancellations Align with Peak Demand**  
   Higher cancellations in January and July imply overbooking risks and increased price sensitivity during busy seasons.

4. **Shift Toward Last-Minute Bookings**  
   The sharp decline in lead times highlights a growing trend of late bookings, increasing uncertainty for capacity and pricing strategies.

5. **Early-Month Risk Window**  
   Elevated no-show activity in the first third of each month suggests a critical period requiring closer monitoring and proactive communication.

6. **Conservative Forecast Behavior**  
   The forecast line appears smoother and less reactive to recent booking declines, indicating potential under-weighting of recent trends.

---

## Strategic Recommendations

- **Refine Peak-Season Policies**  
  Strengthen cancellation rules or adjust overbooking limits during high-demand months such as January and July.

- **Improve Last-Minute Pricing Strategies**  
  Adopt flexible pricing, dynamic offers, and real-time inventory management to respond to shorter booking windows.

- **Reinforce No-Show Prevention Measures**  
  Continue initiatives like automated reminders, partial prepayments, and proactive guest engagement.

- **Prepare for Lower Occupancy Periods**  
  With demand projected to soften, explore promotional campaigns, bundled offers, and cost optimization during low seasons.

- **Encourage Direct Bookings**  
  Since direct channels provide longer lead times, enhance loyalty incentives, exclusive benefits, and direct-booking discounts.

- **Operational Planning**  
  Allocate staffing and resources cautiously during the first 10 days of each month due to higher no-show volatility.

---

## Data Currency

The dashboard reflects booking data available **up to July**, based on the most recent visuals displayed. Regular data refreshes are recommended to ensure forecast accuracy and timely trend detection.
