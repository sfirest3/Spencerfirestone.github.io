---
layout: default
---

# Project 1 : SIEM Deployment & Security Monitoring with Microsoft Sentinel

Organizations of the contemporary fast-paced world of cybersecurity need powerful tools to monitor and respond to security notifications efficiently. This is part of my cybersecurity learning process. I installed a cloud SIEM (Security Information and Event Management) tool with Microsoft Sentinel. This project enhanced my learning on log analysis, threat intelligence, and automated response pipelines within cloud environments.


# Technical Details

The project was implemented on Microsoft Azure, using Microsoft Sentinel as the SIEM tool. The key technical features were:

Azure Virtual Machine Configuration: Configured a Windows Server VM to generate security events for analysis.

Log Ingestion & Analysis: Integrated Sentinel with Azure Monitor Agent (AMA) to ingest and analyze security logs.

Custom Analytics Rules: Developed Kusto Query Language (KQL) scripts to detect security anomalies, i.e., brute-force attacks and unauthorized remote desktop connections.

Automated Response: Created playbooks using Azure Logic Apps to automate the response, including sending alerts and isolating compromised accounts.

Dashboard Visualization: Built interactive dashboards for real-time threat detection and security insights. 
---
layout: default
---

![Branching](Screenshot%202025-04-01%20191149.png)

---
layout: default
---

Some of the challenges I faced were Log Data Overload: Sorting through critical security events from large data sets meant that KQL queries had to be optimized.

Rule Fine-Tuning: Tuning analytics rules to eliminate false positives without suppressing legitimate threats.

Automating Response Operations: Not hindering normal functioning but promptly resolving actual security issues.

---
layout: default
---

![Octocat](Screenshot%202025-04-01%20192149.png)

---
layout: default
---

# Custom analytics Rule that checks for successfull log ins.
Coded Custom analytics rules to detect and alert on potential security threats through the RDP. 
Automated incident response mechanisms, reducing reaction time for suspected breaches.
Gained hands-on knowledge on Azure security utilities, log inspection, and SIEM functionalities.

---
layout: default
---

![ocotoat](Screenshot%202025-04-01%20191106.png)

---
layout: default
---
Having utilized Microsoft Sentinel as a SIEM solution was an excellent means of getting first-hand experience with security monitoring and automation. Working on this project not only solidified my technical skills but also broadened my understanding of real-world cybersecurity practices. As the type of cyber threats becomes increasingly complex, the importance of effective, scalable, and automated security monitoring is crucial to any company.



# Project 2 : Cocktail Finder Web App

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```


### There's a horizontal rule below this.

* * *



### Small image



### Large image








