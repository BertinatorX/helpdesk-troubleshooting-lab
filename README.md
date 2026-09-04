# Help Desk Troubleshooting Lab

This repo is where I practice help desk and desktop support scenarios and work on entry-level IT troubleshooting skills. It documents common support tickets, troubleshooting steps, escalation notes, and what I'd say to the user.

## Purpose

I'm an Information Systems student getting ready for entry-level IT support roles, and this lab is how I practice working a technical issue the way a help desk technician would: gather information, reproduce or isolate the problem, try safe fixes, document results, and escalate when needed. It's simple on paper, the hard part is doing it in that order every time.

## Skills I'm practicing

- Ticket triage and issue documentation
- Hardware and software troubleshooting
- User communication and plain-language explanations
- Basic networking troubleshooting
- Windows, macOS, and Linux support concepts
- Password reset and account access workflows
- Escalation notes for Tier 2 support
- Security-aware support habits

## Repository structure

```text
helpdesk-troubleshooting-lab/
├── README.md
├── tickets/
│   ├── password-reset-and-mfa.md
│   ├── dns-resolution-issue.md
│   ├── dhcp-connectivity-issue.md
│   ├── printer-not-responding.md
│   ├── vpn-connection-failure.md
│   ├── slow-computer-triage.md
│   └── suspicious-email-report.md
├── templates/
│   ├── ticket-template.md
│   ├── escalation-template.md
│   └── user-response-template.md
└── notes/
    ├── troubleshooting-framework.md
    └── common-commands.md
```

## Ticket documentation format

Each ticket writeup follows this structure:

```text
Ticket summary:
User impact:
Environment:
Initial questions:
Troubleshooting steps:
Resolution:
Verification:
Escalation notes:
User-facing response:
What I learned:
```

## Planned ticket scenarios

I'm still writing these up.

### Password reset and MFA

Probably the most common ticket there is: account access problems, identity verification, MFA troubleshooting, and secure handoff steps.

### DNS resolution issue

A device that has network access but can't resolve websites or internal hostnames.

### DHCP connectivity issue

A device that receives an invalid IP address or can't obtain a lease.

### Printer not responding

The classic desktop support ticket: connectivity, queue status, drivers, and, maybe more than anything, user communication.

### VPN connection failure

VPN login, network reachability, client configuration, and escalation details. I'd rather hand this off with good notes than pretend I fixed it.

### Slow computer triage

Since "it's slow" is as vague as a ticket gets, this one is collecting symptoms, checking resource usage, reviewing startup applications, and documenting safe recommendations.

### Suspicious email report

A security-aware help desk response to a possible phishing email, including safe handling and escalation. Closest to the security work I'd like to end up in.

## Troubleshooting framework

Nothing clever here, it's the same list every time:

1. Confirm the user impact.
2. Gather system and error details.
3. Check the simplest causes first.
4. Make one change at a time.
5. Verify the result with the user.
6. Document what changed.
7. Escalate with useful notes if needed.

## Career relevance

This repo backs my applications for:

- Help Desk Technician
- IT Support Specialist
- Desktop Support Technician
- Technical Support Specialist
- Service Desk Analyst
- NOC Technician
- Cybersecurity Intern

Overall I want it to show I can think like a support technician, explain things clearly, and document technical work properly, not just fix it and move on.

## Current certification status

I'm studying for CompTIA Tech+ and plan to complete the exam by October 2026.

## Privacy note

Every ticket in here is made up for practice. None of them include real customer information, employer data, school data, or private screenshots.

## Development note

Parts of this repo were worked through with Claude (Anthropic's AI assistant, via Claude Code), which I used as a pair-programming, debugging, and writing aid. I ran the commands and made the calls myself, and verified the results on my own hardware.
