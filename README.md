# Splunk SOC Investigation Labs

## 📊 Log Analysis | Threat Hunting | Incident Investigation | Splunk Enterprise
This repository demonstrates practical Security Operations Center (SOC) investigations using Splunk Enterprise. The projects focus on collecting, searching, analyzing, and investigating security logs to simulate common Tier 1 SOC analyst responsibilities.

Rather than simply learning Splunk commands, these labs emphasize how security analysts use log data to identify suspicious activity, investigate security events, document findings, and support incident response within enterprise environments.

---

# 🏢 Business Problem
organizations generate thousand of security events every day across servers, endpoints, firewalls, and network devices.
Without centralized log collection and strucred analysis, security teams may overlook indicators of companies, delaying dedection and increasing the impact of security incidents.

Splunk enables Security Operations Centers (SOCs) to centralize log data, investigate suspicious activity, support threat hunting, and improve incident response.

This repository demonstrates practical investigations using Splunk to analyze authentication events, DNS activity, HTTP traffic, and network connection logs

---

## 🎯 Project Objectives
The objective of this repository is to simulate common Tier 1 SOC analyst investigations using Splunk Enterprise. The projects demonstrate how to:
* 🚀 **Deploy and configure** Splunk Enterprise
* 📥 **Ingest** security log data
* 🔍 **Search and analyze** events using SPL
* 🌐 **Investigate** suspicious network activity
* 🔑 **Analyze** authentication logs
* 🖥️ **Investigate** DNS activity
* ✉️ **Examine** HTTP traffic
* 📜 **Review** Zeek connection logs
* 📝 **Document** investigation findings
* 🛡️ **Support** security monitoring and incident response

---
## 🛡️ SOC Responsibilities Demonstrated

#### 👁️ Security Monitoring
* 🗄️ **Centralized log collection**
* 📊 **Security event monitoring**
* 🔎 **Log searching** using SPL

#### 🚨 Alert Investigation
Performed investigations involving:
* 🔐 **Authentication activity**
* 📡 **DNS requests**
* 🌐 **HTTP requests**
* 💻 **Network connections**

#### 🕵️‍♂️ Threat Hunting
Developed SPL queries to identify:
* 📈 **High-volume** DNS requests
* 🛑 **Suspicious** client IP addresses
* ⚠️ **Authentication anomalies**
* 🕸️ **Web traffic** patterns
* 🔌 **Network connection** activity

### 📄 Incident Documentation
Each investigation includes:
* 📋 **Investigation Objective**
* 💻 **SPL Query**
* 📊 **Investigation Results**
* 🧐 **Analyst Observation**

---

### 📁 Repository Structure

| Project | Focus |
| :--- | :--- |
| 💿 **Project 1** | Install & Configure Splunk Enterprise |
| 🌐 **Project 2** | DNS Log Investigation |
| 🔑 **Project 3** | SSH Authentication Investigation |
| 📨 **Project 4** | HTTP Traffic Investigation |
| 📜 **Project 5** | Zeek Connection Log Investigation |

---

### 🛠️ Technologies Used

| Category | Technologies |
| :--- | :--- |
| 🪵 **SIEM** | Splunk Enterprise |
| 🐧 **Operating System** | Ubuntu Linux |
| 💻 **Query Language** | SPL (Search Processing Language) |
| 📝 **Network Logs** | Zeek |
| 🔐 **Authentication Logs** | SSH |
| 🗺️ **Network Analysis** | DNS, HTTP |

---

### 🎯 Skills Demonstrated

* 👁️ **Security Monitoring** — Continuous visibility and log oversight.
* 📊 **Log Analysis** — Parsing and interpreting event details.
* 🕵️‍♂️ **Threat Hunting** — Proactively searching for indicators of compromise.
* 🚨 **Incident Investigation** — Root cause analysis of security alerts.
* 🔎 **SPL Query Development** — Crafting efficient search strings.
* 🛡️ **Authentication Analysis** — Auditing access patterns and failures.
* 🌐 **DNS Investigation** — Identifying anomalous domain resolutions.
* ✉️ **HTTP Investigation** — Reviewing web request and response headers.
* 🎛️ **Network Traffic Analysis** — Evaluating packet flows and connections.
* 📄 **Security Documentation** — Writing clear, structured analyst notes.

---

### 🚀 Future Improvements

* 📈 **Splunk Dashboards** — Build visual metrics for real-time monitoring.
* ⚡ **Detection Rules** — Convert baseline searches into scheduled alerts.
* 🔀 **Alert Correlation** — Link multiple event types to map entire attack paths.
* 🗃️ **Threat Intelligence Integration** — Feed IOC blacklists directly into SPL lookups.
* 🥷 **MITRE ATT&CK Mapping** — Align all investigation results with known adversary tactics.
* 🏢 **Enterprise Security Use Cases** — Scale lab scenarios up to enterprise-level data models.






