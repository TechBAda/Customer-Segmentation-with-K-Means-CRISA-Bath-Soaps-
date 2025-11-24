# Customer Segmentation with K-Means (CRISA Bath Soaps)

##  Project Overview
This project applies K-Means clustering to segment customers for **CRISA Bath Soaps** using both behavioral and motivational data. The segmentation aims to uncover patterns in loyalty, switching, price sensitivity, promotional responsiveness, and purchase motivations. The results guide strategic decisions across pricing, promotions, advertising, and loyalty programs.

##  Purpose of Analysis
The goal of this analysis is to use unsupervised learning to identify meaningful and actionable customer segments for CRISA.  
By analyzing **purchase behavior** (how customers buy) and **basis-for-purchase features** (why they buy), this project creates a dual-layer segmentation framework.

Using silhouette scores and business interpretability, the analysis identifies the optimal segmentation structure, enabling CRISA to improve revenue growth, targeting, and customer retention.  
The project demonstrates how data science supports real marketing and business strategy decisions.  
Based on Assignment 5 PDF :contentReference[oaicite:2]{index=2}.

---

## Datasets Used
- **BathSoap.xlsx** — contains purchase behavior and basis-for-purchase sheets.  
- **segmented_customers.csv** — output dataset containing assigned clusters.

---

##  Key Techniques Used
- Min–max scaling & feature standardization  
- K-Means clustering across multiple variable sets  
- Silhouette score evaluation (k = 2–5)  
- Cluster profiling & interpretation  
- Behavioral segmentation (how customers buy)  
- Attitudinal segmentation (why customers buy)  
- Hybrid segmentation linking both layers  
- Marketing & strategic recommendations  

---

## Segmentation Approaches Compared
### Purchase Behavior Segmentation  
Based on:
- Brand loyalty  
- Switching  
- Volume  
- Spend  
- Frequency  
- Price tier  
- Loyalty concentration  

### Basis-for-Purchase Segmentation  
Based on:
- Promotional sensitivity  
- Price tier preferences  
- Selling proposition affinities  

### Combined Segmentation  
A full model using all 25 variables.

---

## Final Selected Model: **Purchase Behavior (k = 3)**
Chosen because:
- Best balance of silhouette score & interpretability  
- Maps directly to business levers such as loyalty, frequency, spend  
- Easily operationalized for marketing and pricing  

---

## Repository Structure
project/
│
├── notebooks/
│ └── BathSoap_KMeans_Segmentation.ipynb
│
├── data/
│ └── BathSoap.xlsx
│
└── README.md

---

## Author  
**Adanma Okoroafor**  
MS Artificial Intelligence & Business Analytics (FinTech)  
University of South Florida  




