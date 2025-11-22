# Simple_Finance_Dashboard

📌 README.md — Simple Finance Dashboard

Simple Finance Dashboard

A lightweight personal finance analysis tool built using Python, Streamlit, Pandas, and Plotly.
Users can upload bank CSV statements, auto-categorize transactions, adjust them manually, and visualize spending patterns interactively.


---

📍 Overview

Managing expenses manually can be tedious and error-prone.
This dashboard simplifies the workflow by:

✔ Importing bank statements (CSV)
✔ Automatically identifying expense categories using keyword matching
✔ Allowing manual corrections via interactive UI
✔ Providing visual analytics with a category-wise expense summary
✔ Persisting user-defined categories locally

This project demonstrates real-world application of data processing, UI design, and visualization in Python .


---

✨ Features

🔹 Upload CSV bank transaction files

🔹 Automatic categorization using stored keyword rules

🔹 Edit categories easily using Streamlit’s data editor

🔹 Pie-chart visualization of category-wise spending

🔹 Local persistence of categories in categories.json

🔹 Separate tab for credits (payments overview)



---

🏗️ Technologies Used

Component	Purpose

Python	Core programming
Streamlit	Web UI framework
Pandas	Data cleaning + processing
Plotly Express	Graphs & visualization
JSON	Storage for custom categories
GitHub	Version control & project submission 



---

📂 Project Structure

📁 finance-dashboard
│── app.py
│── categories.json
│── README.md
│── (Sample CSV Files)


---

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install streamlit pandas plotly

2️⃣ Run Streamlit App

streamlit run app.py

3️⃣ Upload Your CSV on the UI

Make sure the CSV includes: Date, Details, Amount, Debit/Credit columns.


---

🧪 Testing Instructions

Upload multiple CSV files to check consistency

Manually reassign categories → verify persistence in 🔹 categories.json

Edit entries → Apply → Confirm UI update and keyword learning

Observe pie chart update dynamically



---

📸 Screenshots (optional to add before submission)

Dashboard View	Upload Section

(Insert Screenshot)	(Insert Screenshot)



---

👥 Target Users

Anyone tracking personal finances

Students managing daily spending

Early-stage budgeting use cases



---

🔮 Future Enhancements

Multi-file merging support

Advanced ML-based transaction categorization

Export categorized data as Excel/CSV

Secure cloud-synced category storage

Month-over-month analytics dashboard



---

📚 References

Streamlit Docs

Plotly Express Docs

CSV processing with Pandas

Project structure and documentation guidelines from VIT Build Your Own Project instructions 



---
