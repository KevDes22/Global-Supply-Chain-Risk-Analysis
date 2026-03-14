
# Global Supply Chain Risk Analysis

This project provides a comprehensive analysis of global supply chain risks, utilizing the `global_supply_chain_risk_2026.csv` dataset. The primary objective is to identify key factors influencing supply chain disruptions and lead times, offering insights into optimizing supply chain resilience.

## Key Findings:

1.  **Data Overview & Preparation**:
    *   The dataset comprised 5000 records of shipment data, with no missing values or duplicates identified.
    *   Information was available on 8 unique origin ports and 9 unique destination ports.
    *   Date data was successfully parsed, and 'Month' and 'Month_Number' columns were extracted for temporal analysis.

2.  **Descriptive Statistics**:
    *   Average shipment distance: **7704.06 km** (median: 7750.13 km).
    *   Average shipment weight: **246.25 MT** (median: 243.50 MT).

3.  **Transport Mode Analysis**:
    *   **Air transport** was the most frequent mode with **1320 shipments**, followed by Sea (1281), Road (1214), and Rail (1185).
    *   **990 shipments** out of 5000 experienced a **Hurricane** weather condition.
    *   When considering *only disrupted shipments*, the distribution across transport modes was relatively even:
        *   Air: **26.61%**
        *   Sea: **25.53%**
        *   Road: **24.19%**
        *   Rail: **23.67%**

4.  **Risk and Reliability Assessment**:
    *   **Carrier Reliability Scores** (mean) were consistently around **0.75-0.76** across all weather conditions, with 'Clear' weather showing the highest average (0.761) and 'Hurricane' the lowest (0.749).
    *   **Top 5 Routes with Highest Geopolitical Risk Score**:
        1.  Shanghai to Busan: **5.75**
        2.  Dubai to Busan: **5.70**
        3.  Singapore to Los Angeles: **5.67**
        4.  Hamburg to Shanghai: **5.50**
        5.  Singapore to Hamburg: **5.49**

5.  **Predictive Analytics & Anomaly Detection**:
    *   A linear regression model was developed to predict `Lead_Time_Days` based on `Distance_km`, `Weight_MT`, and `Weather_Condition`. The model achieved an **Average Error (MAE) of 13.80 days**.
    *   **140 anomalous shipments** were detected based on a Z-score greater than 3, indicating significantly longer lead times than expected for their respective routes. For example, a shipment on the Los Angeles -> Marseille route had a lead time of **220.25 days** with a Z-score of **7.26**, far exceeding its route's average lead time of 13.57 days.

## Collaborative Research Team

This project is a joint effort conducted by the following researchers:

-   Kevin Destiny | [connect via LinkedIn](https://www.linkedin.com/in/destiny-kevin-0015861a4/)
-   Candance Chijoke-Mba | [connect via LinkedIn](https://www.linkedin.com/in/candace-chijioke-mba/)
