---
name: forms-submissions
description: "Submissions: List submissions with optional filters, Create a new submission (formId or packageSlug), Get submission by ID, Update submission metadata or progress"
---

# Submissions

- `submissions_list`: List submissions with optional filters
- `submissions_create`: Create a new submission (formId or packageSlug)
- `submissions_find_by_id`: Get submission by ID
- `submissions_update`: Update submission metadata or progress
- `submissions_delete`: Delete a submission
- `submissions_list_grants`: The links that exist for this submission; never their tokens
- `submissions_issue_grant`: Issue a link a buyer can open this submission with; the token is answered once
- `submissions_revoke_grant`: Revoke a link; it stops opening the submission at once
- `submissions_approve`: Approve a submission
- `submissions_get_files`: List all uploaded files for a submission with presigned download URLs
- `submissions_get_submission_form`: The form this submission answers, as this submission has it, with what a host needs to draw it
- `submissions_add_form`: Add a form to a multi-form submission
- `submissions_reject`: Reject a submission
- `submissions_request_changes`: Request changes on a submission
- `submissions_get_status`: Get submission completion status with required-field progress
- `submissions_submit`: Submit for review
- `submission_constraints_get`: What this submission's respondent may not change, and how its fields and groups are narrowed
- `submission_constraints_replace`: Replace this submission's constraints (organization only)
