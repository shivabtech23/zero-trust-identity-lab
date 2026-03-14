---
layout: default
title: Zero Trust & Identity Lab
---

# Zero Trust Lab Overview

A hands-on lab demonstrating how identity-based networking, least privilege,
and log analysis work together in a Zero Trust architecture.

---

## Learning Objectives

After completing this lab, you should be able to:
- Explain how Zero Trust differs from perimeter security
- Implement identity-based access control using Tailscale ACLs
- Enforce least privilege with Linux sudoers policies
- Use an LLM to summarize and investigate authentication logs

## Why this lab exists

Traditional security models often trust users or devices once they are "inside" the network. NIST SP 800-207 takes a different approach: every access request should be evaluated based on policy and context, not location alone.

This lab keeps that idea concrete:

- Identity decides access more than network position.
- Policies should be narrow and explicit.
- Administrative permissions should be limited to the minimum task required.
- Logs should be reviewed continuously because compromise is always possible.

## Outcomes

After completing the lab, you should be able to:

- Explain the difference between perimeter trust and zero trust.
- Identify trust boundaries in a simple environment.
- Read a policy that allows only one identity to reach one application port.
- Recognize how least privilege applies to Linux administration.
- Use an LLM carefully to accelerate log review without pasting secrets unnecessarily.

## Start Here

- [Read the full lab guide]({{ '/lab-guide.html' | relative_url }})
- [Open the Tailscale ACL example]({{ '/resources/tailscale-acl-example.json' | relative_url }})
- [Open the Linux sudoers example]({{ '/resources/junior-admin.sudoers' | relative_url }})
- [Open the sample auth.log]({{ '/resources/sample-auth.log' | relative_url }})

## Scope

This is intentionally a 2-hour lab. It introduces concepts and safe examples rather than full enterprise deployment patterns.
