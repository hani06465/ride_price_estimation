 Ride Price Estimation System

   ==> Project Overview
This project is an end-to-end machine learning system designed to estimate ride prices based on various trip and contextual factors. It covers the full ML workflow: from synthetic dataset design to model implementation and ethical reflection.

   ==> Dataset Description
The dataset was synthetically generated to simulate real-world ride-hailing data. It contains 200 records with the following features:

   ==> Features and Justification
1.  Distance (km): Essential for calculating base price.
2.  Trip Duration (min): Time-based costs are a standard industry practice.
3.  Time of Day: Captures peak vs. off-peak pricing trends (Morning, Afternoon, Evening, Night).
4.  Traffic Level: High traffic increases duration and operational costs.
5.  Weather Condition: Extreme weather often triggers surge pricing.
6.  Demand Level: High demand leads to surge multipliers.
7.  Ride Type: Different service tiers (Economy, Premium, SUV) have different base rates.
8.  Day Type: Weekends and holidays often show different pricing patterns compared to weekdays.

Target Variable: "ride_price" (Continuous numerical).


