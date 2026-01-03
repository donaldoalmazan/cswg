---
date: 2025-11-23
title: Exploring VS Code Collaboration Features
linktitle: exploring-vscode-liveshare
weight: 10

tags: [""]
categories: [""]
---

## Exploring VS Code Collaboration Features

This workshop explored real-time collaboration workflows using VS Code, split into two parts: a short demo with Steve driving, followed by hands-on collaboration using shared tooling. We started from within the Storm environment and connected participants to Steve’s laptop via a browser-based Storm session with an SSH tunnel, alongside VS Code (and NeoVim on Steve’s side).

The primary demo focused on fixing a real bug in the CD International website: email addresses using newer TLDs (such as `.tech`) were incorrectly rejected during account creation. Using VS Code Live Share, we examined diffs, reviewed validation logic, and made a scoped fix under time constraints. The session emphasized collaborative review, cautious use of LLM-assisted changes, and always inspecting diffs before committing.

---

## Update Log

* Overview of VS Code collaboration and Live Share workflows
* Demo started from the Storm tool, with Steve driving
* Live bug fix in CD International site email validation
* Identified issue: newer TLDs (e.g. `.tech`) flagged as invalid
* Reviewed PHP email validation logic

  * `idn_to_ascii` usage
  * MX and A record checks
* Chose a simplified fix due to time constraints
* Compared diff views in VS Code and NeoVim
* Hands-on Live Share testing with participants
* Installed VS Code and Live Share extension
* Tested shared editing, following/unfollowing presenter, and session controls
* Encountered “unexpected file / needs authorization” issue
* Temporary workaround: selecting both input and output files
* Reminder emphasized: always review diffs before accepting LLM-generated changes

---

## Resources

* Visual Studio Code:
  [https://code.visualstudio.com/](https://code.visualstudio.com/)
* VS Code Live Share Extension:
  [https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
* Storm Project (active development):
  [https://github.com/stevegt/grokker](https://github.com/stevegt/grokker)