## 📊 Revenue and Occupancy Metrics

1. **REVPAR_NEW** was calculated using the formula:
   *Room Revenue ÷ Rooms Available*

2. **Occupancy** was derived using:
   *REVPAR_NEW ÷ ADR*

3. The **ADR (Average Daily Rate)** was provided initially, and based on this we computed both **REVPAR_NEW** and **Occupancy**.

4. The calculated value of **REVPAR_NEW** is approximately **1.32 million**, while the average **Occupancy** stands around **680**.

---

## 🧳 Guest Classification

1. Guests were classified based on **guest country**, **booking duration**, and **booking channel**.

2. This classification helped identify whether bookings were made directly or through OTAs, the countries from which guests originated, and the length of stay across different categories.

---

## 👥 Customer Segmentation

1. Customers were segmented using **customer_id**.

   * If a customer ID appeared multiple times, the customer was considered **loyal**.
   * If the customer ID appeared only once, the customer was treated as a **first-time visitor**.
   * If the number of visits exceeded **10**, the customer was categorized as a **high-value (high-spending) customer**.

---

## 🔍 Key Insights and Observations

1. The majority of guests originated from the **USA**.
2. Most bookings were made through **Online Travel Agencies (OTAs)**.
3. The distribution of bookings across different seasons remained nearly **uniform**, with ratios close to **1**.


**Prepared by:**
**Vaibhav Bari**
