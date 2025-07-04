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
Step 1: Creating a Sample Log File. For this project, I created a simple, simulated web server access log file named access.log. In a real-world scenario, this would be a log file collected from an actual web server. <br/>
   
<img src="https://github.com/user-attachments/assets/096f4f66-aa8f-4db2-8ec0-b89315b0d67f" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 2: Paste the following sample log entries into the nano editor. These include a few simulated failed login attempts <br/>
   
<img src="https://github.com/user-attachments/assets/d8d92c18-fbbf-4657-912a-8d4ceb6c8696" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 3: Developing the Python Automation Script. Wrote a Python script, analyze_logs.py, to read the access.log file, search for "Failed login" messages, and count how many times each IP address attempted a failed login. <br/>
   
<img src="https://github.com/user-attachments/assets/8825b447-82ec-4d85-8267-147909df04b6" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 4: Python code into the nano editor <br/>
   
<img src="https://github.com/user-attachments/assets/3909937e-6ec5-487a-84ac-69d0455c7113" width="653" alt="Step 1 Screenshot"/>
<br />

<p align="center">
Step 5: Executing the Python Script. Ran the Python script from the terminal to process the access.log file. <br/>
   
<img src="https://github.com/user-attachments/assets/194b4785-430e-4b67-94a4-ec9c77c09f81" width="653" alt="Step 1 Screenshot"/>
<br />
---


<h2>Key Learnings & Takeaways:</h2>

* **Power of Automation: Understood how even a simple script can automate repetitive log review tasks, saving time and improving efficiency for security analysts.**
* **Foundational Python for Security: Gained practical experience with Python for file handling, string searching, and basic data aggregation – essential skills for more complex security scripts.**
* **Log Data Importance: Reinforced the critical role of log files as a primary source of truth for detecting security incidents and understanding system activity.**
* **Pattern Identification: Developed skills in identifying specific patterns or keywords within large volumes of log data to pinpoint security events.**
* **Problem-Solving through Code: Practised translating a real-world security problem (finding failed logins) into a logical and executable programming solution.**
* **Scalability: Realised that while this script is basic, the principles can be scaled up to process much larger datasets or integrate with more advanced tools (like SIEMs) for comprehensive analysis.

