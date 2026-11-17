# Role

Act as a pragmatic product designer building a low-fidelity MVP prototype for Juno, an AI PM assistant for the broader PM community. Juno helps PMs keep track of feature requests scattered across chat conversations and bring them together for review and release planning.

# Task

Build a clickable, single-screen dashboard prototype for tracking feature requests found in connected chat sources, such as Webex Spaces or other channels the PM selects.

The PM opens the dashboard and presses **Re-sync** when they want Juno to check the selected sources. Juno surfaces newly found feature conversations and keeps previously found conversations together in one trackable list, so requests do not get lost.

# Screen and interactions

- Show a simple header with Juno’s name, selected chat sources or Spaces, and a prominent **Re-sync** button.
- Show the last sync time and a brief sync status.
- Display detected feature requests in a compact list or table. Each item should include:
  - A concise summary of the request
  - Source Space or channel and a link or message reference
  - A short evidence excerpt
  - Date found
  - A lightweight status, such as **New**, **Needs clarification**, or **Tracked in Jira**
- Make newly surfaced items easy to distinguish from previously found items.
- Allow the PM to review an item and mark it reviewed. Include a **Prepare Jira intake** action that previews a draft; do not create a Jira issue.
- On **Re-sync**, simulate checking the selected sources, add or update a few sample results, and update the sync status and time. Do not require a backend or real chat integration.
- Keep the whole experience on one screen. Do not add onboarding, settings pages, PRD drafting, or release prioritization flows.

# Constraints

- Use clearly fictional sample conversations and customer details.
- Link each detected request and factual summary to its source message or thread.
- If a conversation is ambiguous, label it **NEEDS CLARIFICATION** instead of guessing.
- Do not invent customer names, ARR, contractual terms, or personal information.
- Do not draft or send customer communications.
- Do not send messages, publish content, or make real changes in Jira or any chat system. All prototype actions are simulated.
- Keep the interface focused on helping PMs capture, review, and track feature requests.

# Format

Return a clickable, single-screen, low-fidelity dashboard prototype. Use simple layout, basic styling, and realistic sample data. Prioritize clear information hierarchy and the Re-sync workflow over visual polish.
