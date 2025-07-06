# 📌 Project: Exception-Driven Invoice Dispatch Automation - Saved 15+ Hours/Week 
### Outlook, VBA, SSRS and Business Analysis-Driven Case Study

This project showcases how business analysis principles and VBA scripting were applied to automate a self-bill invoice processing and supplier dispatch workflow, 
saving 15+ hours per week in a high-volume finance operation.

---

## 📁 Context

In a high-volume finance environment, self-billed invoices distribution was performed manually every week for 550+ suppliers.
Each email contained Excel and PDF files linked to voucher IDs requiring validation before dispatching to suppliers.
The process involved manual email triage, SSRS report matching, exception handling, and supplier dispatch via Outlook—resulting in 15+ hours/week of BA overhead.

---

## 🎯 Problem Statement

- Manual download and triage of 500+ invoice emails weekly  
- SSRS-based voucher list needed for checklist creation
- No rules for exception flagging (accepted vs. rejected)
- Exception handling done manually against supplier logic  
- High risk of errors and delayed payments  
- Resource drain preventing strategic BA initiatives

---

## ⚠️ Constraints

- No API or integration between Outlook, SSRS, and Excel
- No third-party tools allowed (governance limits)
- Exception logic was undefined and manual  
- Manual voucher validation across exception lists  
- Tight timelines for dispatch to avoid payment delays  
- BA-led design required without tech team dependency

---

## 🔍 Approach

- Defined workflow: Inbox Invoice Downlaod ➜ Validate ➜ Dispatch  
- Conducted requirement gathering and BRD creation for end-to-end process  
- Mapped existing manual workflows using BPMN methodology  
- Defined rules for subject lines, voucher formats, and exception logic  
- Built VBA macro to extract attachments, validate data, and automate dispatch  
- Integrated SSRS reports for voucher reconciliation  
- Facilitated 8-week iterative UAT and stakeholder feedback loops  
- Created email template standards for supplier communication consistency
- Documented SOPs and post-deployment support

---

## 💡 Solution Overview

- Automated download of invoice attachments from Outlook mailbox
- Folder structure auto-generated to store invoices
- Voucher numbers validated against SSRS list
- Cross-checked invoices with exception list to mark accepted/rejected
- Applied rule-based validation using subject line patterns and voucher criteria   
- Automated dispatch of accepted invoices to 550+ suppliers using Outlook macros  
- Archived sent invoices and tracked weekly completion status  
- Documented SOPs and trained users for smooth rollout

---

## 📈 Business Impact

| Area                        | Result                                             |
|-----------------------------|----------------------------------------------------|
| ⏱ Manual Time Saved        | 15+ hours/week (equivalent to 0.4–0.5 FTE)         |
| 📤 Dispatch Cycle Duration | Reduced from 5–7 days/week → 1 days/week          |
| 📈 Accuracy & Compliance   | Reduced manual errors in supplier communication     |
| 🧠 Strategic Capacity Freed | BA time reallocated to backlog clearance and trend analysis |
| 💡 Process Efficiency      | Standardized invoice flow and reusable logic framework |
| 🧠 BA Bandwidth            | Enabled time for backlog resolution      |
| 📊 Data Trends             | Enabled supplier trend and process analysis |
| 📋 Documentation           | Improved handovers via SOPs              |

---

## 🧠 Lessons Learned

- BA-led automation delivers strong ROI in low-code setups
- Defined rules at the email and voucher level reduce ambiguity
- Standardized subject line rules improved automation accuracy dramatically  
- BPMN flow mapping clarified cross-department handoffs and logic gaps  
- Iterative UAT ensures stability before scaling and early stakeholder feedback was essential to aligning automation with reality  
- VBA + BA logic unlocked major time savings in non-engineered environments  
- Structure = scalability: simple rules can fuel future RPA or API integrations

---

## 🛠 Tools & Methodologies Used

### Automation Tools
- VBA Macros (Excel & Outlook Integration)  
- SSRS (SQL Server Reporting Services) Data Extraction  
- Excel for Rule-Based Exception Logic

### BA Artifacts
- BRD & Process Documentation  
- BPMN Workflow Modeling  
- UAT Test Case Design & Execution  
- Supplier Communication Templates  
- Stakeholder Alignment & Feedback Loops  
- Exception Handling Algorithm  

---

> ⭐ **Built for efficiency, owned by Business Analysts.**
