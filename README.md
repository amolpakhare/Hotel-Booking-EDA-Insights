# 🏨 Hotel Booking EDA & Insights

An end-to-end Exploratory Data Analysis (EDA) project on hotel booking data to identify trends in cancellations, understand customer behavior, and generate business-friendly recommendations to reduce booking losses.

Business Problem:

This project aims to explore and analyze booking data to uncover patterns behind cancellations and provide actionable insights to hotel managers for improving customer retention and revenue generation.

---

## 🎯 Objective

Analyze the hotel booking dataset to:
- Understand booking patterns.
- Identify causes of reservation cancellations.
- Suggest business strategies to improve customer retention and revenue.

---

## 📁 Dataset Summary

- **Total Records**: ~119,000 bookings
- **Features**: Includes customer type, booking date, number of guests, children, ADR (price), special requests, and cancellation status.
- **Target**: `is_canceled` (Yes/No)

---

## 🧹 Data Cleaning Steps

- Checked for missing values using `.isnull().sum()`.
- Found and counted duplicate records with `.duplicated().sum()`.
- Cleaned binary labels for clarity:
  - Converted `0/1` to `'No/Yes'` for `is_repeated_guest` and `is_canceled`.
- Removed columns with too many missing values: `company`, `agent`.
- Dropped remaining missing rows using `.dropna()`.

---

## 📊 Key Insights

- Higher average daily rates often result in more cancellations.
- Resort hotels have a significantly higher cancellation ratio than city hotels.
- Portugal leads in cancellations, contributing almost 50% of the total.
- Most cancellations happen from March to May.
- January has the highest number of cancellations.
- Bookings involving children or babies are more likely to be canceled.
- Revenue peaks in summer, drops post-September.

---

## ✅ Business Suggestions

1. **Adjust pricing**: High prices increase cancellation rates — consider targeted discounts.
2. **Resort offers**: Offer weekend and holiday discounts for resort hotels.
3. **January focus**: Run deals or ads in January to counter high cancellations.
4. **Targeted campaigns**: Focus less on high-cancellation countries like Portugal.
5. **Family-friendly options**: Offer more clarity and perks for families.
6. **Improve service quality**: Especially in regions with more cancellations.
7. **Introduce flexible policies**: Offer no-cost changes or cancelation windows when possible.

---

## 📈 Visuals Used

- ADR vs Cancellation distribution
- Cancellation ratio by hotel type
- Country-wise cancellation pie chart
- Monthly cancellation patterns
- Relationship of cancellations with adults, children, and babies

---

## 💻 Technologies Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization
- Jupyter Notebook
- Statistics
- Word

## Project Structure

Hotel-Booking-EDA-Insights/
│
├── data/ # Dataset (if applicable)
├── notebook/ # EDA Jupyter Notebook
├── images/ # All generated plots
├── Hotel_Booking_EDA.pdf # Final Report (for LinkedIn or sharing)
└── README.md # This file


---

## 📌 Conclusion

This project helps hotel managers and analysts understand the key drivers of reservation cancellations. By analyzing the data and visual trends, we provided actionable insights and strategies that can help reduce losses, improve occupancy, and boost revenue through informed business decisions.

---

## 🙋‍♂️ Author

**Amol Pakhare**  
📧 Let's connect on [LinkedIn] - https://www.linkedin.com/in/pakhareamol  
📁 View my work on [GitHub] - https://www.github.com/amolpakhare

---

## 🌟 If you found this helpful, give it a ⭐ and share your thoughts!

