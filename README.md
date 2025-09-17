# fb-scheduler-demo

This repository contains demo materials for the Facebook Page scheduler backend we will use for the Data Access Renewal.

**What’s included**
- `README.md` (this file)
- `scheduler_env.example.json` — placeholders for PAGE_ID and Page Access Token
- `curl_examples.md` — example curl commands for reviewers to run
- `postman/` — (will be added) Postman collection and environment JSON
- `demo_screencast.mp4` — (optional) 30–60s screen recording showing Postman -> scheduled post

**How to use**
1. Export the Postman collection from `postman/` (we will add it after you give the repo URL).
2. Replace placeholders in `scheduler_env.example.json` with test PAGE_ID and a sandbox Page Access Token (do NOT commit real tokens to repo; use the README instructions to upload token privately in the Data Access Renewal form).
3. Run the curl commands in `curl_examples.md` or import the Postman collection and run the "Create scheduled photo" request.

