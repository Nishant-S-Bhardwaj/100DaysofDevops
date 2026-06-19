# 100 Days of DevOps Journey 🚀

Welcome to my **#100DaysOfDevOps** tracking repository! This repository serves as a daily log of my journey as I dive deep into DevOps, cloud engineering, automation, and infrastructure. Inspired by industry frameworks and guided by top communities, I am moving out of my comfort zone, shifting my mindset from "coding features" to "delivering value," and building my technical foundations from the ground up.

---

## 📅 Daily Progress Log

### 🛠️ Day 01: Version Control Foundations (Git & GitHub)
* **Date:** June 2026
* **Instructor/Resources:** *Git and GitHub from Beginner to Pro* by Rahul Wagh & KodeKloud Labs

#### 1️⃣ What I Learned
I kicked off Day 1 by restructuring my understanding of version control. I used to think Git was just a simple tool for saving local code updates, but today provided a crucial reality check. Version control is the structural backbone of modern CI/CD pipelines, collaborative engineering, and infrastructure-as-code state management.

#### 2️⃣ Core Concepts Covered
* **Basic Git & Branching:** Learned how to cleanly isolate experimental features and hotfixes without disrupting the stable `main` branch codebase.
* **Pull, Push, & Merge Operations:** Mastered the core data transport mechanics between local working directories, staging areas, and remote GitHub repositories.
* **Resolving Merge Conflicts:** Learned how to safely approach, analyze, and resolve line-by-line code conflicts directly when upstream changes clash with local branches.
* **Git Fetch vs. Pull:** Evaluated how `git fetch` updates local remote-tracking branches safely to audit upcoming shifts without forcing immediate merges into working files.

#### 3️⃣ Hands-on Execution
* **Lab Environment:** KodeKloud Git Labs
* **Tasks Completed:** Executed real-world terminal scenarios initialized inside sandbox environments. Practiced configuring local repositories, committing standard project histories, branching strategies, and intentionally simulating/resolving code merge conflicts.

---

### 🌐 Day 02: Deconstructing DevOps Culture & Cloud Sandbox Setup
* **Date:** June 2026
* **Instructor/Resources:** Abhishek Veeramalla, TrainWithShubham & KodeKloud

#### 1️⃣ What I Learned (The DevOps Culture Shift)
DevOps is completely misunderstood when viewed as just an accumulated toolstack (like Docker + Jenkins). Following insights from **Abhishek Veeramalla**, I learned that **DevOps is fundamentally a cultural shift**. It is designed to dismantle the historical, friction-heavy *"Wall of Confusion"* that separates application development teams (who favor velocity and rapid feature shipping) from operational infrastructure teams (who prioritize continuous system uptime and strict stability). It's a continuous, automated feedback loop shortening the system development lifecycle.

#### 2️⃣ AWS Sandbox Infrastructure Provisioning
To align with the **TrainWithShubham** structural roadmap, I initialized my dedicated cloud deployment environment:
* Provisioned an **AWS (Amazon Web Services) Account** utilizing active free tier credit layers.
* Configured foundational identity access management wrappers (**IAM roles and groups**) to handle strict principle-of-least-privilege permissions.
* Built initial network security filters via customized **Inbound and Outbound Security Group Rules** to explicitly constrain open ports.

#### 3️⃣ Hands-on Sandbox Exercises
* Logged into **KodeKloud** environments to map abstract theoretical operations against active terminal configurations, preparing to anchor multi-tier cloud infrastructure topologies.

---

### 🐧 Day 03 (Part 1/2): Stepping Out of the Comfort Zone — Navigating Linux
* **Date:** June 2026
* **Instructor/Resources:** *Linux One Shot* by TrainWithShubham & KodeKloud Labs

#### 1️⃣ Shifting the Workspace OS
Today required breaking past my technical comfort boundaries. I formally executed a complete operational workspace transition, moving from **Windows over to Linux** to interact natively with cloud enterprise host systems.

#### 2️⃣ Core Concept: Active Friction over Passive Consumption
Watching tutorials creates an illusion of competence. Tech skills require aggressive muscle memory. 
> 💡 *The Bicycle Analogy:* Watching an expert ride a bicycle flawlessly will never teach you how to maintain your own balance. You can meticulously memorize the underlying physics of a pedal stroke, but until you physically grasp the handlebars, lean into the turns, and manage the wobbles yourself, you cannot ride. The Linux terminal operates exactly the same way—you have to drive it yourself to truly understand it.

#### 3️⃣ Lab Accomplishments
* **Source Training:** TrainWithShubham's deep-dive Linux tracking overview.
* **Practical Validation:** Immersed directly inside **KodeKloud Linux Labs**. Handled raw navigation primitives, complex nested file system trees, explicit numerical/symbolic file permissions mapping (`chmod`/`chown`), and process tracing.

---

### 🤖 Day 03 (Part 2/2): Launching Cloud Assets & Enterprise Automation Architecture
* **Date:** June 2026
* **Instructor/Resources:** Official Ansible Documentation & AWS Hands-on

#### 1️⃣ Launching My First EC2 Node
Transitioned directly into provisioning live cloud infrastructure:
* Initialized and launched a live **Amazon EC2 Instance** compute node.
* Locked down network topology endpoints utilizing the specific security rules configured during Day 2.
* Established an external cryptographic link to securely **SSH directly into the live remote cloud terminal**.

#### 2️⃣ The Scale Paradox: The Need for Configuration Management
Logging into a single EC2 server over SSH to manually run `apt-get update` or deploy a single package is simple. However, if an infrastructure scale grows to **1,000 parallel production servers**, manual node configurations become completely impossible, error-prone, and inefficient. 
As DevOps engineers, our primary imperative is to automate away repetitive toil. To solve this scaling paradox, I began mapping out **Ansible**—an agentless, powerful Configuration Management framework designed to orchestrate states across multiple remote endpoints simultaneously from a solitary controller node.

#### 3️⃣ Initial Automation Blueprinting
Began dissecting architectural documentation to write custom state definitions:
* **Ansible Inventory Files:** Built a structured inventory tracking matrix to logically categorize and map multiple distinct target remote hosts.
* **Ansible Playbooks:** Began drafting descriptive, idempotent **YAML-based blueprints** to automate programmatic changes uniformly across all targets without manually logging into them individually.

---

## 🎯 High-Level Journey Goals
* [x] Master Git workflows & conflict resolution mechanics.
* [x] Set up standard AWS administrative sandboxes.
* [x] Migrate to native Linux terminal infrastructure management.
* [ ] Master Configuration Management workflows via Ansible.
* [ ] Implement secure containerized services via Docker & Kubernetes.
* [ ] Architect resilient, parameter-driven CI/CD Pipelines.

---
*Connect with me on LinkedIn as I document this path live! Let's build, break, and automate together.* 😉
