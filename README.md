# J.A.R.A – Job Application and Referral Assistant (n8n Automation)

J.A.R.A is an ethical, AI-assisted job application and referral automation system.
This repository contains all n8n workflows used to power job ingestion, resume AI,
assisted job applying, referral requests, and application tracking.

## Features
- Job ingestion from multiple sources
- Skill match & ATS scoring
- AI resume generation (user data only)
- Assisted job applying
- Referral drafting (human approval)
- Application status tracking

## Tech Stack
- n8n (automation)
- FastAPI (backend)
- Supabase (database)
- Playwright (assisted automation)

## How to Use
1. Deploy n8n (Cloud / Railway / Docker)
2. Import workflows from `/workflows`
3. Update backend URLs in HTTP Request nodes
4. Activate workflows in order
5. Trigger via webhook

## Safety
- Human-in-the-loop approvals
- No CAPTCHA bypass
- Rate-limited automation
- No fake data generation

## License
MIT
