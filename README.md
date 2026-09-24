# SOC Phishing Analysis Lab

This repository is a personal practice lab for analyzing phishing emails from a SOC analyst perspective.

The goal is to practice investigating real-world phishing samples, including email headers, authentication, sender infrastructure, URLs, attachments, IOCs, threat intelligence, and evidence-based conclusions.

## Samples

The email samples are taken from the [phishing_pot](https://github.com/rf-peixoto/phishing_pot) repository by rf-peixoto, which contains phishing emails collected from honeypot accounts.

The samples are used strictly for educational and defensive security analysis.

## Structure

```text
cases/
└── 001/
    ├── sample-001.eml
    ├── analysis-001.md
    └── screenshots/
```

## Analysis Template

```markdown
# Phishing Analysis — Sample-001

## Headers

- Date:
- Subject:
- To:
- From:
- Reply-To:
- Return-Path:
- Sender IP:
- Resolve Host:
- Message-ID:

## URLs

- 

## Attachments

- Attachment Name:
- MD5:
- SHA1:
- SHA256:

## Description

- Sender Analysis:
- URL Analysis:
- Attachment Analysis:

## Verdict

- 

## Defense Actions

- 
```
