# Retail Waste & Infrastructure Optimization Dashboard

## 📌 Project Description

This project focuses on a data-driven transformation of retail operations to combat a **$1.2M+ annual waste problem**. By analyzing a dataset of 16 days of retail transactions, spoilage records, and store infrastructure data, I developed a dual-layered diagnostic tool.

The dashboard doesn't just report "what" happened; it utilizes advanced DAX modeling to answer **"why"** it happened, isolating failures in cold-chain logistics and procurement bottlenecks. The end goal is a prescriptive roadmap to recover capital through targeted infrastructure investment and inventory precision.

## 🎯 Business Problem

The retailer faced high spoilage rates (averaging 43.8%) but lacked the visibility to determine if the cause was environmental or operational.

* **The Financial Risk:** $11.78M in projected annual waste.
* **The Infrastructure Gap:** High loss in the West Zone suggested equipment failure.
* **The Procurement Gap:** Overstocking was leading to items expiring before they reached the shelf.

## 🛠️ Technical Deep Dive: The DAX Story

I built this project using a "Financialization First" approach, turning raw unit counts into actionable currency.

### 1. Cold Chain & Infrastructure Analysis

I isolated **$341.94K** in "Uncooled Loss" by creating the `Loss No Cooling` measure.

* **Key Discovery:** Using the `Infra Gap %` measure, I proved that stores without cooling support have a **16.26% higher spoilage rate** than those with support.
* **Strategic Outcome:** Identified the specific Meat and Produce categories (accounting for over 68% of loss) that justify immediate refrigeration upgrades.

### 2. Inventory Optimization Logic

I identified **$621.47K** in "Trapped Capital" by calculating the delta between current stock and ideal safety levels.

* **Root Cause Visualized:** Through a Scatter Plot of **Stock Coverage vs. Days Until Expiry**, I revealed that the average stock duration (**12.36 days**) significantly exceeds the average product shelf-life (**7.15 days**).
* **Precision Targeting:** The "Top 10 High-Risk Items" bar chart isolates specific SKUs (Mutton Mince, Chicken Breast) where procurement adjustments would yield the highest immediate ROI.

## 🚀 Key Features

* **Interactive Efficiency Slider:** A What-If parameter allowing stakeholders to project annual savings based on 10% to 50% improvement targets.
* **Dynamic Status Labeling:** DAX-driven `Inventory Status` columns that automatically flag items as "CRITICAL" for immediate clearance or donation.
* **Infrastructure Priority Map:** Visualizes geographic "hotspots" where capital expenditure (CapEx) is required most urgently.

## 📈 Impact & Results

* Identified a clear path to **$4.71M in annual savings** through a 40% efficiency improvement.
* Provided a data-backed justification for cold-chain investment in the **West Zone**.
* Supported **ESG (Environmental, Social, and Governance) goals** by creating a framework to divert at-risk inventory to donation streams before spoilage.
