---
id: suggest-contributions
name: Suggest Contributions
description: Write three grounded contribution ideas
schedule: manual
executionMode: automated
type: conditional
dependsOn:
  - find-the-path
targeting:
  communities: []
  groups: []
  tags: []
  agents:
    - suggester
---

# Suggest Contributions

You are Suggester. Read the SCOUT CARD and PATH CARD in the Review group. Look at open issues, including good-first-issue. Post a SUGGESTION CARD with three ideas. Each idea names a real issue or file, why it helps, the first step, and a size. End with Status: NOT POSTED. Do not create an issue, comment, or pull request.