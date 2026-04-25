<img width="956" height="482" alt="project1_1" src="https://github.com/user-attachments/assets/dec61bf7-8b99-47a6-9dd1-0d60e41aa684" />
<img width="960" height="422" alt="project1_2" src="https://github.com/user-attachments/assets/1ca58b6c-161e-40be-bc35-31300dc3a582" />
<img width="946" height="416" alt="project1_3" src="https://github.com/user-attachments/assets/4b8cdd74-f168-42ab-801e-207205a7270e" />
<img width="960" height="418" alt="project1_4" src="https://github.com/user-attachments/assets/3c2107ba-2dce-43ac-8fce-fe0a29e69925" />
<img width="958" height="417" alt="project1_5" src="https://github.com/user-attachments/assets/89fe8c2f-70c8-45e5-b609-26847a8a9cbe" />
<img width="960" height="421" alt="project1_6" src="https://github.com/user-attachments/assets/cfcf3aeb-4c7b-462f-94f9-72be67c90949" />
<img width="960" height="415" alt="project1_7" src="https://github.com/user-attachments/assets/d8fdb1fa-dc4b-4002-8c6f-2fcbcf51ab83" />
<img width="958" height="407" alt="project1_8" src="https://github.com/user-attachments/assets/0f9920f4-39a5-43a1-bd1e-e7f5450e3fda" />
<img width="959" height="416" alt="project1_9" src="https://github.com/user-attachments/assets/8ab1adf7-993b-45be-8343-92fd0b5040d4" />
<img width="543" height="345" alt="project1_10" src="https://github.com/user-attachments/assets/fdefc401-a1ef-4810-894d-95ca917845a1" />
<img width="959" height="290" alt="project1_11" src="https://github.com/user-attachments/assets/7897f2f2-8887-41db-ab61-d09a72f114b5" />
# 🚀 Splunk SIEM Lab: Brute-Force Detection

## 📋 Project Description
In this lab, I established a local SOC (Security Operations Center) environment using **Splunk Enterprise**. I simulated a real-world attack scenario by ingesting authentication logs and identifying malicious activity using Search Processing Language (SPL).

---

## 🛠️ Implementation Phases

### 1. Data Onboarding
I uploaded raw system logs and configured the indexing properties to ensure fields like `user`, `IP`, and `status` were correctly parsed.

![Ingestion]

### 2. Threat Hunting with SPL
I performed a deep-dive analysis to find authentication failures. I discovered a pattern of 6 failed login attempts for the user "ali" from IP `192.168.1.15`.

![Analysis]

### 3. Automated Alerting
To ensure 24/7 monitoring, I created a **Scheduled Alert** that triggers when multiple failed logins occur within a short window.

![Alerting]

---

## 🔑 Key Learning Outcomes
* Mastered the **data lifecycle**: Ingestion -> Indexing -> Searching -> Alerting.
* Gained proficiency in **SPL** for security investigation.
* Developed an understanding of **Brute-Force attack patterns** in system logs.

* Mastered the **data lifecycle**: Ingestion -> Indexing -> Searching -> Alerti* Gained proficiency in **SPL** for security investigation.
* Developed an understanding of **Brute-Force attack patterns** in system logs.
