# Amaar-Passport-Ai-Agent

This notebook sets up a multi-agent system using crewai to automate passport application processing for Bangladesh. It defines three specialized agents:

Passport Policy Expert: Ensures compliance with e-passport rules, particularly for minors and seniors.
Financial Auditor: Calculates passport fees, including VAT, based on policy decisions.
Documentation Specialist: Generates a customized checklist and a summary in both English and Bangla.
The system then processes a user_query (e.g., for a 15-year-old requesting a 10-year passport) through a sequential workflow, with each agent contributing to the final "Passport Readiness Report." The LOCAL_DB variable holds the fee structure and required documents.

