
# Splunk AppInspect Checklist - O11y for SOCs

## App Info
- App Name: O11y for SOCs
- Version: 1.0.0
- Author: Leonard Wall
- License: Apache 2.0

## Required Checks
✔ App contains a valid `app.conf` file
✔ App has no hardcoded credentials
✔ All default configurations stored in `/default`
✔ External libraries are documented (none included in current build)
✔ Saved searches named descriptively
✔ Dashboard XML is valid and renders in Splunk UI
✔ ML models use modular inputs (if implemented in MLTK)
✔ No execution of external commands without user interaction
✔ Setup page is implemented (`setup.xml`)
✔ No references to local file system paths
✔ Code passes Python 3 compatibility (not applicable - no custom scripts yet)
✔ App does not override Splunk built-in behavior
✔ Includes license, notice, and versioning
✔ README provides user guidance

## Optional Enhancements
✓ GitHub-linked documentation
✓ Simulated data for easy evaluation
✓ ML-based and rule-based detections
✓ MITRE ATT&CK + NIST CSF mapping
