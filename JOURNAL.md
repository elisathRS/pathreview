## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/117

**Issue title:** API docs don't include example curl commands


**Tier:** [X] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
The current API documentation located in docs/API.md outlines the available endpoints but lacks practical, ready-to-use invocation examples. Because of this missing information, developers setting up the project for the first time face unnecessary friction and cannot easily verify that the API is functioning correctly on their local machines. A successful fix will update the documentation to include clear, copy-pasteable curl commands for the endpoints (such as /auth/login, auth/register, /profiles, /health, or /reviews), enabling developers to immediately test and validate their setups.

**Selection notes / “Is this right for me?” checklist reasoning:** I am selecting this Tier 1 issue because it perfectly aligns with my current comfort level as a new contributor to this specific codebase. While I am comfortable with APIs and data architecture, starting with a Tier 1 documentation task is an ideal way to safely familiarize myself with the project's structure without risking unintended side effects in the core backend logic.
Furthermore, the scope of this issue is an excellent fit for my onboarding process. Instead of simply picking it because it "looked interesting," I chose it because the scope is tightly contained to a single file (docs/API.md). Writing the actual curl commands requires me to actively review and understand the routing, required headers, and request payloads for endpoints like /auth/login and /profiles. This makes it a highly strategic first issue, as it forces me to test the local setup and understand the application's data flow—serving as the perfect stepping stone before taking on more complex Tier 2 or Tier 3 feature tickets.

**Branch name:** docs/117-include-api-example-curl-commands

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger