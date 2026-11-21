---
title: "GitHub for Today's Hybrid Teams"
author: "Walt Ludwick"
pubDate: "Thu, 02 Jul 2026 12:00:00 GMT"
description: "In \"What Is the Terminal?\" Jon Udell frames the problem that his new product Bram aims to mitigate -and does surprisingly well, considering how new it is. The terminal has become far more approachable and powerful in this age of AI agents for everyone; you can now ask, in plain…"
urlNext: "https://ludwa6.github.io/practical-groupware-for-good-governance.md"
---
# {{page.title}}

## Technical or not, human or AI – could Bram be the missing link?

![The Bram desktop app: an AI agent's terminal on the left approving a commit, a live interactive social-system map on the right, and a worklist of commits below.](https://waltzweb.wordpress.com/wp-content/uploads/2026/07/screenshot-2026-07-02-at-13.23.13.png)

*Bram at work on my own repo: the agent's terminal on the left, the artifact it's building on the right. Screenshot by the author.*

In "[What Is the Terminal?](https://blog.jonudell.net/2026/07/01/what-is-the-terminal/)" Jon Udell frames the problem that his new product Bram aims to mitigate -and does surprisingly well, considering how new it is.  The terminal has become far more approachable and powerful in this age of AI agents for everyone; you can now ask, in plain language, for the software you want, and watch an agent go build it. And yet, for exactly that reason, comprehensibility of all that it is doing has become more of an issue than ever, for users of every stripe, however technical they may or may not be.

The easy reading of Jon's title is that Bram makes the terminal optional for people who fear it:  "The terminal is a foreign and hostile environment. Now it's optional," he writes, and that much is true. But the sharper point is the one that lands for experts too. In the age of AI agents the terminal has become a firehose: agent messages, your messages, tool calls, file reads, diffs and command output... All streaming past faster than anyone can absorb. Nobody- not the rawest beginner, nor the most seasoned engineer -takes in all of it in real time. That loss of comprehensibility is now a well-worn complaint in developer circles, and it's the problem Bram is really built against.

So this isn't "the terminal for dummies." Jon is explicit that the payoff reaches the pros: "if you are a terminal jockey," he writes, "you may enjoy the more legible display of agent messages, your messages, pasted screenshots, diffs, tool calls and results." That's the tell. Bram isn't hiding the work and dumbing it down for the beginner; it's making the same work legible- for the newcomer who never wants to see a shell, and just as much for the veteran who lives in one and still can't take in the torrent an AI agent throws off.

And legibility here is a set of concrete mechanisms, not a mood. Instead of one linear stream rushing past, Bram decomposes the work into surfaces you can actually inspect: a worklist of discrete tasks, a transcript of the exchange, readable diffs, an issues panel and a commits panel; those are the tabs running down the screenshot above. And between the agent proposing a change and that change touching your files, it interposes explicit gates: you approve what gets applied, then separately approve what gets committed. That is where comprehension is recovered- not by slowing the agent down, but by turning the firehose into discrete things a human can see, review and sign off on, one at a time. It is exactly what a developer needs in order to stay responsible for code they did not personally type.

Here's why that matters to me beyond the code. The teams I care about are hybrid in two directions at once. They mix technical and non-technical people: a farmer, an editor, a designer, a programmer. And, increasingly, they mix humans and AI agents working the same tasks. For twenty years, GitHub gave software teams a shared substrate for exactly this kind of collaboration: issues to name the work, commits to record it, review to bless it. What it never did was welcome the people who would never open a terminal, or the agents now working alongside them.

That's the missing link I think Bram might be. Not "GitHub for programmers," but GitHub for today's hybrid teams: the same legible, reviewable, version-controlled way of working, extended to everyone at the table, human and machine, coder and not. The agent proposes; a person understands enough to approve; the record is public and portable.

And notice the shape of this very post. I'm not replying to Jon inside some platform's walled garden. He wrote on his blog; I'm answering on mine; a pingback will quietly connect the two, and RSS will carry both to whoever's subscribed.  Read in, written out, via the same interface, [the way Dave Winer has always said the social web should work](http://scripting.com/2026/06/28.html#a131214). It's the same instinct as Bram: keep the substrate open, keep the work legible, and let people- and their agents -meet on ground nobody owns.  This ground is sacred; let us work to protect it.
