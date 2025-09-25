Quick deploy (GCP)

- Flask service on port 5000.
- Deploy to GKE via Cloud Build.
- By default uses AI_SCORE_API_URL=http://ai-content-svc (cluster DNS).
- Optionally pass _AI_URL substitution to override with an external URL.
