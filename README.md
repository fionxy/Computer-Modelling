# 🛒 Grocery Store Operations Simulation (Arena) - Computer-Modelling
# 📌 Project Overview
This repository contains a discrete-event simulation model of a local grocery store, built using Rockwell Arena Simulation Software. The purpose of this project is to analyze customer flow, identify operational bottlenecks, and evaluate potential business improvements through "What-If" scenario testing.

# 🎯 Objectives
Model Customer Behavior: Simulate realistic foot traffic routing through different departments (Fresh Produce, Butchery, or Both).

Identify Bottlenecks: Analyze resource utilization to find points of friction in the customer journey.

Optimize Operations: Propose and simulate solutions to reduce waiting times and improve overall system throughput.

# ⚙️ The Simulation Model
The baseline model simulates a 3-day operational period (12 hours/day) with a maximum store capacity of 12 customers at a time. Customers are probabilistically assigned to different shopping paths, each with its own service times and queuing logic.

Key Baseline Findings:

Average Time in System: ~43 minutes per customer.

System Throughput: ~1,255 customers served over 3 days.

Primary Bottleneck: The Checkout Cashier reached 92% utilization, causing significant queue accumulation and pushing average wait times to nearly 30 minutes.

# 🧪 "What-If" Scenario Analysis
To address the bottleneck at the checkout counter, two alternative scenarios were modeled and compared against the baseline:

Scenario A (Increased Staffing): Adding a second cashier to the schedule to alleviate the checkout queue.

Scenario B (Increased Capacity): Raising the maximum store capacity from 12 to 20 customers to observe the impact on internal aisle congestion (e.g., Fresh Produce and Butchery).
