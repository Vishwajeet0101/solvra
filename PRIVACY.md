# Solvra - Privacy Policy

_Last updated: November 24, 2026_

Solvra is a browser extension that helps you revise LeetCode problems, save your accepted solutions to GitHub and/or
your computer, and stay focused while studying. This policy explains what data Solvra handles.

## The short version
- **Solvra has no server.** Everything runs inside your own browser.
- **Your data stays on your device**, except what you choose to send to GitHub (your solutions and notes).
- **We don't sell, share, or use your data for ads or analytics.** There is no tracking.

## What Solvra stores (only in your browser)
Stored with the browser's extension storage (`chrome.storage.local`) on your computer:
- LeetCode problems you solve: title, difficulty, topics, dates you submitted, revision schedule and history.
- Notes and "important points" you write.
- Your settings (theme, reminders, blocked sites, save options).
- Minutes spent per website (for the time tracker), kept only on your device.
- Your GitHub access token and GitHub username/avatar, used to push your solutions. It is never included in backups.

## What Solvra sends, and where
- **GitHub (api.github.com, github.com)** - only when you log in with GitHub and when an accepted solution is saved:
  your profile (to show your name), the list of your repositories (so you can pick one), and the solution code plus a
  README with your notes, pushed to the repository you chose. Logging in uses GitHub's standard OAuth authorization.
- **LeetCode (leetcode.com)** - Solvra reads, from your own logged-in session, whether a problem is solved, your accepted
  submissions and their code, so it can track revisions and save solutions. Nothing is sent to anyone else.
- **ChatGPT / Gemini** - the AI Assistant side panel simply shows chatgpt.com and gemini.google.com. Anything you type
  there goes to those services under their own privacy policies. Solvra does not read or store those conversations.

## What Solvra does NOT do
- No analytics, tracking, advertising, or selling/transferring of data to third parties.
- It does not read your browsing history; the time tracker only counts minutes per website name, locally.
- It does not collect passwords. GitHub login happens on GitHub's own page.

## Files on your computer
If you turn on "Save on this computer" or automatic backups, Solvra saves files into your Downloads folder
(or the folder you choose). They stay on your computer.

## Your control
- **Log out of GitHub** in Solvra's Settings at any time, and revoke access on GitHub > Settings > Applications.
- **Delete all data**: Solvra Settings > Your data > "Delete all data", or remove the extension.

## Contact
Questions or problems: open an issue at https://github.com/Vishwajeet0101/solvra/issues
