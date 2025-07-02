# 🚀 GitHub Action Repository – `action-repo`

This repository is used to **trigger GitHub webhook events** (such as `push`, `pull_request`, and `merge`) which are sent to the backend listener in [`webhook-repo`](https://github.com/IshaGupta2010/webhook-repo).

---

## 📦 Purpose

- Perform commits and pull requests
- Simulate GitHub activity for webhook testing
- Integrates with a webhook endpoint that logs data to MongoDB

---

## 🔗 Webhook Details

This repository is connected to:
Webhook URL: https://<your-ngrok-subdomain>.ngrok-free.app/webhook
Content Type: application/json
Events: push, pull_request


> Make sure to update the Webhook URL if your `ngrok` tunnel restarts.

---

## 🔄 Sample Workflow

1. Push a commit to any branch
2. Create a new branch and open a PR
3. Merge a PR to simulate a `MERGE` event
4. Monitor events in [webhook-ui](https://github.com/IshaGupta2010/webhook-ui)

---

## 🧩 Related Repositories

- [Webhook Listener – webhook-repo](https://github.com/IshaGupta2010/webhook-repo)
- [Frontend Viewer – webhook-ui](https://github.com/IshaGupta2010/webhook-ui)
