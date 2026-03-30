# 🐍 Open Source Audit — Python
OSS Capstone Project | Shell Scripting & System Analysis
📌 Overview

This project is a comprehensive audit of Python as an Open Source Software (OSS), implemented through a suite of Bash shell scripts. It demonstrates practical understanding of Linux environments, system introspection, package management, file systems, and automation.

The project aligns with core OSS principles: transparency, inspectability, and reproducibility.

👨‍🎓 Author
Field	Details
Name	Modansh Rao
Registration Number	24BAI10119
Program	B.Tech — AI & ML
Course	Open Source Software (OSS)
Institution	VIT Bhopal

🎯 Objectives
Analyze Python as an open-source ecosystem
Apply Linux shell scripting in real-world scenarios
Perform system-level inspection and logging analysis
Demonstrate OSS concepts through automation
Build reproducible and portable scripts

🛠️ Tech Stack
Category	Tools / Technologies
Language	Bash (Shell Scripting)
Platform	Linux (Ubuntu / WSL2)
Utilities	dpkg, grep, awk, du, ls, uname, date
Concepts	File Systems, Logging, Permissions, Package Management

⚙️ Environment Setup
1. Clone Repository
git clone https://github.com/<your-username>/OSS-Capstone-Python.git
cd OSS-Capstone-Python/scripts
2. Grant Permissions
chmod +x *.sh

📂 Project Structure
OSS-Capstone-Python/
│
├── scripts/
│   ├── script1_system_identity.sh
│   ├── script2_foss_inspector.sh
│   ├── script3_disk_permission.sh
│   ├── script4_log_analyzer.sh
│   ├── script5_manifesto_generator.sh
│
└── README.md
🚀 Script Modules
1️⃣ System Identity Report

Concepts: System introspection, environment variables

Extracts OS, kernel, uptime, user, and system metadata
Displays licensing information for Linux & Python
./script1_system_identity.sh
2️⃣ FOSS Package Inspector

Concepts: Package management, conditional logic

Verifies Python installation using dpkg
Extracts version, maintainer, and description
./script2_foss_inspector.sh
3️⃣ Disk & Permission Auditor

Concepts: File systems, permissions, storage analysis

Audits critical directories (/etc, /var/log, etc.)
Reports permissions, ownership, and disk usage
./script3_disk_permission.sh
4️⃣ Log File Analyzer

Concepts: File handling, pattern matching

Searches logs for keyword occurrences
Displays frequency and recent matches
echo -e "error: disk full\ninfo: ok\nerror: timeout" > test.log
./script4_log_analyzer.sh test.log error
5️⃣ Open Source Manifesto Generator

Concepts: User input, file writing

Interactive script to generate a personal OSS manifesto
Outputs a structured .txt file
./script5_manifesto_generator.sh
🔑 Key Learnings
Practical exposure to Linux system internals
Understanding of open-source licensing (GPL, PSF License)
Hands-on with shell scripting automation
Log parsing and system diagnostics
Writing modular, reusable scripts
📜 License

This project is created for academic purposes under the Open Source Software course at VIT.

Python → PSF License
Linux → GPL v2

🙌 Acknowledgements
Python Software Foundation
GNU Free Software Foundation
VIT Bhopal — OSS Course

⭐ Optional Enhancements (Future Work)
Add cron jobs for automated audits
Extend log analyzer with regex filters
Convert scripts into a CLI tool
Integrate with monitoring dashboards

💡 Why This Project Stands Out

This is not just a coursework submission—it reflects:

Systems thinking (OS + software interaction)
Automation mindset
Production-relevant Linux skills
Strong OSS fundamentals
