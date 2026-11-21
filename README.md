# NETWORKWALKS-B084-WK3-PASSWORD_CRACKING-
Practical cybersecurity training exercises from Week 3 of the NetworkWalks
Cybersecurity & Ethical Hacking program. All work here is authorized lab work
only — my own files / instructor-approved targets. Nothing here targets real
third-party accounts.

Primary learning objectives:

* Password security and password-strength testing
* Password hashing concepts
* Password-cracking concepts (authorized recovery only)
* John the Ripper (CLI)
* Johnny GUI
* Hash extraction (e.g. PDF → JTR hash)
* Evidence collection
* Security documentation
* Defensive password recommendations

> Status honesty: I only mark something done when the evidence file is really
> in the repo. Everything else stays `In Progress` / `Not Started` / `Optional`.

```text
Training: NetworkWalks Cybersecurity & Ethical Hacking
Week: 3
Focus: Password Security & Password Cracking
Student: Anthony Sifuna
Brand: SIFUNA CODEX
```

## My setup

```text
OS: Kali GNU/Linux Rolling 2026.2
John the Ripper: 1.9.0-jumbo-1+bleeding-aec1328d6c 2021-11-02 (OMP [linux-gnu 64-bit x86_64 AVX2 AC])
pdf2john: /usr/bin/pdf2john (installed)
Johnny GUI: not installed yet
Target: authorized NetworkWalks training PDF only
```

Small gotcha I hit today: `john --version` errors out on this jumbo build
("Unknown option") — bare `john` prints the banner instead. Noted in
`W3-PM1-JTR/john/commands.txt` so I don't forget.

## Progress log

```text
23 Sep 2026 — scaffolded repo, confirmed JTR 1.9.0-jumbo + pdf2john present,
               johnny missing. No cracking runs yet — placeholders everywhere.
[DATE] — PM1 pdf2john + john run ......... [ ]
[DATE] — PM1 screenshots 01-06 ............ [ ]
[DATE] — PM2 official task ................ [ ]
```

## Module status

| Module | Description | Status |
| ------ | ----------- | ------ |
| [W3-PM1-JTR](W3-PM1-JTR/) | Password Cracking with JTR | In Progress |
| [W3-PM2-NW-Tools](W3-PM2-NW-Tools/) | Password Cracking with NW Tools | Not Started |
| [OPTIONAL/W3-OPTIONAL1-AI-JTR](OPTIONAL/W3-OPTIONAL1-AI-JTR/) | AI JTR + Claude + Hexstrike MCP | Optional |
| [OPTIONAL/W3-OPTIONAL2-Mediroza](OPTIONAL/W3-OPTIONAL2-Mediroza/) | Mediroza Patient Portal | Optional |

Statuses change only when actual evidence lands. Optional modules stay
`Not completed / Optional` unless I actually do them.

## Layout
