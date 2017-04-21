class: center, middle, inverse

# What _is_&nbsp; a Container?

---

# What is a Container **not**?

---

# What is a Container **not**?

- Containers are not VMs.

- Although both depend on **resource virtualization** on top of an underlying system in order to provide abstractions of virtual resources.

- TL;DR: containers allow us to think in terms of processes/tasks/jobs rather than physical or virtual machines.

---

# What is a Container **not**?

- Containers do not require the overhead of virtualizing at the **hardware** level, unlike whole-system VMs.

- As a result, they are generally smaller in size and quicker to spin up.

???

---

# What is a Container **not**?

- Ubuntu 16.10 VM: ~2.5 GB

- Ubuntu 16.10 Docker Image: ~110 MB

---

# What is a Container **not**?

- Ubuntu 16.10 VM time to boot: > 1min

- Ubuntu 16.10 Docker Image time to boot: < 1sec

---

# What **is** a Container?

- A Container is an OS-level virtualization.

- Each container has an isolated user space, and may be running a different Linux distro.

- In the case of Docker, the Docker Engine provides the bridge between containers and the host OS kernel.

---

class: center, middle

![](https://cl.ly/0i1P002F3m0e/VMs.png)

---

class: center, middle

![](https://cl.ly/0A3U3f261G2j/Containers.png)

---

class: center, middle

![](https://cl.ly/2V0k272N3i1a/containers-vs-VM.png)

---
