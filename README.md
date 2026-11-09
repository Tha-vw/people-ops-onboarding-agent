# People Ops Onboarding Agent

AI-assisted new-hire onboarding with a human in the loop.
Built with n8n, Claude (Anthropic), Google Workspace and Slack.

> 🚧 In progress · Practice project · Details are fictional.

## What it does
1. A recruiter submits a short form about a new hire.
2. The workflow checks the data and flags anything missing.
3. Claude drafts a personalised welcome email, a first-week plan and a note for the manager.
4. A People Ops reviewer approves or rejects the draft in Slack – nothing is sent without approval.
5. On approval: the email is sent, onboarding tasks are created with due dates,
   the manager is notified, and every AI draft and decision is logged.

## Design principles
- **AI drafts, a human decides.**
- **Rules, not AI, for anything that must be exact:** dates, tasks, recipients.
- **Data minimisation:** no ID numbers, salary or health data in the workflow.
- **Tested against misuse:** incomplete data, prompt injection, sensitive information.

## Coming soon
Workflow files, demo video, 16-case test results and a governance note
(GDPR, EU AI Act, Swedish co-determination).

## Contact
[LinkedIn](https://www.linkedin.com/in/thaiz-wyns)
