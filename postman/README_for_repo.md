# fb-scheduler-demo (artifacts)

Contains demo artifacts for the Facebook Page scheduler Data Access Renewal:

- `postman/Scheduler_Demo.postman_collection.json`
- `postman/scheduler_demo_postman_env.json`
- `curl_examples.md`

How to use:
1. Import the Postman collection and environment.
2. Replace environment variables (PAGE_ID, PAGE_ACCESS_TOKEN, SCHEDULED_TIMESTAMP).
3. Run "Create scheduled photo". Copy returned id to SCHEDULED_POST_ID and run "Get scheduled post" or "List scheduled posts".
4. Record a short screencast (30-45s) showing requests + responses and attach to the renewal.

**Security**: Do NOT commit real tokens or secrets to the public repo.
