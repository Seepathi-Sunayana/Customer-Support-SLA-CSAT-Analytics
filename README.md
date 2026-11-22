# Customer Support - SLA & CSAT Analytics | Power BI

## Problem
1,404 support tickets. Customers were leaving because Refund tickets took 8.12 hrs to resolve - 15% longer than average.

## What I Built
2-page Power BI decision dashboard to track SLA, CSAT and ticket volume.
Page 1: Overview - KPI Cards, Trend, By Category, By Priority
Page 2: Deep Dive - Decomposition Tree, Forecast, AI Insight

## Key Findings
1. Refund tickets take 8.12 hrs - highest resolution time
2. SLA Breach Rate is highest in Refund queue
3. CSAT drops when resolution time goes above 8 hrs
4. Ticket volume is stable at 2-4 tickets/day

## Recommendations
1. Add 1 more agent to Refund queue if SLA breach > 15%
2. Create auto-reply for Refund tickets to improve CSAT
3. Review tickets that take > 24 hrs every Monday

## DAX Measures
- Total Tickets = COUNT(Tickets)
- SLA Breach % = Breached / Total Tickets
- MTTR = AVERAGE(Resolution Hours)
- Avg CSAT = AVERAGE(Satisfaction)
- Repeat Ticket Rate = Tickets from same customer > 1

## AI Features
- Decomposition Tree - root cause of SLA breach
- Forecast - predict next 30 days ticket volume
- Smart Narrative - auto summary

## Tools
Power BI, DAX, Excel / CSV
