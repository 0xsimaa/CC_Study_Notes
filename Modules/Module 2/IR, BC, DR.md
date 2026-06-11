### 2.1 Understand Business Continuity (BC)

### What is Business Continuity?

**Business Continuity (BC)** is the capability of an organization to continue delivering products and services at acceptable predefined levels following a disruptive incident.

**Purpose**

To keep the business running (or recover quickly) when something bad happens — whether it’s a natural disaster, cyber attack, power outage, or supply chain failure.

**Importance**

- Prevents major financial losses
- Protects company reputation
- Helps meet legal and regulatory requirements
- Maintains customer trust

**Key Components of Business Continuity**

- **Business Impact Analysis (BIA)** → The most important starting point. Identifies critical business processes, their dependencies, and the impact if they stop.
- **Business Continuity Plan (BCP)** → The actual documented plan.
- **Recovery Strategies** → Alternate work sites, backup suppliers, cross-training employees, etc.
- **Testing & Exercises** → Tabletop exercises, simulations, full-scale drills.

**Types of Alternate Sites (Very Important for the Exam)**

| Site Type     | Description                                | Cost      | Recovery Speed   | When to Use                            |
| ------------- | ------------------------------------------ | --------- | ---------------- | -------------------------------------- |
| **Hot Site**  | Fully equipped, mirrored data, ready to go | Very High | Minutes to hours | Critical operations (banks, hospitals) |
| **Warm Site** | Partially equipped, needs some setup       | Medium    | Hours to days    | Important but not instant need         |
| **Cold Site** | Empty space with basic infrastructure      | Low       | Days to weeks    | Non-critical functions                 |

### 2.2 Understand Disaster Recovery (DR)

Disaster Recovery (DR) focuses specifically on restoring IT systems, data, and infrastructure after a disaster.

**Purpose**
To get technology back up and running as fast as possible after a major disruptive event.

**Importance** 
Disasters can destroy servers, corrupt data, or make offices unusable. DR ensures the technical backbone of the business recovers.

**Key Relationship:**
DR is usually a subset of Business Continuity. BC is about the whole business, while DR is about the IT side.

### Critical Metrics You Must Know

- RTO – Recovery Time Objective

	The maximum acceptable time to restore a system after a disaster. Example: “We must have email back within 4 hours” → RTO = 4 hours

- RPO – Recovery Point Objective

	The maximum acceptable data loss measured in time. Example: “We can afford to lose only 15 minutes of data” → RPO = 15 minutes

**Exam Tip:**
- Short RTO/RPO = expensive solution (hot site + frequent backups)
- Long RTO/RPO = cheaper solution (cold site + daily backups)

**Main Components of Disaster Recovery**
- Disaster Recovery Plan (DRP)
- Data backups (full, incremental, differential)
- Offsite storage / Cloud backups
- Redundant systems and failover capabilities
- Regular DR testing

**Simple Analogy I used:**
Business Continuity = Making sure the entire restaurant can still serve customers even if the kitchen catches fire.
Disaster Recovery = Making sure the stoves, fridges, and ovens are working again quickly.

### 2.3 Understand Incident Response

Incident Response (IR) is the structured approach to handling and managing security incidents (hacking, malware, data breach, insider threats, etc.).

**Purpose**

To detect, respond to, and recover from security incidents in a controlled and effective manner, while minimizing damage.

**Importance**

- Limits the impact of an attack
- Helps with legal and regulatory compliance (many laws require proper IR)
- Improves future defenses through lessons learned

### Main Components – The Incident Response Lifecycle

I strongly recommend memorizing this order:

- **Preparation** – Having tools, team (CSIRT), and plans ready
- **Identification** – Detecting and confirming an incident
- **Containment** – Stopping the damage from spreading (very important step)
- **Eradication** – Removing the root cause (delete malware, close vulnerabilities)
- **Recovery** – Bringing systems back to normal operation
- **Lessons Learned** – Review what happened and improve (post-incident review)