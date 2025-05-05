# 🏍️ Motorcycle Data Exploration 🚀  

### **A project inspired by my passion for motorcycles**  

This project focuses on collecting, cleaning, and organizing data from [Bikez.com](https://www.bikez.com/) to build a structured database. My goal is to explore the data, create interactive visualizations, and develop tools to help users find their ideal motorcycle.  

I will be sharing updates and improvements as I progress through each stage of development.  

---

## 📌 **Current Progress**  

### 🔍 **Stage 1 - Web Scraping**  
Extracting data presented several technical challenges that required creative solutions:  

✅ **Integrating multiple libraries:** Learned to combine Beautiful Soup with dynamic tools (initially Selenium, later Asyncio) to ensure full data loading without interference from "Loading..." placeholders.  

✅ **Handling inconsistencies:** Bikez.com uses varied column names, requiring custom logic to harmonize the data and ensure usability in later stages.  

✅ **Managing stalled processes:** In some cases, browser processes failed to close properly, causing performance issues. Implementing proper process management was essential for script stability.  

✅ **Intelligent data saving:** To avoid re-scraping previously processed pages, I developed a logging system to track scraped motorcycles, optimizing execution time and efficiency.  

💡 These challenges helped me strengthen my skills and build a more robust scraping pipeline.  

---

### 🛠 **Stage 2 - Data Cleaning**  

Transforming raw data into a clean, structured format involved overcoming several hurdles:  

✅ **Brand/model separation:** Extracted motorcycle brand listings and split combined "Brand+Model" fields into distinct columns for proper categorization.  

✅ **Regex-based standardization:** Implemented dictionary-based regex rules to normalize values and correct minor inconsistencies.  

✅ **Numeric field preparation:** Cleaned numerical columns by removing unnecessary characters and converting values into appropriate formats for analysis.  

✅ **Dataset reorganization:** Maintained structural integrity while systematically adding, modifying, and removing columns without compromising logical organization.  

✅ **Optimized export:** Generated a clean and refined CSV file, ready for use in upcoming phases.  

💡 This process strengthened my data processing skills and ensured a dataset prepared for exploration and modeling.  

---

## 🔜 **Next Steps**  

📌 **Stage 3 - Database creation and population**  
📌 **Stage 4 - Machine Learning model development**  

This project is continuously evolving, with many improvements ahead. Stay tuned for updates! 🚀  
