# RHCSA (EX200) Practice Repository – RHEL 10

This repository provides **hands-on, exam-aligned practice labs** for the  
**Red Hat Certified System Administrator (RHCSA) – EX200** exam, targeting **RHEL 10**.

It is designed for:
- Exam preparation
- Skill refresh for working system administrators
- Professional portfolio demonstration

All content is **outcome-focused**, **persistent**, and **reboot-tested**, mirroring real exam conditions.

---

## What This Repository Is

- A **complete RHCSA practice environment**
- A **self-contained lab workbook**
- A **professional GitHub portfolio project**
- A **real-world Linux administration reference**

This repo intentionally avoids shortcuts, GUIs, and unsupported tools.

---

## What This Repository Is NOT

- ❌ Exam dumps
- ❌ Red Hat proprietary content
- ❌ NDA-protected material
- ❌ Automated “one-command” solutions

Everything here is **original**, **educational**, and **NDA-safe**.

---

## Target Exam

- **Certification:** Red Hat Certified System Administrator (RHCSA)
- **Exam Code:** EX200
- **OS Target:** RHEL 10 (or compatible rebuilds)
- **Exam Style:** Performance-based, hands-on

---

## Repository Structure

```
rhcsa-ex200/
├── README.md
├── workbook/
│   └── rhcsa_workbook.md
├── labs/
│   ├── lab01-users/
│   ├── lab02-storage/
│   ├── lab03-networking/
│   ├── lab04-services/
│   ├── lab05-selinux/
│   ├── lab06-archiving/
│   ├── lab07-scripting/
│   └── lab08-containers/
├── scripts/
│   ├── examples/
│   └── autograde/
├── checklists/
│   └── manual-validation.md
└── vm-lab/
    ├── build.md
    └── reset.md
```

---

## Lab Coverage (Mapped to EX200 Objectives)

| Lab | Topic |
|----|----|
| Lab 01 | Users, Groups, Sudo |
| Lab 02 | Storage & LVM |
| Lab 03 | Networking (nmcli) |
| Lab 04 | Services & Firewall |
| Lab 05 | SELinux |
| Lab 06 | Archiving & Compression |
| Lab 07 | Bash Scripting |
| Lab 08 | Containers (Podman) |

Each lab includes:
- Scenario-based tasks
- Validation commands
- Common failure patterns
- Reset instructions

---

## VM Requirements

- RHEL 10 or compatible rebuild (Rocky / Alma)
- Minimal or Server install (no GUI)
- 2 vCPU, 4 GB RAM (minimum)
- 30–40 GB disk
- firewalld and SELinux enabled

See:
```
vm-lab/build.md
vm-lab/reset.md
```

---

## How to Use This Repository

### Recommended Workflow

1. Build VM using `vm-lab/build.md`
2. Take a clean snapshot
3. Complete labs **in order**
4. Reboot after each lab
5. Manually validate outcomes
6. Run auto-grading scripts
7. Repeat until consistent

---

## Auto-Grading

Read-only auto-grading scripts are provided to assist self-assessment.

Run all graders:
```
sudo ./scripts/autograde/grade_all.sh
```

Important:
- Scripts **do not modify the system**
- Manual validation always takes priority
- Passing the grader is not the same as passing the exam

See:
```
scripts/autograde/README.md
checklists/manual-validation.md
```

---

## Exam Mindset (Critical)

Red Hat exams grade:
- Correct outcomes
- Persistence after reboot
- SELinux compliance
- Minimal changes
- No unnecessary services

This repository enforces those habits.

---

## Professional Use

This repository is suitable for:
- GitHub portfolio
- Resume reference
- Interview discussion
- On-the-job refresh

It demonstrates:
- Linux fundamentals
- Security awareness
- Troubleshooting discipline
- Infrastructure reliability

---

## Disclaimer

This project is an **independent educational resource**.

It is **not affiliated with, endorsed by, or sponsored by Red Hat, Inc.**

Red Hat®, RHCSA®, and EX200® are trademarks of Red Hat, Inc.

No proprietary or confidential exam materials are used.

---

## License

This repository is intended for **educational and professional use**.  
See `LICENSE` for details.

---

## Next Steps

- Complete a **timed mock exam**
- Review the **day-of-exam cram sheet**
- Extend labs for **RHCE (EX294)** follow-on practice

---

**Practice clean.  
Validate everything.  
Reboot often.**