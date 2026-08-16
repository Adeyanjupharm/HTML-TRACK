# Contributing Guide

This is your step-by-step guide to picking an issue, building it, and getting it merged. Follow it exactly the first time — after that it'll feel automatic.

## 1. Pick an issue

Go to the repo's **Issues** tab on GitHub. Find one that's:

- **Open** (not closed)
- **Unassigned** (no one's name is on it yet)

Comment `"I'll take this"` on the issue, and wait for it to be assigned to you before starting.

## 2. Clone the repo (first time only)

```bash
git clone https://github.com/hey-techys/september-project.git
cd september-project
```

## 3. Create your branch

Always branch from the latest `main`:

```bash
git checkout main
git pull origin main
git checkout -b issue-<number>-<short-description>
```

Example: if you're doing issue #3, "Create an ordered list of your top 3 learning goals":

```bash
git checkout -b issue-03-ordered-list-goals
```

## 4. Create your challenge folder

Inside the correct block folder, create a new folder named after your issue, and build your work inside it as `index.html`.

```
challenges/block-1/03-ordered-list-goals/your-name/index.html
```

**Naming convention:** `<issue-number>-<short-slug>` — lowercase, hyphens, no spaces. This keeps folders sorted and searchable, and guarantees your work never collides with anyone else's folder.

## 5. Build your challenge

Write your HTML inside your `index.html`. Check the issue description for exactly what's required — most issues also link back to that block's article for a refresher.

Before opening a PR, check your own work:

- [ ] Does it use semantic HTML (not `<div>` for everything)?
- [ ] If it's a Block 2 (forms) issue — is every input labeled? Can you tab through it with your mouse unplugged?
- [ ] Does it look reasonable when opened directly in a browser?

## 6. Add yourself to the hub page (optional but encouraged)

Open the root `index.html` and add one line linking to your new challenge, under the correct block section. This builds the public hub page over the course of the month.

## 7. Commit and push

```bash
git add .
git commit -m "Complete issue #3: ordered list of learning goals"
git push origin issue-03-ordered-list-goals
```

## 8. Open a Pull Request

On GitHub, open a PR from your branch into `main`. In the PR description:

- Link the issue (`Addresses #3`)
- Add a one-line summary of what you built

## 9. Respond to review

A maintainer will review your PR. You might get feedback — that's normal and part of learning. Push additional commits to the same branch to address it; the PR updates automatically.

## 10. Merged!

Once merged, your points are logged in the scoring tracker. Time to pick your next issue.

---

**Questions?** Ask in the Hey_Techys Slack — don't sit stuck on git commands for more than a few minutes before asking.
