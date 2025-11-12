# 🛒 E-Commerce Order Insights (v1: Basic Data Structures)

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Data Structures](https://img.shields.io/badge/Core%20Concepts-Data%20Structures-orange)](#)
[![CRUD](https://img.shields.io/badge/Operations-CRUD-green)](#)
[![Status](https://img.shields.io/badge/Project_Status-Completed-brightgreen)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

### 📌 Project Overview
This is a **menu-driven mini analytics system** for managing and analyzing e-commerce orders.  
It was built **purely using Python fundamentals** — `lists`, `dictionaries`, `sets`, `tuples`, and `loops`.  
No functions, OOP, or file handling yet — just **clean logic and structured data flow**.

> 💡 The goal: To demonstrate how even Python basics can simulate **real-world analytics dashboards** used by businesses.

---

### 🎯 Features

✅ Add new orders dynamically  
✅ Display all orders in a formatted table  
✅ Update order details (product, price, quantity, category, discount)  
✅ Remove orders by ID  
✅ Input validation (avoid crashes on wrong input)  
✅ Revenue analysis → total & average revenue  
✅ Best-selling product by revenue  
✅ Category-wise revenue breakdown  
✅ Basket analysis → average basket size & product frequency  
✅ Discount simulation → revenue loss & % impact  

---

### 📂 Data Structure
Each order is stored as a **dictionary**, and all orders are managed inside a **list**.

```python
order = {
    "id": 101,
    "product": "iPhone 15",
    "category": "Electronics",
    "price": 80000,
    "qty": 2,
    "discount": 10
}

```
```
========= E-Commerce Order Insights =========
1. Add Order
2. Display Orders
3. Update Order
4. Remove Order
5. Revenue Analysis
6. Best-Selling Product
7. Category-wise Revenue
8. Basket Analysis
9. Discount Simulation
10. Exit
=============================================
```


### 📊 Example Insights  

| Metric | Example Output |
|---------|----------------|
| **Total Revenue** | ₹2,50,000 |
| **Avg. Revenue per Order** | ₹31,250 |
| **Best-Selling Product** | iPhone 15 (₹1,60,000 revenue) |
| **Category-wise Revenue** | Electronics → ₹2,10,000 · Fashion → ₹40,000 |
| **Avg. Basket Size** | 1.8 items/order |
| **Discount Simulation (10%)** | Revenue Drop = 12.5% |

---

### 🚀 Learning Outcomes  

- Strengthened understanding of **lists**, **dictionaries**, **sets**, and **tuples**  
- Practiced **real-world data analytics logic** using only Python fundamentals  
- Gained experience in **menu-driven app design**  
- Learned **input validation** and user-friendly data presentation  
- Built confidence for next-level projects with **functions**, **OOP**, and **file handling**  

---

### 🔮 Next Steps  

- Add **file handling** for saving & loading orders  
- Refactor using **functions** for cleaner modular code  
- Integrate **matplotlib & seaborn** for visual insights  
- Extend into **ML tasks** → sales forecasting & product recommendations  

---

### 🧠 Author  

**Rudrapratap Sarma**  
🎯 *Aspiring Data Scientist | AI Engineer | Python Developer*  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/rudrapratap-sarma/)  
[![GitHub](https://img.shields.io/badge/GitHub-rudrapratap601-black?logo=github)](https://github.com/rudrapratap601)  
[![Kaggle](https://img.shields.io/badge/Kaggle-rudrapratapsarma-20BEFF?logo=kaggle&logoColor=white)](https://kaggle.com/rudrapratapsarma)

---

⭐ **If this project inspired you, give it a star!**  
It helps me stay motivated to turn this into a fully functional **ML-powered E-Commerce Analytics System** 🚀

