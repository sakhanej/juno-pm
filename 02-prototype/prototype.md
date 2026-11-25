# Prototype · Juno

> Module 2 · Prototype. The working build that tests your idea, made with your build tool of choice.

## Prototype link

No public share URL yet. Snippet attached
<img width="1450" height="743" alt="image" src="https://github.com/user-attachments/assets/d562a50e-d938-4242-a3ac-7c525aaf93af" />


The prototype uses fictional sample conversations and simulated sync and Jira actions.

## What it demonstrates

The PM selects chat sources and presses **Re-sync** to surface feature conversations in one source-linked inbox. Juno summarizes each ask, flags ambiguous requests as **NEEDS CLARIFICATION**, and previews a Jira intake draft for PM review without creating an issue.

## Debrief

*Draft based on the current prototype; update after testing it with PMs.*

- **What worked:** The single-screen flow makes the manual sync, source evidence, clarification state, and Jira handoff easy to follow.
- **What broke / felt like a toy:** Chat integrations, source references, and Jira actions are simulated. The prototype does not show whether Juno can reliably find requests, avoid duplicates, or preserve state between syncs.
- **What I'd change next pass:** Connect one real, PM-selected Webex Space; test feature detection and source citations against real conversations; then add a persistent intake ledger and verify that Jira creation stays behind explicit PM direction.
