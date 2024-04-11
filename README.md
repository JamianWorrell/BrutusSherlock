![image](https://github.com/JamianWorrell/BrutusSherlock/assets/101946789/a9ce69c9-7ebc-435b-be5b-38b2237b44b8)

# Scenario
A Confluence server was brute-forced via its SSH service. After gaining access to the server, the attacker performed additional activities, which we can track using auth.log. Although auth.log is primarily used for brute-force analysis, we will delve into the full potential of this artifact in our investigation, including aspects of privilege escalation, persistence, and even some visibility into command execution.

## Category
### DFIR


# Task 1
Analyzing the auth.log, can you identify the IP address used by the attacker to carry out a brute force attack?
