# Action-Repository

 How to test:
✅ Go to your action-repo on GitHub
 ✅ Do one of these:
Make a new push → Edit your README.md → Commit & push.


Open a new pull request.


This will:
GitHub → sends webhook to your ngrok URL.


ngrok → forwards to your Flask app /webhook.


Flask → saves the event to your local MongoDB.


✅ Then:
Refresh MongoDB Compass → You should see a new webhook_db database.
Inside it → you’ll see an events collection → inside that your push or pull request data.

How to test:
✅ Go to your action-repo on GitHub
 ✅ Do one of these:
Make a new push → Edit your README.md → Commit & push.
Open a new pull request.
This will:
GitHub → sends webhook to your ngrok URL.
ngrok → forwards to your Flask app /webhook.
Flask → saves the event to your local MongoDB.

✅ Then:
Refresh MongoDB Compass → You should see a new webhook_db database.


Inside it → you’ll see an events collection → inside that your push or pull request data.


