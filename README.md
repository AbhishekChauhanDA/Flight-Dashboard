✈ Airport Analytics — SQL Project

Overview
End-to-end SQL analysis project built on a relational flight management database using Microsoft SQL Server. The project covers flight operations intelligence, airline revenue benchmarking, passenger CRM insights, and route-level pricing analysis.

Database
Five relational tables: Airports, Airlines, Flights, Passengers, Tickets — connected via foreign keys across 5 airports, 5 airlines, 16 flights, 25 passengers, and 54 ticket records.

Analysis — 8 queries
| # | Question | Area |
|---|----------|------|
| Q1 | Busiest airport by takeoffs | Operations |
| Q2 | Total tickets sold per airline | Revenue |
| Q3 | IndiGo flights with airport names | Operations |
| Q4 | Top airline per departing airport | Strategy |
| Q5 | Flight duration & Short/Medium/Long category | Operations |
| Q6 | Passenger first, last flight & total count | CRM |
| Q7 | Highest ticket price per route | Revenue |
| Q8 | Top spender per frequent flyer tier | CRM |

SQL concepts
JOIN · RANK() OVER (PARTITION BY) · CTE · DATEDIFF · CASE WHEN · Correlated subquery · MIN/MAX aggregation · FETCH NEXT

Tools
Microsoft SQL Server · SQL Server Management Studio (SSMS)
