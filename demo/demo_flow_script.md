# Demo Flow Script

## Setup
- Import workflows into n8n and activate them in order.
- Set `JARA_BACKEND_URL` in `env/.env.example`.

## Run Demo
1. Trigger job ingestion.
   - `POST /webhook/job-ingestion`
2. Confirm jobs are stored in the backend.
3. Run skill match and decision workflow.
   - `POST /webhook/skill-match`
4. Generate resume content for the target role.
   - `POST /webhook/resume-generation`
5. Submit assisted application and referral request.
   - `POST /webhook/apply`
6. Update status tracking and follow-up reminders.
   - `POST /webhook/status-update`
