# GPON-Network-Traffic-Visualisation

<img width="604" alt="Screen Shot 2024-01-10 at 10 30 30" src="https://github.com/SMARTRONALD/GPON-Network-Traffic-Visualisation/assets/123365195/c02d69aa-df66-4328-958b-fcce6800ddf7">

# Overview

Welcome to the GPON Network traffic Project! This repository houses the code and documentation for an end-to-end automation system that revolutionizes the management of Gigabit Passive Optical Network (GPON) traffic across multiple sites. It provides real-time insights, efficient data wrangling, and dynamic visualization.
This GPON GPON Network traffic Project paves the way for enhanced network monitoring and analysis, ensuring optimal performance. 

# Key Features

- **Automated Data Collection:** Python scripts fetch GPON traffic data from the 5529 Statistics and Data Collector, ensuring accuracy and timeliness.
- **Efficient Data Wrangling:** Robust functions process PON and ONT data, optimizing storage and transforming raw data into a structured format.
- **Dynamic Database Management:** PostgreSQL is used for storing and managing processed GPON data, supporting real-time analysis.
- **Intuitive Visualization:** Grafana dashboards offer network administrators real-time performance snapshots.

# Technologies Used

- Python
- PostgreSQL
- Grafana

# Getting Started

# Prerequisites

- Python
- PostgreSQL
- Grafana

# Installation
Clone the Repository:

# Setup PostgreSQL Database:

Ensure you have a PostgreSQL database set up.
Update database connection parameters in the Python scripts (ont_db_connection_params and pon_db_connection_params).

# Install Dependencies:
As shared in the Requirements.txt file

# Run the Scripts:
Execute the main script to start the automated data processing pipeline:
bash
Copy code
python sdc.py

# Configure Grafana:

Configure Grafana to connect to your PostgreSQL database.
Create dashboards for ONT and PON visualizations.

# Scheduled Updates:

The system is set to run updates every 15 minutes. Adjust the interval in the schedule.every() statement in sdc.py as needed.
Contributing:
Contributions are welcome! If you have suggestions, enhancements, or bug fixes, feel free to open issues or create pull requests.



