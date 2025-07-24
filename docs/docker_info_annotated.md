#  Docker Daemon Info - Annotated

##  Server Section (Docker Daemon)


## Containers
- • **Running:** 3 – Currently active containers.
- • **Stopped:** 10 – Containers that were previously active but are now stopped.
- • **Paused:** 0 – No containers are paused at the moment.

---

## Images
- • **6 images** are stored locally. These are used to create and run containers.

---

## Docker Engine
- • **Version:** 28.3.2 – The current version of the Docker Engine running on your system.

---

## Storage Driver
- • **Driver:** `overlay2` – A layered filesystem used to manage container and image data.
- • **Backing Filesystem:** `extfs` – Likely ext4.
- • **Supports d_type:** true – Ensures proper functioning of the overlay driver.
- • **Metacopy:** false – Metadata-only copying is not used.
- • **Native Overlay Diff:** true – Enables efficient image layering.
- • **userxattr:** false – Extended file attributes are not in use.

---

## Logging
- • **Driver:** `json-file` – Logs for each container are stored in JSON format.

---

## Available Plugins
- • **Volume Drivers:** `local`  
- • **Network Drivers:** `bridge`, `host`, `ipvlan`, `macvlan`, `null`, `overlay`  
- • **Log Drivers:** `awslogs`, `fluentd`, `gcplogs`, `gelf`, `journald`, `json-file`, `local`, `splunk`, `syslog`

---

## Security Settings
- • **AppArmor:** Enabled – Provides container-level access control.
- • **Seccomp:** Enabled (Profile: builtin) – Restricts dangerous syscalls.
- • **cgroupns:** Enabled – Ensures containers have isolated resource control namespaces.

---

## Cgroup Driver
- • **Driver:** `systemd` – Manages cgroups using the systemd process manager.
- • **Version:** Cgroup v2 – Uses the newer and more organized hierarchy.

---

## Runtimes
- • **Default Runtime:** `runc` – The standard runtime for Docker containers.
- • **Available Runtimes:** `runc`, `io.containerd.runc.v2`
- • **containerd version:** `05044ec0a9a75232cad458027ca83437aae3f4da`
- • **runc version:** `v1.2.5-0-g59923ef`
- • **init version:** `de40ad0` – Ensures containers handle system signals properly.

---

## Docker Files Location
- • **Root Directory:** `/var/lib/docker` – Where Docker stores images, containers, and volumes.

---

## System Info
- • **Kernel Version:** `6.14.0-24-generic`
- • **Operating System:** Ubuntu 24.04.2 LTS
- • **Architecture:** x86_64
- • **CPU Cores:** 4
- • **Memory:** 7.5 GiB
- • **Hostname:** mohamed-VMware-Virtual-Platform

---

## Swarm Mode
- • **Status:** Inactive – Docker Swarm is not currently enabled.

---

## Live Restore
- • **Enabled:** false – If the daemon restarts, containers will also stop.

---
