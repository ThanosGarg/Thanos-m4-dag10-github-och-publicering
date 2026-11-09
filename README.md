# Day 10 · GitHub and Publishing

_Module 4, UI/UX & Frontend Development, Lexicon IT-Proffs_

## What you will do today

You will upload your work with `git push` and publish your site using GitHub Pages. You will get a public URL that anyone can open.

## Background

So far, your commits have only existed on your computer. A _remote_ repository on GitHub serves as both a backup and a way to share your work. **GitHub Pages** lets GitHub display your HTML files as a real website at `https://your-name.github.io/repo/`.

## How to work (as usual)

1. **Fork** today's repository on GitHub (_Fork → Create fork_).
2. **Clone your fork:** _Code → HTTPS → copy the URL_. In the terminal (Ctrl+ö in VS Code): `git clone <url>`. Open the new folder in VS Code and start _Live Server_.
3. **Complete the assignment.** Save and check your work in the browser after each step. Make a commit after each completed step: `git add .` and `git commit -m "Describe what you did"`.
4. **Push** when you are done: `git push`.
5. **Submit in Microsoft Forms.**

If you get stuck, write down exactly where you got stuck and what you have tried, and bring it up first in the next guided session.

## The assignment step by step

### Step 1. Check the remote connection

In the terminal, run `git remote -v`. You should see `origin` with the URL of your fork on GitHub. This was set up when you cloned it.

### Step 2. Check the history on GitHub

Open your fork on GitHub and click _Commits_. Your commits since day 1 should be visible. This is the same `git push` you have been using all along. GitHub may have asked you to sign in the first time; you normally do not need to do that again.

### Step 3. Commit and push in one go

Make a small change, then run `git add .`, `git commit -m "..."`, and `git push`. Verify the change on GitHub. You now have the standard workflow: edit, add, commit, push.

### Step 4. Enable GitHub Pages

In your fork on GitHub, go to _Settings → Pages_. Under _Build and deployment_: Source = _Deploy from a branch_, Branch = `main`, folder `/ (root)`. Save. Wait 1–2 minutes.

### Step 5. Open your site

The URL appears at the top of the Pages settings. Open it. Are the images and CSS working? If not, check that the paths are relative (`css/base.css`, not `/css/base.css`).

### Step 6. Write the README

Edit `README.md`: include a title, one sentence about the site, a link to the live site, and the technologies you used. Commit and push.

## Checklist: how to know you are done

- [ ] `git push` has uploaded all your commits.
- [ ] GitHub Pages is enabled for your fork, and the live link works.
- [ ] Images and CSS load on the published site.
- [ ] README.md describes the project and includes the live link.
- [ ] You have submitted the link to your fork and your live link.

## Tips if you get stuck

- Getting a 404? Wait a few minutes and check that the file is named exactly `index.html` in the root folder.
- Missing images? Paths must not start with `/`, and filenames are case-sensitive.
- The repository must be public for Pages to work on a free account.
- Push rejected? Run `git pull` first and try again.

## Submission

**Deadline: tomorrow at 09:00.** Submit everything in Microsoft Forms. No oral presentation is required.

Fill in the following in the form:

1. A link to your fork of this repository.
2. Reflection: Paste the live link. What was your first thought when you opened your published site?

## Want to do more? (optional)

- Add a `.gitignore`.
- Add a screenshot of the site to README.md.

# Kafé Kardemumma

En responsiv webbplats för ett fiktivt kafé med meny och kontaktsida.

[Besök webbplatsen](https://thanosgarg.github.io/Thanos-m4-dag10-github-och-publicering/)

## Tekniker

- HTML
- CSS
- GitHub Pages
