# 🌐 Day 02: Understanding What DevOps Really Means & Setting Up AWS

## 📌 Overview

Day 2 turned out to be a lot different from what I expected.

When I first started looking into DevOps, I honestly thought it was all about learning a bunch of tools like Docker, Kubernetes, Jenkins, Terraform, and calling yourself a DevOps Engineer. Today made me realize that those tools are just a small piece of the puzzle.

The biggest takeaway from today was understanding that **DevOps is more about culture, collaboration, and automation than it is about any specific tool.**

Alongside learning these concepts, I also took my first real step into cloud computing by setting up my AWS account and creating a playground where I'll be performing all my future DevOps experiments.

---

## 🧠 What I Learned Today

### 🤝 DevOps Is More Than Just Tools

One thing that really clicked for me today was that DevOps isn't a software or a technology stack.

It's a way of working.

Traditionally, developers focus on building and shipping features as quickly as possible, while operations teams focus on keeping systems stable and secure. These goals often clash with each other.

DevOps tries to bridge that gap by encouraging collaboration, automation, and shared responsibility.

For the first time, I started understanding *why* DevOps exists instead of just learning *what* tools are used in DevOps.

---

### ☁️ The Importance of Cloud Platforms

As I explored more about modern infrastructure, I realized that most applications today don't run on someone's personal computer or a physical server sitting in an office.

Everything runs in the cloud.

Whether it's a startup or a large enterprise, cloud platforms have become the backbone of modern applications.

Since AWS is the most widely used cloud provider, I decided to start my cloud journey there.

---

### 🔐 Learning About IAM and Security

Security was another area where I learned some valuable lessons.

At first, I thought creating an AWS account was enough to get started.

But I quickly learned why experienced engineers never use the root account for day-to-day work.

If root credentials are compromised, an attacker could potentially gain full control over the entire cloud environment.

To avoid that, I learned about:

* IAM (Identity and Access Management)
* Users
* Groups
* Roles
* Principle of Least Privilege (PoLP)

Understanding these concepts made me realize how important security is, even when you're just getting started.

---

### 🛡️ Security Groups

I also learned about Security Groups and how they act as virtual firewalls for AWS resources.

The idea seemed simple at first, but it was interesting to see how traffic can be controlled by allowing or denying access to specific ports.

For example:

* Port 22 → SSH Access
* Port 80 → HTTP
* Port 443 → HTTPS

This gave me a basic understanding of how cloud resources stay protected from unwanted traffic.

---

## 🚀 Learning Resources

To keep my learning structured, I followed:

* **Abhishek Veeramalla's DevOps Roadmap**
* **TrainWithShubham's AWS Setup Videos**

Both resources helped me understand not just the technical steps but also the reasoning behind them.

---

## 💻 Hands-On Practice

### AWS Account Setup

Today I successfully:

* Created my AWS account.
* Activated the AWS Free Tier.
* Explored the AWS Management Console.
* Familiarized myself with different AWS services.

This felt like a major milestone because it marks the beginning of my hands-on cloud journey.

---

### IAM Configuration

To follow security best practices, I:

* Created a separate IAM user.
* Assigned permissions through IAM policies.
* Kept the root account secured.
* Enabled additional security measures.

This was my first experience managing identities and permissions in a cloud environment.

---

### Security Group Configuration

I spent some time understanding how inbound and outbound rules work.

I configured security group rules and learned how network access is controlled for cloud resources.

Although it was a basic setup, it gave me a much better understanding of cloud networking fundamentals.

---

### KodeKloud Practice

I wrapped up the day by spending time in KodeKloud Labs.

The labs helped reinforce the concepts I learned throughout the day and gave me a safe environment to experiment without worrying about breaking anything important.

---

## 🎯 Day 02 Reflection

If Day 1 taught me that Git is more than just a backup tool, Day 2 taught me that DevOps is more than just a collection of tools.

Today helped me understand the bigger picture.

Before today, I was focused on learning Docker, Kubernetes, Jenkins, and Terraform as quickly as possible.

Now I understand that these tools exist to support a much larger goal: **building reliable systems, improving collaboration, and automating repetitive work.**

Setting up AWS today felt like laying the foundation for everything I'll build during this journey.

Excited to dive deeper into Linux, cloud infrastructure, automation, and CI/CD in the coming days. 🚀

---

## 📚 Topics Covered Today

* DevOps Fundamentals
* DevOps Culture
* AWS Cloud Basics
* IAM (Identity & Access Management)
* Principle of Least Privilege (PoLP)
* Security Groups
* Basic Cloud Networking
* AWS Free Tier Setup
* KodeKloud Labs
