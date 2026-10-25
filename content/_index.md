---
title: ''
summary: ''
date: 2026-10-25
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research looks at how zero trust and microsegmentation hold up in the environments where they are hardest to apply: manufacturing floors, OT and ICS networks, and AI agents talking to each other. Current work covers OT network anomaly detection, measuring segmentation maturity, and zero trust for agent-to-agent communication.
    design:
      columns: '1'
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
      order: desc
    design:
      view: citation
---
