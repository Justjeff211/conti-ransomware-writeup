# Conti Ransomware Write Up

## 📌 Overview
This repository contains my full investigation and technical write‑up of a **Conti ransomware compromise** targeting a Microsoft Exchange server.  
The analysis was conducted using **Splunk 8.2.2**, reviewing **28,145 events** across Windows Security, Sysmon, and IIS log sources to reconstruct the complete attack chain.

## 🔍 Key Findings
- Identified **three exploited CVEs**:
  - CVE‑2020‑0796 (SMBGhost)
  - CVE‑2018‑13374
  - CVE‑2018‑13379
- Located a **trojanised cmd.exe** used for persistence.
- Documented attacker techniques for maintaining access even after exploit patching.
- Provided **24 annotated screenshots** supporting the investigation.

## 📂 Repository Contents
- `Conti Ransomware Write Up.pdf` → Full 24‑page technical report
- `/screenshots` → Individual images referenced in the report

## 🎯 Skills Demonstrated
- SOC investigation methodology
- Malware and exploit analysis
- Log correlation across multiple sources
- Clear technical documentation with visual evidence

## 🚀 Purpose
This project showcases my ability to:
- Perform in‑depth incident response investigations
- Identify exploited vulnerabilities and persistence mechanisms
- Communicate findings in a structured, professional format

## 📫 Contact
For collaboration or discussion, connect with me on [LinkedIn](https://www.linkedin.com/in/mojalefa-l-letsoara283b5a211).
