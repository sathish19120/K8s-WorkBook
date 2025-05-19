# K8s-WorkBook

Week 1-2 : Linux Fundamentals
   -- Basic of Linux
   -- File system and Directory 
Structure :
   -- File and directory Permissions
   -- Basic Commands (ls,cd,mv,rm,cp,dir,etc)
   -- Users,groups,permissions(chmod,chown)
Permissions:
   -- environment variables and shell scripting 
Shell Script :
   -- APT
  -- YUM / DNF ( RHEL-based)
Process Management :
   -- ps, top,htop,kill,jobs,bg,fg
Networking basics:
  -- IP, TCP/UDP,DNS,HTTPs
  --Ping,netstat,Telnet,Traceroute 
Week 3-4  : Version Control (Git & Github)
   -- Installation & setup
   -- Git workflow (Clone,add ,commit, push, pull, merge)
   -- Branching & Merging Strategies
   -- Resolving merge Conflicts
   -- Git tags and releases 
   -- Pull requests and code reviews
   -- Github Actions (Intro to CI/CD)
   -- Managing repositories
Week 5-6: Scripting & Automation
  -- Variables loops, Conditions 
  -- Functions and error Handaling
  -- Cron jobs and scheduling tasks
  -- working with files and directories
  -- APIs and web scraping
  -- Process automation 
Week 7-8 : Containers & Dockers
  -- Installation & setup
  -- Docker CLI commands
  -- writing Dockerfiles
  -- Docker Compose 
  -- Kubernetes Basics 
  -- Deployment, pods, Services

week 9-10 : Infrastructure as Code IAC
  -- Benifits of IAC
  -- Declarative vs Imperative
  -- Installing and setting up Terraform
  -- Writing Terraform Configuration 
  -- Managing infrastructure 
week 11-12: CI/CD
  -- Principles and benifts
  -- Installation & setup
  -- creating and managing pipelines 
  -- Integrating with github
  -- Github Actions & Gitlab CI/Cd
  -- Writing CI/Cd workflows
  -- Automating deployments
week 13-14 : Monitoring & logging
  -- Promotheus & grafana
  --new Relic, Datadog, AWS cloudwatch logging & Log Management 
  -- ELK Stack (elastch search , Logstash, kibana)
  -- Fluentd
week 15-16: Cloud & Security Best Practises AWS , GCP, Azure
 -- IAM & Security best practices 
 -- Compute , storage, Networking Services 
 -- SSH best Practices 
 -- Secrets management (Vault, AWS secrets manager)
 -- Container Security 
 -- Compliance & Policy as Code
week 17-18:
 -- Advanced Topics & real worldProject
 -- Advanced Kubernetes (Helm,Operater)
 -- Service mesh (Istio,Linkerd)
 --Serverless & edge Computing
 --Building a real-world Devops pipeline
week 19-20: Final project & Certification
  -- Implement CI/CD
  -- Automate infrastructure 
  -- Monitor & Secure
  -- Certification Preparation 



linux fundamental:
Linux is an open-source operating system.

It's like Windows or macOS but free and customizable.

Used widely in servers, development environments, and even Android.
A file system is a method and data structure that the operating system uses to control how data is stored and retrieved.

In Linux, popular file systems are:

ext4 (most common for Linux)

XFS

Btrfs

VFAT (for USB drives)

NTFS (Windows drives, supported in Linux)

The file system organizes files into a hierarchical tree structure of directories (folders)
Linux Directory Structure (The Tree)
In Linux, everything starts from the root directory, which is represented by /.
/
├── bin/        → Essential user binaries (commands like ls, cp)
├── boot/       → Boot loader files (kernel, initrd)
├── dev/        → Device files (hard drives, USB, etc.)
├── etc/        → Configuration files
├── home/       → User home directories (/home/username)
├── lib/        → Essential libraries for binaries
├── media/      → Mount point for removable media
├── mnt/        → Temporary mount point
├── opt/        → Optional add-on software
├── proc/       → Virtual filesystem for system information
├── root/       → Home directory of the root user
├── run/        → Runtime data
├── sbin/       → System binaries (for admin commands)
├── tmp/        → Temporary files
├── usr/        → User programs, utilities, libraries
└── var/        → Variable data (logs, spool files)

Directories
