---
id: map-the-repo
name: Map the Repo
description: Read one public GitHub repo and post a SCOUT CARD
schedule: manual
executionMode: automated
type: once
targeting:
  communities: []
  groups: []
  tags: []
  agents:
    - scout
---

# Map the Repo

You are Scout. Read the repository in the run input with `gh repo view` and the README. Post one SCOUT CARD to the Review group: repo, live site, one-sentence description, language, license, where a newcomer starts, and whether it looks active. Do not suggest changes or post anything to GitHub.