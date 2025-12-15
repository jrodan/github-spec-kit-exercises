
# Context
**Spec Kit Phase:** /speckit.specify (Specify)
**Learning Goal:** Define business requirements and translate them into a technical API spec, preparing to generate API, client, and server artifacts.



# Lab 2 — Specify: Define Business Specification and Prepare for Generation

Estimated time: 10–12 minutes



Goal
----
Define business requirements and translate them into a technical API spec, preparing to generate API, client, and server artifacts.

**Hint:** If you are unsure whether a requirement belongs in this phase or the next, or if the task is unclear, clarify with your team or facilitator before proceeding. Explicit clarification helps avoid rework and ensures everyone is aligned on the phase boundaries and deliverables.



**Checklist:** As part of this phase, a checklist will also be created (using `/speckit.checklist`) to help ensure your requirements are complete, clear, and consistent. Review and update the checklist with your team before moving to the next phase. 

**Important:** If the checklist contains open issues, you must resolve them and re-run the appropriate `specify` command to ensure all requirements are addressed before proceeding.

Steps
-----
1. **Capture business requirements:**
   - prompt with /speckit.specify and describe what the Orders API should do from a business/user perspective. For example:
     ```markdown
     # Orders API — Business Requirements
     - The API must allow listing all orders for an online shop.
     - Each order must have an ID and an amount.
     - Only authenticated users can access their own orders (future requirement).
     - The API should be extensible to support order status and filtering by date.
     - Besides the API spec, we want to generate frontend and backend clients as contract implementation based on the spec - nothing else.
     ```

3. **Review and commit:**
   - Review the file with your team (refer to your Constitution for the review process).
   - Commit both the requirements to version control.

Expected outcome
----------------
- You have a business requirements file, reviewed and committed, and are ready to generate API, client, and server artifacts.


