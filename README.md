```bash

$ whoami
> Name: Olumo Emmanuel
> Focus: Offensive Security Research, Web Application Penetration Testing, & API Security.
> Mission: Moving applications from "Vulnerable" to "Hardened."

$ ls -R ./capabilities/
./capabilities/:
├── Application_Security
│   ├── OWASP Top 10 Exploitation
│   ├── Business Logic Vulnerabilities (BOLA / IDOR)
│   └── Race Conditions & State Manipulation
├── Recon_&_Mapping
│   ├── Automated Attack Surface Discovery
│   ├── API Endpoints Schema Reconstruction
│   └── Component & Dependency Analysis
└── DevSecOps_Core
    ├── Source Code Review (SAST/DAST)
    ├── Secure SDLC Integration
    └── Patch Verification & Remediation Testing

$ systemctl status deployment-stack
● node.service - Production Security Testing Environment
   Loaded: loaded
   Active: active (running)
   Stack:
     ├─ Interceptors: Caido, Burp Suite Professional
     ├─ Automation: Python (Custom Exploits), Bash, Go
     ├─ Recon Tools: OWASP ZAP, Amass, Nuclei, ffuf
     └─ Targets: Web Apps, REST/GraphQL APIs, Microservices

$ curl -X GET https://api.olumo.dev/connect
{
  "X": "@0lum0",
  "GitHub": "github.com/olumo",
  "Email": "olumo.ai@gmail.com",
  "Status": "Accepting application security & bug bounty contracts"
}
