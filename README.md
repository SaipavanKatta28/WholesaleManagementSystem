# 📦 Wholesale Management System – Group 19

> A complete data-driven project designed to manage and optimize wholesale business operations using SQL, Python, and Power BI.

---

## 👥 Team Members
- Parv Patel  
- Ansh Vaghela  
- Saipavan Katta  
- Nidhi Samarth  
- Sajiri Gokak  

---

## 🚀 Project Workflow (Start to End)

This project was executed in multiple well-defined stages, each simulating real-world data pipeline and system-building practices. Here's how it was done:

---

### 🧠 1. Problem Understanding & Proposal

We began by identifying a real-world problem: **inefficient operations in wholesale businesses** due to:
- Manual inventory tracking
- Disconnected customer and supplier records
- Lack of automation in reordering
- No centralized data for business insights

📄 We proposed a solution: **a centralized Wholesale Management System** that manages all entities through a relational database, backed by automation and reporting tools.

📝 **Document:** `P1.Project Proposal Group 19.pdf`

---

### 🧱 2. Database Design & Planning

We modeled the entire system using **Entity-Relationship Diagrams (ERD)**.

Key Design Elements:
- **Normalized to 3NF** for reduced redundancy
- **Primary & Foreign Keys** to maintain integrity
- Use of **subtypes**, like `ActiveCustomer` and `InactiveCustomer`
- **Associative Entities** like `OrderLine`, `DepletedProduct`, and `ProductInventory`

📄 **Initial Design:** `P2.Database Design, initial ERD.pdf`  
📄 **Final Model:** `P3.Final ERD.pdf`

---

### 🛠️ 3. Database Implementation in SQL Server

Using **Microsoft SQL Server**, we built the backend with:

✅ 16 Tables  
✅ 7 Stored Procedures  
✅ 6 Views  
✅ 1 Trigger  
✅ 1 User-Defined Function (UDF)  
✅ Computed Columns  
✅ Column-level Encryption

📂 SQL Files:
- `P4_Create_Table.sql`: Schema creation
- `P4_Insert_Query.sql`: Sample data
- `Encryption Function Trigger Views Procedure.sql`: Logic & automation

---

### 🧑‍💻 4. Python GUI for Data Entry

We developed a **PyQt5 GUI application** to allow business users to:
- View customer records
- Add new customers
- Update or delete customer profiles

🖥️ **Tech Stack:**
- `PyQt5` for GUI design
- `pyodbc` for SQL Server connectivity
- Clean UX with custom-styled input fields

📂 Python File: `gui.py`

---

### 📊 5. Power BI Dashboard for Data Analytics

To make the system truly data-driven, we built an interactive **Power BI dashboard** that visualizes:

- 📦 Inventory status  
- 📈 Sales trends  
- 🛍️ Customer activity  
- 🚚 Supplier performance  
- 💳 Payment and order history  

This dashboard provides **real-time business insights**, empowering leadership to make data-informed decisions.

🔗 [View Power BI Dashboard](https://app.powerbi.com/groups/me/reports/6ced0e12-a97d-4059-9701-dea157d25409/ReportSection?experience=power-bi)

---

### ✅ 6. Testing & Documentation

We verified:
- Data integrity via constraints and triggers  
- Business logic via stored procedures  
- UI behavior via user testing

📝 Documentation includes:
- ER diagrams
- Proposal and design writeups
- SQL scripts and business logic
- GUI and dashboard links
- This README for walkthrough

---

## 🧠 Key Concepts & Skills Demonstrated

| Area                  | Description |
|-----------------------|-------------|
| **Data Modeling**     | ERD, normalization (3NF), relationships |
| **SQL Development**   | DDL, DML, procedures, views, triggers |
| **Python Scripting**  | GUI design (PyQt5), DB interaction (`pyodbc`) |
| **Business Intelligence** | Power BI dashboards, KPIs, filtering |
| **Data Governance**   | Constraints, encryption, consistency |
| **Team Collaboration**| Project planning and integration |

---

