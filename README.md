Description

This project delivers a unified analytics framework to measure the overall impact of medical congress participation by integrating scientific (abstract), engagement (social/tag), and perception (survey) data. It enables a comprehensive evaluation of congress effectiveness for a top Fortune 500 pharmaceutical organization within the Real-World Evidence (RWE) domain.

Business Context

Medical congresses require significant investment and play a critical role in shaping scientific discourse, stakeholder engagement, and competitive positioning. However, insights are often fragmented across multiple data sources. This solution addresses that gap by consolidating disparate datasets into a single, structured analytics framework to support leadership decision-making.

Objectives
Establish a unified view of congress performance across scientific, engagement, and perception dimensions
Enable cross-functional insights for medical, commercial, and strategy teams
Standardize KPI measurement through a scalable data model
Support data-driven optimization of congress participation strategies
Solution Overview

The solution integrates three core data layers:

Scientific Layer (Abstract Data)
Captures clinical trials, therapy areas, products, and session-level insights
Engagement Layer (Tag/Social Data)
Measures real-time digital engagement, sentiment, and KOL activity
Perception Layer (Survey Data)
Evaluates post-congress feedback including recall, satisfaction, and behavioral intent

These layers are unified through a centralized data model enabling end-to-end analytics.

Data Architecture
Designed a scalable Entity Relationship Model (ERD) integrating all datasets
Implemented a fact-dimension schema for analytical efficiency
Established bridge tables to handle many-to-many relationships (e.g., Study–Tweet, Study–Abstract)
Standardized join keys across datasets (Study, Product, Congress)
Analytical Framework

The project follows the Mu Sigma PDNA (Problem DNA) framework:

Situation: Define current gaps in congress impact measurement
Representation: Structure data into unified analytical layers
Hypothesis: Evaluate relationships between scientific output, engagement, and perception

Supporting artifacts include:

Business Requirement Document (BRD)
Analytical Data Flow (ADF) diagrams
Data Processing and Logic
Performed data extraction, transformation, and integration using SQL
Implemented cohort definition logic using SAS (inclusion and exclusion criteria)
Engineered KPIs across all analytical layers
Ensured data consistency and normalization across sources
Visualization and Reporting
Developed interactive dashboards using Power BI
Created measures and calculated fields using DAX
Delivered three primary analytical views:
Scientific Impact View
Engagement Analytics View
Perception and Outcome View
Key Capabilities
Multi-source data integration across pre-, during-, and post-congress phases
Cross-layer analytics linking scientific output to engagement and perception
KPI-driven performance measurement framework
Scalable and reusable architecture for future congress analysis
Key Metrics
Abstract volume and therapy coverage
Social engagement and sentiment analysis
KOL contribution and influence
Brand recall and booth engagement
Prescription and trial intent
Composite congress impact score
Technology Stack
SQL for data transformation and querying
Power BI for visualization and dashboarding
DAX for KPI calculations
SAS for cohort definition logic
Data Modeling (ERD, Star Schema)
PDNA Framework for structured analytics
Outcomes
Delivered a unified view of congress performance across multiple dimensions
Enabled actionable insights for medical, commercial, and strategy teams
Improved visibility into the effectiveness of scientific communication and stakeholder engagement
Established a scalable analytics framework for future use
Future Enhancements
Integration of real-time data pipelines
Advanced NLP for topic modeling and sentiment refinement
Predictive analytics to model engagement-to-perception impact
Disclaimer

This project is based on a real-world use case for a top Fortune 500 pharmaceutical organization. All sensitive and proprietary information has been anonymized.
