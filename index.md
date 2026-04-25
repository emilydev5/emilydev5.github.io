---
layout: home
author_profile: true
title: "Emily Foster — Cybersecurity Portfolio"
header:
  overlay_color: "#0D1117"
  overlay_filter: "0.6"
  overlay_image: /assets/img/header-bg.jpg   # optional: dark abstract/tech banner
  caption: ""
excerpt: >
  Blue team practitioner · Threat detection · CTF competitor ·
  Documenting the journey from curious to certified.
---

## About

I'm a cybersecurity practitioner focused on the blue team — threat detection,
log analysis, incident response, and continuous learning. I'm currently working
through a structured certification path (ISC2 CC → CompTIA Security+ → CySA+)
while building hands-on skills through CTFs, home lab work, and security tooling projects.

This site documents the work: writeups, tools, notes, and the honest account of
learning cybersecurity from the ground up.

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| Certified in Cybersecurity (CC) | ISC2 | ✅ In Progress |
| CompTIA Security+ | CompTIA | 🎯 Planned |
| CompTIA CySA+ | CompTIA | 🎯 Planned |
| CompTIA Network+ | CompTIA | 🎯 Planned |

---

## Projects

A selection of work in progress and completed projects. Each has its own page with
methodology, findings, and takeaways.

| Project | Focus Area | Status |
|---|---|---|
| [CTF Writeups](/ctf-writeups) | Offensive techniques, problem solving | Active |
| [Detection Rules](/detection-rules) | SIEM, YARA, ATT&CK mapping | Active |
| [Security Scripts](/security-scripts) | Python/Bash tooling & automation | Active |
| [Cert Notes](/cert-notes) | Study notes — CC, Security+, CySA+ | Active |

---

## Skills

**Blue Team & Detection** — Log analysis · SIEM · Threat hunting · Incident response fundamentals · ATT&CK framework mapping

**Security Concepts** — Network security · Vulnerability management · Risk & compliance · Cryptography basics · Identity & access management

**Tooling & Languages** — Python · Bash · Wireshark · Nmap · Splunk (learning) · TryHackMe · HackTheBox

**Frameworks** — NIST CSF · CIS Controls · MITRE ATT&CK · OWASP Top 10

---

## Recent Writeups

<!-- Jekyll will auto-list posts here when you add _posts/ entries -->
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}

*More in the [CTF Writeups](https://github.com/emilydev5/ctf-writeups) repository.*

---

## Contact

- **Email:** [emily@emilyfoster.dev](mailto:emily@emilyfoster.dev)
- **GitHub:** [github.com/emilydev5](https://github.com/emilydev5)
- **LinkedIn:** [linkedin.com/in/ecfoster](https://linkedin.com/in/ecfoster)
- **TryHackMe:** [tryhackme.com/p/emily228](https://tryhackme.com/p/emily228)
