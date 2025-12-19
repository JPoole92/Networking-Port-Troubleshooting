# Networking & Port Troubleshooting (Azure VM)

**Subject:** Networking / Core Help Desk / Cloud Fundamentals

---

## 📌 Project Overview

This project demonstrates **entry-level networking and port troubleshooting skills** performed on a Windows Server virtual machine hosted in an Azure sandbox environment. The lab focuses on validating network connectivity, testing common service ports, and using standard command-line tools to diagnose connectivity issues.

These tasks reflect real-world troubleshooting scenarios commonly handled by **Help Desk, Desktop Support, and Cloud Support** professionals.

---

## 🧠 Key Skills Demonstrated

* Basic TCP/IP networking concepts
* Network connectivity validation
* DNS resolution troubleshooting
* Port and service connectivity testing
* Firewall awareness and validation
* Structured troubleshooting methodology

---

## 🛠️ Environments & Technologies Used

* Microsoft Azure (Sandbox Environment)
* Windows Server 2019 / 2022
* Command Prompt & PowerShell
* Azure Virtual Networking

---

## 💻 Operating Systems Used

* Windows Server (Azure Virtual Machine)

---

## ✅ Tasks Performed

* Deployed a Windows Server virtual machine in Azure
* Verified IP configuration and network connectivity
* Tested local TCP/IP stack functionality
* Confirmed outbound internet access
* Validated DNS name resolution
* Inspected active connections and listening ports
* Tested common service ports (HTTP/HTTPS)
* Identified blocked or filtered ports
* Reviewed firewall status and impact on connectivity

---

## 🔄 Networking & Port Troubleshooting Workflow

1. Verify the system has a valid IP configuration
2. Test the local TCP/IP stack
3. Confirm outbound network connectivity
4. Validate DNS resolution
5. Inspect active network connections and ports
6. Test connectivity to common service ports
7. Identify potential firewall or filtering issues

This workflow mirrors standard troubleshooting approaches used in enterprise IT environments.

---

## 📸 Screenshots & Explanations

### Azure Virtual Machine Overview
<img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/469163bb-8eb3-4c83-a5d0-29b4cb6b931f" />
<img width="975" height="480" alt="image" src="https://github.com/user-attachments/assets/4c1d2cf6-8a29-4f05-8f04-73bda173da7e" />
Shows the deployed Windows Server virtual machine running in the Azure environment.

### IP Configuration Verification (`ipconfig`)
<img width="975" height="512" alt="image" src="https://github.com/user-attachments/assets/8ed3874d-547d-483b-aba5-d07d5034fed5" />
*Confirms the system has a valid IPv4 address, subnet mask, and default gateway.*

### Local Network Stack Test (`ping 127.0.0.1`)
<img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/a20bb66c-97cb-4178-b8e1-dbbd7d81b494" />
*Validates that the network adapter and TCP/IP stack are functioning correctly.*

### Internet Connectivity Test (`ping 8.8.8.8`)
<img width="975" height="509" alt="image" src="https://github.com/user-attachments/assets/4ef5ed0c-c3e5-498e-aa79-d12ae2365847" />
*Confirms outbound network connectivity from the virtual machine.*

### DNS Resolution Test (`nslookup`)
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/0de59c9d-afd6-47ca-aec8-e864f8cd39ec" />
*Demonstrates successful hostname-to-IP resolution using DNS.*

### Port & Connection Inspection (`netstat -an`)
<img width="975" height="726" alt="image" src="https://github.com/user-attachments/assets/9a1ba114-cc0f-4c5b-914e-8b6fd1f4bc17" />
*Displays active network connections and listening ports on the system.*

### Port Connectivity Tests (`Test-NetConnection`)
<img width="975" height="608" alt="image" src="https://github.com/user-attachments/assets/425828fa-5f51-470d-b1bd-143d1f24bef4" />
*Verifies access to common service ports such as HTTP (80) and HTTPS (443) and demonstrates detection of blocked ports.*

### Firewall Status Validation
<img width="975" height="659" alt="image" src="https://github.com/user-attachments/assets/2fc5a4d8-0ff7-4a9b-9c1e-7fce64b2f0c1" />
*Shows how firewall configuration can impact network connectivity and port access.*

---

## 🎯 Outcome

The system’s network connectivity and service port access were successfully validated using standard troubleshooting tools. Potential connectivity issues were identified and analyzed using a structured, repeatable approach.

---

## 📚 What This Project Demonstrates to Employers

* Practical networking troubleshooting experience
* Understanding of common service ports and protocols
* Ability to diagnose connectivity issues methodically
* Familiarity with cloud-hosted virtual machine networking
* Readiness for Help Desk, Desktop Support, or Cloud Support roles

---

## 🚀 Next Steps

Future projects will build on these skills by covering:

* Linux user and service administration
* Ticketing systems and escalation workflows
* Automation and scripting fundamentals

---

*This project was completed as part of a professional IT portfolio to demonstrate hands-on networking and troubleshooting skills.*
