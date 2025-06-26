# Ethical-Phishing-Simulation-Platform
An open-source platform designed for cybersecurity awareness training through realistic, ethical phishing simulations. This tool helps organizations educate employees, test resilience to social engineering attacks, and improve overall security posture — without compromising user privacy or trust.

1.This is the link of sample

phishing_pot/email/sample-1009.eml at main · rf-peixoto/phishing_pot
A collection of phishing samples for researchers and detection developers. - phishing_pot/email/sample-1009.eml at main…
github.com

# 🛡️ Phishing Email Analysis: Sample-1009.eml

A detailed analysis of a real phishing email sample from [phishing_pot GitHub repository](https://github.com/rf-peixoto/phishing_pot/blob/main/email/sample-1009.eml).

---

## 📥 1. Email Header Analysis

**Tool used:** [MXToolbox Header Analyzer](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx)

To analyze the email header:
- Open the email in Gmail.
- Click on the three dots (`⋮`) → **"Show Original"**.
- Copy the full header and paste it into the MXToolbox tool.

### 🔍 Key Findings:
- **Blacklisted IP Address**: The sending server appears on known blacklists.
- **Authentication Failures**: SPF/DKIM/DMARC checks failed.
- **Received Paths**: Indicate email was relayed through suspicious or spoofed sources.

![Header Analysis](https://miro.medium.com/v2/resize:fit:700/1*VBaV4s4h59tyiVjsGtDKrw.png)

---

## 🔗 2. Suspicious Link Detection

### 🔗 Detected URL:
```http
http://ecs-49-0-248-79.compute.hwclouds-dns.com/


fdgd

