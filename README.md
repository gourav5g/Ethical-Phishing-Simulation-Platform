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

Tool used: VirusTotal

Submitted the URL and identified it as malicious.

Domain mimics legitimate cloud infrastructure to avoid detection.

🧠 3. Phishing Red Flags
📌 Phishing Traits Found:
💰 Unexpected large money offer: Claims of $6.4M USD as "compensation".

⏰ Urgency & pressure: "Call immediately" message to trick victims into acting fast.

✉️ Suspicious email address: Uses free email service (Gmail) instead of official domain.

🔒 Requests sensitive information: Name, address, and phone number.

❌ Poor grammar & spelling: Numerous errors and awkward sentence structures.

🔗 Suspicious links: Redirect to untrusted domain names.

❓ Unverified sender: Email headers suggest forged or spoofed addresses.

✉️ 4. Sample Email Body (Excerpt)
Greetings Dear,

You are expected to call DHL office +1(318)901–5153 immediately you receive this message because Bank of America (BOA) has finally released your compensation fund of $6,400,000.00 million USD and it has been programmed into an ATM visa debit card.

Right now your ATM card parcel is in DHL office waiting for your address of where to deliver it.

❗ Issues:
"$6,400,000.00 million" is a nonsensical amount.

"in DHL office" should be "in the DHL office".

Closing salutation like “Yours In Service” is non-standard.

🔐 5. Email Authenticity Issues
🔍 Mismatched Headers
From field claims to be from an official source.

Headers show it was sent from a suspicious server/IP.

❌ Authentication Failures
SPF: Fail

DKIM: Fail

DMARC: Fail

✅ Summary of Key Phishing Indicators
Indicator	Details
💸 Unexpected reward	Promises $6.4M compensation
🕒 Urgency	"Call immediately" tactic
📧 Suspicious sender	Free Gmail used
🌐 Malicious link	Fake cloud domain
✍️ Grammar errors	Numerous throughout email
🔒 Data request	Wants personal info
🔎 Header mismatch	Email source spoofed

📎 Reference
📁 Original Sample: sample-1009.eml

🔍 Header Analysis: MXToolbox Result

📚 Educational Purpose
This project is part of a Cybersecurity Awareness & Threat Detection series.
It demonstrates real-world phishing tactics and how to analyze, detect, and prevent such threats.

⚠️ This is for research and educational purposes only. Do not engage with the email contents.


---






