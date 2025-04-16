---
title: "Week 3: The Network is the Computer"
week: 3
draft: false
type: "hacker-homeroom"
layout: "hackerhomeroom"
---

### Themes

- Trust models
- LAN-level exploitation
- Traffic interception

### Warmup

> Run arp -a in your terminal. What devices can you see on your network? Who are your digital neighbors?

### Tool of the Week

- ettercap – Swiss Army knife for LAN manipulation
- Alt: bettercap – modern, modular, and mean

### Required Reading

- "An Intoduction to ARP Spoofing" – Volume 18, Number 3 (Autumn 2001)
- "Fun With Network Friends" – Volume 25, Number 2 (Summer 2008)
- "Man in the Middle Attack" – Volume 27, Number 3 (Autumn 2010)

### Hands-On Objective

By the end of this week, you will have:

- Performed an ARP spoof on a local network (in a safe lab)
- Intercepted traffic between two hosts
- Captured credentials or unencrypted data (from a test target)

### Prompt for Reflection

> If your router trusts every packet it sees, what does that say about your network’s memory?

### Assignment

- Use ettercap or bettercap to spoof ARP responses in a closed network lab
- Intercept login credentials or other traffic from a controlled dummy target
- Document what was captured, how, and what could be mitigated

**Bonus:** Modify the traffic in-flight to inject a message, redirect a page, or leave a calling card—then explain the ethical implications
