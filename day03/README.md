# 🐧 Day 03: Getting Comfortable with Linux & Taking My First Steps into Ansible

## 📌 Overview

Day 3 was probably the most hands-on day of my journey so far.

For a long time, I had been using Windows for almost everything. Linux always felt like something that only experienced developers and system administrators used. Today, I decided to stop treating Linux as a side tool and start using it as my primary environment for learning DevOps.

The first half of my day was spent understanding how Linux works and getting comfortable with the command line. The second half was all about taking those Linux fundamentals into the cloud by connecting to an AWS EC2 instance and exploring how Ansible can automate server management.

By the end of the day, I wasn't just logging into servers anymore—I was starting to understand how engineers manage hundreds or even thousands of them.

---

## 🧠 What I Learned Today

### 🚲 Learning by Doing Beats Watching Tutorials

One thing became very clear today:

> Watching tutorials alone doesn't make you skilled.

I kept thinking about the analogy of learning to ride a bicycle.

You can watch hours of videos explaining balance, steering, and pedaling, but until you actually sit on the bicycle and fall a few times, you don't truly learn how to ride.

Linux felt exactly the same.

Reading commands and watching demonstrations helped me understand the concepts, but the real learning happened when I opened the terminal and started typing commands myself.

Some commands worked. Some didn't. Some broke things.

And that's where the actual learning happened.

---

### 🐧 Becoming Comfortable with Linux

Most DevOps tools and cloud servers run on Linux, so building a strong foundation here is essential.

Today I spent time learning:

* Linux filesystem structure
* Creating and managing directories
* Navigating between folders
* Managing files
* Understanding users and groups
* File permissions and ownership

I also practiced commands like:

```bash
pwd
ls
cd
mkdir
rm
cp
mv
chmod
chown
```

At first, everything felt unfamiliar, but after a few hours in the terminal, I started feeling much more comfortable moving around the system.

---

### ☁️ Connecting to My First Cloud Server

One of the most exciting parts of the day was launching an EC2 instance on AWS and connecting to it using SSH.

After setting up Security Groups on Day 2, I was finally able to log into a live cloud server directly from my terminal.

Seeing the terminal prompt change from my local machine to a remote AWS server felt like a small but important milestone.

For the first time, I wasn't just learning cloud concepts—I was interacting with real cloud infrastructure.

---

### 🤖 Why Configuration Management Matters

After successfully SSH-ing into my EC2 instance, a question came to mind:

What happens when a company has hundreds or thousands of servers?

Logging into each machine manually to:

* Install software
* Update packages
* Modify configurations
* Restart services

would be incredibly inefficient.

That's when the purpose of configuration management tools started making sense.

Instead of manually managing servers one by one, engineers use automation tools to perform the same task across multiple machines simultaneously.

And that's exactly where Ansible comes in.

---

### ⚡ Introduction to Ansible

Today I learned that Ansible is an automation tool that allows you to manage multiple servers from a single control machine.

What impressed me most is that Ansible is agentless.

Unlike some other tools, you don't need to install special software on every target server. As long as SSH access exists, Ansible can communicate with and manage the machines.

The idea of controlling multiple servers using a simple YAML file felt incredibly powerful.

---

## 🚀 Learning Resources

To keep my learning structured, I used:

* **TrainWithShubham's Linux One Shot Session**
* **Official Ansible Documentation**
* **KodeKloud Linux & Ansible Labs**

These resources helped me combine theory with practical exercises.

---

## 💻 Hands-On Practice

### Linux Practice

I spent a significant amount of time inside KodeKloud Linux Labs working on:

* Directory navigation
* File operations
* User management
* Permission management
* Command-line workflows

The more I practiced, the more natural the terminal started to feel.

---

### AWS EC2 Setup

Today I successfully:

* Launched an EC2 instance.
* Connected it to my Security Group configuration.
* Generated and used SSH keys.
* Connected to the server through SSH.

This was my first experience managing a live cloud machine from the command line.

---

### My First Ansible Inventory

I created my first Ansible inventory file.

This helped me understand how Ansible keeps track of target machines and organizes them into groups.

Although it was a simple setup, it gave me a clear picture of how larger infrastructures are managed.

---

### Writing My First Playbooks

I also started learning the structure of Ansible Playbooks.

Using YAML to describe server configurations felt very different from traditional scripting.

Instead of manually performing tasks, I could simply describe the desired state and let Ansible handle the execution.

It genuinely felt like taking the first step toward real infrastructure automation.

---

## 🎯 Day 03 Reflection

Today was the first day where I truly felt like I was moving beyond just learning concepts.

Linux no longer feels as intimidating as it did a few days ago, and connecting to a live AWS server gave me confidence that I'm building practical skills, not just theoretical knowledge.

The biggest lesson from today was simple:

> The terminal becomes less scary every time you use it.

And Ansible showed me something even more important:

> Good engineers don't scale by working harder. They scale by automating repetitive work.

Excited to build more playbooks and automate even more tasks in the coming days. 🚀

---

## 📚 Topics Covered Today

* Linux Fundamentals
* Linux Filesystem Navigation
* File Permissions & Ownership
* SSH Basics
* AWS EC2
* Configuration Management
* Ansible Fundamentals
* Inventory Files
* YAML Basics
* Ansible Playbooks
* Infrastructure Automation
