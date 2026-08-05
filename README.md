# NYC 311 Service Requests Analytics

## By Siavash Rahkooh

## Overview

This project analyzes NYC 311 service requests to identify high-demand complaint types, borough hotspots, resolution delays, and operational recommendations.

The goal is to help city service teams understand where to focus resources and improve response time.

---

## Dataset

NYC 311 Service Requests sample dataset.

The dataset includes:

- Complaint type
- Agency
- Borough
- Created date
- Closed date
- Request status

---

## Tools

- Python
- pandas
- matplotlib
- seaborn

---

## Core Analysis Questions

### 1. What are the top 10 most frequent complaint types in NYC?
Identifies the most common issues reported by residents (e.g., Noise, Heating, Street Conditions) to understand where city services face the highest operational demand.

### 2. Which city agencies receive the highest volume of service requests?
Evaluates the workload distribution across different city departments (e.g., NYPD, HPD, DOT) to identify which organizations require the most operational support and funding.

### 3. Which borough generates the highest number of complaints?
Compares request distribution across Brooklyn, Bronx, Manhattan, Queens, and Staten Island to identify macro-level geographic hotspots that require broader attention.

### 4. Which specific ZIP codes generate the highest number of requests?
Drills down into neighborhood-level data to pinpoint exact micro-locations where city infrastructure or services are failing most frequently.

### 5. How have complaint volumes changed over time, and are they seasonal?
Analyzes monthly trends to determine if specific complaints spike during certain times of the year (e.g., heating in winter), allowing for proactive resource allocation.

### 6. What is the average resolution time for each major complaint type?
Measures operational efficiency by tracking how long it takes different departments to close tickets, highlighting bottlenecks in the city's repair workflow.

### 7. Which complaint types have the highest percentage of unresolved cases?
Identifies systemic failures by looking at the ratio of open/pending tickets versus closed tickets, revealing which issues the city struggles to fix permanently.

### 8. What operational recommendations can improve service performance?
Synthesizes the data findings into actionable business strategies for city management to optimize staffing, adjust Service Level Agreements (SLAs), and deploy targeted prevention programs.

---

## Business Recommendations

Based on the data analysis, the following operational strategies are recommended for city management:

1. **Micro-Targeted Resource Allocation:** Deploy specialized maintenance crews and sanitation resources directly to the top 5 highest-volume ZIP codes rather than spreading resources evenly across a whole borough.
2. **Optimize Departmental Staffing:** Increase shift allocations in agencies handling the top complaint types that currently show the longest average resolution times.
3. **Address Systemic Unresolved Issues:** Launch root-cause task forces for complaint categories with the highest percentage of open/pending cases to prevent recurring backlog.
4. **Seasonal Preparedness:** Pre-position equipment and staff ahead of predictable seasonal spikes identified in the monthly trend analysis.
5. **SLA Adjustments:** Review and adjust Service Level Agreements (SLAs) for complaint categories that consistently exceed their target resolution times to set realistic public expectations.
## Expected Outputs

- Top complaint types chart
- Requests by borough chart
- Resolution time analysis
- Agency backlog analysis
- Simple next-month demand estimate
- Resource allocation recommendations

---

## Project Status

In progress.

Current step:

- Repository created
- README updated
- Analysis questions finalized

Next step:

- Load dataset
- Clean dataset
- Start descriptive analysis
