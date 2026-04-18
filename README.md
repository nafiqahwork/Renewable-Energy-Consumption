## Renewable Energy Consumption Analysis (USA)

## Project Overview

This analysis explores renewable energy consumption trends in the United States from 1973 to 2024, offering insights into growth patterns, energy composition, and sectoral distribution. An interactive Power BI dashboard presents key metrics such as total renewable energy usage, source breakdowns, and sector-level consumption patterns.

This project serves as a useful resource for policymakers, sustainability analysts, and industry stakeholders aiming to understand the evolution and current landscape of renewable energy adoption in the U.S.

-----

## Dashboard Visualization

[**View Live Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMTJhY2FhN2QtOTc5ZC00ZGFmLWJhZTgtNDA0NjA2YTUwMmVkIiwidCI6Ijg4ZDQ0NWU1LWU5YjAtNGNkMy04MTVmLTQwZjhhMzAwOWI0MiIsImMiOjEwfQ%3D%3D)

The analysis was finalized into an interactive Power BI dashboard to present insights visually

The analysis focuses on four key dimensions of renewable energy consumption:

Historical Consumption Trends – Long-term developments in renewable energy adoption
Energy Source Composition – Distribution across various renewable energy types
Sectoral Consumption – Usage across industrial, residential, commercial, and transportation sectors
Source-Sector Relationships – Interaction between energy sources and consumption sectors

-----

## Dataset Description
The data model is structured to support efficient time-series analysis of renewable energy consumption.
Tables
Dataset: 
The main fact table containing detailed consumption records with the following fields:
- Energy Source: Type of renewable energy (e.g., Biomass, Solar, Wind)
- FactDate: Date of consumption record
- Month: Numeric month identifier
- Month Name: Month in text format
- Sector: Consumption sector (Industrial, Residential, Commercial, Transportation)
- Value (TBTU): Consumption in trillion British thermal units
- Year: Year of record

DateTable:
A date dimension table designed for time-based analysis, including:
- Date: Full date field
- Month: Numeric month
- Month Number: Sequential month index
- Month Year: Combined month and year
- Quarter: Calendar quarter

Measures:
A separate table containing calculated metrics, such as:
- Baseline: Reference values for comparison

-----

## Data Model Relationships
The model follows a star schema design, with the Dataset as the central fact table linked to the DateTable via the FactDate field. This structure enables efficient and flexible time-based analysis and visualization.

### Executive Summary

## Overview of Findings
The analysis highlights notable growth and evolving patterns in U.S. renewable energy consumption over the past five decades:

- Total renewable energy consumption reached 384,036.57 TBTU in the most recent data
- Biomass energy is the leading renewable source, contributing the largest share
- The industrial sector is the primary consumer, followed by the residential sector
- Consumption trends show both seasonal variation and strong long-term growth

## Key Metrics
| Metric                             | Value                                                |
| ---------------------------------- | ---------------------------------------------------- |
| Total Renewable Energy Consumption | 384,036.57 TBTU                                      |
| Top Renewable Source               | Biomass Energy                                       |
| Leading Consumption Sector         | Industrial                                           |
| Historical Growth Pattern          | Steady increase with faster growth in recent decades |


## Insights Deep Dive

Category 1: Historical Consumption Trends
Key observations from the time-series analysis include:
Renewable energy consumption has increased significantly since the 1970s, with accelerated growth starting in the early 2000s
The trend includes periodic fluctuations, likely influenced by economic cycles, policy shifts, and technological progress
Recent years show faster adoption, indicating stronger market penetration and policy support

Category 2: Energy Source Composition
The renewable energy mix is diverse, with varying contributions from different sources:
Biomass energy leads with 141,866.49 TBTU
Wood energy is the second-largest source at 112,315.11 TBTU
Conventional hydroelectric power contributes 42,333 TBTU
Emerging sources such as solar and wind have smaller but steadily increasing shares
Additional sources like waste energy and geothermal contribute to overall diversification

Category 3: Sectoral Consumption Patterns
Energy consumption varies significantly across sectors:
Industrial: 50.82% (largest share)
Residential: 25.04%
Commercial: 13.07%
Transportation: 2.61% (smallest share)
This distribution indicates that renewable energy is primarily used in industrial processes and residential applications.

Category 4: Source-Sector Relationships
The relationship between energy sources and sectors reveals:
Biomass energy is widely used across sectors, especially in industrial applications
Wood energy is strongly associated with residential consumption
Solar and wind are gaining traction in commercial and residential sectors
The dominance of industrial usage suggests opportunities to further expand renewable adoption in manufacturing and processing

-----

##Recommendations
Based on the findings, the following strategic actions are recommended:
- Industrial Sector Focus: Strengthen initiatives to expand renewable energy use in industrial operations
- Residential Growth Opportunities: Promote adoption through incentives and awareness, particularly for solar energy
- Transportation Sector Development: Invest in infrastructure and policies to increase renewable usage in transportation
- Biomass Optimization: Continue supporting biomass while ensuring sustainable sourcing practices
- Emerging Source Acceleration: Provide funding and incentives to scale solar, wind, and other emerging technologies
- Seasonal Planning: Optimize production and consumption strategies based on seasonal demand patterns

-----

Assumptions
- The dataset accurately reflects renewable energy consumption across all sources
- Sector classifications remain consistent throughout the analysis period
- Consumption values are measured using standardized methodologies
- All major renewable energy sources in the U.S. are included

-----

Dashboard Capabilities
- Interactive sector selection
- Detailed breakdowns by energy source and sector
- Historical trend analysis with consumption metrics
  

This analysis provides a comprehensive foundation for understanding renewable energy consumption trends and identifying opportunities for continued growth in sustainable energy adoption.
