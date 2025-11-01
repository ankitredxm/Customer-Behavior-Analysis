🧠 Customer Shopping Behavior Analysis
📄 Overview

This project analyzes 3,900 customer purchase records to uncover insights that drive data-driven retail strategies.
Using Python, SQL, and Power BI, the project explores customer demographics, purchase trends, product performance, and discount behavior.
The insights are compiled into an interactive Power BI dashboard, detailed SQL analyses, and a presentation deck created with Gamma.

📊 Dataset

Dataset Source: Custom / simulated retail dataset
Records: 3,900 purchases
Features (18):

Customer demographics — age, gender, location

Product attributes — category, color, size, price

Transaction data — purchase amount, season, discount use

Subscription and shipping type

Review ratings and promo usage

🧰 Tools & Technologies
Category	Tools Used
Language	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL / MySQL
Libraries	SQLAlchemy, psycopg2, mysql-connector-python
Visualization	Power BI
Presentation	Gamma
Environment	Jupyter Notebook
⚙️ Project Steps
1️⃣ Data Loading & Exploration

Imported dataset with Pandas

Inspected schema using df.info() and summary statistics

2️⃣ Data Cleaning

Handled 37 missing review ratings using median per product category

Standardized column names to snake_case

Removed redundant columns like promo_code_used

3️⃣ Feature Engineering

Created age_group and purchase_frequency_days

Derived revenue-by-segment metrics

4️⃣ Database Integration

Connected to PostgreSQL via SQLAlchemy

Uploaded cleaned dataset for SQL queries and analysis

5️⃣ Exploratory Data Analysis (EDA)

Visualized spending patterns by gender, age, and product category

Compared revenue and discount usage

Identified customer segments (New, Returning, Loyal)

6️⃣ Dashboard & Reporting

Built Power BI Dashboard featuring:

Revenue by gender, age, and location

Product performance and discount dependency

Customer segmentation metrics

Designed summary slides using Gamma

📈 Key Insights

68% of total revenue is driven by male customers

Express shipping users spend 3.5% more per transaction

Top-rated products: Gloves (3.86★), Sandals (3.84★), Boots (3.82★)

Discount users still maintain above-average purchase value

Young adults contribute the highest total revenue ($62K+)

💡 Strategic Recommendations

Boost Subscriptions: Target 2,500+ loyal non-subscribers with incentives

Loyalty Program: Reward repeat buyers to drive retention

Optimize Discounts: Control margin erosion on 50% discount-dependent items

Promote Top Products: Feature high-rating items in campaigns

Target Premium Segment: Focus marketing on express-shipping and young-adult customers

▶️ How to Run Locally

Clone the repository

git clone https://github.com/ankitredxm/Customer-Behavior-Analysis.git
cd Customer-Behavior-Analysis


Install dependencies

pip install -r requirements.txt


Run the Jupyter notebook

jupyter notebook Customer_Behavior_Analysis.ipynb


Configure your SQL connection (PostgreSQL/MySQL)

Update username, password, and database in the script.

Open the Power BI Dashboard

Explore visual insights interactively.

📬 Author

Ankit Kumar
🔗 GitHub Profile

💼 Data Analytics | Python | SQL | Power BI
