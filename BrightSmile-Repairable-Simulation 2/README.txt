BrightSmile Dental CRM — Repairable Practice Simulator

This repaired version adds the controls needed to perform the training cases against the ORIGINAL seeded workflows.

Files:
- index.html
- styles.css
- app.js

How to run locally:
1. Keep all three files in the same folder.
2. Open index.html in a modern browser.
3. Open Workflows in the sidebar.
4. Click Edit Existing on WF-01, WF-02, WF-03, WF-04, or WF-05 to edit the original seeded workflow.
5. Use Inspect / Test to run simulation QA tests. Test results are written into the Workflow Execution Log.
6. Use the Practice Case Labs buttons for click-by-click case instructions.
7. Use Contacts > Edit to set SMS consent for test contacts.
8. Use the workflow editor to configure task owner and round-robin eligible users.
9. Reset sandbox restores the original seeded dataset.

Cases supported:
1. WF-03 No-show Recovery: consent checks/manual fallback, task owner configuration, eligible/ineligible SMS tests.
2. WF-01 Website Lead: source filter, owner assignment, round-robin eligible users, before/after testing.
3. Duplicate Contact Cleanup: merge Ava (#121 into #101) and Sophia (#122 into #103), preserving tags/notes and relationships.
4. WF-04 Proposal Follow-up: edit existing workflow, activate, test.
5. Pipeline QA: edit opportunities and drag stage changes; restore original stage after test.

Simulation limitations:
- Local practice data only. No live HighLevel integration.
- No real email/SMS, task execution, calendar connection, or production automation.
- Test results simulate logic based on configured steps and fields; they are not external delivery proof.
- Changes persist in browser localStorage until Reset sandbox is used.
