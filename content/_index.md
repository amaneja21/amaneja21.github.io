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
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
      count: 0
      order: desc
    design:
      view: citation
  - block: markdown
    id: patents
    content:
      title: 'Patents'
      subtitle: ''
      text: |-
        **2022** · [Deploying a Software Defined Networking (SDN) Solution on a Host Using a Single Active Uplink](https://patents.justia.com/patent/11258729)<br>
        US Patent 11,258,729 · Issued February 22, 2022
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research looks at how zero trust and microsegmentation hold up in the environments where they are hardest to apply: manufacturing floors, OT and ICS networks, and AI agents talking to each other. Current work covers OT network anomaly detection, measuring segmentation maturity, and zero trust for agent-to-agent communication.
    design:
      columns: '1'
---
