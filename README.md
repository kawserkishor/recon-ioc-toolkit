# 🧠 Recon Automation & IOC Enrichment Toolkit (Python)

## 🎯 Objective
Automate reconnaissance tasks and enrich discovered data using threat intelligence APIs to aid red teaming and SOC operations.

## ⚙️ Features
- Subdomain Enumeration (Subfinder, Amass)
- Directory/Endpoint Bruteforcing (ffuf)
- CVE Scanning via Nuclei
- IOC Enrichment:
  - VirusTotal (IP/DNS check)
  - GreyNoise (malicious context)
- Export to JSON, CSV, Markdown

## 💡 Sample Use Case
1. Run target enumeration and asset discovery
2. Automatically enrich discovered domains and IPs
3. Export enriched IOCs to SOC-friendly formats
4. Use outputs for further testing or threat hunting

## 📂 Folder Structure
- /scripts          # Python automation scripts
- /api-keys         # Sample config file (excluded from repo)
- /examples         # Sample input/output
- /docs             # API integration and schema explanation

## 📜 Requirements
- Python 3.9+
- `requests`, `csv`, `json`, `argparse`
- API keys for VirusTotal & GreyNoise (set in `.env` or config)

## 📝 License
MIT
