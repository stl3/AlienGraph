---
id: Technical
created_date: 07/27/2023
type: how-to
year:  2023
tags:
- 07-2023
- how-to
author: aGuyOverThere
---

----

## For Engineers, Developers, Creators, and Anyone Interested

I'm going to break down the technology stacks that are currently in-play today just to help anyone who wants to help in this project get a good bearing on what's doing what. First and foremost, this is a very simple project (right now) and heavily relies on third party (3P) software.

### Obsidian

All notes are written in markdown within the Alien Graph Obsidian Vault. The **Source of Truth** for the vault is the [Alien Graph Github Page](https://github.com/aGuyOverThere/AlienGraph). For how I setup my Obsidian instance (plugins), see [[Setup Obsidian]].

---

### Webserver

The webserver is using the [Obsidian Publish Service](https://obsidian.md/publish) as I didn't want to host and manage a webserver along with a Markdown to HTML renderer (React Gatsby for example). This is a fairly low-effort and cost effective means to simply deploy an Obsidian graph to the web which, is why I opted to use it. I know there are open source versions of Publish but, again, this is a very fast and effective way to deploy. 

---

### Content Creation and Submission

Eventually, I just want to add collaborators to both Github and the [Obsidian Publish Collaborating feature](https://help.obsidian.md/Obsidian+Publish/Collaborating) but, I need some trustworthy people to help make this a reality. In reality, anyone who can write markdown should be able to contribute to this page and making it easy and efficient to do so is key. Today, however, this is one topic I've not fully flushed out as I'm currently the only one writing and deploying content. But the process that I think makes the most sense is:

1. User clones/downloads the obsidian vault from git
	1. `git clone https://github.com/aGuyOverThere/AlienGraph.git` **OR**
	2. `curl -L -O https://github.com/aGuyOverThere/AlienGraph/archive/refs/heads/main.zip`
2. User opens the downloaded vault in Obsidian.
3. User makes changes, additions, deletions
4. User submits changes via a git pull request OR user submits changes in the [Discord Channel](https://discord.gg/MJzQGzPGSG)