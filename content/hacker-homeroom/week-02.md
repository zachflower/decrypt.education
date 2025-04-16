---
title: "Week 2: MAC Daddy"
week: 2
draft: false
type: "hacker-homeroom"
---

### Themes

- Identity vs. identification
- Fingerprinting and tracking
- The futility of hardware-based trust

### Warmup

> Run ip link in your terminal. What brand is your network interface broadcasting? How often do you think it changes?

### Tool of the Week

- macchanger – The classic utility for changing MAC addresses
- Alt: ip link + ifconfig combo – Because it’s good to know what’s underneath the wrappers

### Required Reading

- "DHCP is Your Friend!" - Volume 19, Number 4 (Winter 2002-2003)
- "Vulnerabilities in Subscription Wireless" - Volume 21, Number 4 (Winter 2004-2005)
- "MAC Address Changer" - Volume 25, Number 2 (Summer 2008)

### Hands-On Objective

By the end of this week, you will have:

- Identified your device’s hardware MAC address
- Spoofed it to impersonate another device
- Used your new identity to bypass a basic access control system

### Prompt for Reflection

> If you can change your device's identity at will, what’s left of trust on the network?

### Assignment

- Use macchanger or a manual method to spoof your MAC address
- Connect to a restricted or captive portal network (in a sandboxed lab)
- Document how the network treated you differently—or didn’t
- Reflect on the ease or difficulty of being someone else, digitally

**Bonus:** Set up a cron job to randomize your MAC address every time you connect to Wi-Fi. Then write about whether this improved or hindered your experience online.
