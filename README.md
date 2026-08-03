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

## Analysis Questions

### 1. What are the top 5 complaint types in NYC?

This question looks at the most common problems reported by residents, such as heating issues, plumbing problems, noise complaints, street light failures, or sanitation issues.

The goal is to understand which complaint categories create the highest demand for city services.

---

### 2. Which borough has the highest number of service requests?

This question compares service request volume across NYC boroughs, such as Brooklyn, the Bronx, Manhattan, Queens, and Staten Island.

The goal is to identify geographic hotspots where residents report more issues and where service capacity may need more attention.

---

### 3. Which complaint type has the longest average resolution time?

This question measures how long it takes for different complaint types to move from created date to closed date.

The goal is to find which issues are slower to resolve and may require better processes, more staff, or clearer ownership.

---

### 4. Which agency has the highest number of open or pending requests?

This question checks which agencies currently have the largest backlog of unresolved service requests.

The goal is to identify operational pressure points and understand where follow-up or additional resources may be needed.

---

### 5. Which complaint type is likely to have the highest request volume next month?

This question uses historical request trends to estimate which complaint category may increase in the near future.

The goal is to help service teams prepare in advance for expected demand instead of reacting after requests increase.

---

### 6. Which borough should receive priority resource allocation?

This question combines request volume, complaint frequency, and unresolved cases to recommend where the city should focus resources first.

The goal is to support better planning for staffing, maintenance teams, and service operations.

---

### 7. What response-time target should be set for the most frequent complaint types?

This question uses past resolution time data to propose realistic service-level targets for common complaint categories.

The goal is to help the city set clear expectations for how quickly different types of issues should be resolved.

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
