---
layout: post
title: Do you trust this folder?
description: Mentor, mentee, or partner?
date: 2026-06-26
tags: ai claude-code github homebrew lessons
categories: essay
giscus_comments: false
related_posts: false
---

*A reflection on building this site with Claude Code, Anthropic's terminal-based AI coding assistant. Companion technical write-up coming as a project page soon.*

The first time I launched Claude Code, I stared at the screen for a few seconds.

I had typed `claude`, expecting it to ask what I wanted to build. Instead, it asked a different question.

**Do you trust this folder?**

The folder happened to be my home directory.

If I clicked **Yes**, I wasn't giving Claude Code access to a project. I was giving it permission to read, edit, and execute files across my home directory, including documents, downloads, SSH keys, configuration files, and everything else sitting on my laptop.

Rather than approving it, I exited, created a dedicated project folder, moved into it, and launched Claude Code again. That moment stayed with me for the rest of the project because the first lesson wasn't about coding. It was about permissions, context, and resisting the temptation to approve something before understanding what I was approving.

For the last few years, whenever someone asked what I did, the answer was easy. I built data platforms, cloud architectures, analytics systems, and production pipelines that quietly power businesses behind the scenes. Building a personal website felt like it should have been straightforward. There are countless tutorials that explain how to deploy a website in an afternoon. What they don't teach is how to build one while learning an entirely new way of writing software using AI agents, APIs, prompt engineering, and unfamiliar tools.

Within the first few hours, I realized that AI is remarkably good at helping you write software. It is equally good at exposing everything you don't know. More importantly, it can sound remarkably convincing even when it is wrong, making it difficult to challenge unless you understand enough to question it.

Whenever I tell people this website was built with Claude Code, I usually get one of two reactions. Some assume AI built the entire thing, while others assume I simply let AI do the work. Neither interpretation is accurate.

The experience felt much less like outsourcing and much more like pair programming. Claude Code could read documentation faster than I ever could, explain unfamiliar tools, and catch mistakes before I made them. It could also make confident but incorrect assumptions. Some days it felt like I was mentoring a junior engineer. Other days it felt like the junior engineer was mentoring me. Most of the time, we were simply solving problems together.

Enterprise engineering has a funny way of hiding complexity. Different teams own infrastructure, security, networking, deployment, and platform engineering, allowing you to become deeply specialized in one part of the stack while someone else quietly maintains the rest.

I'd used Git for years, yet I'd never configured it from scratch on my own machine. I had never generated my own SSH keys or thought much about terminal configuration because I'd simply never needed to. Those weren't gaps in my engineering knowledge. They were simply problems enterprise environments had already solved for me.

Coming from a data background, I was thinking about security long before I was thinking about features. How much access should an AI agent have? Which folders should it see? How do approval prompts work? Where should convenience stop and security begin?

Before starting this project, I wondered whether AI coding assistants would make software engineering feel smaller. Instead, they made judgment feel more important.

Writing code became easier, but making decisions became harder. Every approval prompt forced me to pause. Every debugging session reminded me to understand the problem before trying to fix it. Every permission I granted made me weigh the tradeoff between speed and safety.

The more capable the tool became, the more valuable traditional engineering habits felt. Reading documentation carefully, questioning assumptions, debugging methodically, and understanding the consequences of every decision mattered more, not less.

Looking back, the website isn't the most interesting thing I built.

The workflow is.

This project taught me how to collaborate with AI without outsourcing my thinking. It taught me when to trust the tool, when to question it, and when to slow down instead of reaching for the fastest solution. It reminded me that security is established with the first permission you grant, not after you've finished building.

The technical implementation of this project, including the architecture, tooling, debugging process, and security decisions, lives in the companion project write-up. This post isn't about how I built the website. It's about how building it changed the way I think about working with AI.

The website is just the artifact.

What I'll carry into every project from here is a different way of working. Understand permissions before approving them. Treat AI like a collaborator, not an autopilot. Keep the agent's world intentionally small. Slow down before clicking Yes.

Those lessons matter far more to me than the website itself because they'll outlast Claude Code, GitHub, and whatever the next generation of AI tools happens to be.
