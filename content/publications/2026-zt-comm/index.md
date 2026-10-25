---
title: "ZT-COMM: Secure Agent-to-Agent Communication using Context-Aware Policies"
authors:
- me
date: "2026-10-12T00:00:00Z"
publishDate: "2026-10-12T00:00:00Z"

publication_types: ["article-journal"]
publication:
  name: "Under review"
peer_reviewed: false

summary: Under review. A framework that binds each AI agent session to its declared context and verifies every message against it, catching attacks that pass a valid mutual TLS handshake.

abstract: Two AI agents can complete a valid mutual TLS handshake and still be talking to an attacker. ZT-COMM adds mutual authentication, context-aware policy binding, continuous per-message integrity checks and a hash-chained audit log to agent-to-agent channels. In an open-source evaluation, it stopped all five tested attack types, including context manipulation, mid-session hijack and token replay, which mTLS-only, OAuth and allowlist baselines let through.

tags:
- AI Agent Security
- Zero Trust
- Network Security

featured: true

---
