# dast

# POC on DAST
---
| Author          | Created on  | Version   | Last updated by  | Last edited on | Level | Reviewer |
|----------------|------------|-----------|-----------------|---------------|------------------|-------------|
| Pravesh Kumar | 08-03-2025 | V1  | Pravesh Kumar | 09-03-2025    |  |             |       
---
## Table of Contents
- [Pre-requisite](#pre-requisite)
- [DAST using OWASP ZAP](#dast-using-owasp-zap)
- [Report](#report)
- [Conclusion](#conclusion)
- [Contact](#contact)
- [Reference](#reference)
---
## Pre-requisite
- OWASP ZAP
- A Running Application to Perform DAST.
---
## DAST using OWASP ZAP
### Steps 1. Update your OS
```
sudo apt update
```
![image](https://github.com/user-attachments/assets/25efe10a-a28c-43e0-93df-15433df596da)
### Steps 2. Install OWSAP ZAP
```
sudo snap install zaproxy --classic
```
![image](https://github.com/user-attachments/assets/ee3f6be2-2f44-4a2f-93d1-80ba231962ed)
### Steps 3. Launch OWSAP ZAP
```
zaproxy
```
Ensure that your application or api should be running before using this service.

<img src="https://github.com/user-attachments/assets/2c80716f-71fb-4646-a2a4-cab51ad57837" alt="Terraform" width="1000" height="500">

### Steps 4. Enter the API URL into the 'Attack' input field for scanning

<img src="https://github.com/user-attachments/assets/fbc50ca7-e47a-423f-99df-549fe9012a62" alt="Terraform" width="1000" height="500">

### Steps 5. Wait for result

<img src="https://github.com/user-attachments/assets/7470809d-5663-40fc-a7ab-802acf51418b" alt="Terraform" width="1000" height="500">

### Steps 6. Result

<img src="https://github.com/user-attachments/assets/1ef676b3-3913-4a02-a7d5-fa436d83e6d3" alt="Terraform" width="1000" height="500">

---
## Report
| Link         | Description         |
|--------------|------------------------|
| [DAST](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Pravesh-SCRUM-101/Application%20CI%20Design/Frontend%20CI%20checks/DAST/Report/2025-03-09-ZAP-Report-Frontend.pdf)| Report |
---
## Conclusion

DAST tests apps during real-world attacks, helping find vulnerabilities early. Using tools like OWASP ZAP and Burp Suite ensures apps are secure before deployment, protecting both the app and the company's reputation

---


## References
| Link | Description |
|------|-------------|
| [DOC](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Pravesh-SCRUM-101/Application%20CI%20Design/Frontend%20CI%20checks/DAST/Documentation/README.md)| DAST documentation |
| [Report](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Pravesh-SCRUM-101/Application%20CI%20Design/Frontend%20CI%20checks/DAST/Report/2025-03-09-ZAP-Report-Frontend.pdf) | DAST Report |
