# sap-sd-o2c
# SAP SD Capstone Project – Order-to-Cash (O2C)

This project demonstrates the complete **Order-to-Cash (O2C)** business cycle using the SAP Sales and Distribution (SD) module. It covers the full flow from customer creation to payment processing.

---

## 📌 Project Overview

The O2C process integrates Sales, Logistics, and Finance into a single automated workflow. This project simulates a real-world business scenario for a fictitious company **GlobalTech Innovations (Wholesale Hardware Division)**.

---

## 🔄 O2C Process Steps

1. **Customer Master (XD01)**  
   Create customer details (address, payment terms, FI integration)

2. **Inquiry (VA11)**  
   Record customer’s initial request

3. **Quotation (VA21)**  
   Generate a formal offer (created with reference to Inquiry)

4. **Sales Order (VA01)**  
   Confirm customer purchase (ATP check performed)

5. **Delivery & PGI (VL01N)**  
   Ship goods and update inventory

6. **Billing (VF01)**  
   Generate invoice and post financial entries

7. **Incoming Payment (F-28)**  
   Record payment and clear customer account

---

## 🛠 Tech Stack

- **Platform:** SAP S/4HANA / SAP ECC  
- **Core Module:** SAP SD (Sales & Distribution)  
- **Integrated Modules:**
  - SAP MM (Inventory Management & ATP)
  - SAP FI (Accounting & Payment Processing)

---

## 🚀 Key Features

- End-to-end O2C implementation  
- Real-time integration between SD, MM, and FI  
- Zero data redundancy using "Create with Reference"  
- Real-world mapping to Amazon-style workflow  
- Structured and easy-to-understand process flow  

---
## 👤 Author

**Purushottam Kumar**  
Roll No: 23053230  
KIIT University  

---


## 📌 Note

This project is created for academic purposes and demonstrates SAP SD concepts in a structured and practical way.
