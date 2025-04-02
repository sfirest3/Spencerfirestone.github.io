---
layout: default
---

# Project #1 SIEM Deployment & Security Monitoring with Microsoft Sentinel

Organizations of the contemporary fast-paced world of cybersecurity need powerful tools to monitor and respond to security notifications efficiently. This is part of my cybersecurity learning process. I installed a cloud SIEM (Security Information and Event Management) tool with Microsoft Sentinel. This project enhanced my learning on log analysis, threat intelligence, and automated response pipelines within cloud environments.

# Technical Details

The project was implemented on Microsoft Azure, using Microsoft Sentinel as the SIEM tool. The key technical features were:

Azure Virtual Machine Configuration: Configured a Windows Server VM to generate security events for analysis.

Log Ingestion & Analysis: Integrated Sentinel with Azure Monitor Agent (AMA) to ingest and analyze security logs.

Custom Analytics Rules: Developed Kusto Query Language (KQL) scripts to detect security anomalies, i.e., brute-force attacks and unauthorized remote desktop connections.

Automated Response: Created playbooks using Azure Logic Apps to automate the response, including sending alerts and isolating compromised accounts.

Dashboard Visualization: Built interactive dashboards for real-time threat detection and security insights.

# Challenges Faced

Log Data Overload: Sorting through critical security events from large data sets meant that KQL queries had to be optimized.

Rule Fine-Tuning: Tuning analytics rules to eliminate false positives without suppressing legitimate threats.

Automating Response Operations: Not hindering normal functioning but promptly resolving actual security issues.

# Outcomes

On completion of the project:

Can properly monitor real-time security incidents using Sentinel.

Generated bespoke analytics rules to increase the efficacy of threat detection.
Automated incident response mechanisms, reducing reaction time for suspected breaches.
Gained hands-on knowledge on Azure security utilities, log inspection, and SIEM functionalities.

# Lessons Learned

The project reaffirmed the importance of:

Fine-tuning security policies to optimize detection effectiveness and accuracy.

Responsibly automating reaction, minimizing disruptions while maximizing security.

Ongoing monitoring and adjustment, since cyber threats are ever-changing.

# Conclusion

Having utilized Microsoft Sentinel as a SIEM solution was an excellent means of getting first-hand experience with security monitoring and automation. Working on this project not only solidified my technical skills but also broadened my understanding of real-world cybersecurity practices. As the type of cyber threats becomes increasingly complex, the importance of effective, scalable, and automated security monitoring is crucial to any company.





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

![ocotoat](Screenshot%202025-04-01%20191106.png)

### Large image

![Branching](Screenshot%202025-04-01%20191149.png)

![Octocat](Screenshot%202025-04-01%20192149.png)

![Octocat](Screenshot%202025-04-01%20194946.png)


