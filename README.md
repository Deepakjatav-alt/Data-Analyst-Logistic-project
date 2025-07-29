# ShopX Courier Charges Verification – Data Analysis Project

ShopX Courier Charges Verification – Data Analysis Project
📘 Project Overview
This project simulates a real-world data analysis task for a large Indian e-commerce company, ShopX, which incurs significant monthly courier charges for delivering customer orders. The objective is to audit courier invoices by validating the charges based on internal order, product, and zone data.

🎯 Business Problem
ShopX receives over 2 lakh orders per month and pays around ₹2 crores monthly to courier companies. Since charges depend on product weight and delivery zone, ShopX suspects possible overcharging and wants to verify the accuracy of these courier invoices.

📂 Input Data
The analysis is based on data from multiple sources:

🔸 ShopX Internal Data
Order Report

Order ID, Product Code, Units Ordered

Product Weight Data

Product Code, Product Weight (in grams)

Warehouse & Customer Zone Mapping

Store House Pincode, Customer Area Code, Delivery Zone (A–E)

🔸 Courier Company Data
Courier Invoice

AWB Code, Order ID, Chargeable Weight, Delivery Zone, Total Amount, Freight Type

Rate Card

Fixed & Additional charges by zone and weight slab, for both Forward and RTO

🔍 Project Goals
Recalculate the correct weight slab and expected delivery charges for each order using internal product and zone data.

Compare calculated charges with actual courier invoices.

Identify orders where ShopX has been:

Correctly charged

Overcharged

Undercharged

 Output
✅ Output File 1: Order-wise Verification (order_level_analysis.xlsx)
Contains the following columns:

Order ID

AWB Number

Total Weight (ShopX)

Weight Slab (ShopX)

Chargeable Weight (Courier)

Weight Slab (Courier)

Delivery Zone (ShopX)

Delivery Zone (Courier)

Expected Charge (₹)

Billed Charge (₹)

Difference (₹)

