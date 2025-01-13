# Yelp Business Intelligence Platform

---

## **Objective**
This project focuses on converting Yelp's JSON-format data into a structured format in SQL Server (Azure) and deriving insights to help set up a new restaurant based on customer data.

---

## **Project Overview**
The project utilized Kaggle's public Yelp dataset, which includes information about businesses, users, reviews, and tips. The main objectives were to:
- Read and interpret semi-structured JSON data.
- Convert JSON to structured SQL tables.
- Create and update SQL tables using Azure SQL Server.
- Derive valuable business insights using SQL queries.

---

## **Key Insights**
- **Most Popular Cities:** Cities with the highest restaurant engagement based on reviews.
- **Top Categories:** Most popular cuisine categories (e.g., Italian, Fast Food).
- **Sentiment Analysis:** Analyzed reviews to determine average star ratings and customer feedback patterns.
  - Example Insight: *Las Vegas had the highest number of restaurant reviews, and Italian restaurants received an average rating of 4.3 stars.*

---

## **Tools and Technologies**
- **Data Exploration:** Python (Pandas, NumPy)
- **Data Conversion:** SQLAlchemy, Azure SQL Server (for creating and managing tables)
- **Visualizations:** Matplotlib, Seaborn

---

## **Repository Contents**
- `notebooks/`: Contains the Python notebook used for data exploration and SQL conversion.
- `docs/`: Contains the final PDF report detailing project insights and findings.

---

## **How to Run**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/NikhitaShankar97/Yelp-Business-Intelligence-Platform.git
