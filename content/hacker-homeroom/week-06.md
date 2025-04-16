---
title: "Week 6: Trojan Horses for Homework"
week: 6
draft: false
type: "hacker-homeroom"
---

### Themes

- Client-server relationships
- Reverse shells and remote control
- Script-based intrusion

### Warmup

> Visit [https://replit.com](https://replit.com) and fork a simple socket-based chat client. What does it take to reverse the direction of the connection?

### Tool of the Week

- nc (netcat) – the hacker’s Swiss Army knife for networking
- Alt: Python’s socket library

### Required Reading

Search the 2600 archives for articles related to:
- Remote access tools (RATs)
- Python-based shells
- Command-and-control (C2) tactics

### Hands-On Objective

By the end of this week, you will have:

- Written a basic reverse shell in Python
- Connected a target system to a remote listener
- Executed commands remotely (in a controlled lab)

### Prompt for Reflection

> Is a shell still a weapon if it only answers when called?

### Assignment

- Create a simple Python script that connects back to your listener and accepts basic shell commands
- Document your listener setup, command structure, and any limitations
- Include safety measures to ensure it can’t be misused outside the lab

**Bonus:** Add basic obfuscation or persistence features, and explain how you’d ethically disclose this if you found it on a real system
