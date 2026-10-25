# 🦉 OICS

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OICS** — ICS / SCADA / OT Offline Security Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OICS — ICS / SCADA / OT Offline Security Auditor. It provides industrial protocol knowledge base — Modbus/TCP, DNP3, S7comm / S7commPlus, EtherNet/IP + CIP, BACnet/IP, OPC UA, IEC 60870-5-104, PROFINET, IEC 61850 MMS/GOOSE, HART-IP, Niagara Fox, CODESYS, GE-SRTP, OMRON FINS, MELSEC, Crimson, ... (ports, security properties, typical CVE classes).

---

## ✨ Features

- Industrial protocol knowledge base — Modbus/TCP, DNP3, S7comm / S7commPlus, EtherNet/IP + CIP, BACnet/IP, OPC UA, IEC 60870-5-104, PROFINET, IEC 61850 MMS/GOOSE, HART-IP, Niagara Fox, CODESYS, GE-SRTP, OMRON FINS, MELSEC
- Offline protocol identification from port lists, banner text and pasted packet hex (pure parsing)
- Deep packet decoders — Modbus MBAP+PDU, DNP3 link / transport / application, TPKT/COTP/S7, ENIP + CIP, BVLC/NPDU/APDU, OPC UA, IEC-104 APCI/ASDU, PN-DCP
- Function-code dictionaries flagging write / control /
- OT asset-inventory auditor (CSV / JSON, tolerant): exposure, unauthenticated protocols, default creds, outdated firmware, flat IT/OT networks, legacy HMI OS, remote access, missing monitoring / backups
- MITRE ATT&CK for ICS mapping + NIST SP 800-82r3, IEC 62443-3-3 SR and ISA/IEC zone references

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OICS                                     # interactive menu
./OICS --path ./config_or_ruleset
./OICS --demo
./OICS --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
