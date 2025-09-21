# EU Sustainability Performance Tier Classification
## Project Overview
This project was developed as part of the Kiron Thrive Program (AAI-9) and addresses the challenge of classifying European countries based on their sustainability performance. Using data from the 2025 Europe Sustainable Development Report, we applied machine learning techniques to group 49 countries into three performance tiers:

Tier 2 – Sustainability Leaders

Tier 1 – Good Performers

Tier 0 – Needs Improvement

The goal is to identify key policy indicators that influence sustainability outcomes and provide actionable recommendations for improvement.
## Objectives

Classify countries into sustainability tiers using supervised learning

Analyze feature importance across 15 selected SDG indicators

Visualize performance patterns and tier differences

Provide policy insights and advancement pathways for underperforming countries

Document the use case and business impact via the appliedAI platform

## Dataset

Source: Europe Sustainable Development Report 2025

Observations: ~490 (49 countries × 10 years)

Target variable: performance_tier (0, 1, 2)

Features: 15 indicators across Economy, Innovation, Governance, Education, Environment, and Social domains

Link to full dataset and report: eu-dashboards.sdgindex.org

## Methodology

Data Cleaning: Removed rows with missing values for simplicity and model stability

Modeling: Trained and evaluated two models — Logistic Regression and Random Forest

Performance: Achieved >75% accuracy with balanced classification across all tiers

Feature Analysis: Identified top 5 predictive indicators influencing tier assignment

Visualization: Created tier-based country tables and performance plots

## Key Insights

Top Predictive Features: R&D investment, governance quality, renewable energy share, digital infrastructure, and education access

Tier Profiles: Leaders typically show >3% R&D, >80 governance index, and >40% renewables

Advancement Roadmap: Focus on innovation, transparency, and inclusive education to move up tiers

Country Examples: Bulgaria, Romania, and Serbia show potential for targeted improvement

## Use Case Documentation

The project is published on the appliedAI Use Case Platform under the title: "EU Sustainability Performance Tier Classification"

Screenshots of the completed template are available in the /use_case_documentation/ folder.

## Policy Recommendations

A brief report with tier profiles and advancement strategies for EU decision-makers is available in the /policy_analysis/ folder.

## Author

Name: Nataliia Bilai

GitHub Repository: https://github.com/nbilai/Project_B_Bilai_Nataliia
