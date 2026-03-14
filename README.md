# Zero Trust & Identity Lab

A beginner-friendly, 2-hour lab for learning zero trust fundamentals through identity-aware access control, least privilege, and practical host hardening examples.

This repository is designed to be GitHub Pages-ready and easy to follow for workshops, self-paced learning, and internal enablement. The lab uses concepts from NIST SP 800-207 throughout: verify explicitly, limit access by policy, and assume breach.

## What you will learn

By the end of this lab, learners will be able to:

- Explain zero trust in plain language using identity, device, network, and workload context.
- Describe trust boundaries and why implicit trust is risky.
- Read and adapt a simple identity-based Tailscale ACL policy.
- Interpret a narrow Linux `sudoers` rule for least-privilege administration.
- Use an LLM as a security co-pilot to summarize and investigate `auth.log` entries safely.
- Answer basic review questions that reinforce zero trust decisions.

## Prerequisites

- Basic familiarity with Linux commands such as `cat`, `sudo`, and `systemctl`
- A GitHub account for viewing or publishing the lab with GitHub Pages
- Optional: a Linux VM or lab host for trying `sudoers` and log analysis exercises
- Optional: a Tailscale test network or demo environment

## Audience

This lab is for beginners in security, IT, platform engineering, and help desk or junior admin roles. No prior zero trust implementation experience is assumed.

## Lab Structure

- [Landing page](./index.md)
- [Detailed lab guide](./lab-guide.md)
- [Tailscale ACL example](./resources/tailscale-acl-example.json)
- [Linux sudoers example](./resources/junior-admin.sudoers)
- [Sample auth log](./resources/sample-auth.log)

## Suggested 2-Hour Agenda

| Section | Topic | Time |
| --- | --- | ---: |
| 1 | Zero trust and identity overview | 15 min |
| 2 | Trust boundaries and access flow | 15 min |
| 3 | Tailscale ACL walkthrough | 25 min |
| 4 | Linux least privilege with `sudoers` | 25 min |
| 5 | LLM-assisted `auth.log` analysis | 25 min |
| 6 | Review and questions | 15 min |

## GitHub Pages

This repository includes `_config.yml` and Markdown pages so it can be published directly with GitHub Pages from the repository root.

## License

Use internally or adapt for training. Add your preferred license before external distribution.
