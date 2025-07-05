from pathlib import Path

# Define the markdown content based on the optimized case study provided
markdown_content = """
# 📌 Project: BA-Driven Email Workflow Optimization & Escalation Mapping

## 🧭 Context
Handled supplier communications across 80 → 550+ self-billed vendors in a high-volume finance operations environment (2019–Present). Urgent need arose to triage, respond, and route ambiguous email queries with zero API support.

## 🎯 Problem Statement

- Suppliers sent email queries from multiple teams, departments and addresses without standardized references.
- Existing supplier portal supported only 2 fixed email addresses per supplier and lacked searchability.
- Internal teams struggled to trace which query came from which supplier, leading to:
  - Investigation delays
  - Incorrect issue routing
  - Repeated back-and-forth communication
  - Lost visibility into query trends or root causes

## ⚠️ Constraints

- No built-in supplier portal support for query matching (email field constraints, no intelligent mapping)
- No centralized index of email→supplier relationships
- Query surge with no standardized format
- Ambiguous queries required 3–5 touchpoints to resolve
- Needed non-IT-intensive solution deployable by BAs

## 🔍 Approach

Applied Business Analysis techniques to:

- Define stakeholder pain points via observation and email tracking logs
- Identify root cause categories (stock, pricing, commission, VAT, remittance)
- Map interdependencies between teams (Merchandising, Product, Finance)
- Designed UI to bypass Excel’s native filters—enabled “type-to-search” UX for fast lookup
- Indexed all known supplier emails (from various departments)
- Allowed reverse lookup by name, domain, or partial email
- Enabled accurate supplier identification for incoming emails
- Set up query categories for future trend analysis
- Implemented email automation foundations (Outlook + RPA later)

## 💡 Solution Overview

- Enabled query resolution within minutes using flexible name/email search
- Mapped suppliers to their multiple associated email addresses
- Allowed query filtering using any part of an email ID or supplier name
- Routed categorized issues directly to the right internal team (Finance, Merch, Product, etc.)
- Eliminated investigation cycles by 60%+ through root-cause alignment
- Served as a query intelligence repository (to spot patterns)
- Fed categorized issue types back into invoice quality improvement backlog
- Later integrated with: Outlook-based automation and RPA bots to send weekly invoices

## 📈 Business Impact

| Impact Area | Results |
|-------------|---------|
| 🔍 Query Resolution Time | Reduced from hours to minutes |
| 🔁 Back-and-Forth Emails | Minimized through accurate identification |
| 📦 Root Cause Analysis | Enabled proactive issue classification |
| 💬 Team Collaboration | Streamlined across finance, merchandising, and operations |
| ⏱ Weekly Invoice Dispatch | Automated via Outlook/RPA using this distribution list |
| 📊 Supplier Trends | Identified recurring issue patterns for future BA/DA initiatives |

## 🧠 Lessons Learned

- Operational ambiguity can solve chaotic communication problems with low-code BA tooling + empathy for user workflows
- VBA + distribution logic can deliver massive leverage when paired with escalation paths and mapping in mind
- Building reusability upfront saved dozens of hours weekly
- Supplier query data, when structured, becomes a lens for systemic data QA and service-level trends

## 🛠 Tools & Tech Used

- Excel VBA (Auto-filter + Lookup logic)
- Outlook VBA for Email Automation
- RPA (Integration with distribution list)
- Business Analysis: Stakeholder Segmentation, Query Categorization Frameworks, Requirement Mapping, Escalation Mapping, Root Cause Analysis
"""

# Save the content to a markdown file
output_path = Path("/mnt/data/BA_Email_Workflow_Optimization.md")
output_path.write_text(markdown_content.strip())

output_path.name
