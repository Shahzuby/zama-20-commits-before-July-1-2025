# Zama "20 Commits" Bypass

> **Purpose:** This repository provides a simple, step-by-step guide to quickly generate 20 commits on GitHub. It can help simulate tasks like `Zama Dev Guild`'s "10 Commits Before 10 July" challenge — intended for **learning and testing purposes only**.

---

## Step-by-step
1. Go to: https://github.com/new
2. Repository Name: zama20
3. Tick "Add a README file"
4. Click Create repository

now goto your vps and do below task.

```bash
cd ~
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

3. Configure Git user (if not already set):

```bash
git config --global user.name "YourName"
git config --global user.email "you@example.com"
```

4. Add commits by appending to `README.md`. Example commands:

```bash
echo "Commit 1 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:00:01" GIT_COMMITTER_DATE="2025-06-30T01:00:01" git commit -m "Commit 1"

echo "Commit 2 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:15:13" GIT_COMMITTER_DATE="2025-06-30T01:15:13" git commit -m "Commit 2"

echo "Commit 3 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:30:22" GIT_COMMITTER_DATE="2025-06-30T01:30:22" git commit -m "Commit 3"

echo "Commit 4 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T01:45:33" GIT_COMMITTER_DATE="2025-06-30T01:45:33" git commit -m "Commit 4"

echo "Commit 5 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:01:07" GIT_COMMITTER_DATE="2025-06-30T02:01:07" git commit -m "Commit 5"

echo "Commit 6 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:20:11" GIT_COMMITTER_DATE="2025-06-30T02:20:11" git commit -m "Commit 6"

echo "Commit 7 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:33:19" GIT_COMMITTER_DATE="2025-06-30T02:33:19" git commit -m "Commit 7"

echo "Commit 8 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T02:50:05" GIT_COMMITTER_DATE="2025-06-30T02:50:05" git commit -m "Commit 8"

echo "Commit 9 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:12:29" GIT_COMMITTER_DATE="2025-06-30T03:12:29" git commit -m "Commit 9"

echo "Commit 10 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:30:03" GIT_COMMITTER_DATE="2025-06-30T03:30:03" git commit -m "Commit 10"

echo "Commit 11 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T03:44:56" GIT_COMMITTER_DATE="2025-06-30T03:44:56" git commit -m "Commit 11"

echo "Commit 12 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:01:09" GIT_COMMITTER_DATE="2025-06-30T04:01:09" git commit -m "Commit 12"

echo "Commit 13 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:20:20" GIT_COMMITTER_DATE="2025-06-30T04:20:20" git commit -m "Commit 13"

echo "Commit 14 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:40:00" GIT_COMMITTER_DATE="2025-06-30T04:40:00" git commit -m "Commit 14"

echo "Commit 15 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T04:59:44" GIT_COMMITTER_DATE="2025-06-30T04:59:44" git commit -m "Commit 15"

echo "Commit 16 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:12:12" GIT_COMMITTER_DATE="2025-06-30T05:12:12" git commit -m "Commit 16"

echo "Commit 17 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:33:27" GIT_COMMITTER_DATE="2025-06-30T05:33:27" git commit -m "Commit 17"

echo "Commit 18 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T05:50:00" GIT_COMMITTER_DATE="2025-06-30T05:50:00" git commit -m "Commit 18"

echo "Commit 19 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T06:10:10" GIT_COMMITTER_DATE="2025-06-30T06:10:10" git commit -m "Commit 19"

echo "Commit 20 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T06:30:01" GIT_COMMITTER_DATE="2025-06-30T06:30:01" git commit -m "Commit 20"
git push
```

> Git will prompt you for your GitHub username → enter your GitHub username.

Next, it will ask for a password → do not use your actual GitHub password. Instead, provide a Personal Access Token (PAT)

---

> How to Create Your GitHub Personal Access Token (PAT)

Open your browser and go to: https://github.com/settings/tokens

Sign in if prompted.

Click “Generate new token (classic)”.

Give your token a name, e.g., 123abc.

Under Scopes, check only repo ✅ to grant full access to your repositories.

Click Generate token.

GitHub will display a long token string, e.g.:ghp_YNafJi1cqgw........

Important: Copy it immediately — it will not be shown again.

On terminal when prompted for a password during git push, paste this token instead of your GitHub password.

Note: When pasting in the terminal, it may appear invisible — this is normal.

Just right-click and click enter.

Wait 5-10 minutes and done claim your role and delete or remove your PAT token And delete repo from vps.

---

follow me on twitter for more update https://x.com/ZeekeAlpha
