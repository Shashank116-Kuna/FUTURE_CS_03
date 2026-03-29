# FUTURE_CS_03  
📘 API Security Risk Analysis – JSONPlaceholder
📌 Overview

This project presents a read-only API Security Risk Analysis conducted on the public demo API JSONPlaceholder.

The objective of this assessment was to identify common API security risks, evaluate their potential business impact, and provide practical remediation recommendations.

This project simulates a real-world security assessment engagement, following a structured and professional approach.

🎯 Objectives
Analyze publicly accessible API endpoints
Identify potential security vulnerabilities
Assess risk severity (Low / Medium / High)
Explain business impact in simple terms
Provide clear and actionable remediation steps
🌐 Target API
Name: JSONPlaceholder
Base URL: https://jsonplaceholder.typicode.com
🧪 Tools Used
Postman – API testing and request analysis
Browser (Chrome DevTools) – Inspecting API responses
Google Docs / Microsoft Word – Report creation
GitHub – Project documentation and version control
🔍 Scope & Methodology
Scope
Read-only testing only (non-intrusive)
No exploitation or service disruption
Public endpoints only
Methodology

The assessment was performed using:

Manual API testing
Endpoint enumeration
Response data analysis
Security misconfiguration identification

The focus was on identifying design and configuration weaknesses, not exploiting them.

⚠️ Key Findings

The following security risks were identified:

Missing Authentication (High)
All endpoints are publicly accessible without any access control
Public Data Exposure (Medium)
User data (emails, addresses) is openly accessible
No Rate Limiting (Medium)
Unlimited requests can be sent to the API
Predictable Resource Identifiers (Low)
Sequential IDs allow easy data enumeration
Missing Security Headers (Low)
Responses lack standard security protections
📊 Risk Summary
ID	Risk Title	Severity
R1	Missing Authentication	High
R2	Public Data Exposure	Medium
R3	No Rate Limiting	Medium
R4	Predictable Resource IDs	Low
R5	Missing Security Headers	Low
📁 Repository Structure
api-security-analysis/
│
├── report/
│   └── API_Security_Risk_Analysis.pdf
│
├── screenshots/
│   ├── users-endpoint.png
│   ├── posts-endpoint.png
│   ├── user-id-enumeration.png
│
├── README.md
📸 Evidence (Screenshots)

Screenshots of API responses and testing have been included in the /screenshots directory to support the findings in the report.

📄 Deliverables
✅ API Security Risk Analysis Report (PDF)
✅ Supporting screenshots
✅ GitHub documentation
🔐 Disclaimer

This project was conducted for educational purposes only.

The tested API is a public demo service and does not represent a production system.
No exploitation, data manipulation, or service disruption was performed.

🚀 Learning Outcomes

Through this project, the following skills were developed:

API security assessment fundamentals
Risk identification and classification
Writing professional security reports
Translating technical risks into business impact
📬 Contact : @yourshashankkuna@gmail.com

If you’d like to discuss this project or collaborate, feel free to connect. 
