# 🖼️ Portfolio Media & Verified Certifications Repository

> **Central Asset Storage & High-Resolution CDN for Developer Portfolio**  
> A structured media archive hosting verified engineering certifications, project demonstration banners, profile assets, and architecture diagrams used across Anshul Kanodia's digital portfolio, GitHub profiles, and interactive resumes.

[![GitHub](https://img.shields.io/badge/Hosting-GitHub_Raw_CDN-181717?style=flat&logo=github&logoColor=white)](https://github.com/AnshulKanodia/Images)
[![Certifications](https://img.shields.io/badge/Certifications-13_Verified-success?style=flat&logo=coursera&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 Overview & Small Description

This repository functions as the public, high-availability media repository and Content Delivery Network (CDN) for **Anshul Kanodia's** professional online presence.

It hosts high-resolution, uncompressed digital credentials, academic certificates from accredited institutions (Google Cloud, NPTEL, Coursera, FACE Prep), interactive portfolio screenshots, and project demonstration media. Serving assets via GitHub's raw content CDN ensures zero downtime, rapid caching, and consistent asset URLs across external applications, web platforms, and markdown documentation.

---

## ✨ Features

- **Verified Certifications Index**: Complete digital proof for specialized credentials in Artificial Intelligence, Cloud Computing, Database Administration, and Software Engineering.
- **Project Media Assets**: Standardized UI previews and hero banners for core engineering projects (Cyber Shield, Desktop Voice Assistant, Geocraft).
- **Fast Content Delivery**: Pre-optimized raster assets structured for quick embed into markdown documents and web applications via `raw.githubusercontent.com`.
- **Systematic Directory Taxonomy**: Strict separation of concerns between `certificates/`, `Profile/`, and `Projects/`.

### Verified Certifications Roster

| # | Certification Name | Issuer / Organization | File |
|---|---|---|---|
| 1 | **5-Day AI Agents Intensive Course** | Google / Kaggle | `certificates/5-Day AI Agents Intensive Course with Google.png` |
| 2 | **Applied Machine Learning in Python** | University of Michigan / Coursera | `certificates/Applied Machine Learning In Python.jpg` |
| 3 | **Cloud Computing & Distributed Systems** | NPTEL / Swayam | `certificates/Cloud Computing and Distributed Systems.jpg` |
| 4 | **MongoDB Associate Database Administrator** | FACE Prep | `certificates/MongoDB Associate Database Administrator...jpg` |
| 5 | **Fundamentals of AI and ML** | Accredited Institution | `certificates/Fundamentals of AI and ML.png` |
| 6 | **Introduction to Generative AI** | Google Cloud Skills Boost | `certificates/intro to generative ai.png` |
| 7 | **Introduction to Internet of Things** | NPTEL | `certificates/Introduction to Internet of Things.jpg` |
| 8 | **Programming in Java** | NPTEL | `certificates/Programming In Java.jpg` |
| 9 | **Python Essentials** | Cisco Networking Academy | `certificates/python essential.png` |
| 10 | **Operating Systems** | Academic / Professional | `certificates/Operating System.png` |
| 11 | **Open Source Software** | Professional Institute | `certificates/Open Source Software.png` |
| 12 | **Mitigate Threats & Vulnerabilities** | Cyber Security Council | `certificates/mitigate-threats-and-vulnerabilities...png` |
| 13 | **MATLAB Onramp** | MathWorks | `certificates/Matlab onramp.png` |

---

## 📂 File Structure

```text
Images/
├── .gitattributes                # Enforces binary tracking for image extensions
├── .gitignore                    # Excludes OS thumbnails and temporary cache files
├── LICENSE                       # MIT Open Source License
├── README.md                     # Comprehensive media index & embedding guidelines
├── Profile/                      # Professional developer portraits
│   └── main.jpg                  # Primary profile avatar
├── Projects/                     # Project banners & interface mockups
│   ├── main.jpg                  # Universal project header
│   ├── CyberShield/
│   │   └── main.jpg              # Cyber Shield preview thumbnail
│   ├── DVA/
│   │   └── main.jpg              # Desktop Voice Assistant banner
│   └── Geocraft/
│       └── main.jpg              # Geocraft project cover
└── certificates/                 # Verified course and credential certificates
    ├── 5-Day AI Agents Intensive Course with Google.png
    ├── Applied Machine Learning In Python.jpg
    ├── Cloud Computing and Distributed Systems.jpg
    ├── Fundamentals of AI and ML.png
    ├── intro to generative ai.png
    ├── Introduction to Internet of Things.jpg
    ├── Matlab onramp.png
    ├── mitigate-threats-and-vulnerabilities-with-security-.png
    ├── MongoDB Associate Database Administrator certification course by FACE Prep.jpg
    ├── Open Source Software.png
    ├── Operating System.png
    ├── Programming In Java.jpg
    └── python essential.png
```

---

## 🚀 Setup & Usage Guide

### Embedding Assets via Markdown
To reference any asset inside a GitHub `README.md` or external markdown file, use the raw content URL pattern:

```markdown
![AI Agents Certificate](https://raw.githubusercontent.com/AnshulKanodia/Images/main/certificates/5-Day%20AI%20Agents%20Intensive%20Course%20with%20Google.png)
```

### Embedding in HTML / Portfolio
```html
<img 
  src="https://raw.githubusercontent.com/AnshulKanodia/Images/main/Projects/CyberShield/main.jpg" 
  alt="Cyber Shield Preview" 
  loading="lazy" 
/>
```

---

## 🛠️ Tech Stack & Storage Details

| Attribute | Specification |
|---|---|
| **Storage Engine** | Git Repository / GitHub CDN |
| **Media Formats** | PNG (Lossless High-Res), JPG / JPEG (Optimized Web) |
| **Integrations** | Personal Portfolio Website, GitHub Profile README, Resumes |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — see the [LICENSE](LICENSE) file for details.
