# Intrusion detections system

# Abstract
Distributed Denial of Service (DDoS) attack is a menace to network security that aims at exhausting the target networks with malicious traffic. The goal of this project was to use classification models to predict the benign or DNS in network in order to help improvetp prevent cyber attacks and maintenance stability. I worked with data provided by UNB university, leveraging  categorical feature engineering along with a random forest model to achieve promising results for this multiclass problem.
After refining a model, I built an interactive  visualiztion and communicate my results using seaborn library.

# Design
CICDDoS2019 contains benign and the most up-to-date common DDoS attacks, which resembles the true real-world data (PCAPs). It also includes the results of the network traffic analysis using CICFlowMeter-V3 with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack
What makes this dataset special it generate background attakcs and threats.

# Data
The dataset contains 5074413 combined of malcious and bengin with over 88 features for each, 20 of which are categorical. 12 DDoS attacks includes NTP, DNS, LDAP, MSSQL, NetBIOS, SNMP, SSDP, UDP, UDP-Lag, WebDDoS, SYN and TFTP on the training day and 7 attacks including PortScan, NetBIOS, LDAP, MSSQL, UDP, UDP-Lag and SYN in the testing day. The traffic volume for WebDDoS was so low and PortScan just has been executed in the testing day and will be unknown for evaluating the proposed modendertaken to inform baseline models and feature engineering.
