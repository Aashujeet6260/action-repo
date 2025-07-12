# 🚀 GitHub Action Repo

This is the **GitHub Action Repo** used to test the webhook receiver.

It is used to trigger **Push**, **Pull Request**, and **Merge** events which are sent to the webhook receiver for processing.

---

## 📌 Purpose

✅ Contains dummy code, files, or a README so you can make commits and pushes.

✅ Used to open and close pull requests to test your webhook receiver.

✅ Connected to the webhook URL via GitHub Settings → Webhooks.

---

## ⚙️ How to Use

1️⃣ Clone this repo:

```bash
git clone https://github.com/Aashujeet6260/action-repo.git
cd action-repo
```

2️⃣ Make some changes:

- Edit `README.md` or add new files.
- Commit and push:

```bash
git add .
git commit -m "Test push event"
git push origin main
```

✅ This will trigger a **Push** event.

3️⃣ Create a pull request:

- Create a new branch:

```bash
git checkout -b feature/test-pr
# Make changes
# Commit and push branch
```

- Go to GitHub → Open a PR → Merge the PR → This triggers **Pull Request** and **Merge** events.

4️⃣ Verify your webhook receiver logs and your MongoDB Compass database.

---

## 📚 Related Repo

➡️ [webhook-repo](https://github.com/Aashujeet6260/webhook-repo) — the Flask server that receives these events.

---

**Happy Testing! 🚀**

