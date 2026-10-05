# Security Fundamentals

This section documents my introduction to offensive and defensive security through the TryHackMe Cyber Security 101 learning path. Although I had previously studied both concepts during my cybersecurity degree, these practical exercises helped refresh my understanding and demonstrate the difference between approaching security from an attacker and defender perspective.

## Offensive Security

### Overview

Offensive security involves approaching a system from an attacker's perspective to identify weaknesses before they can be exploited by a malicious actor.

During the TryHackMe exercise, I worked with a simulated banking application called FakeBank. The practical exercise involved identifying functionality that was unintentionally exposed and understanding how an attacker could discover and interact with resources that were not intended to be publicly accessible.

### What I Learned

The exercise reinforced the importance of:

- Thinking from an attacker's perspective when assessing a system.
- Identifying exposed resources and functionality.
- Applying appropriate access controls to sensitive functionality.
- Reducing unnecessary exposure that could increase an organisation's attack surface.
- Understanding how seemingly small configuration or access-control weaknesses can create security risks.

### Key Takeaway

One of my main takeaways was that organisations should not assume that a resource is secure simply because users are not given a direct link to it. If sensitive functionality remains accessible, an attacker may still discover it.

This helped reinforce the importance of appropriate access controls, secure configuration and reducing unnecessary exposure.

---

## Defensive Security

### Overview

Defensive security focuses on protecting organisational systems and assets by monitoring activity, detecting threats, investigating suspicious behaviour and responding appropriately.

In the practical exercise, I worked through a simulated Security Operations Centre (SOC) investigation.

### Investigation

I monitored the SOC dashboard and identified a brute-force attack targeting a specific user account.

I investigated the activity and used available threat intelligence to gain additional context about the threat actor. The intelligence indicated that the group was associated with targeting credentials, which could potentially be sold or used for further malicious activity.

Based on the evidence available during the investigation, I responded by disabling the targeted account before the brute-force attempt could successfully compromise it.

As part of the investigation, I also:

- Reviewed the security alert.
- Investigated the suspicious activity.
- Used threat intelligence to understand the threat.
- Updated the threat intelligence information.
- Took a containment action.
- Documented the incident in an incident report.

### SOC Workflow

The exercise helped me understand a basic defensive security workflow:

**Monitor → Detect → Investigate → Enrich → Contain → Document**

Rather than simply observing an alert, a security analyst needs to understand what happened, determine the potential impact, gather additional context and take appropriate action.

### Key Takeaway

My main takeaway was the importance of responding to security events before they develop into successful compromises.

The exercise also demonstrated how threat intelligence can provide context during an investigation and help an analyst make more informed response decisions.
