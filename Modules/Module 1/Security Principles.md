### 1.1 Understand the Security Concepts of Information Assurance

This is the heart of Domain 1; and probably the most tested part of the entire exam. Everything in cybersecurity revolves around protecting information.

### The CIA Triad (Confidentiality, Integrity, Availability)

This is the single most important concept in the whole CC exam. Memorize it, understand it, and be able to apply it to any scenario.

#### Confidentiality

Keeping information secret and only accessible to authorized people.
**Real-world example:** Your medical records or company payroll data. 
**How it’s broken:** Someone steals your password or eavesdrops on unencrypted traffic. 
**Exam tip:** Think “Who is allowed to see this?”

#### Integrity

Making sure data is accurate, complete, and hasn’t been tampered with. 
**Real-world example:** Changing a bank transfer amount from $100 to $10,000. 
**How it’s broken:** Someone alters a file without detection. 
**Exam tip:** Think “Is the data still correct and trustworthy?”

#### Availability

Making sure authorized users can access the data and systems when they need them.
**Real-world example:** A website going down during Black Friday sales.
**How it’s broken:** DDoS attack or ransomware locking files.
**Exam tip:** Think “Can I get to it right now?”

### Authentication

Proving you are who you say you are.

- Something you **know** (password, PIN)
- Something you **have** (smart card, phone)
- Something you **are** (fingerprint, face ID)
- Something you **do** (typing rhythm, gait)

#### Multi-Factor Authentication (MFA)

Using two or more of the above at the same time. 
**Exam favorite:** “Password + text code to your phone” = 2FA (a type of MFA). 
Stronger than single-factor, but not perfect (SIM swapping attacks exist).

### Non-Repudiation

Making sure someone cannot deny they did something.
**Simple analogy:** A signed contract with a notary — you can’t later say “I never signed that.”
**How it’s achieved:** Digital signatures, timestamps, audit logs.
**_Exam tip_:** Often tested with “proof of origin” or “proof of delivery.”

### Privacy

Protecting personal information from unauthorized collection, use, or disclosure.
**Key difference from confidentiality:** Privacy is about people’s rights; confidentiality is about protecting any sensitive data.
**_Real-world_:** GDPR, CCPA, HIPAA all focus on privacy.

#### Quick Study Tip for 1.1:

**Whenever you see a scenario question, ask yourself:** “Which part of the CIA triad is being threatened?” Then check if authentication, non-repudiation, or privacy also apply.

---

### 1.2 Understand the Risk Management Process

Risk management is how organizations decide what to protect and how much effort to spend.

### Key Definitions (Memorize These)

- **Risk** = Threat × Vulnerability (potential for loss)
- **Threat** = Anything that could cause harm (hacker, natural disaster, insider)
- **Vulnerability** = Weakness that can be exploited
- **Asset** = Anything of value (data, systems, people, reputation)

### Risk Management Process (The Cycle)

- **Risk Identification** → Find the risks
- **Risk Assessment** → Measure how bad they are (likelihood × impact)
- **Risk Treatment** (the 4 options):
    - **Mitigate** → Fix or reduce it (install a firewall)
    - **Accept** → Live with it (low risk, too expensive to fix)
    - **Transfer** → Shift it to someone else (buy insurance, use a cloud provider)
    - **Avoid** → Don’t do the risky activity at all
- **Risk Monitoring** → Keep watching it because risks change.

**Risk Priorities & Risk Tolerance**

- Organizations have different **risk appetites** (some are very conservative, some are aggressive).
- _Exam tip_: Questions often ask “What should the company do?” based on their risk tolerance.

My Analogy: Risk management is like buying car insurance — you identify the danger (driving), assess how likely an accident is, then decide to mitigate (drive carefully), accept (no insurance on old beater car), transfer (buy insurance), or avoid (don’t drive).

### 1.3 Understand Security Controls

Security controls are the actual tools and practices we use to reduce risk.

There are three main categories:

| Type of Control    | What It Is             | Real-World Examples                                                 | Exam Tip                                     |
| ------------------ | ---------------------- | ------------------------------------------------------------------- | -------------------------------------------- |
| **Technical**      | Technology-based       | Firewalls, antivirus, encryption, access control lists (ACLs), MFA  | Most common in questions                     |
| **Administrative** | People & process-based | Policies, procedures, training, background checks, risk assessments | “The policy says…”                           |
| **Physical**       | Tangible, real-world   | Locks, fences, security guards, CCTV, badge readers, mantraps       | Often combined with access control questions |

**Important Concept: Defense in Depth**

Using multiple layers of controls (technical + administrative + physical) so if one fails, others still protect you.

### 1.4 Understand the ISC² Code of Ethics

This is short but heavily tested. ISC² expects you to know and live by these four canons (in order of priority):

- **Protect society, the common good, necessary public trust and confidence in information and systems.** (Biggest priority; society comes first)
- **Act honorably, honestly, justly, responsibly, and legally.**
- **Provide diligent and competent service to principals** (your employer/clients).