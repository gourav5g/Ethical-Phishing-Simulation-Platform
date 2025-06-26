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

This is the link of sample

![](https://miro.medium.com/v2/resize:fit:1000/1*eWcC-kJRmOXnzk0ilngkHg.png)

**3.Check email headers for discrepancies (using online header analyzer).**

For email header analysis use same tool [**https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23**](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx?huid=9331f3c8-e3c9-4723-b961-c9abbfe5fe23)

![](https://miro.medium.com/v2/resize:fit:700/1*VBaV4s4h59tyiVjsGtDKrw.png)

you can see this is blacklisted

![](https://miro.medium.com/v2/resize:fit:700/1*4j20KB4I6773IzM5LiIFkA.png)

**4.Identify suspicious links or attachments.**

for identify suspicious link first copy the link and go to the virus total and paste it

suspicious link is ; **http://ecs-49-0-248-79.compute.hwclouds-dns.com/**

![](https://miro.medium.com/v2/resize:fit:700/1*BppDykopYmFlgaWFcIVflQ.png)

you can easily identified suspicious link

![](https://miro.medium.com/v2/resize:fit:700/1*D8FxZ0NmodY1USqyepSqYA.png)

**5.Look for urgent or threatening language in the email body.**

if you read this email you can see this in below;

You are expected to call DHL office +1(318)901–5153 immediately you receive this message because Bank of America (BOA) has finally released your compensation fund of $6,400,000.00 million USD and it has been programmed into an ATM visa debit card.

Right now your ATM card parcel is in DHL office waiting for your address of where to deliver it.

**6.Note any mismatched URLs (hover to see real link).**

There are no clickable URLs in the email, but if there were, it’s important to hover over any links to check if the displayed text matches the actual URL. In phishing emails, attackers often use mismatched URLs to trick users into clicking malicious sites that look legitimate. Always verify the real destination before clicking.

**7.Verify presence of spelling or grammar errors.**

In this mail too much error in spelling and gramatically

The message contains several errors, including incorrect number formats (e.g., “$6,400,000.00 million” is wrong), awkward greetings (“Greetings Dear,” should be “Dear [Name],”), missing articles (“in DHL office” should be “in the DHL office”), and run-on sentences without proper punctuation. Also, phrases like “Best Regard” should be plural (“Best Regards”), and closings like “Yours In Service” are not standard and should be replaced with “Sincerely” or “Yours sincerely.” Proper formatting for lists and clear sentence structure will make the message more professional and easier to read.

**8.Summarize phishing traits found in the email.**

Phishing Traits in the Email:

. Unexpected large money offer: Claims of $6.4 million compensation out of nowhere.

. Urgency and pressure: Asking to call immediately.

. Suspicious contact details: Uses a generic Gmail address instead of an official company email.

. Poor grammar and formatting: Shows unprofessional language and mistakes.

. Request for personal information: Asks for name, address, and phone number.

. Unverified sender: Email headers show inconsistent and suspicious sources.

. Too good to be true: Offers huge money with little explanation.

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






