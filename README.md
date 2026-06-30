# TryHackMe Lab: SOC L1 Alert Reporting, Escalation and Communication

## Objective: Documentation & Escalation of Alert 

## Tools used: 
* TryHackMe 
* Browser
* TryHackMe SIEM (Security Information Event Management) dashboard.

---

## Phishing attack
### Alert Report
This email failed the checks & was brought to attention by the SIEM through the investigation. There are a number of reasons why its a phishing email.The clear domain spoofing "Sender: Microsoft Supportsupport@microsoft.com". A clear indicator and the fact Microsoft would not communicate this report and set of data in this way. There was the clear phishing tactic and social engineering, that of fear and urgency -> "600% price increase; urgent notice; download the report; read the details;".There is Attached "REPORT.rar" to "download the report; read the details". The intended Target of the phishing email was Recipient: Eddie Huffman, IT Managere.huffman@tryhackme.thm the IT manager. The lastly it had failed Security Checks: SPF/Fail; DKIM/Fail; Which ruled out any other possibility.
<img width="715" height="476" alt="image" src="https://github.com/user-attachments/assets/9ec287e6-439e-4c98-9e18-0c5cb701886f" />

I had correctly reassigned the alert to SOC L2 Analyst E. Fleming. Escalating the alert to L2 SOC remediates the alert. In this instance, I wrote down the Five W's and provided a detailed report to provide context for the L2 SOC Analyst.  <img width="766" height="537" alt="image" src="https://github.com/user-attachments/assets/13a1ad39-673e-4b08-92ae-8f2b11417a67" />

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
Accurate reporting of alerts (threats) with proper escalation is crucial for the coordination of SOC teams and the proactiveness of cyber defense.

Accurate reporting of alerts (threats) helps to garner a preserved informational foundation, which further helps create better context if the alert itself needs to be escalated to L2 SOC. Knowing the Five W’s (Who, What, When, Where, and Why) helps give context and an informative, investigative and accurately detailed report of the alert—not just for the SOC L2, but also to give ones like myself (L1) a chance to gain more knowledge of threats, alerts and proper remediation.

Proper escalation further leads to the remediation/mitigation of the alert, if need be, a deeper analysis from Incident Response and Forensics teams if said threat is a DDoS or anything critical. This further leads to communication; SOC analysts need to continually engage with persons inside and outside of the SOC department. Having clear and detailed written reports and verbal communication amplifies the harmonization between the SOC team. Giving more detailed further builds a strong contextual foundation of the Alert.

The Alert Reporting Lab has been quite substantial. I will revisit and engage in it again. The Five W’s have been very enlightening regarding investigation, detailing reports, aswell as finding the True Positives, too add knowing the correct path to follow and what should be included with the report when escalating an alert. Also, never be afraid to ask for support; logically speaking, when I’m new to this field, I will need to learn more, and this is a great way. This will further compound on communication.

Alert Reporting Lab, has been quite substantial, I will revisit and engage in again. The five W’s have been very enlightening with investigation and detailing reports and finding the True Positives. Then the correct path to follow, what should be included with the Report and Escalating the alert. Also to  never be afraid to ask for support, logically speaking, when I’m new to  this field I will need to learn more and this is a great way. This will further compound on Communication. The efficacy of an L2 analyst is directly proportional to the quality of the L1 alert report and overall cyber Security Proactive stance to cyber security defence.

