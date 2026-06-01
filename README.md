  # Graylog SIEM Lab
  
  This project demonstrates the implementation of a SIEM solution using Graylog for centralized log collection, analysis, and alerting.
  
  ---
  
  ## Technologies Used
  - Graylog
  - Ubuntu Server
  - Winlogbeat / Filebeat
  - Syslog
  
  ---
  
  ## Architecture
  - Single-node Graylog deployment on Ubuntu
  - Log collection from:
    - Windows systems (Winlogbeat)
    - Linux systems (Syslog)
    - Network devices and firewall
  - Centralized processing and analysis
  
  ---
  
  ## Features
  - Centralized log collection
  - Log parsing and normalization (pipelines)
  - Event correlation
  - Security dashboards
  - Alerting system
  
  ---
  
  ## Use Cases
  
  ### Failed Login Detection
  Detection of multiple failed authentication attempts.
  
  ### Account Lockout Monitoring
  Monitoring locked user accounts (Event ID 4740).
  
  ### Server Restart Detection
  Detection of system restarts (Event ID 1074).
  
  ---
  
  ## Alerts
  
  - Multiple failed logins detection
  - Account lockout alert
  - Server restart alert
  
  ---

## Project Context
This project was developed as part of a cybersecurity internship, focusing on SIEM implementation and log analysis.
