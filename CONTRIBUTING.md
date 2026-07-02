# 🤝 Contributing

Thanks for helping improve the **GitHub Achievements Guide**! 💙

## Ways to contribute
- 🆕 **New badge** — GitHub added one? Add a guide + badge image.
- 🔢 **Updated thresholds** — tiers changed? Fix the tables.
- ✍️ **Clearer steps** — better wording, screenshots, or GIFs.
- 🐞 **Fixes** — broken links, typos, outdated info.

## How to submit
1. **Fork** this repo and create a branch: `git checkout -b improve-quickdraw`.
2. Make your change (see structure below).
3. Open a **Pull Request** with a clear description. 🔀

## Repo structure
```
github-achievements-guide/
├── README.md              # Main guide + badge table
├── guides/                # One markdown file per badge
│   ├── pull-shark.md
│   └── ...
├── assets/
│   ├── banner.svg
│   └── badges/            # Official GitHub badge PNGs
├── LICENSE
└── CONTRIBUTING.md
```

## Adding a new badge guide
1. Drop the official badge image in `assets/badges/<name>.png`.
2. Copy an existing file in `guides/` and edit the goal, table, and steps.
3. Add a row to the badge table and a link in `README.md`.

## Style
- Keep it **beginner friendly** — assume little prior knowledge.
- Use **emojis** as visual anchors (like the existing guides). 🎯
- Prefer **copy-paste commands** and short numbered steps.
- Keep tricks **legit** — no fake stars, no ToS violations. 🚫

Please be kind and constructive. Happy badge hunting! 🏆
