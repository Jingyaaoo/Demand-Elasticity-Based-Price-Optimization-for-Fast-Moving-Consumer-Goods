# Demand-Elasticity-Based-Price-Optimization-for-Fast-Moving-Consumer-Goods
Final year project for degree of Computer Science specialism in Data Analytics
## Overview
The FMCG industry faces the challenges of balancing revenue maximization with environmental sustainability due to products with short shelf lives, rapid consumption, and large-scale production. Demand forecasting and price optimization are key strategies for effective production planning and dynamic pricing. This project developed a **pricing decision support tool** for FMCG businesses, leveraging these strategies along with price elasticity of demand through advanced machine learning techniques. The following specifies machine learning techniques utilized for each application:  
- Demand Forecasting: **Supervised Learning** with XGBoost Regression algorithm  
- Price Elasticity Estimation: **Double Machine Learning** with XGBoost Regression and Linear Regression algorithms  
- Price Optimization: **Reinforcement Learning** with Twin Delayed Deep Deterministic Policy Gradient (TD3) algorithm  

## Novelty
This project proposes a **hybrid supervised reinforcement learning** technique to approach price optimization for FMCGs. Specifically, the XGBoost Regression demand forecasting model formed the supervised learning component, while the Twin Delayed Deep Deterministic Policy Gradient (TD3) algorithm constituted the reinforcement learning component. 
Additionally, this project uses continuous state and action space for price optimization, to more closely represent real-world scenarios

## Dataset
FMCG Weekly Sales Transaction Data   
- Link: https://www.dunnhumby.com/source-files/  (Breakfast at the Frat)
- Data period: January 14, 2009 to January 4, 2012 (156 weeks)  
- Coverage (After data cleaning): 77 Stores, 7 Product Categories, 37 Universal Product Codes

## Deployment
The project is deployed on a Streamlit web application
![image](https://github.com/user-attachments/assets/39b50cee-16e2-4ddb-867a-0fc240117a1f)
![image](https://github.com/user-attachments/assets/0e7fdddb-a839-4f20-9366-53ff19954aa7)
![image](https://github.com/user-attachments/assets/d217030d-570c-4d1a-be7a-d41f406abe3c)


## Summary & Future Enhancements
The proposed hybrid approach demonstrated promising results in recommending optimal prices within 20% above and below the base price to maximize revenue, with 70% of test cases show increased revenue. The project streamlines decision-making of pricing analysts and supports the long-term economic sustainability of FMCG businesses.   
Future works should consider:  
- Using dataset with greater variety of FMCG categories
- Including customer data and sales transaction data from periods of consumer bulk buying  
- Investigating impacts of product expiry dates on optimal pricing
