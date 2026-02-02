
# 🔗 SQL JOINS – Practice Assignment

📌 A **MySQL-based SQL assignment** focused on applying **SQL JOIN operations** to analyze
**customer behavior, orders, payments, and employee reporting hierarchy**
using a **retail business dataset**.

🎯 Designed to demonstrate **real-world JOIN logic** and **analytical thinking**
required for **Data Analyst and Data Science** entry-level roles.

---

## 🎯 Objectives

✅ Understand and apply different types of SQL JOINs  
✅ Combine multiple tables to answer business questions  
✅ Identify active vs inactive customers  
✅ Detect orphan records and missing relationships  
✅ Analyze customer behavior using orders and payments  
✅ Interpret organizational reporting structures  
✅ Write clean, structured, interview-ready SQL  

---

## 🛠️ Tech Stack

🗄️ **Database:** MySQL  
📜 **Language:** SQL  
⚙️ **MySQL Version:** 8.0+  
📈 **Level:** Beginner → Intermediate  

---

## 📂 What’s Inside

| 🔹 Section | 📄 Description |
|-----------|---------------|
| 🧍 Customers Analysis | Active and inactive customers |
| 🛒 Orders Analysis | Valid and orphan order records |
| 💳 Payments Analysis | Payments without purchases |
| 🔗 JOIN Operations | INNER, LEFT, RIGHT, FULL (UNION) |
| 🔀 CROSS JOIN | Cartesian product analysis |
| 🧠 SELF JOIN | Manager–Employee hierarchy |
| 📊 Consolidated View | Orders + payments per customer |

---

## ▶️ How to Run

1️⃣ Open **MySQL Workbench** or any MySQL client  
2️⃣ Create tables: `Customers`, `Orders`, `Payments`, `Employees`  
3️⃣ Insert the dataset values as provided in the assignment  
4️⃣ Open the file `SQL_Joins_Assignment_MySQL.sql`  
5️⃣ Execute queries **section-wise** for clarity  

---

## 📊 Final Output (Expected State)

📁 After execution, the queries return:

* Customers who **actively place orders**
* Customers who are **inactive**
* Orders with **unknown or missing customers**
* Customers who **paid but never ordered**
* All possible **customer–order combinations**
* Consolidated customer **order & payment summary**
* Employee **manager–reporting structure**

⚠️ Some result sets may include **NULL values**
— this is **expected and correct behavior** in JOIN analysis.

---

## 🧠 Key Takeaways

💡 Learn when to use each JOIN type  
💡 Understand how NULLs behave in JOIN operations  
💡 Simulate FULL OUTER JOIN in MySQL using `UNION`  
💡 Detect data quality issues using SQL  
💡 Think in terms of **business questions**, not just queries  
💡 Write production-quality, readable SQL  

---

## ⚠️ Notes (Important)

⚙️ FULL OUTER JOIN is **not directly supported in MySQL**
→ implemented using `LEFT JOIN + RIGHT JOIN + UNION`  
🚫 No schema modifications are performed  
📘 This is an **analysis-focused assignment**, not CRUD  
🧪 Output depends on dataset integrity and relationships  

---

## 👤 Author

👨‍💻 **Shivansh Yadav**  
📊 Aspiring Data Analyst / Data Scientist  

---
