# **Project Status Report – Sprint 2**

**Project:** Expense Tracker Application  
**Date:** June 12, 2026  
**Prepared By:** [avrojit sen](mailto:avrojit2001@gmail.com)

# **1\. Project Summary**

The Expense Tracker project is designed to provide users with a seamless, intuitive platform for managing personal finances, tracking spending habits, and setting budget goals. Sprint 2 focused on expanding the core functionality through advanced reporting modules, dashboard enhancements, and the integration of a real-time currency conversion API to support international users.

# **2\. Current Status (RAG)**

| Metric | Status | Notes |
| :---- | :---- | :---- |
| **Overall Status** | **AMBER** | Delayed external dependency impacting multi-currency features. |
| **Schedule** | **AMBER** | Integration timeline shifted by 5 business days. |
| **Budget** | **GREEN** | Expenditures remain within the allocated baseline. |
| **Resources** | **GREEN** | Development team is fully allocated and productive. |

# **3\. Milestone Progress**

* **Sprint 1 Completion:** Successfully finalized core CRUD operations and user authentication.  
* **Sprint 2 Progress:** Development of the reporting engine and UI polishing is 90% complete.  
* **Dependency Delay:** Integration with the Currency Conversion API is currently blocked due to a provider-side authentication issue.

# **4\. Accomplishments This Period**

* **Reporting Module:** Completed the backend logic for monthly and category-wise expense aggregation.  
* **Dashboard Enhancement:** Implemented interactive data visualizations using Chart.js, allowing users to view spending trends.  
* **Regression Testing:** Conducted a full suite of regression tests on Sprint 1 features to ensure stability during new deployments.  
* **UI/UX Refinement:** Finalized the responsive design for mobile views, improving accessibility.

# **5\. Planned for Next Period**

* **API Resolution:** Direct escalation with the API provider to resolve credentialing errors.  
* **Workaround Implementation:** Deploy a local manual conversion table as a temporary fail-safe for the demo.  
* **Sprint 3 Backlog:** Finalize grooming for the "Social Sharing" and "Export to CSV/PDF" features.  
* **Stakeholder Demo:** Host a walkthrough of the reporting dashboard on Date.

# **6\. Issues and Risks**

* **Issue (High):** API provider delay. If unresolved, it prevents automated multi-currency tracking.  
* **Risk (Medium):** Stakeholder dissatisfaction regarding the delayed automated conversion feature.  
* **Mitigation:** Clear communication of the "Amber" status and the provision of a manual workaround to maintain project momentum.

# **7\. Budget Status**

The project budget remains **on track**. We have utilized approximately 40% of the total allocated funds, which aligns with our progress at the end of the second sprint. No unforeseen capital expenditures have occurred.

# **8\. Key Decisions Needed**

* **Approval for Workaround:** Seeking formal sign-off to implement a manual currency entry module to avoid stalling the frontend development.  
* **Timeline Agreement:** Agreement on a revised 3-day buffer for the final API integration milestone.

# **9\. Impact Assessment & Mitigation Plan**

While the API delay is a setback, the core value proposition of the Expense Tracker remains intact.

* **Impact:** The lack of automated currency conversion currently limits the "International Traveler" use case and has delayed the finalization of the global settings UI.  
* **Mitigation Steps:**  
  * **Manual Conversion:** We are implementing a temporary feature allowing users to input their own exchange rates manually.  
  * **Revised Timeline:** Shifting non-dependent Sprint 3 tasks forward to ensure the development team remains fully utilized.  
  * **Transparent Reporting:** Maintaining an "Amber" status until the API is fully functional to ensure all stakeholders have a realistic view of the integration timeline.

