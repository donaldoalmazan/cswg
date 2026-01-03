---
date: 2025-11-21
title: Git and Github Collaboration Workflows
weight: 10

tags: [""]
categories: [""]
---

## Git and Github Collaboration Workflows

This workshop walked through the `README.md` of the CSWG repository as a concrete entry point into how contributors collaborate on open source projects using Git and GitHub. While the immediate focus was the current workflow for site updates, the discussion broadened into general collaboration patterns—forks, branches, pull requests, and review cycles—that shape how work is shared and integrated. We noted that blog and post contributions may eventually follow a lighter-weight workflow, to be defined separately.

We also looked beyond CSWG to see how these patterns scale in larger projects. Reviewing active pull requests in the Gitea repository helped illustrate why branch-based pull requests matter, how GitHub supports iterative review, and where its strengths—and limits—lie. This led to a broader conversation about GitHub’s optimization for code-centric workflows and how PromiseGrid aims toward more flexible, generalized systems of exchange.

---

## Update Log

* Walkthrough of the CSWG `README.md` as a collaboration guide
* Overview of standard Git/GitHub workflows for contributors
* Clarified that workflow steps apply to the parent repository, not `./public`
* Noted that including `fixes #<issue>` in a commit or PR comment can auto-close issues
* Emphasized sending pull requests from feature branches, not `main`
* Discussed how GitHub appends new commits to an existing PR on the same branch
* Reviewed pros and cons of this behavior for iterative review cycles
* Identified need for a streamlined blog-post workflow

  * Likely no issue required for simple posts
  * Still use a new branch for each post
* Looked at a larger project (Gitea) to see collaboration at scale
* Discussed GitHub’s limitations beyond code-centric workflows
* Connected these limits to PromiseGrid’s longer-term vision
* Post-workshop discussion on lightweight status check-ins or interview-style updates

---

## Resources

* CSWG Repository & Workshop Material:
  [https://github.com/ciwg/cswg](https://github.com/ciwg/cswg)
* Gitea Pull Requests (example of a larger project):
  [https://github.com/go-gitea/gitea/pulls](https://github.com/go-gitea/gitea/pulls)
* GitHub Pull Request Documentation:
  [https://docs.github.com/en/pull-requests](https://docs.github.com/en/pull-requests)