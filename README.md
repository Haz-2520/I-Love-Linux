# I-Love-Linux

This repository documents my journey learning and practicing Linux on my headless Ubuntu 22.04 homeserver. It's designed to be a comprehensive resource for anyone wanting to master Linux from fundamentals to advanced techniques.

## Linux-Essentials

Core concepts every Linux user needs to understand:

- Linux File System Hierarchy (FHS)
- File permissions and ownership (chmod, chown, umask)
- Hard links vs Soft links (symlinks)
- Systemd and init systems
- Boot process (GRUB, kernel loading, init)
- Process management (foreground, background, daemons)
- User and group management
- Environment variables and PATH
- Standard streams (stdin, stdout, stderr)
- Pipes and redirection
- File descriptors
- Package management (apt, dpkg, snap)
- Runlevels and targets
- Logging system (syslog, journald)
- Cron and scheduled tasks
- Shell basics (bash, sh, environment)

## Linux-History

The journey of Linux from Unix to modern open source:

- Unix origins (Bell Labs, 1970s)
- GNU Project (Richard Stallman, 1983)
- Free Software Foundation (FSF)
- Linux kernel creation (Linus Torvalds, 1991)
- GPL and licensing evolution
- Open Source Initiative (OSI)
- Major distributions timeline (Debian, Red Hat, Ubuntu)
- Unix wars and fragmentation
- POSIX standards
- Commercial Unix vs Linux
- The Cathedral and the Bazaar
- BSD vs Linux differences
- Corporate adoption phases
- Container revolution impact

## Linux-Kernel

Deep dive into the Linux kernel architecture and internals:

- Kernel architecture (monolithic vs microkernel)
- Kernel space vs user space
- System calls interface
- Process scheduler (CFS)
- Memory management (virtual memory, paging, swap)
- Virtual File System (VFS)
- Device drivers and modules
- Interrupt handling
- Kernel compilation and customization
- Namespaces and cgroups
- Netfilter and iptables framework
- Block I/O layer
- Kernel parameters (sysctl)
- Kernel ring buffer (dmesg)
- Security modules (SELinux, AppArmor)

## Linux-Tools

50+ essential commands for daily Linux operations:

**File Operations:**

- ls, pwd, cd, mkdir, rmdir, rm, cp, mv, touch, ln, find, locate, tree, file, stat

**Text Processing:**

- cat, less, more, head, tail, grep, egrep, sed, awk, cut, sort, uniq, wc, diff, tr

**System Information:**

- uname, hostname, uptime, whoami, who, w, id, lsb_release, arch

**Process Management:**

- ps, top, htop, kill, killall, pkill, pgrep, nice, renice, bg, fg, jobs, nohup

**Disk & Filesystem:**

- df, du, mount, umount, fdisk, lsblk, blkid, mkfs, fsck

**Networking:**

- ip, ifconfig, ping, traceroute, netstat, ss, nslookup, dig, curl, wget, scp, rsync, nc, tcpdump

**Archives:**

- tar, gzip, gunzip, zip, unzip, bzip2, xz

**Permissions:**

- chmod, chown, chgrp, umask, getfacl, setfacl

**System Services:**

- systemctl, journalctl, service, dmesg

**Text Editors:**

- vim, nano, ed

**Others:**

- man, which, whereis, alias, history, echo, printf, xargs, tee, watch

## Linux-Tricks

Productivity tools and techniques for efficiency:

**Terminal Multiplexers:**

- tmux (sessions, windows, panes)
- screen

**Enhanced CLI Tools:**

- lsd/exa (better ls)
- bat (better cat)
- ripgrep (rg - better grep)
- fd (better find)
- tldr (simplified man pages)
- fzf (fuzzy finder)
- grc (generic colorizer)
- htop/btop (better top)
- ncdu (disk usage analyzer)
- ranger/nnn (file managers)

**Productivity Techniques:**

- Vim mastery (motions, macros, plugins)
- Bash shortcuts (Ctrl+R, Ctrl+A, Ctrl+E, etc.)
- Command history tricks
- Shell aliases and functions
- Dotfile management
- SSH config optimization
- SSH key management
- Shell scripting patterns
- Regex mastery
- Job control (bg, fg, &, disown)

**Modern Development Tools:**

- git workflows
- jq (JSON processor)
- yq (YAML processor)
- httpie (HTTP client)
- Delta (better diff)
- Starship (shell prompt)
- Zoxide (smarter cd)
- Lazygit (git TUI)

**System Administration:**

- Log analysis techniques
- Performance monitoring
- Automation with cron/systemd timers
- Backup strategies (rsync, tar)
- Security hardening basics
- Firewall management (ufw, iptables)

## 🎯 Learning Goals

This repository aims to provide:

- Comprehensive Linux fundamentals
- Historical context and philosophy
- Deep technical knowledge
- Practical command-line skills
- Modern productivity enhancements
- Real-world system administration techniques

## 🚀 Usage

Each directory contains detailed documentation, examples, and practice exercises for its respective topic. Navigate to any section to begin learning.

## 📝 Contributing

Feel free to suggest improvements, corrections, or additional topics that would benefit Linux learners.

## 📄 License

This project is licensed under the terms specified in the LICENSE file.
