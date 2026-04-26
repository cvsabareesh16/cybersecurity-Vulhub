# Sample VAPT Report

## Project Name
VulnHub Lab Security Assessment

## Tester
Sabareesh C V

## Scope
This test was performed only on a local vulnerable lab machine created for cybersecurity learning.

## Tools Used

- Nmap
- Gobuster
- Burp Suite
- Metasploit
- John the Ripper

## Summary

The target machine had exposed services and weak configurations that allowed enumeration and further exploitation inside a legal lab environment.

## Findings

### Finding 1: Open Services Discovered

**Severity:** Informational

**Description:**
Open ports were discovered using Nmap. These services helped identify the attack surface.

**Recommendation:**
Close unused ports and restrict access using firewall rules.

---

### Finding 2: Weak Authentication

**Severity:** Medium

**Description:**
Weak or guessable credentials may allow unauthorized access.

**Recommendation:**
Use strong passwords, account lockout, and multi-factor authentication.

---

### Finding 3: Privilege Escalation Misconfiguration

**Severity:** High

**Description:**
Misconfigured permissions may allow a low-privileged user to gain higher privileges.

**Recommendation:**
Review sudo permissions, SUID binaries, and file permissions regularly.

---

## Conclusion

This assessment improved my understanding of the penetration testing process from scanning to reporting.
