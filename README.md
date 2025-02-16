# 🏆 Puma Web Scraping Project  

## 📌 Overview  
This project focuses on **web scraping** data from the **Puma website** to extract product details such as prices, discounts, and product links. The extracted data helps analyze pricing strategies, discount trends, and product availability.  

This project is useful for:  
✔ **Tracking product prices and discounts**  
✔ **Monitoring stock availability**  
✔ **Analyzing discount patterns and pricing trends**  
✔ **Comparing different product categories**  

---

## 📊 Features  
✔ **Extracts key product details from Puma’s website**  
✔ **Handles multiple product pages dynamically**  
✔ **Cleans and structures the scraped data**  
✔ **Exports results to CSV or JSON for further analysis**  
✔ **Supports automation for regular updates**  

---

## 📜 Technologies Used  
- **Python** – Main programming language  
- **Requests** – Fetches web pages  
- **BeautifulSoup** – Parses HTML content  
- **Selenium** – Handles JavaScript-rendered elements (if applicable)  
- **Pandas** – Processes and structures data  

---

## 📌 Extracted Data Columns  

The dataset contains the following columns:  

| Column Name       | Description |
|-------------------|------------|
| **Title**         | Name of the product |
| **Discount Price**| Final price after discount |
| **Discount**      | Percentage of discount applied |
| **Original Price**| Price before the discount |
| **Product Link**  | URL of the product page |

---

## 📌 Web Scraping Workflow  

### **1️⃣ Sending HTTP Requests**  
The project fetches product listings from Puma’s website by sending structured HTTP requests.  

### **2️⃣ Parsing Product Information**  
The HTML content is analyzed, and product details such as **title, price, discount, and links** are extracted.  

### **3️⃣ Handling Dynamic Content**  
If Puma’s website loads content dynamically using JavaScript, Selenium is used to handle such cases and retrieve full product information.  

### **4️⃣ Data Cleaning & Structuring**  
- Removes unwanted characters and symbols (e.g., ₹ in price columns).  
- Ensures **prices are stored as numeric values** for analysis.  
- Handles **missing or incorrect values**.  

### **5️⃣ Exporting Data**  
The cleaned data is saved in **CSV** or **JSON** format for further processing and visualization.  

---

## 📊 Data Analysis & Insights  

### **1️⃣ Discount Analysis**  
- Identifies **average discount percentages** across different products.  
- Helps analyze which categories receive the highest discounts.  

### **2️⃣ Price Distribution**  
- Detects **price variations** among Puma products.  
- Compares **discounted vs. non-discounted prices**.  

### **3️⃣ Product Availability & Trends**  
- Monitors which products frequently **go out of stock**.  
- Analyzes **price trends over time**.  

---

## 📌 Conclusion  

This project successfully scrapes and analyzes Puma’s product data, offering insights into pricing trends, discounts, and product availability. The extracted data can be used for competitive analysis, business intelligence, and market research.  

### **Key Takeaways:**  
✅ Automates data extraction from Puma’s website.  
✅ Helps track **price changes and discount trends**.  
✅ Identifies **popular and discounted products**.  
✅ Provides structured data for further analysis.  

🚀 Future improvements could include **real-time monitoring, deeper data visualization, and integration with analytics dashboards.**  
