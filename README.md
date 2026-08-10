# Homelab v3.1

This repository documents the third major iteration of my cybersecurity homelab and a substantial modification to that environment, hence **v3.1**. It is a technical workspace for building, executing, investigating, and documenting controlled security-monitoring exercises.

## Purpose

I maintain this repository to make my technical work visible, improve as a security practitioner, and demonstrate the practical skills I am developing for Junior SOC Analyst roles and future blue-team positions. My blog and LinkedIn contain broader writing and professional reflections; this repository is reserved primarily for technical projects and their supporting evidence.

## Project Navigation

- [Infrastructure Baseline](Infrastructure-Baseline.md) — physical host, virtual machines, networking, monitoring, and recovery design
- [Proof-of-Concept Exercise](Exercise-PoC.md) — primary exercise report, investigation, findings, and response analysis
- [Appendix A: Collections](Appendix-a-collections.md) — chronological evidence collection and exercise execution
- [Appendix B: Research](Appendix-b-research.md) — Wazuh ruleset research and project-planning process
- [PoC Assets](assets/poc/) — full-resolution screenshots used throughout the documentation

Together, the infrastructure baseline, exercise documentation, appendices, and assets form the complete proof of concept for this lab.

## Current Lab

The environment is hosted on a Dell PowerEdge R730 running Proxmox VE. It includes a Windows 10 endpoint monitored by Wazuh and Sysmon, a Kali Linux adversary-emulation system, and an Ubuntu-based Wazuh all-in-one deployment. The baseline is restored between exercises so that intentional changes to the attack surface can be documented and evaluated.

## External Writing

- [SolvingCyber](https://solvingcyber.com/) — cybersecurity learning and professional writing
- [LinkedIn](https://www.linkedin.com/in/brian-randall-102621199/) — project updates and professional background

This README is an interim project index and will continue to evolve as additional exercises are added.
