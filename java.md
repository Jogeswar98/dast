## **Table of Contents**
[Introduction](#introduction)
[Pre-requisites](#pre-requisites)
[Step-by-Step Setup Guide](#step-by-step-setup-guide)
[Step 1: Update Your Linux System](#step-1-update-your-linux-system) 
[Step 2: Install OWASP ZAP](#step-2-install-owasp-zap) 
[Step 3: Launch OWASP ZAP](#step-3-launch-owasp-zap)
[Step 4: Perform an Automated Scan](#step-4-perform-an-automated-scan)
[Step 5: Analyze Results](#step-5-analyze-results) 
[Step 6: Report Generation](#step-6-report-generation)
[Step 7: Report](#step-7-report)
[Conclusion](#conclusion)
[Contact Information](#contact-information)
[References](#references) 
## Introduction
This Proof of Concept (POC) aims to demonstrate the effectiveness of DAST in identifying security vulnerabilities in Java applications.
Dynamic Application Security Testing (DAST) involves evaluating a live application for security vulnerabilities by emulating external threats. OWASP ZAP (Zed Attack Proxy) is a widely used open-source DAST tool designed to detect security flaws in web applications.
## Pre-requisites
[OWASP ZAP](https://www.zaproxy.org/)
**A Running Java Application** to perform DAST.
# Step-by-Step Setup Guide
### **Step 1**: **Update Your Linux System**
Before installing OWASP ZAP, update your system to ensure you have the latest packages and security patches. Open the terminal and run the following command:
``` bash
sudo apt update
```
### **Step 2: Install OWASP ZAP**
Once your system is up to date, you can install OWASP ZAP. To do so, type the following command in the terminal:
``` bash
sudo snap install zaproxy --classic
````
![Screenshot 2025-02-26 190125](https://github.com/user-attachments/assets/7df0b26f-d93c-4423-a851-c998c607c050) ### **Step 3: Launch OWASP ZAP**
Once the installation is complete, you can launch OWASP ZAP from the application menu or the command line. To launch it from the command line, type the following command:
  
``` bash
zaproxy
```
![WhatsApp Image 2025-02-26 at 18 08 40_d4159999](https://github.com/user-attachments/assets/a03f8ae4-682f-48d0-9e35-e5795c0141e6) ### **Ensure that your application or api should be running before using this service.**
![image](https://github.com/user-attachments/assets/2a787b5e-b147-4ffc-9d63-8195abc3a94e) ### Step 4: Perform an Automated Scan
Click on the Automated Scan option.
Provide the URL of the application in the respective field.
Click on Attack to start the scanning process.
OWASP ZAP will now begin scanning your application for vulnerabilities.
![WhatsApp Image 2025-02-26 at 18 15 27_6453a764](https://github.com/user-attachments/assets/db51b160-3e15-4e1e-86cc-6d61c3672536) ### **Step 5: Analyze Results**
Once the scan is complete, navigate to the Alerts tab.
The identified vulnerabilities will be listed.
Click on each alert to view details about the security issue.
![image](https://github.com/user-attachments/assets/e2ff9385-1d28-4de2-bb56-073ed98cb872) ### **Step 6: Report Generation**
Click on the Report option.
Select the desired format (HTML, PDF, JSON, etc.).
Click on Generate Report to save it to the desired directory.
![WhatsApp Image 2025-02-26 at 18 17 27_1c933a21](https://github.com/user-attachments/assets/8343d0e7-7ee8-4fae-91ff-6b3ec3a347b3) ### **Step 7: Report**
| **Link** | **Description** |
|---------|----------------|
| [Download Report](https://github.com/snaatak-Zero-Downtime-Crew/Documentation/blob/Nikita-SCRUM-73/Application%20CI%20Design/Java%20CI%20Checks/DAST/POC/DAST_Report.html) | Click here to download the generated security analysis report. |
## Conclusion
Dynamic Application Security Testing (DAST) is a crucial method for identifying security vulnerabilities in live applications by simulating real-world attacks. OWASP ZAP, as a leading open-source DAST tool, plays a vital role in uncovering and addressing security issues in web applications, thereby enhancing their resilience against potential threats. By integrating DAST tools like OWASP ZAP into the security testing process, organizations can proactively protect their applications and ensure a robust security posture.
## **Contact Information**
| **Name** | **Email address**            | **Github ID**
|----------|-------------------------------|-------------------|
| Nikita joshi    | Nikita.Joshi@mygurukulam.co | https://github.com/jnikita19 | --- ## References
| Links | Description |
|-------|-------------|
|https://techofide.com/blogs/how-to-install-owasp-zap-on-windows-and-linux/ | A step-by-step guide to installing OWASP ZAP on both Windows and Linux platforms. Useful for beginners starting with OWASP ZAP. |
| https://www.zaproxy.org/ | The official website for OWASP ZAP, providing documentation, downloads, and community support. Ideal for exploring all features of ZAP. |
