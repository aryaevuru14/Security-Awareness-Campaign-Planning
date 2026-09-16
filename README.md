# Security Awareness Campaign Planning

A Python-based automation utility designed to programmatically generate a comprehensive, professional 4-week Security Awareness Campaign Plan document (`.docx`) tailored for cybersecurity internship requirements and administrative submissions.

## Project Overview

This tool automates the creation of a structured Word document that outlines a complete corporate security awareness program. It is built to help organizations or internship candidates deliver a standardized, ready-to-submit blueprint focusing on human-factor vulnerabilities, phishing simulations, password hygiene, and incident reporting protocols.

## Features

- **Automated Document Generation:** Instantly creates a formatted `.docx` file using `python-docx`.
- **Structured Curriculum:** Covers a rigorous 4-week schedule from executive summaries and objectives to weekly implementation phases.
- **Measurable Metrics:** Outlines concrete evaluation parameters, including phishing simulation click rates and training completion percentages.

## Project Structure

- `SecurityAwarenessCampaignPlanning.py`: The core automation script containing document generation, heading structures, and paragraph layouts.
- `Security_Awareness_Campaign_Plan.docx`: The generated output file ready for portal upload or offline review.
- `.git/`: Local version control repository tracking project evolution.

## Prerequisites

- Python 3.x installed on your system.
- `python-docx` library for Word document manipulation.

## Installation & Setup

1. Clone or download the repository to your local machine:
   ```bash
   git clone [https://github.com/aryaevuru14/Security-Awareness-Campaign-Planning.git](https://github.com/aryaevuru14/Security-Awareness-Campaign-Planning.git)
   cd Security-Awareness-Campaign-Planning

2. Install the required Python dependency:
```bash
pip install python-docx

## Usage

1. Open your terminal or code editor in the project folder.
2. Run the automation script:
```bash
python SecurityAwarenessCampaignPlanning.py

3. Locate the generated `Security_Awareness_Campaign_Plan.docx` file in your workspace directory.

## Git Workflow Reference

To push updates or track modifications to the remote repository:

```bash
git add .
git commit -m "Update campaign plan script or documentation"
git push origin main
