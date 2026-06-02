---
title: 'Post-mortem: Unauthorized Cline CLI npm publish on February 17, 2026'
url: https://cline.ghost.io/post-mortem-unauthorized-cline-cli-npm/
date: '2026-02-24'
author: Saoud Rizwan
feed_url: https://cline.ghost.io/rss/
---
On February 17th, a compromised npm token was used to publish an unauthorized version of the Cline CLI. No malicious code was delivered, and the Cline VS Code and JetBrains extensions were never affected. Here's the full breakdown of what happened, what we found, and what we've changed.
