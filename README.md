# 🛡️ Phishing Email Detection & Awareness System

**Author:** Mahamat ADAM ADAM  

**Program:** Future Interns – Cybersecurity Internship  

**Task:** Task 2 – Phishing Email Detection & Awareness  

**Year:** 2026

---

# 📌 Project Overview

Phishing remains one of the most common cyber threats affecting individuals and organizations today. Attackers use deceptive emails to trick users into revealing sensitive information such as passwords, personal data, or financial details.

The goal of this project is to analyze real email samples and identify common phishing indicators in order to classify the risk level of each message.

This project focuses on both **technical email analysis** and **user awareness**, helping users understand how phishing attacks work and how to avoid them.

---

# 🎯 Project Objectives

The main objectives of this project are to:

* Analyze real phishing email samples
* Identify common phishing indicators
* Classify email risks (Safe / Suspicious / Phishing)
* Explain phishing techniques in simple terms
* Provide clear prevention guidelines for users

---

# 🛠️ Tools Used

### Email Analysis

* **Google Admin Toolbox – Message Header Analyzer**

* **MXToolbox Email Header Analyzer**
* **VirusTotal**

### Investigation Methods

* Email header analysis
* Sender domain verification
* Link inspection
* Visual phishing indicator analysis

---

# 📊 Email Classification Results

After analyzing the email samples, the following classifications were made:

| Email Source          | Indicator                   | Technical Result    | Risk Level | Classification |
| --------------------- | --------------------------- | ------------------- | ---------- | -------------- |
| Leroy Merlin          | Suspicious sender domain    | SPF FAIL            | High       | 🔴 Phishing    |
| Microsoft             | Fake security alert         | DMARC Error         | High       | 🔴 Phishing    |
| Amil Health Plan      | Misleading marketing domain | SPF PASS            | Medium     | 🟡 Suspicious  |
| Official Notification | Verified sender             | SPF/DKIM/DMARC PASS | Low        | 🟢 Safe        |

---

# 🔍 Key Phishing Indicators Identified

During the analysis, several common phishing techniques were observed:

### Identity Spoofing

Attackers impersonate trusted brands by displaying fake sender names.

### Suspicious Domains

Fraudulent domains are used to imitate legitimate services.

### Social Engineering

Emails create urgency, fear, or curiosity to manipulate users.

### Misleading Links

Links often redirect users to malicious websites or data collection pages.

---

# 📷 Evidence

Screenshots from the **Google Admin Toolbox header analysis** are included in the **Evidence folder**.

These screenshots demonstrate the authentication results and technical indicators used to classify the emails.

---

# 🛡️ Phishing Prevention Guidelines

To reduce phishing risks, users should follow these security practices:

### ✅ Best Practices

* Always verify the sender's email address
* Hover over links before clicking them
* Be cautious with urgent messages
* Verify suspicious emails through official channels

### ❌ What to Avoid

* Do not share passwords through email
* Do not open unexpected attachments
* Do not click suspicious links

---

# 📄 Full Report

The complete phishing analysis report is available here:

📄 **[Download the Full Report](Report.pdf)**

The report contains:

* Detailed email investigations
* Header analysis explanations
* Phishing indicator breakdown
* Security awareness recommendations

---

# 🔐 Key Takeaway

Phishing attacks rely heavily on **human manipulation rather than technical vulnerabilities**.

By improving user awareness and understanding common phishing techniques, organizations can significantly reduce the risk of successful attacks.

---

# 📚 Learning Outcome

Through this project, I developed practical skills in:

* Phishing detection
* Email header analysis
* Security awareness communication
* Risk classification
* Cybersecurity documentation

---

✅ **Status:** Completed  

📌 **Project Type:** Cybersecurity Awareness & Email Threat Analysis

---
