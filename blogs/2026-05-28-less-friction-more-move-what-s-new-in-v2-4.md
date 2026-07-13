---
title: "Less Friction, More Move: What’s New in v2.4?"
url: "https://aptoslabs.medium.com/less-friction-more-move-whats-new-in-v2-4-f5c1d642ec85?source=rss-70211828fe2e------2"
date: "2026-05-28"
author: "Aptos Labs"
feed_url: "https://aptoslabs.medium.com/feed"
---
Overview Based on feedback from Move developers, we added several new language features in the new default version 2.4 that aim at better ergonomics and expressivity: Explicit error messages in aborts instead of opaque abort codes, Public and package visibility for structs, enums, and constants, Extended capabilities for match expressions. We describe these new language features in more detail below: take a look, especially if you are a Move developer! Abort Messages For years, the recommended idiom for reporting a Move runtime error has been: /// Limit exceeded const E_LIMIT_EXCEEDED: u64 = 0
