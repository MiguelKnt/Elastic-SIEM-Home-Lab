# Elastic SIEM Home Lab Project

## Overview
This project demonstrates the setup and configuration of a Security Information and Event Management (SIEM) system using Elastic in a home lab environment. The project involves configuring Elastic to monitor system logs, creating custom rules to detect specific activities, and setting up alerts to respond to potential security events.

## Project Details
In this project, I configured Elastic to run on my Windows machine using the Windows terminal. I built out a SIEM to collect and analyze log data, providing visibility into network activities.

### Key Features
- Setting up a home lab environment for SIEM.
- Sending system logs to the cloud for centralized monitoring.
- Querying and filtering logs to detect specific activities.
- Creating custom rules and alerts for real-time monitoring.

### Testing and Results
After running an Nmap scan on the system, I received an alert from the SIEM based on the configured rule. This demonstrated the effectiveness of the custom alert and how SIEMs can be used to monitor and respond to specific security events in real time.

### Key Outcomes
- **Successful Data Collection:** Elastic SIEM began collecting logs from my system, providing insights into thousands of network events.
- **Effective Querying:** I used custom queries to search for and filter specific data points from the logs.
- **Real-Time Alerts:** I demonstrated the SIEM’s ability to send real-time alerts based on predefined rules, successfully receiving an email notification when Nmap activity was detected.

### What I Learned
Through this project, I gained practical experience in:
- Setting up and configuring a SIEM in a home lab environment.
- Working with Elastic and its powerful capabilities for log collection and monitoring.
- Writing custom queries to filter and detect critical events in system logs.
- Creating real-time alerts based on security events, reinforcing the importance of proactive network monitoring.
- Understanding how a SIEM can be leveraged to enhance network security by responding to potential threats in real time.

### Conclusion
This project illustrates how a SIEM can be implemented in a home lab to enhance security monitoring. By leveraging custom queries and alerts, the SIEM provides real-time visibility and response to potential threats, showcasing its value in protecting network environments.
