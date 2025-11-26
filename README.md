# Anveshak---The-Phishing-Detection-Tool
A powerful Python-based cybersecurity application designed to detect phishing websites, analyze URLs, perform network checks, and generate detailed security reports — all through an intuitive and modern CustomTkinter GUI.



📌 Overview

This project is a Python-based cybersecurity application that identifies phishing or malicious websites using a combination of:

Heuristic Analysis

WHOIS & DNS Inspection

SSL Certificate Validation

OpenPhish Threat Feed

VirusTotal & Google Safe Browsing APIs

AbuseIPDB IP Reputation

Webpage Content Scanning

Interactive Geolocation Mapping

All results are displayed through a modern CustomTkinter GUI and can be exported as a PDF Security Report.

🛡️ Key Features
🔍 1. Heuristic-Based Phishing Detection

Analyzes URLs based on:

Length & Encoding

Suspicious Keywords (login, verify, secure…)

Use of IP Address in URL

TLD & Domain Pattern

Page Content Phrases

SSL Certificate Validity

Domain Age & WHOIS Data

🌐 2. Threat Intelligence Verification

Integrates multiple security feeds:

OpenPhish (Known phishing URLs)

VirusTotal Domain Scanner

Google Safe Browsing API

AbuseIPDB IP Reputation

🗂️ 3. WHOIS & DNS Lookup

Fetches:

Domain creation/expiry

Registrar info

DNS records

IP address, ASN info

🌍 4. Interactive Map Generation

Shows server location on a generated Folium HTML Map.

📊 5. Visualization

Displays phishing risk using matplotlib pie charts inside the GUI.

📝 6. PDF Report Generation

Exports:

URL details

Heuristic results

WHOIS + DNS info

API scan results

Final verdict

💻 7. Executable Build

Includes PyInstaller config to generate a Windows .exe file.
