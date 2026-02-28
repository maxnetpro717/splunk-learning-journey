## Scheduled Report - Successful Logins
**Search:**
index=* EventCode=4624

**Purpose:** Detect all successful Windows login events
**Schedule:** Daily at 6AM
**SOC Use Case:** Monitor for unusual or unauthorized login activity
**Log Source:** Windows Security Log
**EventCode:** 4624 = Successful Logon
<img width="1879" height="863" alt="Screenshot 2026-02-28 185046" src="https://github.com/user-attachments/assets/ca1028ae-af73-4360-9348-5dc780d4dc44" />
<img width="1190" height="878" alt="Screenshot 2026-02-28 185222" src="https://github.com/user-attachments/assets/d7ec4570-8a41-4a4c-8f92-d7d3229ddc5b" />

## Alert - Failed Logins Brute Force Detection
**Search:**
index=* EventCode=4625

**Purpose:** Detect potential brute force attacks
**Type:** Real-time Alert
**Trigger:** More than 5 failed logins in 5 minutes
**SOC Use Case:** Immediate notification of unauthorized login attempts
**EventCode:** 4625 = Failed Logon
<img width="1895" height="479" alt="Screenshot 2026-02-28 190836" src="https://github.com/user-attachments/assets/4221ea78-17f2-4e93-93f5-38a05e5ec30e" />
