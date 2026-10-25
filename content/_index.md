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
    id: highlights
    content:
      title: 'Highlights'
      subtitle: ''
      text: |-
        <style>
        .resume-biography{padding-top:2.5rem!important;padding-bottom:1rem!important}
        .hl-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:1.5rem;margin-top:1rem;width:min(1120px,92vw);position:relative;left:50%;transform:translateX(-50%)}
        @media (max-width:860px){.hl-grid{grid-template-columns:1fr;width:100%;left:0;transform:none}}
        .hl-card{display:flex;flex-direction:column;border:1px solid rgba(100,116,139,.25);border-radius:14px;overflow:hidden;text-decoration:none!important;color:inherit!important;background:rgba(255,255,255,.6);transition:transform .15s ease,box-shadow .15s ease}
        .dark .hl-card{background:rgba(30,41,59,.6);border-color:rgba(148,163,184,.25)}
        .hl-card:hover{transform:translateY(-3px);box-shadow:0 10px 24px rgba(15,23,42,.12)}
        .hl-card img{width:100%;aspect-ratio:16/10;object-fit:cover;margin:0!important;border-radius:0!important}
        .hl-patent{aspect-ratio:16/10;display:flex;flex-direction:column;align-items:center;justify-content:center;background:rgba(79,70,229,.08);font-family:inherit}
        .hl-patent b{font-size:1.6rem;letter-spacing:.02em}
        .hl-body{padding:1rem 1.1rem 1.2rem}
        .hl-tag{font-size:.75rem;text-transform:uppercase;letter-spacing:.08em;opacity:.7;margin:0 0 .35rem}
        .hl-title{font-size:1.05rem;font-weight:600;line-height:1.35;margin:0 0 .4rem}
        .hl-meta{font-size:.875rem;opacity:.75;margin:0}
        </style>
        <div class="hl-grid">
        <a class="hl-card" href="/events/2026-manusec-agentless-ot-visibility/">
        <img src="/media/highlights/manusec.jpg" alt="Amit Aneja presenting at ManuSec USA 2026">
        <div class="hl-body"><p class="hl-tag">Latest talk</p><p class="hl-title">Practical Strategies for Agentless OT Visibility and Microsegmentation for the Modern Factory Floor</p><p class="hl-meta">ManuSec USA 2026 · Chicago</p></div>
        </a>
        <a class="hl-card" href="https://info.zscaler.com/webinar-how-eaton-secured-its-manufacturing-facilities-with-zscaler" target="_blank" rel="noopener">
        <img src="/media/highlights/eaton.jpg" alt="Amit Aneja">
        <div class="hl-body"><p class="hl-tag">Latest webinar</p><p class="hl-title">How Eaton Secured Its Manufacturing Facilities with Zscaler</p><p class="hl-meta">Zscaler webinar · On demand</p></div>
        </a>
        <a class="hl-card" href="https://patents.justia.com/patent/11258729" target="_blank" rel="noopener">
        <div class="hl-patent"><span class="hl-tag">US Patent</span><b>11,258,729</b><span class="hl-meta">Issued Feb 22, 2022</span></div>
        <div class="hl-body"><p class="hl-tag">Patent</p><p class="hl-title">Deploying a Software Defined Networking (SDN) Solution on a Host Using a Single Active Uplink</p><p class="hl-meta">United States Patent and Trademark Office</p></div>
        </a>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['1rem', 0, '2rem', 0]
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research looks at how zero trust and microsegmentation hold up in the environments where they are hardest to apply: manufacturing floors, OT and ICS networks, and AI agents talking to each other. Current work covers OT network anomaly detection, measuring segmentation maturity, and zero trust for agent-to-agent communication.
    design:
      columns: '1'
---
