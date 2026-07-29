# 🏥 NorthBridge Health Services – Customer Service Ticket & SLA Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-yellow)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Dashboard](https://img.shields.io/badge/Dashboard-Data%20Visualization-purple)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-Operational%20Analytics-orange)

---

# Project Overview

This project analyzes customer service operations for **NorthBridge Health Services Ltd**, a fictional healthcare administration and operational support organisation, using **Power BI**. The objective was to monitor service performance, evaluate Service Level Agreement (SLA) compliance, analyse ticket operations, assess workforce capacity, and provide actionable business recommendations to improve operational efficiency.

Interactive dashboards were developed using **Power BI, Power Query, DAX, and data modelling techniques** to transform operational ticket data into meaningful business insights. The final solution provides executive-level reporting that enables management to monitor customer service performance, identify operational bottlenecks, and support strategic decision-making.

---

# Business Problem

NorthBridge Health Services processes thousands of customer service requests every month across appointments, billing, insurance, referrals, complaints, and medical records.

As customer demand increased, the organisation experienced several operational challenges, including:

- Increasing ticket volumes
- Rising response and resolution times
- Frequent SLA breaches
- Growing ticket backlogs
- Uneven workload distribution across agents
- Limited visibility into operational performance
- Manual reporting processes that delayed decision-making

Management required an interactive reporting solution capable of monitoring operational performance, identifying service risks, and supporting proactive decision-making across the customer service function.

---

# Project Objectives

- Centralise customer service reporting into a single Power BI solution.
- Monitor operational performance through executive KPIs.
- Track SLA compliance and breach rates.
- Analyse ticket volumes across categories, priorities, channels, and regions.
- Evaluate workforce capacity and workload distribution.
- Improve operational visibility for management.
- Support data-driven decision-making through interactive dashboards.

---

# Key Questions

- How many customer service tickets were processed during the reporting period?
- What percentage of tickets met SLA targets?
- Which ticket categories generated the highest operational demand?
- Which communication channels handled the largest share of customer requests?
- Which regions generated the highest ticket volumes?
- Which ticket priorities contributed most to SLA breaches?
- How effectively were operational resources utilised?
- Where are the greatest opportunities to improve customer service performance?

---

# Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modelling
- Star Schema
- KPI Development
- Dashboard Design
- Data Visualization
- Business Intelligence
- Git & GitHub

---

# Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modelling
- Star Schema Design
- Power Query
- DAX
- KPI Development
- Dashboard Design
- Business Intelligence
- Operational Analytics
- SLA Performance Analysis
- Executive Reporting
- Data Storytelling
- Stakeholder Reporting

---

# Data Preparation

The dataset underwent several preparation and modelling steps before dashboard development:

- Validated and cleaned customer service ticket data.
- Reviewed data quality and corrected inconsistent data types.
- Built a Star Schema data model using fact and dimension tables.
- Established relationships between operational datasets.
- Created reusable DAX measures for KPI calculations.
- Developed calculated measures for SLA performance, ticket operations, and workload analysis.
- Designed interactive Power BI dashboards using slicers, KPI cards, and dynamic visuals.
- Organised dashboards to support both executive and operational reporting.

---

# Dataset Summary

| Metric | Value |
|------|------:|
| Total Tickets | 3,500 |
| Resolved Tickets | 3,301 |
| Open Tickets | 199 |
| SLA Compliance Rate | 79.5% |
| SLA Breach Rate | 20.5% |
| Active Agents | 48 |
| Regions | 4 |
| Communication Channels | 4 |
| Ticket Categories | 8 |
| Dashboards Developed | 4 |

> *The Power BI solution provides interactive filtering, allowing stakeholders to analyse operational performance by region, ticket category, communication channel, priority level, and reporting period.*

---

# Dashboard Overview
## Executive Summary Dashboard

The Executive Summary dashboard provides senior management with a consolidated view of customer service performance by bringing together the organisation's most critical operational KPIs into a single reporting interface. It enables decision-makers to quickly assess service performance, monitor SLA compliance, evaluate operational efficiency, and identify areas requiring immediate attention.

### Dashboard Features

- Total Tickets
- Resolved Tickets
- Open Tickets
- SLA Compliance Rate
- SLA Breach Rate
- Average First Response Time
- Average Resolution Time
- Monthly Ticket Trends
- Regional Performance Overview

### Key Insights

- NorthBridge processed **3,500 customer service tickets** during the reporting period, successfully resolving **3,301**, representing a resolution rate of over **94%**.
- Although ticket resolution remained high, **SLA compliance was 79.5%**, indicating that approximately one in every five tickets failed to meet contractual service targets.
- Ticket demand declined after the first quarter before stabilising, suggesting a more predictable workload during the latter part of the reporting period.
- Backlog levels continued to grow despite lower ticket volumes, highlighting inefficiencies in clearing outstanding requests.
- Manchester consistently generated the highest ticket volume, making it the primary operational hub requiring process optimisation and resource planning.

### Business Value

This dashboard provides executives with a high-level overview of operational performance, enabling faster strategic decision-making, improved SLA monitoring, and better visibility into overall customer service performance.

---

## Ticket Operations Dashboard

The Ticket Operations dashboard provides a detailed analysis of day-to-day customer service activity by monitoring ticket volumes, communication channels, service categories, regional distribution, and operational performance across the organisation.

### Dashboard Features

- Total Tickets
- Open Tickets
- Resolved Tickets
- Total Escalations
- Average First Response Time
- Average Resolution Time
- Ticket Categories
- Communication Channels
- Regional Ticket Distribution
- Monthly Ticket Volume

### Key Insights

- Appointment Change requests represented the highest proportion of customer enquiries, making them the largest contributor to operational workload.
- Email remained the most frequently used communication channel, indicating an opportunity to improve efficiency through automation or self-service options.
- Manchester processed the largest volume of customer requests throughout the reporting period.
- Most tickets progressed successfully through the customer service lifecycle despite increasing operational demand.
- Monthly ticket trends stabilised after the initial reporting period, supporting more accurate workforce planning and forecasting of future workloads.

### Business Value

This dashboard enables operational managers to understand demand patterns, allocate resources effectively, identify service bottlenecks, and improve overall customer service efficiency.

---

## SLA Risk Monitoring Dashboard

The SLA Risk Monitoring dashboard focuses on contractual service performance by monitoring SLA compliance, breach rates, escalation activity, and tickets approaching SLA deadlines. The dashboard supports proactive operational management by helping teams identify risks before service failures occur.

### Dashboard Features

- SLA Compliance Rate
- SLA Breach Rate
- Total SLA Breaches
- At-Risk Tickets
- Escalation Rate
- SLA Performance by Priority
- SLA Performance by Category
- Monthly SLA Trend Analysis

### Key Insights

- P3 Standard tickets contributed the highest proportion of SLA breaches, representing the greatest opportunity for operational improvement.
- SLA compliance varied across ticket categories, highlighting inconsistencies in service delivery processes.
- At-risk tickets provided an early warning mechanism that enabled operational teams to intervene before contractual deadlines were exceeded.
- Monthly SLA performance fluctuated throughout the reporting period, suggesting recurring operational challenges rather than isolated incidents.
- Escalation activity closely mirrored SLA performance, demonstrating the relationship between delayed ticket resolution and increased operational risk.

### Business Value

This dashboard enables proactive SLA management by helping operational teams prioritise high-risk tickets, reduce contractual breaches, improve response times, and strengthen customer service performance.

---

## Workload & Capacity Dashboard

The Workload & Capacity dashboard evaluates workforce utilisation by monitoring agent capacity, workload distribution, operational efficiency, and staffing requirements. It provides management with valuable insights into how effectively available resources are being utilised.

### Dashboard Features

- Active Agents
- Available Daily Capacity
- Capacity Utilisation
- Capacity Gap
- Average Tickets per Agent
- Workload Distribution
- Agent Performance
- Operational Capacity Overview

### Key Insights

- Capacity utilisation remained below available operational capacity, indicating opportunities to improve workforce allocation.
- Workload distribution varied significantly across agents, suggesting that resources were not being utilised evenly.
- The large capacity gap indicated that operational challenges were driven more by workload distribution and prioritisation than staffing shortages.
- Monitoring agent workloads provides management with valuable insights for workforce planning and scheduling decisions.
- Improving workload balancing could reduce SLA breaches while increasing overall operational efficiency.

### Business Value

This dashboard supports workforce planning by helping management optimise staffing levels, balance workloads, improve operational efficiency, and maximise customer service performance.

---

# Dashboard Preview

## Executive Summary

![Executive Summary](Dashboard%20Images/Executive%20Summary.jpg)

---

## Ticket Operations

![Ticket Operations](Dashboard%20Images/Ticket%20Operations.jpg)

---

## SLA Risk Monitoring

![SLA Risk Monitoring](Dashboard%20Images/SLA%20Risk%20Monitoring.jpg)

---

## Workload & Capacity

![Workload & Capacity](Dashboard%20Images/Workload%20%26%20Capacity.jpg)

---

# Interactive Features

- Executive KPI Cards
- Interactive Slicers
- Dynamic Cross-Filtering
- Drill-Down Visualizations
- Regional Performance Analysis
- Category & Priority Filtering
- Communication Channel Analysis
- Dynamic Operational Reporting

---

# Key Findings

- NorthBridge successfully resolved over **94%** of customer service tickets during the reporting period, demonstrating strong operational throughput.
- SLA compliance remained below the desired organisational target, indicating that improvements are needed to reduce delayed responses and contractual breaches.
- Appointment Change requests generated the highest operational workload, making them the primary opportunity for process optimisation.
- Manchester consistently recorded the highest ticket volumes across all regions, highlighting the need for targeted resource allocation.
- Email remained the dominant communication channel, suggesting opportunities to improve efficiency through automation and self-service solutions.
- P3 Standard tickets accounted for the highest proportion of SLA breaches, representing the greatest operational risk.
- Capacity utilisation indicated that workforce resources could be distributed more effectively to improve productivity and reduce response times.
- Executive KPI monitoring enabled stakeholders to quickly identify operational trends and make informed business decisions.

---

# Recommendations

1. Optimise Appointment Change workflows to reduce operational demand and improve processing efficiency.
2. Implement automated alerts for tickets approaching SLA deadlines to minimise contractual breaches.
3. Improve workload balancing across customer service agents to maximise available operational capacity.
4. Investigate recurring causes of SLA breaches within P3 Standard tickets and introduce targeted process improvements.
5. Expand self-service options for routine customer enquiries to reduce dependency on email support.
6. Regularly review executive KPIs to support proactive operational management and continuous service improvement.
7. Monitor regional workload trends to ensure staffing resources remain aligned with customer demand.

---

# Business Impact

This Business Intelligence solution provides NorthBridge Health Services with a centralised reporting platform that significantly improves operational visibility across customer service activities. By consolidating ticket operations, SLA performance, and workforce capacity into a single interactive Power BI solution, management can quickly identify service bottlenecks, monitor organisational performance, and make evidence-based decisions.

The dashboards enable proactive SLA management, improved workload allocation, enhanced operational efficiency, and reduced reliance on manual reporting. These insights support continuous service improvement while helping the organisation deliver a more responsive and reliable customer experience.

---

# Key Learnings

Through this project, I strengthened my ability to:

- Build end-to-end Business Intelligence solutions using Power BI.
- Design Star Schema data models for analytical reporting.
- Develop reusable DAX measures for KPI reporting.
- Perform operational performance and SLA analysis.
- Design executive-level interactive dashboards.
- Transform complex operational data into meaningful business insights.
- Communicate analytical findings to both technical and non-technical stakeholders.
- Apply data storytelling techniques to support business decision-making.

---

# Repository Contents

| File | Description |
|------|-------------|
| NorthBridge.pbix | Interactive Power BI dashboard |
| NorthBridge Dataset.xlsx | Dataset used for analysis |
| NorthBridge Dashboard.pdf | PDF export of all dashboards |
| Dashboard Images | JPEG previews of each dashboard |
| Presentation.pdf | Executive presentation summarising findings and recommendations |
| README.md | Project documentation |

---

# Author

**Sarah Abhulimhen**

MBA (Distinction) | Data Analyst

---

# Connect With Me

- **LinkedIn:** https://www.linkedin.com/in/sarah-abhulimhen-7353213ba/
- **GitHub Portfolio:** https://github.com/Sarah-Abhulimhen
- **Email:** sarahabhulimhen9@gmail.com

---

© 2026 Sarah Abhulimhen
