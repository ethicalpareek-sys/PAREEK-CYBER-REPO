# 🛡️ Cybersecurity A-Z — Beginner to Advanced / CISO Roadmap

> A complete, structured, ethical cybersecurity education — from absolute zero to CISO-level knowledge.

---

## ⚠️ LEGAL & ETHICAL NOTICE — Read First

This repository is **strictly for**: education, ethical hacking, authorized penetration testing, CTFs, isolated labs, defensive security, and security research.

**NEVER** use any technique here against systems you do not own or do not have explicit written authorization to test.

Unauthorized access to computer systems is **illegal** in virtually every jurisdiction:
- India: IT Act 2000 (Sections 43, 66, 66C, 66F)
- USA: Computer Fraud and Abuse Act (CFAA)
- UK: Computer Misuse Act 1990
- EU: NIS2 Directive, GDPR

**All offensive labs must use:**
- localhost / 127.0.0.1
- Intentionally vulnerable apps (DVWA, Juice Shop, Metasploitable)
- CTF platforms (TryHackMe, HTB, PortSwigger Academy)
- Private VMs you own
- Authorized bug bounty scope only

---

## 📖 Table of Contents

1. What Is This
2. Learning Philosophy
3. Start Here (3 / 6 / 12 / 18 / 24 Month Roadmaps)
4. Career Learning Paths
5. Full Curriculum
6. Phase 0 — Computer Fundamentals
7. Phase 1 — Linux
8. Phase 2 — Windows
9. Phase 3 — Networking (Deep Dive)
10. Phase 4 — Python for Security
11. Web Security
12. Red Team
13. Blue Team
14. Digital Forensics
15. Malware Analysis
16. Cloud Security
17. DevSecOps
18. AI / LLM Security
19. GRC / CISO
20. Tools Encyclopedia
21. Labs
22. Projects
23. CTF Platforms
24. Certifications
25. Career Roadmaps
26. Free Resources
27. Termux Mobile Workflow
28. Validation & QA
29. Contributing
30. FAQ
31. Glossary

---

## 1. What Is This

A single-file, complete cybersecurity curriculum covering **68+ topic areas**, from absolute beginner to CISO-level. This is NOT a "hack in 24 hours" guide. It is a structured multi-year learning system designed to be read, practiced, and iterated.

**Who this is for:**
- Complete beginners with zero IT background
- IT professionals pivoting into security
- Students preparing for certifications
- Security engineers expanding skills
- Aspiring CISOs and security leaders

**What you get:**
- Structured learning paths (3 / 6 / 12 / 18 / 24 month)
- Hands-on labs (100% legal)
- Tool documentation and safe usage
- Career roadmaps for 18 roles
- Certification guidance
- Curated free and paid resource directory

---

## 2. Learning Philosophy

1. **Depth over breadth** — Master fundamentals before chasing trends
2. **Hands-on first** — Every concept has a lab; do not just read
3. **Defense AND offense** — Understand both to be effective
4. **Ethics always** — Authorization is non-negotiable
5. **Document everything** — If you cannot explain it, you do not know it
6. **Build in public** — Portfolio > certificates
7. **Never stop learning** — Security changes weekly

**Mastery tracking per topic:**

    [ ] Not Started
    [ ] Learning
    [ ] Practiced
    [ ] Built
    [ ] Tested
    [ ] Can Explain
    [ ] Can Troubleshoot
    [ ] Advanced

---

## 3. Start Here — Roadmaps

### 3-Month Roadmap (Foundation)

    Month 1: Computer Fundamentals + Linux Basics + Networking Basics
             Deliverable: Linux VM running, can navigate CLI confidently
    Month 2: Python Basics + Web Fundamentals + Cryptography Intro
             Deliverable: 3 working Python scripts, OWASP Top 10 read
    Month 3: TryHackMe Pre-Security Path + Security+ prep
             Deliverable: Complete THM path + practice exam score >80%

### 6-Month Roadmap (Intermediate)

    Months 1-3: Foundation (above)
    Month 4:    Web Security Deep Dive (PortSwigger Academy)
    Month 5:    Blue Team / SOC Basics + SIEM Lab
    Month 6:    Red Team Basics + First CTF competition

### 12-Month Roadmap (Job-Ready)

    Months 1-6:  Above
    Months 7-8:  Cloud Security (AWS/Azure fundamentals)
    Months 9-10: DevSecOps + Container Security
    Month 11:    AI Security + Threat Intelligence
    Month 12:    Portfolio project + job applications

### 18-Month Roadmap (Specialist)

    Choose ONE specialization:
      - Red Team (OSCP path)
      - Blue Team / DFIR (BTL1, GCFA path)
      - Cloud Security (CCSP, AWS Security Specialty)
      - AppSec (OSWE, Burp Suite Certified)
      - GRC / CISO track
    Complete advanced cert + real-world labs + contribute to open source

### 24-Month Roadmap (Senior / CISO Track)

    Leadership skills, GRC, risk, budgeting
    CISO-level knowledge (board comms, strategy)
    Enterprise security architecture
    Mentoring + community contributions
    Executive MBA / CISM / CISSP

**⚠️ Reality Check:** Reading alone does NOT make you an expert. You need: labs, projects, troubleshooting, documentation, and real-world practice.

---

## 4. Career Learning Paths

| Path | Start With | Goal |
|---|---|---|
| SOC Analyst | Blue Team → SIEM | Monitor & respond to alerts |
| Security Analyst | Fundamentals → Networking | Generalist defensive |
| Penetration Tester | Red Team → Web Security | Authorized offensive testing |
| Red Teamer | Pen Testing → Exploitation | Adversary simulation |
| Blue Teamer | SOC → Detection Engineering | Defense engineering |
| Detection Engineer | SIEM → Sigma → YARA | Write detection rules |
| Threat Hunter | Blue Team → MITRE ATT&CK | Proactive hunting |
| Incident Responder | Blue Team → DFIR | Handle breaches |
| Digital Forensics Analyst | DFIR → Disk/Memory forensics | Investigate evidence |
| Malware Analyst | RE → Static/Dynamic analysis | Reverse engineer malware |
| Security Engineer | Linux → Networking → Cloud | Build security systems |
| Cloud Security Engineer | AWS/Azure → Kubernetes | Secure cloud infra |
| Application Security Engineer | Web Sec → Secure Coding | Secure SDLC |
| DevSecOps Engineer | CI/CD → IaC → SAST/DAST | Secure pipelines |
| Security Architect | All technical + GRC | Design systems |
| Threat Intelligence Analyst | OSINT → MITRE → Frameworks | Track adversaries |
| GRC Analyst | Frameworks → Risk → Audit | Governance & compliance |
| CISO | All + Leadership + Strategy | Executive leadership |

---

## 5. Full Curriculum Overview

    PHASE 0  — Computer Fundamentals
    PHASE 1  — Linux
    PHASE 2  — Windows
    PHASE 3  — Networking (Deep Dive)
    PHASE 4  — Python for Security
    PHASE 5  — Bash / Shell Scripting
    PHASE 6  — Git & GitHub
    PHASE 7  — Web Fundamentals
    PHASE 8  — Databases
    PHASE 9  — Cryptography
    PHASE 10 — Identity & Access Management
    PHASE 11 — Authentication & Authorization
    PHASE 12 — Security Fundamentals
    PHASE 13 — Security Operations
    PHASE 14 — SOC
    PHASE 15 — SIEM
    PHASE 16 — Threat Intelligence
    PHASE 17 — Incident Response
    PHASE 18 — Digital Forensics
    PHASE 19 — Malware Analysis
    PHASE 20 — Reverse Engineering
    PHASE 21 — Red Team
    PHASE 22 — Penetration Testing
    PHASE 23 — Web Security
    PHASE 24 — API Security
    PHASE 25 — Network Security
    PHASE 26 — Wireless Security
    PHASE 27 — Active Directory
    PHASE 28 — Exploitation Concepts
    PHASE 29 — Privilege Escalation Concepts
    PHASE 30 — Post-Exploitation Concepts
    PHASE 31 — OSINT
    PHASE 32 — Blue Team
    PHASE 33 — Defensive Engineering
    PHASE 34 — Detection Engineering
    PHASE 35 — Threat Hunting
    PHASE 36 — EDR / XDR
    PHASE 37 — Cloud
    PHASE 38 — AWS Security
    PHASE 39 — Azure Security
    PHASE 40 — GCP Security
    PHASE 41 — Kubernetes Security
    PHASE 42 — Container Security
    PHASE 43 — DevSecOps
    PHASE 44 — Application Security
    PHASE 45 — Secure Coding
    PHASE 46 — Supply Chain Security
    PHASE 47 — Mobile Security
    PHASE 48 — IoT Security
    PHASE 49 — Hardware Security
    PHASE 50 — Reverse Engineering
    PHASE 51 — AI Security
    PHASE 52 — LLM Security
    PHASE 53 — MLSec
    PHASE 54 — GRC
    PHASE 55 — Risk Management
    PHASE 56 — Compliance
    PHASE 57 — Security Governance
    PHASE 58 — Security Architecture
    PHASE 59 — CISO
    PHASE 60 — CTF
    PHASE 61 — Labs
    PHASE 62 — Projects
    PHASE 63 — Tools
    PHASE 64 — Cheatsheets
    PHASE 65 — Career
    PHASE 66 — Certifications
    PHASE 67 — Reference

---

## 6. Phase 0 — Computer Fundamentals

**Why it matters:** You cannot secure what you do not understand.

### Core Concepts

**CPU (Central Processing Unit)**
- Executes instructions, has registers, cache (L1/L2/L3), cores
- Security: Spectre, Meltdown, Rowhammer, side-channel attacks

**RAM (Random Access Memory)**
- Volatile memory, holds running programs and data
- Security: Memory forensics (Volatility), buffer overflows, use-after-free

**Storage**
- HDD (magnetic), SSD (flash), NVMe (PCIe SSD)
- Security: Disk forensics, secure deletion, TRIM, wear leveling

**Motherboard & Buses**
- PCIe, USB, SATA, M.2
- Security: DMA attacks (Thunderbolt), hardware implants

**BIOS / UEFI**
- Firmware that initializes hardware before OS
- Security: Bootkits, firmware rootkits, Secure Boot bypass

**Boot Process**
- Power → UEFI/BIOS → Bootloader (GRUB) → Kernel → Init (systemd) → Services
- Security: Rootkits persist in MBR/bootloader

**Processes & Threads**
- Process = running program with own memory space
- Thread = lightweight process within a process
- Security: Process injection, DLL hijacking, thread hijacking

**Files & Filesystems**
- NTFS (Windows), ext4 (Linux), APFS (macOS), FAT32, exFAT
- Security: Metadata forensics, hidden partitions, ADS in NTFS

**Permissions**
- DAC (Discretionary Access Control) — owner decides
- MAC (Mandatory Access Control) — SELinux, AppArmor
- RBAC (Role-Based Access Control) — role decides
- Security: Privilege escalation via misconfigured permissions

**Users & Groups**
- Identity foundation, IAM starts here
- Security: Credential theft, privilege escalation, lateral movement

**Environment Variables**
- Config variables (PATH, HOME, USER)
- Security: Often leak secrets, PATH hijacking

**Virtual Memory**
- Paging and swapping
- Security: Pagefile forensics, swap file analysis

**Kernel**
- Core OS, bridges hardware and software
- Security: Kernel exploits = root, kernel modules = rootkits

**Drivers**
- Kernel modules for hardware
- Security: BYOVD (Bring Your Own Vulnerable Driver) attacks

**System Calls**
- API between user space and kernel
- Security: Syscall filtering (seccomp), hooking

**Services / Daemons**
- Background processes
- Security: Often misconfigured, running as SYSTEM/root

**Client / Server**
- Architecture pattern
- Security: Understanding protocols, MITM

**Virtualization**
- Type 1 (bare metal): ESXi, Hyper-V, Xen
- Type 2 (hosted): VirtualBox, VMware Workstation
- Security: VM escape, hyperjacking

**Containers**
- Namespaces + cgroups
- Security: Container escape, privilege escalation, insecure images

**Network Interfaces**
- Physical (eth0, wlan0) and virtual (lo, docker0, veth)
- Security: Traffic capture, network forensics

### Lab

    # On any Linux system, run these to see your system
    lscpu                    # CPU info
    free -h                  # RAM usage
    lsblk                    # Block devices
    ps aux                   # All processes
    ls -la /                 # Root directory
    systemctl list-units --type=service
    cat /proc/cpuinfo | head -20
    uname -a                 # Kernel version

---

## 7. Phase 1 — Linux

**Why it matters:** Linux powers 90%+ of servers, cloud infrastructure, and security tooling.

### Architecture

- Kernel (monolithic Linux kernel)
- User space (applications, libraries)
- Init system (systemd, SysV init)
- Shell (bash, zsh, sh)

### Distributions

    Debian / Ubuntu    — Beginner-friendly, apt package manager
    RHEL / CentOS      — Enterprise, dnf/yum
    Fedora             — Cutting edge, Red Hat sponsored
    Arch / Manjaro     — Advanced, rolling release
    Kali / Parrot      — Pentesting focused
    Alpine             — Containers, tiny (~5 MB)

### Filesystem Hierarchy

    /           Root of everything
    /bin        Essential binaries (ls, cp, mv)
    /boot       Bootloader, kernel, initrd
    /dev        Device files (/dev/sda, /dev/null)
    /etc        Configuration files
    /home       User home directories
    /lib        Shared libraries
    /media      Mount points for removable media
    /mnt        Temporary mount points
    /opt        Optional / third-party software
    /proc       Process and kernel info (virtual)
    /root       Root user's home
    /sbin       System binaries (fdisk, mkfs)
    /srv        Service data
    /sys        Kernel and hardware info (virtual)
    /tmp        Temporary files (cleared on reboot)
    /usr        User system resources
    /var        Variable data (logs, spool, cache)

### Users & Groups

    whoami                  # Show current user
    id                      # UID, GID, groups
    sudo useradd -m bob     # Create user bob with home
    sudo passwd bob         # Set password
    sudo usermod -aG sudo bob
    cat /etc/passwd         # User list
    cat /etc/shadow         # Password hashes (root only)
    cat /etc/group          # Group list

### Permissions

    ls -la                  # Show permissions
    chmod 755 file          # rwxr-xr-x
    chmod u+x file          # Add execute for owner
    chmod -R 750 dir        # Recursive
    chown user:group file   # Change owner and group
    chgrp group file        # Change group
    umask                   # Default permission mask

**Permission format:** `-rwxr-xr-x`
- Position 1: Type (`-` file, `d` dir, `l` symlink, `c` char device, `b` block device)
- Position 2-4: Owner (rwx)
- Position 5-7: Group (r-x)
- Position 8-10: Others (r-x)

**Numeric values:** r=4, w=2, x=1
- `755` = rwxr-xr-x
- `644` = rw-r--r--
- `600` = rw-------

**Special bits:**
- SUID (4xxx) — Run as file owner: `chmod 4755 file`
- SGID (2xxx) — Run as file group: `chmod 2755 file`
- Sticky (1xxx) — Only owner deletes: `chmod 1755 dir`

Find SUID binaries (privilege escalation check):

    find / -perm -4000 -type f 2>/dev/null

### Processes

    ps aux                  # All processes (BSD format)
    ps -ef                  # All processes (System V format)
    top                     # Live process monitor
    htop                    # Better top
    kill -9 PID             # Force kill (SIGKILL)
    kill -15 PID            # Graceful kill (SIGTERM)
    killall nginx           # Kill all by name
    pstree                  # Process tree
    pgrep -u bob            # Find processes by user
    lsof -p PID             # Files opened by process
    lsof -i :80             # Processes on port 80
    strace -p PID           # Trace system calls
    ltrace -p PID           # Trace library calls

**Signals:**
- SIGTERM (15) — Graceful shutdown
- SIGKILL (9) — Force kill (cannot be caught)
- SIGHUP (1) — Reload config
- SIGINT (2) — Ctrl+C
- SIGSTOP (19) — Pause
- SIGCONT (18) — Resume

### systemd

    systemctl status sshd
    systemctl start sshd
    systemctl stop sshd
    systemctl restart sshd
    systemctl enable sshd          # Start on boot
    systemctl disable sshd
    systemctl list-units --type=service
    systemctl daemon-reload
    journalctl -u sshd -n 50       # Last 50 lines
    journalctl --since "1 hour ago"
    journalctl -p err              # Only errors
    journalctl -f                  # Follow (like tail -f)

### Logs

    /var/log/syslog       — System messages (Debian)
    /var/log/messages     — System messages (RHEL)
    /var/log/auth.log     — Authentication
    /var/log/kern.log     — Kernel
    /var/log/apache2/     — Web server
    /var/log/nginx/       — Nginx
    /var/log/cron          — Cron jobs
    journalctl            — systemd journal

### Package Management

Debian / Ubuntu:

    sudo apt update
    sudo apt upgrade
    sudo apt install nmap
    apt search nmap
    apt show nmap
    sudo apt remove nmap
    dpkg -l | grep nmap

RHEL / CentOS / Fedora:

    sudo dnf install nmap
    sudo dnf upgrade
    rpm -qa | grep nmap

Arch:

    sudo pacman -S nmap
    sudo pacman -Syu

### Text Processing

    grep "error" file.log               # Search
    grep -r "password" /etc/            # Recursive
    grep -v "debug" file.log            # Exclude
    grep -i "error" file.log            # Case-insensitive
    grep -c "error" file.log            # Count matches
    sed 's/old/new/g' file              # Replace all
    sed -i 's/old/new/g' file           # In-place
    awk '{print $1, $3}' file           # Print columns
    awk -F: '{print $1}' /etc/passwd    # Custom delimiter
    cut -d: -f1 /etc/passwd             # Field 1
    sort file | uniq -c                 # Count unique
    sort -u file                        # Unique sorted
    find / -name "*.conf" 2>/dev/null   # Find files
    find / -mtime -1                    # Modified in last day
    find / -size +100M                  # Larger than 100MB
    xargs -I {} command {}              # Build commands

### Pipes & Redirection

    cmd1 | cmd2             # Pipe stdout of cmd1 to cmd2
    cmd > file              # Redirect stdout (overwrite)
    cmd >> file             # Append stdout
    cmd 2> err              # Redirect stderr
    cmd &> all              # Both stdout and stderr
    cmd < input             # Stdin from file
    cmd 2>&1 | tee log      # Both to screen and file

### Networking Commands

    ip addr                         # IP addresses
    ip route                        # Routing table
    ip link                         # Interfaces
    ip neigh                        # ARP table
    ss -tuln                        # Listening TCP/UDP sockets
    ss -tunap                       # All connections with process
    netstat -tuln                   # Legacy (net-tools)
    ping -c 4 8.8.8.8
    traceroute 8.8.8.8              # Linux
    tracepath 8.8.8.8
    dig example.com
    dig +short example.com
    dig MX example.com
    nslookup example.com
    host example.com
    curl -I https://example.com     # HTTP headers
    curl -v https://example.com     # Verbose
    wget https://example.com/file
    tcpdump -i eth0 -w capture.pcap
    tcpdump -i eth0 port 80
    tcpdump -r capture.pcap

### SSH

    ssh user@host
    ssh -p 2222 user@host           # Custom port
    ssh -i ~/.ssh/key.pem user@host # Identity file
    ssh-keygen -t ed25519 -C "me@example.com"
    ssh-copy-id user@host           # Copy public key
    ssh -L 8080:localhost:80 user@host    # Local port forward
    ssh -R 8080:localhost:80 user@host    # Remote port forward
    ssh -D 1080 user@host                 # SOCKS proxy

### File Transfer

    scp file user@host:/path
    scp user@host:/path/file .
    scp -r folder user@host:/path
    rsync -avz source/ user@host:/dest/
    rsync -avz --delete source/ dest/
    sftp user@host

### Cron

    crontab -e              # Edit user's crontab
    crontab -l              # List
    crontab -r              # Remove

Format: `minute hour day month weekday command`

    0 2 * * *        /backup.sh        # Every day 2 AM
    */5 * * * *      /check.sh         # Every 5 minutes
    0 0 * * 0        /weekly.sh        # Every Sunday midnight
    @reboot          /startup.sh       # On boot

### Hardening Checklist

    [ ] Disable root SSH login (PermitRootLogin no)
    [ ] Use SSH keys, disable password auth (PasswordAuthentication no)
    [ ] Enable UFW/iptables firewall
    [ ] Install fail2ban
    [ ] Regular updates (unattended-upgrades)
    [ ] Audit SUID binaries
    [ ] Restrict sudo (visudo)
    [ ] Enable auditd
    [ ] Monitor logs (journalctl, /var/log/)
    [ ] Disable unused services
    [ ] Set password policies (PAM)
    [ ] Enable SELinux/AppArmor
    [ ] Encrypt disk (LUKS)
    [ ] Set up log rotation (logrotate)
    [ ] Remove unnecessary packages
    [ ] Set up SSH on non-standard port (mild hardening)

### Common Mistakes

- Running everything as root
- World-writable files (`chmod 777`)
- Weak SSH configuration
- No firewall
- 
