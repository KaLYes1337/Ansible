# 📘 Ansible Playbooks Repository

In this repository, I will be adding my Ansible playbooks along with a brief explanation of what each one does. These playbooks help automate common system administration tasks on Linux systems.

---

## 📜 Playbook: set_up_playbook.yaml`

This playbook performs the following tasks on the local machine:

### 🔧 Tasks Overview

1. **Update APT cache**
   - Refreshes the package index to ensure latest package info.

2. **Install essential packages**
   - Installs `htop`, `curl`, and `python3` as an example.

3. **Set hostname**
   - Changes the system hostname.

4. **Create a user group**
   - Creates a group.

5. **Create multiple users**
   - Adds users:
     - Assigns them to group
     - Sets `/bin/bash` as their shell
     - Ensures each user has a home directory

---
