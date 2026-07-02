<p align="center"><img src="../assets/badges/pair-extraordinaire.png" width="140" alt="Pair Extraordinaire"/></p>

# 👯 Pair Extraordinaire

> **Goal:** Have a **co-authored commit** land in a merged pull request.

| Difficulty | Time | Tiers |
|:---:|:---:|:---|
| 🟢 Easy | ~10 min | 1 → 🥉 10 → 🥈 24 → 🥇 48 co-authored PRs |

---

## ✅ What counts
- A commit with a `Co-authored-by:` trailer, included in a **merged** PR.
- The co-author must be a **real GitHub account** (matched by email).

## 🪜 Step-by-step

1. Find the co-author's GitHub email. Two safe options:
   - Their **noreply** email: `ID+username@users.noreply.github.com`
     (find the numeric ID at `https://api.github.com/users/<username>`), or
   - Any verified email on their account.

2. Make a commit with the co-author trailer. 👇
   **The blank line before `Co-authored-by` is required:**
   ```bash
   git commit -m "feat: add feature

   Co-authored-by: NAME <ID+username@users.noreply.github.com>"
   ```

3. Push the branch, open a **Pull Request**, and **merge it**. 🔀✅

4. GitHub shows both avatars on the commit — badge unlocked! 🎉

## 💡 Tips
- Add **multiple** `Co-authored-by:` lines to credit more people (each on its own line).
- Pair with a friend for real — genuinely the nicest way to earn this.

## ⏳ When it appears
Minutes to a couple of hours after the merge.
