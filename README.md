# Wazuh SIEM Deployment Lab

## Project Overview

This project demonstrates the complete setup and deployment of Wazuh SIEM for security monitoring. 
The lab includes Wazuh Manager installation, endpoint agent deployment, File Integrity Monitoring (FIM) configuration, and security alert generation.



# Objectives

- Install and configure Wazuh SIEM
- Deploy Wazuh agent on endpoint machine
- Configure File Integrity Monitoring
- Generate and analyze security alerts
- Understand basic SOC L1 monitoring workflow



# Environment

## Wazuh Manager

Operating System:
- Ubuntu Server

Components:
- Wazuh Manager
- Wazuh Dashboard
- Wazuh Indexer

## Endpoint Agent

Operating System:
- Windows

Agent Purpose:
- Collect security events
- Monitor file changes
- Send alerts to Wazuh Manager



# Wazuh Installation

## Installation Process

Steps performed:

1. Installed Wazuh Manager
2. Configured Wazuh Dashboard
3. Verified Wazuh services
4. Accessed Wazuh web interface



# Agent Deployment

## Windows Agent Installation

Steps:

1. Downloaded Wazuh Agent
2. Installed agent on endpoint
3. Registered agent with Wazuh Manager
4. Started Wazuh agent service

Agent Status:

- Connected successfully
- Logs received by Wazuh Manager


# File Integrity Monitoring (FIM)

File Integrity Monitoring helps detect unauthorized changes in important files.

Configuration:

- Added monitored directories
- Enabled file change detection
- Tested file modification events



# Alert Generation Testing

Testing performed:

1. Created a monitored file
2. Modified file content
3. Deleted file
4. Checked generated alerts in Wazuh Dashboard

Result:

Wazuh successfully detected file changes and generated security alerts.



# Screenshots

(Add screenshots here)

Example:




# Conclusion

This project helped understand the basic workflow of Wazuh SIEM, endpoint monitoring, File Integrity Monitoring, and security alert investigation from a SOC L1 analyst perspective.


# Skills Learned

- SIEM Deployment
- Wazuh Administration
- Agent Management
- File Integrity Monitoring
- Alert Investigation
- Blue Team Monitoring
