#  #Daikin_Plant_Operations – Entity Relationship Diagram (ERD)

##  #Submitted_By  
🔹 **Name:** Khushi Kalra  
🔹 **Roll No:** 055021  

---

##  #Project_Overview  
 This project presents an **Entity-Relationship Diagram (ERD)** for the **Daikin Plant Operations** in **Neemrana, Rajasthan**.  
 The ERD models key processes including:  
   - **#Manufacturing**   
   - **#Inventory_Management**  
   - **#Supplier_Relations**   
   - **#Quality_Control**  
   - **#Logistics & Distribution**  
   - **#Workforce_Management**  

---

##  #ERD_Details  

### 🔹 #Entities_&_Attributes  
 **#Manufacturing**  – Tracks production, assembly line, and workforce.  
**#Inventory**  – Manages stock levels of raw materials and finished goods.  
**#Suppliers**  – Maintains details of vendors providing raw materials.  
**#Orders**  – Records procurement and product dispatches.  
**#Quality_Control**  – Ensures defect tracking and compliance.  
**#Logistics**  – Handles product transportation and delivery.  
**#Employees_&_HR**  – Manages workforce details and training.  

---

##  #Relationships_&_Cardinality  
🔹 **#Suppliers (1) → (N) Orders** *(A supplier provides multiple orders, but each order comes from one supplier)*  
🔹 **#Orders (1) → (N) Inventory** *(One order updates multiple inventory records)*  
🔹 **#Manufacturing (1) → (N) Inventory** *(One production batch produces multiple inventory items)*  
🔹 **#Quality_Control (1) → (N) Products** *(Each QC check applies to multiple products, but each product has one QC check)*  
🔹 **#Logistics (1) → (N) Orders** *(One logistics record handles multiple orders, but each order has one logistics record)*  
🔹 **#Employees (1) → (N) Manufacturing/Quality Control** *(One employee can be involved in multiple processes, but each process has specific employees assigned)*  

---

## #Tools_Used  
**Lucidchart AI** – For generating and visualizing the **ERD diagram**.  
**Markdown (README.md)** – For documentation.  

---

##  #How_To_View  
 Open the **ERD diagram** in **Lucidchart AI**.  
 Analyze entity relationships and operational workflow of Daikin’s plant.  
 Use the diagram for **process optimization, supply chain efficiency, and workforce management insights**.  

---
