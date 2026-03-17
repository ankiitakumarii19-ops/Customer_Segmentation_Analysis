# Customer_Segmentation_Analysis


Project: 
Mall Customer Segmentation — Unsupervised Machine Learning & Behavioral Profiling

Overview:
This project applies Unsupervised Machine Learning to segment a dataset of mall customers into distinct behavioral archetypes. By leveraging K-Means Clustering, the analysis moves beyond basic demographics to identify high-value "Elite" spenders and "Frugal" casual shoppers, enabling data-driven retail strategies.

Executive Summary:
The goal is to solve the "Customer Intelligence Gap" by grouping customers based on their Annual Income and Spending Score. This allows for the creation of tailored marketing campaigns, optimized product placements, and enhanced customer retention strategies based on actual purchasing power rather than intuition.

Dataset Profile:
Target Audience: 200 unique mall customers.

Core Features: Gender, Age, Annual Income (k$), and Spending Score (1–100).

Income Range: $15k to $137k per annum.

Spending Range: 1 to 99 (Score assigned based on behavior and history).

Technical Workflow:
Exploratory Data Analysis (EDA): Visualizing age distributions, gender spending gaps, and income-to-spend correlations.

The "Elbow" Method: Utilizing Within-Cluster Sum of Squares (WCSS) to mathematically determine the optimal number of clusters (k=5).

K-Means Clustering: Segmenting the population into 5 distinct groups:

Target (High Income, High Spend): The "Elite" tier for premium marketing.

Spendthrifts (Low Income, High Spend): High-engagement but price-sensitive.

Sensible (High Income, Low Spend): High potential for luxury conversion.

Careful (Low Income, Low Spend): Budget-conscious shoppers.

Average (Medium Income, Medium Spend): The stable core.

Visualization: 2D and 3D scatter plots to demonstrate cluster separation.

Strategic Applications:

Hyper-Personalization: Targeted promo codes for "Spendthrifts" to maintain volume.

Premium Conversion: Special concierge services or exclusive previews for the "Sensible" high-income group.

Resource Allocation: Focusing loyalty programs on the "Target" cluster to maximize ROI.
