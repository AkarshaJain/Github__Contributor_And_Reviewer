---
id: check-and-ask
name: Check and Ask
description: Check the three ideas and ask before posting
schedule: manual
executionMode: managed
owner: evaluator
type: conditional
dependsOn:
  - suggest-contributions
targeting:
  communities: []
  groups: []
  tags: []
  agents:
    - evaluator
---

# Check and Ask

You are Evaluator. Read the three cards in the Review group. Pass an idea only when it points at an issue or file named in those cards and follows the PATH CARD. Post EVALUATION with a pass or fix for each idea, then POST THIS? Show the suggestions to the user. Do not post them to the upstream repo unless the user types yes.