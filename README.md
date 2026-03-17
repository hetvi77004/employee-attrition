# 📊 Employee Attrition Analysis Dashboard

## 🧾 Overview

This project presents an **Employee Attrition Analysis Dashboard** built to uncover key insights into workforce trends, employee turnover, and organizational performance. It leverages HR data to visualize patterns across departments, salary bands, job roles, and demographics.

The dashboard helps stakeholders:

* Understand **why employees leave**
* Identify **high-risk groups**
* Improve **retention strategies**

---

## 📁 Dataset Description

The dataset contains employee-level HR records with the following key attributes:

### 🔑 Core Columns

* **EmpID** – Unique employee identifier
* **Age / AgeGroup** – Employee age and categorized group
* **Attrition** – Whether the employee left (Yes/No)
* **AttritionCount** – Binary indicator (1 = left, 0 = stayed)
* **Department** – Employee department
* **JobRole** – Specific role
* **SalarySlab / MonthlyIncome** – Compensation details
* **Education / EducationField** – Academic background
* **BusinessTravel** – Travel frequency
* **WorkLifeBalance** – Work-life satisfaction score
* **YearsAtCompany** – Tenure

### 📊 Sample Data

```
EmpID   Age  AgeGroup  Attrition  Department              JobRole                  MonthlyIncome
RM297   18   18-25     Yes        Research & Development  Laboratory Technician    1420
RM302   18   18-25     No         Sales                   Sales Representative     1200
RM458   18   18-25     Yes        Sales                   Sales Representative     1878
```

---

## 📌 Dashboard Features

### 1️⃣ Overview Page

* Total Employees: **5500**
* Attrition Count: **1106**
* Attrition Rate: **20%**
* Average Salary: **84.73K**

**Visuals:**

* Attrition by Department
* Employees by Salary Slab

---

### 2️⃣ Department Performance

* Total Employees by Department
* Average Salary Comparison
* Attrition Rate by Department
* Job Role Distribution

---

### 3️⃣ Attrition Insights & Trends

* Attrition by Age Group
* Attrition by Salary Slab
* Attrition by Education Field
* Attrition by Job Role

---

## 🔍 Key Insights

* 🔺 **Higher attrition** observed in:

  * Sales and HR departments
  * Lower salary brackets
  * Younger employees (18–25)

* 🔻 **Lower attrition** observed in:

  * Senior roles
  * Higher salary slabs
  * Employees with longer tenure

* 📉 Employees with **poor work-life balance** and **frequent travel** show higher attrition risk

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboard creation & visualization
* **Excel / CSV** – Data source
* **Data Modeling** – Relationships & calculated measures

---
![Alt text](https://github.com/hetvi77004/employee-attrition/blob/main/home.png)
![Alt text](https://github.com/hetvi77004/employee-attrition/blob/main/dashbord.png)
![Alt text](https://github.com/hetvi77004/employee-attrition/blob/main/trends.png)
![Alt text](https://github.com/hetvi77004/employee-attrition/blob/main/salary.png)

---

## 🚀 How to Use

1. Clone the repository
2. Open the `.pbix` file in Power BI
3. Interact with filters:

   * Department
   * Age Group
   * Education Field
   * Salary Slab

---

## 🎯 Business Use Cases

* HR analytics & reporting
* Attrition prediction strategies
* Workforce planning
* Compensation benchmarking

---

## 📈 Future Improvements

* Add **predictive modeling (ML)** for attrition
* Integrate **real-time HR data pipelines**
* Build **automated alerts** for high-risk employees


⭐ If you find this project useful, don’t forget to star the repo!
