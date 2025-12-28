# Power BI Refresh Failure Monitoring System

# Project Overview
In enterprise Power BI environments, monitoring dataset refresh failures manually across multiple workspaces is inefficient and can lead to delayed incident resolution.  
This project demonstrates an **automated workflow solution** built using **Power Automate** to monitor Power BI dataset refresh status, send real-time alerts, and maintain audit logs.

---

# Business Problem
- Manual monitoring of Power BI dataset refreshes
- Delayed identification of refresh failures
- No centralized logging for audit and tracking
- Increased downtime of business reports

---

# Solution
An automated monitoring workflow was implemented using **Power Automate** to:

- Periodically check Power BI dataset refresh status
- Capture refresh failure details
- Send instant notifications to stakeholders
- Maintain a centralized audit log

---

# Workflow Automation Steps
1. **Trigger**: Scheduled Power Automate flow runs at defined intervals  
2. **Check**: Power BI dataset refresh status is retrieved  
3. **Condition**: If refresh status = *Failed*  
4. **Actions**:
   - Send alert via **Outlook Email**
   - Post notification in **Microsoft Teams**
   - Log failure details in **SharePoint**

---

# Technologies Used
- Power BI Service  
- Power Automate  
- SQL  
- SharePoint  
- Outlook  
- Microsoft Teams  

---

# Business Impact
-  Reduced manual monitoring effort by **70%**
-  Faster incident identification and resolution
-  Improved report availability
-  Strengthened Power BI governance and reliability

---

# Key Learnings
- Workflow automation improves BI operational efficiency
- Power Automate can be effectively used for monitoring and alerting
- Centralized logging helps in proactive issue management

---


