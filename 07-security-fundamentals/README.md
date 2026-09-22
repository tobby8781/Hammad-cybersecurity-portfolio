# Security Fundamentals — Attacks & Defenses

## Overview

This section documents the security fundamentals I learned during the TryHackMe Pre Security learning path.

The focus was on understanding common security weaknesses, basic attack concepts, and defensive controls used to reduce risk.

---

## 1. Security Fundamentals

Cybersecurity involves protecting systems, networks, applications, and information from unauthorised access, misuse, disruption, modification, or destruction.

A strong foundation requires understanding both:

- How attacks work
- How systems can be protected

The Pre Security material introduced these concepts before moving into more specialised security areas.

---

## 2. Authentication

Authentication is the process of verifying the identity of a user or system.

Examples of authentication factors include:

- Something you know
- Something you have
- Something you are

Authentication is different from authorisation:

- **Authentication:** Who are you?
- **Authorisation:** What are you allowed to access?

---

## 3. Password Security

Passwords are a common authentication mechanism and can become a security weakness when they are weak, reused, predictable, or exposed.

Good password practices include:

- Using strong, unique passwords
- Avoiding predictable passwords
- Avoiding password reuse
- Using a password manager where appropriate
- Enabling multi-factor authentication where available

---

## 4. Authorisation and Privileges

Authorisation determines what an authenticated user or process is allowed to do.

Excessive privileges increase the potential impact of a compromised account.

### Principle of Least Privilege

Users and processes should receive only the permissions required to perform their legitimate tasks.

This reduces unnecessary access and limits potential damage if an account or system is compromised.

---

## 5. Common Attack Concepts

The Pre Security material introduced different ways systems and users can be targeted.

Examples include:

- Social engineering
- Phishing
- Password attacks
- Malware
- Network-based attacks
- Web-based attacks
- Exploitation of vulnerabilities

Understanding these concepts provides context for later practical security investigations.

---

## 6. Phishing and Social Engineering

Phishing attempts to deceive users into revealing information, opening malicious content, or taking an unsafe action.

Social engineering attacks focus on manipulating people rather than relying only on technical vulnerabilities.

Important warning signs can include:

- Unexpected messages
- Suspicious links
- Requests for credentials
- Urgent or unusual requests
- Unexpected attachments
- Impersonation of trusted organisations or people

---

## 7. Malware

Malware is malicious software designed to perform unauthorised or harmful actions.

Examples include:

- Viruses
- Worms
- Trojans
- Ransomware
- Spyware

Understanding malware categories provides a foundation for later threat detection and incident response work.

---

## 8. Vulnerabilities and Exploitation

A vulnerability is a weakness that can potentially be exploited.

An attack may attempt to take advantage of a vulnerability to:

- Gain unauthorised access
- Execute unwanted actions
- Access sensitive information
- Disrupt a service
- Increase privileges

Security teams reduce risk through secure configuration, patching, monitoring, access controls, and other defensive measures.

---

## 9. Firewalls as a Defensive Control

Firewalls can control network traffic according to defined rules.

A firewall can be configured to allow or block traffic based on information such as:

- Source IP
- Destination IP
- Port
- Protocol
- Connection state, depending on firewall type

During the Pre Security practical work, I used a simulated firewall and observed how overly broad rules can unintentionally block legitimate traffic.

This reinforced the importance of precise security rules.

---

## 10. System Hardening

Hardening means reducing unnecessary attack surface and improving the security of a system.

Examples include:

- Applying security updates
- Removing unnecessary software or services
- Restricting privileges
- Using secure configurations
- Enforcing appropriate authentication controls
- Monitoring systems for suspicious activity

Hardening is a preventative security measure.

---

## 11. Security Monitoring

Security monitoring involves observing systems and network activity for signs of suspicious or abnormal behaviour.

Useful sources can include:

- System logs
- Network logs
- Authentication events
- Firewall events
- Application logs

The networking exercises in Pre Security introduced the importance of reading logs and identifying relevant events.

---

## 12. Incident Response Foundations

When suspicious activity is identified, security teams need to understand what happened and determine appropriate actions.

A basic incident-response mindset includes:

1. Identify suspicious activity.
2. Gather relevant evidence.
3. Understand the affected systems.
4. Determine the scope and impact.
5. Contain the activity where appropriate.
6. Remediate the underlying issue.
7. Review lessons learned.

More advanced incident-response techniques will be covered later in the Security Analyst learning path.

---

## 13. Defence in Depth

Security should not depend on a single control.

Defence in depth uses multiple layers of protection.

Examples include:

- Strong authentication
- Least privilege
- Secure configuration
- Firewalls
- Endpoint protection
- Network monitoring
- Logging
- Patching
- User awareness

If one control fails, additional controls can still reduce the impact.

---

## 14. Practical Knowledge Gained

During Pre Security, I practised and reviewed:

- Authentication
- Authorisation
- Least privilege
- Password security
- Phishing and social engineering
- Malware concepts
- Vulnerabilities
- Exploitation concepts
- Firewalls
- System hardening
- Security monitoring
- Network logs
- Basic incident-response concepts
- Defence in depth

---

## 15. Cybersecurity Relevance

These fundamentals provide the foundation for the next stages of my cybersecurity development.

They will support future learning in:

- Security operations
- SOC monitoring
- Threat detection
- Incident response
- Vulnerability management
- Network security
- Web security
- Security analysis

---

## Key Takeaways

- Authentication verifies identity.
- Authorisation determines what an authenticated user can access.
- Least privilege reduces unnecessary permissions.
- Weak or reused passwords can increase security risk.
- Phishing and social engineering target human behaviour.
- Malware can perform unauthorised or harmful actions.
- Vulnerabilities can create opportunities for exploitation.
- Firewalls help control network traffic.
- System hardening reduces attack surface.
- Logs provide evidence for security monitoring.
- Defence in depth uses multiple security controls.
- Understanding attacks and defences is essential for security analysis.

**Status: Completed — TryHackMe Pre Security**
