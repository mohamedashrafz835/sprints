# 🐳 Docker Daemon Info - Annotated

## 🔧 Server Section (Docker Daemon)

---

### 📦 Containers
- **Running:** 3 – Currently active containers.
- **Stopped:** 10 – Previously run containers, now stopped.
- **Paused:** 0 – Containers paused using `docker pause`.

---

### 🖼️ Images
- **6** images stored locally on the system.

---

### ⚙️ Server Version
- **28.3.2** – Docker Engine daemon version.

---

### 💾 Storage Driver
- **overlay2** – Layered file system used for managing images/containers.
- **Backing Filesystem:** extfs – Likely ext4.
- **Supports d_type:** true – Required for OverlayFS to work properly.
- **Using metacopy:** false
- **Native Overlay Diff:** true – Improves performance.
- **userxattr:** false – Extended attributes not enabled.

---

### 📜 Logging Driver
- **json-file** – Default logging method; logs are written as JSON per container.

---

### 🧩 Plugins
- **Volume Drivers:** `local`
- **Network Drivers:** `bridge`, `host`, `ipvlan`, `macvlan`, `null`, `overlay`
- **Log Drivers:** `awslogs`, `fluentd`, `gcplogs`, `gelf`, `journald`, `json-file`, `local`, `splunk`, `syslog`

---

### 🔐 Security Options
- **AppArmor:** Enabled – Mandatory access control.
- **Seccomp:** Enabled (Profile: builtin) – Restricts syscalls inside containers.
- **cgroupns:** Enabled – Isolates cgroups namespace.

---

### 🧠 Cgroup Driver
- **Driver:** systemd – Resource control is managed by `systemd`.
- **Cgroup Version:** 2 – Newer control group hierarchy system.

---

### ⚙️ Runtimes
- **Default:** `runc` – Main container runtime.
- **Available Runtimes:** `io.containerd.runc.v2`, `runc`
- **containerd version:** `05044ec0a9a75232cad458027ca83437aae3f4da`
- **runc version:** `v1.2.5-0-g59923ef`
- **init version:** `de40ad0`

---

### 🐳 Init Binary
- **docker-init** – Ensures proper signal handling in containers.

---

### 📂 Docker Root Directory
- **/var/lib/docker** – Stores container layers, volumes, images, etc.

---

### 🖥️ System Information
- **Kernel Version:** `6.14.0-24-generic`
- **OS:** `Ubuntu 24.04.2 LTS`
- **OSType:** `linux`
- **Architecture:** `x86_64`
- **CPUs:** 4
- **Memory:** 7.5 GiB
- **Hostname:** `mohamed-VMware-Virtual-Platform`

---

### 🕸️ Swarm
- **Status:** Inactive – Swarm mode is not initialized.

---

### 🔧 Live Restore
- **Enabled:** false – If true, containers stay running when daemon is restarted (currently off).

---
