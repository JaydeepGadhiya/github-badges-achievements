---
layout: guide
title: YOLO
description: How to earn the YOLO badge by merging a pull request without a review.
---

<p align="center"><img src="../assets/badges/yolo.png" width="140" alt="YOLO"/></p>

# 🎲 YOLO

> **Goal:** Merge a pull request **without a review**.

| Difficulty | Time | Tiers |
|:---:|:---:|:---|
| 🟢 Easy | ~3 min | Single tier (no levels) |

---

## ✅ What counts
- Merging a PR that has **zero approving reviews**.
- Easiest on your **own** repo where no branch-protection review is required.

## 🪜 Step-by-step

1. On a repo you own, create a branch and make any change. 🌿
   ```bash
   git checkout -b yolo
   echo "You Only Live Once 🎲" >> README.md
   git commit -am "docs: yolo"
   git push -u origin yolo
   ```
2. Open a **Pull Request**. 🔀
3. **Merge it immediately** — do **not** request or add a review. ✅
4. That's it — living dangerously pays off. 😎

## ⚠️ Note
- On **team/shared repos**, merging without review bypasses quality gates. Do this on a personal test repo, not on important shared code.
- If the repo has branch protection requiring reviews, you won't be able to merge without one — use a fresh personal repo instead.

## ⏳ When it appears
Usually within minutes.
