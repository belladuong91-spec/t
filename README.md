# Log Scanner

## Keywords and Rationale
The script searches for the following keywords:
- **error**
- **failed login**
- **unauthorized**

These keywords were selected because they often indicate potential security issues or system anomalies. Errors can signal failed services, while failed logins and unauthorized access attempts may indicate intrusion attempts or brute-force attacks.

## Use Case for a Security Analyst
A Security Operations Center (SOC) analyst could use this script to quickly scan authentication or system logs for suspicious activity. By automating the detection of key terms, analysts can focus on investigating genuine incidents rather than manually searching through large volumes of logs.

## Potential Improvements
To make this a more advanced tool:
- Add **regular expressions** to match more complex patterns (e.g., IP addresses or usernames).
- Include **timestamp filtering** to search within specific time ranges.
- Integrate with **SIEM tools** or send alerts when matches are found.
- Provide **JSON/CSV output** for easier data analysis and visualization.

---

**Author:** [Your Name]  
**Date:** October 2025
