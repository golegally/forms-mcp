# GoLegally Forms

Forms, submissions, field values and themes in GoLegally FormEngine.

## How it works

This package connects your AI assistant to one hosted MCP server at https://golegally-forms.mcp.pretuned.ai/mcp. It runs nothing on your computer. Your requests and the data they return go between your assistant and that server, and you sign in before it can reach your account.

## Skills

- **forms-action-catalogue**: Action catalogue: Predefined actions, the countries each serves, and whether this deployment can run them, The keys of the actions that cost money, Every run of a predefined action, newest first, The 
- **forms-field-actions**: Field Actions: List all actions for a field, Create a field action, Get a single field action, Update a field action
- **forms-field-values**: Field Values: Get all field values for a submission, Batch review multiple fields (admin only), Get a single field value, Save a field value (save-on-blur)
- **forms-form-packages**: Form Packages: List all form packages for the organization, Create a form package (ordered set of forms), Delete a form package, Get a form package by slug with its ordered forms
- **forms-forms**: Forms: List all forms for the organization, Create a new form definition, Get form by slug, Get active form by type
- **forms-group-instances**: Group Instances: Get all group instances for a submission, Ensure a target group count (idempotent; organization secret key only), Ensure minimum group instances exist (idempotent), Get instances for 
- **forms-submissions**: Submissions: List submissions with optional filters, Create a new submission (formId or packageSlug), Get submission by ID, Update submission metadata or progress
- **forms-themes**: Themes: List all themes for the organization, Create a new theme, Get a theme by ID, Update a theme
- **forms-validation**: Validation: Validate a merchant batch against actual organization-owned form definitions without saving, List the built-in validation patterns, optionally for one country, Get a specific validation pa

## Publisher

Published by Vadavision Private Limited.

Support: https://golegally.com/contact

Privacy: https://golegally.com/privacy

Terms: https://golegally.com/terms
