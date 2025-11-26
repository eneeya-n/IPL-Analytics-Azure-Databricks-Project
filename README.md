# IPL Analytics Azure Databricks Project

## Project Overview
This repository contains a complete end-to-end **IPL Data Analytics Platform** developed using **PySpark on Azure Databricks**. The project converts raw historical IPL datasets (2008–2017) into structured, insight-ready information to support **sports analytics, strategic decision-making, and player/team performance evaluation**.

The solution is designed as a real-time industry case study showcasing enterprise-level data engineering and analytical capabilities using Databricks.

---

## Objectives of the Project
- Ingest IPL datasets into Databricks using **schema-based structured pipelines**
- Perform **data validation, cleaning, and feature enrichment**
- Build **SQL-driven cricket analytics** using Spark SQL and DataFrames
- Generate **deep performance insights** about:
  - Batsmen and bowlers
  - Toss decisions
  - Stadiums & run-scoring patterns
  - Dismissal types and match dynamics
  - Team performance consistency
- Visualize cricket trends within Databricks using Python

---

## Tech Stack
| Category | Tools / Technologies |
|---------|----------------------|
| Cloud Platform | Azure Databricks |
| Processing Engine | Apache Spark (PySpark) |
| Language | Python |
| Libraries | Matplotlib, Seaborn, Pandas |
| Storage Types | CSV / DBFS / Cloud Storage (ADLS / Blob Storage) |

---

## Repository Contents
| File / Folder | Description |
|--------------|-------------|
| `Case Study PySpark + Azure DB.pdf` | Case study describing all analytics tasks |
| `Solution_Notebook.ipynb` | Complete Databricks notebook containing solution |
| `IPL_Dataset.rar/` | IPL datasets (2008–2017) in CSV format |
| `README.md` | Repository documentation |

---

## Major Analytics Covered
The project addresses multiple high-value business insights including:

- Top-scoring batsmen per season
- Most effective powerplay bowlers
- Toss impact on match outcomes
- Venue-wise run scoring characteristics
- Most frequent dismissal types
- Team performance after winning the toss
- Long-term season-to-season consistency of teams and players
- Identification of matches with extreme anomalies (high/low scoring, high wicket counts)
- Player impact index for identifying high-value performers

---

## Sample Insights Delivered
The Databricks notebook generates analytical visualizations such as:
- Performance charts of top batsmen and bowlers
- Toss advantage vs match outcomes
- Venue-based heatmaps for run scoring
- Dismissal frequency distributions
- Team performance patterns across seasons

---

## How to Run the Project
1. Create a Databricks workspace and cluster  
2. Upload datasets to DBFS or mount cloud storage  
3. Import the notebook (`Solution_Notebook.ipynb`) into Databricks  
4. Attach the notebook to your running cluster  
5. Run all cells sequentially to reproduce analytics and visualizations  

