# TryHackMe-Alert-Reporting-SOC-L1

# TryHackMe Lab: SOC L1 Alert Reporting, Escalation and Communication

## Objective: Documentation & Escalation of Alert 

## Tools used: 
* TryHackMe 
* Browser
* TryHackMe SIEM (Security Information Event Management) dashboard.

---

## Phishing attack
### Alert Report
This email failed the checks & was brought to attention by the SIEM through the investigation. There are a number of reasons why its a phishing email. There is Attached "REPORT.rar"
The clear domain spoofing "Sender: Microsoft Support<support@microsoft.com>"
Clear phishing tactic and social engineering "600% price increase; urgent notice; download the report; read the details;"
The target of the phishing email was Recipient: Eddie Huffman, IT Manager<e.huffman@tryhackme.thm> the IT manager 
The lastly it had failed Security Checks: SPF/Fail; DKIM/Fail;
<img width="715" height="476" alt="image" src="https://github.com/user-attachments/assets/9ec287e6-439e-4c98-9e18-0c5cb701886f" />

I had correctly reassigned the alert to L2 E. Fleming <img width="766" height="537" alt="image" src="https://github.com/user-attachments/assets/13a1ad39-673e-4b08-92ae-8f2b11417a67" />



---

## What Was Learnt:
* Accurate Alert Reporting (time, date, Five W’s Who, What, When, Where & Why)
* Importance of Accurate Alert Reporting. The efficacy of an L2 analyst is directly proportional to the quality of the L1 report. Clear documentation reduces Mean Time to Respond (MTTR).
* Escalation Who, when and what to Escalate. If there’s a major security threat like DDOS id need to report to L2, manager & Digital Forensics & incident Response Teams.
* Communication with my SOC Team members like SOC L2 or others if, I do not understand an alert. I may need to notify & escalate to higher management & law enforcement like ICO (Information Commissioners Office) etc. 
* If I need to Escalate an alert, I will need to write an formal written escalation report & other times I may need to simply reassign an alert to L2.
* Investigate thoroughly to find the True Positives and those alerts that need to be escalated.

---

## Conclusion:
Accurate reporting of alerts(threat), with proper escalation are crucial for coordination of SOC Teams & Proactiveness of cyber defence. 

Accurate Reporting of alerts(threats) helps to garner an preservative informational foundation, which further helps create better context if, the alert itself needs to be escalated to L2 SOC.
Knowing the Five W’s: Who, What, When, Where and Why, helps give context & informative, investigative and accurately detailed report of the alert not just for the SOC L2 yet too give ones like myself (L1) chance to gain more knowledge of threats and Alerts and proper remediation. 
Proper Escalation further leads to remediation/mitigation, of the alert and if need be, a deeper analysis from Incident Response and Forensics Team(s), if said Threat is a DDOS or anything critical etc. 
Which further leads to Communication, SOC analysts need to continually engage with persons in and out side of the SOC Department. Having clear & detailed written reports and verbal communication amplifies, harmonisation between SOC Team and other departments.

Alert Reporting Lab, has been quite substantial, I will revisit and engage in again. The five W’s have been very enlightening with investigation and detailing reports and finding the True Positives. Then the correct path to follow, what should be included with the Report and Escalating the alert. Also to  never be afraid to ask for support, logically speaking, when I’m new to  this field I will need to learn more and this is a great way. This will further compound on Communication. The efficacy of an L2 analyst is directly proportional to the quality of the L1 alert report and overall cyber Security Proactive stance to cyber security defence.
