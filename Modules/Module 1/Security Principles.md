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