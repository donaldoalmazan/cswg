---
date: 2025-11-22
title: Storm Hands-on Demo
linktitle: storm-hands-on-demo
weight: 10

tags: [""]
categories: [""]
---

## Storm Hands-On Demo

This session focused on a hands-on walkthrough of **Storm**, exploring how AI-assisted developer workflows are reshaping the role of engineers toward higher-level architectural decision-making. We discussed current limitations of LLM tools in making sound architectural choices, and used Storm as a concrete environment to examine how those gaps show up in practice.

Steve demoed an older but actively evolving version of Storm, highlighting recent experiments, rough edges, and near-term improvements. Despite some unfinished pieces, the tool is already proving usable, with visible progress toward multi-project, multi-user workflows and tighter feedback loops for reviewing LLM-generated changes.

---

## Update Log

* Hands-on demo of Storm with active development in progress
* Discussion of AI agents’ impact on developer workflows and architecture decisions
* Current limitation: multiple Storm projects require different ports
* Introduced `storm-port` as a short-term workaround
* Goal identified: multiple projects running on a single port
* Multi-user authentication discussed; tokens preferred over GitHub OAuth
* Web UI tested lightly; confirmed partially working
* Project cards homepage shown; LLM-assisted styling
* Setup instructions displayed when no projects exist
* Local key–value database (`~/.storm/data.db`) using `bbolt`
* Long-term plan to replace `bbolt` with PromiseBase
* Demoed reviewing LLM-generated diffs, accepting/rejecting changes, and running tests
* Noted cases of LLM over-complicating code and future guardrails
* Overall assessment: Storm is already fairly usable and improving quickly

---

## Resources

* Storm TODOs & Active Development:
  [https://github.com/stevegt/grokker/blob/multiuser/x/storm/TODO.md](https://github.com/stevegt/grokker/blob/multiuser/x/storm/TODO.md)
* Go `bbolt` Key-Value Store:
  [https://pkg.go.dev/go.etcd.io/bbolt](https://pkg.go.dev/go.etcd.io/bbolt)
* Cobra (Go CLI Framework):
  [https://github.com/spf13/cobra](https://github.com/spf13/cobra)
* Related Post: *mcp-452-cswg-workshop-recap-and-planning*
