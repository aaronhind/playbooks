# Incident Playbook – Brute Force Login Attempt

## Objective
Detect and respond to repeated authentication failures indicating password attack.

---

## Detection Signals
- Multiple failed login attempts
- Rapid authentication failures
- SIEM brute force alert

---

## Initial Triage Steps
1. Identify source IP
2. Confirm targeted account
3. Check if login succeeded

---

## Investigation Workflow
- Review authentication logs
- Check geographic origin
- Identify repeated patterns

---

## Severity Assessment
Medium if unsuccessful  
High if account compromised

---

## Containment Actions
- Block source IP
- Lock affected account
- Force password reset

---

## Recovery Actions
- Monitor account activity
- Review system integrity

---

## Documentation Requirements
Record timeline, logs, IP address, and actions taken.

---

## Lessons Learned
Implement stronger password policies.
