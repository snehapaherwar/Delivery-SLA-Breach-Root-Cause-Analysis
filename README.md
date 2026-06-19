# Delivery-SLA-Breach-Root-Cause-Analysis

## Problem Statement

A logistics company observed a 15% increase in late deliveries, leading to declining SLA compliance and increased customer dissatisfaction.

The objective was to identify operational bottlenecks contributing to delivery delays across:
- Delivery hubs
- Drivers
- Traffic conditions
- Weather conditions
- Delivery distances

The goal was to uncover root causes and recommend operational improvements.

## Business Questions
1. What is the overall SLA breach percentage?
2. Which hubs contribute most to delivery delays?
3. Does high order volume correlate with delays?
4. Which drivers consistently miss SLA targets?
5. Does driver experience affect delivery performance?
6. How does weather impact delivery delays?
7. Which time slots experience the highest delays?
8. What is the relationship between delivery distance and SLA breaches?

## Dataset
The analysis uses five tables:
- Orders
- Hubs
- Drivers
- Products
- Weather

Relationships:
Orders → Hubs
Orders → Drivers
Orders → Products
Orders → Weather

## KPIs Tracked
- SLA Breach %
- On-Time Delivery %
- Average Delay Time
- Delayed Orders
- Driver Performance Score
- Hub Performance
- Capacity Utilization

## Overall Delivery Health
Analysis revealed a high SLA breach rate across the delivery network.
Key Findings:
- Significant proportion of deliveries exceeded promised timelines.
- Delay severity increased during peak demand periods.
- Operational performance varied significantly across hubs.

## Hub Analysis
Findings:
- Bangalore East Hub recorded the highest delivery volume.
- High-volume hubs generally experienced higher delay percentages.
- Chennai South Hub demonstrated poor SLA performance despite lower order volume, indicating operational inefficiencies beyond workload.

## Driver Analysis
Findings:
- Drivers handling long-distance deliveries exhibited significantly higher delay rates.
- Driver experience showed a positive relationship with SLA compliance.
- Certain drivers consistently breached SLA targets, indicating opportunities for route optimization and training.

## Weather Analysis
Findings:
- Heavy rainfall conditions resulted in substantially higher average delays.
- Weather impact was amplified for long-distance deliveries.

## Peak Hour Analysis
Findings:
- Evening delivery windows showed the highest average delays.
- Increased traffic congestion significantly impacted SLA compliance.

## Distance Analysis
Findings:
- Delivery distance was one of the strongest predictors of delay.
- Orders above 12 km demonstrated significantly higher breach percentages.

## Recommendations
1. Introduce dynamic routing for long-distance deliveries.
2. Increase driver allocation during peak-hour demand.
3. Provide targeted training for low-performing drivers.
4. Adjust SLA commitments during adverse weather conditions.
5. Rebalance workloads across delivery hubs.
