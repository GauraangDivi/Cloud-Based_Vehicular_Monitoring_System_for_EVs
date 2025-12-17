This work presents a real-time vehicular monitoring system for digital twin prototype 
developed for the TATA Nexon EV (40.5 kWh, 312 km range equivalent). The 
prototype is implemented as an interactive Streamlit application that emulates the 
behaviour of the electric powertrain, battery pack, braking system, charging system, 
and vehicle dynamics under different operating conditions. The digital twin models 
the Battery Management System (BMS) using a combined Coulomb counting and 
Kalman filter–based State of Charge (SOC) estimator, along with an empirical State 
of Health (SOH) estimator and an advanced thermal management block capable of 
detecting overheating and thermal runaway. The powertrain and vehicle dynamics 
blocks simulate motor torque, shaft power, battery power, and longitudinal motion, 
while the braking system includes regenerative braking, mechanical braking, ABS 
logic, and brake temperature estimation. A charging subsystem supports multiple 
charging protocols and enforces operational safety constraints such as preventing 
charging initiation while the vehicle is in motion or under acceleration. The 
application provides real-time key performance indicators (KPIs), multi-tab 
visualizations (battery, powertrain, braking, charging), and an extended analytics 
dashboard including cumulative energy, regen energy, SOC–speed heatmap, and 
temperature statistics. The prototype is designed to be OEM-ready, enabling 
calibration with real datasets and CSV export for further analysis. 
