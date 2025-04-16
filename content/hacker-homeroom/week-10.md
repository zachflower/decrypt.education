---
title: "Week 10: Persistence Is Futile (Unless You're the Hacker)"
week: 10
draft: false
type: "hacker-homeroom"
layout: "hackerhomeroom"
---

### Themes

- Startup scripts and scheduled tasks
- Autonomy through automation
- Malware vs. mischief

### Warmup

> Visit [https://crontab.guru](https://crontab.guru). Build a cron expression that would trigger your payload every day at 3:33 AM. Can you obfuscate it?

### Tool of the Week

- crontab – the time-triggered Swiss Army knife of Unix
- Alt: Windows Task Scheduler or systemd timers

### Required Reading

Search the 2600 archives for articles related to:
- Persistence techniques
- Autorun abuse
- Script-based system compromise

### Hands-On Objective

By the end of this week, you will have:

- Written a script that launches at system startup or on a timer
- Hid it using benign-looking filenames or paths
- Demonstrated it working in a sandboxed system

### Prompt for Reflection

> If a script runs every day but no one knows it’s there, is that still activity?

### Assignment

- Create a basic persistence mechanism for a script you’ve written
- Install and verify its execution across reboots or logins
- Document how it could be detected—and how you’d evade that

**Bonus:** Chain together persistence with another tactic from previous weeks (e.g., spoofed MAC + startup payload) and explain the design like a systems architect
