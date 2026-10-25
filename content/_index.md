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
    id: blog
    content:
      title: 'Blog'
      subtitle: ''
      text: |-
        **2026**
        - [Securing the Unsecurable: OT, IoT, and the Factory Floor](https://www.zscaler.com/blogs/product-insights/securing-unsecurable-ot-iot-and-factory-floor) · Zscaler · Aug 2026

        **2021**
        - [Firewall Integration in Azure VMware Solution](https://techcommunity.microsoft.com/blog/azuremigrationblog/firewall-integration-in-azure-vmware-solution/2254961) · Microsoft Tech Community · Apr 2021

        **2019**
        - [Next-Generation Reference Design Guide for NSX-T](https://blogs.vmware.com/networkvirtualization/2019/09/nsx-t-design-guide.html/) · VMware · Sep 2019
        - [Introducing IPv6 in NSX-T Data Center 2.4](https://blogs.vmware.com/networkvirtualization/2019/02/ipv6-support-in-nsx-t-2-4.html/) · VMware · Feb 2019

        **2018**
        - [Flexible Deployment Options for NSX-T Data Center Edge VM](https://blogs.vmware.com/networkvirtualization/2018/10/flexible-deployment-options-for-nsx-t-edge-vm.html/) · VMware · Oct 2018
        - [NSX-T: Multi-Tiered Routing Architecture](https://blogs.vmware.com/networkvirtualization/2018/02/nsx-t-multi-tiered-routing-architecture.html/) · VMware · Feb 2018
        - [NSX-T: Routing Where You Need It (Part 2, North-South Routing)](https://blogs.vmware.com/networkvirtualization/2018/01/nsx-t-routing-part-2.html/) · VMware · Jan 2018

        **2017**
        - [NSX-T: Routing Where You Need It (Part 1)](https://blogs.vmware.com/networkvirtualization/2017/09/nsx-t-routing-where-you-need-it.html/) · VMware · Sep 2017
    design:
      columns: '1'
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
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
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
