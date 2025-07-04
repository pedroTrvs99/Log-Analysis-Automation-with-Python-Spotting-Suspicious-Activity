# Log-Analysis-Automation-with-Python-Spotting-Suspicious-Activity

<h2>Description</h2>

This project focuses on automating a fundamental cybersecurity task: log analysis. I developed a simple Python script to parse web server access logs, identify specific security events (like failed login attempts), and summarize key findings. This demonstrates how basic scripting can significantly improve efficiency in monitoring and detecting suspicious activities, which is a core responsibility of a Junior Security Analyst.

<h2>Objective</h2>

The primary objective of this activity was to develop a Python script that reads and processes web server access logs to identify and count security-relevant events, such as failed login attempts. The script extracts actionable insights from raw log data, demonstrating foundational Python skills for cybersecurity automation and emphasising the role of log analysis in proactive threat detection.

<h2>Tools & Technologies Used</h2>

* **Operating System: Ubuntu Server (or other Linux distribution on your Virtual Machine)**
* **Programming Language: Python 3**
* **Text Editor: Nano**
* **Sample Data: A simulated web server access log file.**

<h2>Program walk-through:</h2>

<p align="center">
Step 1: Creating a Sample Log File <br/>
   
<img src="https://github.com/user-attachments/assets/ae7d3334-882c-46ae-9f6e-2d3e20f33f11" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 2: Interpret the Permissions String <br/>
   
<img src="https://github.com/user-attachments/assets/6f2acc9f-c6c4-475b-af0c-f78e40ed655b" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 3: Identify and Change File Permissions <br/>
   
<img src="https://github.com/user-attachments/assets/573e429b-6763-48c9-82af-224ba6972756" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 4: Modify Hidden File Permissions <br/>
   
<img src="https://github.com/user-attachments/assets/2357ae3f-17cb-4ad2-80c8-0b3bf96e35e7" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 5: Change Directory Permissions <br/>
   
<img src="https://github.com/user-attachments/assets/1ca2f5d6-2b24-4720-80b8-333240d07a20" width="653" alt="Step 1 Screenshot"/>
<br />
---

<h2>Security Concepts Applied:</h2>

* **Principle of Least Privilege: Granting only the minimum necessary permissions for users and processes to perform their tasks.**
* **Access Control: Implementing mechanisms to restrict who can access and modify files and directories.**
* **Data Confidentiality & Integrity: Protecting sensitive information from unauthorised viewing (confidentiality) and unauthorised changes (integrity).**
* **Defence in Depth: Adding layers of security, where file permissions serve as a critical layer at the operating system level.**

<h2>Key Learnings & Takeaways:</h2>

* **Gained practical proficiency in using ls -la and chmod for effective Linux file system security management.**
* **Deepened understanding of how file permissions directly impact system security and data protection.**
* **Reinforced the importance of regularly reviewing and correctly setting permissions to prevent unauthorised access and maintain system integrity.**
* **Developed a more methodical approach to identifying and remediating access control misconfigurations.**

