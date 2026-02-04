# Impact of Ownership Concentration on Financial Performance of Manufacturing Firms in Europe
A Quantitative Panel‑Data Research Project (1980–2021)

# Table of Contents
- [Project Overview](#project-overview)
- [Research Aim](#research-aim)
- [Research Objectives](#research-objectives)
- [Research Questions](#research-questions)
- [Methodology Summary](#methodology-summary)
- [Model Specification](#model-specification)
- [Figures](#figures)
- [Tables](#tables)
- [Literature Review Summary](#literature-review-summary)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [Repository Structure](#repository-structure)
- [Author](#author)

# Project Overview
This project investigates how block ownership, institutional ownership, and government ownership concentration influence the financial performance of manufacturing firms across selected European countries (UK, France, Switzerland, Belgium, Germany, and the Netherlands).

The study uses panel data (1980–2021) and applies fixed effects and random effects regression models to examine the relationship between ownership structures and firm performance (measured using ROA and ROE).

# Research Aim
To evaluate the impact of different ownership concentration structures on the financial performance of manufacturing firms in European countries.

# Research Objectives
- Assess the effect of block ownership concentration on firm performance.
- Examine how institutional ownership concentration influences financial outcomes.
- Determine the impact of government ownership concentration on firm performance.

# Research Questions
1. What impact does block ownership concentration have on financial performance?
2. How does institutional ownership concentration affect financial performance?
3. What is the effect of government ownership concentration on financial performance?

# Methodology Summary
- Data Type: Quantitative secondary data  
- Period: 1980–2021  
- Countries: UK, France, Switzerland, Belgium, Germany, Netherlands  
- Performance Metrics: ROA, ROE  
- Independent Variables:
  - BOC — Block Ownership Concentration
  - IOC — Institutional Ownership Concentration
  - GOC — Government Ownership Concentration
  - LEV — Leverage (Debt/Equity)
- Models Used:
  - Fixed Effects
  - Random Effects
- Tools Used:
  - Excel (data cleaning, descriptive statistics, regression analysis)

# Model Specification
ROA = f(BOC, IOC, GOC, LEV)

ROE = f(BOC, IOC, GOC, LEV)

# Figures
Upload your images into a `/figures` folder and ensure filenames match the placeholders.

### Figure 1: Structure of the Research
<img width="1582" height="753" alt="image" src="https://github.com/user-attachments/assets/8cdfa0a3-44fd-43e2-808f-420128e4d5f8" />


### Figure 2: Average ROE and ROA for the Selected Manufacturing Firms
<img width="941" height="491" alt="image" src="https://github.com/user-attachments/assets/4b1e60e6-42c8-4910-a821-d44358ea2bf7" />

### Figure 3: Average Value of BOC, IOC and GOC
<img width="975" height="485" alt="image" src="https://github.com/user-attachments/assets/2eb48360-64e9-4687-ad71-22847b7785f4" />


# Tables
Upload your table images into a `/tables` folder.

### Table 1: Descriptive Statistics
	ROE	ROA	BOC	GOC	IOC	GEARING
 Mean	16.45	5.84	3.64	16.50	9.18	129.80
 Median	12.45	4.67	0.32	0.00	10.68	94.03
 Maximum	107.09	35.53	51.35	98.99	19.98	752.25
 Minimum	-93.70	-11.73	0.00	0.00	0.00	1.78
 Std. Dev.	23.06	6.39	8.61	27.01	6.58	120.01
 Skewness	0.64	1.55	3.50	1.46	-0.26	2.75
 Kurtosis	9.90	8.04	15.87	3.75	1.61	12.47
 Jarque-Bera	321.84	228.86	1404.19	59.15	14.44	784.37
 Probability	0.00	0.00	0.00	0.00	0.00	0.00
 Sum	2582.71	916.24	571.45	2590.95	1440.54	20378.85
 Sum Sq. Dev.	82926.42	6363.98	11575.51	113796.50	6748.17	2246916.00
 Observations	157	157	157	157	157	157


### Table 2: Correlation Analysis
	ROE	ROA	BOC	GOC	IOC	GEARING
ROA	0.89	1.00				
BOC	-0.14	-0.15	1.00			
GOC	-0.27	-0.23	0.02	1.00		
IOC	-0.45	-0.37	0.17	0.44	1.00	
GEARING	-0.34	-0.37	-0.04	0.16	0.07	1.00


### Table 3: Regression Results (ROA)
VARIABLES	ALL COUNTRIES	UK	BELGIUM	GERMANY	NETHERLAND	SWITZERLAND
BOC	-0.10
[0.13]
-0.71	-450.99**
[179.38]
-2.51	-0.09
[0.08]
-1.10	0.78
[1.03]
0.76	-0.03
[0.10]
-0.30	-1.50
[11.36]
-0.13
IOC	-0.68**
[0.29]
-2.37	
-	0.69*
[0.38]
1.84	-1.13
[1.29]
0.88	-0.07
[0.29]
-0.26	-1.23
[0.76]
-1.62
GOC	-0.05
[0.06]
-0.90	
-	-0.13**
[0.05]
-2.77	-0.09
[0.18]
-0.49	0.02
[0.05]
0.37	
-
GEARING	-0.05***
[0.02]
-3.09	-0.20**
[0.07]
2.69	-0.15**
[0.06]
-2.47	-0.06
[0.05]
-1.31	-0.49***
[0.11]
-4.58	-0.44***
[0.14]
-3.13
C	-28.97***
[4.75]
6.10	58.09***
[13.37]
4.34	21.67**
[7.86]
2.76	37.35*
[21.40]
1.74	33.08***
[6.52]
5.08	70.23***
[13.21]
5.32
Hausman Test
Prob>chi2 =	6.30
0.17	3.51
0.17	3.46
0.48	1.27
0.87	4.37
0.36	35.94
0


### Table 4: Regression Results (ROE)
VARIABLES	ALL COUNTRIES	UK	BELGIUM	GERMANY	NETHERLAND	SWITZERLAND
BOC	-0.06
[0.04]
-1.30	-118.75
[97.58]
-1.22	-0.04
[0.04]
-0.94	0.09
[0.21]
0.43	-0.03
[0.06]
-0.49	-5.89*
[3.11]
-1.89
IOC	-0.18**
[0.09]
-2.07	
-	0.35
[0.23]
1.54	-0.24
[0.27]
-0.87	-0.05
[0.16]
-0.34	-0.02
[0.21]
-0.10
GOC	-0.01
[0.02]
-0.55	
-	-0.07**
[0.02]
-2.90	-0.01
[0.04]
-0.01	0.01
[0.03]
0.31	
-
GEARING	-0.02***
[0.01]
-3.43	-0.1**
[0.04]
-2.36	-0.03
[0.03]
-0.79	-0.01
[0.01]
-1.43	-0.27***
[0.06]
-4.61	-0.14***
[0.04]
-3.52
C	9.58***
[1.27]
7.56	23.30***
[7.27]
3.21	4.47
[4.61]
0.97	9.68**
[4.49]
2.16	18.23***
[3.59]
5.08	20.01***
[3.62]
5.53
Hausman Test
Prob>chi2 =	5.68
0.22	3.46
0.18	15.54
0.003	2.00
0.73	5.36
0.25	15.20
0


# Literature Review Summary
The literature reveals mixed empirical findings:
- Some studies report positive effects of ownership concentration on performance.
- Others find negative or insignificant relationships.
- Results vary by region, industry, methodology, and shareholder type.

This project fills a gap by analysing three ownership categories simultaneously within the European manufacturing sector.

# Key Findings
(Replace these placeholders with your actual regression results)
- Block Ownership Concentration: …
- Institutional Ownership Concentration: …
- Government Ownership Concentration: …
- Overall Model Fit: …

# Conclusion
The study provides evidence on how different ownership structures influence firm performance in Europe. The findings can guide:
- Policymakers
- Investors
- Corporate governance practitioners
- Manufacturing sector stakeholders

# Recommendations
- Encourage optimal ownership structures that enhance monitoring and reduce agency conflicts.
- Strengthen corporate governance frameworks across European manufacturing firms.
- Conduct further research using additional performance metrics (e.g., Tobin’s Q).

# Repository Structure
figures/             # All charts and visualisations  
tables/              # All tables (images or markdown)  
data/                # Raw and cleaned datasets  
scripts/             # Analysis scripts (Python/R/Stata)  
outputs/             # Regression tables, figures, charts  
README.md            # Project documentation  
report.pdf           # Full dissertation (optional)

# Author
Sulaimon Sikiru Oladele  
Data Analyst | Python • SQL • Power BI • Tableau | Excel  
United Kingdom
