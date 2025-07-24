
# Docker Daemon Overview


---

## Client

- • **Edition:** Docker Engine - Community  
- • **Version:** 28.3.2  
- • **Context:** default  
- • **Debug Mode:** false  

### Installed CLI Plugins
- • **Buildx:** v0.25.0  
  ‣ Path: `/usr/libexec/docker/cli-plugins/docker-buildx`
- • **Compose:** v2.38.2  
  ‣ Path: `/usr/libexec/docker/cli-plugins/docker-compose`

---

## Server

### Containers
- • **Total:** 16  
  ‣ **Running:** 3  
  ‣ **Stopped:** 13  
  ‣ **Paused:** 0  

### Images
- • **Stored locally:** 6

### Docker Engine
- • **Version:** 28.3.2

---

## Storage

- • **Driver:** `overlay2`  
- • **Backing Filesystem:** `extfs` (likely ext4)  
- • **Supports d_type:** true  
- • **Using metacopy:** false  
- • **Native Overlay Diff:** true  
- • **userxattr:** false  

---

## Logging

- • **Logging Driver:** `json-file`

---

## Cgroups

- • **Driver:** `systemd`  
- • **Version:** Cgroup v2  

---

## Plugins

- • **Volume Driver:** `local`  
- • **Network Drivers:** `bridge`, `host`, `ipvlan`, `macvlan`, `null`, `overlay`  
- • **Log Drivers:** `awslogs`, `fluentd`, `gcplogs`, `gelf`, `journald`, `json-file`, `local`, `splunk`, `syslog`  

---

## CDI Spec Directories

- • `/etc/cdi`  
- • `/var/run/cdi`  

---

## Swarm Mode

- • **Status:** Inactive

---

## Runtimes

- • **Available Runtimes:** `io.containerd.runc.v2`, `runc`  
- • **Default Runtime:** `runc`  
- • **containerd Version:** `05044ec0a9a75232cad458027ca83437aae3f4da`  
- • **runc Version:** `v1.2.5-0-g59923ef`  
- • **init Version:** `de40ad0`  
- • **Init Binary:** `docker-init`  

---

## Security Options

- • **AppArmor:** Enabled  
- • **Seccomp:** Enabled (Profile: builtin)  
- • **cgroupns:** Enabled  

---

## System Information

- • **Kernel Version:** `6.14.0-24-generic`  
- • **Operating System:** Ubuntu 24.04.2 LTS  
- • **OSType:** linux  
- • **Architecture:** x86_64  
- • **CPUs:** 4  
- • **Total Memory:** 7.5 GiB  
- • **Hostname:** `mohamed-VMware-Virtual-Platform`  
- • **Machine ID:** `c27a5ae1-58a1-4dbc-a489-e335fd48ee14`

---

## Docker Filesystem

- • **Docker Root Directory:** `/var/lib/docker`

---

## Other Settings

- • **Debug Mode:** false  
- • **Experimental Mode:** false  
- • **Insecure Registries:**  
  ‣ `::1/128`  
  ‣ `127.0.0.0/8`  
- • **Live Restore:** false  


---

## Raw Docker Info Output

Below is the unprocessed output of `docker info` as retrieved from the terminal:

```
Client: Docker Engine - Community
 Version:    28.3.2
 Context:    default
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.25.0
    Path:     /usr/libexec/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v2.38.2
    Path:     /usr/libexec/docker/cli-plugins/docker-compose

Server:
 Containers: 16
  Running: 3
  Paused: 0
  Stopped: 13
 Images: 6
 Server Version: 28.3.2
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Using metacopy: false
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: systemd
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 CDI spec directories:
  /etc/cdi
  /var/run/cdi
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 05044ec0a9a75232cad458027ca83437aae3f4da
 runc version: v1.2.5-0-g59923ef
 init version: de40ad0
 Security Options:
  apparmor
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.14.0-24-generic
 Operating System: Ubuntu 24.04.2 LTS
 OSType: linux
 Architecture: x86_64
 CPUs: 4
 Total Memory: 7.523GiB
 Name: mohamed-VMware-Virtual-Platform
 ID: c27a5ae1-58a1-4dbc-a489-e335fd48ee14
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 Experimental: false
 Insecure Registries:
  ::1/128
  127.0.0.0/8
 Live Restore Enabled: false
```
