### 3.1 Understand Physical Access Controls

Physical access control is about protecting the **actual location** of systems, data, and people. If someone can physically touch your server or walk into your server room, they can often bypass many logical controls.

### Purpose

Prevent unauthorized people from entering facilities, rooms, or areas where sensitive assets are located.

### Key Components of Physical Access Controls

**1. Physical Security Controls (Barriers & Entry Systems)**
- **Badge systems / Access cards** — Most common. Employees swipe or tap a card.
- **Biometrics** — Fingerprint, retina scan, facial recognition, palm vein.
- **Mantraps / Airlocks** — Two doors with only one open at a time. Prevents tailgating.
- **Turnstiles & Revolving doors** — Allow only one person at a time.
- **Fences, gates, bollards** — Outer perimeter protection.
- **Environmental design** — Lighting, clear sight lines, landscaping that doesn’t provide hiding spots (Crime Prevention Through Environmental Design – CPTED).

**2. Monitoring Controls**
- **Security guards** — Human presence, can make judgment calls.
- **CCTV / Video surveillance** — Deterrence + investigation. Can be monitored live or recorded.
- **Alarm systems** — Motion sensors, door contacts, glass break sensors.
- **Access logs** — Who entered, when, and where. Critical for audits and investigations.

**3. Authorized vs Unauthorized Personnel**
- Clear distinction between employees, contractors, visitors, and vendors.
- Visitors should be escorted and logged.
- **Tailgating / Piggybacking** — When an unauthorized person follows someone through a secured door. This is a classic exam topic.

**Exam Tip**: ISC² often asks about the **best control** to prevent tailgating. The answer is usually a **mantrap** or **turnstile** (not just a badge reader).


### 3.2 Understand Logical Access Controls

Logical access controls protect **digital resources**; files, databases, applications, networks, etc.

### Core Principles (Memorize These)

**Principle of Least Privilege**

- Users should only have the **minimum** access rights needed to perform their job.
- Example: A receptionist should not have admin rights on the company server.
- **Exam favorite**: “A user only needs access to the folders related to their department.”

**Segregation (or Separation) of Duties (SoD)**

- No single person should control all parts of a critical process.
- Example: The person who creates a vendor in the system should **not** be the same person who approves payments to that vendor.
- Prevents fraud and errors.

### Types of Access Control Models

This is the most tested part of Domain 3. Know the differences cold.

| Access Control Model                   | Who Decides Access?                                   | How Access is Granted                                                  | Best For                                          | Key Characteristics                                            | Real-World Example                                                                   |
| -------------------------------------- | ----------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Discretionary Access Control (DAC)** | **Owner** of the resource                             | Owner decides who gets access                                          | Most common in everyday use                       | Flexible, owner-based, uses Access Control Lists (ACLs)        | Windows file sharing — you decide who can read/edit your folder                      |
| **Mandatory Access Control (MAC)**     | **System / Security Administrator** (based on labels) | System enforces rules based on security labels (classification levels) | High-security environments (military, government) | Very strict, uses labels like Confidential, Secret, Top Secret | Bell-LaPadula model (no read up, no write down)                                      |
| **Role-Based Access Control (RBAC)**   | **Administrator** assigns roles                       | Users get permissions based on their **job role**                      | Large organizations                               | Most scalable and commonly used in companies today             | “Finance Manager” role automatically gets access to budget files and reporting tools |

**Other Important Concepts**

- **Access Control List (ACL)** — List of users/groups and their permissions on an object (file, folder, network share).