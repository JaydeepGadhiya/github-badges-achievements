<p align="center"><img src="../assets/badges/pull-shark.png" width="140" alt="Pull Shark"/></p>

# 🦈 Pull Shark

> **Goal:** Get your pull requests **merged**. This is the easiest badge to grow over time.

| Difficulty | Time | Tiers |
|:---:|:---:|:---|
| 🟢 Easy | ~5 min | 2 → 🥉 16 → 🥈 128 → 🥇 1024 merged PRs |

---

## ✅ What counts
- Any **merged** pull request — including PRs on **your own** repositories.
- Private repos count too (if you share private contributions).

## 🪜 Step-by-step (self-merge method)

1. **Create a repo** (or use an existing one). 📦
   ```bash
   # locally
   git init pull-shark-demo
   cd pull-shark-demo
   echo "# Pull Shark Demo" > README.md
   git add . && git commit -m "chore: initial commit"
   git branch -M main
   git remote add origin https://github.com/<you>/pull-shark-demo.git
   git push -u origin main
   ```

2. **Create a branch and make a change.** 🌿
   ```bash
   git checkout -b update-readme
   echo "Learning about Pull Shark 🦈" >> README.md
   git commit -am "docs: update readme"
   git push -u origin update-readme
   ```

3. **Open a Pull Request** 🔀
   - GitHub shows a *"Compare & pull request"* button → click it → **Create pull request**.

4. **Merge it** ✅
   - Click **Merge pull request → Confirm merge**.

5. 🔁 **Repeat once more** — 2 merged PRs unlocks the badge.

## 💡 Tips
- Prefer real contributions? Fix typos in open-source docs — maintainers love easy, correct PRs.
- Each merged PR moves you toward Bronze (16), Silver (128), Gold (1024).

## ⏳ When it appears
Within minutes to a couple of hours after your 2nd merge.
