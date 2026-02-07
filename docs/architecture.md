# Architecture

J.A.R.A uses n8n as the orchestration layer with FastAPI providing backend services.
Supabase stores job, candidate, and application data.
Playwright runs assisted automation steps that require human oversight.
