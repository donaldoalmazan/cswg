---
date: 2025-11-20
title: Blog Start, Storm features and bug fixes
linktitle: blog-start
weight: 10

tags: [""]
categories: [""]
---

This post is a placeholder for testing and setup of the CSWG blog.

<!--more-->

## Blog Kickoff and Grid Progress

We kicked off the CSWG blog at [https://cswg.infrastructures.org/](https://cswg.infrastructures.org/), aiming for posts that sit between a simple changelog and longer technical write-ups. The goal is to document workshops, experiments, and design discussions with enough context to be useful, without becoming heavy or speculative. We also agreed to backdate posts for earlier workshops where notes already exist, and to distribute authorship by having someone other than the workshop facilitator write each post.

The group then reviewed early progress on the `grid` command. Angela and Steve shared a proof-of-concept focused on self-documenting, context-specific commands for operating a business. Using a filesystem-oriented model inspired in part by AFS, grid treats procedures, permissions, and even external hardware (such as printers) as files discovered within a business context. We discussed safeguards, access control, and open questions around efficiently distributing files across a decentralized system as the work evolves.

---

## Update Log

* CSWG blog launched; scope defined between changelog and long-form posts
  * Decision to backdate workshop posts where possible
  * Donaldo named Blog Editor; blog changes handled via pull requests
  * Plan to simplify contribution guide and write an editor procedure
* Initial `grid` command skeleton shared by Angela and Steve
  * Emphasis on a single entry point and self-documenting commands
* AFS discussed as a historical reference and contrast point
* Example grid workflow reviewed, including permissions and safeguards
  * Open questions noted around decentralized file distribution
* Storm features and bug fixes list reviewed; follow-up planned

---

## Resources

* CSWG Blog: [https://cswg.infrastructures.org/](https://cswg.infrastructures.org/)
* CSWG Repository: [https://github.com/ciwg/cswg](https://github.com/ciwg/cswg)
* Grid POC – Command Skeleton:
  * [https://github.com/promisegrid/grid-poc/tree/main/x/grid-cmd](https://github.com/promisegrid/grid-poc/tree/main/x/grid-cmd)
  * [https://github.com/promisegrid/grid-poc/blob/main/x/grid-cmd/grid-command-examples.md](https://github.com/promisegrid/grid-poc/blob/main/x/grid-cmd/grid-command-examples.md)
* OpenAFS: [https://openafs.org/](https://openafs.org/)
* AFS at Morgan Stanley (2021 talk): [https://workshop.openafs.org/afsbpw21/talks/auditing-afs-at-morgan-stanley-past-present-and-future/](https://workshop.openafs.org/afsbpw21/talks/auditing-afs-at-morgan-stanley-past-present-and-future/)
* Storm TODO List: [https://github.com/stevegt/grokker/blob/multiuser/x/storm/TODO.md](https://github.com/stevegt/grokker/blob/multiuser/x/storm/TODO.md)
