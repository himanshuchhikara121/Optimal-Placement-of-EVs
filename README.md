 Optimal Placement of Solar-Powered Electric Vehicle Charging Stations

 📘 Overview

This project presents a data-driven optimization model to identify the most effective locations and sizes for installing solar-powered electric vehicle charging stations (SPEVCS) in a power distribution network. With growing demand for sustainable mobility, this work helps ensure minimal power loss and enhanced voltage profiles using data modeling and simulation techniques.


 🎯 Objectives

- Analyze energy demand distribution across a 33-bus radial power network  
- Reduce active power losses by optimizing charging station placement  
- Identify high-sensitivity nodes through perturbation-based data modeling  
- Recommend DG sizing based on real-time load response simulations  
- Promote green infrastructure through solar energy integration


 📈 Key Data-Driven Techniques

 ✅ Sensitivity Analysis: Incremental load injection at each bus (0.1 MW) to assess system response  
 ✅ Optimization Modeling: Formulated using loss minimization and voltage stability metrics  
 ✅ Simulation Tools: MATLAB used for executing custom load flow and loss computation scripts  
 ✅ Case Comparison: Evaluated multiple configurations – with and without DG, with increased load  
 ✅ Data Interpretation: Tabular and graphical results for over 30 test cases across buses  
 ✅ Visualization: Plots for voltage trends, loss patterns, and DG impact across the network


 🛠 Tools & Technologies

 MATLAB – Core platform for numerical modeling and sensitivity computations  
 MS Excel / Python  – For tabular data analysis, charting and visualization  
 IEEE 33-Bus Test Network – Realistic distribution network structure  


 🔍 Results

| Scenario           | Active Loss (MW) | Minimum Voltage (pu) |
|--------------------|------------------|-----------------------|
| No Load, No DG     | 0.21100          | 0.90377               |
| +Load, No DG       | 0.22028          | ~0.902                |
| No Load, +DG       | 0.11117          | 0.94095               |
| +Load, +DG         | 0.11438          | 0.94227               |

 📍 Bus 6 and Bus 7 identified as optimal locations for charging stations  
 🔋 Optimum DG sizes: 2.59 MW (Bus 6), 2.47 MW (Bus 7)  
 📉 Losses reduced by ~49% in optimized configurations  


 📌 Applications & Relevance

This project is highly relevant for roles involving:

- Infrastructure data modeling  
- Sustainable energy planning  
- Load forecasting and optimization  
- Sensitivity-based decision-making  
- Data storytelling using technical simulations


 🌱 Future Enhancements

- Real-time dynamic load modeling  
- Multi-objective optimization (cost, carbon impact, reliability)  
- Dashboard integration for visualizing energy network performance  
- Incorporating real-world solar irradiance data and traffic patterns  



