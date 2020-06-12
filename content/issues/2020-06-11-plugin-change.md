---
title: "Minecraft: Turtle Server Plugin Change"
date: "2020-06-13T01:25:00+08:00"
resolved: true
resolvedWhen: "2020-06-13T01:30:00+08:00"
severity: down
affected:
  - "Minecraft: Turtle Server"
section: issue
---

We are going to be changing the configuration of Core Protect. Block and transaction logging will be disabled as we now have a whitelist so we don't have to worry about unknown players. Chat, commands, and player session logging will be left enabled.

While, strictly speaking, we could reload without restarting the server, we are going to do a full server restart to follow best practices.

The restart is scheduled for **{{< htrack "2020-06-13T01:25:00+08:00" >}}** and the expected downtime is 5 minutes.
