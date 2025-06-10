<h1 align="center">🕶️ SPECTERTRACE</h1>
<p align="center"><em>Every file leaves a trace — find it.</em></p>

---

### 🎯 Overview

**SpecterTrace** is a tactical metadata extraction tool built for OSINT analysts, red team operators, and digital investigators. It scans files for hidden data—timestamps, GPS, device info, authorship—and outputs a clean, actionable report.

> _“If you want to find the source, follow the shadows.”_

---

### 🧠 Key Capabilities

- 📸 Extract EXIF metadata from `.jpg` / `.png`  
- 📄 Parse author + software info from `.pdf` and `.docx`  
- 🛰️ Detect GPS coordinates & creation dates  
- 🔍 Flag sensitive metadata automatically  
- 💾 Export results as structured `.json` or plain text

---

### 🛠️ Built With

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python">
  <img src="https://img.shields.io/badge/ExifTool-Metadata-orange">
  <img src="https://img.shields.io/badge/PyPDF2-PDF-yellow">
  <img src="https://img.shields.io/badge/Python--docx-DOCX-lightgrey">
</p>

---

### ⚙️ Installation

```bash
git clone https://github.com/YOUR_USERNAME/spectertrace.git
cd spectertrace
pip install -r requirements.txt
python spectertrace.py /path/to/file
