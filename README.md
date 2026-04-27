# 🛒 Grocery Store Operations Simulation (Arena) - Computer-Modelling

## 📌 Project Overview
This repository contains Phase 1 (Group Assignment 1) of a discrete-event simulation project built using **Rockwell Arena Simulation Software**. The goal of this phase was to establish a functional, baseline model of a local grocery store's daily operations to understand initial customer flow and system capacity.

## ⚙️ The Baseline Model
The model simulates a 3-day operational period (12 hours/day) with a maximum store capacity of 12 customers at a time. Customers are routed probabilistically to different shopping paths: Fresh Produce Only, Butchery Only, or Both.

**Key Features:**
* **Customer Routing & Gatekeeping:** A "Hold" logic ensures no more than 12 customers enter the store at once.
* **Balking Logic:** Customers check aisle queues and will skip shopping if lines are too long.
* **Initial Findings:** The baseline model successfully tracked customer movement but revealed significant waiting times at the checkout counter, indicating a primary bottleneck.

*(Note: Refinements and "What-If" optimization scenarios are covered in the GA2 repository/file).*
