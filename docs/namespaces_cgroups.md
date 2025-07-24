# Namespaces & cgroups Overview

Linux namespaces and control groups (cgroups) are the foundation of containerization technologies like Docker and Kubernetes. Together, they isolate and limit system resources, making it possible to run containers as if they were independent systems.

## 🔹 Linux Namespaces

Namespaces isolate system resources so that each container or process only sees its own environment. There are **six major Linux namespaces**:

1. **PID (Process ID)**: Isolates process trees. A process inside a namespace sees only its own and child processes.
2. **NET (Network)**: Provides separate network interfaces, IP addresses, routing tables, etc.
3. **MNT (Mount)**: Isolates filesystem mount points. Containers can have their own root filesystems.
4. **UTS (UNIX Timesharing System)**: Allows containers to have their own hostname and domain name.
5. **IPC (Inter-Process Communication)**: Separates shared memory, semaphores, and message queues.
6. **USER**: Provides user and group ID mappings, allowing containers to run as "root" internally while being non-root on the host.

Each namespace gives a container the illusion of having its own independent system environment.

## 🔸 cgroups v2 (Control Groups)

**Control Groups v2** manage and limit resource usage (CPU, memory, I/O, etc.) by grouping processes. Unlike v1, cgroups v2 uses a **unified hierarchy** and provides more consistent and fine-grained control.

Key features of cgroups v2:

- **Hierarchical resource limits**: Nested cgroups inherit restrictions.
- **Single controller hierarchy**: Avoids conflicts of split subsystems in v1.
- **Improved memory and CPU controllers**: Better accounting and isolation.
- **Delegation support**: Non-root users can manage their own cgroups securely.

Together, namespaces provide **isolation**, and cgroups provide **resource control**, enabling secure and efficient multi-tenant container environments on a single Linux host.
